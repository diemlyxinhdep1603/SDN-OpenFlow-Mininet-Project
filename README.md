Tìm hiểu và Triển khai Mạng SDN (Software Defined Network)
Dự án nghiên cứu về kiến trúc mạng định nghĩa bằng phần mềm (SDN) và triển khai thực nghiệm mô hình mạng sử dụng giao thức OpenFlow.

📋 Nội dung chính
Nghiên cứu lý thuyết: Tổng quan về SDN, kiến trúc 3 lớp (Ứng dụng, Điều khiển, Hạ tầng) và giao thức OpenFlow.

Giải pháp an toàn: Tìm hiểu các mối đe dọa (giả mạo traffic, lỗ hổng controller) và cách triển khai mạng an toàn trong SDN.

Thực nghiệm (Demo): Mô phỏng topo mạng trên Mininet và đo lường tác động của tấn công DDoS (ICMP Flood) bằng Hping3.

💻 Công cụ triển khai
Môi trường: 02 máy ảo Ubuntu chạy song song.

SDN Controller: OpenDaylight (ODL).

Mô phỏng mạng: Mininet.

Đo lường & Tấn công: Iperf3, Hping3, Wireshark.

📊 Kết quả thực nghiệm
Trạng thái bình thường: Băng thông đạt khoảng 5.48 Gbits/sec.

Khi bị tấn công DDoS: Băng thông sụt giảm còn khoảng 2.54 Gbits/sec.

Sau khi ngừng tấn công: Hiệu suất mạng phục hồi về mức ổn định ban đầu (~5.58 Gbits/sec).
