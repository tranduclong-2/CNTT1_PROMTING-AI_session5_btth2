# **Xây dựng chuỗi Prompt viết bài PR sản phẩm công nghệ**
1. Prompt 1 – Nghiên cứu khách hàng mục tiêu

- Tôi là nhân viên Marketing, cần giới thiệu sản phẩm AI Chatbot chăm sóc khách hàng cho doanh nghiệp.

- Nghiên cứu khách hàng mục tiêu và xác định những vấn đề (Pain Points) mà sản phẩm có thể giải quyết.

- Xác định nhóm khách hàng, nhu cầu và ít nhất 5 Pain Points. Đề xuất giải pháp tương ứng của AI Chatbot.

- Trả kết quả dưới dạng JSON gồm: target_audience, customer_needs, pain_points, solutions, key_benefits.

- Chuyên nghiệp, dễ hiểu, đáng tin cậy.

- Không tự tạo số liệu hoặc tính năng chưa được cung cấp. Lưu kết quả để sử dụng cho Prompt 2.

2. Prompt 2 – Xây dựng dàn ý bài PR

- Sử dụng toàn bộ JSON kết quả từ Prompt 1

- Xây dựng dàn ý chi tiết cho bài PR giới thiệu AI Chatbot, độ dài dự kiến 1000–1500 từ.

- Tạo tiêu đề H1, đoạn mở đầu (Lead), các mục H2, H3, kết luận và CTA. Xác định từ khóa SEO chính và từ khóa phụ.

- Trả kết quả dưới dạng JSON gồm: headline, lead, outline, primary_keyword, secondary_keywords, cta.

- Chuyên nghiệp, tin cậy, thuyết phục.

- Bám sát dữ liệu Prompt 1, không tự thêm thông tin. Lưu toàn bộ dàn ý để sử dụng cho Prompt 3.

3. Prompt 3 – Viết bài PR hoàn chỉnh

- Sử dụng kết quả Prompt 1 và Prompt 2

- Viết bài PR hoàn chỉnh giới thiệu AI Chatbot cho doanh nghiệp, độ dài 1000–1500 từ.

- Triển khai đầy đủ H1, Lead, H2, H3 theo dàn ý. Phân bổ từ khóa SEO tự nhiên, làm rõ Pain Points, lợi ích sản phẩm và kết thúc bằng CTA.

- Bài viết hoàn chỉnh bằng Markdown, đúng cấu trúc SEO, dài 1000–1500 từ.

- Chuyên nghiệp, tin cậy, thống nhất từ đầu đến cuối.

- Không lặp ý, không tự tạo thông tin. Nếu đạt giới hạn token, dừng tại cuối câu hoàn chỉnh và ghi lại chính xác câu cuối cùng cùng mục đang viết để tiếp tục.

4. Kỹ thuật xử lý đứt gãy ngữ cảnh
Khi AI bị ngắt giữa chừng, sử dụng câu lệnh:
Tiếp tục viết bài từ chính xác vị trí đã dừng. Không viết lại nội dung cũ. Giữ nguyên dàn ý, từ khóa SEO và giọng văn chuyên nghiệp. Bắt đầu ngay sau câu cuối cùng, không lặp ý và đảm bảo liên kết tự nhiên với phần trước.

Câu cuối cùng đã viết

Mục đang triển khai

Hãy tiếp tục cho đến khi hoàn thành bài viết 1000–1500 từ.
