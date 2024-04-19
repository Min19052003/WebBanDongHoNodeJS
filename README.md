# Dự án chạy tốt nhất ở môi trường node v21.7.1
# Setup dự án:
B1: clone dự án từ github về
B2: Mở dự án trên Visual studio code.
B3: Bật terminal của visual studio code, trỏ vào thư mục gốc của dự án
B4: chạy lệnh npm i để cài đặt các thư viện cần thiết ==> sẽ tự sinh ra folder node_modules
B5: vào file .env thay các biến môi trường phù hợp, thay giá trị MONGODB_URI là url liên kết
	đến csdl của bạn, dùng mongdb cloud Atlats hoặc mongodb local, đuôi của url là tên csdl;
	thay PORT thích hợp.
B6: chạy lệnh npm start để khởi động dự án ==> dự án sẽ chạy lên, tạo ra các bảng tương ứng
	vào csdl của bạn sau khi đã thêm giá trị url vào biến MONGODB_URI ở .env.
B7: mở trình duyệt, truy cập url: http://localhost:<giá trị port trong file .env> (ví dụ: http://localhost:8888/)
