# Chiến lược gia sư

## Toán/lý/hóa. Tuy nhiên có vẻ là sẽ khó do bài dạy quá sức phức tạp

- Thu học phí trước. Để phụ huynh nói chuyện với gia sư trên google meet, ok rồi giao đi dạy
- Xây dựng 1 cái danh sách dài về kiến thức giáo trình từ lớp 1 tới lớp 12 của môn học.
- Tham khao giáo trình dạy học trên trường của BDT Đào tạo
- Update qua database thành các nội dung phù hợp

## Cờ Vua

## Phân chia lớp

- Kiến thức cần nắm: Phân chia theo Level 1-...
- Đánh giá mức độ tiếp thu của học sinh theo 3 level: Yếu - Tạm - Tốt.
- Với yếu thì cần phải học lại, tốt và tạm sẽ qua level tiếp
- Học sinh đạt được tốt thường xuyên nên cho kết thúc khóa sớm và nhảy lên khóa mới

## Database schema Toán. Tham khảo Khan academy

- File bài tập, với folder kết nối Level.
- Ví dụ Level 1.1 => Folder 1.1. Với 1.1
- 1.1 Sẽ chứa: Các kiến thức cần nắm, danh sách bài tập, mức độ hoàn thành của mỗi bài tập
- Mỗi bài tập sẽ có id, id bài nên là tên File

## Database schema Cờ vua

- Level 1 => Level 6
- Giáo viên ghi báo cáo về học viên mỗi tuần lại. Báo cáo về mức độ tiếp thu
- Tiếp thu: Chậm - Ổn - Khá - Giỏi. Đánh giá theo phiên học
  - Chậm => Quay lại level trước(6b chậm liên tục).
  - Ổn => Tiếp tục học
  - Khá => Qua lớp sau đúng thời gian(12b khá liên tục - Làm đúng 80% đáp án đúng giờ hoặc 100% hơi chậm)
  - Giỏi => Qua lớp nhanh(6 giỏi liên tục - Làm đúng 95% nhanh)
