# Project - Emoji Image Generation - PM09 - AIO2024

**Emoji Generation (Tạo sinh ảnh biểu tượng cảm xúc)** là một bài toán thuộc lĩnh vực Thị giác máy tính (Computer Vision) và Mô hình tạo sinh (Generative Models), tập trung vào việc xây dựng một hệ thống có khả năng tạo ra các emoji mới dựa trên mô tả văn bản hoặc các đặc trưng hình ảnh đầu vào.

Trong bài toán này, chúng ta sẽ áp dụng **Stable Diffusion Model**, một mô hình khuếch tán mạnh mẽ, để sinh ra các emoji theo yêu cầu.

## 1. Mô tả bài toán: 
- **Input:** Một prompt mô tả emoji cần tạo (hình dáng, màu sắc, biểu cảm, nền). Ví dụ: "Một emoji chú mèo dễ thương, có màu cầu vồng, miệng cười, mắt nhắm, đang lơ lửng giữa không trung, nền tối màu".<br>
- **Output:** Hình ảnh emoji mới được tạo theo prompt, mang phong cách từ tập dữ liệu emoji đã được huấn luyện.

## 2. Project pipeline:
![Project pipeline](/readme_image/pipeline.png 'AIO2024')