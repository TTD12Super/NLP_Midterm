# NLP_Midterm

Đồ án NLP tại Trường Đại học Tôn Đức Thắng (TDTU) – Bài tập giữa kỳ.

## Mục tiêu

Hoàn thành **bài toán phân loại văn bản Toxic (độc hại) cho tiếng Việt** với các yêu cầu:

1. **Dữ liệu**  
   - Tự thu thập và xây dựng tập dữ liệu.  
   - Các nhãn:  
     - `non-toxic`: văn bản không độc hại  
     - `toxic`: văn bản có độc hại (có thể chia nhỏ thành các loại con hoặc gom chung thành 1 loại).

2. **Phương pháp**  
   - Sử dụng các mô hình học máy truyền thống:  
     - Logistic Regression, Naive Bayes, SVM, SGD, Decision Tree, Random Forest, Gradient Boosting  
   - Mô hình deep learning:  
     - LSTM (Long Short-Term Memory)  
     - LSTM + Attention (nhằm học trọng số quan trọng của các từ trong câu)

3. **Biểu diễn văn bản**  
   - Theo **term** (word/token) với các chế độ: binary, TF-IDF  
   - **Word Embedding** (Keras Embedding, Word2Vec) để biểu diễn ngữ nghĩa từ  

## Cấu trúc dự án


## Hướng dẫn sử dụng

4. **Cài đặt môi trường**

```bash
python3 -m venv NLP_venv
source NLP_venv/bin/activate
pip install -r requirement.txt
