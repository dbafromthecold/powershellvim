# Running Powershell in Vim

---

## Andrew Pruski

<img src="images/apruski.jpg" style="float: right"/>

### Field Solutions Architect
### Microsoft Data Platform MVP 

<!-- .slide: style="text-align: left;"> -->
<i class="fab fa-twitter"></i><a href="https://twitter.com/dbafromthecold">  @dbafromthecold</a><br>
<i class="fas fa-envelope"></i>  dbafromthecold@gmail.com<br>
<i class="fab fa-wordpress"></i>  www.dbafromthecold.com<br>
<i class="fab fa-github"></i><a href="https://github.com/dbafromthecold">  github.com/dbafromthecold</a>

---

## Session Aim
<!-- .slide: style="text-align: left;"> -->
To show what can be done with powershell and Vim

---

## My Vim Setup
<!-- .slide: style="text-align: left;"> -->
<p align="center">
  <img src="images/vim_setup.png" />
</p>

---

## The Big Question
<!-- .slide: style="text-align: left;"> -->
<p align="center">
  <img src="images/ytho.png" />
</p>

---

## Stop to think
<!-- .slide: style="text-align: left;"> -->
<p align="center">
  <img src="images/stop_to_think.png" />
</p>

---

## History
<!-- .slide: style="text-align: left;"> -->
- Based on its precedessor vi (visual editor)
- Built by Bill Joy in the 1970s
- In 1988, Bram Moolenaar, worked on Vi IMitiation
- Vi IMitation evolved into Vi IMproved
- Released as shareware in 1991
- Continued to evolve in the 1990s and 2000s
- Is now an open-source project

---

## Original Keyboard
<!-- .slide: style="text-align: left;"> -->
<p align="center">
  <img src="images/vim_keyboard_2.png" />
</p>

---

## Exiting Vim
<!-- .slide: style="text-align: left;"> -->
<p align="center">
<img src="images/HowToExitVim.gif"/>
</p>

---

## Opening Vim
<!-- .slide: style="text-align: left;"> -->
<p align="center">
<img src="images/vim_start_screen.png"/>
</p>

---

## Modes
<!-- .slide: style="text-align: left;"> -->
- Command
  + Navigation, file operations, cut/copy/paste
- Insert
  + Writing text to a file
- Visual
  + Selecting text in a file

---

## Running a script
<!-- .slide: style="text-align: left;"> -->
- Open up Vim <!-- .element: class="fragment" data-fragment-index="1" -->
- Write the script<!-- .element: class="fragment" data-fragment-index="2" -->
- Exit and save<!-- .element: class="fragment" data-fragment-index="3" -->
- Navigate to script in powershell<!-- .element: class="fragment" data-fragment-index="4" -->
- Run the script<!-- .element: class="fragment" data-fragment-index="5" -->
- There has to be a better way!<!-- .element: class="fragment" data-fragment-index="6" -->

---

# Demo

---

## Execute Single powershell Command
<!-- .slide: style="text-align: left;"> -->
<p align="center">
<img src="images/SimpleCommandPowershellVim.gif"/>
</p>

---

## Execute multi-line command
<!-- .slide: style="text-align: left;"> -->
<p align="center">
<img src="images/MultiLineCommandPowershellVim.gif"/>
</p>

---

# Demo

---

## Opening a terminal in Vim
<!-- .slide: style="text-align: left;"> -->
<p align="center">
<img src="images/vim_terminal.png"/>
</p>

---

# Demo

---

## More operations and configuration
<!-- .slide: style="text-align: left;"> -->
- Visual Block Mode!
  + Multi-line operations
- Opening a terminal
  + Executing powershell commands
- Opening a file explorer
  + Using NERDTree to access files
- The vimrc file
  + Configuring Vim

---

## NERDTree
<!-- .slide: style="text-align: left;"> -->
- A file tree explorer for Vim
  + Installed as a plugin
  + Or just pull the code down from Github
  + Other repos will add file icons
  + This WILL slow Vim down!

---

# Demo

---

## Resources
<!-- .slide: style="text-align: left;"> -->
<font size="6">
<a href="https://github.com/dbafromthecold/powershellvim">https://github.com/dbafromthecold/powershellvim</a><br>
</font>

<p align="center">
<img src="images/powershellvim_qr_code.png" />
</p>