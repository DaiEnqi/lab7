Step4: 
![Image](Procedure4.png)
The key I pressed: 
```
ssh <space> endai@ieng6.ucsd.edu <enter>
```
Since I have generated SSH Keys for ieng6, I can set up to SSH without a password!

Step5:
![Image](Procedure5.png)
The  key I pressed:
```
git <space> clone <space> <command+V> <enter>
ls <enter>
```
This step I clone my fork of the repository from my Github account (using the SSH URL). Since I have cloned the SSH URL before, it says the lab7 already exits. After the "ls" command, we can see the "lab7" directory which we'll cd into next step.

Step6:
![Image](Procedure6.png)
The key I pressed:
```
cd <space> l <tab> <enter>
bash t <tab> <enter>
```
This step I first cd into the lab7 directory and then run the tests, demonstrating that they fail.

Step7:
![Image](Procedure7_edting2.png)
This step I need to edit the code file to fix the failing test. So firstly I press the key:
```
vim <space> L <tab> .java
```
This helps me open the java file on terminal by using vim to edit.

![Image](Procedure7_edting3.png)
The key: 
```
6ke
```
Since I notice the cursor is at the bottom of the page, I use the key to move it 6 lines up to get to the line I need to edit. And then use the key "e" to put the cursor at the end of the word "index1".

![Image](Procedure7_edting4.png)
The key:
```
r2
```
I use the key to change the "1" to "2" which means the "index1" changed to "index2".

![Image](Procedure7_edting5.png)
The key:
```
<esc> :wq!
```
By using this key, I save and exit the vim.

Step8:
![
