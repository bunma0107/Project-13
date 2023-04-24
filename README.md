# Project-13
Introducing Dynamic Assignment Into Our structure.
In your https://github.com/<your-name>/ansible-config-mgt GitHub repository start a new branch and call it dynamic-assignments.

![image](https://user-images.githubusercontent.com/113097621/229086194-fc770699-096b-4b88-90f3-f452eb122333.png)


Create a new folder, name it dynamic-assignments. Then inside this folder, create a new file and name it env-vars.yml. We will instruct site.yml to include this playbook later. For now, let us keep building up the structure.

![image](https://user-images.githubusercontent.com/113097621/229068463-3c87c504-c9d1-4153-856e-984282f565b0.png)

My GitHub now have following structure:
![image](https://user-images.githubusercontent.com/113097621/229069111-96aa711f-f6d8-4a93-b1f6-c8832c03245c.png)


![image](https://user-images.githubusercontent.com/113097621/229069228-ce13ae48-aabd-482d-8050-618df7035763.png)

We paste the instruction below into the env-vars.yml file.
![image](https://user-images.githubusercontent.com/113097621/229074085-34233ffb-7b74-4145-96b2-2edbf5ba77a9.png)


On Jenkins-Ansible server make sure that git is installed with git --version, then go to ‘ansible-config-mgt’ directory and run
![image](https://user-images.githubusercontent.com/113097621/229803816-4a7a9eb6-be8a-4cdd-b748-59e2d2af8286.png)
  
  
Inside roles directory create your new MySQL role with ansible-galaxy install geerlingguy.mysql and rename the folder to mysql
  
  Inside roles directory create your new MySQL role with ansible-galaxy install geerlingguy.mysql and rename the folder to mysql
![image](https://user-images.githubusercontent.com/113097621/233853433-1dc4931c-e70e-407d-a5cc-dba5f5d09b83.png)

![image](https://user-images.githubusercontent.com/113097621/233853704-59d6ed14-1be4-49d5-a726-06f559d69d4e.png)

Uncomment my My Databases and Users
![image](https://user-images.githubusercontent.com/113097621/233857812-4068bc36-65aa-4909-a7c3-1d82021795a6.png)

Load Balancer roles
Load Balancer roles

We want to be able to choose which Load Balancer to use, Nginx or Apache, so we need to have two roles respectively:

    Nginx
    Apache

![image](https://user-images.githubusercontent.com/113097621/234010022-a75484ba-63eb-473c-9958-8133e4e0575c.png)


