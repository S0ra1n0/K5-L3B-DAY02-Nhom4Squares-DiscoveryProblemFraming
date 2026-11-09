9# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm:
- Candidate problem nhóm chọn (1 câu):
- Quyết định cuối (Go / Not Yet / No-Go):

## Thành viên

| STT | Họ và tên          | MSSV        | Vai trò trong nhóm                                                 | Tài khoản GitHub |
| --: | ------------------ | ----------- | ------------------------------------------------------------------ | ---------------- |
|   1 |                    |             |                                                                    |                  |
|   2 | Nguyễn Tuấn Dũng   | 2A202603859 | Thành viên                                                         | DungNguyen74     |
|   3 |                    |             |                                                                    |                  |
|   4 |                    |             |                                                                    |                  |
| STT | Họ và tên          | MSSV        | Vai trò trong nhóm                                                 | Tài khoản GitHub |
| --: | ---------          | ----        | ------------------                                                 | ---------------- |
|   1 |                    |             |                                                                    |                  |
|   2 |                    |             |                                                                    |                  |
|   3 | Nguyễn Hoàng Trung | 2A202603826 | Người phản biện chính, Thiết kế quy trình & Viết Problem Statement | trungtk03        |
|   4 |                    |             |                                                                    |                  |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint                                 | Người chính        | Người hỗ trợ       | Sản phẩm                                       |
| ------------------------------------------ | ------------------ | ------------------ | ---------------------------------------------- |
| CP3 — Hội tụ nhóm                          | Nguyễn Tuấn Dũng   | Nguyễn Hoàng Trung | Cluster, cây OST, bảng chấm điểm               |
| CP4 — Kiểm chứng                           |                    |                    | Assumption map, snapshot hoặc survey           |
| CP4 — Research                             |                    |                    | Bảng research có link                          |
| CP5 — Quy trình trước/sau                  | Nguyễn Hoàng Trung |                    | Quy trình + bảng before/after                  |
| CP5 — Problem Statement v0                 | Nguyễn Hoàng Trung |                    | Problem Statement v0                           |
| CP6 — Mức can thiệp + Problem Statement v1 |                    | Nguyễn Hoàng Trung | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định                           |                    |                    | 4 rủi ro + Go/Not Yet/No-Go                    |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenLeDangKhoa-2A202603847

**Phần việc phụ trách:**

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- **Điều mình học được từ phần nhóm:**

-

### Dung

**Phần việc phụ trách:** Đề xuất & Phản biện Problem Cards (CP3), Thực hiện chấm điểm Shortlist & Xử lý bất đồng chọn bài toán nhóm (Mục 2.4)

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
  - **Đóng góp Problem Card & Thảo luận hội tụ (CP3):** Chuẩn bị và pitch bài toán cá nhân **#7 — Đối chiếu ngữ cảnh ticket từ nhiều nguồn (Jira, Confluence, Slack, Log)** tại công ty thực tập, đồng thời tham gia phản biện chéo các bài toán của thành viên khác để gom nhóm (cluster) theo đúng bản chất "tổng hợp và đối chiếu thông tin yêu cầu bị phân mảnh".
  - **Phụ trách hoàn thiện Mục 2.4 — Chấm điểm shortlist (1–5) và chốt Candidate Problem:** Trực tiếp lập bảng chấm điểm định lượng trên 7 tiêu chí cho 3 ứng viên đại diện (Candidate A: Gom thông tin bài tập từ nhiều kênh — 34/35 điểm; #7: Đối chiếu ngữ cảnh ticket từ nhiều nguồn — 27/35 điểm; #10: Release notes từ Pull Request — 24/35 điểm).
  - **Viết lập luận lựa chọn, loại trừ và ghi nhận xử lý bất đồng:** Phân tích rõ lý do chọn **Candidate A (#2 + #4)** (cả 4 thành viên đều là actor trực tiếp, đo được baseline ngay trên Discord/LMS/Phoenix, dễ phỏng vấn bạn cùng lớp và tách bạch rõ Rule lọc kênh/từ khóa với AI Workflow đọc hiểu tin nhắn đính chính deadline). Giải trình rõ lý do loại #7 (vướng bảo mật dữ liệu Jira/Slack nội bộ công ty thực tập) và #10 (tần suất thấp 2 tuần/lần, giải quyết được bằng Rule commit + GitHub). Ghi nhận quá trình xử lý bất đồng từ góc nhìn của chính mình (chuyển bài #7 sang hướng mở rộng tiếp theo để ưu tiên bài toán Candidate A có dữ liệu thật cho cả nhóm kiểm chứng ngay trong giờ lab).

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):
  - **Trong `report/group_report.md`:**
    - Mục `2.4. Chấm điểm shortlist (1–5)`: Bảng ma trận chấm điểm 3 candidates (`A`, `#10`, `#7`), phần kết luận Candidate được chọn, lý do chọn/loại và mục Xử lý bất đồng.
    - Mục `2.1. Pitch`: Hàng thông tin pitch và phản biện của Candidate `#7 — Đối chiếu ngữ cảnh ticket từ nhiều nguồn`.
  - **Trong `report/individual/`:**
    - File báo cáo cá nhân `report/individual/2A202603859_NguyenTuanDung.md` (đầy đủ CP1 Scan 8 problems, CP2 Top 3 Problem Cards, CP3–CP7 đóng góp và Reflection).
  - **Commit:**
    - Commit `7d6fadc` — `"Update 2.4 group_report.md"` được thực hiện bởi tài khoản GitHub cá nhân `DungNguyen74` (Verified).

- **Điều mình học được từ phần nhóm:**
  - **Biết đặt tính khả thi kiểm chứng (Feasibility & Data Access) lên trên sở thích cá nhân:** Ban đầu mình rất muốn bảo vệ bài toán #7 (Đối chiếu ngữ cảnh ticket trên Jira/Slack ở công ty thực tập) vì thấy nó sát với môi trường doanh nghiệp. Tuy nhiên, khi cùng nhóm chấm điểm shortlist ở mục 2.4, mình nhận ra một rào cản thực tế là các bạn khác trong nhóm không có quyền truy cập vào Jira/Slack nội bộ công ty mình để lấy dữ liệu thật và đo baseline trong buổi lab.
  - **Nhận diện pattern chung của bài toán:** Qua thảo luận nhóm, mình hiểu ra rằng dù bối cảnh khác nhau (sinh viên gom thông tin bài tập trên Discord/LMS/Phoenix ở bài A so với thực tập sinh gom ngữ cảnh ticket trên Jira/Confluence/Slack ở bài #7), bản chất cốt lõi của cả hai đều là **đối chiếu thông tin phi cấu trúc bị phân mảnh và phát hiện các thay đổi/đính chính phát sinh qua tin nhắn chat**. Nhờ đó, những góc nhìn về trích dẫn nguồn (Citation) và tách bạch Rule/Workflow từ bài cá nhân của mình vẫn đóng góp trực tiếp vào bài toán chung của nhóm.
-

### Son

**Phần việc phụ trách:**

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- **Điều mình học được từ phần nhóm:**

-

### NguyenHoangTrung-2A202603826

**Phần việc phụ trách:**

- Pitch Problem Card #1 (Soạn Technical Release Notes từ danh sách Pull Requests) và tham gia thảo luận hội tụ nhóm (CP3).
- Đảm nhận vai trò Người phản biện chính (Devil's Advocate): Đặt câu hỏi phản biện sâu sắc về tính khả thi, thói quen người dùng và rủi ro tạo thêm "app thứ 6" cho các bài toán khác (CP3).
- Cùng nhóm phân loại 12 candidate thành các cụm (Cluster) và trực tiếp xây dựng cây Opportunity Solution Tree (OST) để tách bạch nhu cầu (Opportunity) và giải pháp (CP3).
- Phụ trách thiết kế và vẽ sơ đồ quy trình hiện tại (As-Is) và quy trình tương lai (To-Be) bằng Mermaid (CP5).
- Đồng tác giả soạn thảo Problem Statement v0 và nâng cấp lên Problem Statement v1, xác lập ranh giới an toàn (Boundary) và cơ chế Human-in-the-loop (CP5, CP6).
- Phân tích và bảo vệ phương án chọn mức can thiệp Workflow kết hợp Rule, kiên quyết từ chối Agent tự hành vì rủi ro an toàn hệ thống (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch Problem Card #1 với dữ liệu baseline đo lường thực tế (bấm giờ 100–115 phút/đợt release) được nhóm đánh giá cao và đưa vào Shortlist của nhóm.
- Đặt câu hỏi phản biện then chốt cho Nguyễn Tuấn Dũng về nguy cơ tạo ra "app thứ 6" khiến người dùng lười áp dụng, giúp nhóm nhận diện rủi ro Usability để điều chỉnh hướng tiếp cận.
- Trực tiếp vẽ sơ đồ Mermaid trực quan cho quy trình hiện tại (As-Is) và quy trình tương lai (To-Be) trong `group_report.md`.
- Soạn thảo nội dung mục 5 (Problem Statement v0) và mục 7 (Problem Statement v1), đặc biệt là 3 ranh giới Boundary cứng: AI không được tự ý hành động nếu chưa có con người duyệt chốt chặn.
- Hoàn thành đầy đủ báo cáo cá nhân `report/individual/2A202603826_NguyenHoangTrung.md` gồm 10 problem scan (đủ 4 lăng kính, đạt bonus B1), 3 Problem Card chi tiết và bài reflection sâu sắc.

### NguyenTuanDung-2A202603859

**Phần việc phụ trách:**

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- **Điều mình học được từ phần nhóm:**

- `report/team/group_report.md`: Bảng 2.1 (Pitch candidate #10), Mục 2.2 & 2.3 (Cluster & Cây OST), Mục 4.1 & 4.2 (Sơ đồ quy trình Mermaid As-Is và To-Be), Mục 5 (Problem Statement v0) và Mục 7 (Problem Statement v1).
- `report/individual/2A202603826_NguyenHoangTrung.md`: Toàn bộ báo cáo cá nhân của Nguyễn Hoàng Trung.
- Các commit trên repo: `0c12ce6`, `d02f50e`, `18544e5`, `5a34a37`, `d40b1a7`.

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

- Nhận thức rõ ràng về sự nguy hiểm của cái bẫy "yêu giải pháp của mình" (solution-first). Ban đầu tôi rất muốn nhóm chọn bài toán kỹ thuật Release Notes của mình, nhưng qua phản biện nhóm, tôi học được cách nhìn nhận khách quan dựa trên tần suất gặp phải và tính cấp thiết đối với người dùng.
- Hiểu sâu sắc sự khác biệt giữa Workflow và Agent: không phải bài toán nào dùng Agent cũng là tốt, mà phải luôn bắt đầu từ mức can thiệp đơn giản nhất đủ dùng; đối với các quy trình có rủi ro cao, sự kiểm soát của con người (Human-in-the-loop) và ranh giới Boundary chặt chẽ là yếu tố sống còn.
