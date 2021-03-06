# P2P Folder Poetry: An introduction to Re-introducing Yourself to Computers

![](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/folder-laser-black-wide.png)


What if we could transform our online networks from something we passively receive to something we actively create? Folder Poetry is the practice of using the structure of computer folder organization as a new kind of poetic form like the haiku or iambic pentameter. By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry. In this workshop we will collectively create peer-to-peer folder poetry using the command line and Dat. Through lecture, examples, and writing folder poetry as meditation, we will explore the narrative qualities of folder structures and Dat as a tool for building digital spaces with and for our networks.

In this session we will get intimate with computers and write poetry with their logic. This workshop is an introduction to writing folder poetry, the P2P protocol Dat, and navigating the command line interface using Bash.

Together, we will create living networked poetry through connecting folders on the peer-to-peer web for each other to inhabit and explore.

This workshop assumes no coding experience and simultaneously takes the position that everyone who interacts with computers in some way is already a programmer.


# Always Already Programming

Everyone who interacts with computers has—in important ways—always already been programming them. Why are the ideas of a programmer and a user so divorced from each other? The distinction between programmer and user is reinforced and maintained by a tech industry that benefits from a population rendered computationally passive. 

Every time you make a folder or rename a file on your computer, the actions you take through moving your mouse and clicking on buttons, have an equivalent text command. When you use a visual interface (called a GUI) text commands are still being fired in the background which eventually compile to binary. Using bash in the terminal is a way to get a little closer to the metal and a little further along in uncovering the mechanics of our most common devices.

Together we can build up and cultivate one another’s agency to shape technology and online spaces that support and care for each other. 
    
## Vocabulary
**Word** | **Notes**
--- | ---
Folder Poetry| The practice of using the structure of computer folder organization as a new kind of [poetic form](https://en.wikipedia.org/wiki/Poetry#Forms) like the [haiku](https://en.wikipedia.org/wiki/Haiku) or [iambic pentameter](https://en.wikipedia.org/wiki/Iambic_pentameter). By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry.
terminal | An application to control and make changes to your operating system by typing text commands. In this class we'll use the terminal to create folder poetry.
terminal commands | text commands to control your computer when entered into a command prompt like the terminal. The commands we'll learn will be in a language called Bash.
Bash | is the programming language we use in the terminal, often one line at a time, but we can also put Bash code in a file and run that file.
Peer-to-Peer | Peer-to-peer computing is a way to make distributed networks in which each computer can act as a server for the others, allowing shared access to files without the need for a central server.
Dat | is a data distribution tool for publishing on peer-to-peer networks.
folder | (also referred to as directory) is an organizational regime imposed on your computer used to store and organize files and other folders
file | is an object on a computer which stores data, information, settings, or commands to be used with various computer programs
file types/formats/extensions | indicate how data has been stored and how to read or open files in specific programs. for example, `.txt` files open in a text editor, `.jpg` files open in an image viewer/editor. full list of file formats and extensions [here](https://en.wikipedia.org/wiki/List_of_file_formats)
file path | tells you the location of a file in a system. for example `users/username/desktop/folder_poetry_club`


## To create our folder poetry, we will use Bash in the terminal. To share our folder poetry, we will use Dat.

>"Dat is a p2p protocol that enables people to publish content and information to the web from their personal computers. This fundamentally changes the relationship people have to the internet by breaking the client server hierarchy and opens the realm of self publishing to everyone." - [New Computers Working Group](https://p2p.newcomputers.group/guides/why-self-host.html)
 
## Notes on why we're using a spatial and narrative metaphors for learning bash and creating folder poetry

**Using the command line and computing in general is a relational practice**. You are never using the command line from a “global” perspective. When you issue commands from the command line, you are doing so, from a particular position within the hierarchy of your computer’s file system.

Similarly, when we are inside a house, we are never simultaneously in the kitchen and the bedroom. If we tried to “get into bed” while in the kitchen, we would not be able to. However if we wanted to wash dishes while standing in the kitchen, we would be able to.

From the command line, if we have navigated to the Desktop folder but try to perform an action on a file that’s inside your home directory, this would not work. You would have to navigate to the home folder by navigating your file path.

## Resources to Review Before Class
- [P2P Folder Poetry Arena Channel](https://www.are.na/melanie-hoff/peer-to-peer-folder-poetry)

## Prerequisites
- A computer running macOS, Linux or [Windows 10](https://gist.github.com/solon/4e254be6e0d2e73ef8624470fc9ca852#file-folder-poetry-setup-md)
- An Internet connection to download software packages
- Administrator access to your computer to install software packages
- In this workshop we will use Bash, Node.js, and Dat.


## Session Objectives

- To create a space where we are getting intimate with computers and writing poetry with their logic
- To develop a taste for creating emotive and community-centered software
- To introduce [Dat](https://dat.foundation/) and navigating the Command Line with [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell))
- To create poetry through building a folder-based city on the peer-to-peer web for each other to inhabit

### Part I: Folder Poetry

**Reintroduction to computers & computing**
_Programming is about the computer, the programmer, the relationship they have with each other, and the environments they create together._ 
- Folders & file systems
- What is Folder Poetry and how will we be creating it?
- Discretely categorizing things. The affordances of folders.
- Examples of folder projects
- Folders Anonymous

### Part II: Terminal & Bash
_The Desktop is a lie_
- Terminal and Bash commands
- Introduction of navigating the command line by walking through the-garden-of-forking-paths
    - [Download the garden](https://melanie-hoff.com/folder-poetry/sfpc-2019/garden-of-forking-paths.zip)
    - growing the garden
- Anatomy of Bash Prompt 
- Editing bash_profile

### Part III
_Making our Folder Poem Poems in Bash_

### Part IIII: Peer-to-Peer Poetry with Dat
_The network is a folder poem, be the poet_
- P2P introduction and description of DAT and "the cloud"
- Dat is a protocol for sharing data between computers.
- Dat’s strengths are that data is hosted and distributed by many computers on the network, that it can work offline or with poor connectivity
- The Distributed Web is about decentralization of servers and control
- Data on the distributed web is not indexed which means it is not easily searchable
- We are creating a local network island away from the default(larger) internet
- Sharing our Poems on the P2P Web 

### 🔮Prompt: Folder Poem as School
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


## 🎲 Bash & Terminal commands

| Command                                    | Description                                   |
| ------------------------------------------ | --------------------------------------------- |
| `cd`                                       | change directory                              |
| `cd ..`                                    | change directory one level back               |
| `ls`                                       | list contents of directory                    |
| `pwd`                                      | print working directory                       |
| `mkdir foldername`                         | create a folder named foldername .            |
| `touch dandelion.txt`                      | create a file named dandelion.txt             |
| `echo "woof woof" > kitty.txt`             | creates a text file called kitty.txt that contains the words, "woof woof"|
| `cat filename.txt`                         | print contents of file                        |
| `rm -rf filename.txt` .                    | remove a file or folder this way              |
| `mv filename.txt newfilename.txt`          | rename a file                                 |
| `open .`                                   | (macOS) open the current folder in Finder     |
| `explorer.exe .`                           | (Windows) open the current folder in Explorer |
| `open filename.txt`                        | (macOS) opens file in Text Edit               |
| `notepad.exe filename.txt`                 | (Windows) opens file in Notepad               |
| `cp filename.txt filename2.txt`            | copy file                                     |
| `say "hello, what is poetic computation?"` | (macOS) speak out loud                        |
| `man cd`                                   | show the manual for 'cd'. Press q to quit     |
| `source ~/.bash_profile`                   | restart your terminal config file             |


### Keyboard Terminal Shortcuts
| Command               | Description            |
|-----------------------|------------------------|
| Up + Down Arrow keys | scroll through history |
| Tab Key               | autocomplete           |
|CMD + CTRL + SPACE     |Emoji Keyboard (Mac OS) |


### Editing a text file
| command              | Description                       |
| -------------------- | --------------------------------- |
|`echo "woof woof" > kitty.txt` | creates a text file called kitty.txt that contains the words, "woof woof"|
| `nano textfile.txt`  | open file in the nano text editor |
| CTRL + X , y , ENTER | exit and save changes             |


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


## In class we will get into small groups and share our poems on the p2p web 💜

### 📤 Sharing your poem   
**First we will share our poems, then we will recieve other's**

1. make sure your poem lives inside ~/my-folder-poem/your-name/your-poem-here 
2. `cd ~/my-folder-poem` 
    - note if your my-folder-poem/ folder is in a different directory, this part may look like `cd ~/code-societies/my-folder-poem`
3. enter `dat share` in your terminal from inside the folder, my-folder-poem/
4. copy and paste the blue url that looks something like `dat://a297239732y98r3y8328320230y352y0350y3520y3` into [P2P Address book](https://docs.google.com/spreadsheets/d/1nDLIUVbKFc3XNALA7Uf65ra-sH4AsPewWWajt2ltxMY/edit?usp=sharing) next to your name 
5. dont close or exit this terminal session so your poem will continue to be shared on the network!
6. Now you are sharing your poem on the p2p web!

### 📥Receiving other's poems
**Now we will recieve other's poems!**

1. OPEN A TOTALLY NEW TERMINAL WINDOW (so we don't disrupt the sharing)
2. `cd ~/folder-society` 
3. now go to the [P2P Address book](https://docs.google.com/spreadsheets/d/1nDLIUVbKFc3XNALA7Uf65ra-sH4AsPewWWajt2ltxMY/edit?usp=sharing) and copy and paste a dat://xxxx url from someone else in the class!
4. enter `dat clone` + paste the dat hash here! 
    - it will look something like this`dat clone dat://7ce94a276f9f16f66644e02/`
5. `ls` and you should see a directory inside your folder-society folder titled something like `7ce94a276f9f16f66644e02/` this will be the name of the hash of the dat poem you just cloned
6. cd into this directory, for me this looks like `cd 7ce94a276f9f16f66644e02/` (remember you can tab to autocomplete!)
7. now you can continue`cd`ing into your classmates poem and explore it! 
8. if you want to see the whole structure enter `tree` into your terminal. if you don't have tree, seee below:

#### 🌳 If you dont have tree
- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- `brew install tree`
- now try entering `tree` into your terminal to expand the folder structures!

### 🕸Install Node & Dat
Run each of these Bash lines one after the other by pasting them in your Terminal application and pressing ENTR. Don't worry if you've never used terminal before or you're not comfortable with it! There will be time in class to install if you dont get to it before class. 

- `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash`
- `source ~/.bash_profile`
- `nvm install --lts`
- `nvm use --lts`
- `npm install -g dat`

To test that everything worked, enter `dat` into your terminal.
If you see output that starts with `Usage: dat <cmd> [<dir>] [options]` you have all the software you need to share your folder poems on the p2p web! 🎊

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

- 🟣 No empty folders.
- 🟣 Every file has to contain text in it.
- 🟣 All lowercase
- 🟣 No spaces. 
- 🔺Underscores and dashes are ok. for example: `my_file.txt` or `my-file.txt`
- 🟣 All files must have a file extension such as .txt


### Read Folder Poetry
**Folder Poetry Examples**
- 🔗[Download & Explore the SFPC Fall 2019 Cohort's Poetry in your Terminal or Finder](https://www.dropbox.com/s/ewh0cowonhqoozf/sfpc-fall-2019-folder-poetry-smaller.zip?dl=0)
- 📒[Download: Folder Poetry - SFPC Yamaguchi Japan Zine](https://melanie-hoff.com/folder-poetry/sfpc-ycam/zine-pdfs-ycam-folder-poetry.zip)<br>
- 📒[Download: Folder Poetry - SFPC Detroit Zine](https://melanie-hoff.com/folder-poetry/sfpc-detroit/detroit-zine-reader.pdf.zip)<br>
- Folder Poetry on the default (non P2P) internet
    - [folderpoetry.club](folderpoetry.club)
    - Laurel Schwulst's adapatation of Folder Poetry in their _Writing as Metadata_ class at Yale: [metadatarocks.nfshost.com](metadatarocks.nfshost.com)
    
 

        
### Helpful Codes

👛 if you have a Mac computer and are feeling fancy, i recommend downloading Iterm
- https://iterm2.com/

Install homebrew
- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

For newer Mac's to switch from zsh to bash
- `chsh -s $(which bash)`<br>
OR<br>
- `chsh -s /bin/bash`
- More info [here](https://www.howtogeek.com/444596/how-to-change-the-default-shell-to-bash-in-macos-catalina/)

To remove "(base)" from prepending the bash prompt after installing Anaconda:
- `conda config --set auto_activate_base False`
- `source ~/.bash_profile`

To change your computer's hostname (Mac)
- sudo scutil --set HostName new_hostname
- restart your computer



## Windows Preparation before Class 
For Windows 10, check out this [preliminary set up guide](https://gist.github.com/solon/4e254be6e0d2e73ef8624470fc9ca852#file-folder-poetry-setup-md)

<br>
🦋🦋🦋

