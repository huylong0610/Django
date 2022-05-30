IMPORTANT (QUAN TRỌNG): Code dưới đây được mình tham khảo và sửa đổi từ nguồn:
https://viblo.asia/p/python-django-xay-dung-ung-dung-e-commerce-part-1-LzD5da4dKjY



I/ Cài đặt requirements trước
1. Dùng câu lệnh để cài đặt các requirements trước
pip install -r requirements.txt

2. Nếu có lỗi thì cài riêng những cái lỗi:
vd: pip install pillow

3. Sau khi cài đặt thành công:
Dùng câu lệnh: 
py manage.py makemigrations -> để chạy database
py manage.py migrate -> để run database
py manage.py runserver -> để chạy trang web

II/ Hướng dẫn sử dụng:
1. Với admin để thêm sửa xóa sản phẩm:
- Dùng terminal Chạy câu lệnh: py manage.py createsuperuser để tạo admin
- Đăng kí theo các bước!

