# 🧪 Lab Title: Splunk SIEM – DNS Log Analysis

---

# 🎯 Objective

In this lab, you will:

- Learn how to ingest and analyze DNS logs using Splunk Enterprise.
- Perform DNS log analysis using SPL (Search Processing Language).
- Investigate DNS traffic patterns, client activity, DNS servers, and response codes.
- Build a SOC-style dashboard for security monitoring.

---

# 🖥️ Lab Setup

- ✅ Splunk Enterprise
- ✅ JSON-formatted Zeek DNS Logs
- ✅ Windows 11
- ✅ Search & Reporting App

📥 **Dataset**

https://github.com/gyanesh-chand/splunk-dns-log-analysis/blob/main/dns_logs.json
---

# ⚙️ Data Ingestion

1. Open **Splunk Enterprise**
2. Navigate to **Settings → Add Data**
3. Select **Upload**
4. Upload `dns_logs.json`
5. Source Type: `_json`
6. Create an index named **dns_logs**
7. Finish the upload and verify successful indexing.

---
