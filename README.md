# 95LAB-DR-Rs
## Mô tả các công việc mà 95LAB có thể đảm nhận: ~ Tổng thời gian 6-8 months (240 days)
  - Sẵn sàn hướng dẫn quy trình thu thập, tiền xử lý dữ liệu, lọc dữ liệu.
  - Cung cấp tool và các công cụ liên quan hỗ trợ quá trình xây dựng cơ sở dữ liệu cho bệnh DR (Diabetic Retinopathy)
  - Nghiên cứu và xây dựng model phát triển API tích hợp hệ thống hoàn thiện

### Tiền xử lý ảnh fundus cho bài toán DR (Diabetic Retinopathy): ~ 80 -120 working days

| Bước                  | Mô tả                                                                 | Công cụ/Phương pháp          | Ghi chú     |
|-----------------------|-----------------------------------------------------------------------|------------------------------|-------------|
| **Thu thập dữ liệu**  | Quy trình thu thập tiền xử lý dữ liệu trước khi đến tay bác sĩ sẽ do 95LAB xây dựng tool tự động sàn lọc              |                              | 95LAB đảm nhận       |
| Lọc ảnh màu           | Chỉ giữ lại ảnh màu RGB                                               | OpenCV, PIL                  | 95LAB đảm nhận       |
| Lọc ảnh cùng size     | Kết hợp ảnh từ cùng một nguồn hoặc thiết bị                            | Python script                | 95LAB đảm nhận       |
| Lọc ảnh chất lượng    | Loại bỏ ảnh mờ, không rõ nét                                           | OpenCV, SIFT                 | 95LAB đảm nhận       |
| **Tiền phân loại**     |                                                                       |                              |             |
| Dự đoán DR             | Sử dụng mô hình deep learning do 95LAB cung cấp để xác định ảnh có nguy cơ DR hay không, giúp giảm thời gian sàn lọc data thô  | CNN, TensorFlow, PyTorch     | 95LAB đảm nhận       |
| **Gán nhãn mức độ**   |                                                                        |                              |             |
| Gán nhãn 0-4          | Gán Nhãn mức độ DR theo các tiêu chuẩn y tế và lưu vào phân mềm quản lý nhãn do 95LAB cung cấp        | Đánh giá của bác sĩ, 95LAB          |             |
| **Khoanh vùng lên ảnh**| Các bác sĩ sẽ sử dụng tool do 95LAB xây dựng và hướng dẫn             |                              | 95LAB đảm nhận       |
| Hoàng điểm            | Tìm vị trí của hoàng điểm và lưu toạ độ                                | OpenCV                       | 95LAB đảm nhận       |
| SE, MA, HE, EX        | Tìm và khoanh vùng các tổn thương                                      | Mask R-CNN                   | 95LAB đảm nhận       |



### Sơ đồ hệ thống AI: ~ 120 working days
 - Nghiên cứu và apply hàng loạt các model hiện đại phục vụ bài toán DR
   
![Sơ đồ tổng thể](https://github.com/hieund12/95LAB-DR-Rs/blob/20fb69d34e375e489f2070383ffdb340fc47a3d1/Screenshot%202023-09-02%20at%2016.21.23.png)
