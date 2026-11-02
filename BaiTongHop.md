phần a
- dùng chung profile có thể gây xung đột cookies và phiên đăng nhập github
- profile 1 personal: dùng cá nhân
- profile 2 company_work: dùng tài khoản công ty
- profile 3 sandbox_test: dùng thử nghiệm và kiểm thử website
- bookmark 1: github, mạng xã hội
- bookmark 2: trang công ty, công cụ quản lý công việc
- bookmark 3: website test, api json
- cho đồng nghiệp dùng guest profile để tránh lộ dữ liệu cá nhân
phần b 
- chọn nhóm dev suite
- cài json viewer để đọc dữ liệu json dễ hơn
- hai nhóm productivity suite và security suite không tập trung vào việc định dạng json
- chọn site access là on click để chỉ cấp quyền khi cần
phần c
- dns lookup: tìm địa chỉ ip
- handshake: thiết lập kết nối an toàn
- http request/response: gửi yêu cầu và nhận phản hồi
- rendering: dựng html, css thành giao diện
- 404 not found: không tìm thấy tài nguyên, kiểm tra url và endpoint
- 500 internal server error: lỗi phía máy chủ, kiểm tra log và backend
- chọn tab network để xem mã trạng thái http vì tab này hiển thị request và response
phần d 
- giao diện css cũ do cache, mở devtools và chọn network rồi bật disable cache, sau đó tải lại trang
- cookie không có httponly có thể bị javascript đọc nếu website bị tấn công xss
- vào application, chọn cookies và xóa cookie session_id để đăng xuất mà không xóa cache
phần e 
- mở f12, chọn elements, dùng inspect để chọn nút đăng nhập rồi chỉnh thuộc tính color hoặc background-color trong styles
- quy trình debug
  - bước 1 xác định request lỗi
  - bước 2 kiểm tra url và mã trạng thái
  - bước 3 xem response và console để tìm nguyên nhân
  - bước 4 sửa hoặc báo dev và kiểm tra lại
- trên network chọn bộ lọc fetch/xhr và bật disable cache để chỉ xem api và lấy dữ liệu mới nhất
