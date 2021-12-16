# API Request/Response Assessment

## Setting Up

1. Click the Gitpod button above. If requested, authorize with Github.
2. After the virtual machine is set up, a terminal will appear at the bottom of the editor.
3. Paste the command `serve -l 8088` into the terminal to start the web server.
4. A new browser window will open where the code is running.
5. Remember that this isn't `create-react-app` so you will need to manually refresh the running code when you make changes in the editor.

## Instructions

You must be able to identify and demonstrate how to inspect the Request URL and the response data from the API using your dev tools.

Write code in `main.js` that requests data from the following URL (https://api.github.com/repos/stevebrownlee/learn-ops-api/commits). For each commit, use the following template to display information about it.

```txt
${login name of author} committed on {date of commit} with the message "${commit message}"
```

