# bookStore
[![Language](https://img.shields.io/badge/Language-Javascript-blue.svg?style=flat)](https://www.javascript.com/)
[![Framework](https://img.shields.io/badge/Framework-Vite+Reactjs-purple.svg?style=flat)](https://vitejs.dev/)
####
Visit [here](https://bookstore-qh90.onrender.com/) to have a look at this website.

## Environmental Setup 
- The website is developed in VS Code.
#### How to setup in local environment
- Download and install a code/text editor.
  - Recommended -
    - Download [VS Code](https://code.visualstudio.com/download)
    - Download [Atom](https://atom.io/)
- Download [Node Js and npm(Node package manager)](https://nodejs.org/en/) (npm gets installed by default on downloading Node)
- Clone the repository by running the command:
```
git clone https://github.com/namanrox/bookstore.git
```
in your GitBash or terminal of VS Code.

- Run the command `cd server`
- Run `npm install nodemon mongoose dotenv express bcryptjs cors` to install all the required dependencies for server side.
- Go to package.json file and add ```"start": "node index.js"```
  ```"dev": "nodemon index.js"``` ```"build": "npm install && npm install --prefix client && npm run build --prefix client"``` inside scripts.
- Now, run the command `cd client`
- Run `npm install axios prop-types react-hook-form react-hot-toast react-router-dom react-slick slick carousel` to install all the required dependencies for client side.
- Also, add devDependencies `daisyui postcss tailwindcss vite`
- Run `npm run dev` to start the client and server both.
- Check for `App started at port {provider}` to know whether the port is connected.
- Now you are set to use it locally.

## Reference Images
![home-light](https://github.com/namanrox/bookstore/blob/master/assets/home-light.png)

![home-dark](https://github.com/namanrox/bookstore/blob/master/assets/home-dark.png)

<img src="https://github.com/namanrox/bookstore/blob/master/assets/login.png" alt="login" width="50%" height="50%" />  <img src="https://github.com/namanrox/bookstore/blob/master/assets/signup.png" alt="sign-up" width="40%" height="40%" />
