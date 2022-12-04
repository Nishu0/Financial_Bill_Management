# Financial_Bill_Management
FBM is Open-Source Bill Management Web App.

![Financial Bill Management](https://user-images.githubusercontent.com/89217455/205477915-a70819c8-7dce-4118-a9ed-a4e76be0f38c.jpg)


<div align="center">
  
![License](https://img.shields.io/badge/License-MIT-737CA1?style=flat-square) 
![Node_Badge](https://img.shields.io/badge/Node-16.7.13-green?style=flat-square)
![Npm_Badge](https://img.shields.io/badge/npm-6.14.12-yellow?style=flat-square)
![React Badge](https://img.shields.io/badge/React-18.0.0-45b8d8?style=flat-square)
![TypeScript_Badge](https://img.shields.io/badge/TypeScript-%5E4.4.2-363636?style=flat-square)
[![Made by Nisarg Thakkar](https://img.shields.io/badge/made%20by-NisargThakkar-blueviolet?style=flat-square)](https://www.linkedin.com/in/nisarg-thakkar-08811a21a)
</div>

# Summary

- [About](#about-project)
- [Architecture and Client-side Flow](#architecture)
- [Features](#features)
- [Built with](#built-with)
- [Development Challenges](#development-challenges)
- [Wishlist](#wishlist)
- [Contribution Guidelines](#contribution-guidelines)
- [Local Depolyment](#how-to-run)
- [Troubleshooting](#troubleshooting)


<a id='about'/>

## About Project

It is a web application created with the web in mind. It is intended to meet the needs of the user by lessening their effort in paying the payment. The software encourages corresponding users to assist in determining who owes whom what and for what. To give users the finest means of making it simple for them and their companion to split costs. This application will enable group users and their friends to view individual costs in detail inside the app and to pay for them via payment gateways.
Made with ReactJS, Typescript, NodeJS, and TailwindCSS.

Motive/Idea:: Users frequently experience problems when sharing among themselves, which inspired the idea for this application. The division of expenses among the group may be confusing, and maintaining personal spending is a major worry. Sticky notes were used by common people, spreadsheets were used by professionals, and ledgers were used to keep track of significant sums of money in the past. Consistency of the data, the chance of missing crucial inputs, and the possibility of human error are still problems. Data recorders are not always readily available, and it could take some time to gain a complete picture of those fees.
This application is clever enough to demonstrate who owes whom. And how much more? " By enabling online payment gateways, this application will also enable transactions.

<a id='architecture' />


## Features

The user can perform the following actions on this Financial Bill Management:

#### Sign Up/In

This application will include a user login screen and a registration option. When using this programme for the first time, the user must register. However, a user who has already registered can access the application by entering the login credentials they made when registering.

#### Managing Groups

The user of this programme has the choice to either establish a new group or modify an existing group that their friend has already created and added to. Only the person who created the group will be able to add members and remove them from the group.

#### Tracking Expenses

Each group member has the ability to add expenses as necessary. Each entry should include information such as the date the item occurred, the item's cost and who paid it, etc. There is a form for entering the cost and choosing the members who were involved in the expense when adding an expense. The mechanism will distribute the cost equally among the chosen members. Following the split, the record will be saved and made available to all group members. Each participant in the expense split transaction will be listed, and an option to pay your friends will also be present.


## Built With

This project was developed with the following technologies:

#### **Frontend** <sub><sup>React + JavaScript + Next.js</sup></sub>
  - [React](https://pt-br.reactjs.org/)
  - [Axios](https://github.com/axios/axios)
  - [Redux](https://redux.js.org/)
  - [TailwindCSS](https://tailwindcss.com/)

#### **Backend** <sub><sup>Express</sup></sub>
  - [Express](https://expressjs.com/pt-br/)

## Development Challenges

- Updating Expenses Cards after an action was performed.
- Provinding a way to invite new members in a group.
- Keeping tracks of every expenses and updating in real time.

## Contribution Guidelines

Is there is anything missing any of your favorite features, which you think you can add to it❓ I invite you to contribute to this project and make it better. To start contributing, follow the below guidelines:

**1.** Fork [this](https://github.com/Nishu0/Financial_Bill_Management) repository.

**2.** Clone your forked copy of the project.

```
git clone https://github.com/Nishu0/Financial_Bill_Management.git
```

**3.** Navigate to the project directory :file_folder: .

```
cd Go-with-flow
```

**4.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/Nishu0/Financial_Bill_Management.git
```

**5.** Check the remotes for this repository.

```
git remote -v
```

**6.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream main
```

**7.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**8.** Perfom your desired changes to the code base.

**9.** Track your changes:heavy_check_mark: .

```
git add .
```

**10.** Commit your changes .

```
git commit -m "Relevant message"
```

**11.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**12.** To create a pull request, click on `compare and pull requests`.

**13.** Add appropriate title and description to your pull request explaining your changes and efforts done.

**14.** Click on `Create Pull Request`.

**15** Voila :exclamation: You have made a PR to the nft-marketplace :boom: . Wait for your submission to be accepted and your PR to be merged.

<br />

## How to run

- Copy `.env.local.example` to `.env.local` and fill it with environment variables
- Install the `node_modules` with `yarn install`
- Start both the servers on the different servers. For frontend run `yarn start` and for backend run `yarn dev`
- Make sure to add `.env` file in both the frontend and backend project. (Check the Readme for the `.env.example`)
- Update the local `.env` file accordingly. Open an issue thread if any error occurs.



## :mailbox_with_mail: Get in touch!

<p align="center">
<a href="https://www.linkedin.com/in/nisarg-thakkar-08811a21a" target="_blank" >
  <img alt="Linkedin - Nisarg Thakkar" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a>
<a href="mailto:itsnisargthakkar@gmail.com" target="_blank" >
  <img alt="Email - Natalie Bravo" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail">
</a> 
<br/>
  Made with :coffee: and ❤️ by <b>Nisarg Thakkar</b>.
<p/>
