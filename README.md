# LeverX_Course_HomeWork1
Starting a java project from the console

<h3>Downloading the project from GitHub</h3>
<ul>
<li> Follow the <a  href = "https://github.com/DergachevDenis/LeverX_Course_HomeWork1">link</a>.</li>

<li>Click on the green <i>Code</i> button, then click <i>Download ZIP</i> on the pop-up window.</li>

<li>We are waiting for our ZIP file to download, then unzip it into the directory we need.</li>
</ul>


<h3>Compile and run our java project</h3>
<ul>
<li> At the command line, go to the disk where our repository is saved using the command [disk_name]: (For example <code>H:</code>). </li>

<li> In the command line, specify the full path to the <code>src</code> folder using the <code>cd</code> command

(For example: <code>cd H:/Java/LeverX_courseJava/HomeWork1</code>). Please note the command line is case-sensitive.</li>

<li> Being in the directory where the <code>src</code> folder is downloaded from GitHub, run the command:

<code>javac -d classes src/com/dergachev/homework1/Main.java</code>. 

The result of this command will be the creation of a new <code>classes</code> directory in the <code>H:/Java/LeverX_courseJava/HomeWork1</code>  directory in which the directory structure will be automatically created as in <code>src</code> with the compiled <code>Main.class</code> file</li>

<li> To run this java program, we must be in the directory in which our <code>classes</code> directory is located, then on the command line we execute the command <code>java -cp ./classes com.dergachev.homework1.Main</code>

The result of executing this command will be the output of the line to the console: <code>Hello, my friend</code>.</li>

<li> To create a JAR file, go to the <code>classes</code>  directory using the <code>cd classes</code> command, and then use the command 

<code>jar cfe homework.jar com.dergachev.homework1.Main com/dergachev/homework1/Main.class</code>.</li>

<li>To run the JAR file, while in the directory with the created <code>homework.jar</code> file, execute the command 

<code>java -jar homework.jar</code>. The result of executing this command will be the output of the line to the console: <code>Hello, my friend</code>.</li>
</ul>
