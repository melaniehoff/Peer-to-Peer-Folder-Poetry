# P2P Folder Poetry Radical Networks

What if we could transform our online networks from something we passively receive to something we actively create? Folder Poetry is the practice of using the structure of computer folder organization as a new kind of poetic form like the haiku or iambic pentameter. By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry. In this workshop we will collectively create peer-to-peer folder poetry using the command line and Dat. Through lecture, examples, and writing folder poetry as meditation, we will explore the narrative qualities of folder structures and DAT as a tool for building digital spaces with and for our networks.

In this session we will get intimate with computers and write poetry with their logic. This workshop is an introduction to writing folder poetry, the P2P protocol Dat, and navigating the command line interface using Bash.

Together, we will create living networked poetry through connecting folders on the peer-to-peer web for each other to inhabit and explore.

This workshop assumes no coding experience and simultaneously takes the position that everyone who interacts with computers in some way is already a programmer....

# Always Already Programmimg

Every time you make a folder or rename a file on your computer, the actions you take through moving your mouse and clicking on buttons, have an equivalent text command. When you use a visual interface (called a GUI) text commands are still being fired in the background which eventually compile to binary. Using bash in the terminal is a way to get a little closer to the metal and a little further along in uncovering the mechanics of our most common devices.

Everyone who interacts with computers has, in very real ways already been programming. The distinction between programmer and user is maintained by a tech industry that benefits from a population rendered computationally passive. 

Together we can build up and cultivate one another’s agency to shape technology and online spaces that support and care for each other and our communities. 
    

## To create our folder poetry, we will use Bash in the terminal. To share our folder poetry, we will use Dat.

>"Dat is a p2p protocol that enables people to publish content and information to the web from their personal computers. This fundamentally changes the relationship people have to the internet by breaking the client server hierarchy and opens the realm of self publishing to everyone." - [New Computers Working Group](https://p2p.newcomputers.group/guides/why-self-host.html)
 
## Notes on why we're using a spatial and narrative metaphors for learning bash and creating folder poetry

**Using the command line and computing in general is a relational practice**. You are never using the command line from a “global” perspective. When you issue commands from the command line, you are doing so, from a particular position within the hierarchy of your computer’s file system.

Similarly, when we are inside a house, we are never simultaneously in the kitchen and the bedroom. If we tried to “get into bed” while in the kitchen, we would not be able to. However if we wanted to wash dishes while standing in the kitchen, we would be able to.

From the command line, if we have navigated to the Desktop folder but try to perform an action on a file that’s inside your home directory, this would not work. You would have to navigate to the home folder by navigating your file path.
 
 ___

### [P2P Folder Poetry - Master syllabus](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry)

### 📒[Download the Class Zine here](https://melanie-hoff.com/folder-poetry/sfpc-ycam/zine-pdfs-ycam-folder-poetry.zip)

### [Slides for Folder Poetry YCAM](https://docs.google.com/presentation/d/1jSeKHcBZwUUZKdRQRrCareC9YdaeYWDdeiE6Zzwe7aY/edit?usp=sharing)
 
### [Bash Drawings made for Folder Poetry by Taeyoon Choi](https://docs.google.com/presentation/d/1WV_vFHtKB7BUBc3P_oGVlLry6W_8K_fJkJiWzisXonY/edit#slide=id.g60e8df3e27_0_113)

**Table of Contents**
- **[Day 1 Agenda](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#day-1-agenda)**
    - [Technical Notes](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#technical-notes)
    - [Click here if you are using Windows 10](https://gist.github.com/solon/4e254be6e0d2e73ef8624470fc9ca852#file-folder-poetry-setup-md)
    - [Folder Poetry Prompts](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#folder-poetry-prompts)
- **[Day 2 Agenda](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#day-2-agenda)**
    - [New Commands for Folder Poetry](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#%EF%B8%8F-new-commands-for-folder-poetry)
    - [Sharing Poems on the P2P Network](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#-sharing-our-poems-on-the-p2p-web)
    - [P2P Adress Book](https://docs.google.com/spreadsheets/d/1h-xDzg3RJ-Xf8A8ItPKm-GGl3T8qBfJcExM3vTsZxtk/edit?usp=sharing)

![](https://melanie-hoff.com/poster.png)

___

# Day 1 Agenda
- Introductions
- What is the story of your (folder) name?
- Introduction: Melanie's files

### Part I: Folder Poetry

**Reintroduction to computers & computing**
- Folders/file systems
- What is Folder Poetry and how will we be creating it?
- What does it mean to put things into discrete categories
- Examples of folder projects
- Examples of poetic computation gifts
- Folders Anonymous
- Folder Poetry Examples
    - [folderpoetry.club](folderpoetry.club)
    - Laurel Schwulst's adapatation of Folder Poetry in their _Writing as Metadata_ class at Yale: [metadatarocks.nfshost.com](metadatarocks.nfshost.com)
    
**BREAK**

### Part II: Terminal & Bash
- The terminal and Bash
- [Technical requirements for P2P Folder Poetry](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#folder--file-requirements-for-p2p-folder-poetry)
- Introduction of navigating the command line by walking through a garden
    - [click this link to download a garden-of-forking-paths](https://melanie-hoff.com/folder-poetry/garden-of-forking-paths.zip). Uncompress this zip file and take note of what folder it is in. Downloads perhaps?
    - we will explore the garden-of-forking-paths with Bash together
    - we will add to the garden
- Anatomy of Bash Prompt 
- [Let's customize our Terminal](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#to-edit-your-bash_profile)

**Creative Writing**
- Draw out folder poem ideas
- share them within your groups and then with the class
- work in class on making them
- [Installation for Day 2](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#installation-for-day-2)



___

# Technical Notes

- 📁[Click to download the garden-of-forking-paths](https://melanie-hoff.com/folder-poetry/garden-of-forking-paths.zip). Uncompress this zip file and take note of what folder it is in. Downloads perhaps?

### Folder & File Requirements for P2P Folder Poetry
- 🔴 For our folder poetry, every file has to have something in it, and every folder has to eventually have a file in it.
- Naming files and folders
    - 🔴 All lowercase
    - 🔴 No spaces.
        - Underscores and dashes are ok (for example, `my_folder` or `my-folder`)
- 🔴 All files must have a file extension such as `.txt`
- 🔴 Keep track of your file path. Whenever we are computing, we are always doing so from a specific location in your computers file tree.
    - `../../../` This line represents a file path 3 levels deep.

### Bash Commands

| Command                                    | Description                                   |
| ------------------------------------------ | --------------------------------------------- |
| `cd`                                       | change directory                              |
| `cd ..`                                    | change directory one level back               |
| `ls`                                       | list contents of directory                    |
| `pwd`                                      | print working directory                       |
| `open .`                                   | (macOS) open the current folder in Finder     |
| `explorer.exe .`                           | (Windows) open the current folder in Explorer |
| `open filename.txt`                        | (macOS) opens file in Text Edit               |
| `notepad.exe filename.txt`                 | (Windows) opens file in Notepad               |
| `cat filename.txt`                         | print contents of file                        |
| `touch filename.txt`                       | create a file named filename.txt              |
| `mkdir foldername`                         | create a folder named foldername .            |
| `rm filename.txt` .                        | remove a file                                 |
| `rm -r foldername`                         | remove a folder                               |
| `mv filename.txt newfilename.txt`          | rename a file                                 |
| `cp filename.txt filename2.txt`            | copy file                                     |
| `say "hello, what is poetic computation?"` | (macOS) speak out loud                        |
| `man cd`                                   | show the manual for 'cd'. Press q to quit     |

### Keyboard Terminal Shortcuts
| Command               | Description            |
|-----------------------|------------------------|
| Up + Down Arrow keys | scroll through history |
| Tab Key               | autocomplete           |
|CMD + CTRL + SPACE     |Emoji Keyboard (Mac OS) |


### Editing a text file
| command              | Description                       |
| -------------------- | --------------------------------- |
| `nano textfile.txt`  | open file in the nano text editor |
| CTRL + X , y , ENTER | exit and save changes             ||

### To edit your ~./bash_profile

_The ~./bash_profile is a configuration file for the terminal._

1. `nano ~/.bash_profile`

    - This command will open your ~./bash_profile in the nano editor


2. `export PS1="🍋 \w\n\u$ "`
    - Add this line to your ~./bash_profile. Change the emoji to customize your Bash prompt.
    - Explanation: `\w` shows your full file path so you'll always know where you are in the terminal, `\n` creates a new line in your bash prompt. `\u` shows your computer username, and `$` symoolizes the end of a bash prompt.

3. `alias tree="find . -not -path '*/\.*' -print | sed -e 's;[^/]*/;|;g;s;|; |;g'"`

    - Also add this line to your ~./bash_profile to be able to show your folder tree from the terminal
    
4. `source ~/.bash_profile`
    - reboot your terminal


### Other fun Bash code

`for i in {1..2000}; do printf ' ♡ 📂 → ➩ ➪ ➫ ➬ ➭ ➮ '; done;` will create an emoji for loop

`curl https://www.ycam.jp/en/` will print out the html of a website in your terminal

___
# 🌿 Installation and Homework for Monday 9/9 at 9:30

### 1. **Installation**

Run each of these Bash lines one after the other by pasting them in your Terminal and pressing ENTR. Please reach out to me or our TAs Brian or Toru on Slack or in person if you receive any errors.

- This installs nvm for node.js. If you are prompted developer tools, say **yes** and then re-paste the line below.

`curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash`    

- Quit your terminal and re-open it.    

- This installs a stable version of node.js. 

`nvm install --lts`  

- This tells your computer to use the stable version of node.js

`nvm use --lts`    

- This installs peer-to-peer software called DAT

`npm install -g dat`   

### 2. **Folder Poem Sketch**
- Consider the [Folder Poetry as Gift Prompt](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#folder-poetry-prompt)
- With paper and pen, sketch some of the structures and details of your folder poem. This can take the form of a paragraph, a mind map, or a list. 
- We will be sharing these with each other and they will be used as the starting point for creating your Folder Poem in class on Monday.

### 3. **_Optional_ Installation**
_Many Mac OS programmers prefer iterm2 than the default Terminal. It is very similar but a little prettier and more customizable_
- [Iterm 2](https://iterm2.com/downloads/stable/iTerm2-3_3_3.zip)

___

# Folder Poetry Prompt
With paper and pen, write or sketch some of the structures of your folder poem. This can take the form of a paragraph, a mind map, or a list. We will be sharing these with eachother. 

💛**Folder Poem as a Gift**
- Consider a person or group who has access to a computer that you would like to give a gift of a folder poem made just for them. This could be a family member, best friend, someone who is part of SFPC YCAM, or yourself <3
- This folder poem can be anything that feels right to you and is specific to your relationship with the person or group you wish to it give to
- Consider how you would like your folder poem to make them feel?
- Consider the many forms it could take,
    - A palace with many rooms and in each room a memory you share with this person
    - Your folder poem could be a map of all the places you would like to go with this person. Inside each place is a description of what you could do together in each of these places
    - It could be a text adventure game made for you and your person to play together.
- Consider your relationship with them and specific moments or memories you share
- What are some things that you often think about when you think about them and how could you incorporate these into a folder poem gift for them?

**Optional: The village is another prompt that I have given in the past. Feel free to incorporate parts of it in you Folder Poem Gift**

🏡 **A Village You Want to Live In**
- your village does not have to be realistic or even physically probable. What would your ideal living environment look like? What is your utopia?
- What is your village called?
- Consider how you would like to share space with others in your environment.
- In your village, how do you communicate and care for each other? How are people held?
- What kinds of public spaces does your village have and how are they accessed?
- Be as specific as you can. What kinds of plants and animals live in your village or in your garden at home? What kinds of rooms does your home contain? What objects and feelings do these rooms hold for you?
- Consider the ephemeral aspects of your village as much as the physical aspects.
- What are the emotional qualities of the spaces in your village?
- What is the weather like in your village?
- How are different parts of your village accessed and by whom?

<br/>
<br/>

# Day 2 Agenda 

### Welcome back everyone!

- Salon/cave debrief
    - soft documents + zines during break

**🗓 Today's Schedule**
- Sharing sketches
- New commands for folder poetry
- Writing folder poetry in class
- Sharing our poems on the P2P web

<br/>  

**Genesis of folder poetry**
- The jokes embedded in idiosynchratic folder organization
- [Oasis](https://mfowler.info/work/oasis)

<br/>

**Showing Folder Poetry at the Showcase**
- As a poster 
- On your laptop for the audience to explore
- Another way(??)   
<br/>

# Sharing Sketches

- Please take the next 5 minutes to silently consider the prompt and sketch on your paper your idea of a [folder poem as gift](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5#folder-poetry-prompt)
- We will share our sketches to gain feedback and inspiration from each other
- count off into groups, 1,2,3,4,5
    - share your sketches and how you each of you are thinking of interpreting the prompt
    - We will share in groups of 4 for **15 minutes**. Each person should get 4 minutes each to discuss their folder poem idea with the group and receive feedback
- Now we'll come together as a class and share as a group 
    - What came out of your discussions? What did you notice?
<br/>

# ✍️ New Commands for Folder Poetry

Before writing more folder poetry let's learn a few more Bash commands.
<br/><br/>


### 🗂 Preparation

For testing new commands let's create a folder to experiment with them so they wont interfere with our folder poem

1. Open Terminal
2. enter `cd` (this brings us to home folder in case we're not already there)
3. `mkdir test-folder` (this creates a folder called test-folder)
4. `cd test-folder` (this goes into test-folder)
<br/>

### 🌱 Review
| Command                                    | Description                                   |
| ------------------------------------------ | --------------------------------------------- |
| `cd`                                       | change directory                              |
| `cd ..`                                    | change directory one level back               |
| `ls`                                       | list contents of directory                    |
| `mkdir foldername`                       | makes a folder                              |
| `touch filename.txt`                    | makes a file               |
| `rm -rf folder`                            | removes a folder (or file)                 |
| `cat filename.txt`                       | prints the contents of a file                |
| `mv oldname.txt newname.txt`            | renames a file (or folder)             |
<br/>


### 🔮 `folder-spell`

`folder-spell` is a folder poetry generator that came out of a conversation our TA Brian Solon and i had on the bus yesterday. It makes writing sentences with folders go very quickly.

- It creates a series of nested folders with a text file at the end.
- The first words you write after `folder-spell` will become a series of nested folders. The text within quotations will become the contents of a text file.

**Installation**

- enter the entire following line in your terminal
    - `curl https://gist.githubusercontent.com/solon/27106a5389c61dcb83fb25fa9c20787d/raw/folder-spell.sh > ~/folder-spell.sh && chmod u+x ~/folder-spell.sh && echo $'folder-spell() {\n ~/folder-spell.sh \"$@\" \n}' >> ~/.bash_profile`
-   `source ~/.bash_profile`

**Usage**

- `folder-spell these are words "this is some text"`
-  ![](https://melanie-hoff.com/folder-spell.png)


- Another example usage:
    - `folder-spell this is a folder poem generator "the first words you write will become a series of nested folders. The text within quotations will become the contents of a text file"`<br/><br/>

### 📃 `echo`

This handy command allows you to write text into a file without using a text editor such as nano

**Usage**

`echo "this is the contents of a text file" > test.txt`<br/><br/>

### 🗣 `say` 

The `say` command makes your computer speak out loud

**Usage**

- `say I am your computer......... use my logic to write poetry`

**Changing the voice style**

- `say -v ?` lists all the voice options
- `say -v yuri hello I am not the default voice`

<br/>
<br/>

# 📁 Writing Folder Poetry in Class
We will spend a large part of class time today creating folder poetry
<br/> 
If you haven't already, follow these steps before you begin
- Open terminal, write `cd` + ENTR
- `mkdir folder-poetry`
- `cd folder-poetry`
- `mkdir yournames-gift`
- inside the folder, yournames-gift is where you will create you folder poems
    
### Writing your poem in a language other than English?

- We have a soft preference that folder poems be written in english but it is optional and after all, your gift recipient may not speak english. **If your poem is not in english**, please include an english description of what your poem is about and who you made it for a file called **about.txt** within the yourname-gift folder.
    - leave this in the the following location: folder-poetry/yourname-gift/about.txt

<br/>
<br/>

# 🕸 Sharing our Poems on the P2P Web

This is the part of class where we will share our poems with each other on a local network on the distributed web.

## **Introduction**

- P2P introduction and description of DAT and "the cloud"
- What do we mean by Peer-to-Peer?
- Dat is a protocol for sharing data between computers.
- Dat’s strengths are that data is hosted and distributed by many computers on the network, that it can work offline or with poor connectivity
- The Distributed Web is about decentralization of servers and control
- Data on the didtributed web is not indexed which means it is not searchable
- We are creating a local network island away from the default(larger) internet

<br/>

## Creating the P2P network using DAT

- This part might feel tricky. Don't worry if you miss a step and encounter any problems. It’s ok, they will be easily resolved. TAs and i are here to help you :)
- **Let's get into pairs.** We'll count off to 10 and pair up with your matching number.
    
### Sending your folder poem to the P2P web
- Open a totally new window in Terminal
- `cd folder-poetry` this brings you into your folder-poetry folder
- `dat share` this starts serving your folder on the P2P web
- copy your hash into this spreadsheet next to your name: [SFPC YCAM Students' Peer-to-Peer address book on the distributed web](https://docs.google.com/spreadsheets/d/1h-xDzg3RJ-Xf8A8ItPKm-GGl3T8qBfJcExM3vTsZxtk/edit?usp=sharing)
- minimize this window so you dont touch it. Your folder will only be sharing as long as this terminal window is active and dat share-ing.

### Creating a new folder for your classmates' folder poems
- In Terminal, write `cd` + ENTR
- `mkdir folder-poetry-class`
- `cd folder-poetry-class`
- copy your parnter's hash from [the spreadsheet](https://docs.google.com/spreadsheets/d/1h-xDzg3RJ-Xf8A8ItPKm-GGl3T8qBfJcExM3vTsZxtk/edit?usp=sharing)
- `dat clone paste-your-parnters-hash-here` _(!!) paste your partners hash after "dat clone"_
- `tree` 
    - you should be able to see your parnters folder poem and explore it!
    
### Syncing changes with your parnter
- Now that you have cloned your parnterns folder poem, lets see live changes in them using Dat.

**First let's make a change in our own poem by navigating back to your folder-poetry folder **
- `cd ~/folder-poetry/your-gift` (!!) edit this line to be `yournames-gift` 
- now leave a message for your parnter in your poem by writing `echo "hello parnter! ♡ 📂 → ➩ ➪ ➫ ➬ ➭ ➮" > hello-folder-friend.txt` (feel free to customize)
- check that this file was created by writing `cat hello-folder-friend.txt`

**Now we'll sync our parntners changes**
- `cd ~/folder-poetry-class`
- `ls` to see your partners hash 
- `cd your-parnters-hash-here`
- `dat sync`
- `tree`
    - you should see the file your partner left for you <3


    




📞 🌿 [SFPC YCAM Students' Peer-to-Peer address book on the distributed web](https://docs.google.com/spreadsheets/d/1h-xDzg3RJ-Xf8A8ItPKm-GGl3T8qBfJcExM3vTsZxtk/edit?usp=sharing)


