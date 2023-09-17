# Data-visualization
အခုဆက်ပြောမှာက Data-visualization အကြောင်းဖြစ်ပါတယ်။ database ထဲက အချက်အလက်တွေကို စိတ်ဝင်စားဖွယ်ဖြစ်အောင် Chart တွေ၊ Graph တွေနဲ့ဖော်ပြနိုင်ပါတယ်။ တည်နေရာအချက်အလက်တွေပါရရှိနိုင်မယ်ဆိုရင် မြေပုံနဲ့ပါပြနိုင်ပါတယ်။ အခုကျွန်တော်တို့ဆီမှာရှိပြီးသား patient data တွေနဲ့ visit data တွေကို အကြမ်းဖျဉ်းဆွဲထုတ်ကြည့်ပါမယ်။
SQL Workshop > SQL Commands ကိုသွားပြီး အောက်ပါ query ကို run ကြည့်ပါ။
```sql
SELECT
    SUM(CASE WHEN PATIENT_GENDER = 'Male' THEN 1 ELSE 0 END) AS TOTAL_MALE
FROM TBL_PATIENT
```