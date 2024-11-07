# genai-application-kepco
UET x KepcoKDN project applying learned Generative AI concepts (Oct 2024)- by Ba-Hoang-Long Nguyen (longnbh)

# Phân Tích và Tăng Cường Nội Dung Hình Ảnh từ Mạng Xã Hội Để Tăng Hiệu Suất Truyền Thông

## Mục tiêu dự án
Dự án này nhằm mục đích tối ưu hóa hình ảnh từ các bài đăng trên mạng xã hội thông qua AI tạo sinh. Hệ thống sẽ nhận diện chủ đề, phân tích và tối ưu hóa hình ảnh, sau đó đề xuất các cải tiến để tăng cường hiệu quả tiếp cận đến với người dùng

## Công nghệ và API sử dụng
- **DenseCap từ DeepAI**: Nhận diện và phân tích nội dung hình ảnh.
- **Colorizer từ DeepAI**: Tăng cường màu sắc cho hình ảnh.

## Cài đặt
1. Cài đặt thư viện `openai` và `requests`:
   ```bash
   pip install openai requests pillow
2. Đăng ký tài khoản tại DeepAI để lấy API Key miễn phí. Sau đó, đặt API Key vào file `main.py` trong biến `deepai_api_key`.
