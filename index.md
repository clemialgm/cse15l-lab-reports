report1

**Installing VScode**

First, we downloaded and installed Visual Studio Code from [link1](vsc webpage)

![image](p8.png)

My computer is MAC.

![Image](p1.png)

**Remotely Connecting**

Second, we connect to a remote computer over the Internet to do work there.
I typed my course-specific account and entered my password.

![image](p9.png)

This is the screenshot showing that I have successfully connected.

![Image](p2.png)

**Trying Some Commands**

Then, I tried to run some commands.
I ran: ls, ls -a, ls -lat

![image](p10.png)

![image](p11.png)

![image](p12.png)

And this is the screenshot of the terminal

![Image](p3.png)

**Moving Files with scp**

Then, I used scp to move files over SSH.

![image](p13.png)

After login into my account, the directory is formed and the code can be run.
![Image](p4.png)
![Image](p5.png)

**Setting an SSH Key**
We use the ssh-keygen command to make a public private key pair for ease of login to the remote computer 

![image](p14.png)

Here is the screenshot of using ssh to store public key on the server, and the private key in a  on the client. 
Then we can use the public key to log in without password.
![Image](p6.png)

**Optimizing Remote Running**

This is the screenshot of running a certain command.

![image](p15.png)

By doing so, there is no need to seperate the commands into different steps.
![Image](p7.png)


