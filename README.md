If you have a problem with the stm32f1xx that it is exactly 0x1ba01477 or 0x2ba01477, which is most likely not the original chip. 

The solution to the problem was checked using Visual Studio and the VisualGDB add-on.

The problem did not appear when using IarIdePm.
To solve the problem, follow the path specified in the File path.txt .If you installed VisualGDB in another location, then go there. The stm32f1x.cfg file should be located there. It should be replaced with a file located in the Fake file folder and from there replace the original cfg file with this one.

IMPORTANT:
If you plan to buy an stm with the original chip in the future, this cfg file will not work with the original chip and you will need to replace the stm32f1x.cfg file with the original one located in the Original file folder.

Of course, it 's not a very good solution to the problem , it looks like a crutch , but even so , if a problem arises , it will be the fastest and easiest solution to the problem .

If this post helped you, put an asterisk on the post.
