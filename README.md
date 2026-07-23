# Dự báo mưa Việt Nam — tổ hợp đa mô hình + VNForce-cast

Trang tĩnh dự báo mưa cho Việt Nam theo **tỉnh/thành** và **phường/xã**, dựng từ
ba hệ tổ hợp toàn cầu (ECMWF IFS-ENS, NOAA GEFS, ECMWF AIFS-ENS) và hệ
**VNForce-cast** neo theo radar (độ phân giải cao, hạn đến 48 giờ).

- Giá trị lấy **trực tiếp từ ô lưới 0,25°** (lớn nhất trong các ô thuộc đơn vị).
- Lớp **Độ phân giải cao VNF-cast**: mưa cộng dồn/cường độ trên lưới 0,05°.
- Chỉ công bố **lần chạy mới nhất**; nhánh `main` được ghi đè (force-push).
