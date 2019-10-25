![](https://github.com/melaniehoff/Peer-to-Peer-Poetry/blob/master/folder-cities.jpg)

# Peer-to-Peer Folder Poetry

What if we could transform our online networks from something we passively receive to something we actively create? Folder Poetry is the practice of using the structure of computer folder organization as a new kind of poetic form like the haiku or iambic pentameter. By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry. In this workshop we will collectively create peer-to-peer folder poetry using the command line and Dat. Through lecture, examples, and writing folder poetry as meditation, we will explore the narrative qualities of folder structures and Dat as a tool for building digital spaces with and for our networks.

In this session we will get intimate with computers and write poetry with their logic. This workshop is an introduction to writing folder poetry, the P2P protocol Dat, and navigating the command line interface using Bash.

Together, we will create living networked poetry through connecting folders on the peer-to-peer web for each other to inhabit and explore.

This workshop assumes no coding experience and simultaneously takes the position that everyone who interacts with computers in some way is already a programmer.

**[Always Already Programming](#always-already-programming)**

 
**[Bash Drawings made for Folder Poetry by Taeyoon Choi](https://docs.google.com/presentation/d/1WV_vFHtKB7BUBc3P_oGVlLry6W_8K_fJkJiWzisXonY/edit#slide=id.g60e8df3e27_0_113)**


## Workshops
_P2P Folder Poetry has been taught in multiple places. These are the notes and slides for each place._
- 🔴[SFPC Fall 2019](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/sfpc-fall-2019.md)
- [Radical Networks - October 2019](https://github.com/melaniehoff/Peer-to-Peer-Folder-Poetry/blob/master/radical-networks.md)
- [SFPC YCAM - September 2019](https://gist.github.com/melaniehoff/96bffd279b0ea66f61291e231283aab5) 
    - 📒[Download the Class Zine here](https://melanie-hoff.com/folder-poetry/sfpc-ycam/zine-pdfs-ycam-folder-poetry.zip)
- [SFPC Detroit - August 2019](https://gist.github.com/melaniehoff/7cda150870c869c1990a744dddbd286f) 
    - 📒[Download the Class Zine here](https://melanie-hoff.com/folder-poetry/sfpc-detroit/detroit-zine-reader.pdf.zip)
- [SFPC Detroit - June 2019](https://github.com/melaniehoff/folderpoetry/blob/master/README.md)

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


## Vocabulary
**Word** | **Notes**
--- | ---
Folder Poetry| The practice of using the structure of computer folder organization as a new kind of [poetic form](https://en.wikipedia.org/wiki/Poetry#Forms) like the [haiku](https://en.wikipedia.org/wiki/Haiku) or [iambic pentameter](https://en.wikipedia.org/wiki/Iambic_pentameter). By naming and nesting folders and files, we can create unfolding narratives, rhythmic prose, and choose-your-own-adventure poetry.
terminal | A desktop application to control and make changes to your operating system by typing text commands. In this class we'll use the terminal to create folder poetry.
terminal commands | text commands to control your computer when entered into a command prompt like the terminal. The commands we'll learn will be in a language called Bash.
Bash | is the programming language we use in the terminal, often one line at a time, but we can also put Bash code in a file and run that file.
Peer-to-Peer | Peer-to-peer computing is a way to make distributed networks in which each computer can act as a server for the others, allowing shared access to files without the need for a central server.
Dat | is a data distribution tool for publishing on peer-to-peer networks.
folder | (also referred to as directory) is an organizational regime imposed on your computer used to store and organize files and other folders
file | is an object on a computer which stores data, information, settings, or commands to be used with various computer programs
file types/formats/extensions | indicate how data has been stored and how to read or open files in specific programs. for example, `.txt` files open in a text editor, `.jpg` files open in an image viewer/editor. full list of file formats and extensions [here](https://en.wikipedia.org/wiki/List_of_file_formats)
file path | tells you the location of a file in a system. for example `users/username/desktop/folder_poetry_club`

# Always Already Programming


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
 
 
## Acknowledgments & Thank You

**_Thank you these collaborators and friends for guiding and inspiring Peer-to-Peer Folder Poetry_**

- [Max Fowler](https://mfowler.info/) for creating [Oasis](https://mfowler.info/work/oasis/) which was one of the early sparks for me creating spatial metaphors with folders and was a beautiful example of collaborating on these folder structures through SSH
- [Taeyoon Choi](http://taeyoonchoi.com/) for inviting me to teach this class at SFPC in Detroit and Japan and for suggesting I name it Folder Poetry instead of Folder Structure Narratives. Another thank you for encouraging me to bring Folder Poetry to the P2P web. And for the [Bash drawings](https://docs.google.com/presentation/d/1WV_vFHtKB7BUBc3P_oGVlLry6W_8K_fJkJiWzisXonY/edit#slide=id.g60e8df3e27_0_113) they created for Folder Poetry in Detroit June 2019!
- [Neta Bomani](https://www.netabomani.com/) for designing and printing the first [Folder Poetry with Bash zine](https://github.com/melaniehoff/folderpoetry/blob/master/assets/pdf/folder_poetry_zine_pages.pdf) in Detroit June 2019.
- [Callil Capuozzo](https://callil.com/) for guiding me through how Dat works and suggesting ways to integrate Folder Poetry with Dat
- [Laurel Shwulst](http://laurelschwulst.com/) for their many tender Dat Projects and for creating http://p2pforever.org/, a charming and helpful P2P resource
- [Dan Taeyoung](https://dantaeyoung.com/) for giving incredible feedback
- [Lauren Gardner](http://laurengardner.com/) for iniviting me to teach Folder Poetry at SFPC Fall 2019 and for helping to create sustainable spaces for creative ideas always





 

    
    






