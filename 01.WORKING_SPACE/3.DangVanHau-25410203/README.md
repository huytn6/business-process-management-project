# 3.8 Quản lý hoàn trả hàng & Chăm sóc khách hàng (CSKH) - Viettel Post

## 3.8.3 PHÂN TÍCH ĐỊNH TÍNH (QUALITATIVE ANALYSIS)

---

### 3.8.3.1 Phân tích giá trị gia tăng (Value-added Analysis)

Toàn bộ 17 bước công việc trong quy trình được phân loại theo 3 nhóm giá trị:
- **VA (Value-Adding)**: Hoạt động tạo giá trị trực tiếp cho khách hàng.
- **BVA (Business Value-Adding)**: Hoạt động phục vụ quản lý, đối soát và tuân thủ quy định Viettel Post.
- **NVA (Non-Value-Adding)**: Hoạt động lãng phí, nằm chờ hoặc làm lại do sai sót.

| Bước quy trình | Bộ phận thực hiện | Phân loại | Giải thích lý do |
|---|---|:---:|---|
| **1. Gửi yêu cầu hoàn trả / khiếu nại** | Khách hàng | **VA** | Khởi tạo nhu cầu chính đáng để được đổi trả hàng hoặc bồi thường. |
| **2. Cung cấp chứng từ bổ sung** | Khách hàng | **NVA** | Phát sinh do đơn nộp lần đầu thiếu thông tin, làm lại tốn thời gian. |
| **3. Tiếp nhận yêu cầu** | Bộ phận CSKH | **BVA** | Ghi nhận vé xử lý vào hệ thống ticket để phân công nhân sự. |
| **4. Kiểm tra thông tin đơn hàng** | Bộ phận CSKH | **BVA** | Xác minh chính chủ và kiểm tra điều kiện pháp lý để ngừa gian lận. |
| **5. Xác minh nguyên nhân sự cố** | Bộ phận CSKH | **BVA** | Đối soát với kho/shipper để làm rõ trách nhiệm thuộc về ai. |
| **6. Phân loại nhóm yêu cầu** | Bộ phận CSKH | **BVA** | Điều hướng yêu cầu đến đúng luồng nghiệp vụ chuyên trách. |
| **7. Tiếp nhận lệnh thu hồi hàng** | Shipper | **BVA** | Nhận nhiệm vụ trên App để xếp lịch di chuyển lấy hàng. |
| **8. Liên hệ khách & thu hồi hàng** | Shipper | **VA** | Đến tận nơi thu hồi hàng hoàn, giải tỏa lo lắng cho khách hàng. |
| **9. Vận chuyển hàng về kho** | Shipper | **NVA** | Di chuyển cơ học không làm tăng giá trị sản phẩm nhưng bắt buộc do địa lý. |
| **10. Kiểm tra hàng hoàn tại kho** | Bưu cục / Kho | **BVA** | Kiểm tra ngoại quan, niêm phong tránh việc tráo hàng hoặc hỏng hóc. |
| **11a. Lập biên bản bất thường** | Bưu cục / Kho | **BVA** | Tạo chứng cứ bảo vệ doanh nghiệp khi hàng lỗi hoặc từ chối hoàn. |
| **11b. Xử lý hoàn trả cho người gửi** | Bưu cục / Kho | **VA** | Giao trả tài sản về cho shop/người gửi, hoàn tất mục tiêu đổi trả. |
| **12. Cập nhật kết quả kiểm hàng** | Bưu cục / Kho | **BVA** | Cập nhật hệ thống kho WMS để đóng luồng hàng vật lý. |
| **13. Giải quyết khiếu nại đền bù** | Bộ phận CSKH | **VA** | Đưa ra phương án đền bù thỏa đáng phục hồi niềm tin khách hàng. |
| **14. Tư vấn & giải đáp thắc mắc** | Bộ phận CSKH | **VA** | Hướng dẫn chính sách trực tiếp giúp khách hàng yên tâm sử dụng dịch vụ. |
| **15. Thông báo kết quả phản hồi** | Bộ phận CSKH | **BVA** | Gửi thông báo chính thức qua App/SMS kết thúc xử lý. |
| **16. Nhận kết quả phản hồi** | Khách hàng | **VA** | Khách hàng nghiệm thu kết quả xử lý thỏa đáng. |
| **17. Cập nhật hệ thống & lưu trữ** | Hệ thống / CSKH | **BVA** | Lưu hồ sơ phục vụ đối soát tài chính và báo cáo KPI. |

---

### 3.8.3.2 Phân tích lãng phí & Sơ đồ Xương cá (Waste & Fishbone Analysis)

#### a. Bảng tổng hợp các điểm lãng phí chính trong quy trình (Lean Wastes)

| Loại lãng phí | Hiện trạng trong quy trình | Nguyên nhân thực tế | Đề xuất cải tiến |
|---|---|---|---|
| **Chờ đợi (Waiting)** | Hồ sơ ngâm chờ xác minh giữa CSKH và Kho mất 1-2 ngày. | Thiếu cơ chế cảnh báo SLA tự động và hệ thống chat thủ công. | Tích hợp SLA Auto-alert trên phần mềm CSKH. |
| **Lỗi / Làm lại (Defects)** | 35% đơn nộp bị thiếu ảnh chứng từ, phải gọi lại bổ sung. | Form trên App không bắt buộc đính kèm ảnh 6 mặt sản phẩm. | Bắt buộc tải ảnh/video khui hàng ngay lúc tạo đơn. |
| **Vận chuyển (Transportation)** | Hàng hoàn luân chuyển qua quá nhiều bưu cục trung gian. | Đi theo tuyến giao nhận cố định, chưa có tuyến thu hồi tối ưu. | Phân luồng Shipper trả trực tiếp cho shop cùng khu vực. |
| **Chuyển động (Motion)** | Shipper di chuyển 2-3 lần do khách vắng nhà. | Không hẹn giờ trước với khách hàng qua ứng dụng. | Tự động gửi thông báo hẹn giờ thu hồi trước 30 phút. |
| **Tồn kho (Inventory)** | Hàng hoàn tồn đọng tại kho 3-4 ngày chờ duyệt biên bản. | Chờ Trưởng bưu cục ký tay trực tiếp trên biên bản giấy. | Áp dụng chữ ký số e-Signature phê duyệt trên App Kho. |
| **Xử lý quá mức (Over-processing)** | Kiểm tra thông tin đơn hàng 2 lần độc lập ở CSKH và Kho. | Phần mềm CSKH và WMS Kho chưa kết nối dữ liệu thời gian thực. | Đồng bộ API dữ liệu tập trung giữa CSKH và WMS. |
| **Xử lý quá thừa (Over-production)** | Tiếp nhận xử lý cả các đơn hàng quá hạn đổi trả quy định. | Thiếu bộ lọc tự động kiểm tra điều kiện ngay tại khâu tạo đơn. | Thêm bộ lọc Auto-validation điều kiện đổi trả trên App. |

#### b. Sơ đồ Xương cá phân tích nguyên nhân gốc rễ (Fishbone Diagram)

- **Measurement (Đo lường)**: SLA theo dõi thủ công bằng bảng tính; chưa có chỉ số đo tự động thời gian đọng hàng hoàn tại kho.
- **Material (Hồ sơ / Hàng hóa)**: Khách chụp ảnh chứng từ mờ/thiếu mã vận đơn; hàng hoàn về kho bị móp vỡ niêm phong.
- **Machine (Công nghệ)**: Phần mềm CSKH và WMS Kho chưa kết nối API thời gian thực; App thiếu AI OCR tự động kiểm tra chứng từ.
- **Milieu (Môi trường)**: Khách vắng nhà giờ hành chính; áp lực lượng đơn tăng cao mùa cao điểm.
- **Man (Con người)**: Khách chưa nắm rõ quy định đổi trả; Shipper không hẹn giờ trước; CSKH mới chưa thành thạo tra cứu.
- **Method (Quy trình)**: Phê duyệt biên bản bất thường qua 3 cấp; bắt buộc ký biên bản giấy thủ công chưa áp dụng e-Signature.

```mermaid
graph TD
    subgraph Sơ đồ Xương cá (Fishbone Diagram) - Nguyên nhân hoàn trả kéo dài
        Problem["Vấn đề: Thời gian xử lý hoàn trả kéo dài & Tỷ lệ sai sót cao"]
        
        Measurement["1. Đo lường (Measurement)"] --> Problem
        Material["2. Hồ sơ / Hàng hóa (Material)"] --> Problem
        Machine["3. Công nghệ (Machine)"] --> Problem
        Milieu["4. Môi trường (Milieu)"] --> Problem
        Man["5. Con người (Man)"] --> Problem
        Method["6. Quy trình (Method)"] --> Problem

        M1["SLA đo thủ công"] --> Measurement
        M2["Hàng hoàn móp vỡ / thiếu ảnh"] --> Material
        M3["CSKH & WMS chưa nối API"] --> Machine
        M4["Khách vắng nhà giờ hành chính"] --> Milieu
        M5["Shipper không hẹn giờ trước"] --> Man
        M6["Ký biên bản giấy thủ công"] --> Method
    end
```

---

## 3.8.4 PHÂN TÍCH ĐỊNH LƯỢNG (QUANTITATIVE ANALYSIS)

---

### 3.8.4.1 Cơ sở đơn giá & Bảng dữ liệu định lượng 17 bước

Đơn giá nhân sự theo phút (Định mức 8h/ngày = 480 phút):
- CSKH: 1.042 VNĐ/phút (500k/ngày)
- Shipper: 729 VNĐ/phút (350k/ngày)
- Bưu cục / Kho: 833 VNĐ/phút (400k/ngày)
- Hệ thống CNTT: 100 VNĐ/phút

| Bước quy trình | Bộ phận | $T_{proc}$ (p) | $T_{wait}$ (p) | $T_{cycle}$ (p) | Xác suất ($p$) | Chi phí (VNĐ) |
|---|---|:---:|:---:|:---:|:---:|:---:|
| **1. Gửi yêu cầu hoàn trả** | Khách hàng | 5 | 0 | 5 | 100% | 0 |
| **2. Cung cấp chứng từ bổ sung** | Khách hàng | 10 | 120 | 130 | 20% (Loop) | 0 |
| **3. Tiếp nhận yêu cầu** | CSKH | 3 | 15 | 18 | 100% | 3.125 |
| **4. Kiểm tra thông tin đơn hàng** | CSKH | 5 | 10 | 15 | 100% | 5.208 |
| **5. Xác minh nguyên nhân sự cố** | CSKH | 15 | 60 | 75 | 100% | 15.625 |
| **6. Phân loại nhóm yêu cầu** | CSKH | 3 | 5 | 8 | 100% | 3.125 |
| **7. Tiếp nhận lệnh thu hồi** | Shipper | 2 | 10 | 12 | 70% (Hoàn) | 1.458 |
| **8. Liên hệ khách & thu hồi hàng** | Shipper | 30 | 15 | 45 | 70% (Hoàn) | 21.875 |
| **9. Vận chuyển hàng về kho** | Shipper | 20 | 30 | 50 | 70% (Hoàn) | 14.583 |
| **10. Kiểm tra hàng hoàn tại kho** | Bưu cục/Kho | 10 | 45 | 55 | 70% (Hoàn) | 8.333 |
| **11a. Lập biên bản bất thường** | Bưu cục/Kho | 15 | 30 | 45 | 10.5% (Lỗi) | 12.500 |
| **11b. Xử lý hoàn trả cho người gửi** | Bưu cục/Kho | 20 | 60 | 80 | 59.5% (Đủ) | 16.667 |
| **12. Cập nhật kết quả kiểm hàng** | Bưu cục/Kho | 5 | 10 | 15 | 70% (Hoàn) | 4.167 |
| **13. Giải quyết khiếu nại đền bù** | CSKH | 15 | 90 | 105 | 20% (K.Nại) | 15.625 |
| **14. Tư vấn & giải đáp thắc mắc** | CSKH | 10 | 10 | 20 | 10% (Tư vấn) | 10.417 |
| **15. Thông báo kết quả phản hồi** | CSKH | 5 | 15 | 20 | 100% | 5.208 |
| **16. Nhận kết quả phản hồi** | Khách hàng | 5 | 0 | 5 | 100% | 0 |
| **17. Cập nhật hệ thống & lưu trữ** | Hệ thống/CSKH | 3 | 5 | 8 | 100% | 3.425 |

---

### 3.8.4.2 Tính toán Phân tích luồng theo từng Block (Áp dụng công thức)

Áp dụng các công thức tính Phân tích luồng (Flow Analysis): Sequence ($CT = T_1+T_2$), Rework Loop ($CT = T / (1-r)$), và XOR Alternative Paths ($CT = p_1 \cdot T_1 + p_2 \cdot T_2 + p_3 \cdot T_3$) theo từng Block BPMN:

#### 1. Block 1: Tiếp nhận & Kiểm tra thông tin (Vòng lặp Rework Loop)
Gồm bước 1 -> 4. Xác suất hồ sơ bị thiếu phải làm lại $r = 20\%$. Hệ số làm lại $1/(1-r) = 1/(1-0.20) = 1,25$:
- $T_{proc}(\text{Block 1}) = \frac{5 + 3 + 5 + 0.20 \times 10}{1 - 0.20} = \frac{15}{0.80} = 18,75$ phút.
- $T_{cycle}(\text{Block 1}) = \frac{5 + 18 + 15 + 0.20 \times 130}{1 - 0.20} = \frac{64}{0.80} = 80,00$ phút.

#### 2. Block 2: Xác minh & Phân loại yêu cầu (Nối tiếp Sequence)
Gồm bước 5 -> 6. Công thức Sequence ($T = T_1 + T_2$):
- $T_{proc}(\text{Block 2}) = 15 + 3 = 18,00$ phút.
- $T_{cycle}(\text{Block 2}) = 75 + 8 = 83,00$ phút.

#### 3. Block 3: Phân nhánh xử lý nghiệp vụ (Alternative Paths XOR)
Gateway rẽ nhánh 3 phương án: Nhánh 1 (Hoàn trả - $70\%$), Nhánh 2 (Khiếu nại - $20\%$), Nhánh 3 (Tư vấn - $10\%$).
- **Nhánh 1 (Hoàn trả 70%)**: Bước 7->12. Tại kho rẽ nhánh $85\%$ đủ điều kiện (20m proc, 80m cycle) vs $15\%$ lập biên bản (15m proc, 45m cycle).
  - $T_{proc}(\text{Nhánh 1}) = 2 + 30 + 20 + 10 + (0.85 \times 20 + 0.15 \times 15) + 5 = 86,25$ phút.
  - $T_{cycle}(\text{Nhánh 1}) = 12 + 45 + 50 + 55 + (0.85 \times 80 + 0.15 \times 45) + 15 = 251,75$ phút.
- **Nhánh 2 (Khiếu nại 20%)**: Bước 13 -> $T_{proc} = 15,00$ phút; $T_{cycle} = 105,00$ phút.
- **Nhánh 3 (Tư vấn 10%)**: Bước 14 -> $T_{proc} = 10,00$ phút; $T_{cycle} = 20,00$ phút.

Áp dụng công thức Alternative Paths XOR ($T = p_1 \cdot T_1 + p_2 \cdot T_2 + p_3 \cdot T_3$):
- $T_{proc}(\text{Block 3}) = 0.70 \times 86.25 + 0.20 \times 15 + 0.10 \times 10 = 60.375 + 3.0 + 1.0 = 64,38$ phút.
- $T_{cycle}(\text{Block 3}) = 0.70 \times 251.75 + 0.20 \times 105 + 0.10 \times 20 = 176.225 + 21.0 + 2.0 = 199,23$ phút.

#### 4. Block 4: Phản hồi & Lưu trữ (Nối tiếp Sequence)
Gồm bước 15 -> 17:
- $T_{proc}(\text{Block 4}) = 5 + 5 + 3 = 13,00$ phút.
- $T_{cycle}(\text{Block 4}) = 20 + 5 + 8 = 33,00$ phút.

---

### 3.8.4.3 Tổng hợp chỉ số KPI toàn quy trình

| Chỉ số Định lượng (KPI) | Giá trị tính toán | Đơn vị | Đánh giá thực tế |
|---|:---:|:---:|---|
| **Tổng Thời gian Xử lý thực tế ($T_{proc\_total}$)** | **114,13** | Phút (~ 1h54m) | Thời gian nhân sự thực sự làm việc trên đơn hàng. |
| **Tổng Thời gian Chờ đọng ($T_{wait\_total}$)** | **281,10** | Phút (~ 4h41m) | Thời gian hồ sơ nằm chờ giữa các nấc giao nhận. |
| **Tổng Thời gian Chu kỳ kỳ vọng ($T_{cycle\_total}$)** | **395,23** | Phút (~ 6h35m) | Tổng thời gian xử lý từ đầu đến cuối quy trình. |
| **Hiệu suất Thời gian Chu kỳ (CTE)** | **28,88%** | % | $CTE = \frac{T_{proc}}{T_{cycle}}$. Thời gian nằm chờ chiếm đến 71.12%. |
| **Chi phí Xử lý Kỳ vọng cho 1 đơn** | **84.500** | VNĐ / đơn | Chi phí trực tiếp nhân sự và hạ tầng CNTT. |
