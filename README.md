# pNEUMA_traffic_research
Traffic analysis and speed forecasting using pNEUMA data.

## Nguồn dữ liệu
Dữ liệu gốc pNEUMA được công bố trên Zenodo:
- Trang tải dữ liệu: https://zenodo.org/records/10491409
- DOI: https://doi.org/10.5281/zenodo.10491409

### Phạm vi dữ liệu cần chuẩn bị
Để chạy lại đúng phạm vi nghiên cứu, cần lấy đầy đủ dữ liệu
của cả bốn ngày:
- 24/10/2018 — `20181024`
- 29/10/2018 — `20181029`
- 30/10/2018 — `20181030`
- 01/11/2018 — `20181101`

Trong mỗi ngày, lấy đầy đủ các file hiện có của tất cả khu vực
`d1` đến `d10` và tất cả khung giờ recording.
Không chỉ tải một khu vực hoặc một khung giờ đại diện.

Giữ nguyên tên file gốc để notebook nhận diện ngày, khu vực
và recording. Phạm vi dữ liệu đã chạy trong nghiên cứu gồm
199 recording; đối chiếu danh sách file và manifest do notebook 1
tạo để kiểm tra dữ liệu đầu vào trước khi chạy notebook 2.
