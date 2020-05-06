---
title: Writing Content for the Maker Event Playbook - Google Docs + Markdown Converter
keywords: General Topics
tags: [How to, contribute, writing, content]
sidebar: home_sidebar
permalink: /contribute/editing-google-docs
summary: Not everyone in your team is going to be comfortable working in GitHub, but they have great knowledge we want to share. This document is a walkthrough on a workflow using Google Docs and some free tools so your team can contribute to this project without ever logging into GitHub.
---
## Overview of the workflow

This workflow seems to work best for our team as most people at this point understand how to use Google Docs. You could use other document editing software, such as word, we found this worked best for us, after reading through how we do it, you might have something better for your team.

The workflow goes like this:

1. Google Doc (start with template linked below)
2. Export as a .docx
3. Import into markdown converter (markdown is the language git uses)
4. Copy/paste into GitHub
5. Publish!

## Google doc template

Start by downloading our google doc template [here.](https://docs.google.com/document/d/1gITR6dMpdQlwCors3B6je-uC3p_hvwRirAqr10cBQIs/edit?usp=sharing)

If you would like to look at a filled out example, you can see one [here.](https://docs.google.com/document/d/1vLAyp8SXgyxwtDAu_Mha2d_3INH6rGgX6SjU46dNQik/edit?usp=sharing)

There really are two sections to this document, first is the Front Matter, second is the content. Let&#39;s look at these two sections in depth.

### Front Matter

![image]({{site.baseurl}}/images/general/MEP-gdoc-1.png)

The Front Matter is sort of the info section for what you are writing up. There are 3 sections that your contributors will need to fill out, if you are the one importing you will need to check some of this as there is other Front Matter that needs to be in place for your page to work correctly, but for the case of the template it is noise to your contributors so we chose to leave it out, otherwise we would have to answer the same questions each time someone is using it.

#### Title:

This is pretty straight forward, this is the title for the page. It is what is going to be displayed on your navigation pages, and of course on the page itself. Try to keep it short and simple. **Do not use : in your title, it will cause a code error and not render your page.**

#### Tags and Categories:

Tags are tools used to help users find the page. They should be some alternative words to your title. For example if you were writing on soda, you would tag it with pop, cola, etc.

**All of your tags must be inside of the [brackets] and comma separated.**

#### Summary:

The summary is what shows up at the top of the page, this is the quick version of your page, what you&#39;re going to tell them.

**The summary is only one paragraph.**

### Content

The content is obviously the meat of your work, this is where all the information you are conveying will go. There are some specifics on how you format this section and we will cover below.

### Sections

If you notice at the top of this page and in the document, there are sections that show up in the table of contents and as well help with organizing the page. This is done through the &quot;styles&quot; control in google docs. It is just to the left of your font and font size, for paragraphs it should look like this, saying &quot;Normal text&quot;

![image]({{site.baseurl}}/images/general/MEP-gdoc-2.png)

When you click on it, you will see a few different options, we will be using the different Headings. The lower the number correlates to how it displays in the table of contents menu.

**You should never use Heading 1, this will cause search errors**

So for your top level sections you should be using Heading 2, then sub points get Heading 3, and so on.

![image]({{site.baseurl}}/images/general/MEP-gdoc-3.png)

As you work on your document you will see what your table of contents is going to look like to the left of the page in the grey area you will see the Document Outline, this table of contents is especially useful to your users as it helps them go directly to the content they want.

![image]({{site.baseurl}}/images/general/MEP-gdoc-4.png)

While you are editing you can use bold, italics, lists/bullets, and hyperlinks just as you would in any google doc, they will get translated. Photos are a little more difficult.

### Photos

Photos will have to be manually uploaded and inserted into your document on the github end. So you will need to save out your images separately, and give them file names that make sense. Do not use spaces, use underscores or dashes in the file names.

In your writing put a separate line with the file name where you want the picture, wrapped in some code. So for instance if you have a picture named soda-pop-flavors.jpg that you want in a section you would block out

![image]({{site.baseurl}}/images/general/soda-pop-flavors.jpg)

Then the publisher will know what picture to put where, if you got the code above correct, they might not have to do anything other than upload the files. But if you didn&#39;t it should stand out to them and they can edit accordingly.

### Download as .docx

As amazing as this writeup is, most of your contributors won&#39;t want to read this whole thing. So in the template we have put a small section in green on how they use the headings section. If you are a contributor and have read this far, you are pretty awesome. You can erase the little help section in green as you don&#39;t want that on your page, and you are totally an expert at this now.

Just as you would think, up at the top bar, click **File** , then click **Download** , then **Microsoft Word (.docx)**

![image]({{site.baseurl}}/images/general/MEP-gdoc-5.png)

Then save the document to your computer, somewhere you will remember as you will be uploading this to the converter.

## File Conversion

**If you&#39;re just a contributor and not working in the GitHub side, you don&#39;t need to read any further.**

I mean this writeup is pretty great, so you could keep reading.

So now you have a word document, we have been using a simple online word to markdown converter, [https://word2md.com/](https://word2md.com/)

There are others with pluses and minuses, this one is simple, so we have been using it.

Upload your word doc to the site and click the big blue Convert button.

You will see the markdown in the middle column and a preview on the right column, highlight it and copy the middle column to your clipboard (Ctrl+C)

## Github page

So you probably should have already navigated to your page where the content is going to land, in GitHub. Remember in your repo, it is going to be under the pages folder.

If you are just putting up your own version of a page from our master repo, you can go into the section, then find the page you want to edit.

If you have a new page you will need to create it.

To edit the page click on the little pencil at the top right

![image]({{site.baseurl}}/images/general/MEP-gdoc-6.png)

You will then see the basic text display in the markdown language.

![image]({{site.baseurl}}/images/general/MEP-gdoc-7.png)

This is where it&#39;s up to however you want to copy/paste, as you can see in the Front Matter there are some other sections that aren&#39;t in the google doc. Depending on your workflow you might add them into the doc before exporting, or just copy and paste the front matter separate from the content. But when you are done you should have something that looks like the above image.

## Publish

At the bottom of the word editor there is a section that says **Commit Changes**

We like to put a little note as to what was done, i.e. the initial upload, or a spelling correction, it helps if something is wrong you can use the features of Github to track or roll back those changes.

And with that you are done! Rinse and repeat for your different pages.
