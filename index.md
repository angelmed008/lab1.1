## Terminal Navigation and Command Usage
![Image](2023-10-22 at 11.23.01.png)
**As you can see in the example above,** I changed the directory to the `/Users/angelmedina/Downloads/` directory. I then used the `cd` (change directory) command to go back to the `Users/angelmedina/` directory, which is my home directory. The following command had no error when I used it.

---
![Image](2023-10-22 at 11.23.25.png)
**In this example,** I started in the `Users/angelmedina/` directory. However, this time I was able to tell the terminal which directory to go to. As you can see above, the directory has changed to `/Users/angelmedina/Documents/`. The following command had no error when I used it.

---
![Image](2023-10-22 at 11.25.36.png)
**Using the following command** with a path to a file as an argument: `/Users/angelmedina/Documents/file.txt`, I got an error as shown above. The reason why the terminal returned an error is because the command expects a directory as its argument and not a file. The working directory was `Users/angelmedina/`.

---
![Image](2023-10-22 at 11.25.53.png)
**In the picture above,** I used `Users/angelmedina/` as the working directory. I also used the `ls` command, which simply lists all of the directories that are in my MacBook. I currently don’t have a lot of directories since this is a new computer. There were no errors available as shown above.

---
![Image](2023-10-22 at 11.26.07.png)
**After using the `ls Downloads` command** on my mac terminal, I was able to see all of the files that were in the Downloads directory. As you can see, I was first in the `Users/angelmedina/`. However, I changed to the Download directory and used the `ls` command to show me what’s in the download folder. There were no errors as you can see above.

---
   
**For the picture above,** I was obviously in the `Users/angelmedina/` directory. However, I switched over to the `Downloads` directory and called the `/Users/angelmedina/Downloads/HelloWorld.py`. There was no error, but I currently don’t have permission to run the particular command due to permissions being locked. However, the command works fine.

---

**As seen in the picture above,** I’m in the `Downloads` directory. The `cat` command is not responding since I am not giving the command an input to begin with. In other words, it expects a file as its argument. Without any file specified, it waits for input from the user.

---

**As seen in the picture above,** I used the `cat` command in the `Downloads` directory. It displayed the content of the `HelloWorld.py` file and there was no error.

---

**The `cat` command** is primarily used to display the contents of files, not directories. However, if you attempt to use `cat` on a directory in the Mac terminal, an error will occur.

