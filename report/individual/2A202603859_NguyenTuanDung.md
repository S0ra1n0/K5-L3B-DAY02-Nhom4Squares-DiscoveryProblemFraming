# Báo cáo cá nhân — 202603859_NguyenTuanDung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Tuấn Dũng
- MSSV: 202603859
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom4Squares
- Link repo nhóm: https://github.com/S0ra1n0/K5-L3B-DAY02-Nhom4Squares-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận ticket sửa lỗi (bug) hoặc làm tính năng nhỏ từ Mentor/QA giao trên Jira ở công ty thực tập, tôi muốn đối chiếu nhanh mô tả lỗi sơ sài trên ticket với tài liệu PRD trên Confluence, lịch sử thảo luận trong thread Slack và log lỗi từ Sentry, để tái hiện (reproduce) đúng lỗi ngay lần đầu mà không code nhầm logic. | Thực tập sinh Kỹ thuật / Junior Dev (6 người trong team), QA/Tester (3 người), Mentor/Tech Lead. | Mỗi tuần 1 thực tập sinh xử lý 8–10 tickets. Mất 35–45 phút/ticket chỉ để lục tìm tài liệu rải rác ở 4 nơi (Jira, Slack, Confluence, Figma). Khoảng 30% PR (Pull Request) của intern bị QA/Mentor trả lại vì hiểu thiếu edge case hoặc đọc nhầm bản spec cũ chưa cập nhật trên Confluence. |
| 2 | Lặp lại | Khi có đợt sinh viên thực tập mới (hoặc thành viên mới) vào team công nghệ, tôi muốn họ tự tra cứu được ngay cách cài đặt môi trường local (Docker, biến `.env`, quyền truy cập DB staging, quy tắc đặt tên branch), để tôi và các anh chị Senior không bị ngắt quãng lúc đang tập trung code. | Thực tập sinh cũ & Junior/Senior Dev trong team (10 người), các bạn Intern mới (4–5 người/đợt). | Mỗi tuần có 15–20 câu hỏi lặp đi lặp lại trên kênh Slack `#dev-help` về lỗi build Docker và thiếu file cấu hình. Mỗi lần chỉ dẫn mất 15–20 phút gọi huddle hoặc tìm lại tin nhắn cũ vì tài liệu `README.md` trong repo đã lỗi thời từ 6 tháng trước. |
| 3 | Tốn thời gian | Khi đến chiều thứ Sáu hàng tuần ở công ty và cuối mỗi tuần học đồ án ở trường, tôi muốn gom nhanh các commit Git, danh sách PR đã merge và các task Jira đã đóng, để viết báo cáo thực tập tuần gửi Mentor/HR và cập nhật nhật ký đồ án cho giảng viên hướng dẫn. | Thực tập sinh tại công ty công nghệ (15–20 bạn mỗi kỳ), sinh viên làm đồ án nhóm (4 người/nhóm). | Chiều thứ Sáu nào cũng mất 45–60 phút mở lại từng lịch sử commit trên GitHub, lướt lại từng ngày trên Jira và Slack để nhớ xem tuần qua mình đã làm gì rồi gõ lại vào form báo cáo. Rất nhiều bạn nộp muộn hoặc viết báo cáo chung chung kiểu "Tiếp tục hoàn thiện tính năng X". |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi làm bài tập lớn hoặc khóa luận ở trường cần viết phần Khảo sát nghiên cứu liên quan (Literature Review), tôi muốn trích xuất và lập bảng so sánh nhanh kiến trúc mô hình, tập dữ liệu (dataset), metric và hạn chế của 20–30 bài báo khoa học (file PDF tiếng Anh), để tìm ra khoảng trống nghiên cứu (research gap) báo cáo cho thầy hướng dẫn. | Sinh viên năm 3–4 làm đồ án/NCKH (nhóm 3–4 người), Giảng viên hướng dẫn. | Mỗi đợt làm đề tài phải tải 25–30 file PDF từ ArXiv/IEEE (mỗi bài dài 10–15 trang). Mất trung bình 40–50 phút/bài để đọc lướt và gõ tay các thông số vào bảng Excel/Notion. Cả nhóm mất gần 2 tuần chỉ để đọc và tổng hợp mà vẫn hay nhầm lẫn thông số giữa các bài. |
| 5 | Lặp lại | Khi gần đến đợt đăng ký tín chỉ, xét học bổng hoặc nộp hồ sơ quy đổi điểm thực tập tại trường, tôi muốn kiểm tra chính xác điều kiện tiên quyết, số tín chỉ tự chọn còn thiếu và biểu mẫu cần nộp theo đúng khóa học của mình, để không bị đăng ký nhầm môn hoặc nộp sai giấy tờ. | Sinh viên toàn khóa (~400–500 người), Cố vấn học tập, Chuyên viên phòng Đào tạo / Công tác sinh viên. | Vào mỗi đầu kỳ (2 tuần cao điểm), group Facebook/Zalo của khóa xuất hiện 30–50 bài đăng/ngày hỏi đi hỏi lại cùng một câu về môn tương đương và quy định thực tập. Sổ tay sinh viên là file PDF dài hơn 120 trang kèm hàng chục thông báo sửa đổi rời rạc trên cổng thông tin trường. |
| 6 | Pain từ người khác | Khi QA hoặc bộ phận CSKH đẩy một bug từ môi trường Staging/Production vào nhóm chat của team dev, tôi muốn ticket đó có sẵn đầy đủ các bước tái hiện (steps to reproduce), payload request, ảnh chụp console log và môi trường trình duyệt, để bắt tay vào fix bug ngay lập tức. | QA/Tester, Thực tập sinh & Developer trực bug (5–6 người). | Trung bình mỗi ngày có 5–8 bug được báo qua chat hoặc tạo nhanh trên Jira chỉ với 1 câu tiêu đề kèm 1 bức ảnh cắt cúp. Dev phải nhắn tin hỏi đi hỏi lại QA mất 20–30 phút (thậm chí nửa buổi nếu QA đang bận test luồng khác) mới lấy đủ thông tin để tái hiện lỗi trên máy. |
| 7 | Tốn thời gian | Khi làm việc nhóm 4–5 người cho đồ án môn học ở trường (hoặc dự án intern), tôi muốn sau mỗi buổi họp trên Google Meet/Discord có ngay danh sách công việc (action items) gắn rõ tên người làm, deadline và các quyết định kỹ thuật đã chốt, để không ai quên việc hoặc cãi nhau về sau. | Sinh viên làm đồ án nhóm (4–5 người/nhóm), Nhóm trưởng. | Một học kỳ một sinh viên học 4–5 môn có đồ án nhóm, mỗi tuần họp 2–3 buổi (45–60 phút/buổi). Sau buổi họp, nhóm trưởng mất 20–30 phút nghe lại hoặc nhớ lại để gõ task lên Notion/Trello. Khoảng 25% đầu việc nói miệng trong lúc họp bị bỏ quên vào tuần kế tiếp. |
| 8 | Pain từ người khác | Khi nộp Pull Request (PR) lên repo của công ty thực tập, tôi muốn rà soát trước các lỗi coding convention, biến thừa, thiếu xử lý ngoại lệ (try/catch) cơ bản và đối chiếu xem đã thỏa mãn đủ Acceptance Criteria của ticket chưa, để Mentor không phải mất thời gian comment những lỗi sơ đẳng. | Thực tập sinh (người tạo PR), Senior Dev / Mentor (người review code). | Mỗi ngày Mentor phải review 6–8 PR từ các intern và junior. Trung bình 1 PR của thực tập sinh mất 2–3 vòng sửa đi sửa lại (kéo dài 1–2 ngày) chỉ vì những lỗi nhỏ như quên xóa `console.log`, hardcode biến môi trường hoặc sót yêu cầu hiển thị trạng thái loading/error trong ticket. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Giữ lại: Gợi ý của AI về bài toán đối chiếu ngữ cảnh khi nhận ticket bug (#1) và bài toán tổng hợp bảng so sánh các bài báo khoa học khi làm đồ án ở trường (#4) vì đây chính xác là hai việc ngốn nhiều thời gian đọc hiểu tài liệu phân tán nhất của tôi mỗi tuần, có thể đếm được ngay số phút và số lần làm lại trên Jira và Notion.
- Bỏ đi: Các gợi ý của AI như "Xây dựng hệ thống AI tự động chấm điểm rèn luyện toàn trường" hoặc "Tự động tối ưu hóa chi phí hạ tầng Cloud AWS cho CTO công ty" vì vượt quá quyền hạn và phạm vi công việc của một sinh viên/thực tập sinh, không thể tiếp cận người có thẩm quyền hay dữ liệu thật để kiểm chứng trong buổi lab.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 — Đối chiếu ngữ cảnh đa nguồn (Jira, Confluence, Slack, Log) khi xử lý ticket bug/task tại công ty thực tập | Nỗi đau xảy ra hàng ngày với chính bản thân và các bạn intern/dev trong công ty. Quy trình có các bước rõ ràng, dễ đo thời gian tìm kiếm thông tin và tỷ lệ PR bị trả lại do hiểu thiếu yêu cầu. | Chưa chắc trong 30% PR bị trả lại thì bao nhiêu phần là do tài liệu phân tán khó tìm, bao nhiêu phần là do bản thân người tạo ticket (BA/PM/QA) chưa hề viết yêu cầu đó ra bất kỳ đâu. |
| 2 | #4 — Đọc và lập bảng tổng hợp Literature Review từ hàng chục bài báo PDF khi làm đồ án/NCKH ở trường | Rất tốn thời gian đọc hiểu tài liệu dài bằng tiếng Anh, hầu như sinh viên CNTT nào làm đồ án hoặc khóa luận cũng đang phải làm thủ công trên Excel/Notion. | Chưa rõ các bạn sinh viên khác mất thời gian nhất ở bước tìm kiếm bài báo phù hợp hay ở bước đọc sâu từng bài để trích xuất bảng thông số kỹ thuật. |
| 3 | #6 — Chuẩn hóa thông tin báo lỗi (Bug Report) từ QA/CSKH chuyển sang cho team Dev | Tác động trực tiếp đến tốc độ xử lý lỗi hàng ngày trong sprint, giảm thời gian nhắn tin hỏi qua lại giữa Tester và Dev. | Cần kiểm chứng xem phía QA/Tester thấy phiền nhất ở bước nào khi tạo ticket lỗi để không đề xuất một quy trình bắt họ điền quá nhiều trường thủ công. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được một ticket sửa lỗi hoặc làm tính năng nhỏ trên Jira tại công ty thực tập, tôi muốn gom và đối chiếu nhanh yêu cầu trên ticket với tài liệu spec trên Confluence, các thay đổi chốt thêm trên Slack và log lỗi thực tế, để hiểu đúng toàn bộ ngữ cảnh và edge cases trước khi bắt tay vào viết code. |
| Actor | Thực tập sinh Kỹ thuật ( Engineering Intern ) / Junior Developer — người trực tiếp nhận ticket và code; QA/Tester và Mentor — người kiểm tra và duyệt Pull Request. |
| Thời điểm / bối cảnh | Diễn ra hàng ngày trong mỗi Sprint khi bắt đầu kéo một ticket mới từ cột To Do sang In Progress trên bảng Jira của team. |
| Quy trình hiện tại (3–7 bước) | 1. Mở ticket trên Jira để đọc mô tả ngắn gọn và tiêu chí nghiệm thu (Acceptance Criteria).<br>2. Tìm link tài liệu PRD/Spec trên Confluence và link thiết kế Figma đính kèm (hoặc tự gõ từ khóa tìm nếu người tạo quên gắn link).<br>3. Copy tên tính năng hoặc mã ticket vào ô tìm kiếm của Slack để đọc lại các cuộc thảo luận/thay đổi yêu cầu phát sinh giữa PM, BA và Tech Lead.<br>4. Mở Sentry/Log hoặc môi trường Staging để tự thao tác tái hiện lại lỗi và ghi chú ra các trường hợp biên (edge cases) cần xử lý.<br>5. Viết code, tự test và tạo Pull Request (PR) gửi Mentor review và đẩy sang QA test.<br>6. Nếu hiểu sai yêu cầu hoặc thiếu edge case đã từng bàn trên Slack: nhận comment trả lại từ Mentor/QA, đọc lại và sửa code. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & Bước 3 (Lục tìm tài liệu trên Confluence và lội đọc hàng chục tin nhắn rải rác trên Slack để đối chiếu xem đâu là yêu cầu mới nhất — mất 30–40 phút/ticket) và Bước 6 (Sửa lại PR do bỏ sót thay đổi yêu cầu — mất thêm 1–2 giờ/lần bị trả lại). |
| Impact (nếu không giải thì sao) | Thực tập sinh mất gần 1 tiếng đầu tiên của mỗi task chỉ để đi tìm đọc thông tin hoặc phải ngại ngùng nhắn hỏi Mentor; khoảng 30% PR bị trả lại vì làm theo spec cũ trên Confluence mà không biết PM đã chốt đổi logic trên Slack, làm trễ tiến độ Sprint. |
| Success metric (baseline → target) | Thời gian thu thập ngữ cảnh và xác nhận yêu cầu trước khi code cho 1 ticket giảm từ 40 phút → dưới 10 phút; Tỷ lệ PR bị trả lại do hiểu sai/thiếu yêu cầu (spec mismatch) giảm từ 30% → dưới 10%. |
| Phương án không dùng AI | Thiết lập mẫu bắt buộc (Jira Issue Template) yêu cầu người tạo ticket phải điền đủ link Confluence, Figma, bước tái hiện lỗi mới cho lưu; quy định mọi thay đổi yêu cầu trên Slack bắt buộc phải được cập nhật lại vào phần Description của Jira. |
| Giả thuyết về AI (nếu có) | Kết hợp Rule (kiểm tra trường bắt buộc trên Jira Template + tự động gắn log lỗi theo mã ID) với AI Workflow (tự động kéo nội dung từ link Confluence và các thread Slack có gắn mã ticket, tóm tắt thành 1 bản Checklist yêu cầu kèm cảnh báo những chỗ Slack đang mâu thuẫn với tài liệu Confluence cũ). |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Nhận ticket trên Jira] -> [1. Đọc mô tả sơ sài trên Jira] -> [2. Tự mò tìm trang PRD trên Confluence & Figma (15 phút)] -> [3. Search từ khóa trên Slack để đọc các thay đổi phát sinh (BOTTLENECK: 20-25 phút, dễ sót tin nhắn)] -> [4. Mở Staging/Log tái hiện lỗi & Viết code] -> [5. Tạo PR gửi Mentor & QA] -> (Nếu sót logic/theo spec cũ ~30%) -> [6a. Bị trả lại PR, phải hỏi lại & sửa code (+1-2 giờ)] / (Nếu đúng đủ 100%) -> [6b. Merge PR & Đóng ticket]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi thực hiện đồ án chuyên ngành hoặc nghiên cứu khoa học tại trường cần khảo sát các công trình liên quan, tôi muốn trích xuất chính xác phương pháp, tập dữ liệu, kết quả thực nghiệm và hạn chế từ 20–30 bài báo khoa học PDF sang một bảng so sánh thống nhất, để nhanh chóng viết phần Literature Review và xác định hướng làm cho nhóm. |
| Actor | Sinh viên năm 3–4 ngành CNTT/AI làm đồ án hoặc khóa luận (nhóm 3–4 sinh viên); Giảng viên hướng dẫn. |
| Thời điểm / bối cảnh | Giai đoạn 3 tuần đầu tiên của học kỳ khi mới nhận đề tài đồ án hoặc khi chuẩn bị viết báo cáo tiến độ giữa kỳ nộp cho giảng viên. |
| Quy trình hiện tại (3–7 bước) | 1. Tìm kiếm theo từ khóa trên Google Scholar, ArXiv, Semantic Scholar và tải về 20–30 file PDF bài báo liên quan.<br>2. Đọc phần Abstract và Conclusion của từng bài để lọc ra khoảng 15 bài sát đề tài nhất.<br>3. Mở từng file PDF (10–15 trang, bố cục 2 cột kèm nhiều bảng biểu), đọc kỹ phần Methodology và Experiments.<br>4. Gõ tay các thông tin (Tên bài, Năm, Kiến trúc mô hình, Dataset, Metric đạt được, Hạn chế, Link code) vào bảng Notion hoặc Excel của nhóm.<br>5. Đối chiếu các dòng trong bảng để viết đoạn văn nhận xét tổng quan đưa vào báo cáo Word/LaTeX. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & Bước 4 (Đọc dò trong các mục Methodology/Experiments của từng file PDF tiếng Anh và gõ tổng hợp vào bảng so sánh — mất 40–50 phút/bài báo, tổng cộng mất 12–15 giờ cho một đợt khảo sát). |
| Impact (nếu không giải thì sao) | Nhóm sinh viên mất gần 2 tuần đầu chỉ để đọc và chép lại thông tin nên bị thiếu thời gian cho việc code thực nghiệm; khi chia nhau đọc mỗi người một kiểu nên bảng tổng hợp bị lệch tiêu chí, thậm chí trích dẫn nhầm con số metric giữa các bài báo. |
| Success metric (baseline → target) | Thời gian trích xuất và kiểm chứng thông tin 1 bài báo vào bảng tổng hợp giảm từ 45 phút → 10 phút/bài; Tỷ lệ trích dẫn sai thông số (dataset/metric) trong bảng giảm về 0%. |
| Phương án không dùng AI | Thống nhất trước một biểu mẫu bảng Excel cố định gồm các cột bắt buộc cho cả nhóm; sử dụng công cụ quản lý tài liệu Zotero kết hợp chia phần đọc theo từng mục cố định của bài báo. |
| Giả thuyết về AI (nếu có) | Dùng AI Workflow đọc file PDF bài báo, tự động trích xuất đúng các trường theo cấu trúc bảng (Dataset, Baseline, Metric, Limitation) kèm theo trích dẫn nguyên văn câu gốc và số trang/bảng (citation) để sinh viên kiểm tra lại trong 2 phút. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Tải 20-30 file PDF bài báo] -> [1. Đọc Abstract lọc ra 15 bài sát đề tài] -> [2. Đọc dò phần Methodology & bảng Experiments trong PDF 2 cột (BOTTLENECK 1: 30 phút/bài)] -> [3. Gõ tay thông số vào bảng Notion/Excel chung của nhóm (BOTTLENECK 2: 15 phút/bài, không đồng nhất)] -> [4. Đối chiếu viết đoạn tổng quan vào báo cáo đồ án]
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi QA/Tester hoặc người dùng nội bộ phát hiện lỗi trên môi trường Staging của công ty, tôi muốn ticket báo lỗi gửi về cho team Dev có sẵn đầy đủ các bước tái hiện, log lỗi console/network và dữ liệu đầu vào, để tôi có thể bắt tay vào debug ngay trên máy cá nhân mà không phải nhắn tin hỏi lại. |
| Actor | Thực tập sinh / Developer (người nhận và sửa bug); QA/Tester (người tạo ticket báo lỗi). |
| Thời điểm / bối cảnh | Trong giai đoạn kiểm thử tích hợp (SIT/UAT) cuối mỗi Sprint, khi QA test dồn dập và đẩy hàng loạt ticket bug về cho team Dev. |
| Quy trình hiện tại (3–7 bước) | 1. QA phát hiện lỗi khi test trên web/app, chụp nhanh màn hình lỗi và tạo ticket trên Jira (hoặc nhắn vào nhóm Slack).<br>2. Thực tập sinh/Dev nhận ticket, đọc tiêu đề và nhìn ảnh chụp màn hình.<br>3. Dev mở môi trường local/staging cố gắng làm theo ảnh để tái hiện lại lỗi nhưng không thấy lỗi xuất hiện.<br>4. Dev nhắn tin qua Slack hỏi QA: dùng tài khoản nào, truyền tham số gì, lỗi trả về mã bao nhiêu trong tab Network.<br>5. Chờ QA rảnh để test lại và gửi cURL/log qua chat, sau đó Dev mới bắt đầu debug và sửa code. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & Bước 4 (Cố tái hiện lỗi trong mù mờ và nhắn tin hỏi đi hỏi lại QA để xin tài khoản test, payload, log — mất 25–30 phút chờ đợi và trao đổi cho mỗi bug). |
| Impact (nếu không giải thì sao) | Thời gian chờ thông tin còn lâu hơn thời gian sửa code thực tế (nhiều bug chỉ sửa 10 phút nhưng mất 1 tiếng hỏi qua lại); làm gián đoạn mạch làm việc của cả Dev lẫn QA. |
| Success metric (baseline → target) | Tỷ lệ ticket bug có đủ thông tin để tái hiện ngay lần đầu (First-time reproducible rate) tăng từ 45% → 85%; Thời gian trao đổi hỏi lại thông tin trung bình trên mỗi bug giảm từ 25 phút → dưới 5 phút. |
| Phương án không dùng AI | Cài đặt quy tắc bắt buộc trên Jira (Validation Rule): không cho phép chuyển trạng thái ticket sang Open nếu bỏ trống các ô Steps to Reproduce, Environment, Test Account và cURL/Log; hướng dẫn QA dùng tiện ích quay màn hình kèm tự động bắt log (như Jam.dev). |
| Giả thuyết về AI (nếu có) | Dùng Rule kiểm tra trường bắt buộc kết hợp AI Workflow đọc log/ảnh chụp màn hình QA tải lên để tự động điền nháp các bước tái hiện, bóc tách mã lỗi HTTP và gợi ý file code có khả năng gây lỗi cho Dev. |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
[QA gặp lỗi & tạo ticket chỉ có ảnh chụp màn hình] -> [1. Intern/Dev nhận ticket & mở máy thử tái hiện] -> [2. Không tái hiện được lỗi vì thiếu data/tài khoản test (BOTTLENECK 1: 15 phút mò mẫm)] -> [3. Nhắn Slack hỏi QA & chờ gửi lại log/cURL (BOTTLENECK 2: 15-30 phút chờ đợi)] -> [4. Debug, sửa code & đẩy lại cho QA re-test]
```

### Card muốn pitch nhất

- Card số: Card #1 — Đối chiếu ngữ cảnh đa nguồn (Jira, Confluence, Slack, Log) khi xử lý ticket tại công ty thực tập.
- Vì sao: Đây là nỗi đau sát sườn nhất mà tôi trải nghiệm hàng ngày khi đi thực tập tại công ty công nghệ, đồng thời các bạn trong nhóm (cũng là sinh viên đi thực tập hoặc làm dự án phần mềm) đều hiểu rất rõ quy trình làm việc với Jira, Git và Slack. Bài toán này giúp phân định cực kỳ rõ ranh giới giữa phần việc giải quyết bằng quy trình/Rule (bắt buộc gắn link tài liệu vào template Jira) và phần việc thực sự cần AI Workflow (đọc hiểu và phát hiện mâu thuẫn giữa tài liệu PRD cũ trên Confluence với các tin nhắn chốt lại logic trên Slack).
- Câu hỏi muốn nhóm phản biện: Trong 30% Pull Request bị trả lại do làm lệch yêu cầu hiện nay, bao nhiêu phần trăm thực sự giải quyết được bằng việc dùng AI tổng hợp tin nhắn Slack và Confluence, và bao nhiêu phần trăm xuất phát từ thói quen bàn bạc miệng ở ngoài rồi không ghi chép lên bất kỳ nền tảng nào (điều mà AI không thể nào đọc được)?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Ở bản nháp đầu tiên, tôi định dùng AI để tự động tìm kiếm toàn bộ kho dữ liệu Slack và Confluence của công ty mỗi khi có ticket mới. AI chỉ ra rằng việc quét toàn bộ workspace rất dễ kéo nhầm các cuộc hội thoại cũ không liên quan (nhiễu thông tin), trong khi phần lớn vấn đề có thể giải quyết bằng Rule: bắt buộc người tạo ticket phải gắn sẵn link Confluence và thread Slack vào trường quy định trên Jira. | Đồng ý | Sửa lại mục Phương án không dùng AI và Giả thuyết về AI: Dùng Rule ép buộc điền link nguồn trên Jira Template trước; AI Workflow chỉ đọc và đối chiếu trong phạm vi các link đã gắn cùng các tin nhắn có chứa đúng mã ID của ticket (ví dụ `PROJ-123`). |
| AI nhận xét rằng metric ban đầu của tôi ("Giúp thực tập sinh hiểu bài toán nhanh hơn và đỡ ngại hỏi Mentor") hoàn toàn cảm tính, không thể đo đếm để chứng minh hiệu quả. | Đồng ý | Đổi sang 2 chỉ số đo lường được trực tiếp từ lịch sử làm việc: Thời gian đọc tìm ngữ cảnh trước khi code (giảm từ 40 phút → dưới 10 phút) và Tỷ lệ PR bị trả lại do hiểu sai/thiếu yêu cầu (giảm từ 30% → dưới 10%). |
| AI gợi ý có thể nâng cấp thành một Coding Agent tự động đọc ticket, tự sửa code trong repo và tự mở Pull Request luôn cho thực tập sinh. | Không đồng ý | Giữ nguyên ở mức Workflow và bác bỏ hướng làm Agent tự code. Với các dự án thực tế ở công ty, việc để AI tự ý sửa code khi yêu cầu giữa Confluence và Slack còn đang mâu thuẫn sẽ tạo ra bug nghiêm trọng hơn; hơn nữa mục tiêu là giúp Dev nắm rõ yêu cầu và phát hiện điểm vênh trước khi code. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Card #1 (Đối chiếu ngữ cảnh từ Jira, Confluence, Slack khi xử lý ticket ở công ty thực tập) và chia sẻ thêm góc nhìn từ Card #2 (Tổng hợp bài báo làm đồ án ở trường) trong vòng 3 phút. | Giúp nhóm thấy rõ điểm chung của các bài toán sinh viên/thực tập sinh đều xoay quanh việc đọc hiểu và đối chiếu thông tin bị phân mảnh ở nhiều nguồn khác nhau. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Với bài toán quản lý công việc nhóm và nhắc lịch của bạn, nếu không dùng AI mà chỉ cài đặt một rule tự động gửi thông báo trên Google Calendar/Slack hoặc bắt buộc điền form cố định thì đã giải quyết được 80% vấn đề chưa? | Giúp nhóm sàng lọc và loại bỏ những candidate problems thực chất chỉ là thiếu kỷ luật làm việc nhóm (giải quyết bằng No AI / Rule), tránh việc cố gán ghép AI vào chỗ không cần thiết. |
| Nhận phản biện | Câu hỏi tôi nhận được: Nếu công cụ AI tóm tắt lại yêu cầu từ Slack và Confluence cho bạn, bạn có dám tin hoàn toàn vào bản tóm tắt đó để ngồi code luôn mà không mở link gốc ra đọc lại không? | Tôi đã sửa gì: Bổ sung yêu cầu bắt buộc vào cơ chế hiển thị (Usability) và tiêu chí Eval: Hệ thống không chỉ viết đoạn tóm tắt chung chung mà mỗi gạch đầu dòng yêu cầu phải đính kèm trích dẫn nguyên văn và link nhảy thẳng tới đúng dòng tin nhắn Slack hoặc mục trên Confluence để người làm kiểm chứng trong 30 giây. |
| Gom cluster / cây OST | Cùng 3 bạn trong nhóm Nhom4Squares gom 12 Problem Cards cá nhân thành 3 cụm trên cây OST: (1) Tổng hợp & đối chiếu tài liệu/ngữ cảnh phân tán; (2) Chuẩn hóa quy trình bàn giao thông tin trong team; (3) Tra cứu quy định/học thuật lặp lại. | Nhóm thống nhất tập trung vào nhánh Opportunity xử lý thông tin phi cấu trúc bị phân mảnh vì đây là nhóm bài toán mà Rule thông thường không giải quyết triệt để được. |
| Chọn candidate problem | Đề xuất chấm điểm chọn bài toán chung của nhóm dựa trên 3 tiêu chí: Tần suất gặp phải mỗi tuần, Khả năng tìm được ít nhất 3–4 bạn sinh viên/thực tập sinh thật để phỏng vấn ngay trong ca lab, và Độ rõ ràng của bottleneck. | Nhóm chốt được bài toán trọng tâm trong 10 phút mà không bị tranh luận lan man theo sở thích cá nhân. |
| Kiểm chứng / research | Cùng nhóm soạn bộ câu hỏi phỏng vấn theo đúng tinh thần The Mom Test (chỉ hỏi về lần gần nhất trong tuần qua bạn ấy bị trả lại task/PR hoặc mất thời gian tìm tài liệu, tuyệt đối không hỏi "bạn có muốn dùng app AI này không"). Trực tiếp hỏi và ghi chép câu trả lời của 2 bạn thực tập sinh/sinh viên. | Thu được bằng chứng hành vi thực tế: người được hỏi chỉ ra chính xác lần gần nhất họ mất gần 1 tiếng lục lại chat nhóm vì tài liệu gốc không được cập nhật sau khi họp, giúp nhóm định vị chuẩn xác hơn bước nghẽn. |
| Quy trình nhóm | Phác thảo và viết mã sơ đồ quy trình hiện tại (As-Is) và quy trình tương lai (To-Be) cho bài báo cáo nhóm, tách bạch rõ bước nào của Con người, bước nào của Rule và bước nào của AI Workflow. | Sơ đồ thể hiện trực quan vòng lặp phải làm lại (rework loop) ở quy trình cũ và cách đặt chốt chặn kiểm duyệt của con người (Human-in-the-loop) ở quy trình mới. |
| Problem Statement | Đóng góp viết phần Boundary (những giới hạn mà AI không được tự quyết) và xây dựng các trường hợp kiểm thử trong bộ Eval của nhóm. | Giúp Problem Statement v0 và v1 của Nhom4Squares chặt chẽ, có tiêu chí chấm Đạt/Không đạt rõ ràng thay vì chỉ mô tả tính năng. |
| Mức can thiệp AI | Lập luận bảo vệ phương án kết hợp Rule (kiểm tra điều kiện đầu vào) với AI Workflow (trích xuất và phát hiện điểm mâu thuẫn giữa các nguồn), bác bỏ phương án dùng Agent tự hành. | Giữ cho giải pháp của nhóm vừa khả thi về mặt kỹ thuật (Feasibility) vừa an toàn, không để AI tự ý ghi đè dữ liệu hay tự động ra quyết định thay con người. |
| Quyết định | Cùng nhóm rà soát bảng đánh giá 4 rủi ro (Value, Usability, Feasibility, Viability) và thống nhất điều kiện kiểm chứng trước khi chốt quyết định cuối cùng. | Đảm bảo kết luận của nhóm trong `group_report.md` dựa trên bằng chứng từ vòng phỏng vấn và có lộ trình thử nghiệm rõ ràng. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý cách diễn đạt đúng chuẩn cấu trúc Job Story (Khi... tôi muốn... để...) cho các vấn đề tôi gặp phải lúc đi học ở trường và lúc đi thực tập ở công ty. | Giúp chuẩn hóa nhanh câu chữ từ những lời than phiền rời rạc thành đúng cấu trúc Actor - Tình huống - Động lực - Kết quả mong muốn. | AI có xu hướng gợi ý thêm các bài toán rất xa rời thực tế sinh viên như "hoạch định chiến lược nhân sự" hoặc tự bịa ra các con số thống kê phần trăm nghe rất kêu nhưng không có thật. | Tôi xóa bỏ toàn bộ các ý tưởng vĩ mô của AI, chỉ giữ lại 8 vấn đề thật mà chính tôi cùng các bạn trong lab và các anh chị trong team thực tập đang trải qua hàng tuần, tự ước lượng lại thời gian dựa trên lịch sử làm việc của mình. |
| CP2 Problem Card | Yêu cầu AI đóng vai một Tech Lead khó tính để phản biện 3 Problem Cards của tôi và chỉ ra chỗ nào không cần dùng tới AI. | AI chỉ ra rất đúng việc nhiều lỗi thiếu thông tin trên ticket thực chất chỉ cần cài đặt Required Fields (Rule) trên Jira là chặn được ngay từ đầu, không cần dùng tới LLM. | Ở mục gợi ý hướng giải quyết, AI lại khuyên nên dùng Multi-Agent tự động đọc ticket rồi tự viết code và tự merge luôn. | Tôi bác bỏ gợi ý làm Agent tự động code vì với trải nghiệm đi thực tập, tôi biết rõ rủi ro phá hỏng hệ thống khi yêu cầu còn chưa rõ ràng; tôi giới hạn lại ở mức Workflow chỉ hỗ trợ tổng hợp và chỉ ra điểm mâu thuẫn giữa các tài liệu. |
| CP4 Research | Đưa bản nháp 6 câu hỏi phỏng vấn cho AI kiểm tra xem có câu nào vi phạm nguyên tắc The Mom Test (hỏi câu dẫn dắt, xin lời khen hoặc hỏi về ý định tương lai) hay không. | Giúp tôi phát hiện ra 2 câu hỏi bị mắc lỗi dẫn dắt ("Bạn có thấy việc tìm tài liệu trên Slack rất bất tiện và cần một con bot AI tóm tắt không?") để đổi thành câu hỏi về sự kiện đã xảy ra trong quá khứ. | AI sửa lại câu hỏi theo văn phong dịch thuật rất cứng nhắc, dài dòng như bảng khảo sát học thuật. | Tôi tự viết lại câu hỏi bằng ngôn ngữ trò chuyện tự nhiên giữa sinh viên và thực tập sinh với nhau (ví dụ: "Cái ticket gần nhất tuần này làm ông bị Mentor bắt sửa lại PR là bị dính lỗi gì thế?"). |
| CP5 Quy trình | Nhờ AI chuyển danh sách các bước quy trình xử lý công việc mà nhóm đã thảo luận thành mã sơ đồ để nhúng vào báo cáo. | Tạo khung sơ đồ rất nhanh, giúp nhóm tiết kiệm thời gian căn chỉnh cú pháp hiển thị trên Markdown. | Sơ đồ AI sinh ra lúc đầu chỉ đi theo một đường thẳng từ bước 1 đến bước cuối, bỏ qua mất nhánh rẽ khi làm sai phải quay lại sửa (rework loop) và không phân biệt rõ bước nào là Rule, bước nào là AI. | Tôi tự chỉnh sửa lại luồng rẽ nhánh trong sơ đồ để làm nổi bật điểm nghẽn (bottleneck) và gắn nhãn rõ ràng vị trí can thiệp của Rule, AI Workflow và bước kiểm duyệt của con người. |
| CP5–6 Problem Statement | Nhờ AI gợi ý cách viết các tiêu chí đánh giá (Eval) để kiểm tra xem đầu ra của AI Workflow đạt hay không đạt. | Gợi ý tốt việc tách tiêu chí Eval thành độ đầy đủ thông tin trích xuất (Recall) và độ chính xác của nguồn trích dẫn (Citation accuracy / chống bịa đặt). | Phần Boundary (Ranh giới) AI viết rất chung chung kiểu "AI không được làm lộ dữ liệu bảo mật của công ty". | Tôi sửa lại Boundary thành các quy tắc hành vi cụ thể gắn với quy trình: AI tuyệt đối không được tự ý sửa nội dung gốc trên Jira/Confluence, không được tự quyết định chọn logic nào khi thấy Slack và PRD mâu thuẫn mà phải gắn cờ cảnh báo để con người xác nhận. |
| CP6 Mức can thiệp / quyết định | Dùng AI để rà soát xem nhóm đã phân tích đủ 4 nhóm rủi ro Value, Usability, Feasibility, Viability theo khung của Marty Cagan chưa. | Nhắc nhóm chú ý tới rủi ro Feasibility về quyền truy cập dữ liệu (phân quyền API giữa Jira, Confluence và các kênh chat riêng tư trên Slack). | AI kết luận quá dễ dãi ở bước cuối khi khuyên nhóm chọn "Go" ngay lập tức mà không xét đến thói quen làm việc thực tế của người dùng. | Tôi và nhóm tự bổ sung phân tích sâu hơn về rủi ro Usability (nếu bắt dev phải copy-paste thủ công sang một web khác thì họ sẽ lười không dùng) và đặt điều kiện phải kiểm thử trên 20–30 trường hợp thật trước. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe các bạn trong nhóm Nhom4Squares trình bày top 3 problems cá nhân, điều tôi nhận ra rõ nhất là những vấn đề đáng giải quyết nhất đều xuất phát từ chính những việc rất nhỏ nhưng lặp đi lặp lại hàng ngày quanh việc học ở trường và chỗ thực tập. Trước đó tôi cứ nghĩ phải tìm một bài toán thật to tát ở tầm doanh nghiệp lớn, nhưng khi nghe các bạn mô tả chi tiết từng bước quy trình với con số cụ thể (như mất bao nhiêu phút để đọc lại tin nhắn nhóm, bao nhiêu lần phải sửa lại bài vì hiểu lệch yêu cầu), tôi thấy bài toán trở nên cực kỳ thuyết phục. Tôi cũng học được cách các bạn tách bạch giữa "triệu chứng bề nổi" và "điểm nghẽn gốc rễ" nằm ở bước chuyển giao thông tin giữa người với người.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, ngay lúc mới bước vào CP3 để thảo luận chọn đề tài nhóm, vì cả nhóm đều học về công nghệ nên phản xạ đầu tiên của tụi tôi là bàn ngay xem bài này sẽ dùng RAG, nối API gì hay thiết kế một con Agent tự động chạy từ đầu đến cuối như thế nào. Tụi tôi nhận ra mình đang bị "solution-first" khi nhìn vào bảng câu hỏi phản biện trong worksheet yêu cầu chỉ rõ: bước nào trong quy trình hiện tại đang tốn nhiều phút nhất và nếu không dùng AI thì giải quyết được tới đâu. Lúc đó cả nhóm đã dừng ngay việc bàn về công nghệ lại, quay về vẽ thật kỹ từng bước quy trình hiện tại của người dùng và ép nhau phải viết ra phương án No AI / Rule trước rồi mới được bàn tiếp.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã đổi ý ở ngay phần thiết kế đầu ra cho bài toán tổng hợp ngữ cảnh công việc của mình. Lúc đầu khi viết Card #1, tôi nghĩ chỉ cần AI đọc hết tài liệu trên Confluence và tin nhắn trên Slack rồi viết ra một đoạn văn tóm tắt ngắn gọn các yêu cầu là người làm sẽ tiết kiệm được rất nhiều thời gian. Nhưng khi pitch trong nhóm, một bạn đã hỏi thẳng tôi: "Nếu là ông đi thực tập, nhìn một đoạn tóm tắt do AI viết ra mà không biết nó lấy ở đâu, ông có dám tin 100% để ngồi code theo luôn mà không mở link gốc ra đọc lại không?". Câu hỏi đó làm tôi tỉnh ra ngay: nếu người dùng vẫn sợ AI bịa (hallucinate) và phải mở từng trang gốc ra đọc lại từ đầu thì thời gian chẳng giảm đi chút nào. Vì vậy tôi đã đổi ý, sửa lại yêu cầu là hệ thống không chỉ tóm tắt mà bắt buộc phải trích xuất kèm câu gốc, thời gian nhắn và link dẫn thẳng tới đúng tin nhắn/mục tài liệu đó, đồng thời làm nổi bật chỗ nào các nguồn đang nói ngược nhau để người làm kiểm tra trong vài chục giây.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Kết quả phỏng vấn nhanh theo nguyên tắc The Mom Test ở CP4 làm tôi khá bất ngờ. Trước khi đi hỏi các bạn thực tập sinh và sinh viên khác, tôi đinh ninh rằng lý do chính khiến mọi người mất thời gian là vì tài liệu ban đầu viết quá dài nên lười đọc. Nhưng khi hỏi về lần gần nhất trong tuần qua họ làm sai yêu cầu phải sửa lại, câu trả lời thực tế lại là: tài liệu ban đầu họ đọc rất kỹ, nhưng trong quá trình làm thì các anh chị hoặc các thành viên khác lại bàn bạc và chốt thay đổi logic ở trong một luồng chat (thread) trên Slack/Zalo mà không ai cập nhật lại vào tài liệu gốc hay ticket. Chính sự lệch pha giữa tài liệu gốc và các cuộc thảo luận phát sinh mới là nguyên nhân thật sự gây ra việc phải làm đi làm lại.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất đối với tôi và nhóm khi viết Problem Statement là việc xác định con số Success Metric sao cho thực tế và đặt ra Boundary (ranh giới những việc hệ thống không được làm) thật sắc nét. Viết phần câu chuyện (narrative) mô tả nỗi đau thì khá dễ, nhưng khi phải chốt con số giảm từ bao nhiêu phút xuống bao nhiêu phút và viết tiêu chí Eval để chấm đầu ra của AI là Đạt hay Không đạt, cả nhóm phải tranh luận rất kỹ. Đặc biệt ở phần Boundary, tụi tôi phải tự kiềm chế mong muốn "để AI làm hết", vạch rõ ranh giới rằng AI không được phép tự ý chọn xem thông tin nào đúng khi hai nguồn mâu thuẫn nhau, mà bắt buộc phải dừng lại gắn cờ cho con người quyết định.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu được làm lại bài lab này từ đầu, tôi sẽ chuẩn bị câu hỏi và tiến hành hỏi chuyện người thật sớm hơn, đồng thời nhờ họ mở cho xem trực tiếp một ví dụ ticket hoặc tài liệu thực tế mà họ vừa xử lý xong để quan sát tận mắt thao tác của họ thay vì chỉ nghe kể lại. Ngoài ra, tôi sẽ phản biện nhóm gắt gao hơn ở khía cạnh Usability (trải nghiệm sử dụng thực tế): một công cụ dù trích xuất thông tin tốt đến mấy nhưng nếu bắt người dùng phải rời khỏi màn hình làm việc quen thuộc (như Jira, IDE hay Notion), tự tay copy-paste từng đường link sang một giao diện khác thì chỉ sau vài ngày họ sẽ bỏ cuộc vì bất tiện.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Bài toán của nhóm xuất phát từ nỗi đau thực tế khi xử lý công việc hàng tuần (nhận ticket dự án thực tập hoặc làm đề tài nhóm): thông tin yêu cầu bị phân mảnh giữa tài liệu gốc (Confluence/Docs), thẻ công việc (Jira) và các tin nhắn thay đổi phát sinh trên kênh chat (Slack/Zalo), khiến người làm mất 35–40 phút tìm đọc cho mỗi đầu việc và vẫn có tới 30% kết quả bị trả lại vì làm theo thông tin cũ. Khi vẽ quy trình hiện tại gồm 6 bước, nhóm chỉ ra điểm nghẽn lớn nhất nằm ở bước thứ 2 và thứ 3: con người phải tự đi lục tìm từng nguồn rời rạc và đọc dò bằng mắt để xem có quyết định nào trên kênh chat đã ghi đè lên tài liệu ban đầu hay không. Từ điểm nghẽn đó, nhóm đặt ra success metric là giảm thời gian thu thập và đối chiếu ngữ cảnh trước khi làm từ 40 phút xuống dưới 10 phút, đồng thời giảm tỷ lệ phải sửa lại do hiểu lệch yêu cầu từ 30% xuống dưới 10%. Để tránh rủi ro làm sai logic của dự án, nhóm vạch ra boundary rất rõ: hệ thống tuyệt đối không được tự ý sửa đổi nội dung trên ticket/tài liệu gốc, không được tự quyết định chọn phương án nào khi thấy kênh chat và tài liệu mâu thuẫn nhau, và không được sinh ra yêu cầu không có nguồn trích dẫn. Dựa trên quy trình và boundary này, nhóm loại bỏ hướng làm Agent tự hành mà chọn mức can thiệp kết hợp giữa Rule (bắt buộc gắn đủ link tài liệu nguồn khi tạo thẻ việc) với AI Workflow (tự động đọc nội dung từ các link đã gắn, tóm tắt thành checklist yêu cầu kèm link dẫn tới câu gốc và gắn cờ cảnh báo những điểm đang mâu thuẫn để con người xác nhận). Cuối cùng, sau khi cân nhắc 4 rủi ro về Value, Usability, Feasibility và Viability, nhóm đưa ra quyết định Go có điều kiện: chỉ triển khai tích hợp sau khi kiểm thử bộ Eval trên 25–30 task thực tế đạt độ chính xác trích dẫn nguồn 100% và phát hiện đúng trên 90% các điểm thay đổi yêu cầu.

---

## 7. Tài liệu tham khảo

- Rob Fitzpatrick (2013), The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you.
- Teresa Torres (2021), Continuous Discovery Habits — Opportunity Solution Tree (OST).
- Marty Cagan (2017), Inspired: How to Create Tech Products Customers Love — 4 Big Risks (Value, Usability, Feasibility, Viability).
- Anthropic (2024), Building Effective Agents — Workflows vs. Agents.
- Google PAIR (People + AI Research), People + AI Guidebook.
- Tài liệu nội bộ khóa học K5 Level 3 Day 02: CHECKPOINTS.md, RUBRIC.md, docs/01-worksheet.md, docs/03-international-frameworks.md.
