# stego-net-basic-interpacket-time-1
nhiệm vụ 1 :
  ping thử từ máy client đến máy server
  mở wireshark trên máy server quan sát các gói tin được ping đến dùng bộ lọc : icpm && ip.src == {ip_client}
  mở code python client để đọc hiểu code
  chạy code với 2 tham số: sudo python3 client.py a 172.25.0.3 (a là string truyền đi, 172.25.0.3 là ip máy server)
  tiếp tục mở wireshark quan sát, lưu ý khoảng thời gian giữa các lần gửi gói tin icmp
nhiệm vụ 2 :
  Sau khi chạy code client và quan sát kết quả từ wireshark, trả lời các câu hỏi trong file txt của container server
nhiệm vụ 3 :
  Sửa lại thời gian giữa các lần truyền gói tin để tăng tốc độ trao đổi gói tin, (giảm xuống 0,5s)
  Sau khi sửa lại, chạy lại code client.py và trả lời câu hỏi trong txt của container server
nhiệm vụ 4:
  Mở code server1.py để đọc hiểu code (đây là code nhận ping và trích xuất thời gian thành các bit nhị phân của string)
  chạy lại client.py và server1.py(server chạy trước client) và quan sát kết quả xem có giống trong wireshark không
nhiệm vụ 5 : 
  Mở code server2.py để chuyển đổi string nhị phân từ nhiệm vụ trước thành thông tin bản rõ
