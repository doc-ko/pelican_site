Vim Cheat Sheet
###############

:date: 2022-04-16 17:51:37
:author: Karl Oberio
:summary: Quick Vim Cheat sheet.

This post was written using vim, and its contents a summary of **vimtutor**.

Lesson 1
********
.. list-table::
  :header-rows: 1

  * - Key
    - Cursor Direction
  * - ``j``
    - move up
  * - ``h``
    - move left
  * - ``k``
    - move down
  * - ``l``
    - move right


* To start vim from shell, type:
    ``vim {fileName} <ENTER>``
* To exit vim, type:
    ``<ESC> :q! <ENTER>``
* To trash all changes, or type:
    ``<ESC> :wq <ENTER>``
* To save changes:
    ``testing``
    
Lesson 2
********
* To delete from cursor location to the next word, type:
  ``dw``
* To delete from cursor location to the end of a line, type:
  ``d$``
* To delete from a whole line, type:
  ``dd``
* To repeat a *motion*, prepend it with a number:
  ``2w``

.. admonition:: Motion

    A **motion** describes the scope of up to where an operator (i.e. a command like ``d`` (delete)) will operate before halting.

    A short list of motions:

    * ``w``: Until the start of the next word, **excluding** its first character.
    * ``e``: To the end of the current word, **including** its last character.
    * ``$``: To the end of the line, **including** the last character.

    For example, typing ``de`` deletes from the current cursor location until the end of the word.
    

    Note that pressing the motion while in Normal mode with no operator moves the cursor as specified. 

Lesson 3
********
To be continued