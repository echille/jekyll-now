---
layout: post
title: How to create your first post
tags: [github, lab resources, how-to]
---

### Overview:

[![How to create your first post](https://i.ibb.co/M8tKQ76/https-i-ytimg-com-vi-Qh-CLq-Js-DIVE-maxresdefault.jpg)](https://youtu.be/QhCLqJsDIVE "How to create your first post")

---

If you do not already have a local copy of your repository on your computer you must clone it to your computer.

### Clone your repository

#### 1. Copy the URL  
Navigate to your repository on your browser, click "Clone or Download" and copy the url. 

#### 2. Clone in Terminal  
Next, navigate to terminal, move to the directory where you want to place your repository, and run the command ```git clone``` to clone the repository. Then navigate to that directory using the ```cd``` command and check to see if everything is in the repo using the ```ls``` command.

---

### Now that your repository is cloned locally you can create your first post!

Open up your favorite Markdown editor. I personally use *[Markdown Plus](https://tylingsoft.com/markdown-plus/)* because you can get a preview of how your code looks as you are writing it. This app does cost money, however, a good free alternative is *[Atom](https://atom.io/packages/markdown-writer)*.

#### 1. Make a new post  
In the toolbar, click "New" to create a new document. This will open a window where you can save your new post. Save the document in the "_posts" directory within your repository with the naming convention "yyyy-mm-dd-title-with-hyphens-replacing-spaces". 

#### 2. Format the post  
Now that you've created a new post, you have to tell your Markdown editor what kind of post it is. You do this by creating a header. For example:

```
---
layout: post
title: Acropora Larvae DNA/RNA Extraction Batch 3
tags: [DNA, RNA, eggs, sperm]
---
```

Once that is done you are good to go! Remember to save often.

---

## Push your changes to GitHub!  

#### 1. Check the status of your repository  
Navigate back to terminal and check the status of your repository using the command ```git status```. You may have to pull to update the local version of your repository before you upload your changes using the ```git pull``` command. Pulling is especially important when you are working with other collaborators on the same repository.

#### 2. Add your changes to the stage  
When you see that it's ok to push, add your changes. You can do this in a few ways:

>```add -A``` will add all of the changes that you've made since you last pushed  
>```add <path_to_file>``` will add just the file that you specify  
>```add path_to_file/some-day*``` will add all of the posts with that day in the title

#### 3. Commit your changes with a message  
Now you have to commit your changes. In terminal, type the command ```commit -m``` and in quotation marks say what changes you made. For example:  ```commit -m "created post Hello World!"```

#### 4. Push to GitHub  
Finally, push your changes with the command ```git push```. If you get an error saying you need authorization, push again and this should prompt you to enter your user name and password.  

That's it! You're on your way! 
---
Resource for embedding videos into Markdown: [Video to Markdown](https://github.com/marcomontalbano/video-to-markdown)