# Báo cáo cá nhân — 2A202603802_TranPhamMinhSon

## 1. Thông tin học viên

- Họ tên: Trần Phạm Minh Sơn
- MSSV: 2A202603802
- Email trường:
- Tên nhóm: 4Squares (Nhóm 4)
- Link repo nhóm: https://github.com/S0ra1n0/K5-L3B-DAY02-Nhom4Squares-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu một buổi lab mới gồm nhiều file hướng dẫn dài (README, CHECKPOINTS, RUBRIC, RULES), tôi muốn nhanh chóng nắm được checklist công việc và cấu trúc bài nộp, để bắt tay làm bài ngay mà không bị ngợp hoặc làm sót mục. | Sinh viên học lab (khoảng 30-40 bạn/lớp) | Tốn 45–60 phút đầu giờ chỉ để đọc lướt, đối chiếu 5-6 file tài liệu; chiếm ~25% thời lượng cả buổi lab (240'). |
| 2 | Lặp lại | Khi bắt đầu ngày học mới, tôi muốn nắm được toàn bộ lịch học, deadline và thông báo quan trọng trong ngày từ Discord, LMS và Phoenix ở một nơi duy nhất, để không bị trễ hạn nộp bài hoặc lỡ lịch standup. | Sinh viên (bản thân và các bạn cùng khóa) | Mỗi sáng mất 15–20 phút mở và lướt qua lại 3 nền tảng; tần suất 6-7 ngày/tuần; tâm lý FOMO sợ lỡ tin nhắn quan trọng. |
| 3 | Tốn thời gian | Khi tự học các bài lý thuyết có khối lượng kiến thức mới và nhiều tài liệu tiếng Anh học thuật, tôi muốn nhanh chóng hiểu được mối liên hệ giữa các khái niệm cốt lõi, để có thể hiểu được bài giảng trên lớp mà không bị đuối. | Sinh viên tự học | Mất 60–90 phút tự đọc trước buổi học; phải tra cứu lại thuật ngữ 4–5 lần trong suốt buổi học. |
| 4 | Lặp lại | Khi chuẩn bị cho buổi họp Daily Standup với nhóm, tôi muốn có sẵn tóm tắt ngắn gọn những việc đã làm hôm qua, việc sẽ làm hôm nay và các vướng mắc (blocker), để cập nhật cho nhóm trong 1–2 phút mà không phải ngồi nhớ lại. | Thành viên trong nhóm làm việc | Mất 10–15 phút trước giờ họp để rà lại ghi chú và tin nhắn; 5 buổi/tuần = khoảng 50–75 phút/tuần. |
| 5 | Pain từ người khác | Khi cả nhóm cùng làm bài chung trên một Git repository, tôi muốn biết rõ từng bạn đang sửa file nào và tiến độ đến đâu, để tránh bị conflict code/markdown hoặc làm trùng lặp công việc của nhau. | Cả nhóm 3–4 người | Ít nhất 1–2 lần mỗi bài lab nhóm bị merge conflict hoặc phải liên tục nhắn tin hỏi "ông đang sửa file nào đấy". |
| 6 | Tốn thời gian | Khi chuẩn bị nộp bài báo cáo cá nhân/nhóm trước hạn chót, tôi muốn đối chiếu nhanh từng mục trong bài với barem chấm điểm (Rubric), để đảm bảo không bị trừ điểm oan do thiếu tiêu chí bắt buộc. | Sinh viên trước deadline | Mất 20–30 phút ngồi dò thủ công từng tiêu chí trong Rubric; hay phát hiện thiếu mục ở 15 phút sát giờ nộp. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý giữ lại:** Ý #4 (Tóm tắt Standup) và Ý #5 (Đồng bộ tiến độ Git trong nhóm) vì đây là trải nghiệm thật khi làm việc nhóm trong các buổi lab gần đây.
- **Ý bỏ qua:** AI gợi ý ý tưởng *"Trợ lý ảo tự động quản lý và giải quyết toàn bộ bài tập lab"* -> **Bỏ vì:** Quá rộng, không có quy trình cụ thể, vi phạm nguyên tắc liêm chính học thuật và biến AI thành giải pháp thay vì tập trung vào nỗi đau quy trình.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Bóc tách checklist & cấu trúc bài lab từ tài liệu dài (#1) | Nỗi đau diễn ra ngay lập tức mỗi buổi lab; quy trình hiện tại rõ ràng; đo đạc được thời gian tiết kiệm cụ thể. | Chưa chắc mức độ can thiệp của AI có làm sinh viên ỷ lại, lười đọc kỹ tài liệu gốc hay không. |
| 2 | Tổng hợp thông báo & lịch trình đa kênh (Discord, LMS, Phoenix) (#2) | Tần suất lặp lại hàng ngày (hầu như ngày nào cũng làm); ảnh hưởng trực tiếp đến việc nộp bài và họp hành. | Dữ liệu từ Discord quá nhiều tin nhắn rác, khó bóc tách nếu không có quy chuẩn phân loại từ đầu. |
| 3 | Chuẩn bị nội dung Daily Standup từ lịch sử làm việc (#4) | Thao tác lặp lại đều đặn mỗi ngày làm việc nhóm; quy trình ngắn gọn, dễ triển khai Rule/Workflow đơn giản. | Giá trị mang lại ở mức vừa phải, chưa phải nỗi đau quá lớn khiến nhóm bị đình trệ. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một buổi lab mới gồm nhiều file hướng dẫn dài (README, CHECKPOINTS, RUBRIC, RULES), tôi muốn nhanh chóng nắm được checklist công việc và cấu trúc bài nộp, để bắt tay làm bài ngay mà không bị ngợp hoặc làm sót mục. |
| Actor | Sinh viên tham gia buổi lab (như lớp L3B) |
| Thời điểm / bối cảnh | 15–30 phút đầu tiên của buổi lab 4 tiếng |
| Quy trình hiện tại (3–7 bước) | 1. Mở và đọc lướt README.md để hiểu đề bài (10')<br>2. Đọc file CHECKPOINTS.md nắm các mốc thời gian (10')<br>3. Mở file RUBRIC.md và RULES.md xem điều kiện đạt/rớt (10')<br>4. Đối chiếu các file để tự lập bảng checklist công việc cần nộp (15')<br>5. Tạo file và dựng khung bài làm cá nhân (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 (Đối chiếu và tự lập checklist công việc: mất 15–20 phút, rất dễ đọc sót vì thông tin nằm rải rác ở 4-5 file khác nhau) |
| Impact (nếu không giải thì sao) | Mất 45–60 phút (chiếm 20–25% thời gian làm lab) chỉ để định hướng; khởi đầu chậm trễ kéo theo các checkpoint sau bị cuống và trễ hạn. |
| Success metric (baseline → target) | Thời gian đọc hiểu và lập checklist rút ngắn từ **50 phút xuống dưới 15 phút**; tỷ lệ làm thiếu mục yêu cầu = 0%. |
| Phương án không dùng AI | Giảng viên/TA cung cấp sẵn một bảng Checklist chuẩn (Master Checklist) tóm tắt 1 trang ở đầu repo. |
| Giả thuyết về AI (nếu có) | Sử dụng AI để trích xuất ma trận công việc từ bộ tài liệu markdown (Checkpoint - Việc cần làm - File cần sửa - Tiêu chí chấm); sinh viên review checklist trước khi thực hiện. |
| Cảm nhận nhanh | **Workflow** (quy trình có các bước định sẵn, AI hỗ trợ trích xuất và map thông tin, con người kiểm tra lại). |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 50 phút đầu giờ lab

[1. Đọc README: 10'] → [2. Đọc CHECKPOINTS: 10'] → [3. Đọc RUBRIC & RULES: 10']
→ [4. Đối chiếu & tự lập checklist: 15'] ← BOTTLENECK (dễ sót, ngợp thông tin)
→ [5. Tạo file & khung bài: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu ngày học mới, tôi muốn nắm được toàn bộ lịch học, deadline và thông báo quan trọng trong ngày từ Discord, LMS và Phoenix ở một nơi duy nhất, để không bị trễ hạn nộp bài hoặc lỡ lịch standup. |
| Actor | Sinh viên theo học chương trình |
| Thời điểm / bối cảnh | 8h sáng hàng ngày hoặc trước ca học |
| Quy trình hiện tại (3–7 bước) | 1. Đăng nhập LMS kiểm tra mục To-do / Bài tập mới (5')<br>2. Vào hệ thống Phoenix kiểm tra lịch học, thông báo lớp (5')<br>3. Mở Discord lướt các channel #announcement, #general, #standup (10')<br>4. Tự ghi chú lại lịch họp và deadline vào sổ/app to-do (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 (Lướt Discord lọc tin quan trọng lẫn giữa các tin nhắn thảo luận: mất 10 phút, tâm lý sợ sót thông báo) |
| Impact (nếu không giải thì sao) | Mất 25 phút mỗi ngày (~125–150 phút/tuần); thỉnh thoảng bỏ sót các thay đổi lịch họp đột xuất hoặc deadline phụ. |
| Success metric (baseline → target) | Thời gian kiểm tra giảm từ **25 phút xuống 5 phút mỗi sáng**; số lần bỏ sót thông báo = 0. |
| Phương án không dùng AI | Quy ước chỉ thông báo qua email hoặc kênh LMS chính thống; bật thông báo mention (@here/@everyone) trên Discord. |
| Giả thuyết về AI (nếu có) | Bot quét các channel chính thức, lọc các tin có tính chất thông báo/deadline và tổng hợp thành 1 bản tin điểm tin sáng ngắn gọn. |
| Cảm nhận nhanh | **Rule** (chỉ cần lọc theo role/kênh thông báo chính) hoặc **Workflow** nhẹ (phân loại tin khẩn). |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 25 phút mỗi sáng

[1. Check LMS: 5'] → [2. Check Phoenix: 5'] 
→ [3. Lướt các kênh Discord: 10'] ← BOTTLENECK (tin rải rác, sợ bỏ sót)
→ [4. Note lịch/deadline: 5']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị cho buổi họp Daily Standup với nhóm, tôi muốn có sẵn tóm tắt ngắn gọn những việc đã làm hôm qua, việc sẽ làm hôm nay và các vướng mắc (blocker), để cập nhật cho nhóm trong 1–2 phút mà không phải ngồi nhớ lại. |
| Actor | Thành viên nhóm làm lab |
| Thời điểm / bối cảnh | 10–15 phút trước giờ họp standup hàng ngày |
| Quy trình hiện tại (3–7 bước) | 1. Ngồi nhớ lại hôm qua mình đã làm những gì (3')<br>2. Mở Git commit log hoặc file bài làm để kiểm tra các phần đã chỉnh sửa (5')<br>3. Soạn 3 gạch đầu dòng: Đã làm - Sắp làm - Khó khăn (5')<br>4. Gửi vào kênh chat nhóm hoặc đọc trong buổi họp (2') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3 (Rà lại lịch sử commit/file để diễn đạt thành câu cập nhật ngắn gọn: mất 10 phút) |
| Impact (nếu không giải thì sao) | Tốn 15 phút mỗi ngày (~75 phút/tuần); khi vào họp hay nói ngắc ngứ, lan man hoặc quên mất khó khăn đang gặp. |
| Success metric (baseline → target) | Thời gian soạn standup giảm từ **15 phút xuống 2–3 phút**; cập nhật súc tích, rõ ràng hơn. |
| Phương án không dùng AI | Đặt thói quen ghi chú 1 dòng vào file cá nhân ngay sau khi hoàn thành mỗi task trong ngày. |
| Giả thuyết về AI (nếu có) | AI đọc danh sách commit git gần nhất và tự đề xuất bản nháp 3 dòng standup; người dùng chỉ cần duyệt hoặc sửa nhẹ. |
| Cảm nhận nhanh | **Rule** hoặc **Workflow**. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 15 phút trước giờ standup

[1. Nhớ lại task cũ: 3'] 
→ [2. Đọc Git log & file đã sửa: 5'] → [3. Soạn nháp 3 ý: 5'] ← BOTTLENECK
→ [4. Gửi cập nhật: 2']
```

### Card muốn pitch nhất

- **Card số:** Card #1 (Bóc tách checklist & cấu trúc bài lab từ tài liệu dài).
- **Vì sao:** Đây là vấn đề cấp thiết nhất mà bất kỳ học viên nào trong lớp cũng trải qua ngay lúc bắt đầu buổi lab. Vấn đề có actor rõ, quy trình hiện tại đo lường được bằng phút, và có thể giải quyết thực tế mà không cần hệ thống quá phức tạp.
- **Câu hỏi muốn nhóm phản biện:** *"Nếu đã có bảng checklist tóm tắt, liệu sinh viên có bị ỷ lại mà bỏ qua các quy định chi tiết trong file RULES.md hoặc các tiêu chí chấm điểm nâng cao trong RUBRIC.md không?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline 50 phút có thể chỉ đúng với người mới đọc lần đầu, các buổi lab sau thời gian đọc có thể giảm đi. | Đồng ý một phần | Giữ nguyên baseline 45-50 phút cho các buổi lab đầu/kỳ mới vì tài liệu mỗi ngày đều có rubric và yêu cầu riêng biệt; bổ sung tiêu chí đo lường tỷ lệ sót mục bài nộp. |
| Nếu dùng AI để tóm tắt đề, sinh viên có nguy cơ bỏ qua các chi tiết quan trọng (hallucination của AI khi đọc rubric). | Rất đồng ý | Đặt rõ boundary (ranh giới): AI chỉ hỗ trợ trích xuất cấu trúc và checklist; sinh viên bắt buộc phải là người đối chiếu chéo với file RUBRIC gốc trước khi nộp. |
| Đề xuất ban đầu có xu hướng nghĩ ngay đến "Làm một Chatbot trợ lý lab" (solution-first). | Đồng ý | Đã sửa lại theo hướng Workflow: chỉ can thiệp vào bước trích xuất checklist, giữ nguyên các bước đọc hiểu và ra quyết định của con người. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Problem Card #1 (Bóc tách checklist bài lab từ tài liệu dài) trong 2 phút với các số liệu thật (50 phút đọc hiểu đầu giờ). | Nhóm thấy đây là nỗi đau chung của cả 4 thành viên ngay trong buổi lab hôm nay. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: *"Nếu công cụ AI tóm tắt lại yêu cầu từ Slack và Confluence cho bạn, bạn có dám tin hoàn toàn vào bản tóm tắt đó để ngồi code luôn mà không mở link gốc ra đọc lại không?"* | Giúp nhóm bổ sung yêu cầu bắt buộc vào cơ chế hiển thị (Usability) và tiêu chí Eval: Hệ thống không chỉ viết đoạn tóm tắt chung chung mà mỗi gạch đầu dòng yêu cầu phải đính kèm trích dẫn nguyên văn và link nhảy thẳng tới đúng dòng tin nhắn Slack hoặc mục trên Confluence để người làm kiểm chứng trong 30 giây. |
| Nhận phản biện | Câu hỏi tôi nhận được: *"Với bài toán quản lý công việc nhóm và nhắc lịch của bạn, nếu không dùng AI mà chỉ cài đặt một rule tự động gửi thông báo trên Google Calendar/Slack hoặc bắt buộc điền form cố định thì đã giải quyết được 80% vấn đề chưa?"* | Tôi đã sửa gì: Thêm bước kiểm tra chéo (Human-in-the-loop) vào quy trình tương lai; AI chỉ gợi ý, người dùng tick xác nhận. |
| Gom cluster / cây OST | Đóng góp 3 candidate cá nhân vào 2 cluster: "Xử lý thông tin học tập rời rạc" và "Giao tiếp & Đồng bộ nhóm". | Nhóm xây dựng được cây OST với outcome trọng tâm: "Giảm thời gian định hướng đầu giờ lab mà vẫn đảm bảo nộp đúng yêu cầu". |
| Chọn candidate problem | Cùng nhóm chấm điểm shortlist trên 7 tiêu chí theo thang điểm 1–5; bảo vệ lập luận cho Card #1. | Candidate "Checklist bài lab" đạt điểm cao nhất (33/35) và được chọn làm bài toán chính thức của nhóm. |
| Kiểm chứng / research | Phỏng vấn nhanh 2 bạn học viên ở nhóm bên cạnh theo nguyên tắc The Mom Test về thời gian đọc tài liệu lab đầu giờ. | Thu được bằng chứng thực tế: cả 2 bạn đều mất 40–50 phút và từng bị trừ điểm ở Day 01 do sót mục nộp. |
| Quy trình nhóm | Phụ trách phác thảo quy trình Tương lai (To-be) gồm 4 bước và lập bảng so sánh Before/After. | Chỉ ra chính xác AI can thiệp ở bước phân tích markdown và tạo checklist; tiết kiệm 35 phút cho mỗi buổi lab. |
| Problem Statement | Cùng nhóm thảo luận và viết 6 trường của Problem Statement v0 và v1, đặc biệt là phần Boundary. | Boundary được siết chặt: "AI không viết hộ nội dung bài làm, chỉ trích xuất cấu trúc và checklist công việc". |
| Mức can thiệp AI | Phân tích và phản biện vì sao không dùng Agent mà chỉ dùng Workflow. | Thuyết phục cả nhóm chọn mức can thiệp là **Workflow** (quy trình định sẵn có AI hỗ trợ) để giảm thiểu chi phí và lỗi hallucination. |
| Quyết định | Tham gia đánh giá 4 rủi ro (Value, Usability, Feasibility, Viability) và xây dựng ngưỡng dừng (Exit criteria). | Nhóm thống nhất ra quyết định **Go (phạm vi nhỏ)** kèm điều kiện đo lường sau 2 buổi lab tiếp theo. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI cấu trúc lại cảm nghĩ ban đầu thành các câu Job Story chuẩn và gợi ý thêm góc nhìn. | Giúp chuẩn hóa cấu trúc "Khi... tôi muốn... để..." rõ ràng, tránh lẫn lộn giải pháp. | AI ban đầu đề xuất làm "Trợ lý AI toàn năng quản lý bài tập", vi phạm nguyên tắc bài lab và không thực tế. | Loại bỏ các ý tưởng quá viển vông, chỉ giữ lại các vấn đề sát với thực tế học tập hàng ngày. |
| CP2 Problem Card | Đóng vai PM hoài nghi để phản biện Card #1, tìm lỗ hổng trong quy trình. | Chỉ ra nguy cơ sinh viên bị ỷ lại vào AI và nguy cơ AI tóm tắt thiếu sót tiêu chí Rubric. | AI gợi ý giải pháp tự động hóa hoàn toàn bằng Agent. | Đã từ chối mức Agent, kéo về mức Workflow với nguyên tắc Human-in-the-loop (con người kiểm tra chéo). |
| CP4 Research | Dùng Perplexity/Gemini tìm kiếm các công cụ và bài toán tương tự về trích xuất checklist từ văn bản dài (PRD to Task). | Tìm được các mẫu prompt và pattern phổ biến trong việc phân tích tài liệu kỹ thuật sang Action Item. | AI đề xuất các giải pháp enterprise phức tạp (như tích hợp Jira Enterprise/ServiceNow) không phù hợp sinh viên. | Tự lọc lại và chỉ chọn case study đơn giản: markdown parser kết hợp LLM extraction. |
| CP5 Quy trình | Nhờ AI chuyển đổi bản thảo quy trình dạng văn bản sang cú pháp sơ đồ Mermaid. | Tiết kiệm thời gian căn chỉnh cú pháp Mermaid flow diagram. | AI tự ý chèn thêm các bước "AI tự động nộp bài", làm sai lệch quy trình mà nhóm đã thống nhất. | Xóa bỏ các bước tự động hóa sai lệch, giữ đúng 4 bước nhóm đã thiết kế. |
| CP5–6 Problem Statement | Prompt AI đóng vai người chấm thi khó tính, chỉ ra các từ ngữ mơ hồ trong Problem Statement. | Phát hiện ra cụm từ "giúp làm bài nhanh hơn" là không đo được (bad metric). | AI cố gắng viết lại toàn bộ Problem Statement theo văn phong quảng cáo thương mại. | Chỉ nhặt ra điểm yếu về mặt câu chữ, sau đó cùng nhóm tự viết lại Success Metric với con số đo lường cụ thể (từ 50' xuống 15'). |
| CP6 Mức can thiệp / quyết định | Tham khảo góc nhìn của AI về 4 rủi ro của Marty Cagan khi áp dụng cho bài toán này. | Đưa ra gợi ý tốt về rủi ro Usability: người dùng lười kiểm tra lại checklist. | Đánh giá rủi ro Feasibility quá cao (cho rằng bài này rất khó làm kỹ thuật). | Tôi điều chỉnh lại: Về mặt kỹ thuật trích xuất Markdown rất đơn giản (Feasibility Thấp), rủi ro lớn nhất thực ra nằm ở Usability (thói quen người dùng). |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**  
Khi nghe các bạn trong nhóm pitch, tôi nhận ra mỗi người đều có những góc nhìn và sự ức chế rất riêng dù cùng chung một môi trường học. Có bạn tập trung vào việc giao tiếp nhóm trên Discord bị trôi tin nhắn, có bạn lại gặp khó khăn ở khâu merge code trên GitHub. Điều này giúp tôi hiểu rằng một vấn đề nhìn bề ngoài tưởng như nhỏ với mình lại có thể là nút thắt cổ chai rất lớn của người khác. Quan trọng hơn, việc lắng nghe giúp tôi học được cách bóc tách: một vấn đề tốt không phải là vấn đề nghe "đao to búa lớn", mà là vấn đề có bối cảnh thật, actor cụ thể và đo lường được bằng thời gian lãng phí hàng tuần.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**  
Nhóm tôi bị "solution-first" ngay từ 10 phút đầu tiên của buổi thảo luận. Khi vừa nhắc đến chuyện đọc tài liệu lab tốn thời gian, một bạn đã ngay lập tức đề xuất: "Hay là mình build một con Agent tự động đọc đề bài rồi tự tạo repo và viết sẵn code mẫu luôn đi". Lúc đó cả nhóm suýt bị cuốn theo ý tưởng công nghệ hấp dẫn này. May mắn là tôi đã nhắc lại nguyên tắc trong RULES.md: "Chưa chỉ ra được bước nào nghẽn thì chưa chọn công nghệ". Chúng tôi dừng lại, quay về vẽ quy trình hiện tại gồm 5 bước của sinh viên. Khi thấy bước nghẽn thật sự chỉ là việc đối chiếu để lập checklist (mất 15–20 phút), nhóm nhận ra việc xây một Agent toàn năng vừa vi phạm quy chế thi, vừa phức tạp không cần thiết, trong khi chỉ cần một workflow đơn giản là đã giải quyết được tận gốc nỗi đau.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**  
Có, tôi đã thay đổi một phần rất cốt lõi trong giải pháp của mình. Ban đầu ở Problem Card #1, tôi từng nghĩ AI sẽ tự động tạo luôn khung bài làm và điền sẵn các đầu mục cần nộp cho sinh viên. Tuy nhiên, một bạn trong nhóm đã phản biện rất gắt: *"Nếu làm sẵn hết như vậy thì sinh viên sẽ chỉ nhìn vào khung đó mà không thèm đọc file RUBRIC.md, đến lúc người ta đổi tiêu chí chấm thì rớt chắc!"*. Lời phản biện này đánh trúng điểm yếu chí mạng về mặt Usability. Tôi hoàn toàn đồng ý và đã chủ động sửa lại quy trình: AI chỉ dừng lại ở việc trích xuất bảng checklist ma trận; sinh viên bắt buộc phải có một bước đọc đối chiếu với Rubric gốc và tự tay xác nhận (Human-in-the-loop) trước khi bắt tay làm bài.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**  
Điều làm tôi bất ngờ nhất khi phỏng vấn nhanh 2 bạn học viên lớp bên cạnh là: họ không hề than phiền về việc tài liệu quá khó hiểu về mặt học thuật, mà họ ức chế nhất là **tài liệu quá phân mảnh**. Một bạn chia sẻ rằng bạn ấy đã từng bị trừ 20% điểm ở bài lab trước chỉ vì tiêu chí nộp bài nằm ở dòng cuối cùng của file RULES.md mà bạn ấy không nhìn thấy. Điều này chứng minh giả định ban đầu của nhóm là hoàn toàn chính xác: "Nỗi đau không nằm ở việc sinh viên không biết làm bài, mà nằm ở chi phí nhận thức (cognitive load) quá lớn khi phải mở cùng lúc 4-5 file markdown chỉ để biết mình cần nộp những gì".

**6.5. Điều khó nhất khi viết Problem Statement là gì?**  
Điều khó nhất đối với tôi và nhóm là việc viết **Success Metric** và **Boundary**. Khi mới viết v0, nhóm thường viết theo cảm tính như "giúp sinh viên làm bài nhanh hơn", "tiết kiệm thời gian". Nhưng khi bị ép phải có Baseline, Target và Cách đo lường cụ thể, nhóm đã phải ngồi tranh luận rất lâu để thống nhất con số: từ 50 phút xuống dưới 15 phút, và tỷ lệ sót mục nộp là 0%. Ngoài ra, việc xác định Boundary (ranh giới những gì AI KHÔNG được phép làm) cũng đòi hỏi tư duy rất kỷ luật để giữ cho giải pháp không vi phạm tính liêm chính học thuật.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**  
Nếu được làm lại từ đầu buổi lab, tôi sẽ chủ động yêu cầu nhóm bấm giờ đo đạc thực tế ngay từ những phút đầu tiên thay vì ước lượng bằng trí nhớ. Ngoài ra, tôi sẽ phản biện nhóm mạnh mẽ hơn ở phần khảo sát thị trường (Research): nhóm nên tìm hiểu sâu hơn về các công cụ quản lý dự án học tập chuyên dụng thay vì chỉ tìm các bài viết chung chung trên mạng. Tôi cũng sẽ thúc đẩy nhóm chốt ứng viên sớm hơn 10 phút để có thêm thời gian trau chuốt sơ đồ quy trình tương lai.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.  
Bài toán của nhóm xuất phát từ **nỗi đau có thật** của sinh viên khi mất tới 50 phút đầu mỗi buổi lab chỉ để đọc và bóc tách yêu cầu từ 5-6 file tài liệu dài, dẫn đến nguy cơ bỏ sót mục nộp bài. Khi mổ xẻ **quy trình hiện tại**, bước nghẽn lớn nhất được xác định là khâu đối chiếu chéo giữa Checkpoints và Rubric để tự lập danh sách việc cần làm. **Success metric** được đặt ra rõ ràng: rút ngắn thời gian chuẩn bị từ 50 phút xuống dưới 15 phút và đưa tỷ lệ sót mục nộp về 0%. Để đảm bảo tính trung thực và tránh việc sinh viên ỷ lại, **boundary** được thiết lập nghiêm ngặt: AI tuyệt đối không can thiệp viết nội dung bài làm, chỉ trích xuất cấu trúc và bắt buộc con người phải tự kiểm tra chéo trước khi thực hiện. Từ bài toán có cấu trúc rõ ràng và độ mơ hồ thấp này, nhóm xác định **mức can thiệp tối ưu là Workflow** (quy trình các bước tuần tự có AI hỗ trợ) thay vì dùng Agent tự trị phức tạp và tốn kém. Cuối cùng, nhóm ra quyết định **Go (ở phạm vi nhỏ)** vì giá trị mang lại rõ ràng, khả thi về mặt kỹ thuật, kèm theo ngưỡng dừng đo lường sau 2 tuần thử nghiệm thực tế.

---

## 7. Tài liệu tham khảo

1. Design Council (UK) — *Double Diamond Design Process*.
2. Rob Fitzpatrick — *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you*.
3. Intercom — *Jobs-to-be-Done (JTBD) & Job Story Framework*.
4. Marty Cagan — *Inspired: How to Create Tech Products Customers Love* (4 Product Risks: Value, Usability, Feasibility, Viability).
5. Google PAIR (People + AI Research) — *People + AI Guidebook: Augment vs Automate*.
6. Anthropic — *Building Effective Agents & Workflows Guide* (2024).
7. Tài liệu hướng dẫn môn học: *K5 · L3 · Day 02 — Discovery & Problem Framing* (VinUni).
