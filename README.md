# 🏛️ Central Library

---

## 🚀 One-Click Cloud Deployment
You can deploy this entire application (both the Spring Boot backend/frontend and a PostgreSQL database) to **Render.com** with a single click:

1. Click the **Deploy to Render** button above.
2. Log in to your Render account.
3. Review the blueprint template details and click **Apply**.
4. Render will provision a free PostgreSQL database, compile the project using the containerized `Dockerfile`, link the connections, and launch your server online automatically.

---

## 💻 Running Locally

### Prerequisites
The repository includes a portable local runner. You do **not** need Java or Maven installed globally.

### Launching on Windows
1. Open PowerShell in the project directory.
2. Execute the launcher script:
   ```powershell
   .\run_local.ps1
   ```
3. Open your browser and navigate to: **[http://localhost:8080](http://localhost:8080)**.

### Launching on Linux/macOS/Replit
1. Open a terminal.
2. Run the shell script:
   ```bash
   bash run.sh
   ```

---

## 🔐 Default Login Credentials
* **System Administrator**:
  * Username: `admin`
  * Password: `admin123`
* **Librarian Profile**:
  * Username: `librarian`
  * Password: `lib123`
* **Student Profile**:
  * Username: `student`
  * Password: `student123`


---
**Developed by Soul of Ghost**
