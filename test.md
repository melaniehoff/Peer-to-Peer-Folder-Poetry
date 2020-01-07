# P2P Folder Poetry: An introduction to Re-introducing Yourself to Computers

![](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/folder-laser-black-wide.png)

**SFPC Code Societies**<br>
**Jan 7th 2020, 6:30 - 9:30pm**

What if we could transform our online networks from something we passively receive to something we actively create? Folder Poetry is the practice of using the structure of computer folder organization as a new kind of poetic form like the haiku or iambic pentameter. By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry. In this workshop we will collectively create peer-to-peer folder poetry using the command line and Dat. Through lecture, examples, and writing folder poetry as meditation, we will explore the narrative qualities of folder structures and Dat as a tool for building digital spaces with and for our networks.

In this session we will get intimate with computers and write poetry with their logic. This workshop is an introduction to writing folder poetry, the P2P protocol Dat, and navigating the command line interface using Bash.

Together, we will create living networked poetry through connecting folders on the peer-to-peer web for each other to inhabit and explore.

This workshop assumes no coding experience and simultaneously takes the position that everyone who interacts with computers in some way is already a programmer.

See: [Always Already Programming](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry#always-already-programming)


## Terms 
- **Folder Poetry** is the practice of using the structure of computer folder organization as a new kind of poetic form like the haiku or iambic pentameter. By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry.
- **The Terminal** is desktop application to control and make changes to your operating system by typing text commands. In this class we'll use the terminal to create folder poetry.
- **Bash** is the programming language we'll use in the terminal, often one line at a time, but we can also put Bash code in a file and run that file.
- **Peer-to-peer** computing is a way to make distributed networks in which each computer can act as a server for the others, allowing shared access to files without the need for a central server.
- **Dat** is a data distribution tool for publishing on peer-to-peer networks.

## Preparation before Class 
For Windows 10, check out this [preliminary set up guide](https://gist.github.com/solon/4e254be6e0d2e73ef8624470fc9ca852#file-folder-poetry-setup-md)


### 1. 🔮Prompt: Folder Poem as School
_What would your speculative liberatory learning environment look like?_

_Previous prompts have been Folder Poem as [Village](https://gist.github.com/melaniehoff/7cda150870c869c1990a744dddbd286f#folder-poetry-prompt--a-village-you-want-to-live-in), [Gift](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#folder-poetry-prompt), & [Home](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/sfpc-fall-2019.md#2-prompt-folder-poem-as-home)_

**Gently explore your imagination and think about the following prompt. Feel free to write or sketch based on your reflections but this is not required.**

- **Imagine a fantastical physical environment that could hold you and those you want to learn nearby.**
- **This school is not like any school that exists. This school does not have to be realistic or adhere to laws of physics.**
    - What kinds of rooms, interconnecting hallways, or gardens could be grown? What kinds of activities would learners do in different spaces throughout the school?
    - What kinds of subjects would be taught there? Are their teachers and students or some other set of roles?
    - Do the roles ever change?
    - What are the bathrooms like? How about the furniture? Are there laboratories? Playgrounds? Napping rooms?
    - Consider the kinds of relationships you would like this school to hold & how people could relate to each other differently based on the proximity and content of their learning?
    - Consider how you would like to share space with others in this school. How are different parts of your school accessed and by whom?
    - Are there grades in this school? How are people separated into groups if ever? What are the taxonomies? For ex: traditional school systems will group people by categories such as age, class, geography, "ability", "behavior", and able-bodied-ness. 
    - Consider the ephemeral aspects of the school as much as the physical aspects.
    - In this school, how do you communicate and care for each other?
    - What are the emotional qualities of the spaces in this school?
    - What is the weather like around this school?
    - Consider the many forms it could take,
        - A memory palace with many rooms. In each room a memory of something that someone learned in this room by seeing the memory of the last person in this room.
        - A forest of learning folders where each participant is a tree and insect files carry information back and forth between them.
        - A school where each room is devoted to something you would like to learn collectively with those you share a that room with.
        - A multi-generational interconnected courtyard boarding house with rooms for climbing, rooms for growing, rooms for cooking, rooms for singing.

### 2. Install Node & Dat
Run each of these Bash lines one after the other by pasting them in your Terminal application and pressing ENTR. Don't worry if you've never used terminal before or you're not comfortable with it! There will be time in class to install if you dont get to it before class. 

- `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | bash`
- `source ~/.bash_profile`
- `nvm install --lts`
- `nvm use --lts`
- `npm install -g dat`

### 3. Read Folder Poetry
**Folder Poetry Examples**
- 🔗[Download & Explore the SFPC Fall 2019 Cohort's Poetry in your Terminal or Finder](https://www.dropbox.com/s/ewh0cowonhqoozf/sfpc-fall-2019-folder-poetry-smaller.zip?dl=0)
- 📒[Download: Folder Poetry - SFPC Yamaguchi Japan Zine](https://melanie-hoff.com/folder-poetry/sfpc-ycam/zine-pdfs-ycam-folder-poetry.zip)<br>
- 📒[Download: Folder Poetry - SFPC Detroit Zine](https://melanie-hoff.com/folder-poetry/sfpc-detroit/detroit-zine-reader.pdf.zip)<br>
- Folder Poetry on the default (non P2P) internet
    - [folderpoetry.club](folderpoetry.club)
    - Laurel Schwulst's adapatation of Folder Poetry in their _Writing as Metadata_ class at Yale: [metadatarocks.nfshost.com](metadatarocks.nfshost.com)
    
## 🟣 Your Folder Poetry Structure

In your home(~) folder we will have:

- a folder called folder-society
- a folder called my-folder-poem
- inside my-folder-poem is a folder called your-name
- inside the folder called your-name is where your poem will live

**To create the above outlined folder structure using Bash in the terminal:**

- `cd`
- `mkdir folder-society`
- `mkdir my-folder-poem`
- `cd my-folder-poem`
- `mkdir your-name`
- `cd your-name`
    - ^ where we'll make our poems

## 🟣 P2P Folder Poetry *Strict* Rules

P2P folder poetry has specific requirements in order for your poems to be shared
with each other via the Dat protocol. If you don't follow these rules, you will have
still created folder poetry, they just wont become P2P folder poetry during this
workshop.

**The artform of folder poetry is forgiving, Dat is not.**

🟣 No empty folders.
🟣 Every file has to contain text in it.
🟣 Naming files and folders
🟣 All lowercase
🟣 No spaces. 
🔺Underscores and dashes are ok. for example: `my_file.txt` or `my-file.txt`
🟣 All files must have a file extension such as .txt

## 🎲 Bash & Terminal commands

[Bash ](https://www.notion.so/6d468ee5b55a43d8bd85d958638a35aa)

[Keyboard Terminal Shortcuts](https://www.notion.so/fea90a3d377d4bb88ef7cde81969dd0e)

[Editing a text file](https://www.notion.so/29030df6129747f6a9a4fe0dcfef8204)

## Editing your ~./bash_profile

_The ~./bash_profile is a configuration file for the terminal._

1. `nano ~/.bash_profile`

    - This command will open your ~./bash_profile in the nano editor
    
In steps 2 and 3 we will paste 2 aliass AKA shortcuts that will help us visualize our folder poem structures.
    
2. `alias tree="find . -not -path '*/\.*' -print | sed -e 's;[^/]*/;|;g;s;|; |;g'"` 
    - (if you have homebrew installed enter `brew install tree` in another terminal window instead)
    
3. `alias treefile="find . -not -path '*/\.*' | xargs  -I {} bash -c 'f={}; echo \$f | sed -e \"s;[^/]*/;|;g;s;|; |;g\"; if [[ \$f == *.txt ]]; then echo; cat \$f; echo; echo; fi'"`

4. `export PS1="🍋 \w\n\u$ "`
    - This will customize your Bash prompt. Feel free to change the emoji. (skip if you use zshell)
    - Explanation: `\w` shows your full file path so you'll always know where you are in the terminal, `\n` creates a new line in your bash prompt. `\u` shows your computer username, and `$` symoolizes the end of a bash prompt.
    
5. `source ~/.bash_profile`
    - reboot your terminal
    
  

### Helpful Codes

Install homebrew
- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

To remove (base) from bash prompt after installing Anaconda:
- `conda config --set auto_activate_base False`
- `source ~/.bash_profile`

To change your computer's hostname (Mac)
- sudo scutil --set HostName new_hostname
- restart your computer

To install Anaconda (Python 3.7+, 64-bit), follow the instructions for your platform here.
- Mac OS X: [go this page](https://www.anaconda.com/download/#macos), wait for the download to complete, and run the installer file. Choose all of the installer’s default options. To test your installation, open a terminal window and type “conda”, without quotation marks, and press enter. You should see a different list of arcane commands than those produced by typing “git”.

- Windows: [go to this page](https://www.anaconda.com/download/#windows), wait for the download to complete, and run the exe file. Choose all of the installer’s default options, except you should reject the suggestion to install Microsoft Visual Studio Code. (Again, we recommend editing text using Atom.) Test your installation by searching for “anaconda prompt” in your system. In the resulting terminal window, type “conda”, without quotation marks, and press enter. You should see a different list of arcane commands than those produced by typing “git”.
