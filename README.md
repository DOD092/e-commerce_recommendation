e-commerce_recommendation/
│
├── .venv/ # Virtual environment
│
├── data/
│ ├── data_clean/ # Dữ liệu đã làm sạch cuối cùng
│ │ ├── df_products_clean.csv
│ │ └── df_reviews_clean.csv
│ │
│ ├── data_full/ # Dữ liệu gốc / dữ liệu test
│ │ ├── checkpoint/ # File trung gian, checkpoint
│ │ ├── final/ # Dữ liệu crawl hoàn chỉnh
│ │ ├── test_home_life_products.csv
│ │ └── test_home_life_reviews.csv
│ │
│ └── data_preprocess/ # Dữ liệu sau tiền xử lý
│ ├── df_products_preprocess.csv
│ └── df_reviews_preprocess.csv
│
├── crawl_data.ipynb # Notebook crawl / thu thập dữ liệu
├── preprocess.ipynb # Tiền xử lý dữ liệu & NLP
├── eda.ipynb # Exploratory Data Analysis
│
├── cf.ipynb # Collaborative Filtering (cơ bản)
├── cf_impro.ipynb # Collaborative Filtering (cải tiến)
├── cf_final.ipynb # Collaborative Filtering hoàn chỉnh
│
├── requirements.txt # Danh sách thư viện Python
├── .gitignore
└── README.md
