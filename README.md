# Sneaker-Head Store

![mylogo.png](./logoW.webp)

### Participants

Github : [@abhijeet007rocks8](https://github.com/abhijeet007rocks8) [@manisha-27](https://github.com/manisha-27)

Twitter : [@Abhijeet Chatterjee](https://twitter.com/Abhijee58090064) [@Manisha Singh]()

Discord : Abhijeet#1624  ||  Macsia#7113

### Description
We have created a **Web-Storefront for Sneakers and Sports Shoes** <br/> 
using NextJs paired with MedusaJs

### Preview


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
cd SportsFactory
cd Backend
medusa develop
```
Open another terminal using path of cloned repository
```bash
cd Frontend 
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
