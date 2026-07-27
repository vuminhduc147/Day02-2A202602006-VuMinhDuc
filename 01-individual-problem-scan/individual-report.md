Dưới đây là toàn bộ nội dung đã được chuyển sang **Markdown chuẩn**, giữ nguyên cấu trúc, nội dung và các bảng để bạn có thể copy trực tiếp vào file `README.md`, `report.md` hoặc GitHub.

````markdown
# 01 — Individual Problem Scan

## Bối cảnh cá nhân

Tôi là sinh viên mới tốt nghiệp ngành Artificial Intelligence (AI), đang trong quá trình tìm kiếm cơ hội việc làm Fresher/Junior hoặc Internship trong lĩnh vực AI Engineer và Data Engineer.

Trong quá trình học tập và chuẩn bị đi làm, tôi thường xuyên:

- Học các công nghệ mới như Python, SQL, Machine Learning, Deep Learning và Data Engineering.
- Làm project cá nhân và project nhóm để xây dựng portfolio.
- Setup môi trường Python và cài đặt dependencies.
- Xử lý lỗi liên quan đến package, version, environment và API.
- Tìm kiếm tài liệu học tập từ Documentation, GitHub, YouTube và các nguồn trực tuyến.
- Đọc Job Description (JD) để chuẩn bị ứng tuyển.
- Đối chiếu yêu cầu tuyển dụng với kỹ năng hiện tại.
- Theo dõi và cải thiện skill gap.
- Làm việc nhóm và hỗ trợ các thành viên mới trong project.

Từ những trải nghiệm trên, tôi scan các problem theo 4 lăng kính:

- Lặp lại
- Tốn thời gian
- AI có thể tốt hơn
- Pain từ người khác

---

# Scan rộng

Tôi scan 10 problems để có góc nhìn rộng trước khi hội tụ vào Top 3.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại + Tốn thời gian | Mỗi khi bắt đầu project mới phải setup Python environment, cài package và cấu hình biến môi trường | Sinh viên mới tốt nghiệp, Fresher/Junior Developer | Các bước setup lặp lại ở nhiều project; thường mất thời gian trước khi có thể chạy code |
| 2 | Tốn thời gian + AI có thể tốt hơn | Khi gặp lỗi Python package hoặc dependency phải tự đọc error log và tìm cách xử lý | Sinh viên AI, Fresher/Junior AI Engineer | Có thể mất 15-60 phút cho một lỗi; thường phải tìm Google, GitHub hoặc hỏi AI |
| 3 | Tốn thời gian | Khi học công nghệ mới phải tìm kiếm và so sánh nhiều nguồn tài liệu | Sinh viên mới tốt nghiệp, người mới học công nghệ | Có thể mất nhiều thời gian tìm YouTube, GitHub, Documentation trước khi chọn được nguồn học |
| 4 | AI có thể tốt hơn | Khó xác định skill gap giữa năng lực hiện tại và yêu cầu của một Job Description | Sinh viên mới tốt nghiệp đang tìm việc | Mỗi JD có nhiều keyword khác nhau; khó biết kỹ năng nào thực sự thiếu và cần ưu tiên |
| 5 | Tốn thời gian + Lặp lại | Phải đọc và phân tích nhiều Job Description để tìm điểm chung về yêu cầu tuyển dụng | Sinh viên mới tốt nghiệp | Khi tìm việc phải đọc nhiều JD và tự ghi chú các skill như Python, SQL, Docker, Spark, ML |
| 6 | Pain từ người khác + Lặp lại | Thành viên mới trong project thường hỏi lại cách clone, setup và chạy project | Thành viên mới, người phụ trách project | Các câu hỏi như "cài package nào?", "chạy project thế nào?", "API key ở đâu?" có thể lặp lại |
| 7 | Pain từ người khác | Thành viên gặp lỗi nhưng không cung cấp đủ thông tin khiến người hỗ trợ phải hỏi lại | Thành viên project, người hỗ trợ | Người hỗ trợ thường phải hỏi lại Python version, error log, OS hoặc package version |
| 8 | Lặp lại + Tốn thời gian | Khi làm project nhóm phải tổng hợp tiến độ từ nhiều thành viên | Team Leader, Project Owner, thành viên nhóm | Thông tin tiến độ nằm rải rác trong Messenger, Discord hoặc nhóm chat |
| 9 | Tốn thời gian + AI có thể tốt hơn | Khó tìm lại câu trả lời hoặc quyết định cũ trong lịch sử chat của project | Thành viên project | Khi cần tìm thông tin cũ phải scroll hoặc search nhiều keyword khác nhau |
| 10 | Lặp lại + Tốn thời gian | Phải cập nhật README hoặc tài liệu setup project thủ công khi môi trường thay đổi | Developer, thành viên project | README có thể nhanh chóng lỗi thời khi package, command hoặc cấu hình project thay đổi |

---

# Vì sao phần scan này mạnh

- Có scan rộng 10 problems, vượt mức tối thiểu 5 problems.
- Có đủ 4 lăng kính: Lặp lại, Tốn thời gian, AI có thể tốt hơn và Pain từ người khác.
- Các problem xuất phát từ trải nghiệm thực tế của một sinh viên mới tốt nghiệp ngành AI.
- Mỗi problem đều có actor cụ thể.
- Mỗi problem đều có dấu hiệu thực tế hoặc giả định có thể kiểm chứng.
- Các problem không bắt đầu bằng solution như "xây chatbot" hoặc "xây AI Agent".
- Một số problem có thể được giải quyết bằng Rule hoặc Workflow mà chưa nhất thiết cần AI.
- Một số problem có khả năng sử dụng AI vì cần đọc hiểu context, phân tích error log, tổng hợp thông tin hoặc tìm kiếm ngữ nghĩa.

---

# Top 3 Problems

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Xử lý lỗi Environment / Dependency | Pain xảy ra trực tiếp khi làm project, workflow rõ, có thể đo thời gian debug và số lần thử | Chưa chắc AI có thể giải quyết tốt hơn Documentation hoặc công cụ debug hiện có |
| 2 | Phân tích Skill Gap giữa JD và năng lực hiện tại | Pain rõ với sinh viên mới tốt nghiệp, xảy ra thường xuyên khi tìm việc, AI có khả năng hỗ trợ phân tích ngôn ngữ | Khó đánh giá chính xác mức độ thành thạo thực tế của người dùng |
| 3 | Onboarding thành viên mới vào Project | Có pain từ người khác, câu hỏi lặp lại, ảnh hưởng cả thành viên mới và người hỗ trợ | Chưa chắc cần AI; README, checklist hoặc script setup có thể giải quyết phần lớn vấn đề |

---

# Problem Card #1 — Xử lý lỗi Environment / Dependency

## Problem 1 câu

Khi làm project AI/Data Engineering, sinh viên mới tốt nghiệp thường mất nhiều thời gian xử lý các lỗi Python package, dependency, version và environment trước khi có thể tiếp tục công việc chính.

## Actor

Sinh viên mới tốt nghiệp hoặc Fresher/Junior AI Engineer và Data Engineer đang làm project cá nhân hoặc project nhóm.

## Thời điểm / bối cảnh

Xảy ra khi bắt đầu project mới, cài đặt package mới hoặc khi chạy project trên một môi trường khác.

## Current workflow

```text
1. Cài đặt package / chạy project
2. Gặp error
3. Đọc error log
4. Kiểm tra Python version
5. Kiểm tra package version
6. Tìm kiếm Google / GitHub
7. Hỏi AI hoặc cộng đồng
8. Thử giải pháp
9. Chạy lại project
10. Nếu vẫn lỗi → tiếp tục debug
````

### Bottleneck

**Bước 6-8 — tìm nguyên nhân và xác định giải pháp phù hợp.**

Một error có thể liên quan đến nhiều nguyên nhân như:

* Python version
* Package version
* Dependency conflict
* Operating system
* Environment variable
* Cấu hình môi trường

Người mới thường phải thử nhiều giải pháp trước khi xác định được nguyên nhân gốc.

### Impact

Một lỗi có thể mất khoảng **15-60 phút** để xử lý tùy mức độ.

Trong một project có nhiều lỗi environment hoặc dependency, tổng thời gian debug có thể ảnh hưởng đáng kể đến tiến độ project.

Ngoài thời gian, việc debug liên tục cũng làm gián đoạn quá trình học tập và phát triển tính năng chính.

### Success metric

Giảm thời gian xử lý một lỗi environment/dependency trung bình từ khoảng **30 phút xuống dưới 10 phút**.

Có thể đo thêm:

* Thời gian từ lúc gặp lỗi đến khi giải quyết.
* Số lần thử giải pháp.
* Số nguồn phải tham khảo.
* Tỷ lệ lỗi được giải quyết thành công.

### Non-AI alternative

Có thể sử dụng:

* README setup rõ ràng.
* `requirements.txt`.
* `environment.yml`.
* Docker.
* Script setup tự động.
* Lock file quản lý dependency.

Các giải pháp này có thể giảm lỗi environment nhưng không giải quyết tốt các lỗi phát sinh bất ngờ khi developer làm việc.

### AI hypothesis

AI có thể đọc error log, hiểu context của project và environment, sau đó:

1. Phân loại loại lỗi.
2. Xác định nguyên nhân có khả năng cao.
3. Gợi ý các bước kiểm tra.
4. Đề xuất solution.
5. Yêu cầu người dùng cung cấp thêm thông tin nếu chưa đủ context.

Developer vẫn kiểm tra và thực hiện giải pháp.

### Quick gut

**Workflow / AI-assisted Workflow.**

Chưa cần Agent ở giai đoạn đầu vì AI chỉ cần hỗ trợ một bước cụ thể trong quy trình debug thay vì tự động thực hiện toàn bộ quá trình.

---

## Draft current workflow

### CURRENT STATE — khoảng 30 phút/lỗi

```text
[1 Chạy code]
        ↓
[2 Gặp Error: 2']
        ↓
[3 Đọc Error Log: 3']
        ↓
[4 Kiểm tra Environment: 5']
        ↓
[5 Search Google / GitHub: 10']
        ↓
[6 Thử giải pháp: 5']
        ↓
[7 Chạy lại]
```

Nếu vẫn lỗi:

```text
Quay lại bước 3-6
```

### Bottleneck

```text
[Search + Diagnose + Try Solution]
              ↑
         BOTTLENECK
```

---

## Draft future workflow

### FUTURE STATE — khoảng 10 phút

```text
[1 Developer gặp Error]
        ↓
[2 Thu thập Error Log + Environment Info: 1']
        ↓
[3 AI phân tích lỗi + Context: 1']
        ↓
[4 AI đề xuất nguyên nhân và 3 bước kiểm tra: 1']
        ↓
[5 Developer kiểm tra: 5']
        ↓
[6 Áp dụng solution: 2']
```

### Human boundary

Developer vẫn chịu trách nhiệm:

* Kiểm tra nguyên nhân.
* Xác nhận solution.
* Thực hiện thay đổi trên environment.
* Đảm bảo solution không phá vỡ project.

### Fallback

Nếu AI không xác định được nguyên nhân:

```text
AI không đủ context
        ↓
Yêu cầu thêm Error Log / Python Version / Package Version
        ↓
Nếu vẫn không giải quyết
        ↓
Developer chuyển sang Google / GitHub / Community / Mentor
```

---

# Problem Card #2 — Phân tích Skill Gap giữa JD và năng lực hiện tại

## Problem 1 câu

Sinh viên mới tốt nghiệp mất nhiều thời gian khi đối chiếu yêu cầu trong Job Description với kỹ năng hiện tại và khó xác định kỹ năng nào cần ưu tiên cải thiện trước khi ứng tuyển.

## Actor

Sinh viên mới tốt nghiệp đang tìm việc Fresher/Junior AI Engineer hoặc Data Engineer.

## Thời điểm / bối cảnh

Khi tìm kiếm và đánh giá một vị trí tuyển dụng mới.

## Current workflow

```text
1. Tìm Job Description
2. Đọc Requirements
3. Ghi lại các kỹ năng yêu cầu
4. Đọc CV của bản thân
5. Đối chiếu Skills
6. Xác định Skill Gap
7. Tìm tài liệu học
8. Tự xác định Priority
9. Lập kế hoạch học
```

### Bottleneck

**Bước 5-8 — đối chiếu năng lực và xác định mức độ ưu tiên.**

Một JD có thể chứa nhiều keyword nhưng không phải tất cả đều có mức độ quan trọng giống nhau.

### Impact

Có thể mất khoảng **20-40 phút** để phân tích một JD.

Nếu ứng tuyển nhiều vị trí, tổng thời gian phân tích có thể tăng đáng kể.

Ngoài ra, việc xác định sai skill gap có thể khiến người học dành thời gian cho kỹ năng ít quan trọng.

### Success metric

Giảm thời gian phân tích một JD từ khoảng **30 phút xuống dưới 10 phút**.

Có thể đo thêm:

* Số skill gap được xác định.
* Thời gian xác định priority.
* Mức độ đồng thuận giữa AI và đánh giá của mentor.
* Tỷ lệ kỹ năng ưu tiên có liên quan đến yêu cầu tuyển dụng thực tế.

### Non-AI alternative

Có thể sử dụng:

* Excel/Google Sheets.
* Checklist kỹ năng.
* Template phân tích JD.
* Skill matrix cá nhân.

Các cách này giúp chuẩn hóa quá trình nhưng vẫn yêu cầu người dùng tự đọc và đối chiếu thông tin.

### AI hypothesis

AI có thể:

1. Trích xuất yêu cầu từ JD.
2. Gom nhóm skill tương đồng.
3. So sánh với CV.
4. Phát hiện skill gap.
5. Gợi ý priority.

Người dùng vẫn cần tự xác nhận mức độ thành thạo thực tế.

### Quick gut

**Workflow.**

AI có thể là một thành phần trong workflow nhưng chưa cần Agent tự động quyết định kế hoạch nghề nghiệp.

---

## Draft current workflow

### CURRENT STATE — khoảng 30 phút/JD

```text
[1 Đọc JD: 10']
        ↓
[2 Ghi Requirements: 5']
        ↓
[3 Đọc CV / Portfolio: 5']
        ↓
[4 Đối chiếu Skills: 5']
        ↓
[5 Xác định Skill Gap: 3']
        ↓
[6 Xác định Priority: 2']
```

### Bottleneck

```text
[Đối chiếu JD ↔ CV ↔ Skill hiện tại]
              ↑
          BOTTLENECK
```

---

## Draft future workflow

### FUTURE STATE — khoảng 10 phút/JD

```text
[1 Upload / Paste JD]
        ↓
[2 AI trích xuất Requirements]
        ↓
[3 AI đối chiếu với CV / Portfolio]
        ↓
[4 AI tạo Skill Gap Matrix]
        ↓
[5 AI đề xuất Priority]
        ↓
[6 User review + xác nhận]
```

### Human boundary

Người dùng vẫn phải:

* Tự đánh giá năng lực thực tế.
* Xác nhận mức độ thành thạo.
* Quyết định kỹ năng nào phù hợp với mục tiêu cá nhân.
* Không hoàn toàn phụ thuộc vào đánh giá của AI.

### Fallback

Nếu AI không đủ thông tin:

```text
AI không xác định được Skill Level
        ↓
Yêu cầu User cung cấp Project / Experience / Test Result
        ↓
AI cập nhật Skill Gap
        ↓
User xác nhận kết quả cuối
```

---

# Problem Card #3 — Onboarding thành viên mới vào Project

## Problem 1 câu

Thành viên mới tham gia project thường mất thời gian setup và phải hỏi lại các câu hỏi đã từng được hướng dẫn, khiến người có kinh nghiệm phải hỗ trợ lặp lại.

## Actor

* Thành viên mới.
* Người phụ trách project.
* Team Leader.
* Mentor hoặc Senior Developer.

## Thời điểm / bối cảnh

Khi một thành viên mới tham gia project AI/Data Engineering.

## Current workflow

```text
1. Thành viên mới nhận project
2. Clone repository
3. Đọc README
4. Setup environment
5. Cài dependencies
6. Cấu hình API key / .env
7. Chạy project
8. Gặp lỗi hoặc không hiểu bước nào đó
9. Hỏi người có kinh nghiệm
10. Nhận hướng dẫn
11. Thử lại
12. Hoàn thành setup
```

### Bottleneck

**Bước 8-10 — tìm kiếm thông tin và nhận hỗ trợ.**

Thông tin có thể nằm rải rác trong:

* README.
* GitHub Issues.
* Discord.
* Messenger.
* Google Drive.
* Các cuộc trò chuyện cũ.

### Impact

Thành viên mới mất nhiều thời gian để bắt đầu project.

Người có kinh nghiệm phải trả lời các câu hỏi lặp lại như:

* Cài package nào?
* Dùng Python version nào?
* API key lấy ở đâu?
* Chạy project bằng command nào?
* Nếu gặp lỗi này thì xử lý thế nào?

### Success metric

Giảm thời gian onboarding từ khoảng **60 phút xuống dưới 20 phút**.

Giảm số câu hỏi hỗ trợ lặp lại từ khoảng **5 câu hỏi/thành viên xuống dưới 2 câu hỏi/thành viên**.

Có thể đo thêm:

* Thời gian từ lúc tham gia project đến khi chạy thành công.
* Số câu hỏi cần người khác hỗ trợ.
* Số câu hỏi đã có câu trả lời trong documentation.

### Non-AI alternative

Có thể cải thiện:

* README.
* Setup checklist.
* FAQ.
* `requirements.txt`.
* Docker.
* Setup script.
* Documentation tập trung.

Đây có thể là phương án đơn giản và ít rủi ro hơn AI.

### AI hypothesis

AI có thể hỗ trợ tìm kiếm và trả lời câu hỏi dựa trên:

* README.
* Documentation.
* GitHub Issues.
* Project setup guide.

AI chỉ được trả lời dựa trên nguồn tài liệu được cung cấp và trích dẫn nguồn khi cần.

### Quick gut

**Workflow.**

Nếu dữ liệu project được tổ chức tốt, AI có thể được thêm vào workflow để hỗ trợ tìm kiếm và onboarding.

Chưa cần Agent vì việc tự động thao tác trên máy của thành viên mới có thể tạo rủi ro.

---

## Draft current workflow

### CURRENT STATE — khoảng 60 phút

```text
[1 Nhận Project]
        ↓
[2 Clone Repository: 5']
        ↓
[3 Đọc README: 5']
        ↓
[4 Setup Environment: 15']
        ↓
[5 Gặp lỗi / Không hiểu: 10']
        ↓
[6 Hỏi người có kinh nghiệm: 10']
        ↓
[7 Chờ phản hồi: 10']
        ↓
[8 Chạy Project thành công: 5']
```

### Bottleneck

```text
[Không tìm thấy thông tin]
        ↓
[Hỏi người khác]
        ↓
[Chờ phản hồi]
        ↑
      BOTTLENECK
```

---

## Draft future workflow

### FUTURE STATE — khoảng 18 phút

```text
[1 Nhận Project]
        ↓
[2 Mở Onboarding Guide]
        ↓
[3 AI / Search tìm hướng dẫn phù hợp]
        ↓
[4 Làm theo Setup Checklist]
        ↓
[5 AI hỗ trợ giải thích lỗi dựa trên Documentation]
        ↓
[6 Thành viên tự hoàn thành Setup]
        ↓
[7 Chỉ escalate cho Mentor nếu không giải quyết được]
```

### Human boundary

Mentor hoặc người phụ trách vẫn xử lý:

* Các lỗi chưa có trong documentation.
* Các vấn đề liên quan đến quyền truy cập.
* Các vấn đề bảo mật.
* Các thay đổi quan trọng trong project.

### Fallback

```text
AI không tìm thấy câu trả lời
        ↓
Thông báo "Không tìm thấy thông tin đáng tin cậy"
        ↓
Gửi câu hỏi cho Mentor / Project Owner
        ↓
Cập nhật câu trả lời mới vào Documentation
```

---

# So sánh Top 3 Problems

| Card                               | Actor                                    | Bottleneck                             | Metric                         | Quick gut                       | Vì sao chưa chọn làm #1                                                      |
| ---------------------------------- | ---------------------------------------- | -------------------------------------- | ------------------------------ | ------------------------------- | ---------------------------------------------------------------------------- |
| Xử lý lỗi Environment / Dependency | Sinh viên mới tốt nghiệp, Fresher/Junior | Tìm nguyên nhân và thử nhiều giải pháp | 30 phút/lỗi → dưới 10 phút/lỗi | Workflow / AI-assisted Workflow | Một số lỗi có thể cần kiến thức chuyên môn sâu; cần validate khả năng AI     |
| Skill Gap giữa JD và năng lực      | Sinh viên mới tốt nghiệp                 | Đối chiếu JD, CV và xác định priority  | 30 phút/JD → dưới 10 phút/JD   | Workflow                        | Khó đo chính xác chất lượng đánh giá Skill Gap                               |
| Onboarding thành viên mới          | Thành viên mới + Mentor                  | Tìm thông tin và chờ người hỗ trợ      | 60 phút → dưới 20 phút         | Workflow                        | README, checklist và Docker có thể giải quyết phần lớn vấn đề mà chưa cần AI |

---

# Kết luận Phase 1

Sau khi scan 10 problems, tôi hội tụ vào 3 candidate problems:

1. Xử lý lỗi Environment / Dependency.
2. Phân tích Skill Gap giữa JD và năng lực hiện tại.
3. Onboarding thành viên mới vào Project.

Trong 3 problems, tôi ưu tiên **Xử lý lỗi Environment / Dependency** làm candidate problem để tiếp tục đưa vào **Phase 3 — Group Convergence**.

```
```
