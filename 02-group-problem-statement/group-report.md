# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Gia Huy   | 2A20262075 | Facilitator, tổng hợp candidate, writer |
| 2   | Đạo       | 2A202602394 | Research, validation, owner candidate V-Learn |
| 3   | Việt      | 2A202602594 | Workflow, phân tích bài toán công việc/freelance |
| 4   | Giáp      | 2A202602903 | Scoring, phản biện Rule / Workflow / Agent |
| 5   | Triển     | 2A202602837 | Reviewer, QA nội dung, final decision |

**Candidate problem nhóm chọn (1 câu):**

Học viên K4B mất khoảng 70-90 phút trước mỗi buổi lab để tìm và tổng hợp kiến thức trọng tâm trong kho tài liệu V-Learn, khiến việc chuẩn bị bài thiếu nhất quán và dễ bỏ sót phần cần áp dụng.

---

## Phase 3 — Group Convergence: từ 15 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Gia Huy | Kiểm tra yêu cầu trước khi nộp bài | Học viên đang chuẩn bị nộp bài lab | So từng yêu cầu trong worksheet/checklist với bài đã làm; dễ bỏ sót field nhỏ | Workflow rõ, đo được số yêu cầu bị thiếu, nhưng có thể checklist thủ công đã đủ |
| 2 | Gia Huy | Tổng hợp góp ý để sửa slide | Nhóm thuyết trình sau khi nhận feedback/ghi âm | Nghe lại ghi âm, đối chiếu với slide, biến góp ý thành danh sách sửa cụ thể | Có input rõ là ghi âm và slide; rủi ro AI nghe sai hoặc gán nhầm slide |
| 3 | Gia Huy | Tổng hợp tài liệu để ôn vấn đáp | Học viên chuẩn bị trả lời vấn đáp sau bài thuyết trình | Đọc lại tài liệu và slide để rút câu hỏi/câu trả lời trọng tâm | Có tài liệu sẵn và scope hẹp, nhưng câu trả lời ngắn chưa chắc giúp hiểu sâu |
| 4 | Đạo | Đọc và tìm kiến thức trọng tâm trong kho tài liệu V-Learn trước mỗi buổi lab tại VinUni | Học viên K4B, ước tính khoảng 35 người trong lớp | Mở nhiều tài liệu, lướt tìm phần liên quan, trích xuất lý thuyết áp dụng cho lab | Pain xảy ra gần như mỗi buổi lab, metric 70-90 phút/buổi rõ; rủi ro nằm ở quyền truy xuất dữ liệu V-Learn |
| 5 | Đạo | Lội tin nhắn Discord lớp K4B để tìm link nộp bài, deadline và tài liệu bổ trợ bị trôi | Học viên K4B và TA | Gom, lọc, phân loại tin nhắn tự do trong nhiều kênh Discord | Lặp lại hằng ngày, impact rộng; nhưng chat tự do nhiều ngữ cảnh dễ trích xuất sai |
| 6 | Đạo | Chấm bài kiểm tra và bài tập Toán cấp 2, dò từng bước đại số để tìm lỗi sai | Gia sư/giáo viên dạy Toán cấp 2 | Đọc bài làm, dò từng dòng biến đổi, xác định bước sai đầu tiên | Bottleneck cô lập và impact rõ, nhưng OCR chữ viết tay/công thức là rủi ro lớn |
| 7 | Việt | Check và điền tiến độ trên WBS cho khách hàng xem | Freelancer/PM dự án và khách hàng | Map tên task trong todolist với mục WBS của khách, rồi cập nhật tiến độ 1-2 lần/ngày | Workflow rõ và ảnh hưởng niềm tin khách hàng; chưa chắc map task tự động đủ chính xác |
| 8 | Việt | Check mail, Zalo để nắm yêu cầu công việc và cập nhật thông tin mới | Freelancer/PM nhận yêu cầu từ khách hàng | Thông tin phân tán ở mail/Zalo, dễ trôi hoặc bỏ sót yêu cầu mới | Pain thật, lặp lại 3-5 lần/ngày; rủi ro tích hợp API/quyền riêng tư |
| 9 | Việt | Go live feature mới và update documentation cho khách hàng | Developer/freelancer bàn giao sản phẩm | Biến thay đổi kỹ thuật, commit/code diff thành documentation dễ hiểu cho khách | Có impact 30-60 phút/lần, nhưng dữ liệu code diff chưa chắc đủ để viết doc cho người không chuyên |
| 10 | Giáp | Mỗi tuần manually review các task đã làm/chưa làm và lập kế hoạch tuần tiếp theo | Software Engineer hoặc người quản lý task cá nhân | Thu thập task, review trạng thái, tìm task chưa xong, ưu tiên và chia lịch mới | Workflow rõ, mất khoảng 2 giờ/tuần; cần làm rõ 2 giờ nằm ở bước nào |
| 11 | Giáp | Khi đọc paper AI, phải liên tục tra cứu thuật ngữ, notation, công thức và kiến thức nền trước khi hiểu nội dung | Software Engineer tự học AI | Context-switch giữa paper và nguồn tra cứu; mất mạch đọc khi gặp concept chưa biết | Actor rõ, có evidence ban đầu từ 3 paper; cần đo thời gian tra cứu/paper |
| 12 | Giáp | Sau khi học một concept AI, phải tự thiết kế thực nghiệm để kiểm chứng mình đã hiểu chưa | Người tự học AI/Machine Learning | Chuyển concept thành experiment, code, chạy và phân tích kết quả | Có khả năng dùng AI hỗ trợ cao, nhưng impact và bottleneck hiện chưa đo rõ |
| 13 | Triển | Debug code khi làm bài tập/đồ án lập trình | Học viên/lập trình viên mới học đang làm bài tập hoặc đồ án | Xác định lỗi thật sự nằm ở đâu trong code, hiểu nguyên nhân và chọn cách sửa đúng | Workflow rõ, tần suất cao 4-5 lần/tuần, impact lớn; cần kiểm chứng AI có nhanh hơn search thủ công không |
| 14 | Triển | Theo dõi deadline nhiều môn trên nhiều nền tảng | Học viên học nhiều môn, dùng nhiều LMS/kênh thông báo | Gom deadline từ nhiều nền tảng, cập nhật thay đổi và tránh quên hạn nộp | Actor rõ, xảy ra hằng ngày, từng có rủi ro quên deadline; chưa rõ công cụ tổng hợp phù hợp |
| 15 | Triển | So sánh code với bài mẫu để tìm lỗi | Học viên có code tự làm và bài mẫu/solution tham khảo | So sánh hai đoạn code, tìm khác biệt có ý nghĩa và lỗi logic thay vì chỉ khác format | Workflow 5 bước rõ, bottleneck là so sánh thủ công; rủi ro AI đọc code dài và chỉ sai chỗ |

### 3.2. Gom trùng / cluster (gom 15 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Học tập / tìm tri thức nền | #3, #4, #11, #12 | Người học phải đọc nhiều tài liệu, tìm phần trọng tâm, nối kiến thức nền với bài đang làm | #4 có scope sát lab nhất, tần suất cao nhất, metric thời gian rõ nhất |
| B — Tổng hợp thông tin từ nguồn rời rạc | #2, #5, #8, #9 | Input nằm ở nhiều kênh/file, người dùng phải gom lại thành action/document dễ hiểu | Phù hợp Workflow; rủi ro lớn thường là quyền truy cập và sai ngữ cảnh |
| C — Kiểm tra/chấm/debug theo tiêu chí | #1, #6, #13, #15 | Đối chiếu bài làm/code với checklist, rubric, bài mẫu hoặc lỗi thực tế để tìm điểm sai | #13 rất mạnh về tần suất và impact, nhưng cần boundary rõ để không biến thành làm bài thay |
| D — Quản lý tiến độ, deadline và planning | #7, #10, #14 | Cập nhật trạng thái, theo dõi deadline, phát hiện việc chưa xong, lập kế hoạch tiếp theo | Một phần có thể giải bằng rule/calendar trước khi dùng AI |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| Đọc và tìm kiến thức trọng tâm trong V-Learn trước mỗi buổi lab | Actor rất rõ: học viên K4B. Workflow hiện tại có thể vẽ được từ mở tài liệu → tìm → trích xuất → chuẩn bị lab. Impact có metric 70-90 phút/buổi và ảnh hưởng trực tiếp tới kết quả lab. | Cần làm rõ quyền truy cập/tải tài liệu từ V-Learn. Cần validation ngoài nhóm để biết bao nhiêu học viên gặp pain tương tự. |
| Debug code khi làm bài tập/đồ án lập trình | Tần suất cao 4-5 lần/tuần và hầu hết học viên lập trình đều gặp. Workflow có thể vẽ từ gặp lỗi → đọc log → khoanh vùng → sửa → chạy lại. Impact lớn vì lỗi code có thể chặn toàn bộ tiến độ bài tập/đồ án. | Chưa rõ AI có thật sự nhanh hơn search/Stack Overflow/manual debugging trong case cụ thể không. Cần boundary để AI không viết hộ toàn bộ bài và học viên vẫn hiểu lỗi. |
| Lội tin nhắn Discord để tìm link nộp bài, deadline và tài liệu bổ trợ | Pain lặp lại hằng ngày cho học viên và TA. Có thể so sánh rõ Rule bot, Workflow gom tin, hoặc Agent hỏi đáp. Output dễ đo bằng số thông báo/link bị bỏ sót. | Chat tự do có nhiều tiếng lóng, reply chéo, thông tin thiếu context. Quyền đọc lịch sử Discord có thể là rào cản. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Đọc và tìm kiến thức trọng tâm trong V-Learn trước mỗi buổi lab | 5 | 5 | 4 | 5 | 4 | 5 | 5 | 33 |
| Debug code khi làm bài tập/đồ án lập trình | 5 | 5 | 4 | 5 | 4 | 4 | 5 | 32 |
| Lội Discord để tìm link nộp bài, deadline và tài liệu bổ trợ | 5 | 4 | 4 | 4 | 4 | 5 | 5 | 31 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Đọc và tìm kiếm kiến thức trọng tâm trong kho tài liệu V-Learn trước mỗi buổi lab tại VinUni.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn bài V-Learn vì actor rất cụ thể: học viên K4B cần chuẩn bị trước mỗi buổi lab. Workflow hiện tại đủ rõ để vẽ và đo, từ mở tài liệu, lướt tìm, trích xuất kiến thức, đối chiếu với worksheet/lab task đến chuẩn bị note cá nhân. Pain có tần suất cao vì xảy ra trước hầu hết các buổi lab, không phải việc hiếm gặp. Impact cũng đo được bằng thời gian chuẩn bị, số concept trọng tâm bị bỏ sót và mức độ sẵn sàng khi vào lab. Bài này còn giúp nhóm so sánh rõ Rule, Workflow và Agent mà không cần xây một trợ lý AI quá rộng.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Debug code khi làm bài tập/đồ án là pain rất mạnh, tần suất cao và impact lớn. Nhóm chưa chọn vì cần boundary học thuật rất rõ để AI không làm bài thay, đồng thời cần kiểm chứng xem AI debug có nhanh và đúng hơn search/manual debugging trong case cụ thể không.

Discord deadline/link cũng rất gần với bối cảnh lớp, nhưng input là chat tự do nên nhiễu cao và dễ thiếu ngữ cảnh. Nếu làm nhanh trong lab, nhóm có thể bị kẹt ở quyền đọc lịch sử Discord và quy tắc phân loại tin nhắn.

WBS progress có workflow tốt và impact công việc rõ, nhưng domain chính thuộc trải nghiệm cá nhân/freelance nên không phải tất cả thành viên đều hiểu đủ sâu. Dữ liệu dự án thật cũng khó chia sẻ đầy đủ trong lab, nhất là phần map tên task với WBS của khách hàng.

Theo dõi deadline nhiều môn là vấn đề thật, nhưng hướng giải quyết đầu tiên có thể là calendar/checklist/rule notification thay vì AI. So sánh code với bài mẫu có workflow rõ, nhưng rủi ro AI chỉ ra sai khác biệt hoặc bị phụ thuộc vào bài mẫu quá nhiều.

Kiểm tra yêu cầu trước khi nộp bài và chấm bài Toán có bottleneck rõ, nhưng phần đầu có thể giải tốt bằng checklist/rule đơn giản, còn phần chấm Toán phụ thuộc OCR chữ viết tay/công thức nhiều hơn mức phù hợp cho pilot nhỏ. Các bài đọc paper/thiết kế experiment hay nhưng metric hiện chưa chắc bằng bài V-Learn.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Lo ngại chính là quyền truy cập và bản quyền tài liệu trên V-Learn. Nhóm chốt không làm bài toán "tự động crawl toàn bộ V-Learn", mà chỉ xét pilot với tài liệu học viên được phép tải/xem và tự đưa vào workflow. Triển và Giáp cũng nhắc rằng nếu chỉ cần sắp xếp tài liệu tốt hơn thì AI không cần thiết; vì vậy nhóm giữ non-AI baseline là checklist/tag tài liệu và chỉ dùng AI ở bước tìm/summary có trích nguồn.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview nội bộ nhóm | 5 thành viên | "Trước mỗi buổi lab phải mở nhiều tài liệu rồi tự lọc xem phần nào áp dụng ngay, rất dễ mất 70-90 phút." / "Nếu có phần gợi ý đúng đoạn cần đọc và có nguồn thì sẽ đỡ mất thời gian hơn." | Có thành viên cho rằng nếu tài liệu được đặt tên/tag tốt hơn thì chưa chắc cần AI. | Thu hẹp từ "trợ lý học tập V-Learn" thành "workflow tìm kiến thức trọng tâm từ tài liệu được phép dùng, có trích nguồn, học viên review trước khi tin". |
| Survey / poll | Chưa chạy survey toàn lớp; dùng nhóm 5 người làm mẫu ban đầu | 4/5 thành viên đánh giá pain đáng giải quyết vì ảnh hưởng trực tiếp tới chuẩn bị lab. Bài toán có khả năng mở rộng cho khoảng 35 học viên K4B nếu survey xác nhận. | Chưa có số liệu đại diện toàn lớp; chưa biết các bạn khác mất 70-90 phút hay ít hơn. | Ghi rõ baseline 70-90 phút là estimate ban đầu, cần đo bằng pilot 1-2 buổi lab trước khi khẳng định. |
| Log / ticket / review (nếu có) | Candidate notes từ phần pitch | Có dữ kiện ban đầu: tần suất trước mỗi buổi lab, actor là học viên K4B, workflow mở tài liệu → tìm → trích xuất lý thuyết áp dụng. | Chưa có log truy cập V-Learn hoặc ảnh survey đính kèm. | Không claim số liệu lớn; quyết định pilot nhỏ với tài liệu mẫu và đo lại thời gian thực tế. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không chỉ nằm ở việc "V-Learn có nhiều tài liệu", mà nằm ở đoạn học viên phải tự xác định tài liệu nào quan trọng cho buổi lab hiện tại và đoạn nào cần đọc trước. Nếu AI không trích được nguồn rõ ràng, output sẽ khó tin và người học vẫn phải quay lại đọc thủ công.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md` (chưa có file riêng; tóm tắt validation đang nằm trong bảng trên)

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| NotebookLM / notebook có source grounding | https://support.google.com/notebooklm/answer/17003757 | Cho người dùng đưa nguồn tài liệu vào notebook rồi hỏi đáp/tóm tắt dựa trên nguồn | Pattern phù hợp với bài học: câu trả lời cần bám vào tài liệu đã cung cấp | Không tự giải quyết quyền truy cập V-Learn; người dùng vẫn phải chọn/tải nguồn đúng | Nên bắt đầu bằng nguồn học viên được phép dùng và yêu cầu AI trả lời kèm citation |
| OpenAI vector stores / file search | https://platform.openai.com/docs/api-reference/vector-stores-files | Lưu file vào vector store, tìm đoạn liên quan để dùng cho hỏi đáp/tóm tắt | Hợp với bước chunk/index/search tài liệu học tập | Chất lượng phụ thuộc chunking, metadata, câu hỏi và kiểm soát hallucination | Bài toán nên dùng retrieval trước, rồi mới để AI tổng hợp; không để AI đoán từ trí nhớ chung |
| Microsoft Foundry RAG concepts | https://learn.microsoft.com/en-us/azure/foundry/concepts/retrieval-augmented-generation | Mô tả pattern Retrieve → Augment → Generate cho dữ liệu riêng/tài liệu thay đổi | Nêu rõ vai trò index, grounding data, citation và rủi ro retrieval sai | RAG vẫn có thể trả lời thiếu/chưa đúng nếu passage truy xuất kém | Cần metric riêng cho retrieval: đoạn trích có đúng nguồn không, có bỏ sót concept trọng tâm không |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm không nên build một agent tự động crawl V-Learn và tự quyết học thay người học. Hướng hợp lý hơn là Workflow/RAG nhỏ: học viên chọn tài liệu được phép dùng, hệ thống index/tìm đoạn liên quan, AI tạo study brief ngắn kèm nguồn, rồi học viên review. Rule vẫn hữu ích ở bước metadata/tag/checklist, nhưng phần "tìm đúng đoạn theo câu hỏi mơ hồ" cần AI hỗ trợ.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
CURRENT STATE — khoảng 70-90 phút trước mỗi buổi lab

[1 Xác định buổi lab / topic cần học: 5' - học viên]
→ [2 Mở V-Learn và từng tài liệu liên quan: 10' - học viên]
→ [3 Lướt slide/worksheet/reading để tìm keyword: 20' - học viên]
→ [4 Trích kiến thức trọng tâm và ghi chú lại: 25' - học viên, bottleneck]
→ [5 Đối chiếu với yêu cầu lab/bài nộp: 10' - học viên]
→ [6 Hỏi bạn/TA khi chưa rõ hoặc thiếu context: 10' - học viên/TA]
→ [7 Chuẩn bị note/câu hỏi trước khi vào lab: 5' - học viên]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Học viên K4B | Lịch học, tên buổi lab, worksheet | Topic cần chuẩn bị | 5 phút / trước mỗi buổi lab | Bước khởi động, chưa nghẽn |
| 2 | Học viên K4B | V-Learn, slide, worksheet, reading | Danh sách tài liệu cần xem | 10 phút / trước mỗi buổi lab | Có thể mất thời gian nếu tài liệu đặt tên chưa rõ |
| 3 | Học viên K4B | Các tài liệu đã mở | Các đoạn có vẻ liên quan | 20 phút / trước mỗi buổi lab | Search thủ công theo keyword, dễ bỏ sót synonym/khái niệm liên quan |
| 4 | Học viên K4B | Đoạn tài liệu liên quan | Ghi chú kiến thức trọng tâm | 25 phút / trước mỗi buổi lab | Bottleneck chính: phải đọc hiểu, lọc, viết lại |
| 5 | Học viên K4B | Ghi chú, worksheet/lab task | Checklist chuẩn bị | 10 phút / trước mỗi buổi lab | Dễ phát hiện thiếu concept muộn |
| 6 | Học viên, bạn học, TA | Câu hỏi chưa rõ | Câu trả lời hoặc hướng đọc tiếp | 10 phút / khi cần | Handoff sang bạn/TA, có thể chờ phản hồi |
| 7 | Học viên K4B | Note và checklist | Note cá nhân trước lab | 5 phút / trước mỗi buổi lab | Output cuối hiện tại |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck chính là bước 3-4: tìm đúng đoạn liên quan trong nhiều tài liệu rồi biến thành ghi chú trọng tâm. Keyword search thủ công không hiểu ngữ cảnh nên học viên phải đọc lướt nhiều trang để chắc mình không bỏ sót. Khi phần chuẩn bị bị chậm hoặc thiếu, vào lab dễ mất thời gian hỏi lại kiến thức nền thay vì tập trung thực hành.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — mục tiêu dưới 30 phút trước mỗi buổi lab

[1 Học viên chọn/tải tài liệu được phép dùng: 5' - người]
→ [2 Máy chunk/index tài liệu + gắn metadata buổi học: 3' - Rule]
→ [3 AI truy xuất đoạn liên quan theo topic/worksheet: 2' - AI]
→ [4 AI tạo study brief ngắn, có citation và câu hỏi tự kiểm: 3' - AI]
→ [5 Học viên mở citation, kiểm nguồn, sửa note: 10' - boundary]
→ [6 Học viên lưu note và câu hỏi cần hỏi TA: 5' - người]

Fallback: Nếu AI không đưa được citation rõ, trích sai nguồn, hoặc bỏ sót phần quan trọng, học viên bỏ study brief và quay lại workflow thủ công bằng keyword search/checklist. Output AI chỉ là bản nháp chuẩn bị học, không phải đáp án bài nộp.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 70-90 phút/buổi | Dưới 30 phút/buổi | Mỗi thành viên tự bấm giờ chuẩn bị cho 1-2 buổi lab trước/sau pilot |
| Số bước | 7 bước | 6 bước | So workflow thực tế trước/sau |
| Số bước thủ công | 7/7 | 3/6 | Đếm bước còn cần học viên tự làm: chọn tài liệu, review nguồn, lưu note/câu hỏi |
| Bottleneck chính | Tìm và trích kiến thức trọng tâm | Review citation và sửa note | Theo dõi bước tốn nhiều thời gian nhất sau pilot |
| Risk mới | Chủ yếu là mất thời gian/bỏ sót thủ công | AI trích sai nguồn, hallucination, vi phạm phạm vi tài liệu | Review citation bắt buộc; chỉ dùng tài liệu được phép |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Học viên K4B tại VinUni cần chuẩn bị kiến thức trước mỗi buổi lab. Actor này có cùng bối cảnh học, cùng kho tài liệu V-Learn và cùng áp lực hoàn thành bài lab đúng yêu cầu. |
| **Workflow** | Trước mỗi buổi lab, học viên mở V-Learn, tìm slide/worksheet/reading liên quan, đọc lướt để tìm keyword, trích kiến thức trọng tâm, đối chiếu với yêu cầu lab và chuẩn bị note/câu hỏi. Workflow hiện tại phần lớn làm thủ công. |
| **Bottleneck** | Bước nghẽn là tìm đúng đoạn liên quan và viết lại thành ghi chú trọng tâm. Học viên phải vừa đọc hiểu vừa tự quyết định phần nào thật sự cần cho lab, nên dễ mất 70-90 phút và vẫn có thể bỏ sót. |
| **Impact** | Mỗi buổi lab mất nhiều thời gian chuẩn bị, ảnh hưởng khoảng 35 học viên nếu pain phổ biến trong lớp. Khi chuẩn bị thiếu, học viên vào lab phải hỏi lại kiến thức nền hoặc mất thời gian tự đọc lại thay vì làm bài. |
| **Success Metric** | Giảm thời gian chuẩn bị từ 70-90 phút xuống dưới 30 phút/buổi. Study brief phải có citation cho các ý chính và không làm tăng số concept trọng tâm bị bỏ sót so với cách đọc thủ công. |
| **Boundary** | AI không tự crawl V-Learn nếu chưa có quyền, không dùng tài liệu ngoài phạm vi học viên cung cấp, không viết đáp án bài nộp thay học viên. AI chỉ gợi ý đoạn cần đọc, tóm tắt có nguồn và tạo câu hỏi tự kiểm; học viên vẫn review và chịu trách nhiệm học. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: "kiến thức trọng tâm" có thể khác nhau giữa từng học viên và từng buổi lab; "35 học viên" là quy mô lớp, chưa phải survey xác nhận tất cả đều gặp pain.
- Tôi sửa gì: thu hẹp success metric thành thời gian chuẩn bị, tỷ lệ citation đúng và số concept bị bỏ sót; giới hạn pilot vào tài liệu học viên được phép tải/xem.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: "trọng tâm" phụ thuộc vào topic lab, worksheet, nền tảng của học viên và cách diễn đạt trong tài liệu.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: bài toán cần chọn tài liệu, tìm đoạn liên quan, tổng hợp, trích nguồn, kiểm lại với worksheet và để người học review.

**Bài toán nhóm nằm ở ô nào:**

```text
Cao mơ hồ + cao phức tạp, nhưng workflow vẫn đi theo đường tương đối cố định nên chưa cần Agent tự lập kế hoạch.
```

**Vì sao (2-3 câu):**

```text
Input là nhiều tài liệu học tập và câu hỏi tự nhiên, nên Rule/keyword search đơn thuần dễ bỏ sót. Tuy nhiên chuỗi xử lý chính vẫn tuyến tính: chọn tài liệu → index → retrieve → summarize → human review. Vì vậy mức phù hợp nhất là Workflow có AI ở các bước retrieval/summarization, không phải Agent tự động toàn quyền.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Tạo checklist buổi lab, đặt tag tài liệu, dùng keyword search, lọc theo metadata tuần/buổi học | Đủ nếu tài liệu ít, tên file rõ, câu hỏi chỉ cần tìm đúng keyword | Bỏ sót synonym/khái niệm liên quan; không tóm tắt được đoạn dài; vẫn tốn thời gian đọc lướt | Dùng cho bước chunk/index/tag tài liệu và checklist nguồn |
| **Workflow** | Học viên chọn tài liệu → máy index → AI retrieve đoạn liên quan → AI tạo study brief có citation → học viên review | Đủ khi workflow cố định, input nằm trong tài liệu đã chọn và cần hỗ trợ ngôn ngữ/tổng hợp | Retrieval sai hoặc summary thiếu ý; cần review citation bắt buộc | Chọn làm mức chính cho pilot |
| **Agent** | Agent tự truy cập nhiều nguồn, tự hỏi lại khi thiếu thông tin, tự lập plan học, tự tạo quiz/lộ trình học cá nhân | Chỉ cần nếu bài toán có nhiều nhánh, nhiều công cụ và cần tự quyết định bước tiếp theo | Quá rộng cho lab, nhiều quyền truy cập, khó kiểm soát hallucination/bản quyền | Chưa chọn; có thể xem xét sau khi workflow nhỏ chạy ổn |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?  
   Rule chưa đủ để giải 70-80% case vì học viên thường hỏi theo ngữ cảnh, không chỉ theo keyword. Rule hữu ích cho checklist/tag tài liệu, nhưng không thay được bước hiểu và nối ý giữa worksheet với nhiều đoạn tài liệu.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?  
   Các bước chính đi khá thẳng: chọn tài liệu → index → retrieve → summarize → review. Chỉ có nhánh fallback khi AI không có citation rõ hoặc học viên phát hiện đoạn trích không đúng.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?  
   Chưa cần trong pilot đầu tiên. Nhóm chỉ cần workflow bán thủ công với tài liệu đã chọn, chưa cần agent tự truy cập V-Learn hay tự quyết định kế hoạch học.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?  
   Học viên là người phát hiện đầu tiên ở bước review citation. Nếu lỗi nhỏ, học viên sửa note trong khoảng 5-10 phút; nếu lỗi lớn hoặc không có nguồn, học viên bỏ output AI và quay lại đọc thủ công.
5. Có hạ được từ Agent → Workflow → Rule không?  
   Có. Bản pilot hạ về Workflow, trong đó các phần đơn giản như tag tài liệu, checklist và lọc theo buổi học có thể làm bằng Rule.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Workflow phù hợp vì bài toán có chuỗi bước cố định và có human boundary rõ ở bước review nguồn. AI có giá trị ở đoạn tìm đoạn liên quan theo ngữ cảnh và tóm tắt thành study brief ngắn, còn rule/script đủ cho việc index, tag và checklist. Mức này giữ được lợi ích của AI nhưng không giao quyền tự động quá rộng như Agent. Nó cũng dễ pilot trong lab vì có thể chạy bán thủ công với tài liệu mẫu.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule/keyword search đơn giản không đủ vì học viên không chỉ tìm đúng từ khóa, mà cần biết đoạn nào quan trọng cho bài lab hiện tại. Nếu tài liệu dùng từ khác với câu hỏi của học viên, rule dễ bỏ sót. Vì vậy cần thêm AI retrieval/summarization, nhưng vẫn giữ review của người học.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Học viên K4B tại VinUni cần chuẩn bị kiến thức trước mỗi buổi lab từ tài liệu V-Learn được phép xem/tải. |
| **Workflow** | Hiện tại: xác định topic buổi lab → mở V-Learn và tài liệu liên quan → lướt tìm keyword → trích kiến thức trọng tâm → đối chiếu worksheet → hỏi bạn/TA nếu chưa rõ → chuẩn bị note cá nhân. |
| **Bottleneck** | Bước tìm và trích kiến thức trọng tâm mất nhiều thời gian nhất vì học viên phải đọc nhiều nguồn, hiểu ngữ cảnh và tự quyết định phần nào áp dụng cho lab. |
| **Impact** | Baseline ban đầu khoảng 70-90 phút chuẩn bị trước mỗi buổi lab; nếu pain phổ biến, tác động có thể ảnh hưởng phần lớn lớp K4B khoảng 35 học viên. Khi chuẩn bị thiếu, thời gian trong lab bị chuyển sang đọc lại lý thuyết hoặc hỏi lại kiến thức nền. |
| **Success Metric** | Pilot thành công nếu thời gian chuẩn bị giảm xuống dưới 30 phút/buổi, 90% ý chính trong study brief có citation đúng nguồn, và số concept trọng tâm bị bỏ sót không tăng so với cách đọc thủ công. |
| **Boundary** (làm / không làm) | Làm: hỗ trợ tìm đoạn liên quan, tạo study brief, trích nguồn, gợi ý câu hỏi tự kiểm. Không làm: crawl V-Learn khi chưa có quyền, dùng tài liệu ngoài phạm vi học viên cung cấp, viết đáp án bài nộp thay học viên, tự khẳng định kiến thức không có nguồn. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | AI can thiệp sau khi học viên đã chọn/tải tài liệu được phép dùng và trước khi học viên tự đọc sâu/ghi chú. AI tạo bản nháp có citation để học viên review trước khi dùng. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow: dùng rule/script cho index/tag tài liệu, AI cho retrieval/summarization, và học viên review nguồn trước khi tin. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI trích sai nguồn, bỏ sót concept quan trọng hoặc tóm tắt quá tự tin. Người kiểm tra là học viên ở bước review citation; với pilot, nhóm cũng có thể nhờ TA hoặc bạn học đối chiếu study brief với worksheet/tài liệu gốc. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor là học viên K4B và workflow chuẩn bị trước lab đã mô tả được thành 7 bước cụ thể. |
| Baseline + metric đo được chưa? | Not Yet | Có estimate 70-90 phút/buổi nhưng cần đo thật trong 1-2 buổi lab để xác nhận baseline và variance giữa các học viên. |
| Data/input đủ dùng chưa? | Yes cho pilot, Not Yet cho tích hợp trực tiếp | Pilot có thể dùng tài liệu học viên được phép tải/xem và tự đưa vào workflow. Tích hợp trực tiếp với V-Learn cần kiểm tra quyền truy cập và bản quyền. |
| AI sai, hậu quả chấp nhận được không? | Yes | Output AI chỉ là study brief bản nháp, không tự nộp bài và không thay quyết định của học viên. Lỗi có thể bị phát hiện qua citation review và fallback về đọc thủ công. |
| Có người review/owner không? | Yes | Học viên là reviewer chính; trong pilot nhóm 5 người review chéo study brief và có thể hỏi TA khi cần kiểm tra concept quan trọng. |
| Có cách non-AI đơn giản hơn không? | Yes | Có thể dùng checklist/tag tài liệu/keyword search. Cách này nên làm baseline, nhưng chưa xử lý tốt câu hỏi mơ hồ và tổng hợp nhiều đoạn liên quan. |

**Decision:**

```text
Go cho pilot nhỏ, Not Yet cho tích hợp tự động trực tiếp vào V-Learn.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Nhóm chọn Go ở mức pilot vì actor, workflow và bottleneck đã rõ, đồng thời impact ban đầu có thể đo bằng thời gian chuẩn bị. Rủi ro lớn nhất là quyền truy cập và AI trích sai nguồn, nên scope pilot chỉ dùng tài liệu được phép và bắt buộc citation review. Nhóm chưa nên làm tích hợp trực tiếp V-Learn hoặc agent tự crawl vì chưa xác nhận permission và chưa có validation toàn lớp. Sau pilot 1-2 buổi, nhóm sẽ đo lại baseline và quyết định có mở rộng hay không.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Data: chọn tài liệu của 1-2 buổi lab gần nhất mà học viên được phép xem/tải, gồm slide, worksheet và reading nếu có.

Chạy tay: mỗi thành viên chuẩn bị cùng một buổi lab bằng cách đưa tài liệu vào workflow, nhập topic/worksheet question, nhận study brief có citation, rồi tự mở citation kiểm lại.

Đo 3 số: (1) tổng thời gian chuẩn bị trước lab, (2) tỷ lệ ý chính có citation đúng nguồn, (3) số concept trọng tâm bị thiếu hoặc phải hỏi lại trong lab.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Cần survey/poll thêm 5-10 học viên ngoài nhóm để xác nhận tần suất và thời gian chuẩn bị thực tế. Cần kiểm tra quyền sử dụng/tải tài liệu từ V-Learn cho mục đích pilot và xác định nhóm chỉ dùng tài liệu được phép. Cần thử với ít nhất 2 buổi lab để xem AI có trích nguồn ổn định không.
```

**Nếu No-Go — làm gì thay AI:**

```text
Nếu pilot thất bại hoặc không được phép dùng tài liệu, nhóm chuyển sang non-AI alternative: checklist chuẩn bị trước lab, bảng mapping topic → tài liệu → trang/slide cần đọc, và quy ước đặt tag/tên file rõ hơn trong nhóm.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng AI nếu trong 2 buổi lab liên tiếp thời gian chuẩn bị vẫn trên 40 phút, dưới 80-90% ý chính có citation đúng, hoặc xuất hiện lỗi nghiêm trọng như bịa nguồn/bịa khái niệm. Khi đó quay về checklist + keyword search + note thủ công và chỉ giữ phần tag/index tài liệu nếu hữu ích.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 15 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
