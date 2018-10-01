# react-js-boilerplate

ReactJS boilerplate using ejected create-react-app. Integrated with node-sass and breakpoints for easier way to make responsive design

## GETTING STARTED

#### Step 1: Clone this repo

Clone this repo by running:

```sh
git clone https://github.com/aviedb/react-js-boilerplate.git
cd react-js-boilerplate
```

#### Step 2: Install dependencies

Install dependencies by running:

```sh
yarn
```

> NOTE: If you prefer to use npm, you can run `npm install`

## Running the project

Running the project is as simple as running:

```sh
yarn start
```

> NOTE: If you prefer to use npm, you can run `npm run start`

> Typically the server runs at http://localhost:3000, but should be automatically opened for you.

## Testing the project

Testing is also a command away:

```sh
yarn test
```

> NOTE: If you prefer to use npm, you can run `npm run test`

> This command runs Jest, an incredibly useful testing utility, against all files whose extensions end in `.test.js` or `.spec.js`. Like with the `yarn start` command, Jest will automatically run as soon as it detects changes. If you'd like, you can run `yarn start` and `yarn test` side by side so that you can preview changes and test them simultaneously.

## Creating a production build

When running the project with `yarn start`, we didn't end up with an optimized build.
Typically, we want the code we ship to users to be as fast and small as possible.
Certain optimizations like minification can accomplish this, but often take more time.
We call builds like this "production" builds (as opposed to development builds).

To run a production build, just run:

```sh
yarn build
```

> NOTE: If you prefer to use npm, you can run `npm run build`

> This will create an optimized build in `./build`

> You won't need to run a production build most of the time,
but it is useful if you need to measure things like the final size of your app.
