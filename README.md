Activité pratique N° 5 : Mise en oeuvre d'une architecture micro-service
Objectif :  
La création une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.

## Première Partie 
1.Créer le micro-service customer-service qui permet de gérer les client

![1](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/3872f7df-1d84-452f-9670-f51ceb3adddf)
![2](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/b0004c79-c7f4-4cfb-b9a5-6bb566bd3992)
### Customer H2 Console :
![3](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/8bd5ccdd-033c-42a9-b222-d360b02ea15c)
### Actuator : 
![actuator](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/4d3e7bf1-fcf0-4312-9b42-f1297b328393)
### Actuator Env :
![env](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/dcdd6567-4cd6-4525-b926-e4159e83fc4c)
### Actuator Beans :
![beans](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/d13b7feb-205e-4e53-903a-717d4cb04eec)
2.Créer le micro-service inventory-service qui permet de gérer les produits


![p2](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/b9a67d6d-b85c-457e-b4ae-161f8aa35698)
![p22](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/f07dd1ae-de9f-42a7-b748-39b0952a108f)
### Product H2 Console :

![P23](https://github.com/SanaeBelfrouh/Activit-pratique-N-5-Mise-en-oeuvre-d-une-architecture-micro-service/assets/116807307/8c46c3b0-a826-4986-8fee-febb40ffb7d2)

### Customers with gateway : 
![customers 8888](https://user-images.githubusercontent.com/86847138/200060024-cdac0216-3801-4944-bf5f-3157a8980def.PNG)


### Products with gateway : 
![products 8888](https://user-images.githubusercontent.com/86847138/200060063-dc514efb-1641-44bc-9e37-1f7d0ffa6180.PNG)


### Id :

![products 8888 id](https://user-images.githubusercontent.com/86847138/200060118-2a85d4f4-27c2-45bf-8276-861e5d1f1f8b.PNG)

### Eureka before enabling Discovery Service :
![eureka before](https://user-images.githubusercontent.com/86847138/200060276-bff3e8ad-383f-46c7-b8de-fa1f53b46f7e.PNG)



### Eureka after enabling Discovery Service :
![eureka after](https://user-images.githubusercontent.com/86847138/200060309-644371cc-e1a7-40cb-a9ea-4e83ba7bff12.PNG)


### Customers with id using the Web Service :

![CUSTOMER SERVICE](https://user-images.githubusercontent.com/86847138/200060405-2f2684d3-92c3-41fb-88a8-4d3910bc5c69.PNG)

## Deuxième Partie : 

### H2 Console Bill :
![h2 console bill](https://user-images.githubusercontent.com/86847138/200087300-68a674d4-4308-4775-8363-2fb78ac3cded.PNG)




### H2 Console Product Item : 
![h2 console product item](https://user-images.githubusercontent.com/86847138/200087326-069e0b07-5d23-473f-9fb3-4c4810432c91.PNG)



### Billing Service toutes les données :
![billing-service all data](https://user-images.githubusercontent.com/86847138/200087372-36bbc5a6-3876-47dd-827a-5068c19c7640.PNG)



### Billing Service selon la donnée dont on a besoin : 
![billing-service selo le besoin (name)](https://user-images.githubusercontent.com/86847138/200087460-274e02b2-2c3a-4e82-8319-53d9494e7404.PNG)

### Billing Service toutes les données :
![billing-service all data](https://user-images.githubusercontent.com/86847138/200087372-36bbc5a6-3876-47dd-827a-5068c19c7640.PNG)



### Billing Service selon la donnée dont on a besoin (name dans le screenshot) : 
![billing-service selo le besoin (name)](https://user-images.githubusercontent.com/86847138/200087460-274e02b2-2c3a-4e82-8319-53d9494e7404.PNG)








