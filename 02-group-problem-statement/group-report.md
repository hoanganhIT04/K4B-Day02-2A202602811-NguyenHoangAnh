# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1 | Nguyễn Viết Đức | 20A202602732 | Writer, tổng hợp nội dung group report, đóng góp candidate về lịch học/thông báo |
| 2 | Nguyễn Hoàng Anh | 2A202602811 | Challenge kỹ thuật, góp candidate về debugging và xử lý vấn đề lập trình |
| 3 | Dương Văn Thành | 2A202602368 | Domain owner cho bài invoice/OCR, phụ trách workflow và problem chính |
| 4 | Hà Thị Mỹ Linh | 2A202602619 | Research và metric, góp candidate về weekly report/data analysis |
| 5 | Vũ Đức Thiện | 2A202602437 | Góp candidate về pain học tập, tìm tài liệu và thông báo rải rác |
| 6 | Tống Trần Tiến Dũng | 2A202602791 | Góp candidate BA workflow, hỗ trợ phân tích requirement/action/user story |                                                              |



**Candidate problem nhóm chọn (1 câu):**


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 |Nguyễn Viết Đức | Mỗi ngày tôi phải check email, Discord và Outlook để cập nhật lịch học, deadline và thông báo workshop, nhưng thông tin nằm rải rác nên dễ mất thời gian hoặc bỏ sót việc quan trọng.| Bản thân tôi, sinh viên/học viên có lịch học trực tiếp và workshop thay đổi theo ngày.|Bước 5 — tự tổng hợp lịch/deadline từ nhiều nguồn khác nhau. |Pain rõ, lặp lại mỗi ngày, dễ đo thời gian và có rủi ro bỏ sót thông tin quan trọng.|
| 2 |Nguyễn Viết Đức | Trong ngày học, tôi vẫn phải check Zalo để phản hồi và chăm sóc khách hàng, nhưng tin nhắn đến rải rác nên dễ phản hồi chậm hoặc mất thời gian nhớ lại context. |Tôi và khách hàng đang cần được hỗ trợ. | Bước 3 — đọc lại lịch sử trao đổi để nhớ context của từng khách hàng. |Có impact thật vì ảnh hưởng trực tiếp tới khách hàng, nhưng cần boundary rõ để AI không tự trả lời sai. |
| 3 |Nguyễn Viết Đức |Sau một ngày học từ 9h đến 18h, tôi thường mất thời gian để nhớ lại hôm nay đã học gì và tối nên ưu tiên học workshop phần nào. |Bản thân tôi, người phải học cả ban ngày và tiếp tục học workshop hoặc làm bài vào buổi tối. | Bước 5-6 — đọc lại tài liệu và tự chọn ưu tiên học khi đã mệt sau cả ngày. |Gắn trực tiếp với hiệu quả học tập, workflow rõ, AI có thể hỗ trợ tóm tắt nhưng vẫn cần tôi review. |
| 4 |Dương Văn Thành| Mỗi tuần phải tổng hợp và viết báo cáo công việc thực tập cho AIRC và nhà trường từ các công việc đã thực hiện | AI Intern| Bước 3-4 — tổng hợp thông tin và chuyển các ghi chú/công việc đã làm thành nội dung báo cáo có cấu trúc, rõ ràng và đủ thông tin.| Problem có tính lặp lại rõ ràng, workflow dễ xác định và có bottleneck cụ thể ở khâu tổng hợp/viết nội dung. Có thể đo thời gian hoàn thành và số lần chỉnh sửa, phù hợp để nghiên cứu giải pháp Workflow có hỗ trợ AI.|
| 5 |Dương Văn Thành| Khi viết tài liệu nghiên cứu, khó nhanh chóng tóm tắt và hệ thống hóa thông tin kỹ thuật thành cấu trúc dễ đọc | AI Intern / người đọc tài liệu | Bước 2-4 — chọn thông tin quan trọng, sắp xếp thành cấu trúc hợp lý và chuyển nội dung kỹ thuật thành tài liệu dễ đọc.| Có pain thực tế trong công việc nghiên cứu và AI có khả năng hỗ trợ tốt ở bước tóm tắt, phân loại và cấu trúc thông tin. Tuy nhiên cần kiểm chứng chất lượng nội dung vì AI có thể tóm tắt sai hoặc làm mất thông tin kỹ thuật quan trọng. |
| 6 |Dương Văn Thành| Kiểm thử invoice phải đối chiếu ảnh JPG với JSON output, kiểm tra từng trường thông tin có khớp hay không | AI Intern / nhóm phát triển | Bước 3-4 — đối chiếu thủ công từng trường giữa ảnh JPG và JSON, sau đó ghi nhận chính xác các trường hợp không khớp.| Workflow và bottleneck rất cụ thể, dễ xác định input/output và đo hiệu quả theo thời gian kiểm thử, số trường kiểm tra hoặc tỷ lệ mismatch bị bỏ sót. Có thể thử Rule/Workflow trước, sau đó mới đánh giá mức độ cần thiết của AI. |
| 7 |Nguyễn Hoàng Anh|Khi gặp lỗi trong quá trình lập trình, phải tìm kiếm nhiều nguồn và thử nhiều cách trước khi xác định nguyên nhân. |Sinh viên lập trình / người làm đồ án|Tìm nguyên nhân và đối chiếu nhiều hướng xử lý.|Workflow rõ, pain thường xuyên, có thể đo thời gian debug; cần kiểm tra AI có thực sự tốt hơn checklist hay không.|
| 8 |Nguyễn Hoàng Anh|Khi xây dựng và chuẩn bị dữ liệu cho đồ án, phải kiểm tra, chỉnh sửa và bổ sung dữ liệu theo từng nhóm trước khi đưa vào model.|Sinh viên / người phụ trách dataset|Kiểm tra từng mẫu và phát hiện dữ liệu sai, thiếu hoặc không phù hợp.|Có nhiều bước lặp lại, dễ đo thời gian; cần xác định phần nào Rule đã giải quyết được và AI thực sự cần thiết ở đâu.|
| 9 |Nguyễn Hoàng Anh|Khi gặp vấn đề kỹ thuật, phải tìm lại thông tin từ nhiều nguồn như Google, GitHub và documentation trước khi xác định cách xử lý phù hợp.|Sinh viên lập trình / người làm đồ án|Đọc và đối chiếu nhiều nguồn thông tin.|Pain khá rõ và AI có khả năng hỗ trợ; cần kiểm tra vấn đề nằm ở search hay ở việc đánh giá thông tin phù hợp với project.|
| 10 |Hà Thị Mỹ Linh|Mỗi tuần Linh mất khoảng 120 phút để tổng hợp, phân tích dữ liệu từ Sapo và Google Sheets, research thông tin bên ngoài, tìm insight và viết Weekly Report cho Manager và CEO; trong đó khoảng 60 phút tập trung vào analysis, research và writing. |Linh - DA |Bước 3-6, đặc biệt là research → tìm insight → viết narrative, chiếm khoảng 80 phút nếu tính cả analysis, research và writing. Đây là phần khó chuẩn hóa hoàn toàn bằng rule vì mỗi tuần có thể xuất hiện những biến động khác nhau. | Nhóm nhận thấy đây là công việc có giá trị cao nhưng tiêu tốn khá nhiều thời gian do đòi hỏi sự kết hợp giữa phân tích dữ liệu, research và khả năng tổng hợp insight. Đặc biệt, phần viết narrative phụ thuộc nhiều vào bối cảnh và judgment của người thực hiện, vì vậy có tiềm năng ứng dụng AI để hỗ trợ nhưng vẫn cần sự kiểm tra và đánh giá của con người. |
| 11 |Hà Thị Mỹ Linh|Mỗi tuần Linh mất khoảng 35 phút để research Internet nhằm tìm context và nguyên nhân giải thích cho các biến động trong dữ liệu kinh doanh. |DA |Bước 3-4: tìm kiếm và đọc nhiều nguồn để xác định thông tin nào thực sự liên quan. | Nhóm nhận thấy việc research Internet đang chiếm một lượng thời gian đáng kể và phần lớn thời gian được sử dụng để sàng lọc, đối chiếu và xác định mức độ liên quan của thông tin. Đây là công đoạn có tiềm năng cải thiện rõ rệt nếu có công cụ hỗ trợ tìm kiếm và tổng hợp context phù hợp. |
| 12 |Hà Thị Mỹ Linh|Mỗi tuần Linh mất khoảng 30 phút để kiểm tra và đối chiếu dữ liệu giữa Sapo và Google Sheets trước khi sử dụng cho Weekly Report. |DA | Bước 3-4: đối chiếu thủ công và tìm discrepancy giữa hai nguồn.| Nhóm nhận thấy việc đối chiếu dữ liệu giữa Sapo và Google Sheets đang được thực hiện thủ công, vừa tốn thời gian vừa có khả năng phát sinh sai sót. Đây là công đoạn tương đối có cấu trúc, do đó có tiềm năng cao để tự động hóa việc kiểm tra discrepancy và giảm thời gian xử lý hàng tuần. |
| 13 |Vũ Đức Thiện |mất nhiều thời gian tìm lại tài liệu, link hoặc file đã xem trước đó nhưng không nhớ lưu ở đâu. |sinh viên |Phải tìm thủ công qua nhiều nơi và mở từng kết quả để kiểm tra vì không nhớ chính xác tên/vị trí tài liệu. |Đây là vấn đề khá thực tế vì tài liệu thường nằm rải rác ở nhiều nơi. Điểm nghẽn rõ, xảy ra lặp lại và có khả năng cải thiện tốt bằng tìm kiếm thông minh/AI.  |
| 14 |Vũ Đức Thiện |phải tua hoặc xem lại video bài giảng dài để tìm đúng đoạn chứa thông tin cần thiết. |sinh viên |Phải tua và xem thử nhiều đoạn vì video không thể tìm trực tiếp theo nội dung/câu hỏi.  |Vấn đề dễ hiểu và dễ đo lường vì người học thường phải tua video nhiều lần để tìm đúng nội dung. AI có tiềm năng giảm đáng kể thời gian tìm kiếm nếu có transcript và timestamp.  |
| 15 |Vũ Đức Thiện |phải kiểm tra nhiều nhóm Discord/Facebook/Zalo để không bỏ sót thông báo học tập quan trọng. |sinh viên |Phải tự đọc và lọc nhiều thông báo từ nhiều nền tảng để xác định cái nào quan trọng.  |Đây là vấn đề có tác động khá lớn vì thông báo học tập đến từ nhiều nền tảng và dễ bị bỏ sót. Tuy nhiên cần chú ý khả năng truy cập dữ liệu và quyền riêng tư khi muốn tự động hóa bằng AI.  |
| 16 | Tống Trần Tiến Dũng | Đọc tài liệu, Phân loại Requirement / Action / Question sau mỗi meeting | Intern BA | Đọc lại toàn bộ notes và Tìm các thông tin quan trọng, Phân loại: Requirement, Action Item, Open Question, Context, Format lại tài liệu | Đây là problem có workflow rõ, lặp lại thường xuyên và có khả năng thử nghiệm AI tương đối tốt |
| 17 | Tống Trần Tiến Dũng | chuẩn bị draft User Story để BA chính review. từ tài liệu ghi chép sau mỗi cuộc họp | Intern BA, Senior BA | phải chuyển thông tin từ format tự do sang format User Story | Problem có tính thực tế và AI có thể hỗ trợ tốt ở bước tạo draft, nhưng cần human review chặt chẽ vì việc tự động hóa quá sâu có thể làm thay đổi business context.  |
| 18 | Tống Trần Tiến Dũng | Tìm Requirement cũ để tìm các tài liệu và giải pháp liên quan | Thông tin nằm ở nhiều nguồn  | Intern BA | Problem có pain point rõ và tiềm năng ứng dụng AI cao, nhưng cần giới hạn scope để có thể prototype trong thời gian ngắn |


### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | #1, #9, #13, #15, #18 | Tìm kiếm / tổng hợp thông tin từ nhiều nguồn rời rạc | Các problem đều có pain là thông tin nằm ở nhiều nơi như email, Discord, Outlook, Google, GitHub, documentation, file cũ hoặc nhóm chat. Bottleneck nằm ở việc tự tìm, lọc và xác định thông tin nào quan trọng/đúng context. |
| B | #3, #4, #5, #10, #11, #16, #17 | Tổng hợp, viết lại và cấu trúc hóa thông tin | Các problem đều cần biến notes, dữ liệu, tài liệu hoặc research thô thành output có cấu trúc như report, checklist học tập, tài liệu kỹ thuật, meeting summary hoặc User Story. AI có thể hỗ trợ tốt ở bước tóm tắt, phân loại, draft nội dung, nhưng cần người review. |
| C | #6, #8, #12 | Kiểm tra / đối chiếu dữ liệu có cấu trúc | Các problem đều có input-output khá rõ và cần kiểm tra từng trường/mẫu dữ liệu để phát hiện sai, thiếu hoặc mismatch. Đây là cụm dễ đo bằng thời gian xử lý, số field/mẫu kiểm tra và số lỗi bị bỏ sót. |
| D | #2, #7, #14 | Phản hồi / xử lý vấn đề cần đọc lại context | Các problem đều yêu cầu đọc lại ngữ cảnh trước khi hành động: trả lời khách hàng, debug lỗi lập trình, hoặc tua video để tìm đúng đoạn. Bottleneck là hiểu đúng context trước khi đưa ra phản hồi/hướng xử lý. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #6 — Kiểm thử invoice phải đối chiếu ảnh JPG với JSON output | Workflow rất rõ: nhận ảnh invoice + JSON → đọc field trên ảnh → đối chiếu JSON → ghi mismatch → báo lỗi. Actor cụ thể là AI Intern / nhóm phát triển. Impact dễ đo bằng thời gian kiểm thử, số field kiểm tra và số mismatch bị bỏ sót. | Cần biết chất lượng OCR/AI đọc ảnh invoice có đủ tốt không. Nếu invoice nhiều format khác nhau, rule đơn giản có thể không đủ. |
| #10 — Weekly Report cho Manager và CEO từ Sapo, Google Sheets và research ngoài | Pain rõ và có số đo cụ thể: khoảng 120 phút/tuần, trong đó 60-80 phút nằm ở analysis, research và viết narrative. Workflow có nhiều bước rõ: lấy dữ liệu → phân tích → research context → tìm insight → viết report. AI có thể hỗ trợ tốt ở phần tổng hợp và draft narrative. | Scope có thể rộng vì vừa có dữ liệu nội bộ, vừa có research bên ngoài, vừa viết insight. Metric chất lượng report khó đo hơn thời gian. |
| #16 — Đọc tài liệu, phân loại Requirement / Action / Question sau mỗi meeting | Actor rõ là Intern BA, workflow rõ: đọc notes → tìm thông tin quan trọng → phân loại → format lại tài liệu. AI phù hợp để hỗ trợ tóm tắt, phân loại và cấu trúc hóa thông tin. Output có thể review được bởi BA chính. | Cần có meeting notes thật để validate. AI có thể phân loại sai requirement/action/question nếu context cuộc họp không đủ rõ. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #6 — Kiểm thử invoice phải đối chiếu ảnh JPG với JSON output | 5 | 5 | 4 | 5 | 5 | 5 | 4 | 33 |
| #10 — Weekly Report cho Manager và CEO từ Sapo, Google Sheets và research ngoài | 5 | 5 | 5 | 5 | 4 | 5 | 4 | 33 |
| #16 — Đọc tài liệu, phân loại Requirement / Action / Question sau mỗi meeting | 5 | 4 | 4 | 4 | 5 | 5 | 4 | 31 |

**Candidate nhóm chọn (1 bài duy nhất):**

```#6 — Kiểm thử invoice phải đối chiếu ảnh JPG với JSON output, kiểm tra từng trường thông tin có khớp hay không.

```

**Vì sao chọn (4-5 câu):**

```Nhóm chọn bài kiểm thử invoice vì workflow rất rõ và có thể vẽ được từ đầu đến cuối: nhận ảnh JPG và JSON output, mở hai nguồn, đọc từng field, đối chiếu, ghi mismatch và báo lại cho nhóm phát triển. Bottleneck nằm ở một bước cụ thể là đối chiếu thủ công từng trường giữa ảnh invoice và JSON, nên dễ phân tích trước/sau. Impact cũng đo được bằng thời gian kiểm thử, số field phải kiểm tra và số mismatch bị bỏ sót. Bài này đủ nhỏ để làm trong lab, nhưng vẫn có chỗ để so sánh Rule / Workflow / Agent. Ngoài ra, nhóm có thành viên hiểu domain AI/OCR và kiểm thử dữ liệu nên có thể đào sâu thực tế hơn.

```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```Không chọn #10 — Weekly Report cho Manager và CEO vì tuy pain rõ và impact lớn, scope khá rộng: vừa lấy dữ liệu từ Sapo/Google Sheets, vừa research bên ngoài, vừa phân tích insight, vừa viết narrative. Metric thời gian có thể đo được nhưng chất lượng insight/report khó thống nhất trong thời gian lab. Bài này phù hợp để nghiên cứu tiếp, nhưng dễ trượt sang workflow quá lớn.

Không chọn #16 — Đọc tài liệu, phân loại Requirement / Action / Question sau mỗi meeting vì bài này có workflow rõ và AI hỗ trợ tốt, nhưng cần meeting notes thật để validate chất lượng phân loại. Nếu notes thiếu context, AI dễ phân loại sai requirement/action/question. So với #6, output của #16 khó kiểm tra đúng/sai hơn vì phụ thuộc vào ngữ cảnh cuộc họp và đánh giá của BA chính.

```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```
Ban đầu nhóm phân vân giữa #6 và #10 vì cả hai đều có điểm cao và workflow rõ. Một số thành viên nghiêng về #10 vì impact business lớn hơn, nhưng nhóm lo scope quá rộng và khó đo chất lượng insight trong lab. Cuối cùng nhóm chốt #6 vì input/output rõ hơn, dễ kiểm thử với mẫu nhỏ, dễ đo thời gian và dễ xác định AI nên can thiệp ở bước nào. Nhóm thống nhất giữ #10 như một candidate tốt nhưng chưa chọn cho scope hôm nay.

```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 2-3 AI Intern / người từng kiểm thử OCR invoice | Cần hỏi nhanh người có kinh nghiệm kiểm thử invoice. Tín hiệu muốn kiểm tra: họ có phải mở ảnh JPG và JSON cạnh nhau không, mỗi batch mất bao lâu, bước nào dễ sai nhất. Quote thật cần điền sau interview, ví dụ: “...” | Có thể một số người nói họ đã có tool tự compare JSON hoặc invoice format khá cố định nên không quá đau. | Nếu interview xác nhận pain nằm ở đối chiếu field, nhóm thu hẹp problem thành “phát hiện mismatch giữa OCR/JSON và invoice image”, không làm toàn bộ hệ thống invoice processing. |
| Survey / poll | 5-10 người nếu có thời gian | Câu hỏi poll: “Bạn đã từng phải đối chiếu output OCR/JSON với ảnh gốc chưa?”, “Mỗi lần mất bao lâu?”, “Bạn hay sai ở bước nào?”. Tín hiệu xác nhận là nhiều người chọn mất trên 15 phút/batch hoặc hay bỏ sót mismatch. | Nếu đa số chưa từng làm invoice/OCR testing, survey không đại diện tốt cho problem này. | Nếu survey yếu, nhóm không dùng survey làm bằng chứng chính mà dựa vào interview/log từ người có domain gần hơn. |
| Log / ticket / review (nếu có) | 1-2 batch invoice mẫu hoặc bug report cũ | Có thể dùng một batch mẫu gồm ảnh invoice + JSON output để đo thử: số field cần kiểm tra, thời gian đối chiếu, số mismatch tìm được. Đây là bằng chứng tốt hơn cảm nhận chung. | Nếu không có sample invoice thật hoặc dữ liệu nhạy cảm không được chia sẻ, nhóm chỉ có thể dùng data giả lập nên độ tin cậy thấp hơn. | Nhóm dùng data mẫu nhỏ, ẩn thông tin nhạy cảm, chỉ đo workflow kiểm thử: thời gian, số field, số mismatch, số lỗi bị bỏ sót. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```
Pain thật không nằm ở việc có ảnh invoice hay có JSON output, mà nằm ở bước người kiểm thử phải tự đối chiếu từng field giữa hai nguồn và phát hiện mismatch thủ công. Đây là bước lặp lại, tốn thời gian, dễ mỏi mắt và dễ bỏ sót lỗi nhỏ nếu invoice có nhiều trường thông tin.

```

Bằng chứng đính kèm (nếu có): 

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Amazon Textract AnalyzeExpense | https://docs.aws.amazon.com/textract/latest/dg/analyzing-document-expense.html | Đọc invoice/receipt từ ảnh hoặc PDF và trích xuất thông tin thành dữ liệu có cấu trúc | Có API chuyên cho invoice/receipt, phù hợp bước OCR và extract field | Có thể đọc sai nếu ảnh mờ, layout lạ hoặc field không rõ; vẫn cần người review | Không nên build OCR từ đầu; nên dùng OCR/AI để tạo dữ liệu đọc từ ảnh rồi so sánh với JSON |
| Google Cloud Document AI Invoice Parser | https://docs.cloud.google.com/document-ai/docs/processors-list | Trích xuất invoice number, supplier, amount, tax, invoice date, due date và line items | Có pre-trained invoice parser, output có cấu trúc | Cần setup cloud/API; kết quả phụ thuộc chất lượng ảnh và format invoice | Nên tập trung vào workflow compare extracted result với JSON output |
| Azure AI Document Intelligence - Prebuilt Invoice | https://azure.microsoft.com/en-us/pricing/details/ai-document-intelligence/ | Dùng model có sẵn để detect/extract dữ liệu từ invoice và document phổ biến | Có prebuilt model, phù hợp đọc invoice và key fields | Có chi phí/API setup; cần kiểm confidence và kết quả thực tế | Pattern hợp lý: AI extract → rule/script compare → người kiểm thử review mismatch |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```Các giải pháp hiện có như AWS Textract, Google Document AI và Azure Document Intelligence đều đã hỗ trợ OCR/extract thông tin từ invoice, nên nhóm không nên tự build OCR từ đầu. Scope hợp lý hơn là workflow nhỏ: nhận JPG invoice + JSON output, dùng AI/OCR đọc field chính, tự động so sánh với JSON, rồi để người kiểm thử review mismatch report. AI chỉ hỗ trợ phát hiện lỗi nhanh hơn, không tự kết luận cuối cùng nếu chưa có người kiểm tra.

```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```
  [1 Nhận JPG invoice + JSON output: 2' - AI Intern / Tester]
→ [2 Mở ảnh invoice và JSON cạnh nhau: 3' - AI Intern / Tester]
→ [3 Đọc từng field trên ảnh invoice: 8-12' - AI Intern / Tester]
→ [4 Đối chiếu từng field với JSON output: 10-15' - AI Intern / Tester] <--bottleneck
→ [5 Ghi lại field sai/thiếu: 5-8' - AI Intern / Tester]
→ [6 Báo lại cho nhóm phát triển: 3-5' - AI Intern / Tester]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | AI Intern / Tester | File JPG invoice + JSON output | Bộ file cần kiểm thử | 2 phút / batch | Bắt đầu workflow kiểm thử |
| 2 | AI Intern / Tester | Ảnh invoice và file JSON | Hai nguồn được mở cạnh nhau để so sánh | 3 phút / batch | Chuẩn bị thủ công trước khi kiểm |
| 3 | AI Intern / Tester | Ảnh invoice JPG | Các field đọc được từ ảnh invoice | 8-12 phút / batch | Dễ mỏi mắt nếu invoice có nhiều field |
| 4 | AI Intern / Tester | Field trên ảnh + field trong JSON | Danh sách field khớp / không khớp | 10-15 phút / batch | Bottleneck chính: đối chiếu thủ công từng field |
| 5 | AI Intern / Tester | Các mismatch phát hiện được | Note lỗi sai, thiếu hoặc không khớp | 5-8 phút / batch | Có thể ghi thiếu nếu nhiều lỗi nhỏ |
| 6 | AI Intern / Tester → Dev team | Note lỗi / mismatch list | Bug report hoặc feedback cho dev team | 3-5 phút / batch | Handoff cho nhóm phát triển |
| 7 | Dev team | Bug report / feedback | Fix lỗi hoặc điều tra thêm | Tùy lỗi | Ngoài scope chính của lab |

**Bottleneck chính (2-3 câu):**

```Bottleneck chính nằm ở bước đối chiếu từng field giữa ảnh JPG invoice và JSON output. Người kiểm thử phải đọc thông tin trên ảnh, tìm field tương ứng trong JSON, rồi kiểm tra value có khớp hay không. Bước này lặp lại nhiều lần, dễ mỏi mắt, dễ bỏ sót mismatch nhỏ và tốn thời gian khi invoice có nhiều trường.

```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```
  [1 Upload JPG invoice + JSON output: 1' - người test]
→ [2 Rule/script chuẩn hóa danh sách field cần kiểm tra: 1-2' - máy]
→ [3 AI/OCR đọc thông tin chính trên invoice: 2-4' - AI]
→ [4 Workflow tự so sánh OCR result với JSON output: 2-3' - máy]
→ [5 Người kiểm thử review mismatch report: 3-5' - human boundary]
→ [6 Gửi report lỗi cho nhóm phát triển: 1-2' - người test]

Fallback: nếu AI/OCR đọc sai ảnh, confidence thấp hoặc mismatch report không đáng tin, người kiểm thử quay lại kiểm tra thủ công invoice đó.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 25-40 phút / batch | 8-15 phút / batch | Bấm giờ khi kiểm thử cùng số lượng invoice |
| Số bước | 6 bước chính | 6 bước chính | So sánh workflow trước/sau |
| Số bước thủ công | 6/6 bước | 2-3/6 bước | Đếm số bước người test phải làm trực tiếp |
| Bottleneck chính | Đối chiếu từng field thủ công giữa JPG và JSON | Review mismatch report do workflow tạo ra | Đo thời gian ở bước nghẽn trước/sau |
| Risk mới | Ít rủi ro AI, chủ yếu là người kiểm thử bỏ sót | OCR/AI đọc sai ảnh hoặc workflow compare sai field | Người test kiểm tra lại mismatch report trước khi gửi |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | AI Intern / tester chịu trách nhiệm kiểm thử output OCR/invoice extraction cho nhóm phát triển. Người này cần kiểm tra xem dữ liệu JSON được hệ thống sinh ra có khớp với thông tin thật trên ảnh invoice JPG hay không. |
| **Workflow** | Tester nhận ảnh invoice JPG và JSON output, mở hai nguồn cạnh nhau, đọc từng field trên ảnh, đối chiếu với JSON, ghi mismatch và báo lại cho dev team. Workflow hiện tại chủ yếu làm thủ công, đặc biệt ở bước đọc ảnh và đối chiếu từng trường. |
| **Bottleneck** | Bottleneck nằm ở bước đối chiếu từng field giữa ảnh invoice và JSON output. Bước này mất khoảng 10-15 phút / batch, dễ mỏi mắt và dễ bỏ sót lỗi nhỏ nếu invoice có nhiều trường. |
| **Impact** | Tổng workflow mất khoảng 25-40 phút / batch. Nếu mismatch bị bỏ sót, dev team có thể tưởng output đúng và lỗi tiếp tục tồn tại trong pipeline OCR/invoice extraction. |
| **Success Metric** | Giảm thời gian kiểm thử từ 25-40 phút xuống 8-15 phút / batch. Đồng thời giảm số mismatch bị bỏ sót sau review và vẫn giữ người test là người approve cuối cùng. |
| **Boundary** | AI không tự approve kết quả JSON, không tự sửa data gốc và không thay người test đưa ra kết luận cuối. AI chỉ hỗ trợ đọc field, so sánh, gợi ý mismatch để người thật kiểm tra lại trước khi báo lỗi. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: “Batch invoice” chưa được định nghĩa rõ là bao nhiêu invoice hoặc bao nhiêu field, nên metric 25-40 phút / batch có thể chưa công bằng nếu mỗi batch có độ lớn khác nhau. Ngoài ra, “mismatch bị bỏ sót” cần có cách kiểm lại để biết thật sự bị bỏ sót bao nhiêu.
- Tôi sửa gì: Nhóm sẽ đo pilot trên một batch nhỏ cố định, ví dụ 3-5 invoice hoặc 20-30 field, để so sánh trước/sau công bằng hơn. Nhóm cũng thêm bước người test review lại mismatch report và kiểm tra mẫu ngẫu nhiên để đo số lỗi bị bỏ sót.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Mỗi field trên invoice hoặc khớp với JSON, hoặc không khớp; kết quả có thể kiểm tra đúng/sai khá rõ.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Workflow có nhiều bước nối tiếp: nhận file, đọc ảnh, extract field, chuẩn hóa format, so sánh với JSON và review mismatch.

**Bài toán nhóm nằm ở ô nào:**

```
Độ mơ hồ thấp, độ phức tạp trung bình/cao.

```

**Vì sao (2-3 câu):**

```
Bài toán có tiêu chí đúng/sai rõ vì value trong JSON phải khớp với thông tin trên ảnh invoice. Tuy nhiên workflow không chỉ là một rule đơn giản vì cần đọc ảnh, extract field, chuẩn hóa format và so sánh với JSON. Vì vậy hướng phù hợp là Workflow có AI/OCR hỗ trợ bước đọc invoice, kết hợp rule/script để compare và người thật review.

```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Viết script so sánh JSON output với một file ground truth đã có sẵn theo danh sách field cố định | Đủ nếu dữ liệu từ ảnh invoice đã được nhập sẵn thành bảng/JSON chuẩn và invoice có format ổn định | Không giải quyết được bước đọc ảnh invoice JPG; nếu format field khác nhau thì rule dễ fail | Không chọn làm toàn bộ, nhưng dùng cho bước compare sau khi đã có field được extract |
| **Workflow** | Upload JPG invoice + JSON output → AI/OCR đọc invoice → rule/script chuẩn hóa và compare field → tester review mismatch report | Đủ vì workflow khá tuyến tính, input/output rõ, AI chỉ hỗ trợ bước đọc/extract và người test vẫn kiểm tra cuối | OCR/AI có thể đọc sai ảnh, mapping sai field hoặc tạo mismatch report thiếu lỗi | Chọn: dùng cho toàn workflow kiểm thử với human boundary ở bước review mismatch |
| **Agent** | Agent tự nhận invoice, tự chọn tool OCR, tự kiểm tra mismatch, tự tạo bug ticket hoặc gửi kết quả cho dev team | Chỉ cần nếu workflow có nhiều nhánh, nhiều hệ thống, cần tự quyết định bước tiếp theo hoặc tự gọi nhiều tool khác nhau | Quá rộng cho lab, nhiều permission/risk; nếu agent tự tạo ticket sai sẽ gây nhiễu cho dev team | Chưa chọn; hiện tại chưa cần agent vì quy trình đủ rõ để dùng workflow |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? 
Rule chỉ giải tốt phần so sánh nếu đã có dữ liệu chuẩn được extract từ ảnh. Nhưng rule không giải quyết được bước đọc ảnh invoice JPG, nên chưa đủ để xử lý toàn bộ workflow.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
Các bước khá đi thẳng một đường: nhận JPG + JSON, đọc ảnh, extract field, chuẩn hóa field, so sánh với JSON, người test review và báo lỗi.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
Chưa cần Agent vì workflow đã cố định và không cần AI tự quyết định bước tiếp theo. Người test vẫn là người kiểm tra và approve cuối cùng.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
Người kiểm thử phát hiện khi review mismatch report. Nếu có field nghi ngờ, người test mở lại ảnh gốc và JSON để kiểm tra thủ công trong khoảng 3-5 phút.
5. Có hạ được từ Agent → Workflow → Rule không?
Có. Nhóm hạ từ Agent xuống Workflow vì chưa cần tự động hóa toàn bộ, và dùng Rule cho bước compare sau khi AI/OCR đã extract field.

**Mức chọn:**

```
Workflow
```

**Vì sao chọn (3-4 câu):**

```
Nhóm chọn Workflow vì bài toán có nhiều bước rõ ràng nhưng không cần AI tự lập kế hoạch. AI/OCR chỉ hỗ trợ đọc và extract thông tin từ ảnh invoice, còn rule/script xử lý phần so sánh có logic rõ. Người kiểm thử vẫn review mismatch report trước khi báo lỗi, nên risk AI sai được kiểm soát. Workflow giúp giảm thời gian đối chiếu thủ công mà không trao toàn bộ quyết định cho AI.

```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```
Không chọn chỉ Rule vì rule không đọc được ảnh invoice JPG nếu chưa có dữ liệu ground truth dạng structured data. Rule vẫn hữu ích cho bước compare sau khi OCR/AI đã extract field, nhưng không đủ để giải quyết bottleneck chính là đọc ảnh và đối chiếu với JSON.

```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | AI Intern / tester chịu trách nhiệm kiểm thử output invoice extraction cho nhóm phát triển. Người này cần xác nhận JSON output có khớp với thông tin thật trên ảnh invoice JPG hay không. |
| **Workflow** | Nhận JPG invoice + JSON output → mở hai nguồn cạnh nhau → đọc field trên ảnh → đối chiếu từng field với JSON → ghi mismatch → báo lại dev team. Workflow hiện tại chủ yếu làm thủ công, đặc biệt ở bước đọc ảnh và đối chiếu. |
| **Bottleneck** | Bottleneck chính là đối chiếu thủ công từng field giữa ảnh invoice và JSON output. Bước này mất khoảng 10-15 phút / batch và dễ bỏ sót lỗi nhỏ khi invoice có nhiều field hoặc layout khó đọc. |
| **Impact** | Tổng workflow mất khoảng 25-40 phút / batch. Nếu mismatch bị bỏ sót, dev team có thể đánh giá sai chất lượng OCR/invoice extraction và lỗi tiếp tục tồn tại trong pipeline. |
| **Success Metric** | Giảm thời gian kiểm thử từ 25-40 phút xuống 8-15 phút / batch. Đồng thời giảm số mismatch bị bỏ sót sau review; người test vẫn là người approve cuối cùng. |
| **Boundary** (làm / không làm) | Làm: hỗ trợ đọc field từ ảnh invoice, chuẩn hóa field, so sánh với JSON và tạo mismatch report. Không làm: tự approve JSON, tự sửa data gốc, tự tạo bug ticket chính thức hoặc gửi kết quả cho dev team nếu người test chưa kiểm tra. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | AI can thiệp sau khi người test upload JPG invoice + JSON output, và trước bước người test đối chiếu thủ công từng field. AI/OCR đọc thông tin trên invoice, sau đó rule/script compare với JSON để tạo mismatch report. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow. Bài toán có nhiều bước rõ ràng, AI chỉ cần hỗ trợ bước đọc/extract từ ảnh, rule/script hỗ trợ compare, còn người test review cuối. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là OCR/AI đọc sai ảnh, map sai field hoặc bỏ sót mismatch. Người kiểm thử kiểm tra mismatch report, mở lại ảnh gốc và JSON khi có field nghi ngờ, rồi mới báo lỗi cho dev team. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor là AI Intern / tester, workflow có input/output rõ từ JPG invoice và JSON output đến mismatch report. |
| Baseline + metric đo được chưa? | Yes | Baseline ước lượng là 25-40 phút / batch, target sau cải thiện là 8-15 phút / batch. |
| Data/input đủ dùng chưa? | Not Yet | Cần chuẩn bị 3-5 invoice JPG mẫu và JSON output tương ứng để chạy pilot nhỏ. |
| AI sai, hậu quả chấp nhận được không? | Yes | Hậu quả chấp nhận được nếu AI chỉ tạo mismatch report và người test luôn review trước khi báo lỗi. |
| Có người review/owner không? | Yes | Người kiểm thử là owner cuối cùng, chịu trách nhiệm kiểm tra lại ảnh gốc và JSON trước khi gửi report cho dev team. |
| Có cách non-AI đơn giản hơn không? | Yes | Có thể dùng checklist field cố định và script compare nếu đã có ground truth dạng structured data, nhưng cách này chưa xử lý tốt bước đọc ảnh JPG. |

**Decision:**

```
Go với scope nhỏ
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```
Nhóm quyết định Go với scope nhỏ vì problem có actor, workflow, bottleneck và metric khá rõ. Baseline hiện tại có thể đo bằng thời gian kiểm thử mỗi batch, số field phải đối chiếu và số mismatch bị bỏ sót. Research cho thấy đã có các giải pháp OCR/invoice extraction như AWS Textract, Google Document AI và Azure Document Intelligence, nên nhóm không cần build OCR từ đầu mà chỉ cần thiết kế workflow hỗ trợ compare và review. Vì người kiểm thử vẫn review mismatch report trước khi báo lỗi, rủi ro AI sai có thể kiểm soát được.

```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```
Pilot nhỏ nhất là dùng 3-5 invoice JPG mẫu và JSON output tương ứng. Nhóm chạy bán thủ công: dùng OCR/AI extract các field chính từ ảnh, dùng rule/script hoặc bảng compare để so sánh với JSON, sau đó người test review mismatch report. Ba số cần đo là: tổng thời gian kiểm thử / batch, số mismatch phát hiện được, và số mismatch bị bỏ sót sau khi review lại ảnh gốc.

```

**Nếu Not Yet — cần validate gì trước:**

```
Cần validate thêm bằng 3-5 invoice JPG mẫu và JSON output tương ứng để đo thời gian kiểm thử thật. Nhóm cũng cần hỏi 1-2 AI Intern / tester xem workflow hiện tại mất bao lâu, bước nào dễ sai nhất và mismatch nào hay bị bỏ sót.

```

**Nếu No-Go — làm gì thay AI:**

```
Nếu không dùng AI, nhóm có thể dùng checklist field cố định và script compare JSON với ground truth do người test nhập thủ công. Cách này ít rủi ro hơn nhưng vẫn chưa giải quyết tốt bước đọc ảnh invoice JPG.

```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```
Nếu OCR/AI đọc sai nhiều, map sai field thường xuyên hoặc làm người test phải kiểm lại gần như toàn bộ invoice, nhóm sẽ dừng workflow AI và quay về checklist + rule/script compare. Nếu pilot không giảm ít nhất 30% thời gian kiểm thử so với baseline 25-40 phút / batch, nhóm chưa nên tiếp tục mở rộng giải pháp AI.

```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
