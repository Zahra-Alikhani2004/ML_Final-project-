# آنالیز بازیکنان فوتسال ایران با Python

این نوت‌بوک شامل تحلیل مقدماتی دیتاست بازیکنان فوتسال ایران است. تحلیل شامل بررسی آماری، نمودار هیستوگرام، باکس‌پلات و همبستگی ویژگی‌های عددی است.

## فایل‌ها

- `Iran_Futsal_Analysis.ipynb` : نوت‌بوک Colab برای تحلیل دیتاست
- `Iran_Futsal_Players.csv` : دیتاست بازیکنان فوتسال ایران

## نحوه اجرا

1. نوت‌بوک را در [Google Colab](https://colab.research.google.com/) باز کنید.
2. تمام سلول‌ها را از بالا به پایین اجرا کنید.
3. دیتاست به صورت مستقیم از GitHub بارگذاری می‌شود:
```python
import pandas as pd

url = "https://raw.githubusercontent.com/Zahra-Alikhani2004/ML_Final-project-/main/Iran_Futsal_Dataset/Iran_Futsal_Players.csv"
df = pd.read_csv(url)
