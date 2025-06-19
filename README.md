# Doctruyen

Ứng dụng web để đọc truyện, tiểu thuyết, và truyện tranh trực tuyến. Doctruyen cung cấp giao diện thân thiện cho người đọc để khám phá và thưởng thức nội dung.

## Tính năng

- Hệ thống xác thực người dùng
- Duyệt truyện theo danh mục
- Đánh dấu truyện yêu thích
- Chức năng tìm kiếm

## Cài đặt

```bash
# Sao chép kho lưu trữ
git clone https://github.com/yourusername/doctruyen.git

# Di chuyển đến thư mục dự án
cd doctruyen

# Cài đặt các phụ thuộc
composer install
npm install

# Sao chép tệp môi trường
cp .env.example .env

# Tạo khóa ứng dụng
php artisan key:generate

# Cấu hình cơ sở dữ liệu trong tệp .env
# Sau đó chạy migrations
php artisan migrate

# Biên dịch tài nguyên
npm run dev
```

## Sử dụng

```bash
# Khởi động máy chủ phát triển cục bộ
php artisan serve
```

Truy cập `http://localhost:8000` trong trình duyệt của bạn để sử dụng ứng dụng.

## Biểu đồ database Class diagram
![Class diagram](dLGzRzim4Dq5w3ySlBWVI9gkHXl4iT4eW2kqjJLaCcY9SOXAb42U-eci7OBq1xJeqA5ZWUprQC3_G_-a5tquaaCPHhY8U4-yU_Vko2EDJ64QXRQbtmkPCCKYy4EcTHzHYLcA_DIFvLXyuN1WMxRLXPVh1QDiyVCDk2UhcspnwnI6on_kIOsthJmIU9eh-6fR.png)

## Biểu đồ database Usecase diagram
![Usecase diagram](PPD1QzH05CVlWNo7nthHGwdTRTVs8hLTYo08LWMluyoO34acwsHIMCHJ3nv4iCSU18lqKheWU793wM4MlyTy4zyaizacNfRyt_kzD__tPdQ_q4JfCal38ENlDUWSb8XY3KmeJhN8PHWKYP1JeaW6Kq8J4l5NUfPoS7aYevJV9Sg2Kr9m-1W600U8Hoel9JlC.png)


## Công nghệ

- Laravel
- MySQL
- Vue.js/React (Framework Frontend)
- Tailwind CSS

## Hình ảnh trang web
### Đăng nhập 
![Đăng nhập](đăngnhập.png)
### Giao diện người dùng
![1](user1.png)
![2](user2.png)
![3](user3.png)
### Giao diện admin
![admin](admin.png)



### 

## Giấy phép

Phân phối theo Giấy phép MIT. Xem `LICENSE` để biết thêm thông tin.

