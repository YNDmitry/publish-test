
# Project Setup Instruction

This guide will help you set up your JavaScript project using `Vite`, initialize a Git repository, and prepare your project for publication.

## Step 1: Setting Up with `Vite`

Start by creating a new project:
```js
npx create-vite
```

## Step 2: Installing Dependencies

Install the necessary dependencies for your project:

- Using npm:
  ```js
  npm install
  ```
- Using bun:
  ```js
  bun install
  ```

## Step 3: Creating a GitHub Repository

Create a new repository on GitHub for your project.

## Step 4: Initializing the Git Repository

Initialize a Git repository in your project and link it with the one created on GitHub:
```js
git add .
git commit -m "initial commit"
git remote add origin git@github.com:username/repository_name.git
git push -u origin master
```

## Step 5: Configuring `package.json`

Make the following changes in the `package.json` file:

1. Set the `"name"` field to be the same as your project's name.
2. Create a new `"config"` object inside the file.
4. Add `"ghUserName": "<username>"` and `"repositoryName": "<your repository name>"` and `"browser": "<browser>"` to `"config"` Available browsers **choise 1!!!** [chrome, chromium, opera, opera_gx, brave, arc, edge, vivaldi, firefox, librewolf, safari].
5. For WebStorm users: you can add a publication script directly in the project. Add `"sh <path to publish.sh>"` to `"build"`.

   To get the path to the file, drag it into the terminal, copy the path, and insert it into the settings.

## Step 6: Preparing for Publication

Before publishing, make sure you are logged into your account on the corresponding site.

## Step 7: Building the Project

Start the project build process using the following command in the terminal:
```js
npm run build 
// or
bun run build
```

Available language versions: [English](README.md), [Русский](README_RU.md).
