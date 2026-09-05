# Quản lý kế hoạch kinh doanh dịch vụ chuyển phát

Tài liệu phân tích quy trình, dựng theo đúng format của
`../Quản trị vòng đời đối tác cung ứng phương tiện vận tải/`.

## Tệp trong thư mục

| Tệp | Nội dung |
|---|---|
| `Quy_trinh_quan_ly_ke_hoach_kinh_doanh_dich_vu_chuyen_phat.docx` | Tài liệu phân tích đầy đủ 5 chương, 23 bảng |
| `Image/kien-truc-quy-trinh-khkd.png` | Hình 1.1 — sơ đồ kiến trúc quy trình |
| `Image/cay-nguyen-nhan-goc-re-khkd.png` | Hình 4.3 — cây nguyên nhân gốc rễ 5 Why |
| `Image/PLACEHOLDER-*.png` | 4 khung chỗ dành cho sơ đồ BPMN (xem bên dưới) |

## Cấu trúc tài liệu

1. **Mô tả quy trình** — thông tin quy trình, kiến trúc, 10 bước, 5 kết quả có thể xảy ra
2. **Phương pháp thực hiện** — 11 minh chứng, kế hoạch làm việc, 22 thuật ngữ, 4 biểu mẫu,
   ma trận 6 tác nhân, 10 câu hỏi định tính, 10 câu hỏi định lượng
3. **Mô hình hóa quy trình** — sơ đồ BPMN 2.0
4. **Phân tích quy trình** — giá trị gia tăng (13 hoạt động), lãng phí (8 loại),
   6 bên liên quan, 6 vấn đề, 5 Why, phân tích thời gian / chất lượng / chi phí
5. **Tài liệu tham khảo** — 12 nguồn

## Còn phải tự làm: 4 sơ đồ BPMN

Bốn hình dưới đây hiện là **khung chỗ**, cần mô hình hóa bằng bpmn.io rồi thay ảnh:

| Hình | Tệp cần tạo | Nội dung |
|---|---|---|
| 3.1 | `..._as_is.bpmn` + `.svg` | Sơ đồ hiện trạng: 2 pool, 5 lane, 10 activity, 3 gateway làm lại |
| 4.1 | `..._VAA.bpmn` + `.svg` | Tô màu VA/BVA/NVA theo cột phân loại của Bảng 4.3 |
| 4.2 | `..._Waste.bpmn` + `.svg` | Gắn nhãn lãng phí Move/Hold/Over-do theo Bảng 4.4 |
| 4.4 | `..._Quantitative.bpmn` + `.svg` | Gắn PT/WT và xác suất rẽ nhánh theo Bảng 4.8 |

Nội dung cụ thể cần thể hiện đã được ghi ngay trên từng khung chỗ.

## Bộ số liệu định lượng (đã kiểm tra khớp nhau)

```
PT  = 134,60 giờ      WT  = 130,80 giờ      CT = 265,40 giờ (33,18 ngày)
PCE = 50,72%          TCT = 124,00 giờ      CRR = 53,28%
FTR = 65,08% (41/63)  FA  = 81,50%          KPI đạt = 73,02% (46/63)
Chi phí = 16.204.000 VNĐ/kỳ  →  257.206 VNĐ/chi nhánh
```

Ba điểm chờ lớn nhất chiếm 96,00 giờ (73,39% tổng thời gian chờ):
chờ 63 chi nhánh phản hồi (40,00h), chờ Ban TGĐ phê duyệt (32,00h), chờ hiệp thương (24,00h).

Ba vòng lặp làm lại chiếm 29,40 giờ, tỷ lệ phát sinh lần lượt 35% / 25% / 20%.

**Lưu ý:** số liệu được xây dựng theo mô hình giải tích dòng chảy của Dumas et al. (2018)
trên cơ sở quy mô 63 chi nhánh của Viettel Post. Cần đối chiếu lại với dữ liệu phỏng vấn
thực tế của nhóm trước khi nộp.
