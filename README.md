# MathChat VietNamese for high school sudent

Dự án này được thực hiện với mục đích phát triển một hệ thống chatbot hỗ trợ giải toán cho nhóm học sinh cấp 3 ở Việt Nam bằng việc tận dụng sức mạnh của hệ thống RAG (Retrieval-Augmented Generation System) được thiết kế chuyên biệt cùng với khả năng xử lý ngôn ngữ tiếng việt tốt của API Gemini. Hệ thống chatbot được tạo ra có hai chức năng chính là giải bài toán cấp 3 mà người dùng đưa vào và đưa ra được tài liệu liên quan như lý thuyết, công thức tính toán liên quan tới bài toán đó cũng như những bài toán tương tự với mục đích củng cố kiến thức dạng toán cho người dùng với lời giải hợp lí nhất dựa vào kho dữ liệu có sẵn.
1. Pipeline
   ![Screenshot 2025-03-25 102526](https://github.com/user-attachments/assets/171e1a7e-e474-4825-a59b-9339aefa96ca)
2. Quy trình truy vấn trong hệ thống
   ![Screenshot 2025-03-25 102718](https://github.com/user-attachments/assets/e8ceab77-71fd-4d59-a5b7-dffc76421be2)
3. Kết quả
   Test trên 1 đề thi THPT môn toán 2024, mô hình của chúng tôi đạt kết quả đáng tin cậy khi giải được 44/50 câu hỏi trắc nghiệm.
   Bảng so sánh kết quả dựa trên đề thi THPTQG môn toán 2024:
   ![Screenshot 2025-03-25 102933](https://github.com/user-attachments/assets/04e2fa7e-f77a-412c-a682-15046f77d63e)
4. Các mô hình sử dụng:
   Colpali model, Qdrant Database, Gemeni model.
