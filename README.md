# Online Payment Fraud Detection

## Giới thiệu
Đây là dự án phát hiện gian lận trong thanh toán trực tuyến bằng cách sử dụng các thuật toán Machine Learning. Mục tiêu của dự án là phân tích dữ liệu giao dịch, xác định các hành vi gian lận và xây dựng mô hình có khả năng dự đoán các giao dịch đáng ngờ.

## Dữ liệu sử dụng
- **Dataset**: Tập dữ liệu chứa thông tin về các giao dịch trực tuyến, bao gồm các thuộc tính như số tiền giao dịch, thời gian, phương thức thanh toán, quốc gia, v.v.
- **Label**: Xác định giao dịch hợp lệ hoặc gian lận.

## Công nghệ sử dụng
- **Ngôn ngữ lập trình**: Python
- **Thư viện**:
  - Pandas, NumPy: Xử lý dữ liệu
  - Scikit-learn: Xây dựng mô hình Machine Learning
  - Matplotlib, Seaborn: Trực quan hóa dữ liệu
- **Mô hình học máy**:
  - Decision Tree, Random Forest, Logistic Regression, XGBoost
  - Neural Network (nếu có)

## Các bước thực hiện
1. **Tiền xử lý dữ liệu**: Làm sạch và chuẩn hóa dữ liệu.
2. **Phân tích dữ liệu**: Xác định xu hướng và đặc trưng của gian lận.
3. **Xây dựng mô hình**: Huấn luyện và đánh giá các mô hình Machine Learning.
4. **Triển khai mô hình**: Tích hợp mô hình vào hệ thống phát hiện gian lận.

## Cách sử dụng
1. Clone repository về máy:
   ```sh
   git clone https://github.com/hoangphuu/Online-Payment-fraud-detection.git
   ```
2. Cài đặt các thư viện cần thiết:
   ```sh
   pip install -r requirements.txt
   ```
3. Chạy file chính để huấn luyện mô hình:
   ```sh
   python train_model.py
   ```
4. Kiểm tra kết quả dự đoán:
   ```sh
   python predict.py --input transaction_data.csv
   ```


