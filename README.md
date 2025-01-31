# Heart Disease Prediction

## Giới thiệu
Dự án này nhằm mục đích dự đoán nguy cơ mắc bệnh tim dựa trên các đặc điểm lâm sàng của bệnh nhân bằng cách sử dụng các thuật toán học máy.

## Yêu cầu hệ thống
- Python 3.x
- Các thư viện cần thiết:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib (tuỳ chọn, nếu cần vẽ biểu đồ)
  - seaborn (tuỳ chọn, để trực quan hóa dữ liệu)

## Cài đặt
1. Clone repository này:
   ```bash
   git clone <repository-url>
   cd heart-disease
   ```
2. Cài đặt các thư viện yêu cầu:
   ```bash
   pip install -r requirements.txt
   ```

## Hướng dẫn sử dụng
1. Chạy tập lệnh xử lý dữ liệu:
   ```bash
   python data_preprocessing.py
   ```
2. Chạy mô hình học máy:
   ```bash
   python train_model.py
   ```
3. Đánh giá mô hình:
   ```bash
   python evaluate_model.py
   ```


