# So sánh ViT5 và BARTpho

- ViT5 vượt trội về độ chính xác (ROUGE, BLEU).
- BARTpho huấn luyện ổn định hơn (Test Loss thấp).
- ViT5 sinh câu dài và đầy đủ hơn.
- BARTpho sinh câu ngắn, gọn hơn.

## Bảng so sánh

| Chỉ số               | ViT5   | BARTpho |
|-----------------------|--------|---------|
| Test Loss             | 0.3629 | 0.2548 ✅ |
| ROUGE-1               | 93.54 ✅ | 91.42 |
| ROUGE-2               | 91.40 ✅ | 88.75 |
| ROUGE-L               | 93.49 ✅ | 91.24 |
| ROUGE-Lsum            | 93.49 ✅ | 91.25 |
| BLEU                  | 78.73 ✅ | 73.00 |
| Độ dài sinh TB (token)| 13.29  | 10.67 ✅ |
