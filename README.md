# Node.js & JavaScript & SAPUI5

## Summary

*Based on MS dev-container 'javascript-node' https://github.com/microsoft/vscode-dev-containers*

*Develop SAPUI5 projects - ui5 tooling, mbt, etc.*

## Testing the definition

This definition includes some test code that will help you verify it is working as expected on your system. Follow these steps:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started) to set up your machine.
2. Clone this repository.
4. Start VS Code, press <kbd>F1</kbd>, and select **Remote-Containers: Open Folder in Container...**
5. Select the `$(pwd)` folder.
6. After the folder has opened in the container, open console and run the commands `npm install` then `ui5 serve` to start the project.
7. Once the project is running, press <kbd>F1</kbd> and select **Remote-Containers: Forward Port from Container...**
8. Select port 3010 and click the "Open Browser" button in the notification that appears.
9. You should see "Example application" after the page loads.

## License

Licensed under the MIT License. See [LICENSE](https://github.com/microsoft/vscode-dev-containers/blob/main/LICENSE).
