# Part 2 - Writing your first chapter with Markdown

Now that you are all set up on Leanpub and your book is created, you can start writing your first chapter.

In this section, you will learn how to write your first chapter with Markdown using the in-browser editor.

More specifically you will:

1. Be introduced to the Leanpub in-browser plain text editor.
2. Learn the basics of Markdown.
3. Write your first chapter.
4. Generate your first preview.

## Opening the Leanpub In-Browser Editor

In your browser, go to leanpub.com and sign in with your account details.

From the home page of Leanpub, you can select the first dropdown menu in the top left corner called "Store" then select “Author”. 

![**Image 1:** *Leanpub Menu - Store*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-01-store-menu.png)

This will open up the author’s dashboard. From the second menu called "Metrics," you can navigate to "Books" where you will find your book under "Your Books" to the right. Click on the relevant book title then select "Write". 

![**Image 2:** *Leanpub Menu - Author*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-02-menu-arrow-write.png)

## The Leanpub In-Browser Editor

Now that you have the editor open, you will find the left pane contains two tabs: Manuscript (where your words live / chapters are stored) and Resources (where your media can be stored and referenced). For now, make sure that "Manuscript" is selected so that the three chapters are listed.

![**Image 3:** *First time opening the editor*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-03-online-editor-first.png)

## Create your First Chapter

To create your new chapter, click on the plus icon in the left pane under the existing chapters, enter a name for the chapter, and click on "OK". This will create a chapter and add it under the existing chapters.

![**Image 4:** *Adding a Chapter*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-04-new-chapter.png)

Delete the three default chapters. To do this, hover your mouse over the chapter name you want to delete and click on the gear icon that appears to the right. Click on delete and confirm the deletion. *Note: You can reorder your chapters by clicking and dragging the names, and you must have at least one chapter in your manuscript.*

![**Image 5:** *Deleting a Chapter*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-05-delete-chapter.png)

Select your chapter and click on the blank page to the right, as you will see as soon as you start typing, all the clutter on the page fades away. This is a fancy feature called "focus" mode that aims to keep the writer from being distracted. From here you will add some content to your book using Markdown.

## What is Markdown

Markdown is a lightweight markup language that is used to easily format plain-text documents. Leanpub uses a modified version of Markdown to format your ebook. In this guide I will introduce you to the basics of the Leanpub Flavored Markdown (LFM) while writing the first chapter of your book, however, you are welcome to check out the [LFM Manual](https://leanpub.com/lfm/read) for a more detailed guide.

## Start Writing

Give your chapter a heading. Note the preceding pound sign in the below example, this tags the following words as a heading(H1) and will format the text accordingly when generating the ebook.

![**Image 6:** *Heading*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-06-Heading-1.png)

Headings are used by LFM to structure your ebook, a single `#` (H1) creates a new chapter, sections are started with `##` (H2) and sub-sections with `###` (H3), you can carry on to create sub-sub-sections following the same pattern.*Note: there must always be a space between the ‘#’ and the first letter*

```
# Chapter 1
## Section 1.1
### Sub-section 1.1.1
```

Now add some introductory paragraphs. In my example, I link out to the Leanpub website. The syntax used to create links within your text is `[text](http://theURL.link)`. Leanpub will create footnotes of all your links at the bottom of the page.

![**Image 7:** *First Paragraph*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-07-first-paragraph.png)

With the introduction done, create the first section of your book. Here I will include a list. Bulleted lists are created with `- Item` and numbered lists `1. Item` as seen in the image below:

![**Image 8:** *Numbered List*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-08-numbered-list.png)

Now start writing the content of your book. You can do this by adding some sub-sections and writing your ideas within them. 

![**Image 9:** *Sub Sections*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-09-subsections.png)

To include images upload them under the "Resources" tab and link to them with the following syntax `![Image Caption](imageName.png)`.

To upload your images, click on the "Resources" tab in the top left to open the resources page. From here, click on the plus icon, click choose file, select the image you would like to upload from the file explorer then click on the "Add button" to upload. *Tip: You can click on the copy icon next to the name of your uploaded image and it will automatically add the correct link to your clipboard*

![**Image 10:** *Add Images*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-10-upload-image.png)

![**Image 11:** *Add Image links*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-11-image-links.png)

Note how the image captions in my example above contain asterisks, these are for emphasis. One asterisk on each side of your word or sentence makes it *italic* and two asterisks for **bold**. ie: 

`*Italic*` = *Italic*

`**Bold**` = **Bold**

## Preview your book

You now know enough to carry on writing and finishing your first technical book. But before you continue writing, let me show you how to generate a preview of what your book currently looks like.

In the top bar above your document, select "Preview". You will then be directed to the Preview page where you can click on "Create Preview".

![**Image 12:** *Create Preview*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-12-preview-page.png)

Leanpub will then generate your ebook in three different formats, showing a progress bar at the top of the page. You can also close the page as they will send you an email once your ebook generation is complete.

![**Image 13:** *Generate Ebook*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-13-generating-ebook.png)

When complete, links to download your book in PDF, EPUB, or MOBI formats will appear. Click on the first (PDF) link to download and preview your ebook in PDF format.

![**Image 14:** *Download Preview*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-14-download-preview.png)

In the next part of this guide, you will design and attach a book cover using Canva, and publish your book on the Leanpub store.
