# what-i-learned-in-week-0

* bash commands
* git commands and basic concepts 
* markdown
 

## shell commands
introductory into bash commands of a shell (terminal). Imagine it to be a command only place with text-only display instead of Graphical User Interface.  

 There are various commands that help you navigate through the directory paths of your filesystem  ie. [cd], along with viewing current or other contents of a directory [ls]. Creating a file [touch], Move/Rename file [mv],remove file [rm], print contents of file [cat].  

## git commands 

Git is a version system for collaborating and creating software. It is a very advanced system but using it for basic functionality for one person is not hard for now. We are using github.com as our git hosting service.  
Steps for usage:  
1. The first stage is to create a repository (your software package) where your software will be created via github.com website GUI.
2.  Clone (download) the repository in your local system in shell. 
3. Add files to the repository via shell command. 
4. Commit your changes to the repository via shell command. 
5. Push (upload) your changes to a branch (version of software) via shell command.
6. Pull (download back) from repository if necessary to view changes made by other collaborators.

## markdown

Markdown is a formatting style of a text. It is used to prettify text that programmers use to make tutorials or take notes.

**below are some of the most used formatting with its description:**
```
# h1
## h2
### h3
h(number up to 6) is a heading that comes up with bigger font and the lesser the number the bigger is the font

* unordered list a
* unordered list b
asterisk at the beginning of a line creates unordered list item

1. ordered list number one
2. ordered list number two
3. ordered list number three
numbers with dot at the end create ordered list

_italics_
    or
*italics*
underscores or asterisks at the beginning and the end of text make text italics (a bit slanted to side)

**bold**
    or
__bold__
double underscores or asterisks at the beginning and the end of tet make text bold (slightly thicker character lines to make it stand out)

!(image description)[image-file.jpg]
this posts an image on translated markdown page. first part (image description) describes image for accessibility and second part [imag-file] links the actual image to a page

[url description](www.example.com)
this creates a link with [url description] which shows up as highlight text and (www.examle.com) link inside of url description

```