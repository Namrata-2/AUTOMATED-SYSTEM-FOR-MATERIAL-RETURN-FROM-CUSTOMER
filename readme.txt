
# 📦 Automated System for Material Return from Customer

This is a **full-stack web application** designed to automate and manage the return process of materials from customers. The system supports role-based access for Admins, Customers, Delivery Personnel, and Warehouse Staff — ensuring a streamlined, trackable, and transparent return workflow.

## 🌐 Tech Stack

- **Frontend:** React.js (Vite)
- **Backend:** Django (Python)
- **APIs:** RESTful communication between client and server
- **Database:** Configurable via Django ORM
- **Other Tools:** Notification system, static file handling

## 🚀 Features

- Customers can submit return requests with item and pickup details.
- Admins manage users, assign pickups, and monitor return statuses.
- Delivery personnel update real-time pickup and delivery info.
- Warehouse team verifies and confirms return completion.
- System provides notifications and reporting for accountability.

## 📁 Project Structure

```

root/
├── client/         # React frontend (Vite)
├── server/         # Django backend
├── DOCUMENTS/      # Additional documentation
├── run.bat         # Startup script
├── README.md

````

## ⚙️ How to Run the Project

### Frontend (React):
```bash
cd client
npm install
npm run dev
````

### Backend (Django):

```bash
cd server
pip install -r requirements.txt
python manage.py runserver
```

> Ensure Django environment variables and database settings are configured.

## 👤 User Roles

* **Admin:** Controls access, manages returns and reporting.
* **Customer:** Submits material return requests.
* **Delivery Staff:** Handles pickups and status updates.
* **Warehouse Staff:** Confirms returned items and closes requests.

## 📄 License

This project is licensed under the MIT License.
