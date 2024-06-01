# PYTHON DATA ANALYTICS

## PHÂN TÍCH VÀ TRỰC QUAN HÓA DỮ LIỆU VỚI PYTHON

### 📌 MỤC TIÊU

### Phân tích và xử lý dữ liệu với Numpy, pandas, Matplotlib

1. **Numpy**:

- Khái niệm cơ bản
- Mảng NumPy (ndarray), các thuộc tính cơ bản
- Indexing and Slicing
- Các phép toán trên mảng
- Mảng đa chiều, Broadcasting
- Lọc và truy vấn dữ liệu

2. **Pandas**

- Cách cài đặt Pandas
- Cấu trúc dữ liệu chính trong Pandas
- Tạo và thao tác với Series và DataFrame
- Đọc và ghi dữ liệu
- Thao tác dữ liệu, Nhóm và tổng hợp dữ liệu
- Xử lý dữ liệu bị thiếu
- Thao tác với dữ liệu thời gian

3. **Matplotlib**

- Cấu trúc cơ bản của một biểu đồ
- Vẽ biểu đồ cơ bản
- Biểu đồ nâng cao
- Tùy chỉnh biểu đồ
- Lưu đồ

### 💡 THỰC HÀNH VÀ ỨNG DỤNG

Trong phần này, chúng ta sẽ thực hành phân tích dữ liệu với hai bộ dataset: Bigmart Sales và Black Friday Sales. Cả hai đều là những ví dụ điển hình trong việc sử dụng khoa học dữ liệu để giải quyết các vấn đề trong ngành bán lẻ.

#### **Bigmart Sales**

1. Mô tả:

- Bigmart Sales là một bộ dữ liệu bao gồm các ghi chép giao dịch của một cửa hàng bán lẻ. Đây là một bài toán hồi quy, nơi chúng ta cần dự đoán doanh số bán hàng của một cửa hàng dựa trên các biến số khác nhau. Bộ dữ liệu có tổng cộng 8523 dòng và 12 biến

2. Ứng dụng:

- Ngành bán lẻ sử dụng phân tích dữ liệu để tối ưu hóa các quy trình kinh doanh như:

  - Sắp xếp sản phẩm
  - Quản lý hàng tồn kho
  - Đề xuất các chương trình khuyến mãi tùy chỉnh
  - Đóng gói sản phẩm

3. Vấn đề cần giải quyết:

- Phân tích dữ liệu chuẩn bị cho việc dự đoán doanh số bán hàng của một cửa hàng

#### **Black Friday Sales**

1. Mô tả:

- Black Friday Sales là một bộ dữ liệu bao gồm các giao dịch bán hàng được ghi lại tại một cửa hàng bán lẻ. Đây là một bộ dữ liệu điển hình để khám phá và mở rộng kỹ năng tạo đặc trưng (feature engineering) cũng như hiểu biết từ các trải nghiệm mua sắm hàng ngày. Đây là một bài toán hồi quy, với bộ dữ liệu chứa hơn 500,000 dòng và 12 cột

2. Ứng dụng:

- Bộ dữ liệu này giúp ta hiểu sâu hơn về các khía cạnh của việc mua sắm trong ngày Black Friday, một trong những ngày mua sắm lớn nhất trong năm. Nó có thể được sử dụng để:

  - Dự đoán số tiền mua sắm của khách hàng
  - Phân tích hành vi mua sắm
  - Xây dựng các chiến lược tiếp thị và bán hàng hiệu quả

3. Vấn đề cần giải quyết:

- Phân tích dữ liệu chuẩn bị cho việc dự đoán số tiền mua sắm của khách hàng

> Trong các phần tiếp theo, chúng ta sẽ đi vào chi tiết cách xử lý và phân tích hai bộ dữ liệu này, sử dụng các thư viện Python như Numpy, Pandas và Matplotlib để thực hiện các bước từ làm sạch dữ liệu, khám phá dữ liệu, đến phân tích dữ liệu để chuẩn bị cho việc xây dựng mô hình dự đoán.

> Bộ DataSet được lấy từ nguồn [Kaggle](https://www.kaggle.com/datasets)
