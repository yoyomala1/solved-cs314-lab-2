Download Link: https://assignmentchef.com/product/solved-cs314-lab-2
<br>
<span class="kksr-muted">Rate this product</span>

Print the string “Hello World” on screen. Each character must be printed by a different process. The process that prints the it​ h​ letter must have been spawned by the process that printed the (i-1)t​ h​ letter. Each process must first print its designated character, as well as its own process ID, second, sleep for a random number of seconds (from 1 to 4 seconds), and then, do anything else it must do to achieve the given task.

What is the minimum lines of C code with which you can achieve the above?

Remember these processes have to be run in the guest Minix3 system. To compile in the guest system, we use a C compiler named ​clang​ (instead of ​gcc​). Also, standard ​make​ is invoked as gmake​ in the Minix3 environment.

Submit: a single zip file (format: &lt;roll-number-1&gt;_&lt;roll-number-2&gt;_lab2_part1.zip) with all required source files and a Makefile. The evaluator will simply unzip the submission, and run “gmake hello”. If the desired output is not seen, you will not be awarded any marks.

Part II

Modify the Minix3 source code such that:

<ul>

 <li>●  A message “Minix: PID &lt;pid&gt; created” is printed, whenever a process is created. (Let usfollow the convention throughout this course that anything printed by the OperatingSystem code will be prepended by the string “Minix: “.)</li>

 <li>●  A message “Minix: PID &lt;pid&gt; exited” is printed, whenever a process ends.Comment on the order in which processes are created and processes exit and justify it is as expected.</li>