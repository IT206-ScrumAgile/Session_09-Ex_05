# THIẾT KẾ CÁCH THEO DÕI GÓP Ý VÀ CẢI TIẾN QUA BA SPRINT — RikkeiAssist

**Người đề xuất:** Thu Hà (Scrum Master), để Scrum Team (Product Owner Minh Anh, Scrum Master và 5 Developers) cùng thống nhất.

**Nhận xét từ dữ liệu Sprint 11–13:** tỷ lệ góp ý đã hỏi rõ tăng 42% → 47% → 56% (5/12, 7/15, 10/18) nhưng vẫn còn 7–8 góp ý chưa làm rõ mỗi Sprint; Improvement còn mở cuối Sprint tăng 2 → 3 → 4. Vì vậy cần hai thứ: góp ý phải được làm rõ rồi mới "xem xét", và Improvement phải có quyết định kết thúc rõ ràng.

**Nguyên tắc giữ nhẹ:** chỉ dùng hai bảng riêng (góp ý, Improvement); cập nhật tại chính buổi họp, mỗi mục một dòng; không thêm cuộc họp mới; Sprint Review chỉ nói góp ý sản phẩm, Sprint Retrospective chỉ nói cách làm việc của nhóm.

---

## Phần 1 — Chu trình theo dõi

### Vòng A — Góp ý (Sprint Review → Product Backlog)

```
[1] Sprint Review: Stakeholders góp ý
        │  Scrum Master ghi ngay vào Bảng Góp ý (nguồn, nguyên văn, Sprint); trạng thái "Mới"
        ▼
[2] Làm rõ (trong Review hoặc ≤ 1 Sprint sau)
        │  Product Owner hỏi lại Stakeholder (ngưỡng, rủi ro, mục đích); ghi "Đã làm rõ" hoặc "Cần làm rõ"
        ▼
[3] Gộp trùng chủ đề và liên kết PBI
        │  Product Owner gộp góp ý cùng chủ đề (giữ mã gốc và nguyên văn); liên kết PBI chỉ ghi "đã xác nhận" khi đã kiểm tra
        ▼
[4] Xem xét Product Backlog (chỉ góp ý "Đã làm rõ")
        │  Product Owner ghi kết quả: tạo PBI / đổi ưu tiên / chưa làm / từ chối, kèm lý do
        ▼
[5] Sprint Review kế tiếp: phản hồi lại Stakeholder
        │  Product Owner báo kết quả xem xét; Scrum Master cập nhật bảng
        └──► góp ý còn thiếu thông tin quay lại bước [2]
```

### Vòng B — Improvement (Sprint Retrospective → kiểm tra ở Sprint sau)

```
[1] Sprint Retrospective: Scrum Team chọn ≤ 2 Improvement
        │  Scrum Master ghi (Hành động, Người/nhóm theo dõi, Khi kiểm tra, Bằng chứng)
        ▼
[2] Sprint Planning kế tiếp: đưa Improvement vào Sprint Backlog
        │  Developers (người/nhóm theo dõi) nhận việc trong Sprint
        ▼
[3] Trong Sprint: ghi bằng chứng
        │  Người/nhóm theo dõi cập nhật một dòng bằng chứng (ví dụ tại Daily Scrum)
        ▼
[4] Sprint Retrospective kế tiếp: kiểm tra lại (mục đầu buổi)
        │  Người/nhóm theo dõi báo bằng chứng; Scrum Master cập nhật bảng
        ▼
[5] Scrum Team cùng quyết định, ghi lý do:
        Đạt → Đóng  |  Chưa đạt → Sửa lại (theo nguyên nhân)  |  Không còn phù hợp → Dừng  |  Chưa đủ bằng chứng → Tiếp tục theo dõi
```

**Ranh giới giữa hai vòng:** vấn đề nội bộ nảy ra trong Review được chuyển sang Retrospective; góp ý sản phẩm nảy ra trong Retrospective được chuyển cho Product Owner. Hai vòng không gộp thành một cuộc họp.

---

## Phần 2 — Bảng theo dõi

### Bảng 1 — Góp ý

Các cột: **Mã | Nguồn | Nguyên văn | Chủ đề | Sprint | Trạng thái | Điều cần làm rõ | Liên kết PBI | Kết quả xem xét Product Backlog | Người cập nhật**

Mẫu cho **F-11-04** (Trưởng nhóm CSKH):

| Mã | Nguồn | Nguyên văn | Chủ đề | Sprint | Trạng thái | Điều cần làm rõ | Liên kết PBI | Kết quả xem xét | Người cập nhật |
|---|---|---|---|---|---|---|---|---|---|
| F-11-04 | Trưởng nhóm CSKH | Chuyển người sớm hơn khi AI không chắc chắn | Ngưỡng AI tự trả lời và chuyển người | 11 | Mới → Cần làm rõ | "Không chắc chắn" là mức nào? Rủi ro chấp nhận? | Không có | Chưa xem xét (chưa đủ thông tin) | Scrum Master ghi; Product Owner làm rõ |
| F-11-04 | (như trên) | (giữ nguyên) | (như trên) | 12 | Cần làm rõ (vẫn chưa rõ ngưỡng); xuất hiện F-12-11 (tăng tự động hóa lên 90%) cùng chủ đề, ý trái chiều | Ngưỡng cụ thể; so với rủi ro Chủ cửa hàng chấp nhận | Không có | Chưa xem xét | Product Owner |
| F-11-04 | (như trên) | (giữ nguyên) | (như trên) | 13 | Cần làm rõ, **gắn cờ lặp lại**: F-13-05 (nhân viên CSKH ca tối) cùng chủ đề; đã 3 Sprint chưa rõ ngưỡng | Ngưỡng cụ thể từ cả CSKH và Chủ cửa hàng | Không có | Chưa xem xét; **đưa lên Sprint Review kế tiếp** để làm rõ cùng hai bên | Product Owner; Scrum Master cập nhật |

### Bảng 2 — Improvement

Các cột: **Mã | Hành động | Người/nhóm theo dõi | Sprint tạo | Khi kiểm tra | Bằng chứng cần có | Bằng chứng ghi nhận | Trạng thái | Quyết định của Scrum Team và lý do**

Mẫu cho **IM-11-02**:

| Mã | Hành động | Theo dõi | Sprint tạo | Khi kiểm tra | Bằng chứng cần có | Bằng chứng ghi nhận | Trạng thái | Quyết định và lý do |
|---|---|---|---|---|---|---|---|---|
| IM-11-02 | Cấp đủ quyền môi trường thử nghiệm từ Ngày 1 và chạy Integration Test khi PBI đầu tiên sẵn sàng | Developers | 11 | Retrospective Sprint 12 | Ngày cấp quyền; ngày PBI đầu tiên sẵn sàng; ngày Integration Test đầu tiên | Sprint 11 (mốc ban đầu): Integration Test đầu tiên Ngày 8 | Mở | Tạo ở Retrospective Sprint 11 |
| IM-11-02 | (giữ nguyên) | Developers | 11 | Retrospective Sprint 13 | (như trên) | Sprint 12: Ngày 7 (sớm hơn 1 ngày, chưa ghi ngày PBI sẵn sàng nên chưa kết luận đạt) | Đang kiểm tra | Tiếp tục theo dõi, bổ sung ghi hai mốc ngày còn thiếu |
| IM-11-02 | (giữ nguyên) | Developers | 11 | Retrospective Sprint 14 | (như trên) | Sprint 13: Ngày 8 (quay lại mốc ban đầu) | Mở, **lặp lại chưa đạt** | Không đóng, không gia hạn y nguyên: Scrum Team **sửa lại** (xem Phần 3) |

---

## Phần 3 — Quy tắc xử lý

**Tình huống 1 — Chủ cửa hàng muốn tăng tự động hóa, nhân viên CSKH muốn chuyển người sớm.**
Ghi cả hai góp ý nguyên văn, gắn cùng chủ đề "Ngưỡng AI tự trả lời và chuyển người" (F-12-11 với F-11-04 và F-13-05), không chọn bên nào và không coi là cam kết. Product Owner làm rõ với cả hai bên (mức "không chắc chắn", rủi ro chấp nhận), rồi xem xét trong Product Backlog và trình bày hai quan điểm cạnh nhau ở Sprint Review kế tiếp. Đây là góp ý sản phẩm, không đưa vào Retrospective.

**Tình huống 2 — Góp ý xuất hiện ở hai Sprint với câu chữ khác nhau; một góp ý có mã PBI kèm dấu hỏi.**
Góp ý cùng ý nghĩa được gộp theo chủ đề nhưng giữ mã gốc và nguyên văn, ghi số lần xuất hiện và số nguồn (F-11-04 và F-13-05: 2 Sprint, 2 nguồn); không sửa hay xóa lịch sử. Liên kết còn dấu hỏi được ghi là "PBI-52 (chưa xác nhận)" cho đến khi Product Owner xác nhận cùng người góp ý (F-12-07 hiện mới "đã làm rõ một phần"), và không tính là "đã liên kết" trước đó.

**Tình huống 3 — Product Owner muốn báo mọi góp ý "đã tiếp nhận"; một Developer đề xuất đóng Improvement quá một Sprint.**
- *Góp ý:* chỉ báo đúng trạng thái thật (Mới / Cần làm rõ / Đã làm rõ / Đã xem xét). "Đã tiếp nhận" không được dùng thay cho "Đã làm rõ"; ví dụ Sprint 13 báo 18 ghi nhận, 10 đã hỏi rõ, 5 đã đưa vào xem xét, không báo 18/18.
- *Improvement:* không đóng vì để lâu. Chỉ đóng, sửa hoặc dừng bằng quyết định minh bạch của Scrum Team kèm lý do ghi trong bảng; Improvement không phải chỉ tiêu cá nhân.
  - **IM-11-02:** đã ba Sprint chưa đạt (Ngày 8, Ngày 7, Ngày 8). Không đóng, không gia hạn y nguyên: **sửa lại**, bổ sung đo ngày cấp quyền và ngày PBI đầu tiên sẵn sàng để tìm nguyên nhân, rồi kiểm tra lại ở Sprint 14.
  - **IM-12-04:** kênh đã ngừng thí điểm nên Improvement không còn phù hợp: Scrum Team quyết định **Dừng** tại Retrospective, ghi lý do và ngày, giữ dòng trong lịch sử (không xóa).
  - **IM-13-03:** mới kiểm tra một lần (hai phiên Pairing, thời gian tái hiện giảm), chưa đủ để đóng: **tiếp tục theo dõi**, kiểm tra lần hai ở Sprint 14 bằng thời gian tái hiện lỗi; nếu đạt lặp lại thì đóng là "Đạt" hoặc chuyển thành thực hành thường xuyên.

**Tiêu chí đo được sau 3 Sprint:** tỷ lệ góp ý đã hỏi rõ trên góp ý ghi nhận đạt **≥ 80% ở Sprint 16** (Sprint 13: 56%, tức 10/18), đo trực tiếp từ Bảng 1. Tiêu chí này đo kết quả (góp ý được làm rõ thật), không đo việc buổi họp có diễn ra đúng lịch hay không.
