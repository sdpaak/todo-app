### DevOps Take-Home Assignment: Deploying a Business-Critical Application

**Welcome to your assignment,**

You have been provided with a Git repository containing a business-critical Todo application based on Next.js. This application is crucial for day-to-day operations, and your challenge is to ensure its reliability and accessibility via Google Cloud Platform.


**Assignment Instructions:**

1. **Repository Setup:** - Clone the provided repository from [https://github.com/yaroslav-lohmus/todo-app](https://github.com/yaroslav-lohmus/todo-app) to your own GitHub account. - Implement all changes within your fork and prepare to submit this fork as part of your deliverables.

2. **Docker Deployment:** - Build the Docker image from the provided Dockerfile to ensure the application runs smoothly in a containerized environment.

3. **Continuous Integration Setup:** - Set up a CI/CD pipeline using GitHub Actions. The pipeline should automate the building of the Docker image upon each commit to your fork.

4. **Infrastructure as Code with Terraform:** - Use Terraform to provision the required resources and accounts necessary for deploying the application on Google Cloud Platform. - The deployment must be completed using Cloud Run v2, and the application must be exposed to the internet.

**Google Cloud Environment Setup:**

- You will need to set up your own Google Cloud environment for this assignment. This requires an active billing account. If you do not have an existing Google Cloud account with a billing setup, you may sign up with a new email to receive $300 in credits. Alternatively, you can add your own credit card to activate the billing account. - Please be aware that while the required services for this assignment should not incur any charges if implemented correctly, St1 is not responsible for any costs that may be accumulated as a consequence of attempting this challenge.

**Encouragement for Submission:**

- It's perfectly fine if you can't complete the entire exercise. Please submit whatever you have managed to accomplish, and we can walk through the exercise together during the review to address any challenges you may have faced.

**Deliverables:** - A link to your fork of the GitHub repository containing the GitHub Actions configuration and all other changes. - The Terraform scripts used to set up the necessary resources. - A live URL to the publicly accessible Todo application on Cloud Run v2.

**Support:** For any questions or issues, please contact support through yaroslav.ishanov@st1.com or submit an issue in your project repository.

We look forward to reviewing your innovative solutions.
