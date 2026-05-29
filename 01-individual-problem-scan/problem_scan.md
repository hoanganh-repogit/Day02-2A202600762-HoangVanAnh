
## ***01 - Individual Problem Scan***

### ***Problem Scan***

---

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Sinh viên phải nhập lại thông tin cá nhân cho nhiều form đăng ký khác nhau | Sinh viên | Điền lặp lại cùng dữ liệu nhiều lần |
| 2 | Tốn thời gian | Tìm lịch học hoặc deadline môn học trong nhiều group chat khác nhau | Sinh viên | Mất 10-15 phút để tìm |
| 3 | AI có thể tốt hơn | Google Drive không tự phân loại file học tập theo môn | Sinh viên | Folder lộn xộn, khó tìm file |
| 4 | Pain từ người khác | Giảng viên đổi deadline nhưng thông báo rải rác | Sinh viên | Nhiều người nộp trễ do không thấy thông báo |
| 5 | Lặp lại | Viết email xin nghỉ học hoặc vắng với nội dung gần giống nhau | Sinh viên, Intern | Copy và sửa lại mỗi lần |
| 6 | Tốn thời gian | Chỉnh format báo cáo Word theo chuẩn trường | Sinh viên | Mất hàng giờ chỉ để căn lề/mục lục |
| 7 | AI có thể tốt hơn | LMS/e-learning không gợi ý môn cần ưu tiên học | Sinh viên | Dễ bỏ quên môn yếu |
| 8 | Pain từ người khác | Thành viên trong nhóm không update tiến độ thường xuyên | Leader nhóm | Phải nhắn hỏi liên tục |
| 9 | Tốn thời gian | Đặt lịch họp nhóm khó vì mỗi người rảnh giờ khác nhau | Sinh viên | Mất nhiều tin nhắn để chốt lịch |
---
## ***Vì sao phần scan này mạnh:***

- Có scan rộng trước khi hội tụ.
- Có nhiều lăng kính khác nhau.
- Mỗi problem có actor và dấu hiệu thật.
- Không bắt đầu bằng "làm chatbot" hoặc "xây agent".

---

## ***Top 3***

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tìm lịch học hoặc deadline trong nhiều group chat | Pain xảy ra hằng ngày, nhiều sinh viên gặp | Khó đồng bộ dữ liệu từ nhiều nền tảng |
| 2 | Chỉnh format báo cáo Word theo chuẩn trường | Tốn rất nhiều thời gian, workflow rõ ràng | Khác format giữa các khoa/trường |
| 3 | Mỗi môn học dùng platform khác nhau để nộp bài | Impact rộng, dễ quên deadline | Khó tích hợp tất cả LMS/platform |

## ***Problem Card #1 — Deadline & Group Chat Tracking***

### ***Problem 1 câu:***
Sinh viên thường mất nhiều thời gian tìm deadline và lịch học vì thông tin nằm rải rác ở nhiều group chat và platform khác nhau.

### ***Actor:***
Sinh viên đại học phải theo dõi deadline bài tập, lịch học, lịch thi từ nhiều môn khác nhau.

### ***Thời điểm / bối cảnh:***
Đầu tuần, trước deadline nộp bài hoặc trong mùa thi.

### ***Current workflow:***

```text
1. Mở Messenger/Zalo/Discord từng môn
2. Scroll tìm thông báo deadline cũ
3. Check LMS hoặc Google Classroom
4. Ghi lại deadline vào note cá nhân
5. So sánh deadline giữa các môn
6. Đặt reminder thủ công
7. Vẫn có thể bỏ sót thông báo
```
### ***Bottleneck:***
Bước tìm deadline từ nhiều group chat và platform mất nhiều thời gian, đồng thời dễ bỏ sót thông báo quan trọng.

### ***Impact:***
Một sinh viên có thể mất 20-30 phút mỗi ngày chỉ để check và tổng hợp deadline. Khi có nhiều môn học cùng lúc, nguy cơ nộp trễ hoặc quên bài tăng cao.

### ***Success metric:***
Giảm thời gian check deadline xuống dưới 5 phút/ngày và giảm số lần nộp trễ hoặc quên bài tập.

### ***Non-AI alternative:***
Sinh viên tự ghi deadline vào Google Calendar hoặc Notion, nhưng vẫn phải nhập thủ công và dễ quên update khi có thay đổi.

### ***AI hypothesis:***
AI có thể tự động đọc thông báo từ nhiều nguồn, trích xuất deadline/lịch học và gom thành một timeline hoặc reminder tập trung cho sinh viên.

## ***Quick gut:***
Workflow.

## ***Draft current workflow***

### ***CURRENT STATE — 30 phút***

```
┌─────────────────┐      ┌──────────────┐      ┌──────────┐      ┌────────────────┐
│ 1 Mở Messenger/ │      │ 2 Search     │      │ 3 Check  │      │ 4 Ghi deadline │
│   Zalo từng môn │  →   │  deadline    │  →   │   LMS    │  →   │  vào note cá   │
│      ○ 5'       │      │   ○ 10'      │      │  ○ 5'    │      │    nhân ○ 5'   │
└─────────────────┘      └──────────────┘      └──────────┘      └────────────────┘
                                                                            ↓
                         ┌──────────────┐      ┌──────────┐
                         │ 5 Đặt        │      │ 6 Vẫn có │
                         │ reminder     │  →   │ thể bỏ   │
                         │ thủ công ● 5'│      │ sót ○ ?  │
                         └──────────────┘      └──────────┘

● = Bottleneck
````

## ***Draft future workflow***

### ***FUTURE STATE — 5 phút***

```
┌──────────────┐      ┌──────────────┐      ┌────────────────┐
│ 1 AI auto-   │      │ 2 AI trích   │      │ 3 AI gom       │
│ pull từ      │  →   │ xuất         │  →   │ thành          │
│ group chat   │      │ deadline     │      │ dashboard      │
│  ○ 2'        │      │  ○ 1'        │      │ timeline ○ 1'  │
└──────────────┘      └──────────────┘      └────────────────┘
                                                      ↓
                      ┌──────────────┐      ┌──────────────┐
                      │ 4 Sinh viên  │      │ 5 Sync to    │
                      │ review       │  →   │ Google Cal   │
                      │ ○ 1' ● green │      │  ○ 1'        │
                      └──────────────┘      └──────────────┘

● = Human boundary
Fallback: AI đọc sai → Sinh viên edit thủ công
```


## ***Problem Cards #2 và #3 — tóm tắt***

| Card                      | Actor     | Bottleneck                      | Metric          | Quick gut        | Vì sao chưa chọn làm #1     |
| ------------------------- | --------- | ------------------------------- | --------------- | ---------------- | --------------------------- |
| Format Báo Cáo Word       | Sinh viên | Chỉnh format/mục lục thủ công   | 2 giờ → 20 phút | Workflow         | Khác format giữa các trường |
| Multi-platform Submission | Sinh viên | Theo dõi nhiều platform nộp bài | Miss deadline ↓ | Workflow / Agent | Khó tích hợp nhiều LMS      |



