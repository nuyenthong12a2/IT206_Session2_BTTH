# KẾ HOẠCH VẬN HÀNH AGILE (AGILE OPERATING PLAN) DỰ ÁN GREENMART

## 1. Lý do chọn Agile cho dự án GreenMart
* **Hạn chế của Waterfall:** Dự án GreenMart thuộc chuỗi 30 siêu thị đang mở rộng sang bán hàng đa kênh (Omnichannel) — đây là mảng kinh doanh chịu ảnh hưởng lớn bởi xu hướng thị trường và thói quen mua sắm. Nếu làm theo Waterfall, việc chốt cứng toàn bộ yêu cầu từ đầu sẽ khiến đội dự án không thể phản hồi khi GreenMart đổi nghiệp vụ. Việc khách hàng chỉ nghiệm thu 1 lần ở cuối dự án dẫn đến rủi ro phát hiện sai lệch quá muộn, gây lãng phí chi phí và thời gian làm lại (rework).
* **Khắc phục bằng Agile:** Agile chia nhỏ quá trình phát triển thành các chu kỳ ngắn. Sau mỗi chu kỳ, đội đều tạo ra phần mềm sử dụng được để trình diễn cho GreenMart. Nhờ đó, các phản hồi được thu thập liên tục, các thay đổi ưu tiên được tiếp nhận ngay ở đầu mỗi Sprint tiếp theo mà không làm gián đoạn tiến độ chung.
* **Kết luận:** Dự án GreenMart nên áp dụng mô hình Agile/Scrum vì môi trường kinh doanh đa kênh có tính biến động cao, cần sự thích ứng nhanh và bàn giao giá trị liên tục cho khách hàng.

---

## 2. Nguyên tắc làm việc theo 4 giá trị Agile

| Thói quen hiện tại | Giá trị Agile bị đi ngược | Cách làm mới phù hợp |
| :--- | :--- | :--- |
| Cả đội chỉ trao đổi qua bình luận trên phần mềm, gần như không họp trực tiếp. | **Cá nhân và sự tương tác** hơn là quy trình và công cụ | Tổ chức họp đứng hàng ngày (Daily Scrum 15 phút) trực tiếp/online để tăng tương tác và giải quyết nghẽn mạch ngay lập tức. |
| Viết tài liệu đặc tả rất chi tiết trước, chỉ trình diễn sản phẩm 1 lần ở cuối. | **Phần mềm chạy tốt** hơn là tài liệu đầy đủ | Tập trung xây dựng các tính năng hoạt động được. Cuối mỗi Sprint (2 tuần), tổ chức Sprint Review để demo sản phẩm chạy thực tế cho GreenMart. |
| Hợp đồng tính phí và bắt chờ 2 tuần phê duyệt mỗi khi khách muốn đổi yêu cầu. | **Hợp tác với khách hàng** hơn là thương lượng hợp đồng | PO chủ động làm việc trực tiếp với GreenMart hằng tuần để lắng nghe nhu cầu, linh hoạt điều chỉnh Product Backlog thay vì thủ tục hành chính. |
| Khi thực tế khác với kế hoạch, đội vẫn làm đúng theo kế hoạch đã duyệt ban đầu. | **Phản hồi với sự thay đổi** hơn là đi theo một kế hoạch | Định kỳ xem xét và điều chỉnh kế hoạch ở mỗi buổi Sprint Planning dựa trên dữ liệu thực tế thu được từ thị trường và phản hồi của khách hàng. |

---

## 3. Thiết lập Khung Scrum (Scrum Framework)
* **Độ dài Sprint cố định:** **2 tuần** (Tổng cộng 3 Sprint cho 6 tuần đầu tiên).
* **Giải thích lựa chọn gắn với 3 trụ cột:**
  * **Minh bạch (Transparency):** Khung thời gian 2 tuần đủ ngắn để mọi tiến độ, mã nguồn và tính năng hoàn thành được hiển thị rõ ràng trên Scrum Board mà không bị tồn đọng công việc ẩn.
  * **Thanh tra (Inspection):** Cứ mỗi 2 tuần, GreenMart và đội dự án lại cùng thanh tra phần Increment thực tế chạy được, giúp phát hiện lỗi hoặc sai lệch nghiệp vụ ngay lập tức.
  * **Thích nghi (Adaptation):** Kết thúc 2 tuần, dựa trên kết quả thanh tra, PO có thể thay đổi thứ tự ưu tiên hoặc yêu cầu cho Sprint tiếp theo một cách linh hoạt.
* **Lý do chọn Scrum thay vì Waterfall:** Scrum giúp giảm thiểu rủi ro xây sai sản phẩm, tăng tính linh hoạt trước các chiến dịch kinh doanh của GreenMart và mang lại giá trị kinh doanh thực sự cho siêu thị sau mỗi 2 tuần.

---

## 4. Phân vai trong Scrum Team

| Thành viên | Vai trò Scrum | Quyền quyết định | Không có quyền quyết định |
| :--- | :--- | :--- | :--- |
| **Long** | **Product Owner (PO)** | Quyết định danh sách, nội dung và thứ tự ưu tiên các hạng mục trong Product Backlog; quyết định tiêu chí chấp nhận (Acceptance Criteria) và nghiệm thu Increment. | Không quyết định phân công công việc chi tiết cho Dev Team, không can thiệp vào giải pháp kỹ thuật hoặc cách thức Dev Lập trình. |
| **Hoa** | **Scrum Master (SM)** | Quyết định việc tổ chức và khai vấn các sự kiện Scrum; loại bỏ các rào cản (impediments) cản trở đội; bảo vệ đội khỏi các can thiệp bên ngoài trong Sprint. | Không có quyền gán task, không quyết định ưu tiên tính năng kinh doanh, không có quyền sa thải hay quản lý hành chính thành viên. |
| **An, Bình, Chi, Dung** | **Development Team (Dev Team)** | Tự tổ chức (Self-organizing) quyết định phương án kỹ thuật, cách phân chia Task và ước lượng khối lượng công việc (Story Points) trong Sprint Backlog. | Không tự ý đổi ưu tiên kinh doanh của Product Backlog, không tự ý thay đổi Sprint Goal nếu chưa có sự thống nhất với PO. |

---

## 5. Artifacts & Lịch sự kiện trong 6 tuần đầu

### 5.1. Product Backlog (Đã sắp xếp ưu tiên)
1. **PB-01:** Tìm kiếm sản phẩm theo tên và danh mục siêu thị.
2. **PB-02:** Xem chi tiết sản phẩm và số lượng tồn kho theo cửa hàng.
3. **PB-03:** Thêm sản phẩm vào giỏ hàng trực tuyến.
4. **PB-04:** Xử lý thanh toán đơn hàng qua Ví điện tử / Thẻ ATM.
5. **PB-05:** Quản lý địa chỉ giao hàng và tính phí vận chuyển.
6. **PB-06:** Tra cứu lịch sử đơn hàng của khách hàng.

### 5.2. Kế hoạch Sprint 1 (Tuần 1 - Tuần 2)
* **Mục tiêu Sprint 1 (Sprint Goal):** *"Cho phép người dùng tìm kiếm sản phẩm và thêm được sản phẩm vào giỏ hàng trực tuyến thành công."*
* **Sprint Backlog 1:** Bao gồm 3 hạng mục **PB-01, PB-02, PB-03** (Phân rã thành các task kỹ thuật cụ thể cho An, Bình, Chi, Dung).
* **Increment mong đợi cuối Sprint 1:** Một mô-đun web/app chạy thực tế cho phép tìm kiếm danh mục hàng hóa GreenMart, xem chi tiết mặt hàng và thao tác thêm vào giỏ hàng thành công với dữ liệu thật.

### 5.3. Lịch 5 sự kiện Scrum trong một Sprint (2 tuần)

[Ngày 1] ───────────────► [Hằng ngày] ───────────────► [Ngày 14] ───────────────► [Ngày 14]
Sprint Planning           Daily Scrum                 Sprint Review               Sprint Retrospective
(4 giờ)                   (15 phút/ngày)              (2 giờ)                     (1.5 giờ)

1. **Sprint Planning (Lập kế hoạch Sprint):**
   * *Thời điểm:* Sáng Ngày 1 của Sprint (Thời lượng: 4 giờ).
   * *Mục đích:* Xác định Mục tiêu Sprint (Sprint Goal) và chọn các hạng mục từ Product Backlog đưa vào Sprint Backlog.
2. **Daily Scrum (Họp đứng hàng ngày):**
   * *Thời điểm:* 9:00 AM mỗi sáng (Thời lượng: 15 phút).
   * *Mục đích:* Đội Dev đồng bộ công việc, kiểm tra tiến độ hướng tới Sprint Goal và phát hiện các rào cản.
3. **Sprint Execution (Thực thi Sprint):**
   * *Thời điểm:* Diễn ra xuyên suốt trong 2 tuần.
   * *Mục đích:* Đội thực hiện công việc lập trình, kiểm thử để chuyển hóa Sprint Backlog thành Increment.
4. **Sprint Review (Đánh giá Sprint):**
   * *Thời điểm:* Chiều Ngày 14 của Sprint (Thời lượng: 2 giờ).
   * *Mục đích:* Đội trình diễn phần sản phẩm tăng trưởng (Increment) cho GreenMart xem và thu nhận phản hồi.
5. **Sprint Retrospective (Cải tiến Sprint):**
   * *Thời điểm:* Cuối Ngày 14 (sau Sprint Review, Thời lượng: 1.5 giờ).
   * *Mục đích:* Nhìn lại cách làm việc, quy trình, mối quan hệ trong Sprint qua để tìm ra ít nhất 1 hành động cải tiến cho Sprint sau.

---

## 6. Xử lý tình huống thay đổi

### Tình huống 1: Giữa Sprint, khách GreenMart muốn đổi thứ tự ưu tiên — làm tính năng đặt hàng online trước

* **Cách tiếp nhận & xử lý:**
  1. **Bảo vệ Sprint đang chạy:** Scrum Master và PO trao đổi với đại diện GreenMart để giải thích nguyên tắc khung thời gian cố định: Sprint Backlog của Sprint hiện tại không bị can thiệp làm gián đoạn trừ khi Mục tiêu Sprint không còn ý nghĩa.
  2. **Tiếp nhận vào Product Backlog:** PO tiếp nhận yêu cầu "đặt hàng online", tiến hành phân tích, làm mịn và đưa hạng mục này lên vị trí ưu tiên cao nhất trong **Product Backlog**.
  3. **Đưa vào Sprint tiếp theo:** Tại buổi Sprint Planning của Sprint ngay sau đó (Sprint 2), PO sẽ đưa tính năng đặt hàng online này vào để Đội triển khai ngay lập tức.

### Tình huống 2: Đến buổi Sprint Review, một tính năng vẫn chưa hoàn thành (Chưa đạt DoD)

* **Cách xử lý khi trình diễn cho khách GreenMart:**
  1. **Cởi mở & Minh bạch:** Tại buổi Sprint Review, PO và Đội tuyên bố rõ ràng tính năng đó chưa đạt chuẩn Definition of Done (DoD).
  2. **Không Demo hàng chưa xong:** Tuyệt đối không trình diễn tính năng dở dang hoặc dùng mã giả/dữ liệu giả để che giấu khách hàng. Chỉ demo những tính năng đã hoàn toàn "xong".
  3. **Cập nhật Backlog:** Chuyển tính năng chưa xong đó quay trở lại Product Backlog. PO làm việc với GreenMart để quyết định xem có tiếp tục ưu tiên làm tiếp trong Sprint sau hay không.
  4. **Rút kinh nghiệm:** Đưa vấn đề này vào buổi Sprint Retrospective ngay sau đó để phân tích nguyên nhân (ví dụ: do nghẽn kiểm thử, hay task quá lớn) nhằm cải tiến khả năng ước lượng công việc của đội.