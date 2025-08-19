# 🛡️ DNSChanger & Region Firewall Manager  

**DNSChanger** is a Windows tool that lets you quickly switch DNS servers and block entire IP ranges of regions/countries through Windows Firewall.  
It is designed to improve security, manage network access, and provide full control over which regions can connect.  

---

## ✅ Current Features  

- **DNS Switching**  
  - Predefined DNS options (Shekan, Electro, Begzar, 403, etc.)  
  - Ability to add and select custom DNS servers  

- **Region Blocking via Firewall**  
  - Blocks all regions except the selected one  
  - Automatically splits IP ranges into smaller batches (max 150 per rule)  
  - Creates **both TCP and UDP firewall rules** for full coverage  
  - Resets previously created rules before applying new ones  

- **Logging**  
  - Displays blocked IPs in groups of 5 for better readability  
  - Shows success/error messages for each applied batch  

- **UI/UX**  
  - Simple and user-friendly Windows Forms interface  
  - ComboBox selection for regions  
  - Status label showing which region is open  
  - Real-time ping monitoring for the selected region  

---

## 🚀 Next Update (Planned Features)  

- **Whitelist Support**  
  - Add custom IPs or domains that will never be blocked  

- **Scheduler**  
  - Automatic block/unblock of regions at specific times  

- **Export & Reports**  
  - Save logs and firewall rules to TXT/JSON files  

- **GeoIP Lookup**  
  - Dynamically block countries using GeoIP instead of static lists  

- **Advanced Rule Management UI**  
  - Display all created firewall rules in-app  
  - Allow users to delete or edit rules manually  

---

🔥 With **DNSChanger**, you can easily take control of your network and keep only the regions you trust open.  
