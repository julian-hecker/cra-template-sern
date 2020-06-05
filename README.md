# cra-template-sern
Highly opinionated Template for creating full stack applications with Sequelize, Express, React, and Node.

Designed to be hosted using Heroku.

## Usage
```bash
npx create-react-app my-app --template sern
```

## Output

```bash
project-root
├───public/ # static files for react app
│   ├───favicon.ico # icon displayed in browser tab
│   ├───index.html # includes all js
│   ├───logo192.png 
│   ├───logo512.png
│   ├───manifest.json # used in PWAs
│   └───robots.txt # specifies web crawler rules
├───server/ # backend
│   ├───bin/ # server executable
│   ├───config/ # database config
│   ├───controllers/ # functions 
│   ├───models/ # database models
│   ├───routes/ # api routes
│   ├───utils/ # shared functions
│   └───index.js # main server file
├───src/ # react source files
│   ├───components/ # reusable components
│   │   ├───Footer/ 
│   │   └───Navbar/
│   ├───routes/ # Router and pages go here
│   └───index.js # Main Entry Point
├───.env # store environment variables
├───.env.example # share env keys without exposing values
├───.gitignore
├───.prettierrc.json # prettier plugin configuration
├───package-lock.json
├───package.json # dependencies, scripts
└───README.md # guide
```


## Create your own template
Follow the guide at the [Create React App Documentation](https://create-react-app.dev/docs/custom-templates/) to create your own `create-react-app` template