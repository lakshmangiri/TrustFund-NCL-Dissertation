BLOCKCHAIN BASED CHARITY WEB APPLICATION
--------------------------------------------------

About:
    This is a web application that allows users to donate cryptocurrency to the charities.

Demo:
    The application can be found live in the following link: https://keen-lokum-06e111.netlify.app/home

The application has been hosted in the Netlify, a open source and free platform to host web application.

Libraries/Frameworks used:
--------------------------------------------------

1. ReactJs:
    React is a free and open-source front-end JavaScript library for building user interfaces based on components. React can be used to develop single-page, mobile, or server-rendered applications

2. Web3Js:
    A library that allow developers to interact with a remote or local Ethereum node using HTTP, IPC, or WebSocket. Using this library, you can develop websites or clients that interact with the blockchain.

3. ThirdWeb:
    Thirdweb offers software development kits (SDKs) that allow seamless integration with your smart contract when developing applications or games using popular programming languages such as React, React Native, TypeScript, Python, Go, and Unity.

4. Hardhat:
    It's a flexible and extensible task runner that helps you manage and automate the recurring tasks inherent to developing smart contracts and dApps. Hardhat is a development environment for Ethereum software. It consists of different components for editing, compiling, debugging and deploying your smart contracts and dApps, all of which work together to create a complete development environment

5. Solidity:
    Solidity is an object-oriented programming language for implementing smart contracts on various blockchain platforms, most notably, Ethereum. Solidity is licensed under GNU General Public License v3.0.

6. ViteJs
    Vite is a frontend tool that is used for building fast and optimized web applications. It uses a modern build system and a fast development server to provide a streamlined and efficient development experience. Used ny default in Vue and React project templates.

7. Tailwind CSS
    Tailwind CSS is an open source CSS framework. The main feature of this library is that, unlike other CSS frameworks like Bootstrap, it does not provide a series of predefined classes for elements such as buttons or tables. A utility-first CSS framework packed with classes like flex, pt-4, text-center and rotate-90 that can be composed to build any design, directly in your markup.

8. Ethers
    Ethers. js is a JavaScript library for Ethereum Blockchain development. It provides a simple and easy-to-use interface for interacting with Ethereum smart contracts. It supports contract deployment, function calls, and events handling.

Building and Deploying Smart Contract using Thirdweb
--------------------------------------------------

1. Install Nodejs, NPM & Git on your system if not already installed

2. Write you Smart Contract

3. Get the private key from the Development MetaMask account

4. Create a .env file and add the private key there and use the .env file in hardhat.config.js file

5. npm run deploy

6. Navigate to the thirdweb url, connect your development wallet, confirm the transcation by selecting deploy.

7. Your contract is deployed.

NPM packages
--------------------------------------------------

1. npx thirdweb@latest create --contract (This will create a plain smart contract)
2. npm install dotenv
3. npx thirdweb create --app
4. npm install react-router-dom
5. npm install -D tailwindcss postcss autoprefixer
6. npx tailwindcss init -p
7. npm install --save-dev jest @testing-library/react @testing-library/jest-dom
8. npm install jest-environment-jsdom
9. npm install identity-obj-proxy --save-dev
10. npm install --save-dev @babel/preset-react @babel/plugin-transform-runtime (Babel to transcript jsx to js)
11. npm install -D vitest
12. npm i -D jsdom @testing-library/react


To Test
--------------------------------------------------


To Build
--------------------------------------------------

cd client && npm run build

Copy the build folder (dist) to the netlify. This will upload the build folder and will be deployed with an random url.
