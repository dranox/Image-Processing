# Image-Processing

Thực hiện các chức năng xử lý ảnh cơ bản sau:
    
1. Thay đổi độ sáng cho ảnh (1 điểm)

![img](https://imgur.com/oJ8bTv7.jpg)

2. Thay đổi độ tương phản (1 điểm)

![img](https://imgur.com/wl8MSu3.jpg)

3. Lật ảnh (ngang - dọc) (1 điểm)

![img](https://imgur.com/MOOvIhN.jpg)

4. Chuyển đổi ảnh RGB thành ảnh xám/sepia (2 điểm)

- Ảnh xám

![img](https://imgur.com/XEfRXWE.jpg)

- Ảnh sepia

![img](https://imgur.com/YXUPjHY.jpg)

Keywords: convert RGB to grayscale/sepia

5. Làm mờ/sắc nét ảnh (2 điểm)

- Làm mờ

![img](https://imgur.com/wZT4vUa.jpg)

- Làm sắc nét

![img](https://imgur.com/H2Fq4Ne.jpg)

Tham khảo tại [đây](https://en.wikipedia.org/wiki/Kernel_(image_processing))

6. Cắt ảnh theo kích thước (cắt ở trung tâm) (1 điểm)

![img](https://imgur.com/fXebjfO.jpg)

7. Cắt ảnh theo khung hình tròn (1 điểm)

![img](https://imgur.com/DEpimhC.jpg)

8. Viết hàm main xử lý (1 điểm) với các yêu cầu sau:

- Cho phép người dùng nhập vào tên tập tin ảnh mỗi khi hàm main được thực thi.
- Cho phép người dùng lựa chọn chức năng xử lý ảnh (từ 1 đến 7, đối với chức năng 4 cho phép lựa chọn giữa lật ngang hoặc lật dọc). Lựa chọn 0 cho phép thực hiện tất cả chức năng với tên file đầu ra tương ứng với từng chức năng. Ví dụ:
    - Đầu vào: `cat.png`
    - Chức năng: Làm mờ
    - Đầu ra: `cat_blur.png`
