<h1 align='center' >
🪐 LLM React App Javascript Template 🪐
</h1>
<p align='center'>
    <a href='https://github.com/golivecosmos/pluto/blob/main/LICENSE'>
        <img src='https://img.shields.io/github/license/golivecosmos/llm-react-node-app-template?style=plastic' alt='License' />
    </a>
    <a href='https://github.com/golivecosmos/llm-react-node-app-template'>
        <img src='https://img.shields.io/github/commit-activity/w/golivecosmos/llm-react-node-app-template?style=plastic' alt='Cosmos'              style='margin-right:3px' />
    </a>
     <a href='https://twitter.com/golivecosmos'>
       <img src='https://img.shields.io/twitter/follow/golivecosmos' alt='Cosmos' style='margin-right:3px' />
     </a>
</p>

## What is an LLM React Node App Javascript Template?

This template is an example project for a simple Large Language Model (LLM) application built on top of React and Node. This template was built on top of [the React template app from nano-react-app](https://github.com/nano-react-app/template-js) and updated with a Node server that uses [LangChain.js](https://github.com/hwchase17/langchainjs) to connect to supported large language models, e.g. OpenAI and Hugging Face. Use this template to easily build and run an LLM app, like the screenshot below:

![screenshot of LLM react app](./examples/llm-react-app.webp)

## Getting Started

To get started, follow the below steps:

1. Create an `.env` file by copying the `SAMPLE_env` file and add API keys for the models you are going to use
1. Install packages
1. Run the backend server that will start with a default port of `3100`
    ```bash
        yarn start-server
    ```
1. Run the frontend server that will start with a default port of `5173`.
     ```bash
        yarn start
    ```
   
    _Note:_ You can use the `-p` flag to specify a port for the frontend server. To do this, you can either run `yarn start` with an additional flag, like so:
    ```bash
        yarn start -- --port 3000
    ```

    Or, edit the `start` script directly:

    ```bash
    vite --port 3000
    ```
    
Additional scripts are provided to prepare the app for production
- `yarn build` — This will output a production build of the frontend app in the `dist` directory.
- `yarn preview` — This will run the production build of the frontend app locally with a default port of `5173` (_note_: this will not work if you haven't generated the production build yet).


👽 If you're looking for more thorough instructions follow [this tutorial on running an LLM React Node app](https://blog.golivecosmos.com/build-an-llm-app-with-node-react-and-langchain-js/). 📚

-------------

## Shout out to the ⭐star gazers⭐ supporting the project
[![Stargazers repo roster for @golivecosmos/llm-react-node-app-template](https://reporoster.com/stars/golivecosmos/llm-react-node-app-template)](https://github.com/golivecosmos/llm-react-node-app-template/stargazers)
