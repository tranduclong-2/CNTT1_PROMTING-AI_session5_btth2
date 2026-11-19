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

#OUTPUT
1. Khách Hàng Mục Tiêu ( Target Audience )

| Nhóm khách hàng | Đặc điểm |
|---|---|
| Doanh nghiệp vừa và nhỏ (SME) | Có lượng khách hàng ổn định nhưng thiếu nhân viên CSKH. |
| Doanh nghiệp thương mại điện tử | Thường xuyên nhận câu hỏi về sản phẩm, đơn hàng và vận chuyển. |
| Doanh nghiệp dịch vụ | Cần tư vấn và hỗ trợ khách hàng nhanh chóng. |
| Bộ phận Marketing và CSKH | Muốn tự động hóa việc trả lời và chăm sóc khách hàng. |

2. Nhu cầu khách hàng (Customer Needs)

- Phản hồi khách hàng nhanh chóng.

- Hỗ trợ khách hàng 24/7.

- Giảm khối lượng công việc cho nhân viên.

- Tiết kiệm chi phí vận hành.

- Nâng cao chất lượng chăm sóc khách hàng.

3. Những vấn đề khách hàng gặp phải (Pain Points)

| STT | Pain Points | Giải pháp từ AI Chatbot |
|---|---|---|
| 1 | Khách hàng phải chờ lâu để được phản hồi. | Tự động trả lời câu hỏi nhanh chóng. |
| 2 | Nhân viên CSKH quá tải khi có nhiều yêu cầu. | Tự động xử lý các câu hỏi thường gặp. |
| 3 | Khách hàng liên hệ ngoài giờ làm việc nhưng không được hỗ trợ. | Hỗ trợ khách hàng 24/7. |
| 4 | Chi phí thuê nhân viên chăm sóc khách hàng cao. | Giảm công việc thủ công và tối ưu nguồn lực. |
| 5 | Câu trả lời giữa các nhân viên thiếu thống nhất. | Chuẩn hóa nội dung tư vấn theo dữ liệu doanh nghiệp cung cấp. |
| 6 | Khó quản lý số lượng lớn yêu cầu từ khách hàng. | Hỗ trợ phân loại và xử lý yêu cầu tự động. |


4.Lợi ích nổi bật (Key Benefits)

- Tiết kiệm thời gian: Tự động xử lý các câu hỏi phổ biến.

- Hỗ trợ liên tục: Có thể phản hồi khách hàng ngoài giờ làm việc.

- Tối ưu nhân sự: Giúp nhân viên tập trung vào những yêu cầu phức tạp.

- Nâng cao trải nghiệm: Giảm thời gian chờ đợi của khách hàng.

- Tăng tính nhất quán: Hỗ trợ cung cấp thông tin theo nội dung đã thiết lập.

5. Dữ liệu đầu ra JSON
Đây là dữ liệu được sử dụng làm đầu vào bắt buộc cho Prompt 2.

```JSON
{
  "target_audience": [
    "Doanh nghiệp vừa và nhỏ",
    "Doanh nghiệp thương mại điện tử",
    "Doanh nghiệp dịch vụ",
    "Bộ phận Marketing và CSKH"
  ],
  "customer_needs": [
    "Phản hồi nhanh",
    "Hỗ trợ 24/7",
    "Giảm tải nhân viên",
    "Tiết kiệm chi phí",
    "Nâng cao trải nghiệm khách hàng"
  ],
  "pain_points": [
    "Phản hồi khách hàng chậm",
    "Nhân viên CSKH quá tải",
    "Không hỗ trợ ngoài giờ",
    "Chi phí nhân sự cao",
    "Thông tin tư vấn thiếu thống nhất",
    "Khó quản lý nhiều yêu cầu"
  ],
  "solutions": [
    "Tự động trả lời câu hỏi",
    "Xử lý câu hỏi thường gặp",
    "Hỗ trợ liên tục 24/7",
    "Tối ưu nguồn lực nhân sự",
    "Chuẩn hóa nội dung tư vấn",
    "Phân loại yêu cầu khách hàng"
  ],
  "key_benefits": [
    "Tiết kiệm thời gian",
    "Hỗ trợ khách hàng liên tục",
    "Tối ưu nhân sự",
    "Nâng cao trải nghiệm",
    "Tăng tính nhất quán"
  ]
}
``` 
