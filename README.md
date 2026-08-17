# cuong-vy-story

Plugin Claude Code đóng gói các skill nội bộ dùng cho kênh TikTok **Cường Vy Story** (@cuongvystory) và các dự án nội dung liên quan của Cường và Vy. Xem định hướng nội dung chi tiết ở [CLAUDE.md](./CLAUDE.md).

## Cài đặt

```
/plugin marketplace add diepvicuong/cuong-vy-story
/plugin install cuong-vy-story
```

Sau khi cài, các skill bên dưới sẽ gọi được trực tiếp qua `/<tên-skill>` trong Claude Code, trên bất kỳ máy nào — không cần copy tay file.

## Danh sách skill

| Skill | Dùng khi nào |
|---|---|
| [`make-idea`](./skills/make-idea/SKILL.md) | Cần ý tưởng video cho Cường Vy Story, ghép từ khóa theo phương pháp lưới 9 ô, gắn kèm trụ cột nội dung. |
| [`quadrant-idea`](./skills/quadrant-idea/SKILL.md) | Cần ý tưởng video cho Cường Vy Story theo hệ trục 4 hướng (độ sẵn sàng người xem × độ sâu chủ đề), ra 4 loại nội dung: Giải pháp / Cảm xúc / Gieo mầm / Viral. |
| [`to-content`](./skills/to-content/SKILL.md) | Đã có ý tưởng, cần dựng thành content đầy đủ (outline rồi kịch bản) cho Cường Vy Story, đi qua flow làm rõ → chọn framework → duyệt outline → viết đầy đủ. |
| [`to-hook`](./skills/to-hook/SKILL.md) | Đã có ý tưởng/kịch bản video, cần viết câu hook mở đầu (3-5 giây đầu) theo công thức 38 kế — dùng được cho mọi kênh. |

## Thêm skill mới

1. Tạo thư mục `skills/<ten-skill>/SKILL.md` (kèm `references/` nếu cần tài liệu phụ) theo đúng cấu trúc của các skill hiện có.
2. Thêm một dòng vào bảng "Danh sách skill" ở trên — không cần sửa gì khác trong file này.
3. Commit và push. Người đã cài plugin sẽ nhận skill mới ở lần cập nhật plugin tiếp theo.
