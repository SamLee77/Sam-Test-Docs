---
layout: default
title: Publish visualizations to the web
nav_order: 4
has_children: false
permalink: /docs/publish
---

{: .fs-6 .fw-300 }

# Publish visualizations to the web
{: .no_toc }

---

### Table of contents
{: .no_toc .text-delta }
* TOC
{:toc}

---

## Benefits of Publishing

Whether it is for business or casual, exporting your dashboard into another type of file is convenient for users to access the interactive graphs. The following will show you how to publish your dashboard vizzes to the web browser.

---

**1.** To publish our dashboard to the Tableau Public server, click on FILE -> Save to Tableau Public As…

>```
>touch test.txt
>```

>Test if the *`test.txt`* file is inside the directory with the following command.

>```
>ls
>```

>You can see that the file named *`test.txt`* exists inside your current directory.

>![Root user](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/files/rootuser.png?raw=true "Root user")
<br />
<br />

**2.** A login credential window will be prompt. If you already have an account, log in. If not, create an account for free and you will login automatically after the setup. 
Tip: You can store up to 10 GB of visualizations in the Tableau Public account.

>```
>cat test.txt
>```

>You will notice that there is no output. That's because nothing was input into the *`test.txt`* file!
<br />
<br />

**3.** After logging in, you can name the visualization to be uploaded on the Tableau Public server platform. After confirming the name, the published website will automatically open from your web browser. 

<br />

>![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: Ensure that you add *`>`* to the command this time to be able to insert text into the file.
<br />
<br />

>```
>cat > test.txt
>```

>Enter some text of your choice into the empty field and hit **[return]**. I will enter the following text into my file.

>```
>I am a test line.
>```
<br />

**4.** You can share this interactive visualization via social media or email, or you can simply copy the embed code for your personal or business website by clicking on the share icon button.


>```
>cat test.txt
>```

>You will see that we did indeed change the contents of the *`test.txt`* file.

>![Inserted text into test.txt](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/files/insert-text.png?raw=true "test.txt has contents")
<br />
<br />

**5.** You can share this interactive visualization via social media or email, or you can simply copy the embed code for your personal or business website by clicking on the share icon button.


Tip: You can share your published viz to others by sharing the link.

This is the last and final instruction set in our guide.Your final viz should look similar to this. https://public.tableau.com/views/TableauPublic10Training-CO2EmissionsWorkbook/DeviceSpecificDashboard?:embed=y&:display_count=yes

We thank you for going through the complete guide and hope you have learned how to utilize Tableau to implement great vizzes!

<br />

>![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: When using the `mv` command to rename a file, enter the current file name and then the new name.
<br />
<br />

>```
>mv test.txt newname.txt
>```

>Check your current directory again to see that the file name change.

>```
>ls
>```

>You will notice that *`newname.txt`* exists instead of *`test.txt`*.

>![Renamed .txt file](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/files/renamed.png?raw=true "Renamed .txt file.")
<br />
<br />


You will see that you have completely removed both the directory and the contents using the `ls` command. You should no longer see both the .txt file and directory.

As you've noticed by now, you were able to do these things without the use of your mouse or a graphical user interface. You should be able to use these commands for your own future use in Linux when the need to create new file types and directories arise.

The next step is to learn how to [find processes and how to stop them.](https://dl90.github.io/linux-basics/docs/processes)
