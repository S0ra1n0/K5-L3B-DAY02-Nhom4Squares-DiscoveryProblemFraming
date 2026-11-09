# Báo cáo cá nhân — MSSV_HoTen

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
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận được bộ hồ sơ đề nghị thanh toán từ các phòng ban gửi về cuối tháng, tôi muốn đối chiếu nhanh và chính xác thông tin giữa Hợp đồng (PDF scan), Biên bản nghiệm thu và Hóa đơn đỏ (XML/PDF), để kịp duyệt lệnh chi đúng SLA mà không bị xuất toán khi kiểm toán nội bộ. | Chuyên viên Kế toán thanh toán (AP) (5 người), nhân viên các phòng ban (Requester), Nhà cung cấp. | Mỗi kế toán xử lý 30–40 bộ hồ sơ/ngày (cuối tháng 60 bộ). Mất 15–20 phút/bộ để đọc và dò số bằng mắt. Khoảng 25% hồ sơ bị trả lại trên hệ thống SAP/Base vì lệch số liệu hoặc thiếu điều khoản, làm trễ hạn thanh toán 2–3 ngày. |
| 2 | Lặp lại | Khi nhân viên mới hoặc nhân viên các phòng ban nhắn tin hỏi về quy trình (tạm ứng, công tác phí, nghỉ phép, bảo hiểm), tôi muốn họ có câu trả lời đúng theo quy chế hiện hành ngay lập tức, để không bị ngắt quãng công việc chuyên môn hàng ngày. | Chuyên viên HRBP & Admin (4 người), toàn bộ nhân viên tập đoàn (~500 người). | Mỗi ngày HRBP nhận 25–30 tin nhắn Teams hỏi đi hỏi lại cùng các câu hỏi cơ bản (mất 3–5 phút/tin nhắn để tìm link quy định và trả lời, tổng mất ~1.5 giờ/ngày). Tài liệu quy chế để trên SharePoint có tới hơn 40 file PDF rời rạc. |
| 3 | Tốn thời gian | Khi kết thúc tuần làm việc vào chiều thứ Sáu, tôi muốn tổng hợp tiến độ, các điểm nghẽn (blockers) và chỉ số KPI của 6 dự án đang chạy từ Jira, Excel và biên bản họp, để gửi báo cáo tuần (Weekly Report) cho Ban Giám đốc trước 17h00. | Quản lý dự án (PM / PMO) (8 người), Trưởng các bộ phận liên quan. | Chiều thứ Sáu nào PM cũng mất 2–2.5 tiếng chỉ để mở từng tab Jira, copy-paste số liệu sang slide PowerPoint và nhắn tin giục các team cập nhật trạng thái. Lịch sử gửi email báo cáo thường xuyên bị trễ sang tối thứ Sáu. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi phòng Mua hàng (Procurement) hoặc Kinh doanh gửi hợp đồng mẫu của đối tác sang yêu cầu rà soát gấp, tôi muốn phát hiện nhanh các điều khoản bất lợi (phạt vi phạm, giới hạn trách nhiệm, bảo mật, luật áp dụng), để phản hồi chỉnh sửa kịp tiến độ ký kết. | Chuyên viên Pháp chế (Legal Executive) (3 người), bộ phận Mua hàng & Sales. | Trung bình 10–15 hợp đồng/tuần, mỗi hợp đồng dài 15–40 trang. Pháp chế mất 45–60 phút/hợp đồng để đọc dò từng dòng. SLA cam kết là 2 ngày nhưng thực tế thường kéo dài 4–5 ngày làm việc, Sales phàn nàn nhiều trên nhóm chat chung. |
| 5 | Lặp lại | Khi nhân viên gặp sự cố CNTT (quên mật khẩu ERP, lỗi VPN, xin cấp quyền truy cập folder, cài phần mềm), tôi muốn phân loại đúng mức độ ưu tiên và hướng dẫn họ tự xử lý các lỗi cơ bản trước, để đội IT chỉ tập trung vào các sự cố hạ tầng nghiêm trọng. | Nhân viên IT Helpdesk (4 người), nhân viên toàn công ty. | Hệ thống ghi nhận 150–200 tickets/tuần. 60% trong số đó là các lỗi lặp lại (reset password, cấu hình lại mạng/máy in). IT mất trung bình 10 phút/ticket để hỏi lại thông tin cấu hình máy và chụp màn hình lỗi vì người dùng mô tả rất chung chung. |
| 6 | Pain từ người khác | Khi đại lý hoặc khách hàng B2B gửi email/Zalo phàn nàn về việc giao hàng thiếu, hỏng hóc hoặc sai chiết khấu, tôi muốn gom đủ thông tin (mã đơn hàng, lịch sử kho, chính sách bán hàng) trong một màn hình, để phản hồi phương án xử lý trong vòng 2 giờ. | Chuyên viên CSKH B2B (6 người), Kế toán công nợ, Kho vận. | Mỗi ngày có 20–30 ca khiếu nại. CSKH phải nhắn tin hỏi qua lại 3 phòng ban (Sales, Kho, Kế toán) mất trung bình 4–6 tiếng mới có đủ thông tin trả lời khách. Tỷ lệ khách hàng phàn nàn vì phản hồi chậm chiếm 35% khảo sát quý trước. |
| 7 | Tốn thời gian | Khi cần mua sắm thiết bị hoặc thuê dịch vụ mới có giá trị trên 50 triệu đồng, tôi muốn bóc tách và so sánh nhanh 3 bảng báo giá (Quotation) từ 3 nhà cung cấp có định dạng hoàn toàn khác nhau, để lập bảng so sánh trình phê duyệt mua sắm. | Chuyên viên Mua hàng (Procurement) (5 người). | Mỗi tuần một chuyên viên làm 5–7 tờ trình mua sắm. Các nhà cung cấp gửi báo giá bằng PDF/Excel với tên gọi hạng mục, đơn vị tính, điều kiện bảo hành và thuế VAT viết khác nhau. Mất 40–50 phút/lần để gõ lại vào 1 file Excel chuẩn. |
| 8 | Pain từ người khác | Khi bước vào đợt tuyển dụng cao điểm đầu quý, tôi muốn sàng lọc nhanh hàng trăm CV ứng viên dựa trên các tiêu chí bắt buộc của JD (số năm kinh nghiệm thực tế, kỹ năng chuyên môn, mức lương kỳ vọng), để chuyển danh sách ứng viên phù hợp cho Hiring Manager trong 48 giờ. | Chuyên viên Tuyển dụng (TA) (5 người), Hiring Managers các phòng ban. | Một vị trí mở ra nhận trung bình 150–200 CV. TA mất 2–3 phút/CV (tổng 6–8 tiếng/vị trí) để mở đọc thủ công. Hiring Manager thường xuyên phàn nàn CV gửi sang chưa sát yêu cầu (khoảng 40% CV vòng đầu bị loại ngay khi Manager đọc lại). |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Giữ lại: Ý tưởng về bài toán so sánh báo giá của bộ phận Mua hàng (#7) và phân loại ticket IT Helpdesk (#5) vì khi đối chiếu với thực tế tại tập đoàn, đây là hai việc tốn nhiều thao tác copy-paste lặp lại và có sẵn dữ liệu lịch sử trên hệ thống để kiểm chứng.
- Bỏ đi: Các gợi ý của AI về "Dự báo biến động dòng tiền vĩ mô cho CFO" và "Tự động đánh giá năng lực nhân sự cuối năm" vì quá vĩ mô, bản thân không phải là actor trực tiếp xử lý hàng ngày và không thể tiếp cận người thật hay dữ liệu thật để kiểm chứng trong phạm vi bài lab.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 — Đối chiếu hồ sơ thanh toán nhà cung cấp (3-way matching) | Nỗi đau diễn ra hàng ngày với tần suất lớn (30–60 bộ/ngày). Quy trình có đầu vào/đầu ra cụ thể, dễ đo lường thời gian xử lý và tỷ lệ lỗi trả hồ sơ. | Chưa chắc tỷ lệ 25% hồ sơ bị trả lại chủ yếu do lỗi thiếu file cơ bản hay do sai lệch ngữ nghĩa/số tiền phức tạp trong hợp đồng. |
| 2 | #4 — Rà soát điều khoản rủi ro trong hợp đồng đối tác | Tốn nhiều thời gian đọc hiểu văn bản dài (45–60 phút/hợp đồng), gây nghẽn trực tiếp đến tiến độ ký kết của khối Kinh doanh và Mua hàng. | Chưa rõ bộ phận Pháp chế đã có sẵn bộ Checklist/Playbook các điều khoản chuẩn bằng văn bản hay tất cả đang nằm trong kinh nghiệm ngầm của từng chuyên viên. |
| 3 | #7 — Bóc tách và lập bảng so sánh 3 báo giá (Quotation Comparison) | Tác vụ thuần túy thủ công, lặp đi lặp lại việc đọc file PDF không đồng nhất và gõ lại vào Excel. Rất phù hợp để chuẩn hóa quy trình. | Cần kiểm chứng xem tần suất 5–7 tờ trình/tuần có xảy ra đều ở mọi chuyên viên mua hàng không hay chỉ tập trung vào một số nhóm ngành hàng nhất định. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được bộ hồ sơ đề nghị thanh toán từ các phòng ban gửi về hệ thống, tôi muốn kiểm tra tính đầy đủ và đối chiếu chéo thông tin (số tiền, điều khoản đợt thanh toán, thông tin pháp nhân) giữa Hợp đồng, Biên bản nghiệm thu và Hóa đơn điện tử một cách nhanh chóng, để duyệt thanh toán đúng hạn SLA mà không để lọt sai sót tài chính. |
| Actor | Chuyên viên Kế toán thanh toán (AP Specialist) — người trực tiếp kiểm duyệt; Nhân viên các phòng ban (Requester) — người nộp hồ sơ. |
| Thời điểm / bối cảnh | Diễn ra hàng ngày, đặc biệt cao điểm vào 5 ngày cuối tháng và cuối quý khi các phòng ban dồn dập đẩy hồ sơ thanh toán để chốt chi phí. |
| Quy trình hiện tại (3–7 bước) | 1. Tải 4–5 file chứng từ (Đề nghị thanh toán, Hợp đồng PDF scan, Biên bản nghiệm thu, Hóa đơn PDF + XML) từ hệ thống về máy.<br>2. Kiểm tra tính hợp lệ của Hóa đơn và Mã số thuế trên cổng Thuế.<br>3. Mở song song các file để đọc và dò bằng mắt (3-way matching): tên công ty, nội dung, số tiền, điều khoản chia đợt thanh toán trong hợp đồng.<br>4. Kiểm tra mã ngân sách (Cost Center) trên Excel/ERP.<br>5. Nếu sai lệch/thiếu: chụp màn hình, viết lý do trả lại hồ sơ cho Requester sửa. Nếu khớp: nhập liệu vào ERP để trình ký lệnh chi. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 (Đọc hợp đồng scan dài 10–30 trang và đối chiếu chéo bằng mắt — mất 10–12 phút/bộ) và Bước 5 (Trả hồ sơ và kiểm tra lại từ đầu khi Requester nộp lại — mất thêm 5–8 phút/bộ). Tổng thời gian xử lý trung bình 18 phút/bộ hồ sơ. |
| Impact (nếu không giải thì sao) | Kế toán AP phải tăng ca liên tục cuối tháng, mỏi mắt dẫn đến rủi ro nhìn nhầm (khoảng 1–2% hồ sơ bị thanh toán sai số tiền hoặc sai điều khoản); 25% hồ sơ bị trả đi trả lại làm trễ hạn thanh toán 2–3 ngày, gây phàn nàn từ nhà cung cấp. |
| Success metric (baseline → target) | Thời gian kiểm tra 1 bộ hồ sơ giảm từ 18 phút → dưới 5 phút/bộ; Tỷ lệ hồ sơ bị trả lại do lỗi thiếu/sai thông tin từ phòng ban giảm từ 25% → dưới 8%. |
| Phương án không dùng AI | Bắt buộc đính kèm đủ trường/file trên Form hệ thống mới cho bấm Submit; ban hành checklist tự kiểm tra cho các phòng ban; dùng script/code thường đọc thẳng file XML của hóa đơn điện tử để lấy số tiền và MST. |
| Giả thuyết về AI (nếu có) | Kết hợp Rule (đọc XML hóa đơn + bắt buộc trường dữ liệu) với AI Workflow (OCR + LLM đọc Hợp đồng PDF scan, tự động trích xuất Điều khoản thanh toán kèm số trang và lập bảng đối chiếu song song với Hóa đơn để chỉ ra điểm lệch cho kế toán duyệt). |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Phòng ban nộp hồ sơ] -> [1. Kế toán tải 4-5 file về máy] -> [2. Tra cứu MST & Hóa đơn trên web Thuế] -> [3. Đọc Hợp đồng scan (10-30 trang) & Dò mắt với Nghiệm thu + Hóa đơn (BOTTLENECK: 10-12 phút/bộ)] -> (Nếu lệch/thiếu ~25%) -> [5a. Chụp ảnh lỗi, trả lại hồ sơ chờ sửa (+2-3 ngày)] -> Quay lại Bước 1 / (Nếu khớp 100%) -> [4. Check ngân sách] -> [5b. Nhập ERP & Duyệt chi]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi bộ phận Kinh doanh hoặc Mua hàng gửi hợp đồng theo mẫu của đối tác sang yêu cầu duyệt gấp, tôi muốn xác định ngay các điều khoản bất lợi hoặc trái với quy chuẩn của tập đoàn, để đưa ra nhận xét chỉnh sửa (redline) nhanh chóng mà không bỏ sót rủi ro pháp lý. |
| Actor | Chuyên viên Pháp chế (Legal Executive); Nhân viên Sales / Mua hàng. |
| Thời điểm / bối cảnh | Khi chuẩn bị chốt giao dịch với khách hàng B2B lớn hoặc nhà cung cấp độc quyền (họ bắt buộc dùng mẫu hợp đồng của họ thay vì mẫu chuẩn của tập đoàn). |
| Quy trình hiện tại (3–7 bước) | 1. Nhận yêu cầu rà soát qua email/hệ thống kèm file Word/PDF hợp đồng.<br>2. Đọc từ đầu đến cuối hợp đồng (15–40 trang) để nắm cấu trúc.<br>3. Đối chiếu từng điều khoản quan trọng (Thanh toán, Phạt vi phạm, Bồi thường thiệt hại, Chấm dứt hợp đồng, Bảo mật) với quy định nội bộ.<br>4. Viết comment hoặc sửa trực tiếp (Track Changes) vào file.<br>5. Gửi lại cho trưởng phòng Pháp chế duyệt trước khi trả về cho Sales/Mua hàng. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & Bước 3 (Đọc toàn văn và dò tìm các điều khoản rủi ro ẩn trong văn bản dài — mất 35–45 phút/hợp đồng). Tổng thời gian xử lý khoảng 60 phút/hợp đồng. |
| Impact (nếu không giải thì sao) | Thời gian phản hồi thực tế bị kéo dài lên 4–5 ngày (vượt SLA 2 ngày), làm chậm tiến độ ký kết hợp đồng của Sales; khi quá tải chuyên viên dễ đọc lướt và bỏ sót câu chữ cài cắm bất lợi về giới hạn trách nhiệm. |
| Success metric (baseline → target) | Thời gian rà soát sơ bộ (First-pass review) 1 hợp đồng giảm từ 60 phút → 20 phút; Tỷ lệ hợp đồng trả kết quả đúng hạn SLA (trong 48h) tăng từ 65% → 90%. |
| Phương án không dùng AI | Xây dựng bộ Contract Playbook (Sổ tay điều khoản chuẩn và các câu mẫu thay thế) để chuyên viên tra cứu và copy-paste nhanh; yêu cầu bộ phận gửi hợp đồng điền trước bảng tóm tắt các thông tin thương mại chính. |
| Giả thuyết về AI (nếu có) | Dùng AI Workflow đối chiếu nội dung hợp đồng tải lên với bộ Contract Playbook của công ty: tự động trích xuất và gắn cờ (Đỏ/Vàng/Xanh) cho 10 điều khoản trọng yếu kèm gợi ý câu chữ sửa đổi để chuyên viên Pháp chế xem xét. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Sales/Mua hàng gửi Hợp đồng đối tác] -> [1. Pháp chế tải file & kiểm tra hồ sơ] -> [2. Đọc dò toàn bộ 15-40 trang văn bản (BOTTLENECK 1: 25-30 phút)] -> [3. Đối chiếu thủ công với quy chuẩn nội bộ (BOTTLENECK 2: 15 phút)] -> [4. Gõ nhận xét Redline / Track Changes vào file] -> [5. Trình Quản lý duyệt & Trả kết quả]
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được 3–4 bảng báo giá từ các nhà cung cấp cho cùng một yêu cầu mua sắm, tôi muốn chuẩn hóa các hạng mục, đơn giá, thuế và điều kiện thương mại về cùng một bảng so sánh chuẩn, để trình lãnh đạo phê duyệt nhà cung cấp tối ưu nhất một cách nhanh chóng. |
| Actor | Chuyên viên Mua hàng (Procurement Specialist). |
| Thời điểm / bối cảnh | Mỗi khi phát sinh yêu cầu mua sắm thiết bị, vật tư hoặc dịch vụ mới cần đấu thầu cạnh tranh (ít nhất 3 báo giá theo quy định tài chính). |
| Quy trình hiện tại (3–7 bước) | 1. Nhận 3 file báo giá (PDF scan có dấu đỏ hoặc Excel) từ 3 nhà cung cấp qua email.<br>2. Mở file Excel mẫu Bảng so sánh giá (Bid Tabulation) của tập đoàn.<br>3. Đọc từng dòng trên 3 báo giá, quy đổi các tên gọi khác nhau của cùng 1 mặt hàng về tên chuẩn, quy đổi đơn vị tính và tách riêng trước thuế/sau thuế.<br>4. Gõ tay toàn bộ số liệu và điều kiện (bảo hành, thời gian giao hàng, điều khoản thanh toán) vào bảng Excel.<br>5. Kiểm tra lại công thức tính tổng và viết nhận xét đề xuất chọn nhà cung cấp. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & Bước 4 (Đọc, quy đổi hạng mục không đồng nhất và gõ tay từ PDF sang Excel — mất 35–40 phút/tờ trình). |
| Impact (nếu không giải thì sao) | Tốn gần 1 giờ cho việc nhập liệu thuần túy trên mỗi hồ sơ mua sắm, làm giảm thời gian chuyên viên dành cho việc đàm phán giá với nhà cung cấp; dễ xảy ra lỗi gõ nhầm con số hoặc nhầm lẫn giữa giá đã gồm VAT và chưa gồm VAT. |
| Success metric (baseline → target) | Thời gian lập Bảng so sánh giá cho 1 gói mua sắm giảm từ 45 phút → 10 phút; Sai số do nhập liệu thủ công giảm về 0%. |
| Phương án không dùng AI | Gửi file Excel biểu mẫu báo giá chuẩn (RFQ Template) của tập đoàn và yêu cầu các nhà cung cấp phải điền đúng vào file đó trước khi nộp. |
| Giả thuyết về AI (nếu có) | Dùng AI Workflow (OCR + LLM) đọc 3 file báo giá PDF bất kỳ, tự động gióng hàng (mapping) các hạng mục tương đương nhau và xuất thẳng ra file Excel theo đúng mẫu chuẩn của công ty để chuyên viên kiểm tra lại. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Nhận 3 file Báo giá PDF/Excel khác cấu trúc] -> [1. Mở mẫu Excel So sánh giá chuẩn] -> [2. Đọc & quy đổi tên hàng hóa viết khác nhau giữa 3 bên (BOTTLENECK 1: 15 phút)] -> [3. Gõ tay từng đơn giá, VAT, bảo hành từ PDF sang Excel (BOTTLENECK 2: 20-25 phút)] -> [4. Kiểm tra lại tổng tiền & Viết đề xuất trình ký]
```

### Card muốn pitch nhất

- Card số: Card #1 — Đối chiếu hồ sơ thanh toán nhà cung cấp (3-way matching).
- Vì sao: Tần suất lặp lại rất cao (hàng chục bộ hồ sơ mỗi ngày), nỗi đau ảnh hưởng trực tiếp tới cả phòng Kế toán lẫn tất cả các phòng ban làm thanh toán. Quy trình có ranh giới rất rõ để tách biệt phần việc của Rule (đọc XML hóa đơn, kiểm tra trường bắt buộc) và phần việc thực sự cần AI Workflow (đọc hiểu điều khoản trong Hợp đồng PDF scan), đồng thời rất dễ tiếp cận người thật để phỏng vấn kiểm chứng ngay trong buổi lab.
- Câu hỏi muốn nhóm phản biện: Trong 25% hồ sơ bị trả lại hiện nay, bao nhiêu phần trăm thực sự cần đến AI đọc hiểu hợp đồng để phát hiện ra, và bao nhiêu phần trăm chỉ là do nhân viên các phòng ban quên đính kèm file hoặc cộng sai số học cơ bản (những thứ chỉ cần sửa lại Form nhập liệu hoặc dùng Rule là giải quyết được)?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Ở bản nháp đầu tiên, tôi gộp chung kiểm tra hóa đơn và đọc hợp đồng thành một bước dùng AI. AI chỉ ra rằng Hóa đơn điện tử tại Việt Nam luôn có file XML chứa dữ liệu có cấu trúc chuẩn, dùng LLM để đọc hóa đơn là lãng phí và không đảm bảo chính xác 100% bằng code Rule thông thường. | Đồng ý | Tách bạch ở mục Phương án không dùng AI và Giả thuyết về AI: Dùng Rule/code thường để bóc tách dữ liệu từ file XML hóa đơn; chỉ dùng AI (OCR + LLM) cho phần tài liệu phi cấu trúc là Hợp đồng PDF scan và Biên bản nghiệm thu. |
| AI phản biện rằng metric ban đầu của tôi ("Giảm áp lực cho kế toán cuối tháng") là cảm tính, không đo lường được. | Đồng ý | Sửa lại Success metric thành 2 chỉ số định lượng có baseline và target rõ ràng: Thời gian kiểm tra 1 bộ hồ sơ (18 phút → dưới 5 phút) và Tỷ lệ hồ sơ bị trả lại (25% → dưới 8%). |
| AI gợi ý có thể nâng lên mức Agent để tự động đối chiếu, tự gửi email đòi lại chứng từ thiếu cho phòng ban và tự đẩy lệnh chi lên ngân hàng nếu khớp. | Không đồng ý | Giữ nguyên mức Workflow và bác bỏ gợi ý Agent vì trong nghiệp vụ tài chính tập đoàn, việc tự động đẩy lệnh chi khi chưa có con người kiểm duyệt mang rủi ro Viability/Value cực lớn. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Card #1 (Đối chiếu hồ sơ thanh toán nhà cung cấp) trong 3 phút, nhấn mạnh vào bottleneck đọc hợp đồng scan 10–30 trang và dò mắt 3 bên mất 18 phút/bộ. | Card #1 được đưa vào danh sách Shortlist của nhóm nhờ có quy trình rõ và số liệu baseline cụ thể. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Với bài toán tổng hợp báo cáo/CSKH của bạn, nếu không dùng AI mà chỉ bắt buộc mọi người điền đúng biểu mẫu chuẩn trên Google Sheet/ERP ngay từ đầu thì giải quyết được bao nhiêu % vấn đề? | Giúp nhóm loại bỏ được 2 candidate problems thực chất chỉ là lỗi thiếu quy định vận hành (No AI), không cần thiết phải xây hệ thống phức tạp. |
| Nhận phản biện | Câu hỏi tôi nhận được: Nếu kế toán vẫn phải tự mắt kiểm tra lại kết quả của AI vì sợ sai số tiền thì thời gian có thực sự giảm từ 18 phút xuống 5 phút được không? | Tôi đã sửa gì: Làm rõ lại cơ chế hiển thị (Usability) và Boundary ở CP5–CP6: AI không chỉ kết luận Đúng/Sai mà phải trích xuất đúng đoạn văn bản trong hợp đồng kèm số trang (citation) đặt cạnh con số trên hóa đơn để kế toán chỉ mất 1 phút nhìn đối chiếu ngay trên 1 màn hình. |
| Gom cluster / cây OST | Cùng nhóm phân loại 12 cards cá nhân thành 3 cụm (Clusters): (1) Đối chiếu & Kiểm duyệt chứng từ/tài liệu dài; (2) Tổng hợp báo cáo đa nguồn; (3) Hỏi đáp quy trình nội bộ. Vẽ nhánh Opportunity trên OST. | Nhóm nhìn ra điểm chung lớn nhất là nỗi đau xử lý dữ liệu phi cấu trúc (file PDF scan, văn bản dài) trong quy trình phê duyệt nội bộ. |
| Chọn candidate problem | Đề xuất bộ tiêu chí chấm điểm chọn bài toán nhóm: Tần suất xảy ra, Khả năng tiếp cận người thật để phỏng vấn ngay trong buổi lab, và Độ rõ ràng của metric. | Nhóm thống nhất hội tụ về 1 bài toán chính để đi sâu từ CP4 đến CP6, không bị lan man tranh cãi cảm tính. |
| Kiểm chứng / research | Soạn 5 câu hỏi phỏng vấn theo nguyên tắc The Mom Test (chỉ hỏi về lần gần nhất họ xử lý/nộp hồ sơ trong tuần qua). Trực tiếp phỏng vấn nhanh 2 người thật (1 kế toán, 1 nhân viên văn phòng). | Thu thập được bằng chứng thực tế chứng minh nỗi đau lớn nhất nằm ở việc đọc tìm điều khoản thanh toán chia nhiều đợt trong hợp đồng và nội dung viết trên hóa đơn khác chữ với hợp đồng. |
| Quy trình nhóm | Vẽ sơ đồ quy trình hiện tại (As-Is) và quy trình tương lai (To-Be), đánh dấu rõ bước nào do Con người làm, bước nào dùng Rule, bước nào dùng AI Workflow. | Sơ đồ trực quan hóa được cách tháo gỡ bottleneck ở Bước 3 mà vẫn giữ chốt chặn an toàn (Human-in-the-loop) ở bước duyệt cuối. |
| Problem Statement | Viết nháp phần Boundary (Ranh giới những gì AI tuyệt đối không được làm) và bộ tiêu chí Eval để chấm chất lượng đầu ra của AI. | Đảm bảo Problem Statement v0 và v1 của nhóm không bị chung chung, có ngưỡng chấp nhận lỗi rõ ràng. |
| Mức can thiệp AI | Phân tích lý do tại sao chọn tổ hợp Rule + AI Workflow thay vì dùng No AI thuần túy hoặc nhảy vọt lên Agent. | Giúp lập luận ở CP6 chặt chẽ: tận dụng Rule cho dữ liệu có cấu trúc (XML) để đạt độ chính xác 100%, chỉ gọi LLM ở bước đọc hiểu ngữ nghĩa PDF. |
| Quyết định | Cùng nhóm đánh giá 4 rủi ro (Value, Usability, Feasibility, Viability) và đề xuất điều kiện cần đạt trước khi triển khai. | Nhóm đi đến kết luận có căn cứ, yêu cầu chuẩn hóa xong tập dữ liệu mẫu 50 bộ hồ sơ để kiểm thử Eval trước khi mở rộng. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý thêm các tác vụ gây nghẽn phổ biến ở các phòng ban chức năng (Pháp chế, Mua hàng, IT) trong tập đoàn lớn để đối chiếu với quan sát của bản thân. | Giúp mở rộng nhanh góc nhìn sang các phòng ban khác ngoài bộ phận của mình, gợi ý cấu trúc viết Job Story đúng chuẩn Khi... tôi muốn... để... | AI đưa ra nhiều bài toán rất chung chung, sáo rỗng (như tối ưu hóa văn hóa doanh nghiệp, dự báo chiến lược) và tự bịa ra các con số phần trăm không có nguồn. | Tôi loại bỏ toàn bộ các bài toán vĩ mô, chỉ giữ lại các quy trình vận hành cụ thể mà bản thân đã chứng kiến, đồng thời thay thế số liệu bằng ước lượng thực tế từ khối lượng công việc hàng ngày. |
| CP2 Problem Card | Dùng AI đóng vai người phản biện (Devil's Advocate) để tìm lỗ hổng trong 3 Problem Cards của tôi. | Chỉ ra rất sắc bén việc tôi đang định dùng AI cho cả những việc chỉ cần code Rule thông thường (như đọc file XML của hóa đơn điện tử). | Khi gợi ý giải pháp, AI luôn có xu hướng đẩy lên mức phức tạp nhất là xây dựng Autonomous Agent tự động duyệt và thực thi từ A–Z. | Tôi bác bỏ đề xuất dùng Agent của AI, giới hạn lại ở mức Workflow vì hiểu rõ quy định kiểm soát nội bộ của tập đoàn không bao giờ cho phép AI tự ý duyệt lệnh chi tiền. |
| CP4 Research | Nhờ AI rà soát lại danh sách câu hỏi phỏng vấn xem có câu nào vi phạm The Mom Test (câu hỏi dẫn dắt, hỏi về tương lai giả định) hay không. | Giúp phát hiện và sửa lại 2 câu hỏi mang tính xin ý kiến ("Nếu có phần mềm tự đối chiếu thì chị có dùng không?") thành câu hỏi khai thác hành vi quá khứ ("Lần gần nhất chị phải trả lại hồ sơ là hôm nào, cụ thể vì lỗi gì?"). | AI đề xuất một kịch bản phỏng vấn quá dài (tới 15 câu hỏi mang tính học thuật), không phù hợp để hỏi nhanh đồng nghiệp trong 10–15 phút. | Tôi cắt gọn xuống còn 5 câu hỏi trọng tâm nhất, dùng ngôn ngữ giao tiếp đời thường của dân văn phòng để người được hỏi thoải mái chia sẻ thật. |
| CP5 Quy trình | Nhờ AI hỗ trợ sinh cú pháp sơ đồ từ bản phác thảo các bước quy trình của nhóm để tiết kiệm thời gian vẽ. | Sinh mã sơ đồ nhanh, đúng cú pháp, giúp nhóm dễ dàng chỉnh sửa và đưa vào file Markdown. | Sơ đồ AI tự vẽ lúc đầu gộp chung các bước xử lý ngoại lệ (khi hồ sơ sai) thành một đường thẳng, làm mất đi vòng lặp trả lại hồ sơ (Rework loop) vốn là nỗi đau chính. | Tôi tự viết lại luồng rẽ nhánh để thể hiện rõ vòng lặp trả hồ sơ làm mất thêm 2–3 ngày chờ đợi. |
| CP5–6 Problem Statement | Dùng AI kiểm tra tính nhất quán giữa Bottleneck, Success Metric và tiêu chí Eval trong bản nháp Problem Statement. | Gợi ý cách chia tiêu chí Eval thành các nhóm cụ thể: độ chính xác trích xuất số tiền (Exact match) và độ chính xác trích xuất điều khoản (Semantic match + Citation). | Phần Boundary do AI viết ban đầu rất chung chung kiểu "AI cần đảm bảo bảo mật và chính xác". | Tôi viết lại phần Boundary bằng các quy tắc nghiệp vụ cứng: (1) AI không được tự bấm duyệt hay từ chối hồ sơ trên ERP; (2) Không tự suy diễn số tiền nếu chữ trên bản scan bị mờ mà phải gắn cờ CẦN NGƯỜI KIỂM TRA. |
| CP6 Mức can thiệp / quyết định | Yêu cầu AI liệt kê các rủi ro tiềm ẩn theo 4 trục Value, Usability, Feasibility, Viability của Marty Cagan để nhóm không bỏ sót góc nhìn. | Gợi mở tốt ở góc độ Feasibility (chất lượng file scan hợp đồng bị mờ, nghiêng hoặc đóng dấu đè lên chữ làm OCR đọc sai). | AI đánh giá quá lạc quan ở phần quyết định, khuyên Go ngay lập tức vì công nghệ LLM hiện nay đã rất mạnh. | Nhóm tự thảo luận lại dựa trên rủi ro thực tế về Usability (nếu giao diện bắt kế toán mở thêm 1 phần mềm nữa thì họ sẽ ngại dùng) và đưa ra điều kiện kiểm thử khắt khe hơn trước khi quyết định. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**


**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**


**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**


**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**


**6.7. Hiểu bài:** 

---

## 7. Tài liệu tham khảo

- Rob Fitzpatrick (2013), The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you.
- Teresa Torres (2021), Continuous Discovery Habits — Opportunity Solution Tree (OST).
- Marty Cagan (2017), Inspired: How to Create Tech Products Customers Love — 4 Big Risks (Value, Usability, Feasibility, Viability).
- Anthropic (2024), Building Effective Agents — Workflows vs. Agents.
- Google PAIR (People + AI Research), People + AI Guidebook.
- Tài liệu nội bộ khóa học K5 Level 3 Day 02: CHECKPOINTS.md, RUBRIC.md, docs/01-worksheet.md, docs/03-international-frameworks.md.
