# jmeter

Mục tiêu
  Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://www.facebook.com.
  Chạy kịch bản kiểm tra và ghi lại kết quả.
  Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
  Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

Kịch bản kiểm tra
  Hread Group:
  Số lượng thread: 100
  Thời gian chạy: 180 giây
  Ramp-up period: 10 giây
  HTTP Request:
  URL: https://www.facebook.com
  Method: GET
  Content encoding: UTF-8

Listeners
View Results Tree
![335413358-cc670054-5e7d-4d34-ac36-9e9ee1b1de28](https://github.com/ggit1403/jmeter/assets/96821807/943e1121-e3b1-4a2c-9708-fb7a300df72c)

![335413475-6ffb90f5-b14f-49c5-a385-148c681919b1](https://github.com/ggit1403/jmeter/assets/96821807/06dacf3d-3f14-469e-8c1a-9ba98456e816)

