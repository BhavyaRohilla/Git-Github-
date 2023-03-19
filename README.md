# **_Version Control System :-_**

<ol>
   <li>Version control is a management software responsible for managing changes to computer programs, documents, large websites, or other collections of information.</li>
   <li>Easy recovery of files/folders.</li>
   <li>Rollback to the previous versions.</li>
   <li>Informs us about Who, What, When, Why changes have been made.</li>
 </ol>

---

<br>
<br>

# **_History of VCS :-_**

## **_Local VCS :-_**

<ol>
<li>Changes are stored in a database, along with timestamp.</li>
<li>Code is in Local System.</li>
 </ol>
 
Cons : Project can be lost, if your hard-disk is corrupted.

---

## **_Centralized VCS :-_**

### **Repository :-**

A directory where your project resides. It can be a local folder in your computer or a remote directory on a server.

### **There are 2 types of repository :-**

1. Local Repository
2. Central Repository

Centralized VCS contain just one repository i.e central repository and each user gets to work on the same.

<br>

![Alt text](images/Screenshot%20from%202023-03-17%2002-02-21.png)

<br>

### **Cons :**

1. If the central repo goes down even for an hour.
2. You'll lose the project if the hard disk of the central server goes down.

---

## **_Distributed VCS :-_**

1. Distributed version control systems contain multiple repositories. Each user has their own local repository & there is a central repository where the final code resides.
2. Provides full Back-up of the project.
3. Git is an example of distributed VCS.

<br>

![Alt text](images/Screenshot%20from%202023-03-17%2002-32-42.png)

<br>

---

<br><br>

# **_How is Git created?_**

"Git was created in 2005 by **Linus Torvalds**. (creator of Linux kernel)"

## **_Git :-_**

1. Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
2. Git stores snapshot of your project (not differences)

<br>

![Alt text](images/Screenshot%20from%202023-03-17%2002-39-04.png)

<br>

### **Git Features :-**

<ul>
<li>Collaboration</li>
<li>Storing Versions</li>
<li>Analyse the code changes</li>
<li>Distributed.</li>
<li>Almost everything is Locally.</li>
<li>Non-linear/Branching.</li>
<li>Secure/Integrity.</li>
<li>Speed.</li>
</ul>

<br>

---

<br><br>

# **_Setting Up the Environment_**

## **"For Windows : Use Git Bash"**

## **"For Mac-os / Linux : Use Terminal"**

<br>

### **# To check the git version :-**

<ul><li>git --version</li></ul>
<br>

### **# configuration of global variables**

<ul>
<li>git config --global user.name "Bhavya Rohilla"</li>
<li>git config --global user.email "officialbhavyarohilla@gmail.com"</li>
</ul>

![Alt text](images/Screenshot%20from%202023-03-18%2010-50-59.png)
<br>

![Alt text](images/Screenshot%20from%202023-03-18%2010-50-19.png)
<br>

### **Git Config list :-**

List all variables set in config file, along with their values.

<li>git config --list</li>
<br>

![Alt text](images/Screenshot%20from%202023-03-18%2010-47-31.png)

<br>

---

<br><br>

# **_Command Line Tool_**

## **"For Windows : Use Git Bash"**

## **"For Mac-os / Linux : Use Terminal"**

<br>

### **1. pwd(Print working directory) :-**

In Unix-like and some other operating systems, the pwd command (print working directory) writes the full pathname of the current working directory to the standard output.
<br>

![Alt text](images/Screenshot%20from%202023-03-18%2011-08-31.png)

<br>

### **2. ls(list) :-**

The ls command is used to list files. "ls" on its own lists all files in the current directory except for hidden files.
<br>

![Alt text](images/Screenshot%20from%202023-03-18%2014-10-36.png)

<br>

#### **Others ls :-**

#### **1.) ls -l :** Show list with details.

#### **2.) ls -a :** Show hide items with details.

#### **3.) ls -al :** Combine 1,2.

<br>

### **3. Change Directory :-**

The cd command allows you to move between directories. The cd command takes an argument, usually the name of the folder you want to move to, so the full command is cd your-directory . Now that we moved to your Desktop, you can type ls again, then cd into it.

<br>

![Alt text](images/Screenshot%20from%202023-03-18%2014-26-24.png)

### **4. cd .. :-**

this command is used to move to the parent directory of current directory, or the directory one level up from the current directory. “..” represents parent directory.

<br>

![Alt text](images/Screenshot%20from%202023-03-18%2014-32-13.png)

<br>

### **5. Create Files & Folders :-**

<br>
<ul>
<li>

#### **mkdir :-** The mkdir stands for 'make directory'. With the help of mkdir command, you can create a new directory wherever you want in your system. Just type **<mark>mkdir dir name</mark>** , in place of **<mark>dir name</mark>** type the name of new directory, you want to create and then press enter.

<br>

![Alt text](images/Screenshot%20from%202023-03-19%2010-44-19.png)

</li>

<br>

<li>

#### **mkdir dir dir dir :-** Create multiple Directories.

<br>

![Alt text](images/Screenshot%20from%202023-03-19%2010-44-59.png)

</li>

<br>

<li>

#### **mkdir dir/dir:-** Create Directory in Directory.

<br>

![Alt text](images/Screenshot%20from%202023-03-19%2010-46-00.png)

<br>

![Alt text](images/Screenshot%20from%202023-03-19%2010-46-54.png)

</li>

<br>

<li>

#### **touch file.txt:-** The touch command is a standard command used in UNIX/Linux operating system which is used to create, change and modify timestamps of a file.

<br>

![Alt text](images/Screenshot%20from%202023-03-19%2011-00-07.png)

</li>

<br>

<li>

#### **open file.txt:-** open a file.

<br>

![Alt text](images/Screenshot%20from%202023-03-19%2011-00-31.png)

 </li>
</ul>

<br>

### **5. Remove Files & Folders :-**

<br>

<ul>
<li>

#### **rm file.txt:-** Use the rm command to remove files you no longer need.

<br>

![Alt text](images/Screenshot%20from%202023-03-19%2011-11-51.png)

<br>
</li>

<br>

<li>

#### **rm f3/file.txt:-** remove file in directory.

<br>

</li>

<br>

<li>

#### **rmdir dir:-** The rmdir command removes the directory, specified by the Directory parameter, from the system.

<br>

</li>
<li>

#### **rm -R dir:-** To delete a directory with all its content recursively use rm command with argument -R. Use the argument -f with the argument -R to delete the directory forcefully.

</li>

</ul>
