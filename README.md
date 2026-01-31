# Student API Automation Testing

This project demonstrates end-to-end **API automation testing** using **Postman**, **Newman**, and **GitHub Actions CI/CD** for the Student API provided by https://thetestingworldapi.com/.

## 💻 Run Instruction:
1. Download the Project Folder
2. Navigate to the Project Folder
3. Install Dependencies: npm install
4. Run API Automaiton Test: npm run api-test

---

## 🧪 APIs Covered
- Fetch all students
- Create a new student
- Verify student creation
- Update student details
- Verify student update
- Fetch specific student details
- Add address to a student
- Delete student
- Verify student deletion

---

## 🛠️ Tools & Technologies
- Postman
- Newman
- Node.js
- GitHub Actions (CI/CD)
- HTML Reporting (newman-reporter-htmlextra)

---

## 📁 Project Structure
API Automation/
├── collections/
│ └── student_Api.postman_collection.json
├── environments/
│ └── student_API.postman_environment.json
├── reports/
│ └── newman-report.html
├── .github/
│ └── workflows/
│ └── api-tests.yml
├── package.json
├── package-lock.json
└── README.md
