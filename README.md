## Project README Template
_created by_: Arlo Gittings  
_created on_: 2021-07-19  
_last modified_: 2024-04-07
### Description
Project templates for every occasion. I am a firm believer that the key to 
solving a complex issue is to identify the problem and begin to disect it into
the smallest possible blocks. These templates are designed to assist me in that
process. The keys to this setup are the README and the plan. As I typically
begin with the plan, I will open with it here as well. As the file extension
indicates both the plan and README files are styled with markdown.

plan.md is the primary design document. It is alive and will change as the 
project develops. Initially, I may only have the description and a single goal
identified. As research into the project develops, Layout details, primary and
secondary goals will solidify.

README the end user facing documentation. This contains a less technical, more
job oriented description. It also contains instructions for installation and
common usage.

change.log keep any changes in here. Typically, these witll be preceeded by a
date and time stamp. There is no need for writing a book. A single sentence can
capture the change as it was committed. Log often, even the smallest change can
completely reshape a project.

My format
YYYY-MM-DD  HHMM  what was done to wich file/function  Changemaker's Name/ID

The license I work under is the GPL, unless otherwise noted. I have a copy of
the version which I am working under tied to the project.

The document template is designed to more align with how I write and research.
It uses an outline instead of a plan, adds a resources file, contains style
guides for markdown and latex, and directories for notes and drafts
### Installation
If you do not have a projects directory, make one and clone this project into
it:

```bash
mkdir ~/projects
cd ~/projects
git clone https://github.com/konijntjesbroek/templates
```

while you are at it, I strongly suggest you add an environment variable for 
this path to you your shell config

```bash
PROJ="${HOME}/projects"
export PROJ
```
This allows you to easily switch projects by typing:

```bash
cd ${PROJ}/<project name>
```
regardless of where you are in the filesytem.

### Usage
When you create a new project:
```bash
cd ${PROJ}
cp -dpR templates/<project type> <project name>
cd <project name>
vim plan.md
```

Replace \<project type\> with the correct template, Most of the time, this will be
'project'.
Replace \<project name\> with the name of the project you are spinning up.

### Special Notes
If you are using this on codepen which requires changelog to be an md file, use the triple backtick to force it to plaintext
