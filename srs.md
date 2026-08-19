B1; xác định bussines contact( ngữ cảnh nghiệp vụ) và bussines problem 
Gợi ý:
Khách hàng muốn giải quyết vấn đề gì?
Vì sao hệ thống hiện tại k thể đáp ứng
Mục tiêu kinh doanh của họ là gì?
Ai sẽ sử dụng hệ thống này?
Giá thị hệ thống này tạo ra so với hệ thống cũ như thế nào?

# B1. Xác định Business Context và Business Problem

## 1. Business Context – Bối cảnh nghiệp vụ

Công ty ABC đang cung cấp dịch vụ đặt xe trực tuyến thông qua tổng đài và một ứng dụng đơn giản. Tuy nhiên, doanh nghiệp đang có nhu cầu xây dựng **CAB System** mới để tự động hóa và quản lý tập trung toàn bộ quy trình đặt xe, từ khi khách hàng yêu cầu xe, tìm và phân công tài xế, thực hiện chuyến, thanh toán đến đánh giá sau chuyến.

**Đối tượng sử dụng chính:**
- Khách hàng
- Tài xế
- Nhân viên vận hành

Hệ thống cũng cần tích hợp với **cổng thanh toán điện tử và dịch vụ thông báo** bên ngoài.

## 2. Business Problem – Vấn đề nghiệp vụ

Hệ thống hiện tại tồn tại các vấn đề:

- Phân công tài xế còn **thủ công**, mất thời gian và khó tối ưu.
- Khách hàng **khó theo dõi trạng thái chuyến đi**.
- Thanh toán và giao dịch **chưa được quản lý tập trung**.
- Nhân viên vận hành gặp khó khăn trong việc **quản lý khách hàng, tài xế, chuyến đi và xử lý sự cố**.
- Khó tổng hợp dữ liệu để theo dõi **doanh thu, số chuyến, tỷ lệ hoàn thành và tỷ lệ hủy**.
- Hệ thống **khó mở rộng** khi số lượng khách hàng và tài xế tăng.

## 3. Mục tiêu kinh doanh

- Tự động hóa quy trình đặt xe và phân công tài xế.
- Nâng cao trải nghiệm và khả năng theo dõi chuyến của khách hàng.
- Quản lý tập trung chuyến đi, thanh toán và dữ liệu vận hành.
- Giảm thao tác thủ công và nâng cao hiệu quả của nhân viên.
- Xây dựng hệ thống **ổn định, bảo mật và có khả năng mở rộng**.

## 4. Giá trị của hệ thống mới

So với hệ thống cũ, CAB System giúp **tự động hóa việc tìm tài xế, theo dõi chuyến, thanh toán và thông báo**, đồng thời cung cấp dữ liệu phục vụ quản lý và báo cáo.

Hệ thống giúp **giảm thời gian xử lý, nâng cao chất lượng dịch vụ, tăng hiệu quả vận hành và tạo nền tảng để doanh nghiệp mở rộng trong tương lai**.

# B2. Xác định các bên liên quan (Stakeholders)
1.	Những stalkholder - 	Vai trò là gì 
2.	Vẽ ma trận stalkholder matrick
## 1. Những stalkholder - 	Vai trò là gì 

| Stakeholder | Vai trò |
|---|---|
| Khách hàng | Đăng ký, đặt xe, theo dõi chuyến, thanh toán và đánh giá tài xế. |
| Tài xế | Nhận chuyến, chấp nhận/từ chối chuyến, thực hiện chuyến và cập nhật trạng thái. |
| Nhân viên vận hành | Quản lý khách hàng, tài xế, phương tiện, chuyến đi và xử lý sự cố. |
| Ban giám đốc | Xác định mục tiêu kinh doanh, theo dõi doanh thu và hiệu quả hoạt động. |
| Bộ phận kế toán/tài chính | Theo dõi giao dịch, thanh toán và doanh thu. |
| Nhà cung cấp thanh toán | Xử lý các giao dịch thanh toán điện tử. |
| Nhà cung cấp thông báo | Cung cấp dịch vụ gửi thông báo như SMS, Email hoặc các kênh khác. |
| Business Analyst (BA) | Thu thập, phân tích và làm rõ yêu cầu của các bên liên quan. |
| Đội phát triển hệ thống | Thiết kế, xây dựng, kiểm thử và triển khai hệ thống. |

2.	Vẽ ma trận stalkholder matrick
## 3. Stakeholder Matrix

**Ma trận Stakeholder theo mức độ ảnh hưởng (Power) và mức độ quan tâm (Interest):**

### MA TRẬN STAKEHOLDER – POWER / INTEREST

|                         | **MỨC ĐỘ QUAN TÂM THẤP** | **MỨC ĐỘ QUAN TÂM CAO** |
|-------------------------|---------------------------|---------------------------|
| **ẢNH HƯỞNG CAO**       | 🟡 **KEEP SATISFIED**     | 🔴 **MANAGE CLOSELY**     |
|                         | • Nhà cung cấp thanh toán | • Ban lãnh đạo            |
|                         | • Nhà cung cấp thông báo  | • Nhân viên vận hành      |
| **ẢNH HƯỞNG THẤP**      | ⚪ **MONITOR**             | 🟢 **KEEP INFORMED**      |
|                         | • BA / Đội phát triển     | • Khách hàng               |
|                         |                           | • Tài xế                   |

### Chiến lược quản lý
- 🔴 **Manage Closely:** Thường xuyên trao đổi và tham gia quyết định.
- 🟡 **Keep Satisfied:** Đảm bảo nhu cầu và duy trì sự hài lòng.
- 🟢 **Keep Informed:** Cập nhật thông tin thường xuyên.
- ⚪ **Monitor:** Theo dõi và cập nhật khi cần.
### Sơ đồ Stakeholder Matrix

                    MỨC ĐỘ ẢNH HƯỞNG
                            CAO
                             │
          Keep Satisfied     │      Manage Closely
                             │
   Nhà cung cấp thanh toán   │   Ban lãnh đạo
   Nhà cung cấp thông báo    │   Nhân viên vận hành
                             │
       ──────────────────────┼──────────────────────
                             │
          Monitor            │      Keep Informed
                             │
   BA / Đội phát triển       │   Khách hàng
                             │   Tài xế
                             │
                            THẤP
                     MỨC ĐỘ QUAN TÂM
                       THẤP → CAO

# B3. BUSINESS GOALS

## BJ01 – HỖ TRỢ THANH TOÁN

Hỗ trợ nhiều hình thức thanh toán nhằm đáp ứng nhu cầu thanh toán của khách hàng.

## BJ02 – GIẢM THỜI GIAN TÌM TÀI XẾ

Rút ngắn thời gian từ khi khách hàng đặt xe đến khi tìm được tài xế phù hợp.

## BJ03 – NÂNG CAO TRẢI NGHIỆM KHÁCH HÀNG

Giúp khách hàng dễ dàng đặt xe, theo dõi chuyến đi và nắm được thông tin chuyến đi.

## BJ04 – NÂNG CAO HIỆU QUẢ HOẠT ĐỘNG TÀI XẾ

Giúp doanh nghiệp quản lý trạng thái, thông tin và hoạt động của tài xế hiệu quả hơn.

## BJ05 – GIẢM TỶ LỆ CHUYẾN ĐI BỊ HỦY

Hạn chế các trường hợp chuyến đi bị hủy do không tìm được tài xế hoặc tài xế không phản hồi.

## BJ06 – NÂNG CAO KHẢ NĂNG THEO DÕI CHUYẾN ĐI

Cho phép doanh nghiệp và khách hàng nắm được trạng thái của chuyến đi trong quá trình thực hiện.

## BJ07 – TẬP TRUNG QUẢN LÝ DỮ LIỆU

Tập trung thông tin khách hàng, tài xế, phương tiện, chuyến đi và giao dịch trên một hệ thống.

## BJ08 – NÂNG CAO HIỆU QUẢ QUẢN LÝ VẬN HÀNH

Giúp nhân viên vận hành theo dõi và xử lý các chuyến đi, tài xế và sự cố hiệu quả hơn.

## BJ09 – NÂNG CAO ĐỘ TIN CẬY CỦA HỆ THỐNG

Đảm bảo các chức năng quan trọng của hệ thống tiếp tục hoạt động khi một thành phần gặp sự cố.

## BJ10 – ĐẢM BẢO AN TOÀN THÔNG TIN

Bảo vệ thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch của người dùng.

## BJ11 – NÂNG CAO KHẢ NĂNG MỞ RỘNG

Cho phép hệ thống đáp ứng số lượng khách hàng và tài xế ngày càng tăng.

## BJ12 – HỖ TRỢ PHÁT TRIỂN DỊCH VỤ MỚI

Tạo khả năng bổ sung các loại dịch vụ và phương thức thanh toán mới trong tương lai.

## BJ13 – NÂNG CAO HIỆU QUẢ THANH TOÁN

Giảm các vấn đề phát sinh trong quá trình thanh toán và hỗ trợ xử lý khi giao dịch thất bại.

## BJ14 – CẢI THIỆN CHẤT LƯỢNG DỊCH VỤ

Thu thập đánh giá sau chuyến đi để doanh nghiệp có cơ sở theo dõi và cải thiện chất lượng dịch vụ.

## BJ15 – HỖ TRỢ RA QUYẾT ĐỊNH KINH DOANH

Cung cấp dữ liệu và báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế.
#B3: BUSINESS GOALS
## BJ01 – Tăng tính linh hoạt và thuận tiện trong thanh toán:
* Hỗ trợ thanh toán bằng tiền mặt.
* Hỗ trợ thanh toán online/chuyển khoản.
--
## BJ02 – Giảm thời gian chờ xe của khách hàng:
* Tìm tài xế tự động.
* Ưu tiên tài xế phù hợp và gần khách hàng.
---
## BJ03 – Nâng cao trải nghiệm đặt xe của khách hàng:
* Dễ dàng tạo yêu cầu đặt xe.
* Biết được trạng thái của yêu cầu đặt xe.
* Biết thông tin tài xế khi chuyến xe được xác nhận.
* Theo dõi được tình trạng chuyến đi.
---
## BJ04 – Nâng cao hiệu quả quản lý và vận hành:
* Theo dõi được các chuyến xe đang diễn ra.
* Nắm được tình trạng hoạt động của tài xế.
* Hỗ trợ xử lý các trường hợp chuyến xe gặp vấn đề.
* Tra cứu được thông tin các giao dịch và chuyến đi.
---
## BJ05 – Nâng cao hiệu quả hoạt động của tài xế
* Nắm được trạng thái hoạt động của tài xế.
* Phân công chuyến xe cho tài xế phù hợp.
* Ưu tiên tài xế có vị trí thuận lợi cho khách hàng.
* Hạn chế thời gian tài xế phải chờ nhận chuyến.
---
## BJ06 – Nâng cao khả năng theo dõi và minh bạch thông tin chuyến đi
* Biết tài xế nào đang thực hiện chuyến.
* Biết thời gian dự kiến tài xế đến.
* Biết trạng thái hiện tại của chuyến xe.
* Tra cứu được lịch sử chuyến đi.
---
## BJ07 – Nâng cao độ tin cậy của dịch vụ đặt xe
* Không làm gián đoạn toàn bộ dịch vụ khi thanh toán gặp lỗi.
* Không làm gián đoạn toàn bộ dịch vụ khi thông báo gặp lỗi.
* Có phương án xử lý khi không tìm được tài xế.
* Có phương án xử lý khi tài xế không phản hồi hoặc từ chối chuyến.
---
## BJ08 – Nâng cao chất lượng thanh toán
* Hỗ trợ nhiều phương thức thanh toán.
* Thông báo rõ kết quả thanh toán.
* Có khả năng xử lý lại khi thanh toán điện tử thất bại.
* Bảo vệ thông tin thanh toán nhạy cảm của khách hàng.
---
## BJ09 – Nâng cao chất lượng dịch vụ thông qua phản hồi khách hàng
* Đánh giá tài xế sau khi hoàn thành chuyến.
* Ghi nhận kết quả đánh giá của khách hàng.
* Sử dụng thông tin đánh giá để theo dõi chất lượng tài xế.
---
## BJ10 – Nâng cao khả năng mở rộng của hệ thống
* Hệ thống có thể phục vụ số lượng lớn khách hàng và tài xế.
* Có thể mở rộng từng thành phần khi nhu cầu tăng.
* Có thể bổ sung các dịch vụ mới trong tương lai.
---

## BJ11 – Tăng khả năng phát triển và thay đổi hệ thống
* Có thể thêm phương thức thanh toán mới.
* Có thể thêm nhà cung cấp thông báo mới.
* Có thể bổ sung các loại dịch vụ mới.
* Có thể thay đổi một số thành phần kỹ thuật khi cần thiết.
---
## BJ12 – Nâng cao khả năng kiểm soát và bảo mật thông tin
* Bảo vệ thông tin cá nhân của khách hàng và tài xế.
* Bảo vệ dữ liệu vị trí.
* Bảo vệ dữ liệu giao dịch.
* Kiểm soát quyền truy cập của nhân viên.
* Lưu lại các thao tác quan trọng để phục vụ kiểm tra.

#B4: Xác định PHẠM VI SCOPE: 
1. Quản lý tài khoản người dùng
- Đăng ký và đăng nhập tài khoản khách hàng.
- Quản lý thông tin cá nhân khách hàng.
- Quản lý tài khoản và hồ sơ tài xế.
- Quản lý quyền truy cập của nhân viên vận hành và quản trị viên.
2. Quản lý tài xế và phương tiện
- Quản lý thông tin tài xế.
- Quản lý thông tin phương tiện.
- Theo dõi trạng thái hoạt động của tài xế.
- Theo dõi vị trí của tài xế.
- Quản lý khả năng nhận chuyến của tài xế.
3. Đặt xe và phân công tài xế
- Nhập điểm đón và điểm đến.
- Lựa chọn loại xe.
- Tiếp nhận yêu cầu đặt xe.
- Tìm kiếm tài xế phù hợp.
- Ưu tiên tài xế dựa trên vị trí, trạng thái và tiêu chí vận hành.
- Tiếp tục tìm tài xế khác khi tài xế từ chối hoặc không phản hồi.
- Thông báo khi không tìm được tài xế.
4. Quản lý chuyến đi
- Theo dõi trạng thái chuyến đi.
- Cập nhật trạng thái chuyến.
- Theo dõi thời gian dự kiến tài xế đến.
- Quản lý quá trình thực hiện chuyến.
- Xử lý các trường hợp chuyến bị hủy hoặc gặp sự cố.
- Lưu lịch sử chuyến đi.
5. Tính cước và thanh toán
- Xác định số tiền khách hàng phải trả.
- Hỗ trợ thanh toán bằng tiền mặt.
- Hỗ trợ thanh toán điện tử/chuyển khoản.
- Tích hợp với nhà cung cấp thanh toán bên ngoài.
- Xử lý kết quả thanh toán.
- Xử lý trường hợp thanh toán thất bại.
- Lưu lịch sử giao dịch.
- Không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.
6. Thông báo
- Thông báo cho khách hàng về trạng thái đặt xe.
- Thông báo khi tài xế nhận chuyến.
- Thông báo khi tài xế đến điểm đón.
- Thông báo khi chuyến hoàn thành.
- Thông báo kết quả thanh toán.
- Thông báo cho tài xế về chuyến mới và các thay đổi liên quan đến chuyến đi.
- Hỗ trợ mở rộng thêm các kênh thông báo trong tương lai.
7. Đánh giá và phản hồi
- Khách hàng đánh giá tài xế sau khi hoàn thành chuyến.
- Lưu thông tin đánh giá.
- Theo dõi chất lượng phục vụ của tài xế.
8. Quản trị và vận hành
- Quản lý khách hàng.
- Quản lý tài xế.
- Quản lý phương tiện.
- Theo dõi các chuyến đang diễn ra.
- Kiểm tra trạng thái tài xế.
- Hỗ trợ xử lý các chuyến bị lỗi.
- Tra cứu lịch sử giao dịch.
- Phân quyền các thao tác quản trị.
9. Báo cáo
- Báo cáo số lượng chuyến.
- Báo cáo doanh thu.
- Báo cáo tỷ lệ chuyến hoàn thành.
- Báo cáo tỷ lệ hủy chuyến.
- Báo cáo hiệu quả hoạt động của tài xế.
10. Bảo mật và kiểm soát
- Xác thực người dùng.
- Phân quyền truy cập.
- Bảo vệ thông tin cá nhân.
- Bảo vệ dữ liệu phương tiện.
- Bảo vệ dữ liệu vị trí.
- Bảo vệ dữ liệu giao dịch.
- Lưu vết các thao tác quan trọng.

# B5. Business Requirements:

| Mã | Tên | Diễn giải |
|---|---|---|
| BR01 | Đặt chuyến xe | Hệ thống cho phép khách hàng đặt chuyến bằng cách xác định vị trí hiện tại, điểm đón, điểm đến và lựa chọn loại xe phù hợp. |
| BR02 | Tìm và phân công tài xế | Hệ thống cho phép tìm và lựa chọn tài xế phù hợp với chuyến đi dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| BR03 | Theo dõi chuyến đi | Hệ thống cho phép khách hàng theo dõi trạng thái chuyến đi trong suốt quá trình di chuyển. |
| BR04 | Quản lý tài xế | Hệ thống cho phép doanh nghiệp quản lý thông tin tài xế, phương tiện và trạng thái hoạt động của tài xế. |
| BR05 | Quản lý chuyến đi | Hệ thống cho phép quản lý và cập nhật trạng thái chuyến đi từ khi tạo yêu cầu đến khi hoàn thành hoặc hủy chuyến. |
| BR06 | Tính cước | Hệ thống cho phép xác định số tiền khách hàng phải trả dựa trên loại dịch vụ và thông tin chuyến đi. |
| BR07 | Thanh toán | Hệ thống cho phép khách hàng thanh toán bằng tiền mặt hoặc phương thức thanh toán điện tử thông qua nhà cung cấp thanh toán bên ngoài. |
| BR08 | Thông báo | Hệ thống cung cấp thông báo cho khách hàng và tài xế về các sự kiện quan trọng trong quá trình đặt và thực hiện chuyến. |
| BR09 | Đánh giá tài xế | Hệ thống cho phép khách hàng đánh giá tài xế sau khi chuyến đi hoàn thành. |
| BR10 | Quản lý vận hành | Hệ thống cung cấp giao diện để nhân viên vận hành quản lý khách hàng, tài xế, phương tiện, chuyến đi và giao dịch. |
| BR11 | Báo cáo hoạt động | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |
| BR12 | Bảo mật và phân quyền | Hệ thống đảm bảo người dùng được xác thực, phân quyền phù hợp và bảo vệ thông tin cá nhân, dữ liệu vị trí và giao dịch. |

#B6.  Business Process:


