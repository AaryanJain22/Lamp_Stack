# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

Reasoning - Firstly, I removed 'unsigned' before int main function since it should return an integer. Then, changed int in last part to char because it is a string of characters. It compiled successfully after these corrections and I got this :

```
What manual page do you want?
For example, try 'man man'.
```


---

## Your first approach below (first.txt)

Reasoning - I noticed that 's' is written alone twice in the text. There are two letters **a** and **i** that can be written alone in english and they make sense.
So, I took both cases and used a code to find that moving 8 letters forward or 18 letters backwards gave meaningful sentence which is :

```
noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT
```

---

## Your second approach below (strings.txt)

Reasoning - For this, I unzipped the file Lamp_Stack_Task.zip and done a set of commands on linux terminal and used `grep -R "string"` to find files in which
any specific string is present. 

```
atishayj25@aaryan13-hp-laptop-15-da0xxx:~/Desktop/Lamp_Stack$
 unzip -l Lamp_Stack_Task.zip
Archive:  Lamp_Stack_Task.zip
  Length      Date    Time    Name
---------  ---------- -----   ----
129  2023-04-14 00:00   Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3/strings.txt

(This is the path to find strings.txt).
Then,
atishayj25@aaryan13-hp-laptop-15-da0xxx:~/Desktop/Lamp_Stack$ cd Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3
atishayj25@aaryan13-hp-laptop-15-da0xxx:~/Desktop/Lamp_Stack/Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3$ cat strings.txt
kw4QLNylm2inErX
DabAWF1UenBD2W
kPVEQPc6ZN8x2jn
g4JoMqFZyat9vd5
ORNwuwGtKDLydge
TqMuGims7vlJtno
8dc2evcCSSc4kUy (password)
```

---

## Your third approach below (fourth.zip)

Reasoning - I judged that the password for unzipping fourth.zip was eleven.txt since it contained only one of seven strings which were in strings.txt file and then,I unzipped fourth.zip and extracted get_in folder where I used command grep -R "DevOps{}*" to find desired string.

```
atishayj25@aaryan13-hp-laptop-15-da0xxx:~/Desktop/Lamp_Stack$ grep -R "DevOps{}*"
get_in/4/2_inner/0.txt:DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}

```
So, the final desired string is 
```
DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}
```
---


- Name : Aaryan Jain
- Roll : 220015
- GitHub username: AaryanJain22
- Discord username: Aaryan_13#8568


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
