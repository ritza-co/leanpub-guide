## Part 2 - Writing your first chapter with Markdown

Now that you are all set up on Leanpub and your book is created, you can start writing your first chapter.

In this section, you will learn how to write your first chapter with Markdown using the in-browser editor.

More specifically you will:

1. Be introduced to the Leanpub in-browser plain text editor.
2. Learn the basics of Markdown.
3. Write your first chapter.
4. Generate your first preview.

Continuing where we left off in part one after you have clicked on the first "start writing" link on the "getting started" page, you should have a book with three introductory chapters in front of you. 

### Open your book from the Leanpub menu

If you do not have the editor open you can find your book and open it from the Leanpub menu

From the home page of Leanpub, you can select the first dropdown menu in the top left corner called "Store" then select “Author”. 

![**Image 1:** *Leanpub Menu - Store*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-01-store-menu.png)

This will open up the author’s dashboard. From the second menu called "Metrics," you can navigate to "Books" where you will find your book under "Your Books" to the right. Click on the relevant book title then select "Write". 

![**Image 2:** *Leanpub Menu - Author*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-02-menu-arrow-write.png)

### The Leanpub In-Browser Editor

Now that you have the editor open, you will find the left pane contains two tabs: Manuscript (where your words live / chapters are stored) and Resources (where your media can be stored and referenced). For now, make sure that "Manuscript" is selected so that the three chapters are listed.

To the right in the top bar, you have some more tabs/options that we will touch on as we progress. In the settings tab, you can customize a few things like font size and switch to dark mode but let’s not get distracted and rather start getting words down in your first chapter.

![**Image 3:** *First time opening the editor*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-03-online-editor-first.png)

### Create your First Chapter

Firstly, to create your new chapter, click on the plus icon in the left pane under the existing chapters, enter a name for the chapter, and click on "OK". This will create a chapter and add it under the existing chapters.

![**Image 4:** *Adding a Chapter*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-04-new-chapter.png)

You can now delete the three default chapters. To do this, hover your mouse over the chapter name you want to delete and click on the gear icon that appears to the right. Click on delete and confirm the deletion. *Note: You can reorder your chapters by clicking and dragging the names, and you must have at least one chapter in your manuscript.*

![**Image 5:** *Deleting a Chapter*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-05-delete-chapter.png)

Select your chapter and click in the blank page to the right, as you will see as soon as you start typing, all the clutter on the page fades away. This is a fancy feature called "focus" mode that aims to keep the writer from being distracted. From here we will add some content to your book using Markdown.

### What is Markdown

Markdown is a lightweight markup language that is used to easily format plain-text documents. Leanpub uses a modified version of Markdown to format your ebook. We will only cover the basics of the Leanpub Flavored Markdown (LFM) while writing the first chapter of your book, however, you are welcome to check out the [LFM Manual](https://leanpub.com/lfm/read) for a more detailed guide.

### Start Writing

Give your chapter a heading. Note the preceding pound sign in the below example, this tags the following words as a heading(H1) and will format the text accordingly when generating the ebook.

![**Image 6:** *Heading*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-06-Heading-1.png)

Headings are used by LFM to structure your ebook, a single `#` (H1) creates a new chapter, sections are started with `##` (H2) and sub-sections with `###` (H3), you can carry on to create sub-sub-sections following the same pattern. Parts of your book are identified with '-#', ie `-# Part 1`  *Note: there must always be a space between the ‘#’ and the first letter*

```
-# Part 1
# Chapter 1
## Section 1.1
### Sub-section 1.1.1
```

Let’s add some intro paragraphs and link out to the Leanpub website, the syntax used to create links within your text is `[text](http://theURL.link)`. Leanpub will create footnotes of all your links at the bottom of the page they are on.

![**Image 7:** *First Paragraph*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-07-first-paragraph.png)

With the introduction done, let's create the first section and include a list. Bulleted lists are created with `- Item` and numbered lists `1. Item` as seen in the image below:

![**Image 8:** *Numbered List*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-08-numbered-list.png)

Now we can start writing the actual content, lets do this by adding some sub-sections and include some images. Images are added with `![Image Caption](http://theImageURL.png)`, alternatively, to use local images, you can upload them under the "Resources" tab and change the link to `![Image Caption](resources/imageName.png)`

![**Image 9:** *Add Image*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-09-add-image.png)

Note how the image captions contain asterisks, these are for emphasis, below are some more ways you can use to style your text:

```
*Italic*
**Bold**
***Italic-Bold***
____Underline____ (4x Underscore each side)
____**Combine** them in a ***sentence*** like *this*____
```
*Italic*

**Bold**

***Italic-Bold***

____Underline____ 

____**Combine** them in a ***sentence*** like *this*____

### Preview your book

You now know enough to carry on writing and finishing your first technical book. But before you continue writing, let’s generate a preview of what your book currently looks like to see how all the above content populates.

In the top bar above your document, select "Preview". You will then be directed to the Preview page where you can click on "Create Preview".

![**Image 10:** *Create Preview*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-10-preview-page.png)

Leanpub will then generate your ebook in three different formats, showing a progress bar at the top of the page. You can also close the page as they will send you an email once your ebook generation is complete.

![**Image 11:** *Create Preview*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-11-generating-ebook.png)

When complete, links to download your book in PDF, EPUB, or MOBI formats will appear. You can click on the first (PDF) link to download and preview your ebook.

![**Image 12:** *Create Preview*](https://i.ritzastatic.com/leanpub-guide/02-first-chapter-markdown/02-12-download-preview.png
)

In the next part of this guide, we will complete your book with an eye-catching cover using Canva and publish your book on the Leanpub store.
