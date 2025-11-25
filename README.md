# AWS Elastic Beanstalk Project

This project demonstrates how to deploy a simple Node.js application to **AWS Elastic Beanstalk** using the Elastic Beanstalk Console.

---

##  Project Overview

This is a beginner-friendly AWS project designed to help understand how Elastic Beanstalk works. It includes:

- A basic **Node.js Express application**
- Deployment to **Elastic Beanstalk (Single Instance, Free Tier Eligible)**
- ZIP upload deployment method
- Environment creation using default IAM roles

---

##  Project Structure

```
aws-elastic-beanstalk-project/
├── app.js
├── package.json
├── .gitignore
└── node_modules/
```

---

##  How to Run Locally

1. Install dependencies:

```bash
npm install
```

2. Start the app:

```bash
node app.js
```

3. Visit:

```
http://localhost:3000
```

You should see:

```
Hello from Elastic Beanstalk!
```

---

##  Deployment Steps (Completed)

The following steps were used to deploy this app:

1. Created a ZIP file containing `app.js`, `package.json`, and `node_modules/`.
2. Created a new Elastic Beanstalk application.
3. Selected **Single Instance (Free Tier)**.
4. Chose the **Node.js platform**.
5. Created a service role automatically when prompted.
6. Uploaded the ZIP file and launched the environment.
7. Verified that the app shows: *"Hello from Elastic Beanstalk!"*

---

##  Live Environment URL


```
http://aws-elastic-beanstalk-project-env.eba-x6gzxacj.us-east-1.elasticbeanstalk.com/
```

---

##  Notes

- This project is intentionally simple to focus on understanding AWS Elastic Beanstalk.
- Future improvements may include environment variables, logging, CI/CD, or connecting to a database.

---

##  License

This project is licensed under the MIT License.

