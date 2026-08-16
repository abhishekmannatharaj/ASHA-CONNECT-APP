# T7 HealthVault
<img width="1024" height="1536" alt="workflow" src="https://github.com/user-attachments/assets/1342c014-786a-44c2-b802-81ad564845e6" />
---

## Tech Stack & Libraries Used

### Frontend & Core
* **Framework:** Flutter (Dart SDK ^3.12.2)
* **UI Design System:** Material Design 3 (Custom Healthcare Teal Theme)

### Database & Storage
* **Local Relational Database:** `sqflite` (Mobile) & `sqflite_common_ffi` (Desktop: Windows, Linux, macOS)
* **Path Management:** `path` & `path_provider`

### Data Visualization & Utilities
* **Charts & Analytics:** `fl_chart` (Vitals and health trend plotting)
* **Date & Number Formatting:** `intl`
* **File Operations:** `file_picker` (JSON database backup & restore)
* **Networking:** `http`

### Backend Stack Architecture
* **Backend Framework:** Python 3.12, Django, Django REST Framework
* **Database Engine:** PostgreSQL
* **Authentication:** SimpleJWT (JSON Web Tokens), Django Auth
* **Configuration:** `python-decouple`, `django-cors-headers`

---

## Features & Functional Modules

* **Dual Role Portal**
  * **Admin Dashboard:** Manage ASHA workers, assign villages/blocks/districts, view systemic health metrics, export/import JSON database backups.
  * **ASHA Worker Portal:** Register families, manage member profiles, record clinical vital signs.
* **Health Metrics Logging**
  * Fasting & Postprandial Blood Sugar (mg/dL)
  * Systolic & Diastolic Blood Pressure (mmHg)
  * Body Temperature (°F) & Pulse Rate (bpm)
* **Data Visualization**
  * Dynamic line charts and trend tracking for patient vital histories.
* **Offline-First Storage**
  * Local SQLite storage with auto-seeded demo dataset and desktop/mobile FFI compatibility.

---

## Getting Started

### Prerequisites
* Flutter SDK (3.12+ recommended)
* Dart SDK

### Installation & Run Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/BLITZz-bot/T7-HealthVault.git
   cd T7-HealthVault/flutter_app
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the application:
   ```bash
   flutter run
   ```

### Sample
<img width="738" height="1600" alt="WhatsApp Image 2026-08-14 at 7 43 12 AM" src="https://github.com/user-attachments/assets/d39294da-3cc0-43ad-8d5a-697e0d29f7b7" />
<img width="738" height="1600" alt="WhatsApp Image 2026-08-14 at 7 43 12 AM (1)" src="https://github.com/user-attachments/assets/b50a5428-9290-41ff-938e-709cf68cb4df" />
<img width="738" height="1600" alt="WhatsApp Image 2026-08-14 at 7 43 11 AM" src="https://github.com/user-attachments/assets/c1332e74-d689-4098-8764-395caeab1f4e" />

## 👥 Engineering Team
* Developed collaboratively by the Smart ASHA Connect Development Team:

-Abhishek Mannatharaj

-Nithelan Jayakumar

-Abdul Shuaib

-M M Bharath
