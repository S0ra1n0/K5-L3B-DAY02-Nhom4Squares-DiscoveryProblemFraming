# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: 4Squares
- Candidate problem nhóm chọn (1 câu): Sinh viên mất khoảng 25 phút mỗi sáng mở LMS, Phoenix và lướt nhiều kênh Discord để không bỏ sót hạn nộp và thay đổi yêu cầu, nhưng vẫn có lúc sót.
- Quyết định cuối (Go / Not Yet / No-Go): Go (phạm vi nhỏ): pilot giải pháp Rule trong 2 tuần trên 4 thành viên; chưa thêm bước AI

## Thành viên

| STT | Họ và tên           | MSSV        | Vai trò trong nhóm                                                                                       | Tài khoản GitHub |
| --: | ------------------- | ----------- | -------------------------------------------------------------------------------------------------------- | ---------------- |
|   1 | Nguyễn Lê Đăng Khoa | 2A202603847 | Nhóm trưởng: điều phối, merge các nhánh; phụ trách research, vẽ quy trình, Problem Statement và quyết định | s0ra1n0          |
|   2 | Nguyễn Tuấn Dũng    | 2A202603859 | Chấm điểm shortlist và xử lý bất đồng khi chọn bài (mục 2.4)                                               | DungNguyen74     |
|   3 | Nguyễn Hoàng Trung  | 2A202603826 | Người phản biện chính; viết bản đầu quy trình và Problem Statement                                         | trungtk03        |
|   4 | Trần Phạm Minh Sơn  | 2A202603802 | Phụ trách kiểm chứng (phỏng vấn nhanh); cung cấp số liệu baseline cho bài A (card #2)                      | sontpm           |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint                                 | Người chính        | Người hỗ trợ                              | Sản phẩm                                       |
| ------------------------------------------ | ------------------ | ----------------------------------------- | ---------------------------------------------- |
| CP3 — Hội tụ nhóm                          | Nguyễn Lê Đăng Khoa (2.1–2.3), Nguyễn Tuấn Dũng (2.4) | Nguyễn Hoàng Trung | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng                           | Trần Phạm Minh Sơn  | Nguyễn Lê Đăng Khoa                        | Assumption map, snapshot hoặc survey           |
| CP4 — Research                             | Nguyễn Lê Đăng Khoa |                                            | Bảng research có link                          |
| CP5 — Quy trình trước/sau                  | Nguyễn Lê Đăng Khoa | Trần Phạm Minh Sơn (số liệu), Nguyễn Hoàng Trung (bản đầu) | Quy trình + bảng before/after |
| CP5 — Problem Statement v0                 | Nguyễn Lê Đăng Khoa | Nguyễn Hoàng Trung (bản đầu)               | Problem Statement v0                           |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Lê Đăng Khoa | Nguyễn Hoàng Trung (bản đầu)               | Ma trận, eval, Problem Statement v1            |
| CP6 — Quyết định                           | Nguyễn Lê Đăng Khoa |                                            | 4 rủi ro + Go/Not Yet/No-Go                    |

"Bản đầu" là bản viết cho bài đối chiếu hồ sơ thanh toán (commit `d02f50e`), đã được thay khi nhóm thống nhất giữ bài A.

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenLeDangKhoa-2A202603847

**Phần việc phụ trách:**

- Nhóm trưởng: fork repo, mời thành viên, điều phối phân công, merge các nhánh vào `main`.
- CP3: dựng bảng pitch, cluster và cây OST.
- CP4–CP6 cho bài A: research, quy trình trước/sau, Problem Statement v0/v1, mức can thiệp, quyết định.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 Problem Card (#4, #5, #6). Card #4 cùng card #2 của Sơn thành candidate A, bài nhóm chọn.
- Dựng bảng 2.1 (12 candidate), 2.2 (4 cluster), 2.3 (cây OST, gạch 2 ý là solution đội lốt).
- Phản biện 3 card của Trung (#10–#12), ghi vào cột phản biện ở 2.1.
- Phát hiện CP4–CP6 đang viết cho bài khác với lựa chọn ở CP3 (bài đối chiếu hồ sơ thanh toán), đề xuất nhóm giữ bài A và viết lại cho khớp.
- Viết mục 3.1 (Assumption Map 5 giả định), 3.3 (5 công cụ có sẵn, chỉ giữ link mở được), 4.1–4.3 (quy trình từ số liệu của Sơn, Before/After), 5 và 7 (Problem Statement v0, v1), 6 (chọn Rule), 8 (4 rủi ro, Go phạm vi nhỏ, 3 ngưỡng dừng).
- Gỡ 2 file trong `report/assets/` của bài kế toán vì không khớp CP3 và không có minh chứng.
- Merge 4 nhánh; khôi phục báo cáo cá nhân của Dũng bị mất khi merge (conflict modify/delete); gộp `TEAM.md` về một bảng thành viên.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1–2.3, 3.1, 3.3, 4, 5, 6, 7, 8.
- Commit `755f29d` (bảng CP3), `dee6248` (khôi phục file của Dũng), `c124d07` (dọn TEAM.md, Assumption Map, research), `bf44b7d` (quy trình 4.1, 4.3), `8a8416e` (viết lại CP4–CP6 cho bài A, gỡ file assets của bài kế toán).

**Điều mình học được từ phần nhóm:**

- Phải chốt bài toán bằng văn bản trước khi chia việc. Nhóm đã chọn bài A ở CP3, nhưng CP4–CP6 lại được viết cho một bài khác, nên phải viết lại gần hết.
- Merge nhiều nhánh cùng sửa một file thì phải merge từng nhánh và xem diff trước khi đẩy lên `main`. Lần này một conflict modify/delete làm mất file của Dũng, và một lần merge khác làm mất các bảng Trung đã điền.
- Tìm công cụ có sẵn trước khi chọn mức AI. Research cho thấy lịch LMS, bộ lọc email và Zapier đã làm được phần lớn bài A, nên nhóm chọn Rule thay vì Workflow có AI.

### NguyenTuanDung-2A202603859

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

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Bảng 2.1 (Pitch candidate #10), Mục 2.2 & 2.3 (Cluster & Cây OST), Mục 4.1 & 4.2 (Sơ đồ quy trình Mermaid As-Is và To-Be), Mục 5 (Problem Statement v0) và Mục 7 (Problem Statement v1).
- `report/individual/2A202603826_NguyenHoangTrung.md`: Toàn bộ báo cáo cá nhân của Nguyễn Hoàng Trung.
- Các commit trên repo: `0c12ce6`, `d02f50e`, `18544e5`, `5a34a37`, `d40b1a7`.

_Ghi chú của nhóm: mục 4.1, 4.2, 5, 7 nói ở trên là bản đầu viết cho bài đối chiếu hồ sơ thanh toán (commit `d02f50e`). Bản hiện tại trong `group_report.md` đã được viết lại cho bài A._

**Điều mình học được từ phần nhóm:**

- Nhận thức rõ ràng về sự nguy hiểm của cái bẫy "yêu giải pháp của mình" (solution-first). Ban đầu tôi rất muốn nhóm chọn bài toán kỹ thuật Release Notes của mình, nhưng qua phản biện nhóm, tôi học được cách nhìn nhận khách quan dựa trên tần suất gặp phải và tính cấp thiết đối với người dùng.
- Hiểu sâu sắc sự khác biệt giữa Workflow và Agent: không phải bài toán nào dùng Agent cũng là tốt, mà phải luôn bắt đầu từ mức can thiệp đơn giản nhất đủ dùng; đối với các quy trình có rủi ro cao, sự kiểm soát của con người (Human-in-the-loop) và ranh giới Boundary chặt chẽ là yếu tố sống còn.

### TranPhamMinhSon-2A202603802

**Phần việc phụ trách:**

- Pitch Problem Card #1 về bóc tách checklist bài lab từ tài liệu (CP3).
- Phụ trách phác thảo quy trình Tương lai (To-be) 4 bước và bảng so sánh Before/After (CP5).
- Tham gia phỏng vấn kiểm chứng thực tế 2 bạn sinh viên theo The Mom Test (CP4).
- Phân tích và lập luận lựa chọn mức can thiệp Workflow thay vì Agent (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Trình bày và bảo vệ thành công candidate problem của Card #1.
- Đặt câu hỏi phản biện sâu sắc giúp nhóm nhận diện rủi ro Usability/Eval.
- Thu thập bằng chứng phỏng vấn xác nhận nỗi đau phân mảnh tài liệu của sinh viên.
- Hoàn thiện sơ đồ quy trình tương lai có cơ chế Human-in-the-loop, giúp rút ngắn thời gian chuẩn bị từ 50 phút xuống dưới 15 phút.

**Bằng chứng**:

- Báo cáo cá nhân: `report/individual/2A202603802_TranPhamMinhSon.md`.

**Điều học được từ phần nhóm:**

- Nắm vững nguyên tắc "Problem-first, not AI-first": chỉ khi tìm ra chính xác bước nghẽn (bottleneck) mới cân nhắc can thiệp AI ở mức đơn giản nhất đủ dùng (Workflow).
- Thấy rõ giá trị của phản biện đa chiều từ đồng đội giúp phát hiện lỗ hổng Usability và bổ sung boundary an toàn cho AI.
