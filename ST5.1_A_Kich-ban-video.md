# 🎬 KỊCH BẢN – ST5.1: Quy trình debug và giải quyết vấn đề kỹ thuật số

**HOOK (0:00–0:45)**
LMS không tải được bài nộp. Zoom không bật mic. Code chạy đúng trên máy bạn, sai trên máy thầy. Trong môi trường số, vấn đề kỹ thuật không phải 'ẩu rủi' – đó là bài toán có hệ thống để giải. Ai có tư duy debug sẽ không bao giờ bị kẹt quá 15 phút với 1 vấn đề.

**QUY TRÌNH DEBUG 5 BƯỚC (0:45–2:30)**
Bước 1 – Tái tạo vấn đề: Vấn đề có xảy ra đều không? Xảy ra trong điều kiện gì? Lần cuối hoạt động bình thường là khi nào?
Bước 2 – Thu hẹp phạm vi: Thử trên thiết bị/browser/mạng khác. Nếu vấn đề biến mất = vấn đề ở bối cảnh cụ thể đó.
Bước 3 – Tìm lỗi: Error message nói gì? Copy paste vào Google nguyên vẹn. Stack Overflow thường có câu trả lời trong vòng 5 phút.
Bước 4 – Thử giải pháp: Thử từng thứ một, không thử 3 thứ cùng lúc. Ghi lại đã thử gì – tránh thử lại.
Bước 5 – Tư liệu hóa: Ghi lại vấn đề + giải pháp. Lần sau gặp lại = 30 giây.

**CÁC VẤN ĐỀ PHỔ BIẾN VÀ GIẢI PHÁP NHANH (2:30–3:30)**
LMS không nộp được: Clear cache → Thử Chrome Incognito → Thử thiết bị khác → Báo IT với screenshot + error code.
Zoom không âm thanh: Kiểm tra quyền mic trong System Preferences → Thử Virtual Audio Device → Restart Zoom.
Code Python không chạy: Kiểm tra phiên bản Python (python --version) → Kiểm tra đường dẫn file → Kiểm tra encoding.

**KHI NÀO BÁO TRỢ GIÚP (3:30–4:30)**
Trước khi hỏi: Thử ≥3 giải pháp → Google ≥3 lần → Đọc documentation. Khi báo: Mô tả bối cảnh + đã thử gì + error message cụ thể. 'Nó không chạy' ≠ báo lỗi. 'Python 3.11 trên Windows 11, lỗi ModuleNotFoundError: pandas, đã thử pip install' = báo lỗi tốt.

**PHẢN TƯ (4:30–5:00)**
Vấn đề kỹ thuật số gần nhất bạn gặp. Bạn giải quyết theo quy trình hay theo cảm tính?