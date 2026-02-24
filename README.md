# Phân Tích và Dự Đoán Giá Nhà 

## Giới thiệu
Đây là sản phẩm thực nghiệm môn **Học Máy** tại **Trường Đại học Khoa học Tự nhiên – ĐHQGHN**, với mục tiêu xây dựng một hệ thống phân tích và dự đoán giá nhà

## Thành viên thực hiện
- Nguyễn Thị Hoàng Yến


## Dữ liệu
Bộ dữ liệu sử dụng: **House Prices - Advanced Regression Techniques** (Kaggle)  
- Link tải: [Google Drive]
+ tập train: https://drive.google.com/file/d/1MxBekO1SWGZIZGmhb-T60NAFKbuPjxJo/view?usp=sharing
+ tập test:  https://drive.google.com/file/d/12cXCBbm4WOt6KEmVOF2kEF8qrFBiqvNs/view?usp=sharing

Gồm các nhãn:
- `  Id ', 'MSSubClass', 'LotFrontage', 'LotArea', 'OverallQual',...
## Quy trình thực hiện
1. **Tiền xử lý dữ liệu**: xử lý những dữ liệu bị thiếu, chuẩn hóa dữ liệu
2. **Giảm chiều dữ liệu**: PCA, LDA.
3. **Phân cụm không giám sát**: K-Means.
4. **Huấn luyện mô hình phân loại**:
   - Linear Regression
   - Multi Layer Perceptron
   - Rừng ngẫu nhiên (Random Forest)
5. **Đánh giá mô hình**: Mean Squared Error (MSE), R-squared

## Kết quả nổi bật
| Mô hình           |MSE cao nhất |
|-------------------|------------------|
| Random Forest     | ~0.9            |
| MLP         | ~0.8            |
| LinearRegression          | ~0.83            |

## Hướng dẫn chạy
1. Cài đặt Python ≥ 3.8 và các thư viện: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, 
2. Chạy file tương ứng trong từng thư mục để huấn luyện mô hình hoặc thử nghiệm.

## Ghi chú
Dự án được thực hiện trong khuôn khổ học phần, do đó có thể còn hạn chế về hiệu suất và tối ưu hoá mô hình.
