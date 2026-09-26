# ⚡ TI Studio Pro — Real-Time Telemetry & Security Analytics Dashboard

Live Telemetry and Workstation Security Dashboard for **TI Studio Pro**.

🌐 **Live URL**: [https://nitinarya09.github.io/TI-Studio-Dashboard/](https://nitinarya09.github.io/TI-Studio-Dashboard/)

---

### 📊 Connected Telemetry Stream
* **Google Sheet**: [TI Studio Pro Telemetry](https://docs.google.com/spreadsheets/d/1n3uZ0k86EeGGSehGc0Btd5WTvWR-cIn4wZ6LYSujHcg/edit?usp=sharing)
* **Webhook Endpoint**: `https://script.google.com/macros/s/AKfycbxnQ21or6ClugN5AU_UDF0jMr-sSqgbtO_Ct75_VkOLuFnxwX7-kQsuuuoRcNwgsXN0qw/exec`
* **Remote Kill-Switch / HWID Config**: [GitHub Gist](https://gist.github.com/nitinarya09/1c4b00f71aaca63f51f1f6f180c8cb1c)

---

### 🚀 Features
- **Live Stream & Auto-Refresh**: Polls Google Sheets every 30 seconds with local caching.
- **KPI Summary Cards**: Total Events, Active Workstations (Unique HWIDs), Active Operators, Audit Runs, Dossier Exports.
- **Interactive Visualizations**: Event Timeline, Event Types Distribution, Workstation Load by HWID, Operator Engagement, Client Environments.
- **Hardware ID (HWID) Control**: One-click HWID copying and direct remote kill-switch integration.
- **Searchable Event Logs**: Client-side filtering across operators, HWIDs, IPs, and details with CSV export.
