## i'm just here to pass some information.
the project is still undering developing. I have refactored it two times, and
now it's the third time.

And it may have a new architecture.

Go down and find my temp blog. There exists newest information for flax.

Maybe consider writing some wiki pages on this repository. :)

### after the new release, README may be update

## this is a static site generator ##
- it's going to be supported by `chez scheme`

* the following is the past
> it's supported by Gnu Guile
> developed from Gnu haunt([view haunt here](https://dthompson.us/projects/haunt.html))
> simple to use, just need some config and some styles and meta posts written in markdown.
> you can write the post in sxml which will give you more control on the output file.

## Is there a demo page to view before i download it?
Yes, it is. You can View my Blog [Here](https://memorytoco.github.io/Lasga/).
It is purely genereted by **flax** along with some css style and maybe some js.
But i'm not quite familiar with front end so it may be ugly.
Because the flax is undering a big change, i'm unable to update the blog
now. Having changed to a new temp blog. --> [Lago](https://memorytoco.github.io/Lago/)

## the following way may be the past now, i have moved it to chec shceme
## How to use it ?

1. Just clone the repository to your machine.
2. put the *Flax* directory to your local guile library directory or just add the path to load path list.
3. cp the guile script which is named **flax.scm** in **/usr/bin** and change the execution permission.
4. edit the flax.scm in the **/usr/bin**, make the line
```
#!/usr/bin/guile --no-auto-compile
```
to 
```
#!path/to/guile --no-auto-compile
```
(you can get more information about the script execution mode in guile manual ([and the link is here](https://www.gnu.org/software/guile/manual/)))

5. Just test and type flax !!


## Where will it go?
* Here is a big change now.
> i will continue to complete it and make it stable enough to use.
> After all, i may not add it any other new features.
> i will focus on my another site generator written in c.
> which will be a completed system comming along with the latest commonmark engine(i do it),
> having server and one completed plugin system which lets anyone to write
> plugins in c for this new generator. It will use purely system call and standard library without 
> any third party library.

## There seems no document, where can i get help?
* i am now writing an internal help system in flax also with an api webpage.
> Well, i have added some comments in the source code, you can view it.
> I will explain the working flow and show the api i provided later.

feel free to contact me @ **Memorytoco@gmail.com** ,i will get you around .

## maybe you are more interested on my temp blog
Here is it . --> [Lago](https://memorytoco.github.io/Lago/) <--
