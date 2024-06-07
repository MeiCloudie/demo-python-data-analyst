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

Trong phần này, chúng ta sẽ thực hành phân tích dữ liệu với các bộ DataSet:

#### **Bigmart Sales**

1. **Mô tả**:

- Bigmart Sales là một bộ dữ liệu bao gồm các ghi chép giao dịch của một cửa hàng bán lẻ. Đây là một bài toán hồi quy, nơi chúng ta cần dự đoán doanh số bán hàng của một cửa hàng dựa trên các biến số khác nhau. Bộ dữ liệu có tổng cộng 8523 dòng và 12 biến

2. **Ứng dụng**:

- Ngành bán lẻ sử dụng phân tích dữ liệu để tối ưu hóa các quy trình kinh doanh như:

  - Sắp xếp sản phẩm
  - Quản lý hàng tồn kho
  - Đề xuất các chương trình khuyến mãi tùy chỉnh
  - Đóng gói sản phẩm

3. **Vấn đề cần giải quyết**:

- Phân tích dữ liệu chuẩn bị cho việc dự đoán doanh số bán hàng của một cửa hàng

#### **Black Friday Sales**

1. **Mô tả**:

- Black Friday Sales là một bộ dữ liệu bao gồm các giao dịch bán hàng được ghi lại tại một cửa hàng bán lẻ. Đây là một bộ dữ liệu điển hình để khám phá và mở rộng kỹ năng tạo đặc trưng (feature engineering) cũng như hiểu biết từ các trải nghiệm mua sắm hàng ngày. Đây là một bài toán hồi quy, với bộ dữ liệu chứa hơn 500,000 dòng và 12 cột

2. **Ứng dụng**:

- Bộ dữ liệu này giúp ta hiểu sâu hơn về các khía cạnh của việc mua sắm trong ngày Black Friday, một trong những ngày mua sắm lớn nhất trong năm. Nó có thể được sử dụng để:

  - Dự đoán số tiền mua sắm của khách hàng
  - Phân tích hành vi mua sắm
  - Xây dựng các chiến lược tiếp thị và bán hàng hiệu quả

3. **Vấn đề cần giải quyết**:

- Phân tích dữ liệu chuẩn bị cho việc dự đoán số tiền mua sắm của khách hàng

#### **Golden Ball (The Ballon d'Or)**

1. **Mô tả**:

- Ballon d'Or (Quả Bóng Vàng) là một giải thưởng bóng đá hàng năm do tạp chí France Football trao tặng, được xem là một trong những giải thưởng cá nhân danh giá nhất dành cho các cầu thủ bóng đá. Giải thưởng này đã được trao từ năm 1956, mặc dù từ năm 2010 đến 2015, giải thưởng này đã được hợp nhất tạm thời với giải Cầu thủ xuất sắc nhất thế giới của FIFA và được gọi là FIFA Ballon d'Or. Tuy nhiên, sự hợp tác này đã kết thúc vào năm 2016 và giải thưởng trở lại với tên gọi Ballon d'Or, trong khi FIFA cũng trở lại với giải thưởng hàng năm riêng của mình là The Best FIFA Men's Player.

- Ban đầu, giải thưởng này chỉ dành cho các cầu thủ từ châu Âu và được biết đến rộng rãi như giải Cầu thủ xuất sắc nhất châu Âu. Vào năm 1995, Ballon d'Or đã mở rộng để bao gồm tất cả các cầu thủ từ bất kỳ quốc gia nào miễn là đang chơi bóng tại các câu lạc bộ châu Âu. Đến năm 2007, giải thưởng này đã trở thành một giải thưởng toàn cầu với tất cả các cầu thủ bóng đá chuyên nghiệp trên khắp thế giới đều đủ điều kiện tham gia.

2. **Ứng dụng**:

- Giải thưởng Ballon d'Or không chỉ có ý nghĩa danh giá mà còn có ảnh hưởng lớn đến sự nghiệp của các cầu thủ bóng đá, bao gồm:

* Công nhận thành tựu cá nhân của các cầu thủ xuất sắc.
* Nâng cao giá trị thương hiệu và sự công nhận toàn cầu của các cầu thủ.
* Góp phần thúc đẩy và nâng cao hình ảnh của các câu lạc bộ bóng đá.

3. **Vấn đề cần giải quyết**:

- Phân tích dữ liệu để tìm hiểu các xu hướng, đặc điểm của các cầu thủ đã giành được giải thưởng Ballon d'Or qua các năm và xác định các yếu tố ảnh hưởng đến việc giành giải thưởng này.

<hr>

> Trong các phần tiếp theo, chúng ta sẽ đi vào chi tiết cách xử lý và phân tích hai bộ dữ liệu này, sử dụng các thư viện Python như Numpy, Pandas và Matplotlib để thực hiện các bước từ làm sạch dữ liệu, khám phá dữ liệu, đến phân tích dữ liệu để chuẩn bị cho việc xây dựng mô hình dự đoán.

> Các Bộ DataSet được lấy từ nguồn [Kaggle](https://www.kaggle.com/datasets)
