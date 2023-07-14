# MarkDown(.md) file syntax Cheat Sheet
1\. **Tab (like ordered list)** <br />

1\. Subject 1, <br />
2\. Subject 2, <br />
3\. Subject 3 <br />
&emsp;1\. Sub-Subject <br />

1. Subject 1,
2. Subject 2,
3. Subject 3
   1. Sub-Subject

<br />

2\. **Tab (like unordered list)** <br />

\- Subject 1, <br />
\- Subject 2, <br />
\- Subject 3 <br />


- Subject 1,
- Subject 2,
- Subject 3

<br />

3\. **Add 1 space** <br />
\&nbsp; <br />
&nbsp;xyz <br />

4\. **Add 2 spaces** <br />
\&ensp; <br />
&ensp;xyz <br />

5\. **Add 4 spaces** <br />
\&emsp; <br />
&emsp;xyz <br />

6\.  **Comment code** <br />
\\ <br />
\**\<Comment>**

7\. **Heading** <br />
\# \<Heading> 
# \<Heading> 

<br />

8\. **Sub Heading** <br />
\## \<Sub Heading> <br />
## \<Sub Heading> 

continue . . . 

<br />

9\.  **Strong/Bold** <br />
\**\<Strong/Bold>** <br>
**\<Strong/Bold>** <br>

10\.  **Strong/Bold and Italics** <br />
\*\*\*\<Strong/Bold and Italics>*** <br>
***\<Strong/Bold and Italics>*** <br>

11\.  **Italics** <br />
\_\<Italics>_ &nbsp; <br>
_\<Italics>_ &nbsp; <br>

**Alternate method for Italics** <br />
\*\<Italics>* &nbsp; <br>
*\<Italics>* &nbsp; <br>

12\.  **Underline** <br />
\<u>\<Underline>\</u> <br>
<u>\<Underline></u> <br>

13\. **Strikethrough** <br />
\~~\<Strikethrough>~~ <br />
~~\<Strikethrough>~~ <br />

14/. **Linebreaks** <br />
\<br />
<br />

<br />

15/. **Horizontal Line** <br />
\***
***
\---
---
<br />

16\. **Link** <br />
\[\<Link Url>](http://www.example.com "\<Hover Over>") <br />
[\<Link Url>](http://www.example.com "<Hover Over>") <br />

17\.  **Image** <br />
\!\[\<Alternative Text>](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png)

![<Alternative Text>](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png)

<br />

\<img src= "https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png" width="200px" height="85px">

<img src= "https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png" width="200px" height="85px">

<br />

18\. **Code Snippets** <br />

Use `for` loop
```javascript
var name = "Sayantan";
console.log(name);
```
```java
String name = "Sayantan";
System.out.println(name);
```

19\. **Tables** <br />

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |

 <br />

20\. **Tables with alignment** <br />

| Left-aligned | Right-aligned | Center-aligned |
|:------------|-------------:|:-------------:|
| Cell 1      |    Cell 2     |    Cell 3     |
| Cell 4      |    Cell 5     |    Cell 6     |

<br />

21\. **Code** <br /> 
>Write a code here to generate odd numbers upto 100 <br /> Hi, how are you doing. 

<br /> 

<br /> 

# Useful Git Commands
- $ git init
- $ git add ReadMe.md
- $ git add .
- $ git status
- $ git commit -am "Initial Commit"
- $ git branch
- $ git branch -M main
- $ git config --global user.name "Sayantan Das"
- $ git config --global user.email "sdas45758@gmail.com"
- $ git remote add origin https://github.com/iamsayantan1/Full-Stack-Web-Development.git
- $ git push -u origin main
- $ git rebase -i HEAD~2
- $ git push -f
- $ git log