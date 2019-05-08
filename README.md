# Notes: Udacity's Writing READMEs 

___

READMEs help developers makes sense of other people's code. 

**Who is Documentation For?**

When you hear the phrase technical documentation you might think of dry literature that is difficult to understand. But good documentation isn't boring or unapproachable -- often it's written in plain English! Sometimes, it's even written as a series of guides or tutorials.

As it turns out, there isn't a secret ruling body that makes laws for what documentation should and shouldn't look like. That's because unlike your code which is written for computers documentation is written for humans. Documentation exists to help us make sense of the code that we've written, which may not always be quite as intuitive as we'd like it to be.

For instance if you're working a large open source library that other people can use, good documentation is absolutely essential for acquiring both users and contributors. If your documentation is good, people will want to use your library in their projects. If your documentation is great, people might even chip in and help you with your library.

Perhaps your project is a portfolio piece to help you land your first job. As a developer, in that case you'll want to document your work in a way an employer can easily skim and pull relevant information. Give some thought as to who is going to be reading your documentation. You'll want it to be easy for anyone to dive into your code and get it up and running without any hiccups!

___

 People will look at your README as an example of how to get your project up and running. 

 So if you don't provide a README or document well enough for others to follow, then they may not use your project and move on. 

 Documentation will help the future you, figure out what you were thinking when you were writing your code. As well as help others follow along. 

 ___


## Anatomy of a README

Title 

Description 

Installation 

Usage

Don't make any assumptions on what the end user knows. 

So make sure your README includes these:

1. What steps need to be taken?
2. What should the user already have installed or configured?
3. What might they have a hard time understanding right away?


___

As your code base grows you could add the following to your README:

1. Known bugs
2. Frequently asked questions
3. Table of contents


___

Markdown 101
Markdown is a light markup language often used for READMEs (though you'll find other use cases for it, too!). It is fairly straightforward, and much of the syntax is intuitive.

But as it turns out, there are many different dialects of Markdown, just like in a spoken language. Each of these dialects is known as a flavor of Markdown. Most of these dialects are pretty much the same, with only minor differences.

Since your READMEs will ultimately end up on GitHub, we'll be using GitHub Flavored Markdown. I've included a link to the full documentation for it in the instructor notes (and we'll be using that later in this course), but I'll get you started with a quick crash course.

Feeling Bold?
To make text bold, surround it with double asterisks. So this code:

Isn't today a **wonderful** day?
becomes: Isn't today a wonderful day?

This reads a bit more nicely than a <strong> tag would in HTML, and takes considerably fewer keystrokes to type out.

Italics, I tell you!
To italicize text, surround it with underscores. So this code:

And in that moment I thought to myself: _Did I turn off the stove?_
becomes: And in that moment I thought to myself: Did I turn off the stove?

Much like the previous example, this code reads much more like English, which is great for when you're skimming the original document.

To code, or not to code?
Inline code is useful for indicating that you're writing code and not a regular word. For this, you'll surround text in backticks (`, not a single quote). So this code:

You should use the `strong` tag.
becomes: You should use the strong tag.

...which makes much more sense than "You should use the strong tag."

The Title Sequence
Headings are even simpler! For h1 through h6 tags, all you'll need is a # before your text. The number of #s you include tells Markdown which header tag you're using. For example:

## This is an h2.

### This is an h3.

becomes...

This is an h2.
This is an h3.




