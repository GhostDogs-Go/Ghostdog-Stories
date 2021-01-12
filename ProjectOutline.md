+++
title = 'Project Outline'
date = "Tue, 29 Sep 2020 08:39:00 +0000"
draft = false
tags = ["Go"]
categories = ["Grief","Go Programming"]
author = "Alan Greenwell"
[[images]]
  src = "img/go.jpg"
  alt = "Desktop"
  stretch = ""
+++
# Project outline

When NASA sent a man to the moon they did not build a rocket and fire it to the moon on the first attempt. They took steps and worked towards improving every flight and taking it further than the previous flight. Learning as they went along and improving the previous stages. That is what I have decided to do with my little project.

## Outline

I want a program that will generate a markdown file for feeding the Hugo webserver. The markdown file will be a blog post or page which has a TOML header and a markdown body. 

The TOML header looks like this

```yaml
+++
title = 'New Blog Post'
date = "Sun Sep 27 03:07:54 2020"
draft = false
tags = ['Birthday','Grief','Sorrow']
categories = ["Grief"]
author = "Alan Greenwell"
[[images]]
	src = "img/h-photo.jpg"
	alt = "Photo"
	stretch = ""
+++
```

The rest of the file is just markdown formatted text. Hugo takes the TOML part of the file to place and format it correctly and renders the markdown as a webpage. 

Now for anyone that uses Hugo you will be screaming at the screen saying that Hugo does some of this anyway. Well I was to make Hugo work in my way and I also want to learn the Go Language. 

The plan is to develop the program using the following steps.

### First Program

Objective - Write out the TOML header to the console.

### Second Program

Objective - Write out the TOML header to a file.

### Third Program

Write the TOML header out to a file and append a dummy blog post to the end of the file.

### Fourth Program

Pass file name and blog post name to the program and write out to a file.

### Fifth Program

Receive file and blog post name during program call. Request input for other items such as image name & title, category, tag and blog filename.

### Sixth Program

Make the whole experience graphical. Use a framework to make it work on Mac and Linux.

### Seventh Program

Add a Markdown editor for the blog post.

### Eighth Program

Run hugo server after completion and sftp the generated website. Also perform Git commit.

### Summing up

The intention is to put all of the code up during my posts but to also put the code on Github for anyone to reference, comment or improve. I know I will learn a lot through this process and maybe it will help someone else by posting this. 

>Further Thought - I had envisioned all of this to be a windowed graphical app that works on MacOS and Linux. So I will need to do a parallel learning process using a Framework Library such as [Fyne.io](http://fyne.io) as my support. Probably will look at building the layout with input and output fields in one fell swoop. I will investigate. Some of this will be lacking error trapping and correction but it is something I will deal with as and when I start to feel more comfortable with each iteration.
