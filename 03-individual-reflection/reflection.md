## 03 - Individual Reflection

### Đóng góp của tôi trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra 9 problem theo nhiều lăng kính (Lặp lại, Tốn thời gian, AI có thể tốt hơn, Pain từ người khác) | Nhóm có nguồn pain rộng, không dồn vào "làm chatbot" hay "xây agent" trước |
| Tập trung top 3 | Lọc ra những problem có actor rõ, workflow rõ và metric đo được: Tìm deadline/lịch học, Format báo cáo Word, Multi-platform submission | Nhóm có 3 candidate hiện thực được và dễ so sánh |
| Converge nhóm | Đề xuất cluster: Cam kết & theo dõi, Tổng hợp/tóm tắt, Tìm thông tin rải rác, Chuẩn hóa tài liệu | Nhóm hiểu nhanh pattern chung, loại trừ scope sai và chọn được focus phù hợp |
| Shortlist & score | Gợi ý đánh giá 4 candidate theo 8 tiêu chí (actor rõ, workflow rõ, pain có evidence, impact đo được, làm trong lab, so sánh R/W/A được, nhóm hiểu domain) | Nhóm chọn được bài "Chỉnh format Word" vì data access đơn giản, workflow rõ nhất và metric đo objective |
| Workflow | Vẽ current/future workflow (80 phút → 21 phút), xác định bottleneck bước 2 (đối chiếu draft ↔ chuẩn) và human boundary bước 4 (sinh viên sửa theo checklist) | Giúp nhóm quyết định tập trung vào workflow chứ không phải agent |
| Research | Tìm và so sánh 7 giải pháp: Word Template `.dotx`, Macro VBA, python-docx, Grammarly/LanguageTool, Docxtools add-in, Claude/GPT-4o, SharePoint/Drive | Nhóm dừng ở stack: template chuẩn + AI pre-check theo rubric + sinh viên sửa, không chọn agent toàn phần |

---

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan | Gợi ý thêm pain/candidate theo role và product pattern | Giúp mở rộng lăng kính, nhớ thêm các lăng kính như "Lặp lại", "Pain từ người khác", "AI có thể tốt hơn" | Nhiều ý quá rộng, thiếu dấu hiệu thật và actor cụ thể | Lọc lại theo workflow rõ, evidence thật (mất 10-15 phút, copy sửa lại mỗi lần) và actor cụ thể |
| Converge | Chuyển mô tả các problem thành cluster rõ ràng theo pattern chung | Giúp nhóm nhanh thấy pattern và loại trừ scope sai | Đôi khi gộp nhiều case khác nhau vào một cluster, làm mờ ranh giới | Tách rõ từng cluster (ví dụ: "Tổng hợp/tóm tắt" vs "Tìm thông tin rải rác"), giữ focus vào pattern |
| Workflow | Phác thảo current/future workflow và đánh dấu bottleneck, human boundary | Rút gọn bước, thấy được chỗ AI nên can thiệp (bước đối chiếu rubric) và chỗ người phải giữ (bước sửa và nộp) | Một số bước bị gộp chung, chưa tách rõ effort từng bước | Tách rõ step và thời gian từng bước (ví dụ: đọc rubric 10', đối chiếu 35', sửa heading 15') để thấy đúng bottleneck |
| Research | Tìm các tool và case tương tự giải quyết format tài liệu | Tìm nhanh 7 giải pháp từ Word Template, Macro VBA, python-docx đến AI assistant, so sánh điểm mạnh/khoảng trống | Có đề xuất quá tổng quát, không phù hợp scope lab (ví dụ: Grammarly chỉ check grammar, không check format) | Chỉ giữ insight thực tế, tập trung vào pattern giải pháp (rule → workflow → agent) và loại rõ những tool không giải quyết đúng bottleneck |
| Decision | Phân tích rule/workflow/agent cho bài toán format Word | Giúp nhóm so sánh nhanh 3 mức và đi đến quyết định chọn workflow | AI có xu hướng đề xuất agent khi thấy từ "tự động hóa" | Chọn workflow vì phù hợp scope, AI chỉ lo phần dò lỗi theo rubric, sinh viên vẫn sửa và nộp — risk kiểm soát được |

---

## Những gì mình học được

- Problem tốt không phải là "AI nhất" mà là problem có actor rõ, workflow tuyến tính, input/output cụ thể và metric đo được — "chỉnh format Word" thắng vì đáp ứng đủ tiêu chí đó, không phải vì "nghe hay".
- Làm problem scan rộng trước (9 problem theo nhiều lăng kính) rồi mới converge giúp tránh bị dồn scope vào một đề tài quá rộng hoặc quá công nghệ ngay từ đầu.
- Workflow map giúp thấy ngay chỗ nào dùng rule đủ (template chuẩn), chỗ nào AI mới có giá trị thật (dò quy tắc ngầm), và chỗ nào người phải giữ (confirm và sửa cuối).
- Agent không phải đích đến mặc định; trong bài này, workflow rõ + AI pre-check + human boundary là đủ và an toàn hơn agent tự sửa/tự nộp.
- Quick validation (3 interview + mini poll 8 người) thay đổi scope bài: pain thật không phải "áp template" mà là "đối chiếu draft với quy tắc ngầm" — đây là thứ template tĩnh không giải quyết được và là chỗ AI có giá trị thật.
- Dùng AI để gợi ý và mở rộng lăng kính, không phải để quyết định. Luôn cần lọc output, giữ phần có evidence và phù hợp scope lab.

---

## Nếu làm lại

```text
Tôi sẽ validate data access sớm hơn (trước khi đưa candidate vào shortlist) và hỏi thêm
sinh viên từ nhiều khoa khác để hiểu rõ mức độ đồng nhất của bộ chuẩn format trước khi
chốt metric (80 phút → 25 phút). Ngoài ra, tôi sẽ thử pilot nhỏ với 1–2 bài thật ngay
trong buổi lab thay vì chỉ vẽ future workflow trên lý thuyết.
```