# FinalProject



## Getting started

Đây là đồ án về trang web xem phim trực tuyến.

- [ ] Các chức năng phía người dùng: Cho phép người dùng đăng nhập nhanh bằng tài khoản Google hoặc Facebook. có chức năng quên mật khẩu gửi mã OTP về email để xác thực người dùng, và có thể thay đổi mật khẩu hoặc người dùng vẫn có thể xem phim mà không cần tài khoản (nhưng có một số hạn chế). Trang chủ hiển thị thông tin phim sắp ra mắt, phim đề cử với rating cao nhất và phim mới nhất vừa được cập nhật. Đi sâu vào trang phim, ở đây hiển thị tất cả các phim, có thể sử dụng bộ lọc như lọc theo thể loại, năm sản xuất, độ tuổi, rating ngoài ra cũng có chức năng tìm kiếm cho người dùng. Trang phim chi tiết hiển thị chi tiết thông tin của phim như: tên, diễn viên, đạo diễn, mô tả, đánh giá, năm sản xuất và độ tuổi để xem phim. Ngoài ra còn có chức năng cho người dùng đã đăng nhập như đánh giá, bình luận, thêm vào danh mục yêu thích. Hiển thị các phim có cùng thể loại.
- [ ] Các chức năng phía admin: admin có thể quản lý các thể loại của phim (xóa, sửa) hoặc quản lý thông tin của phim (thêm, xóa, sửa). Admin còn có thể quản lý được bình luận cũng như là tài khoản người dùng đễ giữa môi trường xem phim "trong lành".

## How to run this project

- [ ] Copy link git vào thư mục muốn lưu gõ lệnh
```
git clone link_project
```
- [ ] Mở command line (nếu đã download MongooseDB)
```
mongod
```
- [ ] Di chuyển và mở command line (đã cài đặt NodeJS) trong thư mục vừa clone gõ lệnh dưới để tải thư viện cần thiết về cho project hoạt động
```
npm i
```
- [ ] Tiếp tục gõ lệnh dưới để khởi động hệ thống
```
node app.js
```
- [ ] Vào [link](http://localhost:3000) và bắt đầu trả nghiệm

Lưu ý: Dữ liệu của phim đã được thêm vào database khi bắt đầu khởi động, tài khoản admin mặc định được lưu trong database là:
```
username: "admin"
password: "123456"
```
