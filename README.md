![GoIndex](https://raw.githubusercontent.com/ceecx/goindex-plus/master/themes/logo.png)  

GoIndex Plus
====  

Modified based on [original](https://github.com/donwa/goindex) and [yanzai/goindex](https://github.com/yanzai/goindex), adjusted for your needs.

Copy the `index.js` code to Cloudflare Workers and modify your information for deployment.

## Preview

Demo: https://dl.cee.cx


## Update log

### 1.0.1 (2020-07-08)

-Modify all static files to jsDelivr CDN to speed up domestic access.
-Modify the default theme color to white.
  

---



> **For installation and deployment, please refer to the original version, the following is taken from the deployment instructions of the original version of GoIndex:**



## Demo  
material: [https://index.gd.workers.dev/](https://index.gd.workers.dev/)  
classic: [https://indexc.gd.workers.dev/](https://indexc.gd.workers.dev/)  

## Deployment  
1.Install `rclone` software locally  
2.Follow [https://rclone.org/drive/]( https://rclone.org/drive/) bind a drive  
3.Execute the command`rclone config file` to find the file `rclone.conf` path  
4.Open `rclone.conf`,find the configuration `root_folder_id` and `refresh_token`  
5.Download index.js in https://github.com/donwa/goindex and fill in root and refresh_token  
6.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)

## Quick Deployment  
1.Open https://installen.gd.workers.dev/  
2.Auth and get the code  
3.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)  



## About  
Cloudflare Workers allows you to write JavaScript Code which runs on all of Cloudflare's 150+ global data centers.  
