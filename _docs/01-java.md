---
layout: doc
title: 1 Java
order: 1
previous: /
next: /git/
---
## 1.1 What is Java?
[Java](https://en.wikipedia.org/wiki/Java_(programming_language)) is a general-purpose programming language. It is used to write various kinds of software.

## 1.2 Command line
We will be using the **command line**/**terminal**/**console** to install Java and everything else we need. It is a text-based interface used to interact with computers by entering commands. Since you will have to know how to use the command line for future courses, it is recommended to start using and learning about it now.

## 1.3 How to install Java
First, check if Java is already installed on your computer. Click on the name of your operating system below and follow the steps shown:

---

<details>
<summary>► Windows</summary>

<ol>
<li>open the application <b>Command Prompt</b></li>
<li>type or paste <code>java -version</code> and press enter</li>
</ol>

<img src="img/check_java_installed_win.jpg" alt="check if Java is installed on MacOS" width="60%" height="auto">[^1]

</details>

---

<details>
<summary>► MacOS</summary>
<ol>
<li>open the application <b>Terminal</b></li>
<li>type or paste <code>java -version</code> and press enter</li>
</ol>

<img src="img/check_java_installed_macos.jpg" alt="check if Java is installed on MacOS" width="60%" height="auto">[^2]

</details>

---

<details>
<summary>► Linux</summary>

you know what you're doing :D but in case you don't:
<br>
<ol>
<li>open the application <b>terminal</b></li>
<li>type or paste <code>java -version</code> and press enter</li>
</ol>

</details>

---

**Inspect the output**: if it looks anything like
```shell
openjdk version "24.0.1" 2025-04-15
OpenJDK Runtime Environment (build 24.0.1+9-30)
OpenJDK 64-Bit Server VM (build 24.0.1+9-30, mixed mode, sharing)
```
, Java is already installed on your computer. Skip the instructions below and move on to the next step, installing Git & setting up GitHub, by using the menu on the left or scrolling up and clicking on the arrow on the right.


If Java is not installed, download it from [here](https://www.java.com/en/download/) (all operating systems), open it, and follow the instructions. Then, if you are using Windows:

---

<details>
<summary>► Windows</summary>

Check if the <code>JAVA_HOME</code> variable is set. It allows other software to see your Java installation.
<br>
<ol>
<li>type or paste 'advanced system settings' into the start menu</li>
<li>click on 'view advanced system settings'</li>
<li>go to the 'advanced' tab</li>
<li>click on 'environment variables'</li>
<br>
<img src="img/set_java_home_win.png" alt="set JAVA_HOME on Windows" width="60%" height="auto">[^3]
<br>
<li>if <code>JAVA_HOME</code> exists under 'system variables' and has a value similar to <code>C:\Program Files\Java\jdk-21</code>, it is already set. Go to the next step, installing Git, by using the menu on the left or scrolling up and clicking on the arrow on the right. Else:</li>
<li>click on the 'new' button under the 'system variables' section</li>
<li>set name to <code>JAVA_HOME</code></li>
<li>set value to the location of your Java installation, which should look something like <code>C:\Program Files\Java\jdk-21</code>. If you do not know the location, find it using File Explorer</li>
<br>
<img src="img/set_java_home_win1.png" alt="set JAVA_HOME on Windows cont." width="60%" height="auto">[^3]
<br>
<li>to test if the variable has been set correctly, go back to the command prompt and type or paste <code>echo %JAVA_HOME%</code> and press enter; check the output</li>
</ol>

</details>

---

Double-check if Java was installed successfully by running `java -version` as described above.

---

Done. Move on to the next step, installing Git & setting up GitHub, by using the menu on the left or scrolling up and clicking on the arrow on the right.

---

[^1]: image taken from https://www.wikihow.com/Check-Your-Java-Version-in-the-Windows-Command-Line, 08/10/2025
[^2]: image taken from https://www.wikihow.com/Check-Java-Version-on-a-Mac, 08/10/2025
[^3]: images taken from https://mkyong.com/java/how-to-set-java_home-on-windows-10/, 08/10/2025