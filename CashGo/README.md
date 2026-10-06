#  CASHGO

## Ứng dụng so sánh giá đa sàn và hoàn tiền khi mua hàng

---

## 1. Giới thiệu đề tài

**CashGo** là ứng dụng di động hỗ trợ người dùng mua sắm trực tuyến tiết kiệm hơn thông qua việc **so sánh giá sản phẩm giữa nhiều sàn thương mại điện tử** và **nhận hoàn tiền (Cashback)** khi mua hàng thông qua liên kết tiếp thị liên kết (Affiliate Link).

Các nền tảng dự kiến hỗ trợ:

- Shopee
- Lazada
- TikTok Shop

CashGo hướng đến việc kết hợp nhiều chức năng mua sắm trong cùng một ứng dụng:

- Tìm kiếm sản phẩm.
- So sánh giá đa sàn.
- Kiểm tra mức hoàn tiền.
- Tạo liên kết mua hàng Affiliate.
- Theo dõi đơn hàng.
- Quản lý Cashback.
- Rút tiền.
- Theo dõi biến động giá.
- Nhận thông báo giảm giá.

---

## 2. Lý do chọn đề tài

Hiện nay việc mua sắm trực tuyến ngày càng phổ biến.

Một sản phẩm có thể được bán trên nhiều nền tảng thương mại điện tử với mức giá, voucher, phí vận chuyển và chương trình khuyến mãi khác nhau.

Người dùng thường phải truy cập từng ứng dụng như Shopee, Lazada hoặc TikTok Shop để tìm kiếm và so sánh trước khi quyết định mua hàng.

Ngoài ra, nhiều người dùng chưa tận dụng được các chương trình Affiliate và Cashback để tiết kiệm thêm chi phí.

Vì vậy nhóm đề xuất xây dựng **CashGo** nhằm giúp người dùng:

1. Tìm kiếm sản phẩm nhanh chóng.
2. So sánh giá giữa nhiều sàn.
3. Kiểm tra mức Cashback.
4. Chọn phương án mua hàng phù hợp.
5. Theo dõi đơn hàng.
6. Nhận và quản lý tiền hoàn.

---

## 3. Vấn đề cần giải quyết

### 3.1. Khó so sánh giá giữa nhiều sàn

Người dùng phải mở từng ứng dụng để tìm kiếm cùng một sản phẩm.

CashGo hướng đến việc tổng hợp thông tin sản phẩm từ nhiều nền tảng để người dùng dễ dàng so sánh.

### 3.2. Giá niêm yết chưa phản ánh toàn bộ chi phí

Một sản phẩm có giá niêm yết thấp hơn chưa chắc là lựa chọn tiết kiệm nhất.

Chi phí thực tế còn phụ thuộc vào:

- Giá sản phẩm.
- Voucher.
- Phí vận chuyển.
- Cashback.
- Các chương trình ưu đãi.

Công thức tham khảo:

**Chi phí thực tế = Giá sản phẩm + Phí vận chuyển - Voucher - Cashback**

### 3.3. Người dùng chưa tận dụng Cashback

CashGo hỗ trợ người dùng truy cập sản phẩm thông qua Affiliate Link.

Khi đơn hàng đáp ứng các điều kiện của chương trình Affiliate, một phần hoa hồng có thể được chia lại cho người dùng dưới dạng Cashback.

### 3.4. Khó theo dõi tiền hoàn

CashGo cung cấp:

- Đơn hàng đang chờ.
- Đơn hàng đã ghi nhận.
- Đơn hàng hoàn tất.
- Cashback đang chờ.
- Cashback khả dụng.
- Lịch sử giao dịch.

### 3.5. Khó theo dõi biến động giá

Giá sản phẩm trên các sàn có thể thay đổi theo thời gian.

CashGo hướng đến việc cho phép người dùng theo dõi giá và nhận thông báo khi sản phẩm đạt mức giá mong muốn.

---

## 4. Mục tiêu của dự án

### Mục tiêu chính

Xây dựng một ứng dụng hỗ trợ người dùng mua sắm trực tuyến thuận tiện và tiết kiệm hơn.

### Mục tiêu cụ thể

- So sánh giá đa sàn.
- Hiển thị Cashback dự kiến.
- Hỗ trợ tạo Affiliate Link.
- Theo dõi trạng thái đơn hàng.
- Quản lý ví Cashback.
- Hỗ trợ rút tiền.
- Theo dõi biến động giá.
- Thông báo khi sản phẩm giảm giá.
- Hỗ trợ nhiều ngôn ngữ.

---

## 5. Đối tượng người dùng

CashGo hướng đến:

- Sinh viên.
- Người trẻ.
- Người thường xuyên mua sắm trực tuyến.
- Người sử dụng Shopee.
- Người sử dụng Lazada.
- Người sử dụng TikTok Shop.
- Người muốn tiết kiệm chi phí khi mua sắm.

---

## 6. Giải pháp của CashGo

Luồng hoạt động chính:

**Người dùng**

↓

**Tìm kiếm sản phẩm hoặc dán link sản phẩm**

↓

**CashGo nhận diện sản phẩm**

↓

**So sánh sản phẩm giữa các sàn**

↓

**Hiển thị giá + ưu đãi + Cashback**

↓

**Người dùng lựa chọn sàn**

↓

**CashGo tạo Affiliate Link**

↓

**Người dùng chuyển sang sàn thương mại điện tử**

↓

**Người dùng mua hàng**

↓

**Đơn hàng được ghi nhận**

↓

**Đơn hàng được xác nhận**

↓

**Cashback được cộng vào ví CashGo**

↓

**Người dùng rút tiền**

---

## 7. Điểm khác biệt của CashGo

CashGo không chỉ là ứng dụng hoàn tiền.

Ứng dụng hướng đến việc kết hợp:

###  So sánh giá đa sàn

So sánh sản phẩm giữa:

- Shopee
- Lazada
- TikTok Shop

###  Cashback

Hiển thị số tiền hoàn dự kiến cho người dùng.

###  Affiliate Link

Hỗ trợ chuyển link sản phẩm thành Affiliate Link.

###  Theo dõi đơn hàng

Người dùng có thể kiểm tra trạng thái của từng đơn hàng.

###  Ví CashGo

Quản lý:

- Cashback đang chờ.
- Cashback khả dụng.
- Lịch sử giao dịch.
- Rút tiền.

###  Theo dõi giá

Theo dõi sự thay đổi giá của sản phẩm.

###  Thông báo giảm giá

Người dùng có thể đặt mức giá mong muốn và nhận thông báo khi sản phẩm giảm giá.

---

## 8. Chức năng chính

### Tài khoản

- Đăng ký.
- Đăng nhập.
- Quên mật khẩu.
- Quản lý thông tin cá nhân.

### Trang chủ

- Deal nổi bật.
- Sản phẩm nổi bật.
- Cashback cao.
- Truy cập nhanh các sàn.

### Tìm kiếm

- Tìm kiếm sản phẩm.
- Xem kết quả.
- Lọc sản phẩm.

### So sánh giá

- So sánh giá giữa các sàn.
- So sánh Cashback.
- Đề xuất lựa chọn phù hợp.

### Cashback

- Dán link sản phẩm.
- Nhận diện sàn.
- Kiểm tra Cashback.
- Tạo Affiliate Link.

### Đơn hàng

- Danh sách đơn hàng.
- Chi tiết đơn.
- Trạng thái đơn.
- Cashback của đơn.

### Ví CashGo

- Số dư khả dụng.
- Cashback đang chờ.
- Lịch sử giao dịch.
- Rút tiền.

### Theo dõi giá

- Lưu sản phẩm.
- Theo dõi biến động giá.
- Đặt mức giá mong muốn.

### Thông báo

- Thông báo giảm giá.
- Thông báo đơn hàng.
- Thông báo Cashback.

### Tài khoản

- Hồ sơ cá nhân.
- Ngôn ngữ.
- Cài đặt.
- Trung tâm hỗ trợ.

---

## 9. Các màn hình dự kiến

1. Splash Screen
2. Onboarding
3. Login
4. Register
5. Forgot Password
6. Home
7. Search
8. Search Result
9. Compare Product
10. Product Detail
11. Create Cashback Link
12. Cashback Result
13. Orders
14. Order Detail
15. Wallet
16. Withdraw
17. Transaction History
18. Favorites
19. Price Tracking
20. Notifications
21. Profile
22. Settings
23. Language
24. Help Center

---

## 10. Bottom Navigation

Thanh điều hướng chính gồm:

**Trang chủ | Đơn hàng | Tạo link | Ví | Tài khoản**

---

## 11. Công nghệ dự kiến

### Mobile Application

- Flutter
- Dart

### Backend

- REST API

### Database

Dự kiến nghiên cứu sử dụng:

- Firebase
- MySQL
- PostgreSQL

### UI/UX

- Figma

### Version Control

- Git
- GitHub

---

## 12. Thiết kế Figma

Figma dự kiến gồm các Page:

1. Cover
2. Design System
3. User Flow
4. Authentication
5. Home
6. Search & Compare
7. Cashback
8. Orders
9. Wallet
10. Profile
11. Prototype

### Link Figma

**Đang cập nhật**

---

## 13. Tiến độ Tuần 1

- [x] Chọn đề tài
- [x] Lên ý tưởng
- [x] Xác định vấn đề thực tế
- [x] Đề xuất giải pháp
- [x] Xác định đối tượng người dùng
- [x] Xác định chức năng ứng dụng
- [ ] Phân tích chi tiết đối thủ
- [ ] Hoàn thiện User Flow
- [ ] Hoàn thiện Use Case
- [ ] Thiết kế Database
- [ ] Hoàn thiện toàn bộ UI trên Figma
- [ ] Nối Prototype Figma

---

## 14. Thành viên nhóm

|STT| Họ và tên          |    MSSV
| 1 | Phạm Minh Nhật     | 068206010555
| 2 | Trần Lê Đông Nghi  | 079306041859
| 3 | Lê Hoàng Minh Nhật | 067206003243


---

## 15. Trạng thái dự án

**Tuần 1 – Nghiên cứu, phân tích và thiết kế ứng dụng CashGo.**
