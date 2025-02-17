<p align="center"><img src="https://miro.medium.com/v2/resize:fit:1400/0*H-h0uuA8PHFuQM6a" alt="osTicket logo"/></p>

<h1>Phishing Attack Simulation with Gophish</h1>
This tutorial outlines how to set up Gophish to simulate a phishing attack and employee awareness using Gophish<br/>

<h2>Environments and Technologies Used</h2>

- GitHub
- GoPhish
- Railwawy [Cloud Hosting Service]

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enabling Internet Information Services (IIS) with CGI

<h2>Installation Steps</h2>

<p>The first step is to create a Railway account, sign up using GitHub, and click "Authorize Railway app" when you are redirected. </p>

![image](https://github.com/user-attachments/assets/bd8ee381-32e4-4854-a92b-58edc723cb39)

![image](https://github.com/user-attachments/assets/3b45e2f9-6673-49b1-b74f-0d9eb23e1272)

<h2>Deploy GoPhish</h2>

<p>The second step is go to this link (https://railway.com/new/template/gEmUp6?referralCode=alphasec&ref=alphasec.io) which auto selects the template for Gophish Docker image.</p>

![image](https://github.com/user-attachments/assets/014f843f-1e95-468d-acff-4f50717de589)

<p>Under the Deployments section of the deployed service, click View Logs for the latest deployment, and find an entry similar to Please login with the username admin and the password 0f564e8fxd9171d25. You'll need these credentials to log into the admin server.</p>

![image](https://github.com/user-attachments/assets/520cc1f8-85d1-4e59-9c9c-21e28e9e32ca)

![image](https://github.com/user-attachments/assets/2e11494c-9fb7-4cf8-a1b4-2a38b2b8cb09)

<h2>Run Phishing Attack Simulations with Gophish</h2>

<p>Login to the Gophish admin server using the temporary credentials found in the deployment logs, and change the password upon login. You can access the login page by clicking the link next to the globe which you can see as "gophishgophish-production-obea.up.railway.app"</p>

![image](https://github.com/user-attachments/assets/4c06cacc-eb68-4a33-a7bf-a186c2f2c0b1)

![image](https://github.com/user-attachments/assets/a443e86e-3ed7-4fff-9d90-9ffbf13424f3)

![image](https://github.com/user-attachments/assets/5239dddb-a335-49ee-a306-4180f8d5ae4c)

<p>Now that you have a functional setup, play around with the various settings to generate realistic (in your context) phishing templates. In the minimum, you'll need to configure:

- Users & groups to send the simulated phishing emails
- Phishing email templates, including attachments
- Sending profiles to specify sending SMTP relay details
- Landing pages returned to users when they click the phishing links</p>

![image](https://github.com/user-attachments/assets/636cf006-92b6-4b5a-b7e5-3c53e03bf731)

<h2>Configuring Users & Groups</h2>
