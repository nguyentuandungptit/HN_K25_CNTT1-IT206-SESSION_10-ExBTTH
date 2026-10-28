# BÀI THỰC HÀNH 1: Chuẩn bị Sprint Review cho ứng dụng cảnh báo lừa đảo RikkeiSafe

## 1. Bối cảnh tóm tắt
* **Dự án:** Ứng dụng cảnh báo lừa đảo RikkeiSafe.
* **Sprint Goal:** Người dùng kiểm tra được số điện thoại hoặc đường link, xem cảnh báo kèm lý do và gửi báo cáo.
* **Scrum Team:** 
  * Product Owner (PO): Ngọc Hương
  * Scrum Master (SM): Quang Minh
  * Developers: Thu An, Gia Bình, Mai Lan
* **Stakeholders:** Cô Mai (người dùng lớn tuổi), anh Phúc (nhân viên ngân hàng đối tác), chị Vy (người dùng thử).
* **Definition of Done (DoD):** (1) Đủ chức năng thống nhất; (2) Đã review chéo; (3) Đã kiểm thử trên máy tính và điện thoại; (4) Không còn lỗi nghiêm trọng; (5) Đã ghép vào bản chạy được.

---

## 2. Giải chi tiết các nhiệm vụ

### Nhiệm vụ 1 - Hoàn thành phiếu chuẩn bị Sprint Review

| Bước | Việc cụ thể cho buổi Review này |
| :--- | :--- |
| **1. Chốt mục tiêu và người tham gia** | Mục tiêu: xem người dùng có tự kiểm tra được số, link và hiểu cảnh báo không. Mời đủ 3 Stakeholders. |
| **2. Kiểm tra Increment** | • **PBI được trình diễn là Done:** PBI-01 (Kiểm tra số điện thoại), PBI-02 (Kiểm tra đường link), PBI-03 (Gửi báo cáo số hoặc link đáng ngờ).<br>• **PBI phải nói rõ là chưa Done, kèm điều kiện DoD chưa đạt:**<br>  - **PBI-04 (Lưu lịch sử kiểm tra):** Chưa đạt điều kiện (1) – còn thiếu 2 chức năng đã thống nhất là xóa lịch sử và lọc theo loại.<br>  - **PBI-05 (Hướng dẫn khi người dùng đã lỡ chuyển tiền):** Chưa đạt điều kiện (2) và (3) – chưa được review chéo và mới kiểm thử trên máy tính (chưa kiểm thử trên điện thoại). |
| **3. Chọn User Journey và người demo** | • **User Journey:** Mở ứng dụng RikkeiSafe ➔ Nhập số điện thoại đáng ngờ để kiểm tra và xem cảnh báo kèm lý do (PBI-01) ➔ Dán đường link lạ để kiểm tra và xem cảnh báo kèm lý do (PBI-02) ➔ Bấm gửi báo cáo số điện thoại/đường link lừa đảo cho hệ thống (PBI-03).<br>• **Người demo:** **Developers** (Thu An, Gia Bình hoặc Mai Lan trực tiếp thao tác trình diễn bản chạy được). |
| **4. Chuẩn bị kỹ thuật** | Kiểm tra bản chạy được, tài khoản dùng thử, đường truyền họp trực tuyến. |
| **5. Chuẩn bị trao đổi** | **2 câu hỏi mở dành cho Stakeholders:**<br>1. *"Với giao diện hiển thị cảnh báo và lý do đi kèm như vừa trình diễn, các cô/anh/chị (đặc biệt là người lớn tuổi như cô Mai) thấy thông tin nào khó hiểu hoặc cần làm rõ hơn để người dùng yên tâm quyết định dừng chuyển tiền?"*<br>2. *"Từ góc độ người dùng thực tế và quy trình hỗ trợ tại ngân hàng, theo anh Phúc và chị Vy, luồng kiểm tra và gửi báo cáo hiện tại còn bước nào gây bất tiện hoặc thiếu thông tin quan trọng cần ưu tiên bổ sung ở các Sprint tới không?"* |
| **6. Chia thời gian** | Xem lịch trình ở Nhiệm vụ 2. |

---

### Nhiệm vụ 2 - Sửa lịch trình Sprint Review (35 phút)

| Thời gian | Hoạt động ban đầu | Nhận xét và cách sửa |
| :--- | :--- | :--- |
| **0–5'** | Product Owner nhắc Sprint Goal. | Phù hợp, giữ nguyên. |
| **5–20'** | Product Owner trình diễn cả 5 PBI, giới thiệu PBI-05 là đã hoàn thành. | • **Sai ở đâu:** (1) Sai vai trò: PO làm thay việc demo kỹ thuật của Developers; (2) Sai nguyên tắc minh bạch của Scrum: trình diễn cả PBI-04, PBI-05 chưa đạt DoD và báo cáo sai sự thật rằng PBI-05 đã hoàn thành.<br>• **Cách sửa:** **Product Owner (Ngọc Hương)** thông báo rõ PBI-01, 02, 03 đã Done và giải thích minh bạch lý do PBI-04, 05 chưa Done (không đưa vào demo). Sau đó, **Developers (Thu An, Gia Bình, Mai Lan)** trực tiếp trình diễn Increment (PBI-01, 02, 03) theo luồng User Journey. |
| **20–32'** | Từng Developer lần lượt báo cáo việc cá nhân mình đã làm. | • **Sai ở đâu:** Biến Sprint Review thành buổi báo cáo tiến độ cá nhân một chiều, làm mất thời gian tương tác với khách hàng (dành tận 12 phút chỉ để báo cáo nội bộ).<br>• **Cách sửa:** Bỏ phần báo cáo cá nhân. Dành trọn 12 phút này để **cả Scrum Team và Stakeholders (cô Mai, anh Phúc, chị Vy)** cùng thảo luận hai chiều, đặt câu hỏi mở, trải nghiệm thử tính năng và thu thập góp ý (Feedback) về sản phẩm. |
| **32–35'** | Stakeholders được nói trong 3 phút cuối; Scrum Master chốt góp ý nào sẽ làm ở Sprint sau. | • **Sai ở đâu:** (1) Thời gian 3 phút cho Stakeholders là quá ít (đã được khắc phục ở khung 20–32'); (2) Sai vai trò: Scrum Master không có quyền quyết định chọn việc cho Sprint sau, và cũng không được hứa làm ngay tại buổi Review.<br>• **Cách sửa:** **Scrum Master (Quang Minh)** chỉ giữ vai trò điều phối thời gian (timebox) và tóm tắt biên bản. **Product Owner (Ngọc Hương)** cảm ơn Stakeholders, tổng hợp các Feedback đưa vào Product Backlog, chia sẻ định hướng ưu tiên dự kiến và hẹn sẽ đánh giá kỹ để chọn hạng mục cụ thể trong buổi Sprint Planning tiếp theo. |

---

### Nhiệm vụ 3 - Ghi nhận Feedback

| Mã | Góp ý | Cách xử lý |
| :--- | :--- | :--- |
| **FB-01** | Anh Phúc: nên có nút hướng dẫn gọi ngân hàng khi người dùng báo đã chuyển tiền. | Ghi vào Product Backlog để Product Owner xem xét cùng PBI-05; chưa hứa làm ngay. |
| **FB-02** | Chị Vy: muốn thêm chức năng chia sẻ cảnh báo cho người thân. Việc này nằm ngoài Sprint Goal. | **Scrum Team** cảm ơn góp ý rất thực tế của chị Vy. **Product Owner (Ngọc Hương)** tạo một PBI mới trong Product Backlog cho tính năng "Chia sẻ cảnh báo", giải thích rõ rằng tính năng này nằm ngoài Sprint Goal hiện tại nên cần được đánh giá lại mức độ ưu tiên so với các hạng mục khác, **tuyệt đối không hứa sẽ làm ngay ở Sprint tới**. |
| **FB-03** | Cô Mai: dán đường link rất dài thì nút "Kiểm tra" bị đẩy ra ngoài màn hình điện thoại (PBI-02). | **Developers** và **Product Owner (Ngọc Hương)** ghi nhận ngay đây là lỗi hiển thị giao diện (UI bug) trên thiết bị di động của **PBI-02** (ảnh hưởng đến trải nghiệm người dùng thực tế dù đã qua bước kiểm thử DoD). **Product Owner** tạo thẻ Bug/cải tiến giao diện vào Product Backlog và đánh giá mức độ ưu tiên cao để **Scrum Team** đưa vào xử lý trong buổi Sprint Planning sắp tới, không tự ý cam kết sửa ngay lập tức trong buổi họp. |