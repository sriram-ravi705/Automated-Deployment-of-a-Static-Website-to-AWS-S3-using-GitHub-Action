# **Automated Deployment of a Static Website to AWS S3 using GitHub Actions**

**Technologies Used**: GitHub, GitHub Action, AWS S3

**Links**: [GitHub](https://github.com/sriram-ravi705/Automated-Deployment-of-a-Static-Website-to-AWS-S3-using-GitHub-Action)

**Objective:**

* **GitHub as SCM with Webhook Integration for Static Website**: Utilized GitHub as the source code management (SCM) system and configured GitHub webhooks to trigger an automated deployment pipeline for static website content.
    
* **Automated Build and Deployment via GitHub Actions**: Set up GitHub Actions to automatically trigger on code push events, build the static website, and deploy the HTML files to an AWS S3 bucket for hosting.
    
* **AWS S3 Deployment Automation**: Automated the process of copying the static website files (index.html, error.html) to an S3 bucket upon every push to GitHub, ensuring the website is always up-to-date.
    
* **Continuous Deployment to AWS**: Enabled continuous deployment by using GitHub Actions to deploy the latest version of the static website to S3, making it publicly accessible without manual intervention.
    
* **Seamless Deployment of Static Content**: Ensured that changes to the static website files in the GitHub repository are immediately reflected on the live website hosted on AWS S3, enabling real-time updates with every code change.
    

**Architecture:**  

![](./s3_cd.png align="center")