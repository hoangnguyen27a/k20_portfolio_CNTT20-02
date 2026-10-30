# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Nguyễn Huy Hoàng ]
- Mã sinh viên – Lớp: [ 2071020079-lớp20-02]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ https://hoangnguyen27a.github.io/k20_portfolio_CNTT20-02/ ]
- URL website: [ https://github.com/hoangnguyen27a/k20_portfolio_CNTT20-02.git]
- Tình huống: [không tìm thấy css ] Website của tôi  [https://github.com/hoangnguyen27a/k20_portfolio_CNTT20-02.git ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [chưa có css]
- Mong muốn và hiện tượng thực tế: [thấy được css trên trang]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [Trong DevTools → Network, lọc CSS và xem yêu cầu style.css: URL đầy đủ, status, và nội dung phản hồi. Nếu không thấy yêu cầu CSS, xem Console để tìm lỗi tải tài nguyên.Xác nhận trang đang mở là URL website đã triển khai, không phải trang repository hoặc URL .git. 304 chỉ cho biết trình duyệt có thể dùng bản đã lưu trong cache; không chứng minh CSS bị thiếu.Kiểm tra cấu hình triển khai GitHub Pages và URL của trang được mở.
]
- Tôi nghi nguyên nhân là: [ sai đường link trong HTML đang nằm trên đường dẫn trên windows]
- Vì sao tôi nhận định như vậy: [vì ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [ ] Công cụ AI: [ copilot ]  [của giáo viên ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ PROMPT MẪU
Tôi có URL [https://github.com/hoangnguyen27a/k20_portfolio_CNTT20-02.git], cấu trúc [ main].
Network: Request URL [https://github.com/hoangnguyen27a/k20_portfolio_CNTT20-02.git], Status [304].
Tôi dự đoán [chưa có css].
Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu.
Chỉ tư vấn, không sửa tệp. Không kết luận đã sửa thành công.]

- Gợi ý chính của AI:

  [ Bản sửa tối thiểu đề xuất
Trong cả hai trang HTML, đổi:
<link rel="stylesheet" href="D:\CNTT20-04\portfolio\css\style.css" />

thành:

<link rel="stylesheet" href="css/style.css" />
Đây là hướng sửa được đề xuất dựa trên nội dung repository; chưa có tệp nào được sửa và chưa xác nhận trang đã hoạt động sau sửa. ]

## 3. Quyết định của tôi

- [chấp nhận ] Chấp nhận gợi ý
- [đúng ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [sửa theo gợi ý ]
- Lý do, dựa trên dữ kiện nào: [ tôi đã kiểm tra và thấy đúng]

## 4. Thực hiện và kiểm chứng
## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): Không sửa tệp; chỉ nhận tư vấn.
- Nội dung thay đổi hoặc cách xử lý khác: Chưa áp dụng. Gợi ý là đổi đường dẫn CSS trong index.html và ket-qua.html từ đường dẫn tuyệt đối trên máy tính sang css/style.css.
- Commit của bản sửa, nếu có: Không có.
- Bản sửa đã deploy: [ ] Có  [ ] Chưa  [x] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | Theo thông tin đã ghi nhận: URL https://github.com/hoangnguyen27a/k20_portfolio_CNTT20-02.git, Status 304. Chưa xác nhận đây là yêu cầu tải style.css. | Chưa kiểm tra lại. |
| Giao diện/chức năng trên URL website | Theo ghi nhận, trang chưa hiển thị CSS. | Chưa thử lại vì chưa có thay đổi được áp dụng. |

- Cách thử lại và kết quả thực tế: Chưa thử lại. Khi kiểm tra, mở website GitHub Pages, vào DevTools → Network, lọc CSS rồi tải lại trang. Kiểm tra yêu cầu style.css, status và nội dung phản hồi; sau đó đối chiếu giao diện. Chỉ ghi kết quả sau khi thực sự kiểm tra.
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): Mã nguồn hiện có tệp css/style.css; hai trang index.html và ket-qua.html đang tham chiếu đường dẫn tuyệt đối D:\CNTT20-04\portfolio\css\style.css. Chưa có commit sửa hoặc ảnh chụp kiểm chứng sau sửa.


## 5. Kết luận
- [ ] Đã xử lý được  [ ] Xử lý được một phần  [x] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [Mã nguồn có tệp css/style.css nhưng hai trang HTML đang dùng đường dẫn tuyệt đối trên máy tính. Cần đổi đường dẫn CSS thành css/style.css, deploy lại rồi kiểm tra yêu cầu style.css và giao diện trên website.]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
