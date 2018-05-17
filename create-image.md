### 1. Create a server with Centos7 Image.
### 2. Run the following commands
```
# yum update -y
# curl -s https://raw.githubusercontent.com/cit-astrum/lab-setup/master/vm-init.sh | bash
```
Note: Server will get rebooted.

### 3. Create a image of the server which you created.
  #### a.  Shutdown the server.
  #### b. Go to `Google Cloud Platform` -> `Compute Engine` -> `Images` -> `Create Image`. Provide details as in screenshot.
  ![image](https://user-images.githubusercontent.com/29029753/40151082-627b76c2-599b-11e8-8379-d7c0dc308de5.png)
  #### c. Verify your Image.
  ![image](https://user-images.githubusercontent.com/29029753/40151122-ab0dd150-599b-11e8-8bfa-fb17af708b4b.png)
  #### d. Create a server with new Image.
  ![image](https://user-images.githubusercontent.com/29029753/40151151-e063235a-599b-11e8-8617-defada1f5876.png)
  
  ![image](https://user-images.githubusercontent.com/29029753/40151166-f193fab4-599b-11e8-98f3-4c961fa982f5.png)

  
