# Tìm hiểu và Triển khai Mạng SDN (Software Defined Network)

[cite_start]Dự án nghiên cứu về kiến trúc mạng định nghĩa bằng phần mềm (SDN) và triển khai thực nghiệm mô hình mạng sử dụng giao thức **OpenFlow**[cite: 8].

---

### 📋 Nội dung chính
* [cite_start]**Nghiên cứu lý thuyết:** Tổng quan về SDN, kiến trúc 3 lớp (Ứng dụng, Điều khiển, Hạ tầng) và giao thức OpenFlow[cite: 36, 37, 140].
* [cite_start]**Giải pháp an toàn:** Tìm hiểu các mối đe dọa (giả mạo traffic, lỗ hổng controller) và cách triển khai mạng an toàn trong SDN[cite: 50, 409, 410, 421].
* [cite_start]**Thực nghiệm (Demo):** Mô phỏng topo mạng trên Mininet và đo lường tác động của tấn công DDoS (ICMP Flood) bằng Hping3[cite: 53, 547, 549, 553, 554].

### 💻 Công cụ triển khai
* [cite_start]**Môi trường:** 02 máy ảo Ubuntu chạy song song[cite: 521, 551].
* [cite_start]**SDN Controller:** OpenDaylight (ODL)[cite: 450, 458].
* [cite_start]**Mô phỏng mạng:** Mininet[cite: 502, 504].
* [cite_start]**Đo lường & Tấn công:** Iperf3, Hping3, Wireshark[cite: 552, 553, 1159, 1265].

### 📊 Kết quả thực nghiệm
* [cite_start]**Trạng thái bình thường:** Băng thông đạt khoảng **5.48 Gbits/sec**[cite: 657, 660].
* [cite_start]**Khi bị tấn công DDoS:** Băng thông sụt giảm còn khoảng **2.54 Gbits/sec**[cite: 668, 852].
* [cite_start]**Sau khi ngừng tấn công:** Hiệu suất mạng phục hồi về mức ổn định ban đầu (**5.58 Gbits/sec**)[cite: 862, 957].
