# 🎬 Netflix Pipeline Project (Jenkins + Maven + Tomcat Deployment)

This is a simulated **Netflix Sign-In Clone Web App** built using Java and JSP, designed to demonstrate a complete CI/CD pipeline using **Jenkins**, **Maven**, and **Tomcat**. The application mimics Netflix's login page with enhanced UI and is deployed automatically through Jenkins to a remote Tomcat server.

---

## 🚀 Project Highlights

- ✅ CI/CD pipeline via **Jenkins Declarative Pipeline**
- ✅ Maven WAR packaging and multi-threaded build
- ✅ Deployment to **Remote Tomcat 9.x** Server
- ✅ Clean UI resembling real Netflix login experience
- ✅ Organized code structure with GitHub integration

---

## 🛠️ Tech Stack

| Tool         | Purpose                          |
|--------------|----------------------------------|
| Java & JSP   | Backend / View Rendering         |
| Maven        | Build & Dependency Management    |
| Jenkins      | CI/CD Pipeline Automation        |
| Tomcat 9     | Web Application Server           |
| GitHub       | Version Control & SCM            |

---

## 🧩 Pipeline Stages (Jenkinsfile Summary)

```
1. Checkout GitHub Repository
2. Build Project with Maven (Multithreaded)
3. Generate WAR Artifact (Netflix-2.4.war)
4. Deploy WAR to Remote Tomcat Container



📂 Folder Structure
Netflix-Pipeline-Project/
├── pom.xml
├── Jenkinsfile
├── src/
│   └── main/
│       └── webapp/
│           ├── index.jsp
│           └── style.css
└── target/
    └── NETFLIX-1.2.2.war






📷 UI Preview
  ![UI](https://github.com/user-attachments/assets/b1bfea9a-8367-41d3-a41f-488697795c9c)


🌟 Star this repo if you like it!
