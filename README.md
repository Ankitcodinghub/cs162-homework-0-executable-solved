# cs162-homework-0-executable-solved
**TO GET THIS SOLUTION VISIT:** [CS162 Homework 0-Executable Solved](https://www.ankitcodinghub.com/product/cs162-homework-0-executable-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91025&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS162 Homework 0-Executable Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1.2 Vagrant

We have prepared a Vagrant virtual machine image that is preconfigured with all the tools necessary to run and test your code for this class. Vagrant is an tool for managing virtual machines. You can use Vagrant to download and run the virtual machine image we have prepared for this course.

Note: If you do not want to set up Vagrant on your own machine, take a look at the CS162 VM provisioner2 on GitHub for more options. You can run the VM on a variety of hypervisors, cloud computing platforms, or even on bare metal hardware.

(If you are using Windows, these steps might not work – skip to the section below labeled “Windows”)

<ol>
<li>Vagrant depends on VirtualBox (an open source virtualization product) so first you will need to download and install the appropriate version from the VirtualBox website3. We will talk in class about virtual machines, but you can think of it as a software version of actual hardware.</li>
<li>Now install the appropriate version of Vagrant from the Vagrant website4.</li>
<li>Once Vagrant is installed, type the following into your terminal:
<pre>     $ mkdir cs162-vm
     $ cd cs162-vm
     $ vagrant init cs162/spring2018
     $ vagrant up
     $ vagrant ssh
</pre>
These commands will download our virtual machine image from our server and start a ssh session. Note the “up” command will take a while, and requires an Internet connection.
</li>
<li>You need to run all vagrant commands from the cs162-vm directory you created earlier. Do NOT delete that directory, or vagrant will not know how to manage the VM you created.</li>
<li>You can run vagrant halt to stop the virtual machine. If this command does not work, make sure you are running it from your host machine, not inside SSH. To start the virtual machine the next time, you only need to run vagrant up and vagrant ssh. All of the other steps do not need to be repeated.</li>
</ol>
1 https://cs162.eecs.berkeley.edu/autograder

2 https://github.com/Berkeley-CS162/vagrant/ 3https://www.virtualbox.org/wiki/Downloads 4 http://www.vagrantup.com/downloads.html

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1.2.1 Windows (OS X and Linux users can skip this section)

Since windows does not support ssh, the “vagrant ssh” command from the above steps will cause an error message prompting you to download Cygwin or something similar that supports an ssh client. Here5 is a good guide on setting up Vagrant with Cygwin in windows.

If you get an error about your VM bootup timing out, you may need to enable VT-x (virtualization) on your CPU in BIOS.

1.2.2 Troubleshooting Vagrant

If “vagrant up” fails, try running “vagrant provision” and see if it fixes things. As a last resort, you can run “vagrant destroy” to destroy the VM. Then, start over with “vagrant up”.

1.2.3 Git Name and Email

Run these commands to set up your Name and Email that will be used for your Git commits. Make sure to replace “Your Name” and “your email@berkeley.edu” with your REAL name and REAL email.

<pre>$ git config --global user.name "Your Name"
$ git config --global user.email "your_email@berkeley.edu"
</pre>
1.2.4 ssh-keys

You will need to setup your ssh keys in order to authenticate with GitHub from your VM.

New GitHub Users

SSH into your VM and run the following:

<pre>$ ssh-keygen -N "" -f ~/.ssh/id_rsa
$ cat ~/.ssh/id_rsa.pub
</pre>
The first command created a new SSH keypair. The second command displayed the public key on your screen. You should log in to GitHub and go to github.com/settings/ssh6 to add this SSH public key to your GitHub account. The title of your SSH keypair can be “CS 162 VM”. The key should start with “ssh-rsa” and end with “vagrant@development”.

Experienced GitHub Users

If you already have a GitHub SSH keypair set up on your local machine, you can use your local ssh- agent to utilize your local credentials within the virtual machine via ssh agent forwarding. Simply use vagrant ssh to ssh into your machine. The Vagrant should enable SSH agent forwarding automatically. If this doesn’t work, you can also use the instructions in the previous “New GitHub Users” section.

1.2.5 Repos

You will have access to two private repositories in this course: a personal repository for homework, and a group repository for projects. We will publish skeleton code for homeworks in Berkeley-CS162/ta7 and we will publish skeleton code for group projects in Berkeley-CS162/group08. These two skeleton

5 https://github.com/Berkeley-CS162/vagrant/blob/master/Windows.md 6 https://github.com/settings/ssh

7 https://github.com/Berkeley-CS162/ta/

8 https://github.com/Berkeley-CS162/group0/

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
code repositories are already checked out in the home folder of your VM, inside ~/code/personal and ~/code/group.

You will use the “Remotes” feature of Git to pull code from our skeleton repos (when we release new skeleton code) and push code to your personal and group repos (when you submit code). The Git Remotes feature allows you to link GitHub repositories to your local Git repository. We have already set up a remote called “staff” that points to our skeleton code repos on GitHub, for both your personal and group repo. You will now add your own remote that points to your private repo so you can submit code.

You should have received the link to your personal private GitHub repo when you registered with the autograder earlier. Add a new remote by doing the following steps in your VM:

<ol>
<li>First cd into your personal repository
<pre>     cd ~/code/personal
</pre>
</li>
<li>Then visit your personal repo on GitHub and find the SSH clone URL. It should have the form “git@github.com:Berkeley-CS162/…”</li>
<li>Now add the remote
<pre>     git remote add personal YOUR_GITHUB_CLONE_URL
</pre>
</li>
<li>You can get information about the remote you just added
<pre>     git remote -v
     git remote show personal
</pre>
</li>
<li>Pull the skeleton, make a test commit and push to personal master
<pre>     git pull staff master
     touch test_file
     git add test_file
     git commit -m "Added a test file."
     git push personal master
</pre>
In this course, “master” is the default Git branch that you will use to push code to the autograder. You can create and use other branches, but only the code on your master branch will be graded.
</li>
<li>Within 30 minutes you should receive an email from the autograder. (If not, please notify the instructors via Piazza). Check cs162.eecs.berkeley.edu/autograder9 for more information.</li>
</ol>
1.3 Autograder

Here are some important details about how the autograder works:

<ul>
<li>The autograder will automatically grade code that you push to your master branch, UNLESS the assignment you are working on is LATE.</li>
<li>If your assignment is late, you can still get it graded, but you will be using slip days. You can request late grading using the autograder’s web interface at cs162.eecs.berkeley.edu/autograder10.
9 https://cs162.eecs.berkeley.edu/autograder 10 https://cs162.eecs.berkeley.edu/autograder• •
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
1.4

</div>
<div class="column">
Your final score will be the best score that you received in any build. So, even if you push code that fails more autograder tests than before, it will not decrease your score.

If your score does not improve when you push new code, it will not affect your slip days. So, if you request a build after the deadline that does not improve your score, you will not have to use slip days.

Editing code in your VM

</div>
</div>
<div class="layoutArea">
<div class="column">
The VM contains a SMB server that lets you edit files in the vagrant user’s home directory. With the SMB server, you can edit code using text editors on your host and run git commands from inside the VM. This is the recommended way of working on code for this course, but you are free to do whatever suits you best.

1.4.1 Windows

1. Open the file browser, and press Ctrl L to focus on the location bar. 2. Type in \\192.168.162.162\vagrant and press Enter.

3. The username is vagrant and the password is vagrant.

You should now be able to see the contents of the vagrant user’s home directory.

1.4.2 Mac OS X

1. Open Finder.

2. In the menu bar, select Go → Connect to Server…. 3. The server address is smb://192.168.162.162/vagrant. 4. The username is vagrant and the password is vagrant.

You should now be able to see the contents of the vagrant user’s home directory.

1.4.3 Linux

Use any SMB client to connect to the /vagrant share on 192.168.162.162 with the username vagrant and password vagrant. Your distribution’s file browser probably has support for SMB out of the box, so look online for instructions about how to use it.

1.5 Shared Folders

The /vagrant directory inside the virtual machine is connected to the home folder of your host machine. You can use this connection if you wish, but the SMB method in the previous section is recommended.

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
2 Useful Tools

Before continuing, we will take a brief break to introduce you to some useful tools that make a good fit in any system hacker’s toolbox. Some of these (git, make) are MANDATORY to understand in that you won’t be able to compile/submit your code without understanding how to use them. Others such as gdb or tmux are productivity boosters; one helps you find bugs and the other helps you multitask more effectively. All of these come pre-installed on the provided virtual machine.

Note: We do not go into much depth on how to use any of these tools in this document. Instead, we provide you links to resources where you can read about them. We highly encourage this reading even though not all of it is necessary for this assignment. We guarantee you that each of these will come in handy throughout the semester. If you need any additional help, feel free to ask any of the TA’s at office hours!

2.1 Git

Git is a version control program that helps keep track of your code. GitHub is only one of the many services that provide a place to host your code. You can use git on your own computer, without GitHub, but pushing your code to GitHub lets you easily share it and collaborate with others.

At this point, you have already used the basic features of git, when you set up your repos. But an understanding the inner workings of git will help you in this course, especially when collaborating with your teammates on group projects.

If you have never used git or want a fresh start, we recommend you start here11. If you sort of understand git, this presentation12 we made and this website13 will be useful in understanding the inner workings a bit more.

2.2 make

make is a utility that automatically builds executable programs and libraries from source code by reading files called Makefiles, which specify how to derive the target program. How it does this is pretty cool: you list dependencies in your Makefile and make simply traverses the dependency graph to build everything. Unfortunately, make has very awkward syntax that is, at times, very confusing if you are not properly equipped to understand what is actually going on.

A few good tutorials are here14 and here15. And of course the official GNU documentation (though it may be a bit dense) here16.

For now we will use the simplest form of make: without a Makefile. (But you will want to learn how to build decent Makefiles before long!) You can compile and link wc.c by simply running:

$ make wc

This created an executable, which you can run. Try

$ ./wc wc.c

How is this different from the following? (Hint: run “which wc”.)

$ wc wc.c

11http://git-scm.com/book/en/Getting-Started 12http://goo.gl/cLBs3D

13 http://think-like-a-git.net/

14 http://wiki.wlug.org.nz/MakefileHowto 15http://mrbook.org/blog/?s=make

16 http://www.gnu.org/software/make/manual/make.html

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Your first assignment is going to be to modify wc.c, so that it implements word count according to the specification of “man wc”, except that it does not need to support any flags and only needs to support a single input file, (or STDIN if none is specified). Beware that wc in OS X behaves differently from wc in Ubuntu. We will expect you to follow the behavior of wc in Ubuntu.

2.3 gdb

Debugging C programs is hard. Crashes don’t give you nice exception messages or stack traces by default. Fortunately, there’s gdb. If you compile your programs with a special flag -g then the output executable will have debug symbols, which allow gdb to do its magic. If your run your C program inside gdb it will allow you to not only look get a stack trace, but inspect variables, change variables, pause code and much more!

Normal gdb has a very plain interface. So, we have installed cgdb for you to use on the virtual machine, which has syntax highlighting and few other nice features. In cgdb, you can use i and ESC to switch between the upper and lower panes.

gdb can start new processes and attach to existing processes (which will be useful when debugging your project.)

This17 is an excellent read on understanding how to use gdb.

Again, the official documentation18 is also good, but a bit verbose.

Take a moment to begin working on your wc. Provide the -g flag when you compile your program

with gcc. Start the program under gdb. Set a break point at main. Run to there. Try out various commands. Figure out how to pass command line arguments. Add local variables and try probing their values. Learn about step, next, and break.

2.4 tmux

tmux is a terminal multiplexer. It basically simulates having multiple terminal tabs, but displays them in one terminal session. It saves having to have multiple tabs of sshing into your virtual machine.

You can start a new session with tmux new -s &lt;session_name&gt;

Once you create a new session, you will just see a regular terminal. Pressing ctrl-b + c will create a new window. ctrl-b + n will jump to the nth window.

ctrl-b + d will “detach” you from your tmux session. Your session is still running, and so are any programs that you were running inside it. You can resume your session using tmux attach -t &lt;session_name&gt;. The best part is this works even if you quit your original ssh session, and connect using a new one.

Here19 is a good tmux tutorial to help you get started. 2.5 vim

vim is a nice text editor to use in the terminal. It’s well worth learning. Here20 is a good series to get better at vim. Others may prefer emacs. Whichever editor you choose, you will need to get proficient with an editor that is well suited for writing code.

If you want to use Sublime Text, Atom, CLion, or another GUI text editor, look at 1.4 Editing code in your VM, which shows you how to access your VM’s filesystem from your host.

2.6 ctags

ctags is a tool that makes it easy for you to navigate large code bases. Since you will be reading a lot of code, using this tool will save you a lot of time. Among other things, this tool will allow you to jump to

17http://www.unknownroad.com/rtfm/gdbtut/gdbtoc.html 18https://sourceware.org/gdb/current/onlinedocs/gdb/

19 http://danielmiessler.com/study/tmux/

20 http://derekwyatt.org/vim/tutorials/

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
any symbol declaration. This feature together with your text editor’s go-back-to-last-location feature is very powerful.

Instructions for installing ctags can be found for vim here21 and for sublime here22. If you don’t use vim or sublime, ctags still is probably supported on your text editor although you might need to search installation instructions yourself.

3 Your first assignment 3.1 make

You have probably been using gcc to compile your programs, but this grows tedious and complicated as the number of files you need to compile increases. For this assignment, you will need to write a Makefile that compiles main.c, wc.c, and map.c when make is run (you may want to add the -g gcc flag to this step). It may also help to write a clean target (for make clean) to remove your binaries, but this is optional. If all of this is new to you please read 2.2 make.

3.2 wc

We are going to use wc.c to get you thinking once again in C, with an eye to how applications utilize the operating system – passing command line arguments from the shell, reading files, and standard file descriptors. All of these things you encountered in CS61C, but they will take on new meaning in CS162.

Your first task to write a clone of the tool wc, which counts the number of lines, words, and characters inside a particular text file. You can run the official wc in your VM to see what your output should look like, and try to mimic its basic functionality in wc.c (don’t worry about the flags or spacing in the output).

You only need to support running “wc FILE_NAME” and running wc (which should read data from standard input).

While you are working on this take the time to get some experience with gdb. Use it to step through your code and examine variables.

Beware that wc in OS X behaves differently from wc in Ubuntu. We will expect you to follow the behavior of wc in Ubuntu.

3.3 Executables and addresses

Now that you have dusted off your C skills and gained some familiarity with the CS 162 tools, we want you to understand what is really inside of a running program and what the operating system needs to deal with.

3.3.1 gdb

Load up your wc executable in gdb with a single input file command line argument, set a breakpoint at main, start your program, and continue one line at a time until you are in the middle of your program’s execution. Take a look at the stack using where or backtrace (bt).

While you are looking through gdb, think about the following questions and put your answers in the file gdb.txt.

• What is the value of argv? (hint: print argv)

• What is pointed to by argv? (hint: print argv[0])

21http://ricostacruz.com/til/navigate-code-with-ctags.html 22 https://github.com/SublimeText/CTags

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
• What is the address of the function main?

• Try info stack. Explain what you see.

• Try info frame. Explain what you see.

• Try info registers. Which registers are holding aspects of the program that you recognize?

3.3.2 ob jdump

There is more to the executable than meets the eye. Let’s look down inside. Run “objdump -x -d wc”. You will see that your program has several segments, names of functions and variables in your program correspond to labels with addresses or values. And the guts of everything is chunks of stuff

within segments.

In the objdump output these segments are under the section heading. There’s actually a slight

nuance between these two terms which you can read more about online.

While you are looking through the objdump try and think about the following questions and put the

answers in the file objdump.txt.

<ul>
<li>What file format is used for this binary? And what architecture is it compiled for?</li>
<li>What are some of the names of segment/sections you find?</li>
<li>What segment/section contains main (the function) and what is the address of main? (It should
be the same as what you saw in gdb)
</li>
<li>Do you see the stack segment anywhere? What about the heap? Explain.
3.3.3 map

OK, now you are ready to write a program that reveals its own executing structure. The second file in hw0, map.c provides a rather complete skeleton. You will need to modify it to get the addresses that you are looking for. The output of the solution looks like the following (the addresses may be different).

<pre>_main  @ 0x4005c2
recur @ 0x40057d
_main stack: 0x7fffda11f73c
static data: 0x601048
Heap: malloc 1: 0x671010
Heap: malloc 2: 0x671080
recur call 3: stack@ 0x7fffda11f6fc
recur call 2: stack@ 0x7fffda11f6cc
recur call 1: stack@ 0x7fffda11f69c
recur call 0: stack@ 0x7fffda11f66c
</pre>
Now think about the following questions and put the answers in map.txt.

<ul>
<li>Use objdump with the -D flag on the map executable. Which of the addresses from the output of
running ./map are defined in the executable, and which segment/section is each defined in?
</li>
<li>Make a list of the important segments, and what they are used for (look up their names on the
Internet if you don’t know).
</li>
<li>What direction is the stack growing in?</li>
<li>How large is the stack frame for each recursive call?</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
CS 162 Spring 2018 HW 0: Executable

</div>
</div>
<div class="layoutArea">
<div class="column">
• Where is the heap? What direction is it growing in?

• Are the two malloc()ed memory areas contiguous? (e.g. is there any extra space between their

addresses?)

3.4 user limits

The operating system needs to deal with the size of the dynamically allocated segments: the stack and heap. How large should these be? Poke around a bit to find out how to get and set these limits on linux. Modify main.c so that it prints out the maximum stack size, the maximum number of processes, and maximum number of file descriptors. Currently, when you compile and run main.c you will see it print out a bunch of system resource limits (stack size, heap size, ..etc). Unfortunately all the values will be 0. Your job is to get this to print the ACTUAL limits (use the soft limits, not the hard limits). (Hint: run “man getrlimit”)

You should expect output similar to this:

<pre>stack size: 8388608
process limit: 2782
max file descriptors: 1024
</pre>
3.5 Autograder &amp; Submission

To push to autograder do:

<pre>cd ~/code/personal/hw0
git status
git add wc.c main.c map.c gdb.txt objdump.txt map.txt Makefile
git commit -m "Finished my first CS162 assignment"
git push personal master
</pre>
This saves your work and it gives the instructors a chance to see the progress you are making. Congratulations for not waiting till the last minute.

Within a few minutes you should receive an email from the autograder. (If not, please notify the instructors via Piazza). Check cs162.eecs.berkeley.edu/autograder23 for more information.

Your work on gdb.txt, objdump.txt, and map.txt will not be graded by the autograder and instead will be graded manually based on effort.

Hopefully after this you are slightly more comfortable with your tools. You will need them for the long road ahead!

</div>
</div>
<div class="layoutArea">
<div class="column">
23 https://cs162.eecs.berkeley.edu/autograder

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
