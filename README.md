# 2023_Spring_FER_SE1634
Source code của lớp SE1634

----- Cài đặt Web server (Lite-Server) và thử nghiệm ----
- Cài đặt NodeJS từ https://nodejs.org
- Kiểm tra phiên bản của:
	+ NodeJS: > node -v
	+ Node Packages Manager: > npm -v
1. Tạo mới thư mục chứa Project
2. Khởi tạo dự án trên Git local
	> git init
3. Khởi tạo dự án sử dụng NodeJS
	> npm init
   Khai báo thông tin cấu hình phù hợp với dự án
4. Kết nối đồng bộ với Git Hub
5. Cài đặt web server: Lite server
	> npm install lite-server --save-dev
6. Cấu hình command khởi động web server trong package.json
	"scripts": {
    		"start": "npm run lite",
    		"test": "echo \"Error: no test specified\" && exit 1",
    		"lite": "lite-server"
  	}
7. Thêm index.html vào project
8. Chạy web server để xem kết quả
	> npm start

---- CÀI ĐẶT, TÍCH HỢP THƯ VIỆN BOOTSTRAP V4 VÀO NODEJS ----
1. Cài đặt Bootstrap vào NodeJS:
	> npm install bootstrap@4.0.0 --save
2. Cài đặt JQuery, Poper.js
	> npm install jquery@3.3.1 popper.js@1.12.9 --save
3. Tạo các style và script dạng custom
4. Liên kết sử dụng thư viện Bootstrap và Jquery và Custom
5. Chạy thử nghiệm
