# DỰ ĐOÁN NỒNG ĐỘ NO2 TRONG KHÔNG KHÍ


## 1. Giới thiệu dự án

Dự án xây dựng mô hình Machine Learning nhằm dự đoán nồng độ khí Nitrogen Dioxide (NO2) trong không khí dựa trên bộ dữ liệu Air Quality từ UCI Machine Learning Repository.

Thông qua việc phân tích dữ liệu và xây dựng mô hình dự đoán, dự án hướng đến việc tìm hiểu khả năng ứng dụng Machine Learning trong phân tích chất lượng không khí.

## 2. Mục tiêu dự án

- Khám phá và phân tích bộ dữ liệu Air Quality.
- Xử lý dữ liệu thiếu và dữ liệu bất thường.
- Xây dựng mô hình dự đoán nồng độ NO2.
- So sánh và đánh giá hiệu quả của các mô hình.
- Phân tích kết quả và những hạn chế của dự án.

## 3. Thông tin bộ dữ liệu

- **Tên:** Air Quality.
- **Nguồn:** UCI Machine Learning Repository.
- **Đường dẫn:** https://archive.ics.uci.edu/dataset/360/air+quality
- **Số bản ghi:** 9.358.
- **Số thuộc tính:** 15.
- **Biến mục tiêu:** `NO2(GT)`.

## 4. Công nghệ sử dụng

- Python 3.14.7.
- Pandas.
- NumPy.
- Matplotlib.
- Seaborn.
- Scikit-learn.
- Jupyter Notebook.

## 5. Cấu trúc dự án

```text
BaoCaoCuoiKy/
├── data/
│   └── AirQualityUCI.csv
├── notebooks/
│   └── 01_data_exploration.ipynb
├── src/
├── results/
│   └── figures/
├── report/
├── README.md
└── requirements.txt
```