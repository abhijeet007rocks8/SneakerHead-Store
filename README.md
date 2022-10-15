# Sneaker-Head Store

![mylogo.png](./logoW.webp)

### Participants

Github : [@abhijeet007rocks8](https://github.com/abhijeet007rocks8) [@manisha-27](https://github.com/manisha-27)

Twitter : [@Abhijeet Chatterjee](https://twitter.com/Abhijee58090064) [@Manisha Singh](https://twitter.com/Manisha87672782)

Discord : Abhijeet#1624  ||  Macsia#7113

### Description
We have created a **Web-Storefront for Sneakers and Sports Shoes** <br/> 
using NextJs paired with MedusaJs

### Preview

Demo Video:
https://user-images.githubusercontent.com/64676594/195950378-61a5f101-88c2-4412-97b6-284cbb63c33f.mp4

ScreenShots:

![Screenshot (244)](https://user-images.githubusercontent.com/64676594/195950548-361eece7-16c2-49e3-a049-39dc934dc231.png)
![Screenshot (245)](https://user-images.githubusercontent.com/64676594/195950551-71c0cbb0-d5ac-41ec-b2a2-83aece8dddcd.png)
![Screenshot (246)](https://user-images.githubusercontent.com/64676594/195950552-1c97bbd6-fa6b-4431-a5e1-e1cff10cf8ce.png)
![Screenshot (247)](https://user-images.githubusercontent.com/64676594/195950555-8365a54d-5deb-4eb2-8f72-f424223b0e2a.png)
![Screenshot (248)](https://user-images.githubusercontent.com/64676594/195950560-8b97d5a7-4719-4d49-baa6-32b2a828b7b2.png)
![Screenshot (249)](https://user-images.githubusercontent.com/64676594/195950563-c33cac3b-2263-4286-908a-b10d777dec5a.png)
![Screenshot (250)](https://user-images.githubusercontent.com/64676594/195950569-1f158ff2-8fb2-4044-aeb9-6607fd0f23e6.png)


## Set up Project
Here's how to setup and run the project locally :

### Prerequisites
- Medusa CLI (```npm install -g @medusajs/medusa-cli```) .
- Node (https://node.org/)
- yarn (https://yarnpkg.com/)


### Install Project
1. Clone the repository:

```bash
git clone https://github.com/abhijeet007rocks8/SportsFactory.git
```

2. Change directory and install dependencies:

```bash
cd SneakerHead-Store
cd Backend
medusa develop
```
Open another terminal using path of cloned repository
```bash
cd frontend 
yarn install
yarn dev
```

3. (Optional)
To setup a new store 
```bash
medusa new my-medusa-store --seed
```

To use exiting Seed file in DB
```bash
medusa seed -f ./data/seed.json
```

## Resources
Here are some technologies that proved to be very useful throughout the process :

- [Medusa’s GitHub repository](https://github.com/medusajs/medusa)
- [How to Create Services](https://docs.medusajs.com/advanced/backend/services/create-service)
- [NextJs](https://nextjs.org/)
