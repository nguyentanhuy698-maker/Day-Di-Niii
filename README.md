# Dậy Sớm Đi Níiii

Game nhỏ giúp mình sống có kỷ luật hơn: mỗi ngày một con boss "thói xấu", mỗi việc làm đúng giờ là một đòn đánh.

## Tính năng

- **Chiến đấu**: danh sách việc trong ngày theo thời khóa biểu (dậy 6:30, gym, học, ăn uống, tắt màn hình 22:30, ngủ 23:00). Làm xong việc nào là boss mất máu việc đó. Làm được từ 80% việc là hạ boss, mở rương nhận trang bị.
- **Bình nước phép**: mỗi bình 250ml, có sẵn giờ uống. Bình nào tới giờ mà chưa uống sẽ phát sáng nhắc.
- **Lên cấp**: tích XP, đổi danh hiệu, giữ chuỗi ngày hạ boss, xem nhật ký 30 ngày.
- **Chi tiêu**: đặt ngân sách tháng, ghi từng khoản chi, xem biểu đồ chi theo ngày và theo loại. Ngày tiêu trong mức được thưởng thêm XP.
- **Thực đơn**: mục tiêu tăng cơ giảm mỡ (2.700–2.800 kcal, 140–160g đạm), thực đơn 5 bữa tự đổi theo ngày gym hay ngày nghỉ, kèm vòng quay chọn món khi không biết ăn gì.

## Lịch tuần

| Thứ | Sáng | Chiều | Tối |
|---|---|---|---|
| 2 | Học bài | Tự do / đi làm ca | Tiếng Anh |
| 3 | Học bài | Đi làm ca | Rảnh |
| 4 | Học bài | Gym 16:30 | Tiếng Anh |
| 5 | Gym 7:30 | Học trường | Rảnh |
| 6 | Học bài | Tự tập gym ~16:00 | Tiếng Anh |
| 7 | Gym 7:30 | Học trường | Rảnh |
| CN | Nghỉ ngơi | Chuẩn bị tuần mới | Rảnh |

## Chạy thử

Chỉ cần mở `index.html` bằng trình duyệt, không cần cài gì.

- Khi mở dưới dạng artifact trên claude.ai, dữ liệu được đồng bộ giữa các thiết bị.
- Khi mở file trực tiếp, dữ liệu được lưu trong trình duyệt đang dùng (localStorage).

## Cấu trúc

```
index.html                    Toàn bộ game (HTML, CSS, JS trong một file)
docs/Thoi_khoa_bieu_Huy.xlsx  Thời khóa biểu ăn, ngủ, tập, uống nước dạng bảng tính
```
