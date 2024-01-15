# TypeScript Tutorial #02 - How to Install TypeScript?

<p align="center">
  <img src="https://cdn.educba.com/academy/wp-content/uploads/2019/03/How-to-Install-Typescript-2.jpg" alt="TypeScript Logo" width="800"/>
</p>

## TLDR

This file explains the installation and setup process of TypeScript on a local machine, including the use of Node.js and Visual Studio Code, and the compilation of TypeScript code into JavaScript.

## Key Insights

- TypeScript needs Node.js and Visual Studio Code for installation and setup.
- TypeScript is installed globally to use the TSC command anywhere in the terminal.
- The TSC command is used to compile TypeScript code into JavaScript code, and any errors are shown in the terminal.
- TypeScript provides a configuration file (TS config) to customize compiler settings.

## Main Part

### Installation and Setup of TypeScript

#### Installation Requirements

Node.js and Visual Studio Code need to be installed to use TypeScript.

TypeScript provides a playground for writing and testing TypeScript code without explicit commands.
[Visit TypeScript Playground](https://www.typescriptlang.org/play#code%2FDYUwLgBAtiDOsEMDmIBcswCcCWA7JAvAEQASIwwA9gDQQAqAngA5wDGOTYAdFwIREAoVpVyxKoLlSQAKGPGQgAlEA)

#### Global Installation of TypeScript

TypeScript is installed globally to use the TSC command in the terminal.

**Commands:**
```bash
# Install TypeScript globally
npm i -g typescript

# Check TypeScript version
tsc -v

The TSC command compiles TypeScript into JavaScript, and any errors are displayed in the terminal.

# To compile the file
tsc filename

TypeScript provides a TS config file to customize compiler settings for project requirements.

# To create TS config file
tsc --init




