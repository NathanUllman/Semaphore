# Semaphore

A Semaphore

Guide: https://cdkworkshop.com/20-typescript/20-create-project

## How to Setup Project

1. Pull down Project

```
mkdir Semaphore
git init
git pull https://github.com/NathanUllman/Semaphore.git
```

Note that when you are prompted for your password, you need to enter a personal token which can be received by following [this guide](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

2. Install cdk CLI

```
npm install -g aws-cdk
```

## To Deploy

1. Authenticate with your AWS Account using the CLI
2. If using a new account, Update the S3 bucket name TODO
3. If new account, do `cdk bootstrap` in the cdk folder
4. Build the website/semaphore react app using `npm run build`
5. Deploy by running `cdk deploy` in the cdk folder, you can now view the cloudfront url (e.g. https://d29kj88f4q5wq4.cloudfront.net/)

## Helpful commands

To change the node version

```
bash install nvm
source ~/.nvm/nvm.sh
nvm use 17.3.0
```

To change permissions for a file so it is an executable

```
chmod +rwx nate
```
