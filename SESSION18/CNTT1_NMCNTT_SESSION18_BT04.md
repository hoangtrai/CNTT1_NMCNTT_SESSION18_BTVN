


# Phần 1. Phân tích : 
|tiêu chí|Incognito Mode|Dedicated Profile |
|-|-|-|
|lưu trữ |lưu trên RAM tự động xóa sạch toàn bộ cookie, cache, sau khi đóng cửa sổ trình duyệt.|lưu trên ổ cứng |
|tác dụng |mọi phiên đăng nhập sẽ mất hết khi tắt trình duyệt |Lưu trữ tài khoản, cookie, mật khẩu|

# Phần 2. Triển khai :
 - quy trình tạo và đồng bộ hóa Cloud Sync để bảo vệ Bookmark khi đổi máy tính : 
   + Mở trình duyệt, click vào biểu tượng Profile
   + Chọn **Add**
   + Đặt tên profile 
   + Mỗi profile sẽ mở ra một cửa sổ độc lập với thanh tác vụ riêng biệt
  

# Phần 3. Kiểm thử : 
- Click vào biểu tượng Profile trên trình duyệt và chọn **Guest**
- Nguyên lý bảo mật: 
   + tạo ra một không gian duyệt web tạm thời
   + Khi người dùng đóng cửa sổ Guest, toàn bộ lịch sử duyệt web, cookie, sẽ tự động hủy 
