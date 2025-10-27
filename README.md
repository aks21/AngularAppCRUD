🅰️ AngularAppCRUD

A simple CRUD (Create, Read, Update, Delete) application built with Angular and a mock REST API using JSON Server. This project demonstrates core Angular concepts such as components, services, routing, forms, and HTTP client integration.

📋 Features

✅ Create new employee records
✅ View a list of employees
✅ Update existing employee details
✅ Delete employee records
✅ Uses JSON Server as a mock backend
✅ Proxy configuration for seamless API communication

🛠️ Tech Stack

Frontend: Angular

Backend (Mock API): JSON Server

Language: TypeScript

Package Manager: npm

⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/AngularAppCRUD.git
cd AngularAppCRUD

2️⃣ Install Dependencies
npm install

3️⃣ Start JSON Server

Run the mock API server:

npx json-server --watch db.json --port 4000

4️⃣ Run the Angular Application

Start the app with proxy configuration enabled:

ng serve --proxy-config proxy.conf.json

5️⃣ Open in Browser

Visit:
👉 http://localhost:4200

📁 Project Structure
AngularAppCRUD/
├── src/
│   ├── app/
│   │   ├── components/
│   │   ├── services/
│   │   ├── models/
│   │   └── app.module.ts
│   ├── assets/
│   └── environments/
├── db.json
├── proxy.conf.json
├── package.json
└── README.md

🧠 Learnings

This project helps understand:

CRUD operations in Angular

Using HttpClient for API calls

Working with Observable and RxJS

Implementing forms and validation

Using JSON Server for local REST API simulation

📸 Screenshots

(Optional — you can add screenshots of your UI here)

![App Screenshot](./src/assets/screenshot.png)

💬 Feedback

If you find this project helpful or have suggestions for improvement, feel free to open an issue or contribute via pull request!

⭐ Don’t forget to star this repo if you like it!
