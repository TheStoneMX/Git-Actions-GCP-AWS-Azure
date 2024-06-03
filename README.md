# Git-Actions-GCP-AWS-Azure
## Example Github Actions Project designed to show how to connect to all three mayor shell



![GitActions](https://github.com/TheStoneMX/Git-Actions-GCP-AWS-Azure/blob/1c5a47ef8d601eed2a7fa2be88cb3be661fa9a3a/%20An%20illustration%20of%20continuous%20integration%20with%20Git%20actions%20connecting%20the%20three%20major%20cloud%20platforms_%20Google%20Cloud%20Platform%20(GCP)%2C%20Amazon%20Web%20Service.webp)


### Go to each shell and create a virtual environment: 
    python3 -m ~/.venv; 
    source ~/.venv/bin/activate

    0.- need to create keys for each cloud provider to communicate :
    1.- ssh-keygen -t rsa # keys are saved to /home/{user_name}/.ssh/id_rsa.pub
    2.- print out the key cat /home/{user_name}/.ssh/id_rsa.pub
    3.- then create a new key by copying the key and paste in the GitHub menu-->settings->SSH & GPC Keys
    4.- this has to be done by each provider
    5.- Copy from the menu "code-local-" git@github.com:TheStoneMX/Git-Actions-GCP-AWS-Azure.git to each provider shell
    6.- makefile all
    7.- Create Triggers to be notified when the source code changes so it will recompile the code, generate the Docker file, and push it to Kubernetes
    
