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
	
 3.	Fetches the latest code.
	
 4.	Deploys the website to GitHub Pages.
	
 5.	Live Deployment → Updates appear instantly.


How to Use


Clone this repository:
        
	git clone https://github.com/Basheer98/ci-cd-static-website
        cd ci-cd-static-website
    
Make changes and push:
        
	git add .
        git commit -m "Updated UI elements"
        git push origin main
	
GitHub Actions will automatically deploy the updated version.

License

This project is released under the MIT License.
