
# Linux Notes

Collection of Self-gathered used linux notes.


## ⭐️ Easier to interact

```
tail -f /var/log/messages
```
Preferred with **multiple** files (show you changes in all monitored files)

- insert empty lines as a visual separation
```
less +F /var/log/messages	
```
Preferred with **one** file  (only show you the first file (unless you use ctrl-c, :n, F to switch
between buffers))

- Search “foo” with **/foo**  
- Jump to the next occurence with **n** or the previous with **N**  
- Go up with **j** or down with **k**  
- Create marks with **m**  
 

 Two modes:
     (navigation ---**ctrl+c**---> watch) 
     (watch ---**F**---> navigation) 

- rotating logs **--follow-name** option 

```
nmtui	
```
edit Net. Conf.

```
nautilus	
```
open explorer
```
sudo -u USER command
```	
run a command as a USER
```
script	
```
record my CLI session
```
cd - 	
```
return to previous directory
```
command 1 && command 2	
```
sudo apt update && sudo apt upgrade
```
nano +123 FILE	
```
open the document on line 123
```
reset	
```
remove everything from the CLI
```
mtr -b GOOGLE.COM	
```
report about google.com
```
sudo !!	
```
run the last command as root


## ⭐️ Shortcuts

### CTRL+x+e	  
open nano to write commands
### CTRL+u	    
delete all before
### CTRL+w	   
delete 1 word before = ALT+ backspace
### CTRL+r       
reverse search of commands
### CTRL+a/CTRL+e	
crusor at start/end of the command
### CTRL+s/CTRL+q	 
freeze/unfreeze command line




## cat & grep

Show
```python
Ubuntu:~$ cat data.txt
Mamdouh
iam Mamdouh
iam mamdouh
Egypt
Germany
frankfurt
123456
```
Show + **n**: lines number

```python
Ubuntu:~$ cat -n data.txt 
     1	Mamdouh
     2	iam Mamdouh
     3	iam mamdouh
     4	Egypt
     5	Germany
     6	frankfurt
     7	123456
```
Match
```python
Ubuntu:~$ cat data.txt | grep 'ma'
iam mamdouh
Germany
```
Insensitive Match
```python
Ubuntu:~$ cat data.txt | grep -i 'ma'
Mamdouh
iam Mamdouh
iam mamdouh
Germany
```
Reverse Match
```python
Ubuntu:~$ cat data.txt | grep -v 'ma'
Mamdouh
iam Mamdouh
Egypt
frankfurt
123456
```
Count Match

```python
Ubuntu:~$ cat data.txt | grep -c 'ma'
2
```
**A**: After  
**B**: Before  
**n**: lines number
```python
Ubuntu:~$ cat data.txt | grep -A 1 -B 2 -n 'er'
3-iam mamdouh
4-Egypt
5:Germany
6-frankfurt
```
**o**: only match part   
**n**: lines number
```python
Ubuntu:~$ cat data.txt | grep -on 'er'
5:er
```

## Author

**Mamdouh Muhammad**

- [Profile](https://github.com/MamdouhEgy "Mamdouh Muhammad")
- [Email](mailto:mamdouh.muhammad@gmx.de?subject=Hi "Hi!")


## ✔️ ✅ ☑️ ⛔ ❌ 🔴 ⚫ ⚪ 🔵 🔷 🔹 💯❗ ⭕ ⁉️ 🔺 🔻
## 🆕 🆓 🆒 🆙 🆗
## ▶️ ◀️ ⬇️ ⬆️ ↔️ ↕️ ↙️	↘️ 	↖️ 	↗️ 🔁 🔀 🔄
## 1️⃣	2️⃣	3️⃣ 4️⃣ 	5️⃣ 	6️⃣ 7️⃣ 	8️⃣ 	9️⃣ 🔟 
## 🚩 💎 ✨ ⭐ 	🌟	💫 	💥 🤝
## ✏️ 📏 📐 	📕 	📗 📘 	📙 	📓 📔 	📒 	📚 
## 📄 📑
## 📧
