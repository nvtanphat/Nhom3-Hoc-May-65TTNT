# XÂY DỰNG MÔ HÌNH HỌC SÂU CHO BÀI TOÁN PHÂN LOẠI BỆNH TRÊN GÀ TỪ ẢNH PHÂN GÀ

**Môn học:** Học Máy
**Lớp:** S26-65TTNT
**Giảng viên:** ThS. Vũ Thị Hạnh

**Nhóm thực hiện:** Nhóm 3
**Thành viên:**
1. Nguyễn Văn Tấn Phát
2. Nguyễn Hoàng Lộc
3. Trần Thiên Bảo
4. Phạm Thành Doanh

## Giới thiệu
Dự án này tập trung vào việc xây dựng mô hình học sâu (Deep Learning) để phân loại bệnh trên gà dựa vào hình ảnh phân gà. Chúng tôi thực hiện huấn luyện và đánh giá trên 4 mô hình khác nhau, bao gồm một mô hình CNN tự xây dựng và 3 mô hình Transfer Learning phổ biến.

## Dữ liệu (Dataset)
Bộ dữ liệu được sử dụng trong dự án này là **Chicken Disease Image Classification**, có sẵn trên Kaggle.
- **Nguồn:** [Chicken Disease Dataset](https://www.kaggle.com/datasets/allandclive/chicken-disease-1)
- **Mô tả:** Bộ dữ liệu bao gồm hình ảnh phân gà được phân loại thành các nhóm bệnh khác nhau (ví dụ: Coccidiosis, Healthy, New Castle Disease, Salmonella).

## Danh sách các Notebooks
Thư mục này chứa 4 notebook tương ứng với quá trình huấn luyện của 4 mô hình:

### 1. CNN From Scratch (`01_cnn_from_scratch.ipynb`)
- **Mô tả:** Xây dựng một mô hình Convolutional Neural Network (CNN) cơ bản từ đầu.
- **Mục tiêu:** Thiết lập baseline để so sánh hiệu quả với các mô hình pre-trained phức tạp hơn.

### 2. MobileNetV3 (`02_mobilenetv3.ipynb`)
- **Mô tả:** Sử dụng kiến trúc MobileNetV3 (Small/Large) đã được huấn luyện trước (pre-trained).
- **Mục tiêu:** Tận dụng ưu điểm nhẹ và nhanh của MobileNet cho các thiết bị di động/nhúng, đánh giá sự cân bằng giữa tốc độ và độ chính xác.

### 3. ResNet50 (`03_resnet50.ipynb`)
- **Mô tả:** Sử dụng kiến trúc ResNet50 với kỹ thuật Residual Learning.
- **Mục tiêu:** Đánh giá khả năng trích xuất đặc trưng sâu của mạng ResNet trên tập dữ liệu ảnh phân gà.

### 4. EfficientNetB3 (`04_efficientnetb3.ipynb`)
- **Mô tả:** Sử dụng kiến trúc EfficientNetB3, mô hình tối ưu hóa cả chiều sâu, chiều rộng và độ phân giải.
- **Mục tiêu:** Đạt được độ chính xác cao nhất có thể bằng cách sử dụng kiến trúc EfficientNet hiện đại.

## Yêu cầu cài đặt
## Hướng dẫn sử dụng

