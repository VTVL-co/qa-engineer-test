# QA Engineer Test

A deployed version of the app can be found in the link below:

#### https://recipient-sign.netlify.app/

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Tasks (Goal of this test)](#tasks)
- [Remarks](#remarks)

## Description

This is test repo designed for VTVL's QA Engineer hiring. The app itself is very simple has the following functions:

- it would trigger metamask to prompt for **"Connect with MetaMask"**
- user should click **"Connect"** to allow the dapp to read the connected wallet address
- user should copy and paste your connected wallet address to the Input Box **_"Wallet address:"_**
- user can then type any text in the **_"Message:"_** field
- user should click **"Sign the message"** to trigger MetaMask for signing
- upon successful signing, a **_signature string_** will be displayed accordingly
- if user clicks **"Verify the Signature"** button with the same inputs that generates the signature string, a successful toast should display as _"Valid Signature"_
- if user provides a different wallet address / message from the original signature, the toast should display as _"Invalid Signature"_

## Installation

To get your development environment up and running, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/VTVL-co/Recipient-sign
```

2. Install dependencies and run the project

```bash
yarn && yarn start
```

3. The application should now be running on `http://localhost:3001`

<a id="tasks"></a>

## Tasks (Goal of this test)

The aim of this test is to ask the candidate to apply any testing framework / tools to build automated testing in a web3 dapp user flow (interaction with MetaMask)

You are expected to demostrate the following:

- 🧠 Your thought process on how to approach testing this dapp
- 🤖 How you can automate and mimic user interactions wtih a chrome plugin (i.e. MetaMask)
- 📝 Write tests to emulate different user inputs that leads to the intended outputs (Verify Message function)
- 🤓 _(Optional)_ anything that you think would make you stands out for this QA role

### Remarks

The purpose of this test is to see if posses the right skillset and mentaility to the QA role. There is no 100% right or wrong approach to this test. If you encounter any difficulties on running the repo or making your test compatible with this repo, you can always **_write_** things out and demostrate your thought process.

If you have any questions, feel free to reach out lawrence@vtvl.io / tg: [@lawrencehui](https://t.me/lawrencehui).

Happy coding! 💻
