## Requirements

### Project Firefly Access

A pre-requisite of the codelab is to have access to [Project Firefly](https://github.com/AdobeDocs/project-firefly) or at least a namespace in Adobe I/O Runtime. 
If you don't have access, please [request trial access](https://github.com/AdobeDocs/adobeio-runtime/blob/master/overview/request_a_trial.md).

### Pre-requisites

- [NodeJS](https://nodejs.org/en/download/) (at least v12). It should also install npm together. We recommend using [nvm](https://github.com/nvm-sh/nvm/blob/master/README.md) to manage NodeJS installation and versions on your machine.  
- [Visual Studio Code (VSCode)](https://code.visualstudio.com/download) as the supported IDE for editor, debuggger, etc. You can use any other IDE as a code editor, but advanced usage e.g. debugger is not yet supported.
- [Docker Desktop](https://www.docker.com/get-started).
- [Java Development Kit (JDK)](https://www.oracle.com/technetwork/java/javase/overview/index.html) (at least Java 11).

### Additional tools for debugging

- [Chrome debugger extension in VSCode](https://github.com/Microsoft/vscode-chrome-debug)

### Command Line Interface

Install the [Project Firefly CLI](https://github.com/adobe/aio-cli) with: 
```bash
npm install -g @adobe/aio-cli
```     
It's a swiss army knife that will help you build, deploy and debug your apps. We'll publish a dedicated codelab for the CLI to explain what you can achieve with this tool and what's actually happening behind the scenes.  

Start the first lesson: [Bootstrap a headless app](/lessons/bootstrap.md).