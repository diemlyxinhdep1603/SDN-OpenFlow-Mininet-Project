# 🚀 TÌM HIỂU VÀ TRIỂN KHAI MẠNG SDN (SOFTWARE DEFINED NETWORK)

**Dự án nghiên cứu chuyên sâu về kiến trúc mạng định nghĩa bằng phần mềm (SDN) và triển khai thực nghiệm mô hình mạng qua giao thức OpenFlow.** 

---

### 📑 NỘI DUNG TRỌNG TÂM

* **Lý thuyết:** Phân tích toàn diện kiến trúc 3 lớp gồm Application, Control và Infrastructure Layer.
* **Giao thức:** Nghiên cứu tiêu chuẩn OpenFlow và cơ chế hoạt động của Flow Table.
* **An ninh mạng:** Nhận diện các mối đe dọa như giả mạo traffic, lỗ hổng Controller và cách triển khai bảo mật.
* **Thực nghiệm:** Xây dựng mô phỏng topo mạng thực tế để đo lường khả năng chống chịu trước tấn công **DDoS (ICMP Flood)**.

### 💻 HỆ THỐNG TRIỂN KHAI

| Thành phần | Công cụ sử dụng |
| :--- | :--- |
| **Môi trường** | 02 máy ảo Ubuntu chạy song song để tối ưu hiệu suất |
| **SDN Controller** | **OpenDaylight (ODL)** - Bộ điều khiển trung tâm |
| **Mô phỏng mạng** |**Mininet** - Giả lập Switch, Host và các liên kết |
| **Phân tích & Tấn công** | **Iperf3** (Băng thông), **Hping3** (DDoS), **Wireshark** (Gói tin)  |

### 📊 KẾT QUẢ ĐO LƯỜNG HIỆU SUẤT

* **Trạng thái bình thường:** Duy trì băng thông cực kỳ ổn định ở mức **~5.48 Gbits/sec**.
* **Khi bị tấn công DDoS:** Hệ thống bị quá tải lưu lượng, băng thông sụt giảm mạnh chỉ còn **~2.54 Gbits/sec**.
* **Phục hồi:** Sau khi ngừng tấn công, hiệu suất mạng lập tức trở lại mức **~5.58 Gbits/sec**


