# Stock_Price_Prediction
Dự án: Dự đoán biến động giá cổ phiếu 4 công ty (FPT, PNJ, MSN, VIC) bằng LSTM và XGBoost

**1. Giới thiệu**
Mục tiêu: Dự đoán biến động giá cổ phiếu của 4 công ty lớn tại Việt Nam (FPT, PNJ, MSN, VIC) trong tương lai gần dựa trên dữ liệu lịch sử.

Mô hình:
LSTM: Mạng thần kinh tuần hoàn dài hạn (Long Short-Term Memory) được sử dụng để tận dụng thông tin chuỗi thời gian trong dữ liệu chứng khoán.
XGBoost: Thuật toán tăng cường gradient (Gradient Boosting) được sử dụng để so sánh hiệu suất và tìm kiếm mô hình tối ưu.

Đánh giá:
MSE (Mean Squared Error): Được sử dụng để đo lường độ chính xác của mô hình, với mục tiêu đạt được MSE từ 0.05 đến 0.2.

**2. Dữ liệu**

Các chỉ tiêu: Giá đóng cửa, giá mở cửa, giá cao nhất, giá thấp nhất, khối lượng giao dịch

Tiền xử lý:
Làm sạch dữ liệu: Xử lý dữ liệu thiếu, ngoại lệ.

Chuẩn hóa dữ liệu: Tiêu chuẩn hóa hoặc chuẩn hóa dữ liệu để cải thiện hiệu suất mô hình.

**3. Mô hình**

LSTM:
Cấu trúc mạng: Số lớp, số neuron, hàm kích hoạt,...
Huấn luyện: Optimizer, loss function, số epoch,...

XGBoost:
Tùy chỉnh hyperparameter: Số cây quyết định, độ sâu cây, learning rate,...
So sánh hiệu suất: So sánh MSE của hai mô hình trên tập kiểm thử.

**4. Kết quả**

Đánh giá: Trình bày kết quả dự đoán của cả hai mô hình trên tập kiểm thử.

Biểu đồ: Vẽ biểu đồ so sánh giá thực tế và giá dự đoán.

Phân tích: Phân tích ưu nhược điểm của từng mô hình, nguyên nhân dẫn đến kết quả.
