# PROJECT: GIẢI PHÁP TỰ ĐỘNG HOÁ CÔNG CỤ POWER BI CHO DOANH NGHIỆP
<img src="https://fox.ai.vn/wp-content/uploads/2024/07/Logo_Original-1.png" alt="Hình ảnh" width="30%" />

![Phiên_bản](https://img.shields.io/badge/Phiên_bản-1.0-brightgreen)
![Bản_quyền](https://img.shields.io/badge/Bản_quyền-FoxAI-blue)
![Tình trạng](https://img.shields.io/badge/Tình_trạng-Đã_ban_hành-darkorange)
![Hỗ trợ](https://img.shields.io/badge/Hỗ_trợ_247-Chatbot-purple)
![Hotline](https://img.shields.io/badge/Liên_hệ-info@foxai.vn-red)

# Nội dung

## MỤC TIÊU DỰ ÁN

Giải pháp tự động hóa công cụ Power BI cho doanh nghiệp nhằm tối ưu hóa quy trình phân tích dữ liệu và báo cáo thông qua việc tự động hóa việc thu thập, xử lý và trình bày dữ liệu. Mục tiêu nhằm giúp doanh nghiệp tiết kiệm thời gian và nguồn lực trong việc thu thập dữ liệu từ nhiều nguồn khác nhau, tự động cập nhật và tạo các báo cáo trực quan, từ đó tăng cường hiệu quả công việc và khả năng ra quyết định nhanh chóng. Với việc tích hợp các nguồn dữ liệu và công cụ tự động, doanh nghiệp sẽ tiết kiệm thời gian phân tích và nâng cao độ chính xác trong các báo cáo và dự báo, giúp đội ngũ quản lý đưa ra quyết định chính xác hơn và kịp thời hơn. Bên cạnh đó, giải pháp này còn hỗ trợ việc triển khai các quy trình kiểm tra chất lượng dữ liệu và báo cáo tự động, giúp đảm bảo tính toàn vẹn của dữ liệu và giảm thiểu rủi ro sai sót.

## Gateway

### Gateway là gì?

**Gateway** là bộ chuyển đổi giao thức giúp kết nối hai mạng có giao thức truyền tin khác nhau, cho phép các mạng này giao tiếp với nhau. Thiết bị **Gateway** giống như một cửa ngõ trong mạng, nơi tất cả dữ liệu đều phải đi qua trước khi chuyển đến bộ định tuyến (router) hoặc đến các thiết bị khác trong mạng.

Trong một mạng **IP** duy nhất, hầu hết lưu lượng chỉ truyền giữa các nút trong cùng phân đoạn mạng cục bộ (**LAN**), và những dữ liệu này không cần đi qua **Gateway**. Tuy nhiên, trong trường hợp dữ liệu cần vượt qua các phân đoạn mạng khác nhau, hoặc giữa các mạng có giao thức khác nhau, **Gateway** sẽ đóng vai trò quan trọng trong việc định tuyến và chuyển giao thông tin.

### Các khái niệm liên quan đến Gateway:
1. **Gateway Network**: Mạng nơi thiết bị Gateway kết nối các hệ thống có giao thức khác nhau.
2. **Default Gateway**: Được sử dụng khi một thiết bị trong mạng không biết cách định tuyến đến một địa chỉ ngoài phạm vi mạng cục bộ của nó. Khi đó, các gói dữ liệu sẽ được chuyển đến Default Gateway để tiếp tục tìm đường ra ngoài.

### Các vai trò của Gateway:
- **Chuyển giao thức**: **Gateway** giúp chuyển đổi giữa các giao thức khác nhau, ví dụ, từ mạng LAN sang mạng WAN, hoặc giữa các hệ thống sử dụng giao thức khác nhau như TCP/IP và SNA.
- **Chuyển hướng dữ liệu**: Làm nhiệm vụ chuyển tiếp gói dữ liệu giữa các mạng có cấu trúc khác nhau hoặc các mạng không tương thích với nhau.
- **Bảo mật mạng**: **Gateway** có thể thực hiện các chức năng bảo mật, kiểm tra các gói dữ liệu trước khi cho phép chúng tiếp cận mạng nội bộ.

### Ví dụ về sử dụng Gateway:
- Trong các môi trường doanh nghiệp, **Default Gateway** thường được thiết lập trên router hoặc firewall, giúp tất cả các thiết bị trong mạng LAN có thể truy cập internet.
- Một **Gateway** cũng có thể được sử dụng để kết nối mạng IPv6 và IPv4, khi các mạng này không thể trực tiếp giao tiếp với nhau.

## Cách tích hợp Gateway với Power BI

Power BI Gateway là công cụ giúp kết nối và truyền tải dữ liệu từ các nguồn dữ liệu **on-premises** (dữ liệu trong hệ thống nội bộ) lên **Power BI** (trực tuyến). Đây là một phần không thể thiếu khi bạn cần cập nhật và làm mới dữ liệu từ các nguồn như SQL Server, Oracle, SAP, hoặc các nguồn dữ liệu nội bộ khác.

Dưới đây là các bước để tích hợp **Gateway** với **Power BI**:

### 1. Cài đặt Power BI Gateway

Để tích hợp **Gateway** vào **Power BI**, bạn cần cài đặt **Power BI Gateway** trên máy tính hoặc máy chủ của mình.

Các bước cài đặt:
- **Tải Gateway**: Tải **Power BI Gateway** từ trang chính thức của Microsoft: [Power BI Gateway](https://powerbi.microsoft.com/en-us/gateway/)
- **Cài đặt**: Sau khi tải về, mở tệp cài đặt và làm theo hướng dẫn trên màn hình.
- **Đăng nhập**: Bạn sẽ cần đăng nhập bằng tài khoản **Power BI** hoặc **Office 365** để liên kết **Gateway** với tài khoản của bạn.

### 2. Chọn Loại Gateway (Personal vs Enterprise)

Có hai loại **Power BI Gateway**:
- **Personal Gateway**: Dành cho người dùng cá nhân hoặc khi chỉ cần kết nối với một nguồn dữ liệu duy nhất.
- **Enterprise Gateway**: Dành cho các tổ chức lớn, hỗ trợ nhiều người dùng và nhiều nguồn dữ liệu, cũng như tính năng bảo mật và quản lý quyền truy cập cao hơn.

### 3. Đăng ký Gateway trong Power BI Service

Sau khi đã cài đặt và cấu hình **Gateway**, bạn cần đăng ký **Gateway** trong **Power BI Service**.

Các bước đăng ký:
1. **Đăng nhập** vào **Power BI Service** ([link](https://app.powerbi.com)).
2. **Chọn "Settings"** (Cài đặt) ở góc trên bên phải màn hình.
3. **Chọn "Gateways"** trong menu.
4. **Chọn "Add data source"** và chọn **"Power BI Gateway"** để kết nối với nguồn dữ liệu nội bộ.
5. **Chọn Gateway** vừa cài đặt và cấu hình từ danh sách **Gateways**.

### 4. Cấu hình và Kết nối Nguồn Dữ liệu

Sau khi **Gateway** đã được kết nối với **Power BI**, cần cấu hình các nguồn dữ liệu mà bạn muốn sử dụng trong **Power BI**.

Các bước cấu hình nguồn dữ liệu:
1. Trong **Power BI Service**, vào phần **"Settings" > "Data sources"**.
2. **Chọn "Add data source"** và nhập thông tin về nguồn dữ liệu (ví dụ: SQL Server, Oracle, Excel, v.v.).
3. **Cung cấp thông tin kết nối** như tên máy chủ, tên cơ sở dữ liệu và các thông tin bảo mật.
4. **Chọn Authentication Method** (Phương thức xác thực): Chọn **Windows**, **Basic** hoặc **OAuth** tùy thuộc vào loại nguồn dữ liệu.
5. **Lưu lại cấu hình**.

### 5. Làm mới Dữ liệu tự động

Sau khi cấu hình xong, có thể lên lịch để **Power BI** tự động làm mới dữ liệu từ các nguồn nội bộ thông qua **Gateway**.

Các bước cấu hình làm mới tự động:
1. **Vào Power BI Service** và chọn báo cáo hoặc dataset muốn làm mới tự động.
2. **Chọn "Schedule Refresh"**.
3. **Chọn Gateway** đã cấu hình và thiết lập thời gian làm mới dữ liệu theo lịch trình.
4. **Lưu cấu hình**.

### 6. Giám sát và Quản lý Gateway

**Power BI** cung cấp công cụ giám sát để bạn theo dõi trạng thái của **Gateway**. Kiểm tra xem liệu **Gateway** có đang hoạt động bình thường hay không, cũng như kiểm tra lịch sử làm mới dữ liệu và bất kỳ lỗi nào phát sinh trong quá trình truyền tải dữ liệu.

# ETL Dữ liệu trong Power BI

ETL (Extract, Transform, Load) là một quy trình quan trọng trong việc xử lý và tích hợp dữ liệu vào trong **Power BI**. Quy trình này giúp bạn chuyển dữ liệu từ nhiều nguồn khác nhau vào **Power BI** để phân tích và trực quan hóa. Dưới đây là các bước cơ bản trong quy trình **ETL** khi sử dụng **Power BI**.

### Lợi ích khi sử dụng Power BI Gateway
- **Tự động làm mới dữ liệu**: Dữ liệu được cập nhật một cách tự động từ các nguồn dữ liệu nội bộ mà không cần can thiệp thủ công.
- **Bảo mật**: Dữ liệu không phải di chuyển ra ngoài hệ thống nội bộ của doanh nghiệp, giúp bảo vệ thông tin nhạy cảm.
- **Hỗ trợ nhiều nguồn dữ liệu**: **Gateway** hỗ trợ kết nối với nhiều nguồn dữ liệu khác nhau như **SQL Server**, **SAP**, **Oracle**, và các tập tin **Excel**, **CSV**.
- **Tính liên tục**: Đảm bảo khả năng truy cập dữ liệu liên tục giữa **Power BI** và các nguồn dữ liệu nội bộ.
# ETL

ETL (Extract, Transform, Load) là một quy trình quan trọng trong việc xử lý và tích hợp dữ liệu vào trong **Power BI**. Quy trình này giúp chuyển dữ liệu từ nhiều nguồn khác nhau vào **Power BI** để phân tích và trực quan hóa. Dưới đây là các bước cơ bản trong quy trình **ETL** khi sử dụng **Power BI**.

# Extract
### 1. Kết nối với SQL Server
- Mở Power BI Desktop.
- Chọn **Home** > **Get Data** > **SQL Server**.
- Nhập thông tin máy chủ và cơ sở dữ liệu SQL Server của khách hàng.
- Chọn kiểu kết nối:
  - **Import**: Dữ liệu sẽ được tải về Power BI.
  - **DirectQuery**: Dữ liệu sẽ không được tải về mà sẽ được truy vấn trực tiếp từ SQL Server mỗi lần sử dụng.

### 2. Chọn bảng và truy vấn dữ liệu
- Sau khi kết nối thành công, Power BI sẽ hiển thị danh sách các bảng dữ liệu từ SQL Server.
- Chọn các bảng cần dùng để sao chép dữ liệu.
- Sử dụng **Query Editor** để lọc và chuẩn hóa dữ liệu.

### 3. Chỉnh sửa và lọc dữ liệu
- Tại **Query Editor**, thực hiện các thao tác làm sạch và biến đổi dữ liệu như:
  - **Loại bỏ cột không cần thiết**.
  - **Lọc dữ liệu**: Chọn các bản ghi cần thiết (theo ngày, loại sản phẩm, v.v.).
  - **Chuyển đổi kiểu dữ liệu**: Đảm bảo dữ liệu có đúng kiểu (date, number, text, v.v.).
  - **Gộp các bảng dữ liệu**: Kết hợp các bảng nếu cần thiết.

### 4. Sao chép dữ liệu về cơ sở dữ liệu của mình
- Sau khi dữ liệu đã được chuẩn bị và làm sạch, hãy sao chép dữ liệu vào cơ sở dữ liệu của mình.
  - **Tạo một bảng mới** trong cơ sở dữ liệu của mình hoặc **sử dụng công cụ ETL** (Extract, Transform, Load) để tự động sao chép dữ liệu vào cơ sở dữ liệu.
  - Nếu cần sao chép thủ công, hãy xuất dữ liệu dưới dạng **.csv** hoặc **.xlsx** và tải lên cơ sở dữ liệu của mình.

### 5. Lưu và làm mới dữ liệu
- Sau khi truy vấn dữ liệu và sao chép dữ liệu thành công, lưu kết nối và truy vấn trong Power BI.
- Để đảm bảo dữ liệu luôn được cập nhật, thiết lập lịch làm mới trong Power BI Service.
  - Vào **Power BI Service** > **Dataset settings** > **Schedule Refresh**.
  - Chọn thời gian và tần suất làm mới dữ liệu từ SQL Server.

## Transform

### 1. Mở Power Query Editor
- Trong Power BI Desktop, sau khi dữ liệu được tải về, mở **Power Query Editor** để thực hiện các bước biến đổi dữ liệu.
- Chọn **Transform Data** từ màn hình chính của Power BI Desktop.

### 2. Làm sạch và chuẩn hóa dữ liệu
a. Loại bỏ dữ liệu không cần thiết
  - Loại bỏ các cột không cần thiết.
  - Để loại bỏ cột, chọn cột và nhấp chuột phải, sau đó chọn **Remove**.

b. Lọc dữ liệu
  - Nếu chỉ muốn giữ lại các dữ liệu có giá trị nhất định (ví dụ: lọc theo ngày, loại sản phẩm, v.v.), hãy sử dụng chức năng **Filter**.
  - Chọn cột cần lọc.
  - Chọn mũi tên ở đầu cột và thiết lập bộ lọc.

c. Xử lý dữ liệu thiếu
  - Kiểm tra và xử lý các giá trị **null** hoặc **empty**.
  - Hãy thay thế giá trị null bằng một giá trị mặc định hoặc loại bỏ các bản ghi thiếu thông tin quan trọng.

## 3. Chuyển đổi kiểu dữ liệu
  - Đảm bảo rằng tất cả các cột dữ liệu có kiểu dữ liệu chính xác (ví dụ: ngày tháng, số, văn bản).
  - Để thay đổi kiểu dữ liệu, chọn cột, sau đó chọn **Data Type** trong menu **Transform** và chọn kiểu dữ liệu phù hợp.

## 4. Thực hiện các phép toán và tính toán
  - Thêm các cột tính toán (nếu cần), như tổng, trung bình, hoặc tỷ lệ phần trăm.
  - Ví dụ: để tính tổng, vào **Add Column** và chọn **Custom Column**, sau đó nhập công thức.
  - Tạo các chỉ số và KPI phục vụ cho phân tích sau này.

### 5. Gộp hoặc phân tách dữ liệu
a. Gộp cột
- Nếu cần, hãy gộp nhiều cột thành một cột duy nhất (ví dụ: gộp cột họ và tên).
  - Chọn các cột cần gộp, rồi vào **Transform** > **Merge Columns**.

b. Phân tách cột
- Nếu muốn tách một cột thành nhiều cột (ví dụ: tách địa chỉ thành đường, quận, thành phố, v.v.), chọn cột cần phân tách và sử dụng **Split Column**.

### 6. Tạo các bảng kết nối (Joins)
  - Nếu dữ liệu đến từ nhiều bảng khác nhau và bạn muốn kết hợp chúng, bạn có thể thực hiện các phép toán **join**.
  - Chọn **Merge Queries** và kết nối các bảng dữ liệu với nhau dựa trên các khóa chung (ví dụ: ID khách hàng).

## 7. Loại bỏ các giá trị trùng lặp
  - Để loại bỏ các giá trị trùng lặp trong bảng, bạn có thể sử dụng **Remove Duplicates** trong Power Query Editor.
  - Chọn cột bạn muốn kiểm tra trùng lặp, rồi vào **Remove duplicates** trong menu **Transform**.

## 8. Lưu các thay đổi
  - Sau khi hoàn tất các bước biến đổi dữ liệu, chọn **Close & Apply** để lưu các thay đổi và quay lại Power BI Desktop.

## 9. Kiểm tra lại dữ liệu
  - Kiểm tra lại dữ liệu đã biến đổi để đảm bảo mọi thông tin đã được xử lý đúng cách, không có lỗi hay sai sót trong các phép biến đổi.

## Load

### 1. Chọn chế độ Load
- Sau khi hoàn tất việc biến đổi dữ liệu trong Power Query Editor, bạn cần tải dữ liệu vào Power BI Desktop.
- Chọn **Close & Apply** từ Power Query Editor để tải dữ liệu vào Power BI.

### 2. Chọn nguồn dữ liệu
- Nếu dữ liệu đã được biến đổi thành công, bạn có thể kiểm tra lại nguồn dữ liệu trong **Fields** pane ở Power BI Desktop.
- Chọn **Data** hoặc **Model** để kiểm tra các bảng và mối quan hệ giữa các bảng sau khi dữ liệu đã được Load.

### 3. Đảm bảo bảng và mối quan hệ
- Kiểm tra các bảng đã được tải lên để đảm bảo chúng có đầy đủ dữ liệu cần thiết.
- Nếu cần, thiết lập các mối quan hệ giữa các bảng để đảm bảo tính toàn vẹn dữ liệu và khả năng phân tích.

### 4. Xác nhận dữ liệu đã được tải đúng
- Kiểm tra dữ liệu trong **Data view** và **Report view** để đảm bảo dữ liệu được hiển thị chính xác.
- Nếu dữ liệu có vấn đề, quay lại Power Query Editor để sửa chữa và làm lại quá trình **Transform** và **Load**.

### 5. Thiết lập làm mới dữ liệu
- Nếu bạn muốn cập nhật dữ liệu theo lịch trình, bạn cần thiết lập tính năng làm mới dữ liệu tự động.
- Truy cập vào **Power BI Service** (trực tuyến) và đăng ký lịch làm mới dữ liệu cho dataset của bạn.
  - Chọn **Settings** > **Datasets** > **Scheduled Refresh**.
  - Cấu hình các cài đặt làm mới dữ liệu theo lịch trình bạn mong muốn.

### 6. Giám sát quá trình Load dữ liệu
- Kiểm tra trạng thái Load dữ liệu trong Power BI Service để đảm bảo dữ liệu được tải và cập nhật chính xác.

## Tạo biểu đồ


