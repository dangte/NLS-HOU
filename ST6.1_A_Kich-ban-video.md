# 🎬 KỊCH BẢN – ST6.1: Hiểu cơ chế hoạt động của LLM và AI tạo sinh

**HOOK (0:00–0:45)**
Bạn hỏi ChatGPT một câu. Trong vài giây, nó trả lời dài 3 đoạn, nghe rất thuyết phục. Nhưng nó làm điều đó như thế nào? Hiểu cơ chế LLM không phải để trở thành kỹ sư AI – mà để dùng AI thông minh hơn và không bị lừa bởi sự tự tin giả tạo của nó.

**LLM LÀ GÌ? (0:45–2:00)**
Large Language Model: Mô hình học sâu huấn luyện trên hàng nghìn tỷ từ từ internet và sách. Nhiệm vụ cốt lõi: Dự đoán từ tiếp theo có xác suất cao nhất dựa trên ngữ cảnh. Không 'biết', không 'hiểu' theo nghĩa con người – tổng hợp pattern ngôn ngữ.

Quy trình đơn giản:
1. Bạn nhập prompt
2. Tokenizer phân tách thành token
3. Attention mechanism xử lý ngữ cảnh
4. Mô hình dự đoán token tiếp theo
5. Lặp lại cho đến khi hoàn chỉnh

**AI TẠOO SINH vs AI PHÂN TÍCH (2:00–2:45)**
AI tạo sinh (Generative): GPT-4, Gemini, Claude – tạo nội dung mới (text, ảnh, code). AI phân tích: Hệ thống spam filter, recommendation engine, face recognition – phân loại dữ liệu.

**HẠN CHẾ THIẾT KẾ CỦA LLM (2:45–3:45)**
Không có bộ nhớ thực: Mỗi cuộc trò chuyện bắt đầu lại từ đầu (trừ memory tính năng). Cutoff date: Không biết sự kiện sau ngày training. Hallucination: Tạo ra thông tin nghe có vẻ đúng nhưng sai (xem ST1.5). Stochastic: Cùng prompt cho kết quả khác nhau.

**CÁC MÔ HÌNH CHÍNH (3:45–4:30)**
GPT-4o (OpenAI) · Gemini 1.5 Pro (Google) · Claude 3.5 Sonnet (Anthropic) · Llama 3 (Meta, open source). Mỗi mô hình có điểm mạnh riêng về reasoning, coding, hay safety.

**PHẢN TƯ (4:30–5:00)**
Biết LLM dự đoán từ theo xác suất thay đổi cách bạn tin tưởng output của nó như thế nào?