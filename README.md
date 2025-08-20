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
