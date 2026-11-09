9# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm:
- Candidate problem nhóm chọn (1 câu):
- Quyết định cuối (Go / Not Yet / No-Go):

## Thành viên

| STT | Họ và tên                 | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
| --: | ---------                 | ---- | ------------------ | ---------------- |
|   1 |                           |      |                    |                  |
|   2 |Nguyễn Tuấn Dũng           |2A202603859     |Thành viên                    |DungNguyen74                  |
|   3 |                           |      |                    |                  |
|   4 |                           |      |                    |                  |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint                                 | Người chính | Người hỗ trợ | Sản phẩm                                       |
| ------------------------------------------ | ----------- | ------------ | ---------------------------------------------- |
| CP3 — Hội tụ nhóm                          |  Nguyễn Tuấn Dũng           |              | Cluster, cây OST, bảng chấm điểm               |
| CP4 — Kiểm chứng                           |             |              | Assumption map, snapshot hoặc survey           |
| CP4 — Research                             |             |              | Bảng research có link                          |
| CP5 — Quy trình trước/sau                  |             |              | Quy trình + bảng before/after                  |
| CP5 — Problem Statement v0                 |             |              | Problem Statement v0                           |
| CP6 — Mức can thiệp + Problem Statement v1 |             |              | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định                           |             |              | 4 rủi ro + Go/Not Yet/No-Go                    |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenLeDangKhoa-2A202603847

**Phần việc phụ trách:**

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- **Điều mình học được từ phần nhóm:**

-

### NguyenTuanDung-2A202603859

**Phần việc phụ trách:** Đề xuất bài toán trọng tâm (Domain Owner), Kiểm chứng người dùng thực tế (CP4) & Thiết kế Quy trình / Boundary / Quyết định Pilot (CP5–CP6)

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
  - **CP3 (Hội tụ nhóm):** Đóng góp và pitch 3 Problem Cards thuộc cụm nghiệp vụ đối chiếu chứng từ/văn bản dài (Candidate #1: Đối chiếu hồ sơ thanh toán 3-way matching, Candidate #2: Rà soát điều khoản hợp đồng đối tác, Candidate #3: Bóc tách so sánh báo giá nhà cung cấp). Trực tiếp phản biện Candidate #4 (về tần suất xảy ra 2 tuần/lần so với nghiệp vụ hàng ngày của kế toán) và Candidate #10 (về giải pháp No AI dùng tài liệu Swagger chuẩn). Cung cấp số liệu thực tế về áp lực xử lý 30–60 bộ hồ sơ/ngày và rủi ro xuất toán thuế để thuyết phục cả nhóm đồng thuận chọn Candidate #1 làm bài toán chính (35/35 điểm).
  - **CP4 (Kiểm chứng & Research):** Xây dựng Assumption Map (6 giả định cốt lõi) và trực tiếp thực hiện phỏng vấn sâu theo nguyên tắc The Mom Test với Kế toán thanh toán (AP Specialist) và Kế toán trưởng để đo baseline (18 phút/bộ hồ sơ, 10–12 phút đọc hợp đồng scan, 25% tỷ lệ trả hồ sơ) cũng như phát hiện tín hiệu phản bác ở nhóm doanh nghiệp siêu nhỏ (<10 nhân sự). Tham gia khảo sát 3 giải pháp có sẵn (Kofax AP Agility, AWS Textract, invoice2data) để xác định khoảng trống thị trường ở khâu đọc hiểu Hợp đồng dịch vụ PDF scan tiếng Việt.
  - **CP5–CP6 (Quy trình, Problem Statement & Quyết định):** Phác thảo sơ đồ Mermaid và bảng phân tích quy trình Trước/Sau (giảm từ 18 phút xuống ~2.5 phút/bộ), tách bạch rõ kiến trúc Hybrid: Rule (bóc tách XML hóa đơn chuẩn Tổng cục Thuế 100%) ➔ AI Workflow (OCR + LLM trích xuất điều khoản thanh toán kèm Citation số trang/điều khoản) ➔ Rule Matching (gắn cờ Xanh/Đỏ) ➔ Con người (Kế toán AP rà soát và bấm duyệt). Viết phần Boundary tuyệt đối, kịch bản Fallback (khi độ tin cậy OCR < 60%), 4 tiêu chí đánh giá (Eval), phân tích 4 rủi ro của Marty Cagan và thiết lập kế hoạch Pilot 2 tuần trên 50 bộ hồ sơ kèm 3 ngưỡng dừng (Stop Threshold).

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):
  - Trong `report/group_report.md`:
    - Mục 2.1 (Bảng Pitch Candidates #1, #2, #3 và các câu hỏi phản biện cho #4, #10), Mục 2.2 (Cluster A), Mục 2.3 (Cây OST) và Mục 2.4 (Chấm điểm shortlist & Xử lý bất đồng).
    - Mục 3.1 (Bảng Assumption Map), Mục 3.2 (Bảng Interview Snapshot Người #1 và tổng hợp tín hiệu kiểm chứng 5 phỏng vấn + 24 mẫu survey), Mục 3.3 (Bảng so sánh Kofax AP Agility, AWS Textract, invoice2data).
    - Mục 4.1, 4.2, 4.3 (Hai sơ đồ `flowchart TD` quy trình Hiện tại/Tương lai, khối Boundary/Fallback và bảng so sánh Before/After).
    - Mục 5, 6, 7, 8 (Problem Statement v0 & v1, bảng so sánh 4 mức can thiệp No AI/Rule/Workflow/Agent, AI Canvas, 2 câu hỏi Google PAIR, 4 tiêu chí Eval và Quyết định Go Pilot + Ngưỡng dừng).
  - Trong `report/assets/`:
    - File `report/assets/cp4-interview-snapshots.md` (Biên bản chi tiết 5 cuộc phỏng vấn sâu theo The Mom Test và kết quả micro-survey 24 người).
    - File `report/assets/cp6-eval-dataset.md` (Bộ 10 test cases định lượng kiểm thử độ chính xác trích xuất, phát hiện sai lệch Zero-miss và trích dẫn Citation).
  - Trong `report/individual/`:
    - File báo cáo cá nhân `report/individual/2A202603859_NguyenTuanDung.md` (commit trực tiếp bằng tài khoản GitHub cá nhân trên nhánh chính của repo nhóm `K5-L3B-DAY02-Nhom4Squares-DiscoveryProblemFraming`).

- **Điều mình học được từ phần nhóm:**
  - **Không để AI làm thay những việc Rule làm tốt hơn và an toàn hơn:** Qua quá trình tranh luận nhóm, mình học được cách bóc tách bài toán rất thực tế: Hóa đơn điện tử tại Việt Nam đã có sẵn file XML theo chuẩn Tổng cục Thuế nên dùng code Rule bóc tách đạt độ chính xác 100% và miễn phí; chỉ dùng AI Workflow vào đúng điểm nghẽn mà Rule bó tay là đọc hiểu văn bản Hợp đồng PDF scan phi cấu trúc.
  - **Niềm tin của người dùng nằm ở khả năng truy vết (Citation & Traceability):** Phản biện của bạn Nguyễn Hoàng Trung lúc pitch (*"Nếu kế toán vẫn phải tự mắt kiểm tra lại kết quả của AI vì sợ sai số tiền thì thời gian có thực sự giảm từ 18 phút xuống 5 phút được không?"*) và ý kiến của Kế toán trưởng lúc phỏng vấn giúp mình nhận ra: AI chỉ tóm tắt kết quả sẽ vô dụng vì không ai dám tin để ký duyệt tiền. Bắt buộc phải thiết kế cơ chế trích dẫn thẳng tới số trang và câu chữ gốc (Citation) để chuyển việc "đọc dò 30 trang (12 phút)" thành "nhìn bằng chứng xác nhận (1 phút)".
  - **Tầm quan trọng của tín hiệu phản bác khi đi kiểm chứng:** Nhờ phỏng vấn thực tế theo The Mom Test (như trường hợp Giám đốc công ty 5 nhân sự chuyển khoản thẳng trong 30 giây không cần đối chiếu), nhóm đã kịp thời thu hẹp chính xác chân dung Actor về các doanh nghiệp quy mô vừa và lớn (>100 nhân sự, >20 bộ hồ sơ/ngày) thay vì định nghĩa chung chung.
-

### Son

**Phần việc phụ trách:**

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- **Điều mình học được từ phần nhóm:**

-

### Trung

**Phần việc phụ trách:**

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- **Điều mình học được từ phần nhóm:**

-
