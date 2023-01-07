![image](https://user-images.githubusercontent.com/24469318/211132005-11fe4076-d6f1-48ac-92d5-f298cf4dd252.png)

![image](https://user-images.githubusercontent.com/24469318/211132127-6e955f2d-faba-453b-a24c-b06e052d2e1a.png)


![image](https://user-images.githubusercontent.com/24469318/211132159-320cb1ac-256c-4791-b1ca-bf9cd317d4da.png)

![image](https://user-images.githubusercontent.com/24469318/211132168-8c71aeac-1529-4495-9f25-c0811038a15e.png)


![image](https://user-images.githubusercontent.com/24469318/211132179-29f6d83d-a859-4278-ac6d-403a0297815b.png)

az aks create --resource-group readit-app-rg-2023 --name cart-aks --node-count 1 --generate-ssh-keys --attach-acr readitacr2023 --node-vm-size Standard_DS2_v2


az aks install-cli

set PATH=%PATH%;"C:\Users\adibi\.azure-kubectl"

az aks get-credentials --resource-group readit-app-rg-2023 --name cart-aks





