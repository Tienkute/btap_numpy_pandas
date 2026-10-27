# Bài tập NumPy & Pandas

Repository chứa notebook thực hành NumPy/Pandas với các bài phân tích dữ liệu chuyên sâu.

## Nội dung
* **Bài 1: Titanic** — Phân tích hành khách Titanic (tỷ lệ sống sót theo giới tính, hạng vé, thống kê tuổi và giá vé).
* **Bài 2: Insurance** — Phân tích chi phí bảo hiểm y tế (theo độ tuổi, tình trạng hút thuốc, vùng miền và phát hiện outlier).
* **Bài 3: Netflix** — Phân tích phim và chương trình truyền hình Netflix (xu hướng phát hành, quốc gia, thể loại và thời lượng).
* **Bài 4: World Happiness** — Phân tích chỉ số hạnh phúc các quốc gia năm 2019 (tương quan với GDP, hỗ trợ xã hội, tuổi thọ).
* **Bài 5: Wildfires** — Phân tích dữ liệu cháy rừng tại Hoa Kỳ từ cơ sở dữ liệu SQLite (thống kê theo năm, bang, nguyên nhân và diện tích cháy).

## Cấu trúc project
```text
btap_numpy_pandas/
├── data/
│   ├── train.csv
│   ├── insurance.csv
│   ├── netflix_titles.csv
│   ├── world_happiness.csv
│   └── FPA_FOD_20170508.sqlite
├── .gitignore
├── README.md
└── btap_numpy_pandas.ipynb
```

## Lưu ý về Dataset
* Thư mục `data/` chỉ tồn tại trên máy local và **không được upload lên GitHub**.
* Các dataset cần được tải riêng và đặt đúng tên trong thư mục `data/`.
* File `FPA_FOD_20170508.sqlite` có dung lượng rất lớn (~750 MB) nên được quản lý qua `.gitignore` và không đưa vào GitHub repository.

## Hướng dẫn chạy
1. **Clone repository:**
   ```bash
   git clone https://github.com/Tienkute/btap_numpy_pandas.git
   cd btap_numpy_pandas
   ```
2. **Chuẩn bị dữ liệu:**
   * Tạo thư mục `data/` ở thư mục gốc của project.
   * Đặt các file dataset cần thiết (`train.csv`, `insurance.csv`, `netflix_titles.csv`, `world_happiness.csv`, `FPA_FOD_20170508.sqlite`) vào thư mục `data/`.
3. **Mở và thực thi notebook:**
   * Mở file `btap_numpy_pandas.ipynb` bằng Jupyter Notebook, JupyterLab, VS Code hoặc Google Colab.
   * Chọn kernel Python đã cài đặt các thư viện cần thiết (`numpy`, `pandas`, `matplotlib`, `seaborn`).
   * Chạy lần lượt các cell từ trên xuống dưới.
