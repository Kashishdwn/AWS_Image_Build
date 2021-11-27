# AWS_Image_Build
Build Custom AWS Image

1. Setup Jenkins Server
2. Launch an Ec2-Instance from AWS Console
3. Open port 8080 on security group attached to the instance
4. Login to the Instance
5. Run the script server_installation.sh
6. Open Jenkins Url <Ec2 Public Ip>:8080
7. Setup New User
8. Configure following credentials:
    SSH Key Fingerprint to access github repositries
    AWS Secret and Access Key to launch new instance on AWS
9. Create a new freestyle project
  ![image](https://user-images.githubusercontent.com/56489521/143673343-8ccf2e1f-eec3-45ef-8c1b-1b451fd3a1d2.png)
  ![image](https://user-images.githubusercontent.com/56489521/143673352-21058a74-378d-46fe-9097-371f91f232ac.png)
  ![image](https://user-images.githubusercontent.com/56489521/143673366-9c232da7-eb45-4311-b369-8a5812a54844.png)
  ![image](https://user-images.githubusercontent.com/56489521/143673374-c8e18688-4e2d-4148-b070-495d9e3699e3.png)
10. Trigger a new Build Job
11. ter Successfull completion of build job, you can see your image in aws console
12. you can launch an ec2 instance from your custom AMI
  
UseFull Links:
  https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/
