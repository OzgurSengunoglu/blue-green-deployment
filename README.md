# blue-green-deployment via ALB

Using Application Load Balancers for Blue-Green and Canary Deployments  

1- Provised underlying resources (VPC, security groups, load balancers) and a set of web servers to serve as the blue environment.  
2- Provised a second set of web servers to serve as the green environment.  
3- Added feature toggles to your Terraform configuration to define a list of potential deployment strategies.  
4- Used feature toggles to conduct a canary test and incrementally promote your green environment.  



