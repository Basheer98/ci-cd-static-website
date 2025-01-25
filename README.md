CI/CD Pipeline Deployment

This project demonstrates a fully automated CI/CD pipeline that deploys a static website using GitHub Actions & GitHub Pages.

Project Overview

This repository is designed to:
	•	Automate the deployment process using GitHub Actions.
	•	Host a modern static website with GitHub Pages.
	•	Ensure that every push to the main branch triggers an automatic deployment.

How It Works
	1.	Push changes to GitHub → GitHub Actions workflow is triggered.
	2.	GitHub Actions Workflow:
	•	Fetches the latest code.
	•	Deploys the website to GitHub Pages.
	3.	Live Deployment → Updates appear instantly.
How to Use
	1.	Clone this repository:
        git clone https://github.com/Basheer98/ci-cd-static-website
        cd ci-cd-static-website
    
    2.	Make changes and push:
        git add .
        git commit -m "Updated UI elements"
        git push origin main
	
    3.	GitHub Actions will automatically deploy the updated version.

License

This project is released under the MIT License.