# NFT minting project
## ✨ Project architecture
![demo](.github/architecture.PNG)
![demo](.github/new_explore.png)
## 🍁 Profile / NFT list
![demo](.github/profile.jpg)
## ⚙️ Tech stack
![demo](.github/architecture.jpg)
- Frontend: React, node.js, SCSS
- Ethereum(Rinkeby Testnet), Ganache
- Etc: web3.js, NFT Storage, MetaMask
## 🧰 Get Started
To get this project up and running in your development environment, follow these step-by-step
instructions.
### 📋 Prerequisites
In order to install and run this project locally, you would need to have the following installed on
your local machine.
- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/get-npm)
- [Git](https://git-scm.com/downloads)
### ⚙️ Installation and Run Locally
**Step 0:**
Note :bangbang: the application uses EmailJS in order to send emails using client-side, therefore,
you need to create EmailJS account [here](https://emailjs.com/) and sets the
`VITE_EMAILJS_SERVICE_ID`, `VITE_EMAILJS_TEMPLATE_ID`, and `VITE_EMAIL_JS_ACCESS_TOKEN` environment
variables in `.env` file.
**Step 1:**
Download or clone this repo by using the link below:
```bash
git clone https://github.com/Laniorepsid/Hafedir.git
```
**Step 2:**
Execute the following command in the root directory of the downloaded repo in order to install
dependencies:
```bash
npm install
```
**Step 3:**
Execute the following command in order to run the development server locally:
```bash
npm start
```
**Step 4:**
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
### 📜 Scripts
All scripts are defined in the `package.json` file. Here is a list of all scripts:
| Script             | Action                                      |
| :----------------- | :------------------------------------------ |
| `npm install`      | Installs dependencies                       |
| `npm start`      | Starts local dev server at `localhost:3000` |
| `npm run build`    | Build your production site to `./dist/`     |
| `npm run preview`  | Boot up a local static web server           |
| `npm run lint`     | Run ESLint                                  |
| `npm run ts:check` | Perform type-checking                       |
