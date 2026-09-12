# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: [đã ẩn]
- Mã học viên: [đã ẩn]
- Nhóm: Top1VinAi
- Candidate problem nhóm chọn: HR mất nhiều thời gian sàng lọc CV đa định dạng và đối chiếu thủ công với Job Description; nhóm muốn xây dựng trợ lý OCR + multi-agent có kiểm soát để tạo báo cáo bằng chứng cho HR review, không tự động tuyển hoặc loại ứng viên.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi quét 10 vấn đề quanh việc học Python/AI, làm bài nhóm, debug, đọc tài liệu và nộp assignment; mỗi vấn đề có actor và thời gian/tần suất ước lượng. | Có danh sách rộng hơn mức tối thiểu và bao phủ cả 4 lăng kính. |
| Pitch Problem Card | Tôi trình bày candidate đọc CV giúp HR duyệt nhanh hơn, tập trung vào bước đọc, trích xuất thông tin và lọc CV theo tiêu chí tuyển dụng. | Nhóm có một bài toán gắn với actor rõ là HR, có bottleneck ở khâu đọc/lọc thủ công và có thể đo thời gian duyệt mỗi CV. |
| Challenge bài của bạn khác | Chưa thực hiện vì chưa có nội dung top 3 hoặc biên bản trao đổi của các bạn khác trong repo. | Chưa có kết quả để ghi; không nhận là đã challenge khi chưa có bằng chứng. |
| Gom trùng / cluster | Chưa thực hiện với nhóm. Ở mức cá nhân, tôi nhận ra debug, lỗi môi trường và khác biệt phiên bản có thể gom thành cụm giảm ma sát khi làm assignment. | Có một gợi ý cluster để dùng khi hội tụ, nhưng chưa phải cluster chính thức của nhóm. |
| Chọn candidate problem | Tôi cùng nhóm chọn bài đọc CV giúp HR duyệt nhanh hơn vì actor rõ, workflow có thể giới hạn ở screening ban đầu và impact có thể đo bằng thời gian/CV. | Candidate được thu hẹp từ “tuyển dụng bằng AI” thành hỗ trợ HR đọc và lọc CV, không tự quyết định tuyển. |
| Validation / research | Chưa có interview, survey hoặc research link được ghi trong group report; các điểm cần validate là thời gian HR đọc mỗi CV, tiêu chí lọc và hậu quả khi AI bỏ sót ứng viên. | Chưa có bằng chứng đủ để chốt metric hoặc cho AI quyền xếp hạng cuối. |
| Workflow nhóm | Tôi đề xuất workflow: nhận CV và tiêu chí tuyển dụng → AI trích xuất/tóm tắt → HR kiểm tra và quyết định đưa CV vào vòng sau. | Giúp nhóm nhìn rõ AI chỉ hỗ trợ screening, còn HR giữ human review. |
| Problem Statement | Chưa hoàn thiện Problem Statement nhóm vì cần xác nhận baseline, nguồn CV và tiêu chí đánh giá với nhóm. | Giữ statement ở mức candidate, tránh khẳng định AI sẽ chọn ứng viên tốt hơn khi chưa có dữ liệu. |
| Rule / Workflow / Agent | Tôi nghiêng về Workflow: rule kiểm tra field và keyword, AI tóm tắt/đối chiếu CV với tiêu chí, HR review; không chọn Agent tự tuyển. | Làm rõ AI chỉ hỗ trợ screening, không tự loại hoặc tự quyết định ứng viên. |
| Decision | Chưa có quyết định cuối của nhóm. Với dữ liệu hiện tại, tôi đề xuất Not Yet cho đến khi có CV mẫu, baseline thời gian và tiêu chí để kiểm tra độ chính xác. | Giữ quyết định dựa trên bằng chứng và giới hạn rủi ro tuyển sai. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Phần có dấu tay rõ nhất của tôi là việc thu hẹp candidate thành “đọc CV giúp HR duyệt nhanh hơn”. Tôi nhấn mạnh bottleneck ở screening ban đầu, đề xuất đo thời gian đọc/lọc CV và giữ HR là người kiểm tra, không giao quyết định tuyển cho AI.

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI sau khi tự scan để gợi ý thêm problem theo 4 lăng kính. | Gợi ý thêm các góc như đọc tài liệu, quản lý phiên bản và tổng hợp tiến độ. | Một số ý quá rộng, giống “trợ lý AI toàn năng”, không có workflow thật. | Tôi chỉ giữ ý gắn với assignment Python/AI, actor, thời gian và tần suất quan sát được. |
| Problem Card | Dùng AI để phản biện candidate đọc CV và sắp xếp các field của card. | Giúp tôi nhận ra cần tách bước screening khỏi quyết định tuyển, đồng thời ghi rõ metric và human review. | AI có thể đề xuất chấm điểm ứng viên quá sớm hoặc bỏ qua bias trong tiêu chí tuyển dụng. | Tôi giới hạn AI ở trích xuất, tóm tắt và đối chiếu tiêu chí; HR tự kiểm tra và quyết định. |
| Workflow | Dùng AI để chuyển mô tả thành flow mũi tên cho việc nhận CV, tóm tắt, đối chiếu và HR review. | Giúp nhìn rõ AI nằm ở bước nào và thời gian được đo ở đâu. | AI có thể gộp tóm tắt, xếp hạng và quyết định thành một bước tự động quá rộng. | Tôi tách các bước và giữ HR ở cuối workflow với quyền quyết định. |
| Research | Không dùng AI để kết luận research nhóm vì chưa có nguồn hoặc link được kiểm chứng. | Chưa có kết quả thực tế để đánh giá. | Dùng claim hoặc số liệu chưa verify sẽ làm reflection thiếu trung thực. | Tôi ghi rõ phase chưa thực hiện thay vì tự điền nguồn hoặc số liệu. |
| Problem Statement | Không dùng AI để chốt Problem Statement nhóm vì candidate chưa được nhóm chọn. | Chưa có lợi ích ở phase này. | Chốt sớm sẽ biến giả định cá nhân thành quyết định của nhóm. | Tôi giữ problem ở mức candidate và ghi rõ cần validation trước. |
| Rule / Workflow / Agent | Dùng AI để so sánh nhanh ba mức cho bài đọc CV. | Giúp thấy Workflow phù hợp hơn Agent: rule xử lý field/keyword, AI hỗ trợ tóm tắt, HR review. | AI có thể đề xuất Agent tự xếp hạng hoặc tự loại CV quá sớm. | Tôi giữ checklist/keyword làm đối chứng và không cho AI quyết định tuyển dụng. |
| Decision | Không dùng AI để quyết định thay nhóm. | Chưa có decision nhóm để đánh giá. | Chốt Go từ ước lượng cá nhân sẽ bỏ qua chất lượng dữ liệu và hậu quả khi AI sai. | Tôi đề xuất Not Yet ở cấp cá nhân và nêu rõ validation cần làm trước. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

**Nguyên tắc sử dụng AI:** AI chỉ là công cụ hỗ trợ. Tôi tự quan sát problem, tự chọn candidate, tự kiểm tra thông tin, tự viết reflection và tự chịu trách nhiệm về các kết luận trong bài.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text

Khi nghe top 3 problems của các bạn khác, tôi học được rằng problem tốt không phải problem nghe “AI” nhất mà là problem có actor, workflow và dấu hiệu đo được. Với candidate đọc CV, actor HR và bottleneck screening ban đầu rõ hơn so với một ý tưởng rộng như “AI tuyển dụng”. Nhóm có nguy cơ solution-first nếu nghĩ ngay đến việc AI tự chấm điểm hoặc tự loại CV. Tôi đã thay đổi cách nhìn theo hướng chỉ dùng AI để trích xuất, tóm tắt và đối chiếu tiêu chí, còn HR vẫn kiểm tra và quyết định. Tôi chưa thể nói mình đã đổi ý sau challenge của thành viên khác vì group report chưa có biên bản trao đổi cụ thể. Đóng góp thật sự của tôi là giúp thu hẹp candidate, đặt câu hỏi về baseline thời gian đọc CV và nhấn mạnh boundary không giao quyết định tuyển cho AI. Tôi chưa có đủ bằng chứng để nhận phần validation, research hoặc decision cuối của nhóm. Điều khó nhất là chọn metric không chỉ đo tốc độ mà còn phải theo dõi việc bỏ sót ứng viên phù hợp và bias. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn bằng câu hỏi tiêu chí nào được dùng để kiểm tra chất lượng tóm tắt và ai chịu trách nhiệm khi AI đánh giá sai. Tôi cũng sẽ yêu cầu thử trên một tập CV mẫu đã ẩn thông tin nhạy cảm trước khi quyết định Go.



```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [12] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [12] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [5] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [15] [15đ] Nhóm có workflow trước/sau
- [20] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [15] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [10] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [10] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [6] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

