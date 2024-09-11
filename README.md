# Speech-Emotion-Recognition-project
# Nhận dạng Cảm xúc từ Giọng nói sử dụng RAVDESS Dataset

Dự án này thực hiện nhận dạng cảm xúc từ giọng nói sử dụng bộ dữ liệu RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song). Mô hình được xây dựng bằng Python và sử dụng các thư viện như scipy, scikit-learn và matplotlib.

## Tính năng

- Trích xuất đặc trưng âm thanh từ file WAV
- Huấn luyện mô hình Random Forest để phân loại cảm xúc
- Đánh giá mô hình bằng báo cáo phân loại và ma trận nhầm lẫn
- Dự đoán cảm xúc cho file âm thanh mới

## Yêu cầu

- Python 3.7+
- numpy
- scipy
- scikit-learn
- matplotlib
- seaborn

## Cài đặt

1. Clone repository:
   ```
   git clone https://github.com/your-username/speech-emotion-recognition.git
   cd speech-emotion-recognition
   ```

2. Cài đặt các thư viện cần thiết:
   ```
   pip install -r requirements.txt
   ```

3. Tải bộ dữ liệu RAVDESS và giải nén vào thư mục `ravdess_data`.

## Sử dụng

1. Mở file `Speech_Emotion_Recognition_RAVDESS.ipynb` trong Jupyter Notebook hoặc Google Colab.
2. Chạy từng ô code theo thứ tự để huấn luyện mô hình và xem kết quả.
3. Để dự đoán cảm xúc cho file âm thanh mới, sử dụng hàm `predict_emotion(file_path)`.

## Cấu trúc dự án

```
speech-emotion-recognition/
│
├── Speech_Emotion_Recognition_RAVDESS.ipynb
├── README.md
├── requirements.txt
└── ravdess_data/
    ├── Actor_01/
    ├── Actor_02/
    └── ...
```

## Kết quả

Mô hình đạt được độ chính xác 36% trên tập kiểm tra. Chi tiết về hiệu suất của mô hình có thể được tìm thấy trong notebook.

## Đóng góp

Mọi đóng góp đều được hoan nghênh. Vui lòng mở issue hoặc gửi pull request để cải thiện dự án.

## Giấy phép

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.
