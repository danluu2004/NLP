# NLP Normalization: ViT5 & BARTpho

## 📌 Giới thiệu
Repo này chứa code và notebook huấn luyện 2 mô hình **ViT5** và **BARTpho** trên bộ dữ liệu **ViLexNorm** cho bài toán chuẩn hóa ngôn ngữ mạng tiếng Việt.

## 📂 Cấu trúc
```
.
├── NLP_ViT5.ipynb          # Notebook huấn luyện ViT5
├── NLP_BARTpho.ipynb       # Notebook huấn luyện BARTpho
├── results/                # Kết quả đánh giá mô hình
│   ├── vit5_results.png
│   ├── bartpho_results.png
│   └── comparison.md
├── requirements.txt        # Thư viện cần cài
└── README.md               # Tài liệu mô tả repo
```

## ⚙️ Cài đặt
```bash
pip install -r requirements.txt
```

## 🚀 Huấn luyện
- ViT5: chạy `NLP_ViT5.ipynb`
- BARTpho: chạy `NLP_BARTpho.ipynb`

## 📊 Kết quả
| Mô hình   | ROUGE-1 | ROUGE-2 | ROUGE-L | BLEU | Test Loss |
|-----------|---------|---------|---------|------|-----------|
| ViT5      | 93.54   | 91.40   | 93.49   | 78.73| 0.3629    |
| BARTpho   | 91.42   | 88.75   | 91.24   | 73.00| 0.2548    |

## 👨‍🏫 Người thực hiện
- Họ tên: *[Tên bạn]*
- Trường/Viện: *[Thông tin của bạn]*
