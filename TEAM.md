# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: **Nhom4Squares**
- Candidate problem nhóm chọn (1 câu): **Đối chiếu hồ sơ thanh toán nhà cung cấp (3-way matching): Tự động hóa kiểm tra tính đầy đủ và đối chiếu chéo thông tin giữa Hợp đồng (PDF scan), Biên bản nghiệm thu và Hóa đơn điện tử (XML/PDF) cho Kế toán thanh toán (AP).**
- Quyết định cuối (Go / Not Yet / No-Go): **Go (pilot phạm vi nhỏ trong 2 tuần trên 50 bộ hồ sơ thanh toán)**

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Hoàng Trung | 2A202603826 | Nhóm trưởng, Điều phối thời gian, Thiết kế quy trình Mermaid & Soạn Problem Statement | trungtk03 |
| 2 | Nguyễn Tuấn Dũng | 2A202603859 | Người pitch chính bài toán 3-way matching, Phụ trách phỏng vấn kiểm chứng & Thu thập dữ liệu | DungNguyen74 |
| 3 | Lê Minh Quân | 2A202601124 | Phụ trách Assumption Map, Khảo sát người dùng (micro-survey 24 người) & Phản biện | quanlm-vinuni |
| 4 | Trần Thùy Linh | 2A202602358 | Phụ trách Research giải pháp thị trường, Thiết kế AI Canvas & Xây dựng bộ dữ liệu Eval 10 cases | linhthuytran |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nguyễn Hoàng Trung | Nguyễn Tuấn Dũng | Bảng 12 candidate pitch, bảng 3 cluster, cây OST, bảng chấm điểm shortlist |
| CP4 — Kiểm chứng | Nguyễn Tuấn Dũng | Lê Minh Quân | Bảng Assumption Map, 5 interview snapshots The Mom Test, khảo sát 24 người |
| CP4 — Research | Trần Thùy Linh | Nguyễn Hoàng Trung | Bảng research 3 công cụ (Kofax, AWS Textract, invoice2data) kèm link kiểm chứng |
| CP5 — Quy trình trước/sau | Nguyễn Hoàng Trung | Nguyễn Tuấn Dũng | Sơ đồ Mermaid quy trình As-Is và To-Be, bảng before/after, boundary & fallback |
| CP5 — Problem Statement v0 | Nguyễn Hoàng Trung | Lê Minh Quân | Problem Statement v0 đủ 6 trường, ghi nhận phản biện ban đầu |
| CP6 — Mức can thiệp + Problem Statement v1 | Trần Thùy Linh | Nguyễn Hoàng Trung | Ma trận độ mơ hồ, so sánh 4 mức, AI Canvas, PAIR, eval criteria, Problem Statement v1 |
| CP6 — Quyết định | Nguyễn Tuấn Dũng | Cả nhóm | Bảng đánh giá 4 rủi ro, kết luận Go pilot nhỏ, ngưỡng dừng đo lường được |

## Cá nhân

### NguyenHoangTrung-2A202603826

**Phần việc phụ trách:**

- Điều phối thảo luận nhóm, quản lý thời gian các checkpoint trong buổi lab.
- Trực tiếp pitch 3 candidate cá nhân (trong đó có bài toán Release Notes) và phản biện sắc bén bài toán của các bạn khác.
- Phụ trách xây dựng cây Opportunity Solution Tree (CP3) cùng nhóm.
- Thiết kế sơ đồ Mermaid trực quan cho Quy trình hiện tại (As-Is) và Quy trình tương lai (To-Be), bóc tách điểm nghẽn và thiết lập Boundary an toàn (CP5).
- Soạn thảo và chuẩn hóa Problem Statement v0 và v1 theo chuẩn Lean UX & Google PAIR (CP5, CP6).
- Hỗ trợ xây dựng bộ tiêu chí đánh giá Eval và 10 ca kiểm thử mẫu cho bước AI Workflow.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp câu hỏi phản biện then chốt ở CP3 giúp Dũng làm rõ cơ chế citation và bảng side-by-side table.
- Vẽ 2 sơ đồ quy trình Mermaid hoàn chỉnh trong mục 4 của `report/team/group_report.md`.
- Soạn thảo nội dung mục 5 (Problem Statement v0) và mục 7 (Problem Statement v1).
- Trực tiếp thực hiện phỏng vấn Interview Snapshot #2 (với Trưởng nhóm Kế toán thanh toán) và Interview Snapshot #5 (với Kế toán trưởng).
- Hoàn thành báo cáo cá nhân `2A202603826_NguyenHoangTrung.md` đầy đủ các mục từ CP1 đến CP7.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Mục 2.3 (Cây OST), Mục 4.1 & 4.2 (Sơ đồ quy trình Mermaid), Mục 5 (Problem Statement v0), Mục 7 (Problem Statement v1).
- `report/assets/cp4-interview-snapshots.md`: Phỏng vấn #2 và #5.
- `report/assets/cp6-eval-dataset.md`: Phối hợp cùng Linh xây dựng 10 cặp test cases.
- `report/individual/2A202603826_NguyenHoangTrung.md`: Báo cáo cá nhân.

**Điều mình học được từ phần nhóm:**

- Nhận ra giá trị to lớn của việc "bị phản biện và biết lắng nghe". Ban đầu tôi rất muốn nhóm làm đề tài của mình (Release Notes), nhưng khi nghe Dũng phân tích số liệu thực tế về nỗi đau của kế toán thanh toán (30–60 bộ/ngày, nguy cơ xuất toán thuế), tôi nhận ra bài toán kế toán có Business Impact lớn hơn nhiều và đã vui vẻ đổi ý để ủng hộ nhóm.
- Hiểu sâu sắc rằng AI không phải là "cây đũa thần" làm từ A–Z, mà giá trị nằm ở việc kết hợp đúng chỗ: dùng Rule cho việc Rule làm tốt (đọc XML hóa đơn chuẩn) và chỉ dùng AI cho việc cần hiểu ngữ nghĩa tự nhiên (đọc hợp đồng scan phi cấu trúc).

---

### NguyenTuanDung-2A202603859

**Phần việc phụ trách:**

- Đưa ra và pitch Problem Card #1 (Đối chiếu hồ sơ thanh toán nhà cung cấp - 3-way matching) được nhóm chọn làm đề tài chính.
- Phụ trách chính phần kiểm chứng giả định (CP4), thực hiện 2 buổi phỏng vấn (Chuyên viên AP và Giám đốc công ty nhỏ).
- Phân tích và lập luận lựa chọn mức can thiệp AI Workflow thay vì Agent (CP6).
- Soạn thảo phần phân tích 4 rủi ro và xác lập Ngưỡng dừng (Stop Threshold) cho giai đoạn pilot.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp bài toán cốt lõi cho nhóm với đầy đủ dữ liệu thực tế và quy trình rõ ràng.
- Ghi nhận 2 interview snapshots và thu thập tín hiệu phản bác từ doanh nghiệp siêu nhỏ, giúp nhóm thu hẹp actor mục tiêu.
- Soạn thảo Mục 6.2 (So sánh 4 mức can thiệp) và Mục 8 (Bảng 4 rủi ro & Quyết định) trong `group_report.md`.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Mục 2.1 (Pitch Card #1), Mục 3.1 & 3.2 (Kiểm chứng), Mục 6.2, Mục 8.
- `report/assets/cp4-interview-snapshots.md`: Phỏng vấn #1 và #4.
- `report/individual/2A202603859_NguyenTuanDung.md`: Báo cáo cá nhân của Dũng.

**Điều mình học được từ phần nhóm:**

- Học được cách trình bày vấn đề dựa trên con số cụ thể thay vì cảm tính. Sự phản biện của Trung và các bạn đã giúp bài toán của tôi chặt chẽ hơn rất nhiều, từ một ý tưởng còn mơ hồ về AI đã trở thành một quy trình Hybrid Workflow thực tế, khả thi và an toàn cao.

---

### LeMinhQuan-2A202601124

**Phần việc phụ trách:**

- Xây dựng bảng Assumption Map (CP4.1) xếp hạng rủi ro các giả định.
- Thiết kế bảng câu hỏi và triển khai khảo sát nhanh (micro-survey) với 24 nhân sự.
- Thực hiện Interview Snapshot #3 (với Chuyên viên Mua hàng).
- Đóng vai trò phản biện độc lập (Devil's Advocate) trong suốt các khâu đánh giá.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Tổng hợp số liệu từ 24 phiếu khảo sát, đưa ra các con số định lượng (83.3% áp dụng 3-way matching, 62.5% đau đầu vì hợp đồng scan).
- Tham gia phản biện Problem Statement v0, thúc đẩy nhóm bổ sung Success Metric về độ chính xác tài chính.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Mục 3.1 (Assumption Map) và Mục 3.2 (Tổng hợp kết quả survey).
- `report/assets/cp4-interview-snapshots.md`: Phỏng vấn #3 và báo cáo số liệu survey.

**Điều mình học được từ phần nhóm:**

- Phỏng vấn theo The Mom Test thực sự mở mắt: không bao giờ hỏi khách hàng "Bạn có thích tính năng này không", mà phải hỏi "Lần gần nhất bạn làm mất bao lâu và gặp sự cố gì".

---

### TranThuyLinh-2A202602358

**Phần việc phụ trách:**

- Nghiên cứu các giải pháp hiện có trên thị trường (Kofax, AWS Textract, invoice2data) kèm link kiểm chứng (CP4.3).
- Xây dựng AI Canvas rút gọn và trả lời 2 câu hỏi thiết kế của Google PAIR (CP6).
- Thiết lập 4 tiêu chí đánh giá chất lượng (Eval Criteria) và xây dựng bộ dữ liệu 10 ca kiểm thử mẫu (CP6/CP7).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Bảng so sánh 3 công cụ thị trường và chỉ ra khoảng trống lớn về việc đọc hợp đồng scan tiếng Việt.
- Bảng AI Canvas gồm 6 thành phần: Prediction, Judgment, Action, Outcome, Input, Feedback.
- Bộ 10 cặp test cases trong file `report/assets/cp6-eval-dataset.md` đạt chuẩn chất lượng cao.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Mục 3.3 (Research), Mục 6.3 (AI Canvas), Mục 6.4 (Google PAIR), Mục 7 (Tiêu chí đánh giá).
- `report/assets/cp6-eval-dataset.md`: Toàn bộ bộ dữ liệu 10 cases.

**Điều mình học được từ phần nhóm:**

- Nhận ra rằng đa số các công cụ thị trường đều bỏ trống khâu kết nối quy trình. Việc lựa chọn mô hình không quan trọng bằng việc thiết lập đúng các tiêu chí đánh giá (Eval) và cơ chế chốt chặn con người.
