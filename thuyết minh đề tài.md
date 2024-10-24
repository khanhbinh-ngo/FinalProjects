# **ĐỀ CƯƠNG NGHIÊN CỨU - ĐỒ ÁN CHUYÊN NGÀNH VÀ KHÓA LUẬN TỐT NGHIỆP**
I. Đồ án chuyên ngành
1. Tên đồ án
> Triển khai và giám sát các ứng dụng microservice sử dụng k8s và grafana
2. Thời gian thực hiện: 3 tháng
3. Nội dung chính
3.1. mục tiêu: 
- tự động hóa quy trình triển khai 
- nghiên cứu quy trình giám sát hệ thống
3.2. nội dung chính
- tổn quan và k8s và ansible
- vai trò của k8s và ansible trong việc phát triển phần mềm
- triển khai các microservice trên k8s
- giám sát các microservice 
- tự động hóa quy trình quản lý và giám sát: sử dụng ansible để có thể tự động scale microservice, nâng cấp hoặc rollback tới các phiên bản mới
- tối ưu hóa hiệu năng của hệ thống
vậy, qua đồ án ta có thể triển khai một hệ thống hoàn chỉnh từ tự động hóa đến triển khai các hệ thống giám sát và giải quyết một số bài toán về triển khai và giám sát hệ thống. 
3.3. Mô tả nghiên cứu
Giới thiệu đề tài

**Giới thiệu về mục tiêu chính của đề tài**
- Tự động hóa được quy trình triển khai: nghiên cứu ansible có thể tối ưu hóa việc triển kahi các ứng dụng microservice trên môi trường k8s.
- Giám sát hệ thống: Tích hợp các công cụ giám sát như prometheous, grafana và elk để theo dõi hiệu suất và phát hiện sự cố.
**Kết quả đạt được**: Triển khai một hệ thống hoàn chỉnh từ việc tự động hóa triển khai đến giám sát hệ thống, giải quyết bài toán thực tế về vận hành và quản lý microservices trong môi trường sản xuất.



II. Khóa luận tốt nghiệp
1. Tên đồ án: Tối ưu hóa quy trình triển khai và giám sát microservices bằng AI và federated learning. 
2. Thời gian thực hiện: 4 tháng

III. Tổng thời gian thực hiện: 7 tháng
Mujc tiêu chính:
- Tối ưu hóa và giám sát điều chính hệ thống: sử dụng AI để có thể tự động điều chỉnh tài nguyên và dự đoán sự cố trên hệ thống microservices.
- Ứng dụng FL: Áp dụng FL để xử lý dữ liệu phân tán và đưa ra các mô hình AI mà khoogn cần tập trung dữ liệu.
3. Nội dung chính
- AI trong giám sát và tối ưu hóa hệ thống microservices: Tích hợp AI vào các công cụ giám sát hiện có (Prometheous), giúp tự động điều chỉnh tài nguyheen và tối ưu hóa hiệu suất làm việc bất thuwognf trong hệ thống. 
- Ứng dụng federated learning trong lĩnh vực y tế: sử dụng microservices để triển khai các mô hình máy học phân tán cho bài toán thực tế 

ĐỊnh hướng: Một chủ đề phù hợp vopwis xu hướng phát triển hiện tại về cloud computing, AI và bảo mật dữ liệu phân tán để có thể phát triển.

Có một hướng khác là phát triển các kiến trúc microservices cho ứng dụng di động. 
Kiến trúc microservices cho ứng dụng di động thường yêu cầu một kiến trúc back-end phức tapoj và xử lý các tác vụ như quản lý người dùng, lưu trữ dữ liệu và tích hợp thực hiện các dịch vụ bên thứ 3. Thay vì sử dụng một kiến trúc đơn khối monolithic architecture thì miccroservices sẽ tách từng chức năng riêng biệt thành các dịch vụ khác nhau.

1. Kiến trúc Microservices cho Ứng dụng Di động
Ứng dụng di động thường yêu cầu một kiến trúc back-end phức tạp để xử lý các tác vụ như quản lý người dùng, thanh toán, lưu trữ dữ liệu và tích hợp với dịch vụ bên thứ ba. Thay vì sử dụng một monolithic architecture (kiến trúc đơn khối), microservices sẽ tách biệt từng chức năng (user authentication, payment, notifications, etc.) thành các dịch vụ riêng biệt.

Ví dụ về kiến trúc microservices cho ứng dụng di động:
Authentication service: Dịch vụ xác thực người dùng, có thể sử dụng OAuth hoặc JWT.
User service: Quản lý hồ sơ người dùng và dữ liệu cá nhân.
Payment service: Xử lý giao dịch thanh toán qua các cổng thanh toán như Stripe hoặc PayPal.
Notification service: Quản lý và gửi thông báo đẩy (push notifications) đến người dùng.
Analytics service: Theo dõi hành vi của người dùng và gửi dữ liệu về hệ thống phân tích.
2. Lợi ích của Microservices đối với Ứng dụng Di động
Tính mô-đun: Mỗi microservice chỉ chịu trách nhiệm cho một chức năng cụ thể, giúp dễ dàng phát triển, kiểm thử và triển khai độc lập mà không ảnh hưởng đến toàn bộ hệ thống.
Khả năng mở rộng (Scalability): Các dịch vụ có thể được mở rộng độc lập tùy vào nhu cầu sử dụng. Ví dụ, nếu lượng giao dịch tăng đột biến, bạn chỉ cần mở rộng dịch vụ thanh toán mà không cần ảnh hưởng đến các dịch vụ khác.
Khả năng chịu lỗi (Fault Isolation): Nếu một microservice bị lỗi, các dịch vụ khác không bị ảnh hưởng, giúp cải thiện độ tin cậy và khả năng hoạt động liên tục của hệ thống.
Linh hoạt trong công nghệ: Mỗi microservice có thể được viết bằng một ngôn ngữ lập trình hoặc framework khác nhau, tùy thuộc vào nhu cầu và đặc điểm kỹ thuật cụ thể.
3. Triển khai Microservices cho Ứng dụng Di động trên Kubernetes (K8s)
Backend API Gateway: Ứng dụng di động không tương tác trực tiếp với từng microservice mà qua một lớp trung gian gọi là API Gateway. API Gateway sẽ nhận yêu cầu từ ứng dụng di động và chuyển đến các microservice tương ứng.

Ví dụ, API Gateway phổ biến có thể là Kong, NGINX, hoặc AWS API Gateway.

Triển khai các microservice trên Kubernetes: Kubernetes giúp quản lý các container của từng microservice. Bạn sẽ triển khai từng microservice dưới dạng các Deployment trên K8s, giúp quản lý tài nguyên, tự động scale, và đảm bảo tính sẵn sàng cao.

Sử dụng Ansible để quản lý triển khai: Ansible có thể giúp bạn tự động hóa quy trình triển khai các microservice trên Kubernetes, đảm bảo rằng các phiên bản mới được triển khai chính xác và có thể rollback dễ dàng khi cần thiết.

4. Giám sát và Bảo mật cho Microservices
Giám sát: Sử dụng các công cụ giám sát như Prometheus, Grafana để theo dõi hiệu suất và hành vi của microservices trong thời gian thực. Điều này rất quan trọng khi triển khai cho ứng dụng di động có lượng người dùng lớn.
Bảo mật: Sử dụng các giải pháp bảo mật như mTLS (mutual TLS) để mã hóa dữ liệu giữa các microservices, hoặc API Gateway để kiểm soát truy cập và bảo vệ hệ thống khỏi các cuộc tấn công.
5. Ví dụ về Kịch bản Thực tế
Nếu bạn có một ứng dụng di động cần xử lý thanh toán và gửi thông báo đẩy, bạn có thể triển khai như sau:

Microservice 1 (Payment): Xử lý các giao dịch thanh toán. Dịch vụ này kết nối với các cổng thanh toán và trả về kết quả cho API Gateway.
Microservice 2 (Notifications): Xử lý và quản lý thông báo đẩy. Dịch vụ này nhận yêu cầu từ API Gateway để gửi thông báo đến thiết bị người dùng qua dịch vụ của Apple (APNs) hoặc Google (Firebase).
6. Thách thức của Microservices cho Ứng dụng Di động
Phức tạp trong quản lý: Việc triển khai và duy trì nhiều microservice đòi hỏi sự phối hợp chặt chẽ, quản lý phức tạp hơn so với kiến trúc monolithic.
Giao tiếp giữa các service: Phải đảm bảo giao tiếp giữa các microservice qua API ổn định và bảo mật, đồng thời cần cơ chế fallback khi một microservice không khả dụng.

ý tưởng: Ứng dụng thương mại điện tử (E-commerce)
Ứng dụng này là một nền tảng mua bán trực tiếp nơi người dùng có thể tìm kiếm, mua sắm và thanh toán trực tuyến., Các microservices sẽ quản lý từng phần của quy trình mua sắm: 
+ Product catalog service: quản lý danh mục sản phẩm
+ order management service: xử lý giỏ hàng và đơn hàng
+ Payment Gateway service: xử lý giao dịch thanh toán
+ User Service: quản lý hồ sơ và thông tin người dùng
+ Inventory service: quản lý kho hàng
+ Recommendation Engine: Gợi ý sản phẩm cho người dùng (có thể tích hợp AI)





B. **Mô tả nghiên cứu**
B1. Giới thiệu đề tài
Trong bối cảnh sự phát triển mạnh mẽ của công nghệ và nhu cầu mua sắm trực tuyến ngày càng tăng cao, ứng dụng thương mại điện tử đang trở thành một trong những yếu tố quan trọng giúp doanh nghiệp tiếp cận toàn cầu.
Ứng dụng E-commerce đang trở thành công cụ thiết yếu cho các doanh nghiệp hiện đại nhằm tiếp cận người tiêu dùng và mở rộng thị trường. Với sự phát triển mạnh mẽ của công nghệ, việc xây dựng các hệ thống thương mại điện tử phải đáp ứng những khả năng yêu cầu về mở rộng, quản lý tài nguyên hiệu quả và tích hợp các công nghệ tiên tiến. Đặc biệt, việc sử dụng kiến trúc microservices và các công cụ quản lý tự động như Kubernetes (K8s) và Ansible đã mang lại những cải tiến vượt trội trong việc triển khai, vận hành và quản lý hệ thống phức tạp.

Một số ứng dụng E-commerce và nội dung của nó, các ứng dụng E-commerce hiện nay đa dạng với nhiều mô hình và nội dung cực kì phong phú. Một số ứng dụng phổ biến hiện nay bao gồm:
- Amazon: một trong những nền tảng E-commerce lớn nhất thế giới với mô hình đa dạng bao gồm bán lẻ, giao dịch giữa các cá nhân (c2c) và cung cấp dịch vụ cho các doanh nghiệp (b2b)
- ebay: nền tảng đấu giá trực tuyến, nơi người dùng có thể mua bán sản phẩm mới và đã qua sử dụng, tập trung vào giao dịch c2c.
- lazada, shopee (ở khu vực đông nam á): các nền tảng này hoạt động theo mô hình marketplace, kết nối người bán và người mua với nhau trên một nền tảng duy nhất, hỗ trợ các hoạt động từ thanh toán, giao hàng đến tiếp thị sản phẩm.
- Tiki, Sendo (ở Việt Nam): tập trung vào các mặt hàng đa dạng từ điện tử, gia dụng đến thực phẩm, với nhiều chính sách hỗ trợ và bảo hành sản phẩm cho người dùng. 
Các ứng dụng này đều dựa trên nền tảng quản lý phức tạp, kết hợp nhiều dịch vụ và phải đáp ứng nhu cầu xử lý khối lượng giao dịch trong thời gian ngắn, đồng thời đảm bảo an toàn cho bảo mật thông tin cho khách hàng.
Từ đó, chúng ta tìm hiểu dược những nền tảng đó cung cấp các chức năng như:
- quản lý sản phẩm và kho hàng: cho phép doanh nghiệp quản lý danh sách sản phẩm, số lượng tồn kho và theo dõi tình trạng đơn hàng, hàng hóa.
- Tích hợp thanh toán: hỗ trợ từ nhiều phương thức thanh toán trực tuyến, từ một thẻ tín dụng đến các ví điện tử, giúp khách hàng dễ dàng thanh toán và hoàn tất giao dịch.
- Quản lý đơn hàng: từ việc mua thêm sản phẩm vào giỏ hàng đến theo dõi tình trạng giao hàng, giúp người mua và doanh nghiệp kiếm soát quá trình giao dịch.
- Tính năng qảng cáo và tiếp thị: các ứng dụng này cũng thích hợp nhiều tính năng tiếp thị, từ quảng cáo trực tuyến đến gợi ý sản phẩm, cá nhân hóa, giúp doanh nghiệp tiếp cận đúng đối tượng khách hàng một cách hiệu quả.
B2. Mục tiêu, nội dung và kế hoạch nghiên cứu
B2.1. Mục tiêu
- Hệ thống mà đồ án này xây dựng là nơi doanh nghiệp có thể tiếp thị và bán các sản phẩm của mình đến khách hàng một cách dễ dàng và hiệu quả, từ đó tối ưu hóa hoạt động kinh doanh trực tuyến. Hệ thống được xây dựng với các chức năng chính như:
- quản lý và sản phẩm và danh mục: doanh nghiệp có thể dễ dàng tạo, cập nhật và quản lý danh mục sản phẩm, bao gồm mô tả, giá cả và hình ảnh. 
- Quản lý đơn hàng và thanh toán: tích hợp nhiều phương thức thanh toán và theo dõi trạng thái đơn hàng, giúp quá trình giao dịch diễn ra nhanh chogns và an toàn.
- quản lý tiếp thị và quảng cáo: cho phép doanh nghiệp xây dựng các chiến dịch tiếp thị trực tuyến, quảng cáo sản phẩm và gợi ý sản phẩm cho người mua dựa trên hành vi mua sắm. 
- Tối ưu hóa chi phí và hiệu suất: hệ thống được triển khai trên nền tảng k8s để đảm bảo tính linh hoạt, khả năng mở rộng và tối ưu hóa chi phí khi nhu cầu sử dụng tăng cao.
- Tích hợp AI: nhằm phân tích thị hiếu của người dùng để doanh nghiệp đưa ra phương án tiếp thị tốt nhất cho doanh nghiệp.
B2.2. Nội dung và phương pháp nghiên cứu 
Nội dung 1. Tìm hiểu về các kĩ thuật và công nghệ được sử dụng trong đề tài.
- phương pháp: tìm hiểu và nghiên cứu các tài liệu về:
+ Lý thuyết về các thuật toán xử lý dữ liệu hiện nay 
+ Lý thuyết về dataflow và các mô hình xử lý logic trong doanh nghiệp
+ Các mô hình Federated learning thích hợp để tìm đặc điểm từ dữ liệu người dùng cung cấp
+ Lý thuyết về xây dựng và triển khai các microservices bằng Kubernetes và Ansible.
+ 
Nội dung 2. Tìm hiểu, xây dựng hoàn thiện ứng dụng E-commerce đã nói từ trước=
Phương pháp: 
+ Hoàn thiện ứng dụng di động bằng framework thích hợp.
+ Phát triển các microservices thích hợp

Nội dung 3: Triển khai các microservices.
Phương pháp:
+ Chuyển đổi từ triển khai service trên các thiết bị vật lý sang các microservices bằng Kurbenetes và Ansible

B2.3. Kế hoạch triển khai
1. Xây dựng ứng dụng E-commerce
- Thực hiện thiết kế và xây dựng ứng dụng.
- Hoàn thiện các yêu cầu của ứng dụng theo các yêu cầu của hệ thống đã đề ra
    Sau khi chỉnh lý về hình thức và nội dung của ứng dụng, sinh viên sẽ thực hiện gải quyết vấn đề đồng bộ và kiểm soát các yêu cầu về đồng bộ hóa các dịch vụ cần thiết và liên quan.

B3. Kết quả dự kiến
B4. Tài liệu tham khảo