# HelloWorld-to-GithubActions-using-Azure
This repo contains a basic hello world to github actions (CI/CD pipeline) using azure to deploy a web app.

Also a secret key is passed by the pipeline to index.html `${secret-value}`,
I set the `${secret-value}` to `SECRET_VAlUE`.

A sanity check is added after deployment to check if deployment went fine or not.

**It can be further improved by:**
1) Using a Matrix for Branches, If we have multiple branches that need similar workflows, consider using a matrix strategy to avoid duplicating job definitions.

2) Using kubernetes depending on the environment and inreasing/decreasing number of pods depending on load.

3) Using Environment Variables for commonly used values to make workflow more readable and maintainable. This can include the Azure Static Web Apps API token and the URL for deployment.

**You can see the application deployed at url:** https://witty-grass-09a172510.3.azurestaticapps.net/

![image](https://github.com/AitzazTahirCh/helloworld-to-GithubActions-using-Azure/assets/72460814/a7f6467e-7d23-4d27-9705-61ba9450b8c6)
![image](https://github.com/AitzazTahirCh/helloworld-to-GithubActions-using-Azure/assets/72460814/3c353154-e7e0-4bb2-8f18-a7a84667f5ce)
![image](https://github.com/AitzazTahirCh/HelloWorld-to-GithubActions-using-Azure/assets/72460814/171d57b2-e100-428c-bed2-f6a2b1f8b5fe)
