# Welcome Again!
## We will talk about:
**1. Finding Stuff.**

**2. Filtering with grep.**

**3. A brief about Piping.**

**4. Creating Files and cat command.**

## Finding Stuff:
You can use the Command `locate` to know the location of a file in the system:

![](https://media.geeksforgeeks.org/wp-content/uploads/2-415.png)

You can use also `which` command:

![](https://media.geeksforgeeks.org/wp-content/uploads/which-main.png)

## Filtering with grep and a brief about piping:
The command `grep` you can use it for Filtering the result of a process you did, for example if you have a file name `IPs.txt` containing Much IPs and you want to filter the file to reach a specific IP you can use `grep "The IP"`. And if you want to use the filtered result with another process here you use `|` It enables you to do two operations with one line, the second depends on the first, for example:
`cat IPs.txt | grep "192.168.1.1"` here the system will open the file`IPs.txt` and will filter it to give you the Ip that you searched about.

## Creating Files and cat command:
The `cat` command followed by a filename will display the contents of that file, but to
create a file, we follow the `cat` command with a redirect, denoted with the > symbol, and
a name for the file we want to create. Here’s an example:
![](https://www.howtogeek.com/wp-content/uploads/2018/02/clt_top.png?height=200p&trim=2,2,2,2&crop=16:9)

When you press `ENTER`, Linux will go into interactive mode and wait for you to start
entering content for the file, and when you finish press `CTRL + D` to exit.

To view the file you can use `cat file.txt`:

![](https://static.javatpoint.com/linux/images/linux-cat-display.png)

And if you want to add more content to your existing file you use `cat >> file.txt` and the system will allow you to write like the Previous Command. For replacing the content you use the first command `cat > file.txt` with an existing file.

_**We will finish here and continue later... Thanks For Reading.**_

## **`Twitter : @MuhammadMJabr`**
