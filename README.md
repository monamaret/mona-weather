# mona-weather 

This is a demonstration project showing how to refactor an existing reference application to support a new sensor chip.

## how to use this project

This project is intended as a learning exercise to demonstrate various Tabnine features useful for refactoring embedded development projects, including:

- remote repository index
- agent workflows
- MCP tool calling

The project is incomplete by design. You need to fork the project and complete some initial setup:

### Remote repository connection

This project leverages a remote repository of an existing LVGL application located (here)[https://github.com/monamaret/lvgl-weather]. This repository should be connected to your Tabnine team by following the instructions located (here)[https://docs.tabnine.com/main/administering-tabnine/private-installation/managing-your-team/settings/workspace-settings/connecting-to-remote-repositories#setting-remote-git-providers] before starting the exercise. You will need to fork it into your own source control before creating the connection.

### MCP PDF to MD conversion

This project leverages an [MCP server for converting PDF files to Markdown](https://github.com/monamaret/datasheet-to-md-mcp). The MCP binary needs to be installed on your local before starting. See the instructions in the project readme.

### TODO and prompts

The high level project changes to be done are described in the file at `.prompt-library/TODO`.

The actual prompts used during the live demo are saved in the file at `.prompt-library/TODO`. Be mindful of the Conversation/Prompt numbers as some prompts exist as part of a conversation and some prompts are on new conversations. This is done to ensure a clean context window when switching tasks.

The intent is that after initial setup, you can recreate the end state of the demo by following the prompts. 