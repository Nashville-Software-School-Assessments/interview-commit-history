# API Request/Response Assessment

## Setting Up

1. Click the Gitpod icon above. If requested, authorize with Github.
2. After the virtual machine is set up, create a new terminal by clicking the icon at the top left of the screen and then choose `Terminal > New Terminal`
3. One the terminal is open at the bottom, install serve with `npm i -g serve`
4. Then run the web server with `serve -l 8080`.
5. When prompted how to access your project, click "Open Browser"

## Instructions

You must be able to identify and demonstrate how to inspect the Request URL and the response data from the API using your dev tools.

Write code in `main.js` that requests data from the following URL (https://api.github.com/repos/stevebrownlee/learn-ops-api/commits). For each commit, use the following template to display information about it.

```txt
${login name of author} committed on {date of commit} with the message "${commit message}"
```

