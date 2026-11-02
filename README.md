# Tanori releases

Bộ cài Windows và các bộ chạy giọng đọc tùy chọn của Tanori, do Tanpopo AI phát triển.

- Bản Beta dùng thư viện và cấu hình riêng, không nhập dữ liệu từ bản Tanori đang sử dụng.
- Người dùng tự cấu hình và thanh toán các dịch vụ API của mình.
- Model giọng đọc không nằm trong bộ cài; chọn thư mục lưu trước khi tải trong **Giọng đọc**.
- Bộ chạy VieNeu CPU và NVIDIA CUDA tải riêng. App kiểm tra RAM, dung lượng ổ đĩa và GPU trước khi tải, sau đó kiểm tra bộ chạy thực tế.
- Các tệp `.zip.001`, `.zip.002`… là phần của một gói bộ chạy. App tự tải, kiểm SHA256 và giải nén; không cần tự ghép.

## Gói bộ chạy

Các gói sử dụng Python portable và thư viện riêng; không yêu cầu cài Python, Anaconda hoặc CUDA Toolkit. Gói GPU vẫn cần driver NVIDIA phù hợp.

Manifest công bố dung lượng tải, dung lượng giải nén và checksum của từng phần. Các thư viện và giấy phép đi kèm được giữ trong gói. Model được tải riêng từ tác giả VieNeu.

Không lưu API key, dữ liệu sách hay cấu hình cá nhân trong repository này.
