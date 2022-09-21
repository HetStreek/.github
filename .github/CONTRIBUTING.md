# Contributing

If you'd like to contribute to this project, feel free to submit a pull request!

## Setup

First things first, fork and clone the main branch of this repository. Then, open the project folder and run `npm ci` to install dependencies and set up environment.

Next, create a .env file in your project root and add the necessary environment variables. You can find the required variables in the `.env.example` file, along with explanations how to obtain them.

## Coding and testing

Once you have the project set up, you can start coding!

While coding, you can always test it by doing the following:

1. Make sure all of your code is saved.
2. Open a terminal in the project folder.
3. Run `npm run dev` to start the bot.
4. If you make any other changes and save it, the bot will restart with the new changes.

## Commit and push

> Make sure to follow the [commit message convention](./COMMIT_CONVENTION.md).

When you are done coding, run `npm test` and make sure there are no linting errors. If there are, please resolve them and try again. You can run `npm run lint:fix` to automatically fix some linting errors. When everything works fine and there are no linting errors, you can commit and push your code and open a pull request!
