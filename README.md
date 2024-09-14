
# Đánh Giá Thang Đo Hạnh Phúc Dựa Theo Dữ Liệu Thống Kê

## Môn Học: Khai Phá Dữ Liệu

### Nhóm thực hiện:
- Trần Nhật Minh - 2051052081
- Hồ Quang Văn - 2051050561
- Lê Đông Anh Kiệt - 2051052068
- Lớp: IT2002
- Giảng viên hướng dẫn: TS. Nguyễn Tiến Đạt, Thầy Nguyễn Văn Bảy

## Giới thiệu

Báo cáo này phân tích dữ liệu từ **World Happiness Report** từ năm 2015 đến năm 2022 để tìm hiểu về mức độ hạnh phúc của các quốc gia trên thế giới. Mục tiêu của báo cáo là khai thác và đánh giá sự tương quan giữa các yếu tố kinh tế, xã hội, và các chỉ số hạnh phúc của các quốc gia.

### Các thuộc tính quan trọng trong dữ liệu:
- `Country`: Quốc gia
- `Region`: Khu vực
- `Happiness Rank`: Xếp hạng hạnh phúc
- `Happiness Score`: Điểm số hạnh phúc
- `Economy (GDP per Capita)`: GDP bình quân đầu người
- `Health (Life Expectancy)`: Tuổi thọ trung bình
- `Freedom`: Tự do cá nhân
- `Trust (Government Corruption)`: Niềm tin vào chính phủ, nhận thức tham nhũng
- `Generosity`: Mức độ hào phóng
- `Dystopia Residual`: Chỉ số hạnh phúc giả định nếu không có các yếu tố tích cực.

## Công cụ và Thuật toán

- **Công cụ**: Sử dụng Google Colab với ngôn ngữ lập trình Python để xử lý và phân tích dữ liệu.
- **Thuật toán**: Các kỹ thuật phân tích được sử dụng bao gồm:
    - **Hồi quy tuyến tính**: Để đánh giá mức độ phù hợp giữa các biến.
    - **Phân cụm KMeans**: Phân nhóm các quốc gia dựa trên chỉ số hạnh phúc và GDP.
    - **Luật kết hợp**: Phân tích mối quan hệ giữa các yếu tố.
    - **Phân lớp và cây quyết định**: Dự đoán các quốc gia hạnh phúc dựa trên dữ liệu có sẵn.

## Các bước xử lý dữ liệu

1. **Chuẩn hóa dữ liệu**: Bổ sung các cột thiếu và loại bỏ các trường dữ liệu rỗng.
2. **Phân tích dữ liệu**:
    - Tìm ra các quốc gia có chỉ số hạnh phúc cao nhất trong 8 năm.
    - Phân tích theo khu vực dựa trên các chỉ số: hạnh phúc, GDP, tuổi thọ, chế độ phúc lợi, tự do tinh thần, hào phóng, nhận thức tham nhũng.
3. **Hồi quy tuyến tính**: Xác định mối quan hệ giữa GDP và chỉ số hạnh phúc.
4. **Phân cụm KMeans**: Phân nhóm các quốc gia dựa trên chỉ số GDP và hạnh phúc.
5. **Phân lớp và cây quyết định**: Dự đoán khả năng hạnh phúc của các quốc gia dựa trên chỉ số hạnh phúc.

## Kết quả chính

- **Các quốc gia hạnh phúc nhất**: Finland, Denmark, Iceland, Netherlands liên tục đứng đầu bảng xếp hạng hạnh phúc.
- **Phân tích theo khu vực**:
    - Bắc Mỹ, Châu Âu và Châu Úc là các khu vực có chỉ số hạnh phúc cao nhất.
    - Châu Á, Nam Mỹ có chỉ số hạnh phúc trung bình.
    - Châu Phi có chỉ số hạnh phúc thấp nhất, trong đó có nhiều quốc gia không được xếp hạng.
- **GDP và Hạnh phúc**: Có mối liên hệ rõ ràng giữa chỉ số GDP cao và mức độ hạnh phúc của quốc gia.
- **Tuổi thọ và Hạnh phúc**: Các quốc gia có tuổi thọ cao thường có mức độ hạnh phúc cao hơn.
- **Tự do cá nhân**: Việt Nam nằm trong nhóm các quốc gia có chỉ số tự do cá nhân cao.
- **Hào phóng và tham nhũng**: Các quốc gia có chỉ số hạnh phúc cao thường có mức độ hào phóng thấp và nhận thức về tham nhũng cao.

## Kết luận

Báo cáo này đã phân tích và đưa ra các kết luận quan trọng về mối quan hệ giữa các yếu tố kinh tế, xã hội và chỉ số hạnh phúc của các quốc gia từ năm 2015 đến năm 2022. Qua đó, chúng ta có thể hiểu sâu hơn về những yếu tố đóng vai trò quan trọng trong việc xây dựng một quốc gia hạnh phúc, từ GDP, tuổi thọ đến tự do cá nhân và nhận thức về tham nhũng.

## Hướng phát triển

- **Cải thiện mô hình**: Tăng cường độ chính xác của các mô hình dự đoán hạnh phúc, đặc biệt là ở các quốc gia có chỉ số hạnh phúc thấp.
- **Mở rộng dữ liệu**: Sử dụng thêm các nguồn dữ liệu khác để có cái nhìn toàn diện hơn về các yếu tố ảnh hưởng đến hạnh phúc.

---

**Tháng 08 năm 2023**

