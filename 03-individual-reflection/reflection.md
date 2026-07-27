# 03 — Individual Reflection

## Đóng góp của Đức trong nhóm

| Hoạt động | Đức đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra 10 problems xuất phát từ trải nghiệm học tập và làm project AI/Data Engineering | Có nhiều candidate problem liên quan đến Environment/Dependency, Skill Gap, Onboarding và Project Workflow |
| Top 3 Problems | Chọn và phân tích 3 problems: Xử lý lỗi Environment/Dependency, Phân tích Skill Gap giữa JD và năng lực hiện tại, Onboarding thành viên mới | Nhóm có 3 candidate problems được mô tả rõ actor, context, workflow, bottleneck và impact |
| Problem Card | Viết chi tiết Problem Card cho 3 candidate problems | Làm rõ problem, current workflow, bottleneck, success metric, non-AI alternative và AI hypothesis |
| Workflow | Xây dựng Current State và Future State cho problem Environment/Dependency | Xác định bottleneck chính nằm ở quá trình Search + Diagnose + Try Solution |
| AI / Non-AI Analysis | So sánh khả năng sử dụng AI với các giải pháp như README, requirements.txt, environment.yml, Docker và setup script | Nhận ra AI không phải luôn là giải pháp tốt nhất; cần xem xét giải pháp đơn giản trước |
| Rule / Workflow / Agent | Phân tích mức độ phù hợp của Rule, Workflow và Agent đối với problem Environment/Dependency | Ưu tiên Workflow / AI-assisted Workflow vì AI hỗ trợ phân tích và đề xuất, còn Developer vẫn kiểm tra và quyết định |
| Candidate Problem | Ưu tiên Xử lý lỗi Environment / Dependency để tiếp tục đưa vào Phase 3 — Group Convergence | Có một candidate problem có workflow rõ, bottleneck cụ thể và metric có thể tiếp tục validate |

---

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan | Gợi ý thêm các problems có thể gặp khi học và làm project AI/Data Engineering | Giúp tôi mở rộng góc nhìn và nhớ thêm các vấn đề như Skill Gap, Onboarding, Documentation và Project Workflow | Một số gợi ý quá rộng hoặc bắt đầu từ solution thay vì problem thực tế | Tôi loại bỏ các ý không xuất phát từ trải nghiệm thật hoặc không có actor, workflow và dấu hiệu rõ |
| Top 3 Problems | Hỗ trợ so sánh và đánh giá các candidate problems | Giúp tôi hệ thống hóa pain, bottleneck, impact và khả năng ứng dụng AI của từng problem | AI có thể đánh giá problem dựa trên lý thuyết nhưng không thể tự xác nhận pain thực tế của người dùng | Tôi ưu tiên các problem tôi đã trực tiếp gặp và ghi rõ những điểm còn chưa chắc chắn cần validate |
| Workflow | Hỗ trợ chuyển mô tả problem thành Current State và Future State | Giúp tôi nhanh chóng hình dung luồng công việc và xác định bottleneck | AI có xu hướng tạo workflow quá lý tưởng và đơn giản hóa quá trình debug thực tế | Tôi chỉnh lại workflow để phản ánh đúng các bước Search, Diagnose và Try Solution, đồng thời bổ sung Human Boundary |
| Problem Card | Hỗ trợ cấu trúc hóa Problem Card gồm Actor, Context, Workflow, Bottleneck, Impact, Metric và AI Hypothesis | Giúp tôi không bỏ sót các thành phần quan trọng khi phân tích problem | Một số metric do AI đề xuất có vẻ cụ thể nhưng chưa có dữ liệu thực tế để chứng minh | Tôi xem các metric như "30 phút → dưới 10 phút" là hypothesis và ghi rõ cần validate baseline thực tế |
| AI Hypothesis | Hỗ trợ phân tích AI có thể tham gia ở bước nào trong quy trình debug | Giúp tôi xác định AI phù hợp với việc đọc error log, phân loại lỗi, tìm nguyên nhân và đề xuất bước kiểm tra | AI có xu hướng đề xuất tự động hóa quá nhiều hoặc đưa ra solution khi chưa đủ context | Tôi giới hạn AI ở vai trò hỗ trợ phân tích và đề xuất; Developer vẫn kiểm tra và thực hiện giải pháp |
| Rule / Workflow / Agent | Hỗ trợ suy nghĩ về mức độ phù hợp giữa Rule, Workflow và Agent | Giúp tôi hiểu rõ hơn sự khác nhau giữa các cách tiếp cận | AI có thể dễ dàng đề xuất Agent vì đây là hướng có mức độ tự động hóa cao hơn | Tôi chọn Workflow / AI-assisted Workflow vì problem có quy trình tương đối rõ và cần Human-in-the-loop |

---

## Bài học của Đức

- **Problem tốt không phải problem nghe "AI" nhất**, mà là problem có người thực sự gặp, workflow rõ, bottleneck cụ thể và metric có thể đo.
- Scan nhiều problem trước khi hội tụ giúp tôi nhận ra rằng một trải nghiệm cá nhân có thể tạo ra nhiều problem khác nhau khi nhìn từ các lăng kính khác nhau.
- **Vẽ workflow giúp xác định bottleneck chính xác hơn.** Với problem Environment/Dependency, bottleneck không đơn giản là "gặp error" mà nằm ở quá trình **Search + Diagnose + Try Solution**.
- **Non-AI alternative cần được xem xét trước khi quyết định dùng AI.** README, `requirements.txt`, `environment.yml`, Docker và setup script có thể giải quyết một phần đáng kể vấn đề.
- **AI không nhất thiết phải thay thế toàn bộ workflow.** Trong problem của tôi, AI phù hợp hơn khi đóng vai trò hỗ trợ đọc error log, phân loại lỗi và đề xuất nguyên nhân.
- **Agent không phải đích đến mặc định.** Trong case Environment/Dependency, Workflow hoặc AI-assisted Workflow hợp lý hơn vì Developer vẫn cần review và chịu trách nhiệm với thay đổi trên environment.
- Metric cần có cơ sở thực tế. Việc đặt mục tiêu **30 phút/lỗi → dưới 10 phút/lỗi** hiện mới là ước tính từ trải nghiệm cá nhân, chưa phải số liệu đã được validate.
- Tôi học được rằng AI có thể giúp tôi cấu trúc và phản biện problem nhanh hơn, nhưng **nhận định cuối cùng vẫn cần dựa trên trải nghiệm thực tế và dữ liệu từ người dùng**.

---

## Nếu làm lại

> Tôi sẽ validate problem với nhiều sinh viên AI, Fresher/Junior Developer và Data Engineer hơn trước khi chốt metric **30 phút/lỗi → dưới 10 phút/lỗi**, vì baseline hiện tại chủ yếu đến từ trải nghiệm cá nhân của tôi.

Tôi cũng sẽ thu thập thêm dữ liệu về:

- Tần suất gặp lỗi Environment/Dependency.
- Thời gian trung bình để xử lý một lỗi.
- Các nguồn thường được sử dụng để tìm solution.
- Mức độ hiệu quả của AI khi hỗ trợ debug.
- Những loại lỗi AI có thể hỗ trợ tốt và những loại lỗi cần Mentor hoặc Community.

Sau khi có dữ liệu thực tế, tôi mới quyết định liệu problem này có đủ mạnh để tiếp tục phát triển thành một AI-assisted Workflow hay cần pivot sang một problem khác.
