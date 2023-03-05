## Image Scraper Deployment

### Steps
1. Push code to github
2. Create: Web App
```
### I am using azure for deployment
* Create/Select: Resource
* Create: Instance name
* Select; Runtime stack
* Review + Create
* Goto: Deployment
    * Continious Dep: Enable
```
```
## for AWS Follow the following steps
* Create/Select: Elastic beanstalk
* Create: give name
* Select: pipeline service 
* Select: github repo give exact github name and then provide exact github repo name
* Review + Create
* Goto: Deployment
 wait for some time it will atomatically connect with github and creates your web app in 2-3 min
```



* yml file auto created by Azure for deployment
    * .github/workflows/tproj-image_scrap_deploy_image-scrap.yml
    * Delete this if want to deploy again
