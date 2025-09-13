1. Create a security group using http port 80, and ipv4 port 22. Name security group
2. Create a instance by first naming, then select Ami, create a keypair for SSH
3. Select security group that was already created
4. Scroll down to advance details until reaching advanced details, open section
5. Move down to the section User Data
6. Use escript by copying and pasting from github repo
7. Click create instance


Teardown
Go to EC2 instance, and select terminate instance
After instance has terminated, go to Security group section
Delete Security group associated with terminated instance
