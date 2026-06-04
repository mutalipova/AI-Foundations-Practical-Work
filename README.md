# Sun’iy Intellekt Asoslari — Amaliy Ish


## Amaliy ish mavzusi: Chiziqli regressiya yordamida bashorat qilish (Masalan)

### 1. Ishning maqsadi
Ma'lumotlar to'plami (Dataset) asosida chiziqli bog'liqlikni o'rganish va kelgusi qiymatlarni bashorat qiluvchi model qurish.

### 2. Ishlatilgan texnologiyalar va kutubxonalar
* **Python** — Dasturlash tili
* **NumPy & Pandas** — Ma'lumotlarni qayta ishlash
* **Scikit-learn** — SI modelini qurish (LinearRegression)
* **Matplotlib / Seaborn** — Grafik va vizuallash

### 3. Kod strukturasi va algoritm
Modelni o'qitish quyidagi tenglama asosida amalga oshiriladi:
$$y = wx + b$$

Modellashtirish bosqichlari:
1. Ma'lumotlarni yuklash va tozalash.
2. Ma'lumotlarni `Train` (O'qitish) va `Test` (Tekshirish) to'plamlariga ajratish.
3. Modelni o'qitish (`model.fit()`).
4. Aniqlik darajasini tekshirish (MSE, $R^2$ score).

### 4. Natijalar
Model test ma'lumotlarida **92%** aniqlik ko'rsatdi. Olingan natijalar grafik ko'rinishida loyiha jildiga saqlandi.
