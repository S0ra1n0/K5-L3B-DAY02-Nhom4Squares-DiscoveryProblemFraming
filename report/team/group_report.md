# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: 4Squares
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

|   # | Người đưa ra | Candidate (Job Story ngắn)                                                                 | Actor                                | Bottleneck                                                                           | Câu hỏi phản biện nhận được (ai hỏi) |
| --: | ------------ | ------------------------------------------------------------------------------------------ | ------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------ |
|   1 | Sơn          | Bóc tách checklist và cấu trúc bài lab từ tài liệu dài                                     | Sinh viên làm lab                    | Đọc tài liệu dài để rút ra các mục phải nộp; [Sơn bổ sung: số phút]                  | [điền câu hỏi thật (người hỏi)]      |
|   2 | Sơn          | Tổng hợp thông báo và lịch từ nhiều kênh (Discord, LMS, Phoenix)                           | Sinh viên                            | Lọc thông báo thật giữa nhiều tin nhắn rác trên Discord; gần như ngày nào cũng làm   | [điền câu hỏi thật (người hỏi)]      |
|   3 | Sơn          | Chuẩn bị nội dung Daily Standup từ lịch sử làm việc                                        | Thành viên làm việc nhóm             | Nhớ lại và gom việc đã làm hôm qua; lặp lại mỗi ngày làm việc nhóm                   | [điền câu hỏi thật (người hỏi)]      |
|   4 | Khoa         | Gom yêu cầu, nơi nộp, hạn nộp của một việc đang nằm rải rác ở 4–5 nền tảng                 | Sinh viên học nhiều môn/lab cùng lúc | Lục Discord/Zalo tìm thông báo thay đổi (giả định, đang bấm giờ)                     | [điền câu hỏi thật (người hỏi)]      |
|   5 | Khoa         | Rà tiến độ task cuối tuần, có task bị lệch trạng thái                                      | Người tự quản lý task                | Kiểm lại task quên cập nhật trạng thái: thêm 2–3 phút/task, ngoài 5 phút/task khi rà | [điền câu hỏi thật (người hỏi)]      |
|   6 | Khoa         | Bạn bè hỏi lại nơi nộp, format, hạn nộp                                                    | Bạn cùng lớp; Khoa là người bị hỏi   | Bạn tự tìm trên LMS/Discord không chắc nên phải nhắn hỏi                             | [điền câu hỏi thật (người hỏi)]      |
|   7 | Dũng         | Đối chiếu ngữ cảnh từ nhiều nguồn (Jira, Confluence, Slack, Log) khi xử lý ticket bug/task | Intern/dev tại công ty thực tập      | Tìm đủ yêu cầu ở nhiều nguồn; khoảng 30% PR bị trả lại do hiểu thiếu yêu cầu         | [điền câu hỏi thật (người hỏi)]      |
|   8 | Dũng         | Đọc và lập bảng tổng hợp Literature Review từ hàng chục bài báo PDF                        | Sinh viên làm đồ án/NCKH             | Chưa rõ: bước tìm bài phù hợp hay bước đọc sâu để trích bảng thông số                | [điền câu hỏi thật (người hỏi)]      |
|   9 | Dũng         | Chuẩn hóa thông tin bug report từ QA/CSKH chuyển cho team Dev                              | QA/Tester và Dev                     | Thiếu thông tin trong ticket nên phải nhắn hỏi qua lại                               | [điền câu hỏi thật (người hỏi)]      |
|  10 | Trung        | Soạn Technical Release Notes từ danh sách Pull Request                                     | Dev phụ trách release                | Đọc từng PR/diff để viết release notes: 100–115 phút mỗi 2 tuần                      | [điền câu hỏi thật (người hỏi)]      |
|  11 | Trung        | Trích thông tin cốt lõi từ bài báo khoa học cho Literature Review                          | Sinh viên nghiên cứu                 | Đọc tài liệu dài: 3–4 tiếng/tuần                                                     | [điền câu hỏi thật (người hỏi)]      |
|  12 | Trung        | Sàng lọc và gom nhóm bug report từ Discord/Google Form                                     | Người phát hành ứng dụng thử nghiệm  | Phân loại thủ công, dễ trùng ticket, thiếu thông tin môi trường                      | [điền câu hỏi thật (người hỏi)]      |

### 2.2. Cluster

| Cluster                                | Các candidate  | Pattern chung                                                                        |
| -------------------------------------- | -------------- | ------------------------------------------------------------------------------------ |
| A — Thông tin học tập rải rác          | #1, #2, #4, #6 | Sinh viên phải gom "làm gì, nộp ở đâu, hạn khi nào" từ nhiều kênh và tài liệu dài    |
| B — Bug report / ticket thiếu ngữ cảnh | #7, #9, #12    | Thông tin lỗi hoặc yêu cầu đến tay Dev thiếu hoặc lộn xộn, phải hỏi lại hoặc làm lại |
| C — Đọc tài liệu khoa học dài          | #8, #11        | Trích thông tin cốt lõi từ nhiều bài báo (Dũng và Trung đưa ra cùng một candidate)   |
| D — Tổng hợp lịch sử làm việc          | #3, #5, #10    | Gom các việc đã làm thành bản tóm tắt định kỳ (standup, release notes, tiến độ)      |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian sinh viên gom thông tin bài tập và số lần nộp sai hoặc trễ
├── Opportunity A: Thông báo của một bài nằm rải rác ở nhiều kênh (LMS, Outlook, Discord, Zalo, Phoenix)
├── Opportunity B: Thông báo thay đổi (đổi hạn, đổi format) bị trôi giữa nhiều tin nhắn, dễ bỏ sót
├── Opportunity C: Tài liệu bài lab dài, khó rút ra danh sách mục phải nộp
└── Opportunity D: Không chắc thông tin nên phải hỏi lại bạn bè
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ✗ "Bot tổng hợp thông báo từ các kênh": đây là cách giải cho Opportunity A, không phải pain.
- ✗ "Chatbot hỏi đáp môn học": đây là cách giải cho Opportunity D, không phải pain.

> [Nhóm xác nhận: OST trên viết theo cluster A. Nếu nhóm chốt candidate khác thì viết lại outcome và các opportunity.]

### 2.4. Chấm điểm shortlist (1–5)

| Candidate                                         | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain |  Tổng |
| ------------------------------------------------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | ----: |
| A — Gom thông tin bài tập từ nhiều kênh (#2 + #4) |        5 |            5 |                  5 |              4 |           5 |                                      5 |                5 | 34/35 |
| #10 — Release notes từ Pull Request               |        4 |            4 |                  4 |              4 |           3 |                                      5 |                3 | 27/35 |
| #7 — Đối chiếu ngữ cảnh ticket từ nhiều nguồn     |        4 |            4 |                  3 |              3 |           4 |                                      3 |                3 | 24/35 |

**Candidate được chọn:** Gom thông tin bài tập từ nhiều kênh

**Vì sao chọn:** Cả 4 thành viên đều là actor, gặp quy trình này hằng ngày trên LMS, Phoenix và Discord của khóa học. Nhóm bấm giờ đo được ngay và phỏng vấn được bạn học trong lớp theo The Mom Test.

**Vì sao loại các candidate còn lại:**

- **#7:** Không phải cả 4 thành viên đều thực tập ở môi trường dùng Jira + Confluence + Sentry. Dữ liệu ticket và Slack là dữ liệu nội bộ, không lấy ra làm bộ eval được.
- **#10:** Chỉ 2 tuần mới làm một lần (100–115 phút/lần). Khi phản biện, nhóm thấy phần lớn thời gian có thể giảm bằng Rule hoặc công cụ có sẵn.

**Xử lý bất đồng (nếu có):** Nhóm phân vân giữa bài toán kỹ thuật phần mềm ở doanh nghiệp và bài toán gom thông tin bài tập. Nhóm chốt bằng bảng điểm, ưu tiên bài lấy được bằng chứng thật ở CP4 và cả 4 người cùng đóng góp được ở CP5–CP6, không chọn theo đề tài "nghe kêu" hơn.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | -------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 |          |                                                    |                  |                        |                   |
|   2 |          |                                                    |                  |                        |                   |
|   3 |          |                                                    |                  |                        |                   |
|   4 |          |                                                    |                  |                        |                   |
|   5 |          |                                                    |                  |                        |                   |
|   6 |          |                                                    |                  |                        |                   |

_Điền 4–6 giả định; xóa dòng thừa._

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường                                            | Nội dung |
| ------------------------------------------------- | -------- |
| Người được hỏi (vai trò, không ghi tên thật)      |          |
| Câu nói đáng nhớ nhất (nguyên văn)                |          |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |          |
| Hiện đang xử lý bằng cách nào (workaround)?       |          |
| Mất bao lâu, bao lần?                             |          |
| Insight / opportunity rút ra                      |          |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
| ----- | ----------------: | ----------------- | ----------------- |
|       |                   |                   |                   |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------------ | ---- | ------------------------------ | --------- | --------------------- | ---------------- |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | ----- | ----- | ------ | -------------------- | ------- |
|    1 |       |       |        |                      |         |
|    2 |       |       |        |                      |         |
|    3 |       |       |        |                      |         |
|    4 |       |       |        |                      |         |
|    5 |       |       |        |                      |         |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số               | Trước | Sau (kỳ vọng) | Ghi chú |
| -------------------- | ----: | ------------: | ------- |
| Số bước              |       |               |         |
| Tổng thời gian       |       |               |         |
| Số bước thủ công     |       |               |         |
| Bottleneck chính     |       |               |         |
| Rủi ro mới phát sinh |       |               |         |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor**                                                                  |          |
| **Quy trình**                                                              |          |
| **Bottleneck**                                                             |          |
| **Impact**                                                                 |          |
| **Success Metric** (baseline → target, cách đo)                            |          |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) |          |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- ***

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) |                            |            |        |       |
| **Rule**                  |                            |            |        |       |
| **Workflow**              |                            |            |        |       |
| **Agent**                 |                            |            |        |       |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          |          |
| **Judgment** — con người cân nhắc, quyết định gì?                 |          |
| **Action** — hành động cuối cùng là gì, ai làm?                   |          |
| **Outcome** — đo kết quả bằng gì?                                 |          |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |          |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   |          |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       |                                 |
| **Quy trình**                                   |                                 |
| **Bottleneck**                                  |                                 |
| **Impact**                                      |                                 |
| **Success Metric** (baseline → target, cách đo) |                                 |
| **Boundary**                                    |                                 |
| **AI intervention point**                       |                                 |
| **Mức chọn**                                    | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra**                     |                                 |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
|        |     |     |            |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 |          |         |               |
|   2 |          |         |               |
|   3 |          |         |               |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       |                                                       |                    |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |                                                       |                    |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     |                                                       |                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     |                                                       |                    |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
