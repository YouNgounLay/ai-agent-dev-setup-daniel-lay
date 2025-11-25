# ai-agent-dev-setup-daniel-lay

| Student Name           | Workshop Cohort                                      |
| ---------------------- | ---------------------------------------------------- | 
| You Ngoun Lay (Daniel) | FullStack and Agentic AI Industry Project Internship |

## Resources Version

> Node Version
![image](resources/images/node%20version.png)

> Git Version
![image](resources/images/git%20version.png)

> Vscode Insider with Copilot Running
![image](resources/images/github%20copilot%20with%20vscode%20insider.png)

> Claude Window with 4 MCP Servers Running
![image](resources/images/claude%20window%20with%204%20mcp%20servers%20running.png)

## Installed MCP Server Functionalities 



| MCP Server               | Use case                                                                                         | Example                                                                                   |
| ------------------------ | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| Read & Write Apple Notes | Managing my apple notes, maintaining and changing the note structures as well as creating links. | Find my note about the project deadline and update it.                                    |
| Control Chrome           | Workflow automation and piloting the Chrome browser.                                             | Using the provided urls, generate a quick summary of the contents listed on the web page. |
| Roll Dice                | Generate random numbers for games, decisions or simulations                                      | Roll a 20-sided die for my attack                                                         |
| Github                   | Complete Github repository management given the token access privilege.                          | Create a new repos.                                                                       |


Installing the above MCP servers was quick, I could not find the respository for Bootcamp AI agent & Calendar booking, so I replaced them both with Control Chrome, and Read Write Apple Note. Github MCP server installation was a bit more elaborate, I had to do a quick research, verifying the right source, as it might expose all my repositories if I were not careful. After which, I setup a Github Token, and Docker, the config file, then restart Claude desktop. 



📋 Week Deliverable: Development Environment Setup Repository
Due Date:

End of Week 1
Duration:

Setup verification
Description:

Submit a single GitHub repository demonstrating complete development environment setup with all MCP server connections working and documented. This repository serves as proof of your AI Agent Developer environment readiness.
📝 Submission Requirements:

    Create a public GitHub repository named 'ai-agent-dev-setup-[your-name]'
    Repository must contain the following files and folders:
    📁 /mcp-configs/ - Folder containing:
    • claude-desktop-config.json (your Claude Desktop MCP configuration)
    • mcp-servers-list.md (documentation of all 4 servers: Rolldice, Bootcamp AI Agent, Calendar Booking, GitHub)
    • connection-test.md (evidence that each MCP server is working)

    🎯 **MINIMUM ACCEPTANCE CRITERIA:**
    • All 4 MCP servers (Rolldice, Bootcamp AI Agent, Calendar Booking, GitHub) must be demonstrably connected - Done
    • Repository must have at least 5 meaningful commits showing development workflow - Done
    • All screenshots must be clear and show the required functionality 
    • Written content must demonstrate understanding of AI Agent Developer concepts