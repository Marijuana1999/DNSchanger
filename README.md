# 🛡️ DNSChanger & Region Firewall Manager  

**DNSChanger** is a lightweight Windows tool for managing DNS servers and blocking entire IP ranges of regions/countries through Windows Firewall.  
It is designed for gamers and advanced users who want **safe control over DNS, regions, and system updates** – without hidden risks.  

⚠️ This application is **not a virus** and contains nothing harmful.  
It uses standard Windows tools (PowerShell & `netsh`) to apply DNS and firewall changes securely.  

---

## ✅ Current Features  

- **DNS Switching**  
  - Predefined DNS options (Shekan, Electro, Begzar, 403, etc.)  
  - Add and select custom DNS servers  

- **Region Blocking via Firewall**  
  - Blocks all regions except the selected one  
  - Splits large IP ranges into smaller batches (max 150 per rule)  
  - Creates **both TCP and UDP rules** for complete coverage  
  - Resets old firewall rules before applying new ones  

- **Logging & Monitoring**  
  - Shows blocked IPs in groups of 5 for readability  
  - Displays success/error messages for each applied batch  
  - Real-time ping monitoring for the selected region  

- **User Interface**  
  - Clean and user-friendly Windows Forms design  
  - ComboBox for region selection  
  - Status label showing which region is open  

---

## ✨ What’s New in Version 2
- **Game Mode** – Temporarily disable all Windows Updates while gaming to prevent background interruptions.  
- **Improved UI** – Redesigned interface with smoother user experience.  
- **Bug Fixes** – Increased stability and reliability.  
- **Safe Firewall Rules** – More efficient region blocking with improved rule handling.  

---

## 🚀 Planned Features (Next Update)  

- **Whitelist Support** – Add custom IPs or domains that bypass blocking  
- **Scheduler** – Automatically block/unblock regions at specific times  
- **Export & Reports** – Save logs and firewall rules to TXT/JSON files  
- **GeoIP Lookup** – Dynamically block countries using GeoIP data  
- **Advanced Rule Manager** – View, edit, or remove firewall rules inside the app  

---

## ⚠️ Important Notes
1. The app **may request Administrator privileges** – this is required for DNS and firewall changes.  
2. If you see errors when applying DNS/region changes, press **Continue**, then close and restart the app.  
3. **Do not install the program in Drive C:** – use another location to avoid permission issues.  
4. If antivirus shows a warning during region setup, it is safe: the app only creates firewall rules to block foreign IP ranges.  
5. DNSChanger contains **no malware, hidden processes, or dangerous code** – only the functions described here.  

---

✅ With **DNSChanger v2**, you can take full control of your DNS, block unwanted regions, and enjoy safer gaming with zero background updates.  

# 🛡️ DNSChanger & Region Firewall Manager  

**DNSChanger** یک ابزار سبک برای ویندوز است که امکان مدیریت سریع DNS و مسدودسازی محدوده‌های IP مربوط به کشورهای مختلف از طریق فایروال ویندوز را فراهم می‌کند.  
این نرم‌افزار مخصوص گیمرها و کاربران پیشرفته طراحی شده تا **کنترل امنی روی DNS، مناطق دسترسی و حتی آپدیت‌های ویندوز** داشته باشند – بدون هیچ ریسکی یا کد مخفی.  

⚠️ این نرم‌افزار **ویروس نیست** و هیچ محتوای مخربی ندارد.  
تنها از دستورات استاندارد ویندوز (PowerShell و `netsh`) برای تغییر تنظیمات DNS و فایروال استفاده می‌کند.  

---

## ✅ قابلیت‌های فعلی  

- **تغییر سریع DNS**  
  - دارای DNSهای آماده (شکن، الکترو، بگذر، 403 و …)  
  - امکان افزودن و انتخاب DNS سفارشی  

- **مسدودسازی منطقه‌ای از طریق فایروال**  
  - مسدود کردن همه کشورها به‌جز کشور انتخاب‌شده  
  - تقسیم رنج‌های بزرگ IP به دسته‌های کوچک‌تر (حداکثر 150 آی‌پی در هر قانون)  
  - ایجاد قوانین همزمان برای **TCP و UDP** جهت پوشش کامل  
  - حذف قوانین قدیمی پیش از ایجاد قوانین جدید  

- **لاگ و مانیتورینگ**  
  - نمایش آی‌پی‌های مسدود شده به‌صورت گروهی (هر 5 عدد) برای خوانایی بهتر  
  - نمایش پیام موفقیت/خطا برای هر دسته آی‌پی  
  - مانیتورینگ پینگ به‌صورت زنده برای منطقه انتخاب‌شده  

- **رابط کاربری**  
  - طراحی ساده و کاربرپسند با Windows Forms  
  - انتخاب کشور از طریق ComboBox  
  - نمایش وضعیت منطقه باز شده  

---

## ✨ تغییرات نسخه ۲
- **حالت گیم (Game Mode)** – امکان بستن موقت آپدیت‌های ویندوز هنگام بازی برای جلوگیری از لگ و قطع شدن.  
- **رابط کاربری بهبود یافته** – طراحی جدید و تجربه کاربری روان‌تر.  
- **رفع باگ‌ها** – افزایش پایداری و کاهش خطاها.  
- **قوانین امن‌تر فایروال** – مدیریت بهینه‌تر برای مسدودسازی مناطق.  

---

## 🚀 امکانات آینده (برنامه‌ریزی‌شده)  

- **لیست سفید (Whitelist)** – امکان افزودن آی‌پی‌ها یا دامنه‌هایی که هرگز مسدود نمی‌شوند  
- **زمان‌بندی (Scheduler)** – مسدود یا آزاد کردن خودکار مناطق در زمان مشخص  
- **گزارش و خروجی‌گیری** – ذخیره لاگ‌ها و قوانین فایروال در فایل TXT/JSON  
- **جستجوی GeoIP** – مسدودسازی کشورها به‌صورت پویا با استفاده از GeoIP  
- **مدیریت پیشرفته قوانین** – نمایش، ویرایش یا حذف قوانین فایروال از داخل نرم‌افزار  

---

## ⚠️ نکات مهم
1. برنامه ممکن است **دسترسی ادمین** بخواهد – این دسترسی برای تغییر DNS و فایروال ضروری است.  
2. اگر هنگام تغییر DNS یا مناطق خطا دیدید، روی **Continue** کلیک کنید، سپس برنامه را ببندید و دوباره اجرا کنید.  
3. نرم‌افزار را **در درایو C نصب نکنید** – برای جلوگیری از مشکلات دسترسی، در مسیر دیگری نصب کنید.  
4. اگر آنتی‌ویروس هنگام ست کردن منطقه پیغام داد، نگران نباشید: برنامه فقط آی‌پی‌های کشورهای دیگر را در فایروال می‌بندد.  
5. DNSChanger هیچ‌گونه ویروس، کد مخفی یا رفتار مشکوکی ندارد – تنها همان کارهایی را انجام می‌دهد که در این توضیحات گفته شده است.
6. ارتباط با من @SpungeBOOB tm

---

✅ با **DNSChanger v2** می‌توانید کنترل کامل روی DNS داشته باشید، مناطق ناخواسته را ببندید و هنگام بازی از آپدیت‌های مزاحم ویندوز راحت شوید – همه این‌ها به‌صورت امن و بدون ریسک.

