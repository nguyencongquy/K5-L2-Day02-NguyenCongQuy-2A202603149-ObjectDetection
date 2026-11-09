# Mini guideline — bài làm cá nhân  
  
> Điền nội dung này trước khi bắt đầu gán nhãn. Giữ lại các quyết định sau khi self-QC.  
  

****Định nghĩa lớp****  

| Lớp | Định nghĩa của bạn | Ví dụ/điểm phân biệt |
| ----- | ----------------------------------------------- | ---------------------------------- |
| car | 0 — Xe con, SUV, taxi và xe bán tải. | Sedan, SUV, taxi hoặc bán tải. |
| truck | 1 — Xe tải chở hàng hoặc xe đầu kéo. | Ví dụ: xe tải thùng hoặc đầu kéo. |
| bus | 2 — Xe buýt hoặc minibus chở khách. | Minibus chở khách thuộc bus. |
| van | 3 — Xe van hoặc minivan chở hàng hay chở người. | Ví dụ: van giao hàng hoặc minivan. |
  
  
## Quy tắc chung  
  
- Box bám sát vật thể nghĩa là: Mỗi xe một box riêng, ôm sát phần xe nhìn thấy và tránh lấn sang nền hoặc xe bên cạnh.  
- Vật thể bị che khuất: Nếu nhận diện được lớp, vẽ box quanh phần xe nhìn thấy.  
- Vật thể bị cắt bởi rìa ảnh: Vẽ sát phần xe trong ảnh và cho cạnh box chạm đúng mép cắt.  
- Vật thể rất nhỏ/mơ hồ: Nếu chưa xác định được lớp, ghi tên ảnh và tình huống để hỏi giảng viên.  
  
## Ghi lại quyết định cho ít nhất ba ca mơ hồ  

| Ảnh | Tình huống | Quyết định cuối | Lý do theo schema |
| ------------- | ---------------------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------- |
| drive_001.jpg | Xe trắng ở làn bên phải bị cột che một phần. | Đề xuất gán car (0), vẽ sát phần thấy được. | Dáng xe con vẫn nhận ra. Box theo biên phần nhìn thấy. |
| drive_006.jpg | Xe xanh nhạt sát vỉa hè bên phải dễ nhầm với xe con. | Đề xuất gán van (3). | Thân dạng hộp, mui cao và đầu ngắn gợi kiểu minivan. |
| drive_029.jpg | Xe buýt ở góc dưới phải bị cắt bởi mép ảnh. | Đề xuất gán bus (2), box chạm mép cắt. | Thân dài và dãy cửa kính lớn vẫn nhận ra. Chỉ bao phần trong ảnh. |
  
