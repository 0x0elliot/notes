<h1>Commands related to finding files/Things in files:</h1>




```
find -name {filename}
```




Works like a charm, Saves time.





Audio Driver Interface commands are nice to use. Most linux systems use PulseAudio. It's commands look like the ones I have used in https://www.github.com/masterhackertool


<h1>Vim Help:</h1></br>

1. Press esc to enter command mode.

2. Press i to go back to typing.

<b>On command mode:</b>

1. :wq --> Save and Quit
2. :w  --> Save

<b>How To Copy-Paste Test In Vim:</b>

3. Press (Not hold) Control+V in Command mode and then use your arrow keys to select the desired portion of text you want to copy.
Then press y to 'yank'/copy the text. Move your cursor to the desired area where you want to paste the copied text. Press 'p' to paste
the test. Bingo! You copied and pasted a code block on vim.
<br>
<b>How to delete a line:</b><br>
4. Place your cursor on the line you want to delete, Then press esc to go to command mode and enter 'dd'. You will see that your line will disapear.<br>
5. <b>Deleting multiple lines:</b> Again, Repeat the same process, Just do 5dd instead of just dd to delete 5 lines <b>below the line, Including the lines your cursor is on.</b>. Replace 5 with whatever number of lines you want to delete.
<br><br>
<b>5. How to pass commands into the command line from vim: </b><br>






```
:!ls
```




Similarly you can run your script without leaving vim.
<b>Running python from VIM, For example:</b><br>






```
:!python3 script.py
```



<b>Run Multiple VIM commands together: </b><br>
Put '|' between the commmands.
For example:
<br>





```
:w | :!python3 run.py
```
