---
layout: post
title:  "The problem with file systems"
author: achyut
categories: [ files, "the problem" ]
tags: ["the problem"]
image: "https://cdn.zmescience.com/wp-content/uploads/2011/05/cluttter.png"
description: "My discussion on the failures and insuffisiencies of modern filesystems."
featured: true
hidden: false
---

Let's do a quick experiment. Take a look at your computer for a second. You, like most people, probably have an absolutely abhorrent mess for a desktop wallpaper, or home screen. Now, think about the files that are really important to you right now. Do you know where they are on your computer right now? Are you sure that it is not buried deep within several nested layers of folders? If you are like most people, the answer to both questions was no.


The modern paradigm of file management, i.e. primarily textual files stored within various named folders, came about at a time when the computer was seen as little more than a business machine. It made perfect sense at the time to sort data into easily accessible folders and files, which could be manipulated as needed. Computers were after all, never going to be used for too much more.

Now however, the computer has evolved to fill a staggering number of roles. It is our portal to the internet, our personal assistant, our knowledge base. Almost every single part of computer, from software to hardware has evolved several times. Yet, the file system is still there, fundamentally unchanged, barely holding up under the sheer weight of its responsibilities. 

The amount of data stored on a filesystem has become many orders of magnitude larger than what it was designed for, making it near impossible to find anything. The main problem behind this is the way files and folders are organized. Having files sorted into folders makes sense as long as each file is about a single topic, and can be easily classified into a given folder. However, this approach begins to fall apart when considering the amount of conscious thought and effort needed to design a folder classification system that works for a given user. Should a user simply neglect to organise his files and folders, it very quickly spirals out of control into a huge mess.

The other big mess plaguing the modern computer is that of web bookmarks. As someone who has close to 4000 bookmarks, I find that it is nearly impossible to find what I need, when I need it. In addition, websites have a nasty habit of going out of date, and being edited, modified or deleted. This makes their usable life much shorter than a traditional information conduit, like a book, meaning that most of those 4000 bookmarks are near useless clutter.

![Bookmarks]({{ site.baseurl }}/assets/images/bookmarks.png)

The main function of a modern computer is to be a conduit of ideas, both good and bad, into and out of our worlds. While it excels at bringing information in and out via social media, email, and websites; The actual storage and usage of these ideas is woefully lacking. 

My idea to fix this hot mess, is to create a new paradigm, of user created documents, based on the idea of, small, atomic, "snippets". Each snippet acts as a small individual store of information, that is easily searchable and indexable. Much like modern note taking apps like mem, or obsidian, these snippets would link to one another, to form cohesive groups of knowledge. Each of these snippets can be tagged, linked, and since they are atomic, fuzzy searched. The great advantage with a system like this is how much of the cognitive load it takes off of the end user. 

Let us take an example of a business meeting, in which various ideas for a brand new app are being discussed. You finally decide on a major conclusion, deciding to switch your brand direction. You can take notes in a snippet, label it, and forget about it. 
![Sample snippet]({{ site.baseurl }}/assets/images/sample_snippet.png)

Later, you need to recall your conclusions, and your reasoning. You need your notes. Let's say you don't know when the meeting was, and what you called the file, you just have a vague remembrance of it. Now, in a traditional file based system, you have to go digging through a folder called work, then a folder called meeting notes, then trudge through many days worth of notes, to then find it stored deep inside. 

In a snippet based system, you can simply search for snippets tagged "meeting notes", then fuzzy search the snippets for "brand direction", et voila. The system spits out your snippet, all ready to go.

The bookmarks issue can also be sorted out via such a system. Instead of a bookmark which retains only the name and url of a resource, you save the resource into your system as a snippet. Now, it you have a local copy, that cannot be removed or deleted by someone else. You can now reference it and link it inside various other files, as well as fuzzy search it, making the process of finding and effectively utilising it far simpler.

Most importantly, this sort of arrangement would only apply for user generated content. For applications, the traditional "file and folder" approach is far simpler to work with. Therefore, a document manager of sorts would be used to access and utilise these snippets, further improving our flexibility.

Famously, in greek mythology, Mnemosyne, the goddess of memory, was the mother of the Muses, the godesses of inspiration. Only with good input of ideas, and adequate storage, can something new and great be created. Each idea must stand atop a mountain of others, to be sent forth into the world. Our current data processing tools clearly lack ability to store our ideas, and something new must be done.