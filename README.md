# Table of Contents
  1. [History](#history)
      1. [GNU/Linux Philosophy](#history--philosophy)
      1. [GNU/Linux Distributions](#history--distributions)
  1. [Commands](#commands)
  1. [Users](#users)
  1. [Groups](#groups)
  1. [Permissions](#permissions)
  

## History

<a name="history--philosophy"></a><a name="1.2"></a>
> Based on years of conversations, I am convinced that part of the cause of the problem is the tendency to call the system Linux rather than GNU, and describe it as open source rather than free software.
> -- Richard Stallman


What is GNU? GNU is a recursive acronym for "GNU's Not Unix!"

The GNU is a system that is used every day by many people all of the world. Although many users refer to it by name "Linux" without knowing that it is GNU system that they actually use.

Linux is just a part of this system. It is a kernel:
the program in the system that allocates the machine's resources to the other programs that user runs.

So instead of sounding smart and showing off let's be really smart and know things in their right ways.

You can read about GNU project following these links:

[The GNU Manifesto](https://www.gnu.org/gnu/manifesto.html)

[What is free software?](https://www.gnu.org/philosophy/free-sw.html)

[Philosophy](https://www.gnu.org/philosophy/philosophy.html)

- `Do one thing and do it well`
- `Release early, release often `
- `Free as in Freedom (the GNU philosophy)`

<a name="history--distributions"></a>
#### GNU/Linux Distributions

  A GNU/Linux distribution is an operating system made from a software collection, which is based upon the Linux kernel and, often, a package management system.
      Widely used distributions are:

  **Debian**
  - `Ubuntu, a desktop and server distribution derived from Debian`
  - `Linux Mint Debian Edition`
  - `Linux Mint, a distribution based on and compatible with Ubuntu.`

  **Fedora**
  - `Red Hat Enterprise Linux (RHEL)`
  - `CentOS, a distribution derived from the same sources used by Red Hat`

  **Arch Linux**
  - `Manjaro Linux`

  **Gentoo**
  - `Chrome OS, Google's commercial operating system`

You may find and use other distributions.
Each one will have its installation guide, just follow the steps and you'll be fine.
You don't need to be a hacker to install an Ubuntu on your machine.
Though consider which distribution suits your needs best.

##### Which one to choose ?

Distribution name | Reason(s) for using
------------ | -------------
Red Hat Enterprise (RHEL) | You are a manager and you want a good support contract.
CentOS| You want Red Hat without the support contract from Red Hat.
Fedora | You want Red Hat on your laptop/desktop.
Linux Mint | You want a personal graphical desktop to play movies, music and games.
Debian | Good for servers, laptops, and any other device.
Ubuntu | Good for new users. Has a new release each 6 months.
Kali | Designed for digital forensics and penetration testing. Good for hacking (they say).
others | Advanced users may prefer Arch, Gentoo, OpenSUSE, Scientific, etc.

**[⬆ back to top](#table-of-contents)**

## Commands

<a name="commands--man"></a><a name="2.1"></a>
#### Man pages
Have you ever came across RTFM? It's an initialism for the expression "read the fucking manual".
Everything could be found in manuals. But you may use search engines too.


<a name="commands--directories"></a><a name="2.2"></a>
#### Directories
- `pwd`
- `cd`
- `absolute and relative paths`
- `path  completion`
- `mkdir`
- `rmdir`
      
<a name="commands--files"></a><a name="2.3"></a>
#### Files
  
- `all  files  are  case  sensitive`
- `everything  is  a  file`
- `file`
- `touch`
- `rm`
- `cp`
- `mv`
- `rename`
        
<a name="commands--filecontents"></a><a name="2.4"></a>
#### File contents
- `head`
- `tail`
- `cat`
- `tac`
- `more  and  less`
- `strings`

<a name="commands--filetree"></a><a name="2.5"></a>
#### File tree
- `filesystem  hierarchy  standard`
- `man  hier`
- `the  root  directory  /`
- `binary  directories`
- `configuration  directories`
- `data  directories`
- `in  memory   directories`
- `/usr  Unix  System  Resources`
- `/var  variable  data`

     
**[⬆ back to top](#table-of-contents)**

## Users

<a name="users--intro"></a><a name="3.1"></a>
#### Intro
- `whoami` The whoami command tells you your username.

- `who` The who command will give you information about who is logged on the system.

- `w` The w command shows you who is logged on and what they are doing.

- `id` The id  command will give you your user id, primary group id, and a list of the groups that you belong to.

- ` su to another user` The  su command allows a user to run a shell as another user.
    You can also su to become root, when you know the root password.

    ```bash
    su root
    ```

<a name="users--profiles"></a><a name="3.2"></a>
#### User profiles
- `system  profile`
- `~/.bash_profile etc.`
      
## Groups

<a name="groups--intro"></a><a name="4.1"></a>
#### Groups

- `groupadd`

- `usermod`

- `groups`


**[⬆ back to top](#table-of-contents)**

## Permissions

<a name="permissions--file"></a><a name="5.1"></a>
#### File permissions

- `file  ownership`

- `list of special files`

- `permissions`
     

**[⬆ back to top](#table-of-contents)**

