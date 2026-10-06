# 01. NGHIÊN CỨU VÀ PHÂN TÍCH ĐỀ TÀI CASHGO

## 1. Tổng quan đề tài

### 1.1. Tên đề tài

**CashGo – Ứng dụng so sánh giá đa sàn và hoàn tiền khi mua hàng**

### 1.2. Mô tả đề tài

CashGo là ứng dụng di động hỗ trợ người dùng mua sắm trực tuyến tiết kiệm hơn bằng cách kết hợp hai chức năng chính:

- So sánh giá sản phẩm giữa nhiều sàn thương mại điện tử.
- Hoàn tiền (Cashback) khi người dùng mua hàng thông qua liên kết Affiliate.

Các nền tảng thương mại điện tử dự kiến hỗ trợ:

- Shopee
- Lazada
- TikTok Shop

Ngoài hai chức năng chính, CashGo còn hướng đến:

- Theo dõi đơn hàng Cashback.
- Quản lý ví Cashback.
- Theo dõi biến động giá sản phẩm.
- Thông báo khi sản phẩm giảm giá.
- Lưu sản phẩm yêu thích.
- Hỗ trợ nhiều ngôn ngữ.

---

# 2. Bối cảnh thực tế

Mua sắm trực tuyến ngày càng trở thành một hình thức mua hàng phổ biến.

Người dùng có thể tìm cùng một sản phẩm trên nhiều nền tảng thương mại điện tử khác nhau như Shopee, Lazada và TikTok Shop.

Tuy nhiên, mỗi nền tảng có:

- Giá bán khác nhau.
- Voucher khác nhau.
- Phí vận chuyển khác nhau.
- Chương trình khuyến mãi khác nhau.
- Chính sách hoàn tiền khác nhau.

Điều này khiến người dùng khó xác định nơi mua hàng có lợi nhất.

Ví dụ:

Một sản phẩm có thể được bán:

| Nền tảng | Giá sản phẩm | Voucher | Cashback |
|---|---:|---:|---:|
| Shopee | 500.000đ | 30.000đ | 20.000đ |
| Lazada | 480.000đ | 10.000đ | 15.000đ |
| TikTok Shop | 510.000đ | 50.000đ | 25.000đ |

Nếu chỉ nhìn vào giá niêm yết, Lazada có giá thấp nhất.

Tuy nhiên, sau khi tính voucher và Cashback, TikTok Shop có thể trở thành lựa chọn có lợi hơn.

Do đó, người dùng cần một công cụ hỗ trợ so sánh nhiều yếu tố thay vì chỉ so sánh giá niêm yết.

---

# 3. Vấn đề thực tế cần giải quyết

## 3.1. Người dùng phải tìm kiếm trên nhiều ứng dụng

Khi muốn mua một sản phẩm, người dùng thường phải:

1. Mở Shopee.
2. Tìm sản phẩm.
3. Ghi nhớ giá.
4. Mở Lazada.
5. Tìm lại sản phẩm.
6. So sánh giá.
7. Mở TikTok Shop.
8. Tiếp tục tìm kiếm.
9. Kiểm tra voucher.
10. So sánh lại.

Quá trình này tốn thời gian và gây bất tiện.

### Giải pháp của CashGo

CashGo hướng đến việc tổng hợp thông tin sản phẩm để hỗ trợ người dùng so sánh trên cùng một giao diện.

---

## 3.2. Giá thấp nhất chưa chắc là lựa chọn tiết kiệm nhất

Giá niêm yết không phải yếu tố duy nhất quyết định chi phí cuối cùng.

Người dùng còn phải xem xét:

- Voucher.
- Phí vận chuyển.
- Cashback.
- Khuyến mãi.
- Ưu đãi của từng nền tảng.

CashGo sử dụng các thông tin này để hỗ trợ người dùng đánh giá phương án mua hàng.

Công thức tham khảo:

**Chi phí thực tế = Giá sản phẩm + Phí vận chuyển - Voucher - Cashback**

---

## 3.3. Người dùng chưa tận dụng được Affiliate Cashback

Affiliate Marketing cho phép một hệ thống nhận hoa hồng khi người dùng mua hàng thông qua một liên kết giới thiệu.

CashGo hướng đến việc sử dụng cơ chế này để chia lại một phần lợi ích cho người dùng dưới dạng Cashback.

Luồng cơ bản:

**Link sản phẩm**

↓

**CashGo**

↓

**Affiliate Link**

↓

**Người dùng mua hàng**

↓

**Đơn hàng được ghi nhận**

↓

**Hoa hồng được xác nhận**

↓

**Cashback cho người dùng**

---

## 3.4. Khó theo dõi trạng thái Cashback

Sau khi mua hàng, Cashback thường không được xác nhận ngay lập tức.

Đơn hàng có thể trải qua các trạng thái:

**Đang chờ**

↓

**Đã ghi nhận**

↓

**Đã xác nhận**

↓

**Cashback khả dụng**

Ngoài ra đơn hàng có thể:

**Bị hủy / Không đủ điều kiện**

CashGo cung cấp màn hình quản lý đơn hàng để người dùng theo dõi quá trình này.

---

## 3.5. Khó theo dõi biến động giá

Giá của sản phẩm trên các sàn thương mại điện tử có thể thay đổi liên tục.

Người dùng có thể mua một sản phẩm với giá cao và sau đó sản phẩm giảm giá.

CashGo hướng đến chức năng:

- Theo dõi sản phẩm.
- Lưu lịch sử giá.
- Hiển thị biến động giá.
- Đặt mức giá mong muốn.
- Thông báo khi giá giảm.

---

# 4. Nhu cầu của người dùng

Qua phân tích vấn đề, người dùng có các nhu cầu chính:

### Nhu cầu 1

Tìm sản phẩm nhanh chóng.

### Nhu cầu 2

So sánh giá giữa nhiều nền tảng.

### Nhu cầu 3

Biết được Cashback trước khi mua.

### Nhu cầu 4

Biết phương án mua hàng nào có lợi hơn.

### Nhu cầu 5

Theo dõi đơn hàng Cashback.

### Nhu cầu 6

Quản lý số tiền Cashback.

### Nhu cầu 7

Rút tiền Cashback.

### Nhu cầu 8

Theo dõi giá sản phẩm.

### Nhu cầu 9

Nhận thông báo khi giá giảm.

### Nhu cầu 10

Sử dụng ứng dụng đơn giản và dễ hiểu.

---

# 5. Đối tượng người dùng

## 5.1. Đối tượng chính

CashGo hướng đến:

- Sinh viên.
- Người trẻ.
- Người thường xuyên mua sắm online.
- Người thường xuyên săn voucher.
- Người muốn tiết kiệm chi phí.
- Người sử dụng nhiều sàn thương mại điện tử.

## 5.2. Đặc điểm

Người dùng mục tiêu thường:

- Sử dụng smartphone.
- Có tài khoản trên các sàn thương mại điện tử.
- Quan tâm đến giá sản phẩm.
- Quan tâm đến voucher.
- Quan tâm đến khuyến mãi.
- Có nhu cầu mua hàng trực tuyến thường xuyên.

---

# 6. User Persona

## Persona 1 – Sinh viên

**Tên:** Nguyễn Minh Anh

**Tuổi:** 21

**Nghề nghiệp:** Sinh viên

### Hành vi

- Thường mua quần áo online.
- Mua mỹ phẩm online.
- Mua phụ kiện điện thoại.
- Thường sử dụng Shopee và TikTok Shop.
- Thường tìm voucher trước khi mua.

### Khó khăn

- Phải mở nhiều ứng dụng để so sánh.
- Không biết sàn nào thực sự rẻ hơn sau ưu đãi.
- Có thể bỏ lỡ chương trình Cashback.
- Khó theo dõi biến động giá.

### Mong muốn

- Tìm được nơi mua tiết kiệm.
- Nhận thêm Cashback.
- Theo dõi giá sản phẩm.
- Nhận thông báo khi sản phẩm giảm giá.

---

# 7. Giải pháp đề xuất

CashGo đề xuất một hệ thống gồm các chức năng chính sau.

## 7.1. Tìm kiếm sản phẩm

Người dùng nhập tên sản phẩm cần tìm.

Ví dụ:

**AirPods Pro 2**

CashGo hiển thị các kết quả phù hợp.

---

## 7.2. So sánh giá đa sàn

CashGo hiển thị thông tin sản phẩm từ nhiều nền tảng.

Ví dụ:

| Sàn | Giá | Cashback |
|---|---:|---:|
| Shopee | 4.990.000đ | 4% |
| Lazada | 4.850.000đ | 2% |
| TikTok Shop | 4.790.000đ | 5% |

Người dùng có thể lựa chọn phương án phù hợp.

---

## 7.3. Tạo Affiliate Link

Người dùng có thể copy link sản phẩm từ sàn thương mại điện tử và dán vào CashGo.

Ví dụ:

**Dán link sản phẩm**

↓

CashGo nhận diện sàn

↓

CashGo kiểm tra sản phẩm

↓

Hiển thị Cashback dự kiến

↓

Tạo Affiliate Link

↓

Người dùng nhấn **Mua ngay**

↓

Chuyển đến sàn thương mại điện tử

---

## 7.4. Theo dõi đơn hàng

CashGo cung cấp màn hình Orders.

Các trạng thái dự kiến:

- Đang chờ.
- Đã ghi nhận.
- Đã xác nhận.
- Đã hoàn tiền.
- Bị hủy.

---

## 7.5. Ví Cashback

Ví CashGo gồm:

### Cashback đang chờ

Tiền từ các đơn chưa được xác nhận hoàn toàn.

### Cashback khả dụng

Tiền đã được xác nhận và có thể rút.

Ngoài ra người dùng có thể xem:

- Lịch sử Cashback.
- Lịch sử rút tiền.
- Trạng thái giao dịch.

---

## 7.6. Theo dõi giá

Người dùng có thể nhấn:

**Theo dõi giá**

CashGo lưu sản phẩm vào danh sách theo dõi.

Người dùng có thể đặt:

**Thông báo khi giá dưới 4.500.000đ**

Khi đạt điều kiện, ứng dụng gửi thông báo cho người dùng.

---

# 8. Mục tiêu của dự án

## 8.1. Mục tiêu tổng quát

Xây dựng ứng dụng di động hỗ trợ người dùng mua sắm trực tuyến thuận tiện, minh bạch và tiết kiệm hơn.

## 8.2. Mục tiêu cụ thể

- Hỗ trợ tìm kiếm sản phẩm.
- Hỗ trợ so sánh giá đa sàn.
- Hiển thị Cashback.
- Hỗ trợ Affiliate Link.
- Quản lý đơn hàng.
- Quản lý Cashback.
- Hỗ trợ rút tiền.
- Theo dõi biến động giá.
- Gửi thông báo giảm giá.
- Xây dựng giao diện dễ sử dụng.

---

# 9. Phạm vi dự án

## 9.1. Phạm vi phiên bản đồ án

Trong phạm vi đồ án môn học, nhóm tập trung xây dựng:

- Giao diện ứng dụng Mobile.
- Luồng đăng nhập và đăng ký.
- Trang chủ.
- Tìm kiếm.
- So sánh sản phẩm.
- Dán link sản phẩm.
- Cashback.
- Quản lý đơn hàng.
- Ví.
- Rút tiền.
- Theo dõi giá.
- Hồ sơ người dùng.

Một số dữ liệu có thể được mô phỏng trong giai đoạn đầu để hoàn thiện luồng nghiệp vụ và giao diện.

## 9.2. Phạm vi phát triển tương lai

Nếu triển khai thực tế, hệ thống có thể mở rộng:

- Tích hợp API Affiliate chính thức.
- Đồng bộ dữ liệu sản phẩm.
- Đồng bộ trạng thái đơn hàng.
- Tích hợp hệ thống thanh toán/rút tiền.
- Hỗ trợ thêm nhiều nền tảng thương mại điện tử.
- Cá nhân hóa đề xuất sản phẩm.
- Phân tích hành vi mua sắm.

---

# 10. Yêu cầu chức năng

Hệ thống dự kiến có các yêu cầu chức năng sau:

**FR01:** Người dùng có thể đăng ký tài khoản.

**FR02:** Người dùng có thể đăng nhập.

**FR03:** Người dùng có thể tìm kiếm sản phẩm.

**FR04:** Người dùng có thể xem chi tiết sản phẩm.

**FR05:** Người dùng có thể so sánh giá sản phẩm.

**FR06:** Người dùng có thể dán link sản phẩm.

**FR07:** Hệ thống có thể nhận diện nền tảng từ link.

**FR08:** Hệ thống hiển thị Cashback dự kiến.

**FR09:** Hệ thống hỗ trợ tạo Affiliate Link.

**FR10:** Người dùng có thể theo dõi đơn hàng.

**FR11:** Người dùng có thể xem Cashback của đơn hàng.

**FR12:** Người dùng có thể xem ví Cashback.

**FR13:** Người dùng có thể yêu cầu rút tiền.

**FR14:** Người dùng có thể xem lịch sử giao dịch.

**FR15:** Người dùng có thể lưu sản phẩm yêu thích.

**FR16:** Người dùng có thể theo dõi giá sản phẩm.

**FR17:** Người dùng có thể đặt mức giá mong muốn.

**FR18:** Hệ thống có thể gửi thông báo.

**FR19:** Người dùng có thể quản lý thông tin cá nhân.

**FR20:** Người dùng có thể thay đổi ngôn ngữ.

---

# 11. Yêu cầu phi chức năng

## 11.1. Dễ sử dụng

Giao diện cần đơn giản, rõ ràng và phù hợp với người dùng phổ thông.

## 11.2. Hiệu năng

Các màn hình chính cần phản hồi nhanh và hạn chế thời gian chờ không cần thiết.

## 11.3. Bảo mật

Thông tin tài khoản và giao dịch của người dùng cần được bảo vệ.

## 11.4. Khả năng mở rộng

Hệ thống cần có khả năng bổ sung thêm sàn thương mại điện tử trong tương lai.

## 11.5. Đa ngôn ngữ

Kiến trúc ứng dụng nên hỗ trợ việc bổ sung nhiều ngôn ngữ.

## 11.6. Tính nhất quán

Giao diện cần sử dụng thống nhất:

- Màu sắc.
- Font chữ.
- Button.
- Icon.
- Khoảng cách.
- Component.

---

# 12. Tính thực tế của đề tài

CashGo giải quyết một nhu cầu thực tế trong mua sắm trực tuyến:

**Người dùng muốn mua sản phẩm với chi phí hợp lý và tiết kiệm thời gian tìm kiếm.**

Ứng dụng kết hợp các chức năng:

**Tìm kiếm → So sánh → Cashback → Theo dõi đơn → Quản lý tiền**

thành một quy trình thống nhất.

---

# 13. Khả năng thương mại hóa

CashGo có thể nghiên cứu mô hình doanh thu từ Affiliate Marketing.

Mô hình cơ bản:

**Người dùng**

↓

**CashGo Affiliate Link**

↓

**Sàn thương mại điện tử**

↓

**Phát sinh đơn hàng hợp lệ**

↓

**Hoa hồng Affiliate**

Sau đó một phần giá trị có thể được sử dụng làm Cashback cho người dùng, tùy theo điều kiện và chính sách của chương trình Affiliate tương ứng.

Ngoài Affiliate, trong tương lai có thể nghiên cứu:

- Quảng cáo.
- Vị trí sản phẩm tài trợ.
- Hợp tác với thương hiệu.
- Chương trình ưu đãi độc quyền.

---

# 14. Kết luận

CashGo được đề xuất nhằm giải quyết ba vấn đề chính:

1. Khó so sánh giá giữa nhiều sàn.
2. Người dùng chưa tận dụng tốt Cashback.
3. Khó theo dõi giá, đơn hàng và tiền hoàn trong cùng một nơi.

Giải pháp của CashGo là kết hợp:

**SO SÁNH GIÁ + CASHBACK + AFFILIATE + THEO DÕI ĐƠN + VÍ + THEO DÕI GIÁ**

trong một ứng dụng di động.

Mục tiêu cuối cùng là giúp người dùng:

**Tìm nhanh hơn – So sánh dễ hơn – Mua tiết kiệm hơn.**
