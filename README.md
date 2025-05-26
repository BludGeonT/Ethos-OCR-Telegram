# Ethos-OCR-Telegram
An EthosProject Telegram Message OCR Tool For Pattern Matching, Learning, and Predicting


# Ethos-OCR-Telegram Project

## Read PLANNING.md First Before Any Thinking or Planning or Coding to establish AI agent guidelines and guardrails.
## Read UI.md to understand how the layout will be formatted, behave, and interact to provide the user experience for this tool
## Read any other .md Markdown files next, if present, and apply the guidelines and considerations from the Markdown files before it.

## Ethos-OCR-Telegram Additional configuration considerations when we start to build this
- In addition to reading and going through all of the markdown .md files for this project, there are some other things to consider when the time to build this comes with Agents
  - I have a raspberry Pi available here at home with me running some other bots outside of AI.  They are running Python either by crontab or screen sessions running a bot that is listening.
  - When it comes time to write the code for these bots for this module, and other modules within the EthosProject.ai Telegram suite, then the repos need to be laid out and prepared according to all of the rules in the md files but also so that I can clone the repos to my Pi and run them locally.
    - I have a CIFS mount from the Pi running Ubuntu that mounts an external spindle drive for storage within the /data directory
    - I have a CIFS mount from the Pi running Ubuntu that mounts an external spindle drive for storage for the /processing directory.

## Ethos-OCR-Telegram Project Meanings
- In this article, when I refer to `ethos-ocr-bot`, I am referring to the Telegram bot that has been added into the Ethos-OCR-Telegram Project by a user with permissions to be used by this project.
- When I refer to the "Project" I mean this module that we are building specifically to manage Telegram spam with our Ethos OCR Telegram utility which will contain a web UI, user management, bot management, database management, configurations, etc - some of which may be linked and utilize other databases within the EthosProject.ai main telegram utility.

## Ethos-OCR-Telegram Project Functionality
There are a few things to consider

### IDEAS
- monitor the logging channels and look for triggered filter bans and then configure up the command to issue a fban autmoatically
- 
