# Hệ Thống Quản Lý Vị Trí Đỗ Xe Thông Minh Sử Dụng YOLOv8

## Giới thiệu

Đề tài này hướng tới việc xây dựng một **hệ thống giám sát và quản lý bãi đỗ xe thông minh** bằng cách sử dụng **trí tuệ nhân tạo (AI)**, cụ thể là mô hình **YOLOv8** để **phát hiện và giám sát phương tiện**
trong khu vực đỗ xe. Hệ thống giúp người quản lý dễ dàng theo dõi tình trạng các vị trí đỗ xe theo thời gian thực, đồng thời tối ưu hóa hiệu quả sử dụng không gian đỗ.

## Mục tiêu

- Phát hiện chính xác vị trí có xe và trống trong bãi đỗ bằng camera.
- Hiển thị thông tin trực quan các vị trí đang được sử dụng hoặc còn trống.
- Tích hợp hệ thống quản lý (giao diện web hoặc desktop).
- Cảnh báo hoặc ghi nhận khi có đỗ sai vị trí hoặc quá thời gian quy định (nếu cần).
- Ứng dụng học sâu (Deep Learning) thông qua mô hình YOLOv8.
- Cung cấp giao diện trực quan hoặc API phục vụ giám sát từ xa.

## Công nghệ sử dụng

- **YOLOv8**: Phát hiện đối tượng (xe máy, ô tô) theo thời gian thực.
- **OpenCV**: Xử lý ảnh và video từ camera.
- **Python**: Ngôn ngữ chính để xử lý AI và backend.
- **Flask/FastAPI**: Xây dựng API backend.
- **HTML/CSS/JS** : Giao diện người dùng.
- **CAMERA** : Thiết bị thu hình ảnh.

## Các tính năng chính

- Phát hiện và phân loại xe theo thời gian thực từ luồng camera.
- Theo dõi trạng thái từng ô đỗ (Trống / Có xe).
- Giao diện trực quan thể hiện bản đồ bãi đỗ và trạng thái hiện tại.
- Thống kê số lượng ô trống, số ô đã sử dụng.
- Tùy chọn mở rộng: cảnh báo đỗ sai, phân tích lưu lượng, tích hợp thanh toán...

## Quy trình hoạt động
![image](https://github.com/user-attachments/assets/e35545c4-cc96-417d-9be7-3e881b2b1432)

## Cấu trúc dự án
![image](https://github.com/user-attachments/assets/711062e3-cd15-494e-8b16-d995bf57ab31)

## 1 số hình ảnh hệ thống
![z6623897517794_323dbc8b8472749eb77677e09f00220a](https://github.com/user-attachments/assets/1668eadd-3e3d-4d52-956c-07fdc86c2c37)
![z6623897517793_0222b1de502e69a949111674c73fedee](https://github.com/user-attachments/assets/99531edd-7538-41b1-858c-291d59e92349)
![z6623897470119_7b001df5b1561a35322f23b8c514c168](https://github.com/user-attachments/assets/3a7fb648-cc96-4c88-8ce9-1ee61c36b9e5)
