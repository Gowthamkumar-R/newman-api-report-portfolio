# Newman API Report Portfolio

This project showcases a **live API test report** generated using [Postman](https://www.postman.com/) and [Newman](https://www.npmjs.com/package/newman), as part of my **software testing portfolio**. It demonstrates how I use automated testing and reporting tools to validate RESTful APIs with precision and clarity.

---

## 📊 Live Report Access

🖥️ **View the full interactive Newman report here**:  
👉 [Newman HTML Report](https://gowthamkumar-r.github.io/newman-api-report-portfolio/Newman_HTML_Report.html)

> The report includes assertion results, response times, request details, and schema validation for each API.
> ![image](https://github.com/user-attachments/assets/9da7f444-44eb-4b38-aeb9-b94d26027c50)


---

## 🛠️ Tools & Technologies

- **Postman** – for writing API test collections
- **Newman** – for CLI execution of Postman collections
- **newman-reporter-htmlextra** – for detailed HTML reporting
- **GitHub Pages** – for hosting and sharing the report live

---

## 📁 Folder Contents
---

## 🧪 What’s Included in the Report

- ✅ Request & response details  
- ✅ Assertion results (pass/fail)
- ✅ Response status and time
- ✅ JSON schema validation
- ✅ Visual summary of execution

---

## 🚀 How I Use This

This live report is part of my portfolio to:

- Showcase API automation skills
- Provide transparency in test execution
- Help teams quickly analyze test outcomes
---

## 🙋‍♂️ About Me

I'm a passionate QA engineer focused on building efficient, scalable, and modern test automation frameworks.
---

## 📌 Want to Run It Yourself?

To generate a similar report locally:

```bash
npm install -g newman newman-reporter-htmlextra
newman run <your-postman-collection.json> -r htmlextra --reporter-htmlextra-export "<Location>"

![image](https://github.com/user-attachments/assets/8dd3fab9-ec0c-4b71-88be-93f2588f30ef)

