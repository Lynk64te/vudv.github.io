* Những điều cần tải xuống trước khi tiếp tục
- Chúng em đã sử dụng MERN (MongoDB, ExpressJS, ReactJS và NodeJS) cho dự án này.
- Các bước cấu hình
Cài đặt các thư viện cần thiết (sử dụng Terminal):
$ cd Project_Movie

$ npm install

$ cd backend

$ npm install

$ cd..

$ cd frontend

$ npm install

$cd..
- Tạo dotenv file:
Tạo một .env file trong thư mục backend với nội dung sau
MONGODB_PASSWORD=Mật khẩu database

SECRET_KEY=Mật khẩu bạn muốn
- Tạo một database MongoDB và thay thế đường dẫn của database vừa tạo cho đường dẫn cũ trong file app.js
- Chạy lần lượt lệnh sau ở cả backend và frontend

$ npm start
- Lúc này một trang web sẽ được mở lên và có thể trải nghiệm
