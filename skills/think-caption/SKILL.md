---
name: think-caption
description: Phân tích insight người xem từ một input (bài viết, thông tin, ý tưởng thô, hoặc kịch bản có sẵn), rồi dựng thành một chuỗi caption/text-overlay chạy trên màn hình video — công thức rút ra từ việc phân tích các video "hook dài" dạng chữ hiện tuần tự (3 lớp: mở chạm định kiến có sẵn của người xem → khai triển có số liệu/lý lẽ cụ thể tạo vòng lặp đúng-sai → chốt bằng một câu quotable đứng độc lập được). Dùng được cho mọi lĩnh vực/kênh (tài chính, sức khỏe, kinh doanh, đời sống, skincare...), không giới hạn kênh cụ thể nào. Dùng bất cứ khi nào người dùng đưa một chủ đề, bài viết, thông tin, hoặc ý tưởng và muốn "viết caption", "làm text overlay", "viết chuỗi chữ chạy trên video", "viết phụ đề dạng bubble", hoặc nói kiểu "phân tích insight rồi viết caption cho cái này" — kể cả khi họ không dùng đúng các từ trên hay không nhắc tới "hook".
---

# Nghĩ caption dạng chuỗi text-overlay (think-caption)

Nhận một input — bài viết, thông tin, ý tưởng thô, hoặc kịch bản có sẵn — và trả ra một **chuỗi caption** (đoạn chữ hiện tuần tự trên màn hình video, không phải lời thoại nói ra miệng). Công thức này được rút ra từ việc phân tích lý do một số video có phần chữ mở đầu dài (nhiều đoạn nối tiếp nhau) vẫn giữ chân và kéo tương tác tốt, thay vì bị lướt qua như phần lớn video có chữ dài.

## Cơ chế đứng sau công thức — đọc trước khi viết, đừng chỉ điền mẫu

Ba việc khác nhau đang xảy ra, và mỗi bubble trong chuỗi caption chịu trách nhiệm cho một việc:

- **Hứng thú ngay từ câu đầu** không đến từ việc tạo tò mò từ số 0, mà từ việc **chạm vào một định kiến/nỗi sợ/niềm tin người xem đã có sẵn** trong đầu về chủ đề này. Người xem phản ứng ngay (đồng tình hoặc muốn phản bác) trước khi kịp quyết định có xem tiếp hay không.
- **Ở lại xem hết** đến từ việc câu mở tạo ra một phán đoán còn treo lơ lửng ("mình đoán đúng hay sai?") — não người không chịu được việc bỏ dở một câu hỏi đã mở ra. Số liệu/chi tiết cụ thể (con số, mốc thời gian, phép so sánh) càng khiến người xem chủ động tính nhẩm, càng giữ họ tập trung lâu hơn thời lượng thật của video.
- **Tương tác (comment/share/save)** đến từ việc câu chốt đủ ngắn gọn để tách rời khỏi video, đứng một mình vẫn có nghĩa, đủ đáng nhớ để chụp màn hình hoặc gửi cho người khác — và từ việc câu mở đủ "có phe" để mời người xem vào bình luận tranh luận thay vì chỉ gật đầu rồi lướt.

Nếu một chuỗi caption thiếu bất kỳ lớp nào trong ba lớp trên, nó vẫn có thể đọc được nhưng sẽ không đạt hiệu quả giữ chân/kéo tương tác như công thức này nhắm tới — vì vậy đừng bỏ qua bước phân tích insight ở dưới chỉ để nhanh có caption.

## Bước 1: Xác định input đang có là loại gì

- **Ý tưởng/chủ đề thô** (chỉ có một câu hoặc từ khóa, chưa có tình huống/nhân vật/số liệu cụ thể nào) → cần tự nghĩ ra một tình huống cụ thể làm chất liệu (ví dụ một nhân vật phiếm chỉ như "bạn t", một câu hỏi lưỡng phân, một con số giả định hợp lý) trước khi viết caption. Nói rõ trong phần trình bày rằng tình huống là ví dụ minh hoạ tự nghĩ ra, không phải sự kiện có thật, để người dùng biết cần thay bằng chất liệu thật của họ nếu có.
- **Bài viết/thông tin/kịch bản có sẵn** (đã có nội dung, số liệu, lập luận cụ thể) → khai thác trực tiếp chất liệu đã có, không bịa thêm tình huống mới. Nhiệm vụ ở đây là *cấu trúc lại* thông tin sẵn có theo công thức 3 lớp, không phải sáng tác nội dung mới.

Nếu input quá mỏng để nhận ra insight nào (ví dụ chỉ có một từ khóa trơ trọi, không đủ ngữ cảnh để đoán người xem là ai) và người dùng không nói rõ thêm, hỏi lại ngắn gọn thay vì đoán mò rồi viết caption lạc đề.

## Bước 2: Phân tích insight người xem trước khi viết bất kỳ câu caption nào

Xác định bốn điều sau, và trình bày ngắn gọn phần này trước khi đưa caption — để người dùng có thể chỉnh lại insight nếu đọc sai, thay vì phải sửa từng câu caption sau đó:

1. **Người xem mục tiêu của nội dung này là ai** (nếu người dùng không nói rõ, suy luận hợp lý từ chủ đề/input).
2. **Định kiến, nỗi sợ, hoặc niềm tin có sẵn** mà nhóm người xem đó đã mang theo về chủ đề này — đây là thứ câu mở cần chạm vào, không phải thứ cần giải thích lại từ đầu. Càng là chủ đề có "phe" trong xã hội (tiền bạc, sức khỏe, sự nghiệp, quan hệ...) càng dễ tìm định kiến rõ để khai thác; với chủ đề trung tính/mới lạ, tìm góc bất ngờ/phản trực giác thay thế (xem ghi chú cuối file).
3. **Số liệu, chi tiết, hoặc phép so sánh cụ thể** có trong input (hoặc cần thêm nếu là ý tưởng thô) để dùng làm phần khai triển — chỗ này là "thịt" giữ độ tin cậy, không thể chỉ toàn cảm thán.
4. **Bài học/thông điệp cốt lõi** đủ ngắn để trở thành câu chốt độc lập.

## Bước 3: Dựng chuỗi caption theo 3 lớp

Số lượng bubble linh hoạt tuỳ độ phức tạp của input (có thể chia phần khai triển thành 2 bubble nếu lý lẽ dài), nhưng luôn giữ đủ ba vai trò:

- **Bubble mở** — chạm định kiến đã xác định ở bước 2, bằng một chi tiết cụ thể (số liệu, câu hỏi lưỡng phân, tình huống có nhân vật, hoặc một tuyên bố có vẻ ngược đời). Mục tiêu: người xem phải hình thành ngay một phán đoán trong đầu ("chắc đúng vậy", "vô lý", "mình cũng vậy").
- **Bubble khai triển** (1-2 đoạn) — dùng lý lẽ/số liệu cụ thể để xác nhận hoặc lật lại phán đoán ở bubble mở. Đây là phần chứa thông tin thật từ input, không rút gọn thành khẩu hiệu chung chung.
- **Bubble chốt** — một câu hoặc đoạn ngắn diễn đạt insight cốt lõi, đứng được độc lập. Tự kiểm tra bằng cách hình dung câu này bị cắt khỏi video, dán riêng ra — nếu người đọc vẫn hiểu và thấy đáng nhớ/đáng lưu lại, câu chốt đạt; nếu cần xem cả video mới hiểu, viết lại cho gọn và độc lập hơn.

## Định dạng khi trình bày kết quả

Trả lời trực tiếp trong hội thoại (chỉ ghi ra file khi người dùng yêu cầu lưu lại), theo thứ tự:

1. Phần phân tích insight (4 điều ở bước 2), trình bày ngắn gọn.
2. Chuỗi caption — chỉ đưa đúng phần chữ sẽ hiện lên màn hình, xuống dòng (cách nhau một dòng trống) mỗi khi chữ đổi sang đoạn mới, không đánh số, không ghi chú vai trò (mở/khai triển/chốt) kèm theo. Ba vai trò ở bước 3 là cách nghĩ khi *dựng* caption, không phải nhãn cần hiển thị ra kết quả cuối. Ví dụ:

   ```
   ...

   ...

   ...
   ```

## Ghi chú / giới hạn

- Skill này chỉ viết **phần chữ hiện trên màn hình** (text-overlay/caption). Không viết lời thoại nói ra miệng, không gợi ý hình ảnh/b-roll, không dựng outline nội dung đầy đủ — nếu người dùng cần cả kịch bản, đó là việc của một skill khác.
- Không tự kiểm duyệt theo ràng buộc riêng của một kênh cụ thể (chính sách nền tảng, định vị thương hiệu, vùng nội dung được/không được nói). Nếu kênh của người dùng có ràng buộc riêng, họ tự đối chiếu lại caption sau khi nhận kết quả, hoặc nêu rõ ràng buộc đó trong yêu cầu để caption viết đúng ngay từ đầu.
- Công thức "chạm định kiến có sẵn" hoạt động tốt nhất với chủ đề mà người xem đã có sẵn lập trường hoặc tranh cãi xã hội. Với chủ đề hoàn toàn trung tính/mới lạ, không có định kiến nào để chạm vào — chuyển bubble mở sang hướng tình huống cụ thể bất ngờ hoặc phép so sánh phản trực giác, thay vì cố tạo tranh cãi giả không có căn cứ.
