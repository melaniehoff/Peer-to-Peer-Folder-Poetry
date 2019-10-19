# P2P Folder Poetry – Radical Networks

![](https://melanie-hoff.com/poster.png)

# Table of Contents
- [Preparation for Class](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#preparation-for-class) _look here first 👀_
- [Agenda](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#day-1-agenda)
- [Slides](https://docs.google.com/presentation/d/1K6vC-erUczNtjtBB4Q8wDeJXCcRIrP_t_BttH_kDxKo/edit?usp=sharing)
- [Folder Poetry Zines & Examples](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#folder-poetry-examples)
- [P2P Poetry Rules](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#p2p-folder-poetry-rules)
- [Bash & Terminal Commands](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#-bash--terminal-commands)
- [Editing your .bash_profile](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#to-edit-your-bash_profile)
- [Sharing on the P2P web](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#-sharing-our-poems-on-the-p2p-web)
    - [P2P address book](https://docs.google.com/spreadsheets/d/1YPHB6c4ATzImkolcQz2nHPz1xm8n1AluqQrsI_R_sl4/edit?usp=sharing)
- [Workshop Description & Theory](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#workshop-description)

# Preparation for Class (Download, Install, Prompt)
**1.  Download [this folder](https://melanie-hoff.com/folder-poetry/radical-networks/garden-of-forking-paths.zip) and move it to your Home directory**<br>
**2. Install Node & Dat**
Run each of these Bash lines one after the other by pasting them in your Terminal and pressing ENTR.
- `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | bash`
- `source ~/.bash_profile`
- `nvm install --lts`
- `nvm use --lts`
- `npm install -g dat`

#### 3. 🌳Prompt: Folder Poem as Home
_What would your utopic, liberatory living environment look like?_

Gently explore your imagination and think about the following prompt. Write, diagram, or draw out your thoughts.

- **Imagine a kind of housing or space that could hold all your friends, chosen family, and maybe your biological family too.**
- **This home does not have to be realistic or even physically probable.**
    - What kinds of rooms, interconnecting hallways, or gardens could be grown? What kinds of activities would residents do in different spaces throughout the home?
    - Consider the kinds of relationships you would like this home to hold & how people could relate to each other differently based on the proximity of their daily lives?
    - Consider how you would like to share space with others in this home. How are different parts of your home accessed and by whom?
    - Consider the ephemeral aspects of your home as much as the physical aspects.
    - In this home, how do you communicate and care for each other?
    - What are the emotional qualities of the spaces in your home?
    - What is the weather like around your home?
    - Consider the many forms it could take,
        - A palace with many rooms. In each room a memory of something that happened in this room with someone in you live with.
        - A forest of folders where each resident is tree and insect files carry messages back and forth between them.
        - A school where each room is devoted to something you would like to learn collectively with those you share a home with.
        - A multi-generational interconnected courtyard housing compound with rooms for climbing, rooms for growing, rooms for cooking, rooms for learning.


# Day 1 Agenda
- Our Folder Names
- Preparation / Installation / Downloading 
- Introduction: Melanie's files

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
- [Terminal and Bash commands](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#-bash--terminal-commands)
- Introduction of navigating the command line by walking through the-garden-of-forking-paths
    - [Download a garden-of-forking-paths](https://melanie-hoff.com/folder-poetry/radical-networks/garden-of-forking-paths.zip) and move it to your Home folder
    - growing the garden
- Anatomy of Bash Prompt 
- [Editing bash_profile](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#editing-your-bash_profile)

### Part III
[_Making our Folder Poem Homes_](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#making-our-folder-poems)
- [Bash commands](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#-bash--terminal-commands)
- [Folder Poetry Rules](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#p2p-folder-poetry-rules)

### Part IIII: Peer-to-Peer Poetry with Dat
[_The network is a folder poem_](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md#-sharing-our-poems-on-the-p2p-web)



### [Workshop Slides](https://docs.google.com/presentation/d/1K6vC-erUczNtjtBB4Q8wDeJXCcRIrP_t_BttH_kDxKo/edit?usp=sharing)

## Folder Poetry Examples
📒[Download: Folder Poetry - SFPC Yamaguchi Japan Zine](https://melanie-hoff.com/folder-poetry/sfpc-ycam/zine-pdfs-ycam-folder-poetry.zip)<br>
📒[Download: Folder Poetry - SFPC Detroit Zine](https://melanie-hoff.com/folder-poetry/sfpc-detroit/detroit-zine-reader.pdf.zip)<br>
- Folder Poetry on the regular internet
    - [folderpoetry.club](folderpoetry.club)
    - Laurel Schwulst's adapatation of Folder Poetry in their _Writing as Metadata_ class at Yale: [metadatarocks.nfshost.com](metadatarocks.nfshost.com)

## P2P Folder Poetry Rules
_The artform of folder poetry is forgiving, Dat is not_

P2P folder poetry has specific requirements in order for your poems to be shared
with each other via the Dat protocol. If you don't follow these rules, you will have
still created folder poetry, they just wont become P2P folder poetry during this
workshop.

🔴 No empty folders.<br>
🔴 Every file has to contain text in it.<br>
🔴 Naming files and folders<br>
🔴 All lowercase<br>
🔴 No spaces. <br>
    - Underscores and dashes are ok. for example: `my_file.txt` or `my-file.txt`
🔴 All files must have a file extension such as .txt<br>

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
    
3. `alias treefile ="find . -not -path '*/\.*' | xargs  -I {} bash -c 'f={}; echo \$f | sed -e \"s;[^/]*/;|;g;s;|; |;g\"; if [[ \$f == *.txt ]]; then echo; cat \$f; echo; echo; fi'"`

4. `export PS1="🍋 \w\n\u$ "`
    - This will customize your Bash prompt. Feel free to change the emoji. (skip if you use zshell)
    - Explanation: `\w` shows your full file path so you'll always know where you are in the terminal, `\n` creates a new line in your bash prompt. `\u` shows your computer username, and `$` symoolizes the end of a bash prompt.
    
5. `source ~/.bash_profile`
    - reboot your terminal

## Making our Folder Poems
- `cd`
- `mkdir folder-poetry`
- `cd folder-poetry`
- `mkdir myname-home`
    - ^ this is where your folder poem will grow

## 🕸 Sharing our Poems on the P2P Web

This part might feel tricky. Don't worry if you miss a step and encounter any problems. It’s ok, they will be easily resolved. TAs and i are here to help you :)
    
- Open a totally new window in Terminal
- `cd folder-poetry` this brings you into your folder-poetry folder
- `dat share` this starts serving your folder on the P2P web
- copy your hash into [this spreadsheet](https://docs.google.com/spreadsheets/d/1YPHB6c4ATzImkolcQz2nHPz1xm8n1AluqQrsI_R_sl4/edit?usp=sharing) next to your name
- minimize this window so you dont touch it. Your folder will only be sharing as long as this terminal window is active and dat share-ing.

### Networked Poems (cloning your neighbor's poem)
- **In a new Terminal window:**
- `cd`
- `mkdir folder-homes`
- `cd folder-homes`
- `dat clone + copy-someone-elses-poem-hash-from-spreadsheet`
- `ls` you should be able to see and explore their poem!

___

# Workshop Description

What if we could transform our online networks from something we passively receive to something we actively create? Folder Poetry is the practice of using the structure of computer folder organization as a new kind of poetic form like the haiku or iambic pentameter. By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry. In this workshop we will collectively create peer-to-peer folder poetry using the command line and Dat. Through lecture, examples, and writing folder poetry as meditation, we will explore the narrative qualities of folder structures and Dat as a tool for building digital spaces with and for our networks.

In this session we will get intimate with computers and write poetry with their logic. This workshop is an introduction to writing folder poetry, the P2P protocol Dat, and navigating the command line interface using Bash.

Together, we will create living networked poetry through connecting folders on the peer-to-peer web for each other to inhabit and explore.

This workshop assumes no coding experience and simultaneously takes the position that everyone who interacts with computers in some way is already a programmer.

### Always Already Programmimg

Every time you make a folder or rename a file on your computer, the actions you take through moving your mouse and clicking on buttons, have an equivalent text command. When you use a visual interface (called a GUI) text commands are still being fired in the background which eventually compile to binary. Using bash in the terminal is a way to get a little closer to the metal and a little further along in uncovering the mechanics of our most common devices.

Everyone who interacts with computers has, in very real ways already been programming. The distinction between programmer and user is maintained by a tech industry that benefits from a population rendered computationally passive. 

Together we can build up and cultivate one another’s agency to shape technology and online spaces that support and care for each other and our communities. 
    

### To create our folder poetry, we will use Bash in the terminal. To share our folder poetry, we will use Dat.

>"Dat is a p2p protocol that enables people to publish content and information to the web from their personal computers. This fundamentally changes the relationship people have to the internet by breaking the client server hierarchy and opens the realm of self publishing to everyone." - [New Computers Working Group](https://p2p.newcomputers.group/guides/why-self-host.html)
 
### Notes on why we're using a spatial and narrative metaphors for learning bash and creating folder poetry

**Using the command line and computing in general is a relational practice**. You are never using the command line from a “global” perspective. When you issue commands from the command line, you are doing so, from a particular position within the hierarchy of your computer’s file system.

Similarly, when we are inside a house, we are never simultaneously in the kitchen and the bedroom. If we tried to “get into bed” while in the kitchen, we would not be able to. However if we wanted to wash dishes while standing in the kitchen, we would be able to.

From the command line, if we have navigated to the Desktop folder but try to perform an action on a file that’s inside your home directory, this would not work. You would have to navigate to the home folder by navigating your file path.


___



### Emoji for loop

`for i in {1..2000}; do printf ' ♡ 📂 → ➩ ➪ ➫ ➬ ➭ ➮ '; done;` will create an emoji for loop

### 🔮 `folder-spell`

`folder-spell` is a folder poetry generator that came out of a conversation our TA Brian Solon and i had on the bus yesterday. It makes writing sentences with folders go very quickly.

- It creates a series of nested folders with a text file at the end.
- The first words you write after `folder-spell` will become a series of nested folders. The text within quotations will become the contents of a text file.

**Installation**

- enter the entire following line in your terminal
    - `curl https://gist.githubusercontent.com/solon/27106a5389c61dcb83fb25fa9c20787d/raw/folder-spell.sh > ~/folder-spell.sh && chmod u+x ~/folder-spell.sh && echo $'folder-spell() {\n ~/folder-spell.sh \"$@\" \n}' >> ~/.bash_profile`
-   `source ~/.bash_profile`


