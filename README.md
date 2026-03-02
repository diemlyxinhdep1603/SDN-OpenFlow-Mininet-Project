# 🚀 TÌM HIỂU VÀ TRIỂN KHAI MẠNG SDN (SOFTWARE DEFINED NETWORK)

> [cite_start]**Dự án nghiên cứu chuyên sâu về kiến trúc mạng định nghĩa bằng phần mềm (SDN) và triển khai thực nghiệm mô hình mạng qua giao thức OpenFlow.** [cite: 8, 129]

---

### 📑 NỘI DUNG TRỌNG TÂM

* [cite_start]**Lý thuyết:** Phân tích toàn diện kiến trúc 3 lớp gồm Application, Control và Infrastructure Layer[cite: 140].
* [cite_start]**Giao thức:** Nghiên cứu tiêu chuẩn OpenFlow và cơ chế hoạt động của Flow Table[cite: 316, 326].
* [cite_start]**An ninh mạng:** Nhận diện các mối đe dọa như giả mạo traffic, lỗ hổng Controller và cách triển khai bảo mật[cite: 410, 421, 425].
* [cite_start]**Thực nghiệm:** Xây dựng mô phỏng topo mạng thực tế để đo lường khả năng chống chịu trước tấn công **DDoS (ICMP Flood)**[cite: 547, 662].

### 💻 HỆ THỐNG TRIỂN KHAI

| Thành phần | Công cụ sử dụng |
| :--- | :--- |
| **Môi trường** | [cite_start]02 máy ảo Ubuntu chạy song song để tối ưu hiệu suất [cite: 534, 536] |
| **SDN Controller** | [cite_start]**OpenDaylight (ODL)** - Bộ điều khiển trung tâm [cite: 450, 458] |
| **Mô phỏng mạng** | [cite_start]**Mininet** - Giả lập Switch, Host và các liên kết [cite: 504, 508] |
| **Phân tích & Tấn công** | [cite_start]**Iperf3** (Băng thông), **Hping3** (DDoS), **Wireshark** (Gói tin) [cite: 552, 553, 1159] |

### 📊 KẾT QUẢ ĐO LƯỜNG HIỆU SUẤT

* [cite_start]**Trạng thái bình thường:** Duy trì băng thông cực kỳ ổn định ở mức **~5.48 Gbits/sec**[cite: 657, 660].
* [cite_start]**Khi bị tấn công DDoS:** Hệ thống bị quá tải lưu lượng, băng thông sụt giảm mạnh chỉ còn **~2.54 Gbits/sec**[cite: 668, 847].
* [cite_start]**Phục hồi:** Sau khi ngừng tấn công, hiệu suất mạng lập tức trở lại mức **~5.58 Gbits/sec**[cite: 862, 956].


