🚀 Project Showcase: Production-Ready Flask Deployment on AWS EC2 (Gunicorn + Nginx)

Excited to share my hands-on project where I deployed a Python Flask application on AWS EC2 using a production-grade architecture with Gunicorn and Nginx.

Instead of using the default Flask development server, I implemented a scalable and secure setup commonly used in real-world environments.

🔧 What I built:

✅ Launched Amazon EC2 (Amazon Linux 2023)
✅ Configured Security Groups for HTTP/SSH access
✅ Connected securely using SSH key pair
✅ Developed a simple Flask web application
✅ Installed and configured Gunicorn as WSGI server
✅ Set up Nginx as reverse proxy
✅ Enabled Nginx service with systemctl
✅ Verified public access via EC2 Public IP

⚙️ Tech Stack:
 • AWS EC2
 • Python 3
 • Flask
 • Gunicorn (WSGI server)
 • Nginx (Reverse Proxy)
 • Amazon Linux 2023
 • Linux CLI

🌐 Architecture Flow:

User Browser → Internet → Nginx (Port 80) → Gunicorn (Port 5000) → Flask App → Response back to User

💡 Key Learnings:

• Difference between development vs production servers
• Reverse proxy configuration using Nginx
• WSGI server setup with Gunicorn
• Linux service management (systemctl)
• Port management and security groups in AWS
• End-to-end web app deployment on cloud

This project gave me practical exposure to how real production Python applications are deployed in the cloud.
