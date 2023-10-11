### Deploying Simple Todo List Web App with Tailwind CSS and JavaScript on Render(PAAS)
<!-- - Resources: [How To Deploy a React Application with Nginx on Ubuntu 20.04 Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-react-application-with-nginx-on-ubuntu-20-04) or [Deploy Your React App with AWS EC2](https://aws.plainenglish.io/deploy-your-react-app-with-aws-ec2-f355f5700aae)

- Youtube: [Deploying a React Application with Nginx on Ubuntu](https://youtu.be/WKfmhgYQlCM?si=po5HjoOEKE8cQIpo) -->

Deploying a Web application to Render instance involves several steps. Here's a high-level overview of the process:

**Deployment link:** [https://tasks-todo-list.onrender.com](https://tasks-todo-list.onrender.com)
![image](https://github.com/Rhythmic-1/Tasks-List/assets/87231338/98b43d65-234f-4f9e-a8f9-b5063cdfdd82)

1. **Sign Up on Render:**
   - If you don't have a Render account, sign up at Render.

2. **Login to Render:**
   - Log in to your Render account.

   

3. **Create a New Service:**
   - In the Render dashboard, click on "New" and select "Service."
   - Choose your deployment method, either from a Git repository or by uploading a code bundle. In this project, we have used a Git repository.

4. **Connect to Your Git Repository:**
   - Select the Git repository where the project is hosted.
   - Choose the main branch to deploy.
   - Configure the build and run settings based on the project's requirements.

5. **Deploy Your Web Application:**
   - Review your configuration and click the "Create Service" or "Deploy" button. Render will build and deploy your application.

6. **View Your Deployed Application:**
   - Once the deployment is complete, you can access your live application by visiting the provided URL.

   ```bash
   https://tasks-todo-list.onrender.com
   ```

7. **Monitor and Manage Your Service:**
   - In the Render dashboard, you can monitor your service's performance, view logs, and scale your resources as needed.

8. **Scale and Configure:**
   - Depending on your project's requirements, you can scale your service up or down, add background workers, and configure other settings through the Render dashboard.

## Screenshots

![image](https://github.com/Rhythmic-1/Tasks-List/assets/87231338/2483ff1c-2bfb-404a-8889-ff3c7db24b5b)


Remember that this is a simplified overview, and the exact steps may vary depending on your specific requirements and the Render region you are using. Always follow best practices for security and performance when deploying to production environments.

## Deploying Simple Todo List Web App with Tailwind CSS and JavaScript on Vercel(PAAS)

Deploying a Simple Todo List Web application to a Vercel instance involves several steps. Here's a general guide on how to do it:

**Deployment link:** [https://tasks-list-sooty.vercel.app/](https://tasks-list-sooty.vercel.app/)
![image](https://github.com/Rhythmic-1/Tasks-List/assets/87231338/98b43d65-234f-4f9e-a8f9-b5063cdfdd82)

1. **Sign Up for Vercel:**
   - If you don't already have a Vercel account, sign up at Vercel's website.

2. **Install the Vercel CLI (Command Line Interface):**
   - You can use the Vercel CLI to deploy your project from your local development environment. Install it using npm (Node Package Manager) if you haven't already:

   ```bash
   npm install -g vercel
   ```

3. **Log In to Vercel:**
   - In your terminal, log in to Vercel using the CLI by running:

   ```bash
   vercel login
   ```
   - Follow the prompts to log in with your Vercel account.

4. **Prepare Your Project:**
   - Make sure your project is version-controlled (e.g., with Git) and has the necessary files for deployment. Vercel is especially good for front-end projects and Jamstack applications.

5. **Deploy Your Project:**
   - Navigate to your project's root directory in the terminal and use the vercel command to deploy it:

   ```bash
   vercel
   ```
   - The Vercel CLI will guide you through the deployment process. You'll be prompted to configure your project and set deployment options.

6. **Custom Domains (Optional):**
   - If you have a custom domain, you can add it to your Vercel project during the deployment process or later via the Vercel dashboard.

7. **SDeployment Settings:**
   - Vercel provides various deployment settings and options that you can configure to suit your project's needs. These include deployment branches, deployment triggers, and more. You can configure these settings through the Vercel dashboard or by using the Vercel CLI.

8. **View Deployment Status:**
   - Once your project is deployed, Vercel will provide you with a URL where your project is accessible. You can also check the deployment status and logs in the Vercel dashboard.

9. **Continuous Integration (Optional):**
   - You can set up continuous integration with services like GitHub, GitLab, and Bitbucket to automate deployments when you push changes to your repository.

10. **Scaling (Optional):**
    - Vercel provides automatic scaling for your project. If your project experiences increased traffic, Vercel will automatically scale your application to handle the load.

## Screenshots

![image](https://github.com/Rhythmic-1/Tasks-List/assets/87231338/34aa8513-4226-4e73-85bd-808186b0a3cc)

This is a general guide, and specific configurations may vary based on your application's requirements and Vercel region. Ensure you follow best practices for security, performance, and scalability when deploying to a production environment.
