# Riva Manager
<img width="1774" height="887" alt="ChatGPT Image May 15, 2026, 12_18_30 PM" src="https://github.com/user-attachments/assets/7bcaa587-391c-434f-a4b0-64afb90df2e2" />

### Professional Business, Inventory & GST Management Suite

Riva Manager is a high-fidelity, all-in-one business management solution designed for retail, service centers, and IT hubs. Built with a focus on keyboard-driven efficiency, real-time GST compliance, and robust staff administration.

---

## 🚀 Key Modules & Features

### 1. Unified Finance Hub
*   **GST Compliance Center**: Real-time GSTR-1 and GSTR-3B JSON exports, portal-ready for direct filing.
*   **Professional Cashbook**: Digitalized daily ledger with automated balance calculation and system-wide data imports.
*   **Voucher Management**: Support for Journal, Contra, and Payment vouchers with automated accounting impact.
*   **Outstanding Dues**: Dynamic tracking of Receivables and Payables with aging analysis and party-wise statements.

### 2. Intelligent Inventory System
*   **Bulk Excel Engine**: Professional 3-step import workflow with custom column mapping and live data preview.
*   **Smart HSN System**: Automated HSN suggestion based on product type and historical categorization.
*   **Category Manager**: Comprehensive suite for renaming, merging, and cleaning up inventory groupings with zero-stock safety locks.
*   **Stock Alerts**: Real-time low-stock thresholds with automated WhatsApp alerts for replenishment.

### 3. Sales & Billing Workflow
*   **Hybrid Billing**: Support for GST B2B (Business) and B2C (Consumer) sales with automated tax calculation.
*   **Credit Management**: Integrated credit sales tracking with due-date alerts and one-click payment settlement.
*   **WhatsApp Integration**: Instant professional invoices and challans sent via WhatsApp with custom emojis and branding.
*   **Sales History**: Deep-dive audit trail of every transaction with edit/delete history and status tracking.

### 4. Service & Repair Center
*   **Job Sheet Engine**: Track service jobs from intake to delivery with custom status labels (Pending, Urgent, Ready).
*   **Engineer Dashboard**: Dedicated views for technicians to update job progress and part requirements.
*   **ETA Prediction**: Smart logic to calculate estimated completion dates based on business working days.
*   **Digital Challans**: Professional PDF and WhatsApp challans for service intake and delivery.

### 5. Staff & Payroll Management
*   **Geo-Fenced Attendance**: Mobile-responsive check-in/out system restricted by office coordinates.
*   **Dynamic Payroll**: Monthly salary calculation with automatic deductions for late arrivals and half-days.
*   **Shift Configuration**: Support for multiple shifts with custom grace periods and monthly salary derivation.
*   **Staff Activity Logs**: Complete audit trail of staff actions across the application for accountability.

### 6. Administration & Security
*   **Granular Permissions**: Fine-grained access control for staff members (Export, Import, Category Manage, Page Visibility).
*   **Database Tools**: Integrated SQLite browser, automated backups, and one-click database restoration.
*   **Multi-User Environment**: Secure login system with role-based dashboard redirection.

---

## 🛠 Technical Stack
*   **Backend**: Python (Flask) with SQLite3
*   **Frontend**: HTML5, Vanilla CSS3 (Custom Design System), Bootstrap 5
*   **Data Processing**: Pandas, OpenPyXL
*   **Offline Support**: PWA (Progressive Web App) with Service Workers

---

## ⚡ Setup & Installation
### 1. Local Setup
1.  **Download release and extract**
2.  **Install Dependencies**: 
    -   **Windows**: Run `install.bat`
    -   **Others**: `pip install -r requirements.txt`
3.  **Run Setup Wizard**: `python setup.py` (Optional)
4.  **Launch App**: `python app.py`
5.  **Access**: Open `http://localhost:5050` in your browser.

### 2. PythonAnywhere Deployment (Anytime Access)
To host Riva Manager for 24/7 access from any device:

1.  **download the zip and upload it to python anywhere server, extract it with unzip filename.zip on root **:

2.  **Configure Web App**:
    -   Go to the **Web** tab on PythonAnywhere.
    -   Click **Add a new web app**.
    -   Select **Manual Configuration** -> **Python 3.13, flask**.
    -   **select path to app**: `/home/<your-username>/app.py`
3.  **Reload**: Go back to the Web tab and click **Reload**.
4.  **Setup**: Visit `your-username.pythonanywhere.com/setup` to initialize your business.

