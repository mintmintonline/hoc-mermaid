```mermaid
stateDiagram-v2
 [*] --> Chờ
 Chờ --> Xử_lý : Bắt đầu
 Xử_lý --> Hoàn_thành : Thành công
 Xử_lý --> Lỗi : Thất bại
 Hoàn_thành --> [*]
 Lỗi --> Chờ : Thử lại
 Lỗi --> [*] : (https://www.facebook.com/photo?fbid=122192520476048970&set=a.122094791546048970)
