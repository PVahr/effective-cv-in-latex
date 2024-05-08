# effective-cv-in-latex
An effective, modern, professional CV that looks so good you wouldn't tell it's made with LaTeX.

Heavily inspired, cough cough maybe a bit copied, from the great materials of Jean-Iuc Doumont, that you can retrieve at this [link](https://principiae.be/pdfs/ECV-1.01.pdf).

## How to use it
1. Download everything
2. Change the content to your taste
3. Complie under LuaLaTeX or XeLaTeX (the latter one hasn't been tested. Will it work?).
It will not compile in Latex because of the 'fontspec' package

## Code design
The pdf is built out of 'minipage' environments.
They are little blocks that are stack together horizonthally.
When you insert a newline, you stack the next block of minipages below the previous one.
Is the the core logic behind the whole document. 

There is a command '\event{}{}{}' to automatize the insertion of, yeap, an event.
In the format time range, event name, description in light gray.
In the folder 'img' there are the pictures of linkedin and github; of course remove or add what you need.



The final product looks like this:



![ ](https://github.com/PVahr/effective-cv-in-latex/blob/main/img/cv_screenshot.png)
