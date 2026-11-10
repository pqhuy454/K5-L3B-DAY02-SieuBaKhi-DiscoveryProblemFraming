# Báo cáo cá nhân — 2A202603886_DangDucMinh

## 1. Thông tin học viên

- Họ tên: Đặng Đức Minh
- MSSV: 2A202603886
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: SieuBaKhi
- Link repo nhóm: https://github.com/pqhuy454/K5-L3B-DAY02-SieuBaKhi-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin|Khi tôi muốn kiểm tra thông báo từ các ứng dụng liên lạc liên quan tới công việc/ học tập (Zalo/Discord/Telegram/...) Tôi cần lướt và kiểm tra rất nhiều kênh, nhiều tin nhắn ở nhiều ứng dụng mà đa phần là không liên quan hoặc hữu ích |Cá nhân |30p/ứng dụng/ngày, từ 2-4 ứng dụng|
| 2 | Lặp lại|Khi bắt đầu tham gia vào một dự án mới, tôi thường phải thực hiện nhiều bước setup như clone github, cài đặt môi trường, dependencies, extension |Contributors |15p-45p/project tùy độ phức tạp và platform |
| 3 | Lặp lại|Khi phải nộp báo cáo của dự án/ bài tập, tôi thường xuyên được yêu cầu phải tạo log/ documents những gì đã làm, thay đổi ở trong dự án |Creator/Contributors |1-3 tiếng ở dự án nhỏ tới hàng tuần ở các dự án lớn |
| 4 | Tốn thời gian|Khi tìm kiếm cơ hội việc làm, tôi thường phải nộp nhiều loại CV khác nhau cho các công việc khác nhau (Dev/BA/Tester/...) cho các công ty khác nhau ở các nền tảng khác nhau.|Free agents |30p-45p/1 công ty|
| 5 | Cần đọc và tổng hợp nhiều thông tin|Khi tôi muốn sử dụng một dự án open-source trên github, thường những dự án nhỏ không được hỗ trợ tốt trên nhiều configuration(CPU/GPU/OS) khiến cho xuất hiện bug lạ mà không có document |Users |Với những người thành thạo công nghệ vẫn có thể tốn hàng giờ để debug >=1h, với những user không thạo có thể không làm được |
| 6 | Cần đọc và tổng hợp nhiều thông tin|Hằng ngày, khi tôi dậy vào buổi sáng cần check mail, thông báo công việc, tiến độ làm việc, deadline,.. |Workers |30p-45p/ngày |
| 7 | Pain từ người khác|Khi làm bài tập nhóm, dự án nhóm, nhiều khi đồng đội không làm đúng theo tiêu chuẩn được đặt ra (khác format/thiếu file/sai tên) gây mất thời gian rà soát, chỉnh sửa|Teammates/Leader |5p-10p với lỗi nhỏ, >=1h với lỗi lớn, có thể gây mất điểm |
| 8 | Pain từ người khác|Khi phải merge code từ nhiều branch khác nhau, khác biệt giữa coding convention, naming convention, cách tổ chức code gây ra merge conflict khó giải quyết và tốn thời gian |Project manager |<30p với conflict nhỏ, >1h tới nhiều ngày với conflict phức tạp |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Tinh chỉnh CV theo từng Job Description(JD). **BỎ** vì AI thường không thể nắm rõ tất cả skill set, kinh nghiệm làm việc của người dùng, có thể 
- Giải quyết merge conflict lớn. **GIỮ** vì AI hiện giờ có khả năng code rất tốt, chỉ cần cung cấp đủ document và log có thể giải quyết conflict nhanh và chuẩn.
- Tạo log/ documents cho dự án. **GIỮ** vì việc tạo log và viết document thường tốn nhiều thời gian trong cả quá trình làm việc, tự động hóa bằng AI sẽ giúp tiết kiệm nhiều thời gian, đồng thời AI cũng rất giỏi trong việc summerize code.
- Đọc và tổng hợp tài liệu kỹ thuật. **BỎ** vì hiện tại AI vẫn còn chưa hoàn toàn chuẩn trong việc tìm kiếm nguồn dữ liệu chuyên sâu, ngành ngách, vẫn còn hay hallucinate hoặc đưa thông tin outdated
---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp thông tin từ các ứng dụng liên lạc|Đây là vấn đề phổ biến, nhiều người trong thị trường lao động gặp phải, nhất là quản lý của các công ty, dự án lớn |Nguy cơ về bảo mật thông tin cá nhân, thông tin nhạy cảm |
| 2 | Cài đặt môi trường khi bắt đầu dự án mới|Đây là vấn đề chung của những người tham gia nhiều dự án như FreeLancer, Open-source contributors, sinh viên, nhân viên out-sourcing |Đã có Docker giúp giải quyết được nhiều trường hợp. Khả năng cài đặt và chạy những ứng dụng, extensions, đoạn code có chứa mã độc, không an toàn, không phù hợp|
| 3 | Tổng hợp log, document cho dự án|Mọi dự án đều nên được log và documented đầy đủ để hỗ trợ quá trình phát triển sau này, debugging và cho người khác sử dụng dễ dàng |Rò rỉ mã nguồn |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu ngày làm việc/học tập với hàng chục tin nhắn trên Zalo, Discord, Telegram, tôi muốn lọc nhanh các tin nhắn quan trọng và task cần xử lý, để không bỏ lỡ hạn chót hoặc thông báo khẩn mà không mất cả tiếng lướt từng kênh chat |
| Actor | Sinh viên năm cuối, người đi làm/quản lý dự án sử dụng nhiều nền tảng chat cùng lúc |
| Thời điểm / bối cảnh | Đầu giờ sáng (8h–9h) hoặc cuối ngày làm việc |
| Quy trình hiện tại (3–7 bước) | 1. Mở lần lượt từng app (Zalo, Discord, Telegram, Messenger) · 2. Lướt qua danh sách các nhóm chat và tin nhắn cá nhân · 3. Đọc nội dung từng nhóm/thread đang có thông báo mới · 4. Tự phân loại tin nào là chat phiếm, tin nào có task/deadline · 5. Copy/ghi chú các task quan trọng ra app ghi chú hoặc to-do list |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & 4 (Đọc và tự lọc thông tin quan trọng): mất 40–60 phút/ngày vì tin nhắn rác, spam và chat phiếm chiếm đa số |
| Impact (nếu không giải thì sao) | Tốn 60–90 phút mỗi ngày cho việc đọc tin; thường xuyên bị trôi tin nhắn khẩn của mentor/đồng đội dẫn đến trễ việc |
| Success metric (baseline → target) | Thời gian lọc và cập nhật task đầu ngày giảm từ 60 phút xuống dưới 15 phút; tỉ lệ bỏ sót tin nhắn khẩn/tag tên bằng 0% |
| Phương án không dùng AI | Bật notification VIP/Mention only, tắt thông báo nhóm không quan trọng, đặt quy ước tag @here/@all khi có việc khẩn |
| Giả thuyết về AI (nếu có) | AI quét tóm tắt các đoạn chat chưa đọc trong kênh công việc, trích xuất các action item / deadline và lập danh sách tóm tắt |
| Cảm nhận nhanh | Workflow |


```text
HIỆN TẠI — khoảng 60 phút/ngày

[1. Mở 3-4 app chat: 5'] → [2. Lướt tìm nhóm có tin mới: 10']
→ [3. Đọc lướt từng kênh/thread: 20'] ← BOTTLENECK
→ [4. Tự lọc tin quan trọng & deadline: 15'] ← BOTTLENECK
→ [5. Ghi chú task ra to-do list: 10']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi clone một repo dự án mới về máy cá nhân, tôi muốn cài đặt đúng và đủ các dependencies/configurations tương thích với hệ điều hành, để bắt tay vào chạy và test mã nguồn ngay mà không bị lỗi môi trường |
| Actor | Lập trình viên mới tham gia dự án (Fresher/Intern), sinh viên làm bài tập lớn, Open-source contributor |
| Thời điểm / bối cảnh | Buổi onboarding đầu tiên hoặc khi bắt đầu một đồ án môn học mới |
| Quy trình hiện tại (3–7 bước) | 1. Clone repository từ GitHub/GitLab · 2. Đọc file README.md hoặc tài liệu setup (nếu có) · 3. Cài đặt runtime, SDK, database, dependencies theo hướng dẫn · 4. Tạo và cấu hình file biến môi trường (.env) · 5. Chạy lệnh start/build thử · 6. Gặp lỗi xung đột version (OS/Node/Python/DB) · 7. Tìm kiếm cách fix trên StackOverflow/GitHub Issues và cấu hình lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 6 & 7 (Debug lỗi môi trường và xung đột thư viện): mất 45–120 phút do tài liệu setup bị cũ hoặc khác hệ điều hành (Windows vs MacOS/Linux) |
| Impact (nếu không giải thì sao) | Chậm tiến độ onboarding từ nửa ngày đến 2 ngày; tạo tâm lý nản lòng cho người mới; tốn thời gian của senior/leader khi phải ngồi hỗ trợ gỡ lỗi |
| Success metric (baseline → target) | Thời gian setup từ lúc clone code đến khi chạy thành công giảm từ 90 phút xuống dưới 20 phút; tỉ lệ setup lỗi giảm 80% |
| Phương án không dùng AI | Đóng gói toàn bộ dự án bằng Docker (Dockerfile, docker-compose) hoặc viết script setup tự động (setup.sh/setup.bat), duy trì file .env.example chuẩn |
| Giả thuyết về AI (nếu có) | AI đọc log lỗi build/start, đối chiếu với cấu hình OS và tự sinh lệnh fix hoặc điều chỉnh config tương thích |
| Cảm nhận nhanh | Rule (ưu tiên Docker/Script) hoặc Workflow |


```text
HIỆN TẠI — khoảng 90 phút/lần onboarding

[1. Clone repo: 5'] → [2. Đọc README: 10'] → [3. Cài runtime & dependencies: 15']
→ [4. Cấu hình .env & DB: 15'] → [5. Chạy build/run thử: 5']
→ [6. Gặp lỗi build/version mismatch: 20'] ← BOTTLENECK
→ [7. Search StackOverflow & sửa cấu hình: 20'] ← BOTTLENECK
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi hoàn thành một đợt phát triển tính năng (sprint) hoặc chuẩn bị nộp bài tập lớn, tôi muốn tổng hợp nhanh danh sách thay đổi và cập nhật tài liệu kỹ thuật, để các thành viên khác hiểu code và giảng viên/khách hàng nghiệm thu dễ dàng mà không phải lục từng commit |
| Actor | Trưởng nhóm kỹ thuật, thành viên làm đồ án, lập trình viên bàn giao tính năng |
| Thời điểm / bối cảnh | Cuối mỗi sprint 2 tuần hoặc trước hạn nộp đồ án/nghiệm thu dự án |
| Quy trình hiện tại (3–7 bước) | 1. Mở Git log, Pull Requests và danh sách task trên Jira/Trello · 2. Đọc lại từng commit/PR để nhớ lại các thay đổi logic · 3. Soạn tài liệu changelog và cập nhật tài liệu API/hướng dẫn sử dụng · 4. Rà soát lại với code thực tế xem có mô tả thiếu endpoint/param nào không · 5. Format lại tài liệu vào file Markdown/Word và commit/gửi báo cáo |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3 (Đọc lại commit và tự viết narrative/tài liệu): mất 60–120 phút vì code nhiều file, commit message sơ sài (fix bug, update) khiến việc xâu chuỗi thông tin rất mệt |
| Impact (nếu không giải thì sao) | Tốn 2–3 tiếng mỗi lần nộp bài; tài liệu thường bị bỏ qua hoặc viết sơ sài đối phó, khiến người sau vào đọc không hiểu, khó bảo trì |
| Success metric (baseline → target) | Thời gian tạo changelog & draft document giảm từ 90 phút xuống dưới 20 phút; độ bao phủ thay đổi (các file/hàm quan trọng) đạt trên 90% |
| Phương án không dùng AI | Ép chuẩn Conventional Commits (ví dụ feat:, fix:) và dùng công cụ tự động sinh changelog (như standard-version, git-cliff) |
| Giả thuyết về AI (nếu có) | AI đọc git diff / PR commits và tự sinh mô tả tóm tắt kỹ thuật dạng Markdown |
| Cảm nhận nhanh | Workflow |


```text
HIỆN TẠI — khoảng 90 phút/sprint

[1. Gom Git log & PRs: 10'] → [2. Đọc code diff & commit cũ: 30'] ← BOTTLENECK
→ [3. Viết nháp changelog & API doc: 30'] ← BOTTLENECK
→ [4. Rà soát đối chiếu lại với code: 15']
→ [5. Format Markdown & commit: 5']
```

### Card muốn pitch nhất

- Card số: 1 (Tổng hợp thông tin từ các ứng dụng liên lạc)
- Vì sao: Đây là vấn đề xảy ra hằng ngày với tần suất rất cao (mỗi sáng), ảnh hưởng trực tiếp đến năng suất làm việc của cá nhân lẫn tiến độ dự án nhóm. Vấn đề có baseline đo lường rõ ràng (60 phút/ngày) và có thể thử nghiệm pilot ngay lập tức mà không phụ thuộc vào chu kỳ sprint.
- Câu hỏi muốn nhóm phản biện: "Việc truy cập tin nhắn qua API hoặc bot bên thứ ba có gặp rào cản lớn về bảo mật dữ liệu riêng tư (privacy) không, và liệu các thành viên/quản lý có sẵn sàng phân quyền cho công cụ đọc tin nhắn trong các nhóm chat dự án không?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Rất khó tích hợp API để đọc tin nhắn từ nhiều ứng dụng đóng (như Zalo, Telegram cá nhân) do chính sách bảo mật khắt khe | Đồng ý | Thu hẹp phạm vi kiểm chứng ban đầu: chỉ tập trung vào các nhóm làm việc/học tập có hỗ trợ Webhook/Bot API mở (Discord server lớp, Telegram group dự án), không quét tin nhắn cá nhân |
| Success metric mới chỉ đo về tốc độ (từ 60' xuống 15'), chưa có thước đo về độ chính xác và chất lượng lọc tin | Đồng ý | Bổ sung thêm metric chất lượng: "Tỉ lệ bỏ sót tin nhắn khẩn/tag tên trực tiếp bằng 0%, mọi tin nhắn có mention phải được giữ nguyên văn" |
| Các công cụ chat hiện tại đã có bộ lọc (Mention only, VIP notifications, Pin message), liệu giải pháp Rule đơn giản đã đủ chưa? | Không đồng ý | Làm rõ vai trò: Rule chỉ giúp lọc ai gọi mình, nhưng không tóm tắt được chuỗi thảo luận dài 50+ tin nhắn để rút ra việc cần làm. Do đó kết hợp Rule để lọc kênh + AI để tóm tắt |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| **Pitch Problem Card** | Đề xuất và thuyết trình Candidate #1: Lọc và tổng hợp thông tin quan trọng / task cần làm từ các kênh chat nhóm dự án mỗi sáng để tránh trôi deadline. | Card nhận được sự quan tâm lớn của nhóm, đạt điểm cao nhất (34/35) trong bảng chấm điểm shortlist và được chọn làm bài toán chung của nhóm. |
| **Phản biện bài của bạn khác** | Câu hỏi tôi đã đặt:<br>• Cho Candidate #4 (Huy): *"Làm sao để biết bản tóm tắt của AI là chính xác, không bịa kiến thức (hallucination) mà người học không phải mất công đọc lại slide gốc để đối chiếu?"*<br>• Cho Candidate #6 (Huy): *"Tính năng khôi phục phiên làm việc (Restore Session) của VS Code và trình duyệt đã hỗ trợ việc này, liệu một script tự động có giải quyết triệt để hơn không?"* | Giúp Huy và nhóm nhận ra Candidate #4 có rủi ro ảo giác cao và đã có các công cụ mạnh như NotebookLM giải quyết; còn Candidate #6 thì dùng Rule/Script đơn giản là đủ, không cần dùng AI. |
| **Nhận phản biện** | Câu hỏi tôi nhận được: Huy hỏi: *"Các nền tảng như Zalo/Telegram cá nhân có chính sách bảo mật API rất khắt khe, làm sao công cụ có thể đọc được tin nhắn mà không vi phạm quyền riêng tư?"* | Tôi đã sửa gì: Thu hẹp phạm vi kiểm chứng ban đầu: loại bỏ tin nhắn riêng tư (DM) và Zalo cá nhân; chỉ tập trung vào các kênh dự án mở có bot gia nhập chính thức (Discord server lớp, Telegram group dự án) và biến điều này thành Boundary bắt buộc của giải pháp. |
| **Gom cluster / cây OST** | Đảm nhận vai trò chính: Phân loại 6 candidate của 2 thành viên thành 3 cụm (Cluster A, B, C); xây dựng cây Opportunity Solution Tree (OST) với 1 Outcome cốt lõi và 3 Opportunity nhánh, đồng thời gạch bỏ 4 ý tưởng giải pháp trá hình đội lốt cơ hội. | Định hình khung tư duy "Problem-first" rõ ràng cho cả nhóm, giúp nhóm không bị sa đà vào việc nghĩ tính năng/công cụ; trở thành nội dung Mục 2.2 và 2.3 trong `group_report.md`. |
| **Chọn candidate problem** | Cùng Huy chấm điểm 3 candidate shortlist theo 7 tiêu chí định lượng; viết phần phân tích so sánh và giải thích vì sao loại Candidate #4 và Candidate #6. | Thống nhất chọn Candidate #1 với 34 điểm một cách khách quan, dựa trên dữ liệu và lập luận chặt chẽ chứ không bỏ phiếu theo cảm tính. |
| **Kiểm chứng / research** | Hỗ trợ Huy xây dựng Assumption Map với 5 giả định; cùng phân tích kết quả phỏng vấn The Mom Test của bạn Hoàng và bạn Linh. | Xác nhận 1 tín hiệu phản bác quan trọng: người dùng dùng tag @mention và tin nhắn ghim thủ công xử lý được 60–70% công việc; từ đó làm rõ AI chỉ cần tập trung xử lý 30–40% tin nhắn ngữ cảnh tự do còn lại. |
| **Quy trình nhóm** | Đảm nhận vai trò chính: Xây dựng bảng quy trình As-Is (5 bước, 60', xác định bottleneck 35' ở bước 3 & 4) và quy trình To-Be (3 tầng: Rule 8:00 AM $\rightarrow$ AI 8:01 AM $\rightarrow$ Human 8:15 AM); lập bảng before/after và trực tiếp lập trình sinh 2 biểu đồ PNG chuẩn Draw.io dark-theme. | Hoàn thiện Mục 4 trong `group_report.md` và tạo ra 2 file sơ đồ quy trình trực quan `cp5-workflow-current.png`, `cp5-workflow-future.png` trong `report/assets/`. |
| **Problem Statement** | Đảm nhận vai trò chính: Soạn thảo Problem Statement v0 (CP5) và nâng cấp lên Problem Statement v1 (CP6) với đầy đủ 9 trường; xây dựng bảng so sánh Delta v0 vs v1 và bộ 4 tiêu chí đánh giá đầu ra của AI (Task Recall, Deadline Accuracy, Source Traceability, Digest Readability). | Hoàn thiện Mục 5 và Mục 7 trong `group_report.md`, bảo đảm các thước đo đều có baseline, target và cách đo định lượng theo đúng rubric. |
| **Mức can thiệp AI** | Đảm nhận vai trò chính: Phân tích ma trận Ambiguity $\times$ Complexity (High $\times$ Low-to-Med); lập bảng so sánh 4 mức (No AI, Rule, Workflow, Agent) để khẳng định mức Workflow with AI; hoàn thiện AI Canvas rút gọn và trả lời 2 câu hỏi của Google PAIR. | Hoàn thiện Mục 6 trong `group_report.md`, chứng minh rõ ràng vì sao Rule là không đủ và vì sao Agent là quá thừa thãi/nguy hiểm. |
| **Quyết định** | Cùng Huy thảo luận đánh giá 4 rủi ro lớn (Value, Usability, Feasibility, Viability); thống nhất quyết định GO (Small Pilot trong 2 tuần) và đóng góp xây dựng 3 điều kiện dừng định lượng (Stopping Threshold). | Hoàn thiện Mục 8 trong `group_report.md`, giúp kế hoạch thử nghiệm thực tế và có phương án quay về an toàn nếu không đạt kỳ vọng. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **CP1 Scan** | Brainstorm các góc nhìn và gợi ý thêm các tình huống gặp vấn đề trong học tập/làm việc hàng ngày. | Gợi ý nhanh các nhóm tình huống đa dạng (tài liệu, môi trường kỹ thuật, tin nhắn). | Các gợi ý ban đầu toàn là "giải pháp trá hình" (ví dụ: "cần chatbot hỗ trợ", "cần app tự động...") và các dấu hiệu mơ hồ kiểu "cảm thấy mất thời gian". | Viết lại toàn bộ 8 bài toán theo format Job Story chuẩn, loại bỏ chữ "cần AI/app", đưa vào dấu hiệu đo đếm thật (60 phút, 50–100 tin nhắn, 3 lần mở app). |
| **CP2 Problem Card** | Đóng vai trò Product Manager khó tính để phản biện điểm yếu của Problem Card #1. | Đặt ra câu hỏi rất sắc bén về chính sách bảo mật API của Zalo và Telegram cá nhân. | AI tự đề xuất quy trình As-Is rất chung chung, không tính được số phút cụ thể từng bước và không chỉ rõ được bước nào là bottleneck chính. | Tự tính toán mốc thời gian thực tế (tổng 60 phút, bước 3 & 4 chiếm 35 phút); bổ sung phương án không dùng AI (No-AI baseline) bằng cách dùng bộ lọc và ghim tin nhắn. |
| **CP4 Research** | Tìm kiếm tài liệu, tính năng tương tự trên thị trường của các nền tảng lớn (Slack, Discord, Telegram). | Cung cấp từ khóa chính xác về các tính năng như "Slack AI Conversation Summaries" hay "Discord Conversation Summaries". | Đưa ra một số URL bị 404 (link chết) hoặc bịa đặt tính năng không có thật trên Discord. | Tự tay truy cập và kiểm tra từng đường link trên trình duyệt, thay thế bằng các liên kết chính thức sống 100% (help center của Slack, blog chính thức của Discord, repo GitHub mã nguồn mở của Telegram). |
| **CP5 Quy trình** | Gợi ý phân tách các tầng xử lý và viết code Mermaid ban đầu. | Giúp cấu trúc luồng tuần tự theo các mốc giờ (8:00 AM, 8:01 AM, 8:15 AM). | Sơ đồ Mermaid bị lỗi cú pháp render trên trình soạn thảo; thiết kế ban đầu thiếu phương án quay về (Fallback) khi API lỗi và không thể hiện rõ bước kiểm soát của con người (HITL). | Thay thế Mermaid bằng việc viết script C# kết xuất ra 2 biểu đồ PNG Draw.io dark-theme nền trong suốt; bổ sung ranh giới an toàn (Boundary) và phương án dự phòng (Fallback) khi bot mất mạng. |
| **CP5–6 Problem Statement** | Rà soát các trường trong Problem Statement v0 và v1 xem có bị thiếu sót hay mơ hồ không. | Nhắc nhở cần phải có metric đo lường định lượng và chỉ số đo chất lượng của AI chứ không chỉ đo mỗi thời gian. | Gợi ý các metric viển vông kiểu "tăng 100% hiệu suất học tập" hoặc "người dùng cảm thấy hài lòng". | Đưa ra các chỉ số cụ thể: thời gian giảm từ 60' xuống 12–15', tỉ lệ bỏ sót deadline bằng 0%, và tỉ lệ chấp thuận task $\ge 85\%$ đo bằng nhật ký 2 tuần pilot. |
| **CP6 Mức can thiệp / quyết định** | Thử nghiệm tranh luận xem có nên dùng mức Agent tự trị đa tác nhân hay không. | Chỉ ra các rủi ro kỹ thuật khi AI tự gửi tin nhắn (hallucination, spam nhóm). | Xu hướng ban đầu của AI luôn muốn "bán" giải pháp Agent phức tạp, đa tác nhân để nghe có vẻ tân tiến. | Kiên quyết từ chối Agent, chọn Workflow with AI kết hợp con người bấm duyệt (HITL); thiết lập 3 ngưỡng dừng định lượng cực kỳ thực tế nếu pilot không đạt hiệu quả. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua phần trình bày của Huy về tóm tắt slide (Candidate #4) và khôi phục workspace (Candidate #6), tôi nhận ra bài học về việc tránh lạm dụng AI cho các bài toán đã có giải pháp tối ưu. Tóm tắt tài liệu đã được các công cụ lớn như NotebookLM giải quyết hiệu quả. Khôi phục tab làm việc chỉ cần script tự động hóa hoặc tính năng Restore Session có sẵn của hệ thống. Một bài toán chỉ nên áp dụng AI khi quy trình thủ công gây nghẽn nghiêm trọng và các giải pháp Rule hoặc công cụ hiện hữu không thể xử lý được.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm gặp bẫy "solution-first" ở giai đoạn đầu xây dựng cây OST tại CP3. Cả hai thành viên đều tập trung thảo luận về tính năng kỹ thuật như xây dựng Discord bot bằng LangChain, tạo dashboard hoặc gửi email tự động thay vì xác định vấn đề của người dùng. Nhận thấy các nhánh này đều là giải pháp công nghệ, nhóm đã loại bỏ toàn bộ và định nghĩa lại 3 Opportunity cốt lõi: tin nhắn quan trọng bị trôi giữa tin nhắn rác, các cuộc thảo luận kéo dài gây mất thời gian theo dõi, và nguy cơ bỏ sót deadline do không thể đọc hết các kênh mỗi sáng.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã thay đổi phạm vi bài toán sau phản biện của Huy về tính khả thi API tại Problem Card #1. Ban đầu, tôi đề xuất hệ thống đọc tin nhắn từ cả Zalo cá nhân, Telegram và Discord. Huy chỉ ra rằng Zalo và tin nhắn riêng tư (DM) không cung cấp API mở hợp pháp, việc can thiệp sẽ vi phạm chính sách bảo mật và điều khoản dịch vụ. Tôi đồng thuận và thu hẹp phạm vi: hệ thống chỉ hoạt động trên các kênh dự án mở có phân quyền bot chính thức của Discord và Telegram, đồng thời thiết lập ranh giới an toàn (Boundary) không truy cập tin nhắn riêng tư.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Quá trình phỏng vấn The Mom Test mang lại tín hiệu phản bác quan trọng: người dùng không hoàn toàn bị động mà đã sử dụng tính năng lọc @mention và ghim tin nhắn để xử lý được 60–70% công việc quan trọng. Điều này giúp nhóm xác định lại phạm vi can thiệp của AI: không thay thế toàn bộ quy trình mà tập trung giải quyết 30–40% công việc còn lại — những yêu cầu phân công bằng ngôn ngữ tự nhiên trong các chuỗi thảo luận chưa được gắn thẻ hoặc ghim.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Thách thức lớn nhất là phân tách rạch ròi giữa vấn đề và giải pháp công nghệ, đồng thời định lượng hóa các tiêu chí thành công. Khi xây dựng Problem Statement v0, nhóm dễ rơi vào thói quen đưa giải pháp AI vào phần mô tả quy trình. Việc lượng hóa Success Metric đòi hỏi phải xác định rõ baseline (60 phút/ngày), mục tiêu (dưới 15 phút/ngày, tỉ lệ bỏ sót 0%) và phương thức đo lường cụ thể qua nhật ký pilot 2 tuần thay vì các nhận định định tính.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu thực hiện lại, tôi sẽ triển khai phỏng vấn The Mom Test ngay từ CP2 để sớm kiểm chứng các giả định thay vì đợi đến CP4. Về mặt phản biện, tôi sẽ đề xuất nhóm chỉ tập trung thử nghiệm trên nền tảng Discord trong giai đoạn pilot 2 tuần thay vì dàn trải cả Telegram. Discord có cấu trúc phân quyền bot và quản lý thread rõ ràng hơn, giúp giảm thiểu rủi ro kỹ thuật và đo lường chính xác chỉ số chấp thuận task.

**6.7. Hiểu bài:**

Chuỗi logic của dự án được xây dựng qua 6 mắt xích:
1. **Problem:** Sinh viên mất 35–45 phút mỗi sáng đọc lướt tin nhắn rác trên các kênh chat nhóm và đối mặt nguy cơ trôi deadline đồ án.
2. **Quy trình:** Hệ thống tự động quét tin ngầm qua API lúc 8:00 AM, trích xuất Action Items thành Morning Digest có link gốc lúc 8:01 AM, người dùng chỉ mất 10–12 phút đọc và duyệt lưu task lúc 8:15 AM.
3. **Metric:** Đo lường định lượng bằng việc giảm thời gian xuống 12–15 phút, tỉ lệ bỏ sót deadline đạt 0% và tỉ lệ chấp thuận task $\ge 85\%$ qua 2 tuần pilot.
4. **Boundary:** Ranh giới an toàn: AI không tự gửi tin nhắn, không tự tạo task khi chưa được duyệt, không đọc tin nhắn riêng tư và bắt buộc đính kèm link tin nhắn gốc.
5. **Mức can thiệp AI:** Chọn **Workflow with AI** do ngôn ngữ tự nhiên có độ mơ hồ cao nhưng quy trình xử lý tuần tự theo lịch cố định; mức Rule không đáp ứng được ngữ cảnh và mức Agent tự trị tiềm ẩn nhiều rủi ro.
6. **Quyết định:** Quyết định **GO (Small Pilot)** thử nghiệm 2 tuần trên 1 server Discord (4–6 người) với ngưỡng dừng định lượng: dừng dự án nếu tỉ lệ bỏ sót deadline $> 5\%$ hoặc thời gian xử lý vẫn $> 20$ phút.

---

## 7. Tài liệu tham khảo

1. **Slack Technologies (2024).** *Guide to AI features in Slack — Search and conversation summaries.* Truy cập tại: [https://slack.com/help/articles/25076892548883-Guide-to-AI-features-in-Slack](https://slack.com/help/articles/25076892548883-Guide-to-AI-features-in-Slack) (Tài liệu về tính năng tự động tóm tắt kênh chat và thread thảo luận của Slack).
2. **Discord Blog (2023).** *AI on Discord: Your Place for AI with Friends.* Truy cập tại: [https://discord.com/blog/ai-on-discord-your-place-for-ai-with-friends](https://discord.com/blog/ai-on-discord-your-place-for-ai-with-friends) (Bài viết chính thức của Discord về tính năng Conversation Summaries tự động nhóm tin nhắn thành các chủ đề có thể đọc lướt nhanh).
3. **Open-source Project (2024).** *Telegram Group Chat Summarizer Bot.* Repository: [https://github.com/moalimir/Telegram-Group-Chat-Summarizer-Bot](https://github.com/moalimir/Telegram-Group-Chat-Summarizer-Bot) (Dự án mã nguồn mở ứng dụng LLM tóm tắt tin nhắn nhóm Telegram).
4. **Google PAIR (People + AI Research).** *People + AI Guidebook — Designing human-centered AI products.* Truy cập tại: [https://pair.withgoogle.com/guidebook/](https://pair.withgoogle.com/guidebook/) (Nguyên tắc thiết kế hệ thống AI hỗ trợ con người, xử lý lỗi False Positive / False Negative và thiết kế Human-in-the-Loop).
5. **Rob Fitzpatrick (2013).** *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you.* (Phương pháp phỏng vấn kiểm chứng nhu cầu thực tế dựa trên hành vi quá khứ).
