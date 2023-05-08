Download Link: https://assignmentchef.com/product/solved-ve280-lab1
<br>



<h1>Ex0. A fun bash game BashCrawl (not mandatory)</h1>

A fun game that helps you get famaliar with Linux command.

The game is attached in the files. See <sub>/bashcrawl </sub>. It has its README.It will be uploaded on Gitea soon. Have fun.




<h1>Ex1. Hiding Photos</h1>

Related Topics: <em>Linux</em>.

Kyon is thinking of moving his favourite Mikuru’s photos from SOS Quantum Library <sub>sql/</sub> to his own webserver <sub>webserver/</sub> without being noticed.

“If Haruhi knows this, Haruhi will destory the world. We have to avoid this”.

Yuki suggests Kyon to use command lines. So Kyon decides to implement a shell script to automate command line tasks. He may need these tasks:

Create: create the working directory of the database and webserver, and initialize the database;

Dump: dump the data in the database into the webserver;

List: list all the files stored in the webserver;

Display: display the data in the webserver;

Destroy: remove the working directory of database and webserver.

He has already implemented the skeleton of <sub>ex1.sh </sub>, but now he . There are 5 of such lines in the script that are marked as <sub>TODO</sub> comments:

1 # TODO: Replace this line with a linux command line.

Please help him finish this script by replacing the <sub>TODO </sub>s with a Linux command line you learned from lecture.

<ol>

 <li>Create a directory named <sub>sql/ </sub>.</li>

 <li>Copy the file sql/database.txt to the directory webserver/ List all files in directory <sub>webserver/ </sub>.</li>

 <li>Display webserver/database.txt in stdout .</li>

 <li>Remove the <sub>webserver/</sub> and <sub>sql/</sub></li>

</ol>

<h2>Testing</h2>

To test the script, please first <a href="https://askubuntu.com/questions/443789/what-does-chmod-x-filename-do-and-how-do-i-use-it">make it executable</a> by running:

Then, you can test the script by running the following commands and observe the results.




<h1>Ex2. Validating Password</h1>

Related Topics: <em>loops</em>, <em>arrays</em>, <em>boolean</em>, <em>ASCII</em>.

Miyamori Aoi is designing the wbsite for Musani Animation. When designing the register page, she plans to Write a function that checks whether the password that the user type in meets all the requirements below (or say it is valid):

Contains at least 1 alphabetic characters;

Contains at least 1 numerical characters; Contains at least 1 non-alphanumeric characters. The max length of a password is 50 characters.

The function takes a password (an array of chars) as input, returns true if the password is valid and returns false if not.

Miyamori is busy with their new animation. Please help her implement the function.

Note: In fact, when writing a web page, we use <strong>Regular Expression</strong> to validate whether a password meets our requirement. We do not use <strong>C++</strong> but we use <strong>JavaScript</strong> for web programming. For those interested, you can Google it yourself.




<h2>Example</h2>

Example input:

Example output:




<h1>Ex3. Flipping an image</h1>

Related Topics: <em>loops</em>, <em>array</em>s

<h2>Description</h2>

Here our topic is about the principle behind image processing software, like how to flip an image horizontally and invert it.

Like

Will result in

Of course this image will be too complicated for us to handle here. Let’s simplify the problem.

We are given a  binary matrix as a simple image.

To flip an image horizontally means that each row of the image is reversed.

For example, flipping [1,1,0] horizontally results in [0,1,1] .

To invert an image means that each <sub>0</sub> is replaced by <sub>1 </sub>, and each <sub>1</sub> is replaced by <sub>0 </sub>.

For example, inverting [1,0,1] results in [0,1,0]

<h2>TODO</h2>

Just modify on the image. There is no need to return a new image here.

<h2>Input</h2>

The first line contains a number <sub>n </sub>, which is the size of the matrix <sub>image </sub>.

The following lines represents the matrix, which only contains <sub>0</sub> or <sub>1 </sub>. Each row separated by a 
 and each column separated by space.

<strong>Output                                                                                                                  </strong>

The flipped and inverted matrix

<h2>Example</h2>

<strong>Example input:</strong>

<strong>Example output:</strong>

<strong>Explantion</strong>:

First flip horizontally

Then invert it