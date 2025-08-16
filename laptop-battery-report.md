Windows tizimida batareya holatini tahlil qilish uchun **battery report** (batareya hisobotini) olish . Buni bajarish uchun quyidagi amallarni bajarishingiz mumkin:

### 1. **PowerShell yoki Command Prompt orqali battery report olish**:

1. **Win + X** tugmalarini bosib, **Command Prompt (Admin)** yoki **Windows PowerShell (Admin)** ni tanlang.

2. Quyidagi buyruqni yozing va Enter tugmasini bosing:

   ```
   powercfg /batteryreport /output "C:\battery_report.html"
   ```

   Bu buyruq batareya hisobotini HTML formatida saqlaydi. Siz bu faylni **C:** diskidagi `battery_report.html` nomi bilan topasiz.

3. **Faylni ochish**: Endi "C:" diskiga o'ting va `battery_report.html` faylini oching. Bu hisobotda batareyaning umumiy holati, qachon olinganligi, batareya imkoniyatlari va boshqa batareya parametrlarini ko'rishingiz mumkin.

### 2. **Hisobotni ko'rish**:

Faylni brauzer orqali oching va batareyaning so'nggi ishlash holati, xizmat muddati, batareyaning maksimal quvvati va boshqa muhim ma'lumotlarni ko'rib chiqing.

