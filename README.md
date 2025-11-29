# mT5-SFT-and-DPO-Training
# Dịch Máy Anh–Việt với mT5: Supervised Fine-Tuning & RL

Repository này chứa hai notebook minh họa quá trình xây dựng mô hình **dịch máy (Machine Translation)** từ Anh → Việt dựa trên **mT5**, một mô hình encoder–decoder đa ngôn ngữ mạnh mẽ của Google.

Dự án triển khai đầy đủ các bước huấn luyện và căn chỉnh mô hình:

- **Supervised Fine-Tuning (SFT)** trên dữ liệu song ngữ chuẩn  
- **Alignment bằng phần thưởng (RL/DPO)** để cải thiện chất lượng bản dịch  
- **Đánh giá bằng chỉ số BLEU** – tiêu chuẩn phổ biến trong dịch máy  

---

## Mục tiêu

Xây dựng hệ thống dịch Anh–Việt có khả năng:

- Truyền tải **đúng ý nghĩa** của câu nguồn  
- Sinh câu đích **mượt mà, tự nhiên**  
- Tăng chất lượng bản dịch thông qua căn chỉnh hành vi mô hình  
- Tối ưu mô hình bằng các phương pháp hiện đại (SFT → RL/DPO)

---




