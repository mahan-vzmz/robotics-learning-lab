<div dir="rtl" align="right" markdown="1">

# برگهٔ فرمول سینماتیک ربات سیار

**قرارداد مشترک:** $x_R$ جلو، $y_R$ چپ، $\theta$ پادساعت‌گرد؛ $r$ شعاع هر چرخ بر حسب متر، $L$ فاصلهٔ کامل دو چرخ بر حسب متر. $\dot\phi_R,\dot\phi_L$ بر حسب رادیان‌برثانیه‌اند. سطح صاف، شعاع‌های برابر و غلتش بدون لغزش فرض می‌شوند.

| کار | رابطه |
| --- | --- |
| سرعت بدنه از چرخ‌ها | $v=\frac r2(\dot\phi_R+\dot\phi_L)$، $\omega=\frac rL(\dot\phi_R-\dot\phi_L)$ |
| سرعت چرخ از بدنه | $\dot\phi_R=\frac{v+L\omega/2}{r}$، $\dot\phi_L=\frac{v-L\omega/2}{r}$ |
| سرعت در جهان | $\dot x=v\cos\theta$، $\dot y=v\sin\theta$، $\dot\theta=\omega$ |
| قید جانبی | $-\sin\theta\,\dot x+\cos\theta\,\dot y=0$ |
| انکودر | $\Delta s_i=2\pi r\,n_i/N$، $\Delta s=(\Delta s_R+\Delta s_L)/2$، $\Delta\theta=(\Delta s_R-\Delta s_L)/L$ |
| شعاع مسیر مرکز | $R=v/\omega$، فقط وقتی $\omega\ne0$ |

برای **اولر**: $x'=x+v\cos\theta\,\Delta t$، $y'=y+v\sin\theta\,\Delta t$، $\theta'=\theta+\omega\Delta t$.

برای **سرعت‌های ثابت در تمام گام** و $\omega\ne0$:

$$
x'=x+\frac v\omega[\sin(\theta+\omega\Delta t)-\sin\theta],\qquad
y'=y-\frac v\omega[\cos(\theta+\omega\Delta t)-\cos\theta],\qquad
\theta'=\theta+\omega\Delta t.
$$

اگر $\omega=0$، از رابطهٔ حرکت مستقیم استفاده کن. این برگه جای توضیح فرض‌ها و تمرین را نمی‌گیرد؛ [توضیح تکمیلی](reference-additions.md) را برای معنی هر رابطه بخوان.

</div>
