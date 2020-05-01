# Git in a Jiff

## (Black Sea in History Version)

<a href="http://moacir.com">Moacir P. de Sá Pereira</a> | <a href="http://twitter.com/muziejus">@muziejus</a><br />
Research Data Librarian | <a href="http://library.columbia.edu">Columbia University Libraries</a> <br />
moacir.p@columbia.edu | <a href="http://pronoun.is/he">pronoun.is/he</a><br />
New York, NY, 1 May 2020

Note: Thanks all for coming, and let’s get started on today’s workshop. First
thing’s first, I want you all to open up this presentation on your computers.
It will make things much, much easier. Head on over to 

---

## [talks.moacir.com/black-sea-git-in-a-jiff](http://talks.moacir.com/black-sea-git-in-a-jiff)

Note: This will let you follow along with me, which will come in handy when
you have to click on links and copy paste things.

---

## Outline

1. VS Code
2. Git
3. GitHub
4. Jekyll

---

## Why VS Code?

<ol>
<li class="fragment">Free</li>
<li class="fragment">Similar across platforms</li>
<li class="fragment">One-stop shop with integrated shell</li>
<li class="fragment">Excellent Git support built in</li>
</ol>

---

## Isn’t Google Docs Free and Platform Agnostic?

<ol>
<li class="fragment">“Free”</li>
<li class="fragment">Ethics, Availability, and Sustainability of Plain Text (see <a href="https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown">Tenen and Wythoff</a>)</li>
</ol>

---

## Windows Users Please Install Git:

[https://git-scm.com/download/win](https://git-scm.com/download/win)

* Choose 64-bit.
* Start the install.
* The defaults are fine, but be sure to choose “Git from the command line and
also from 3rd-party software” and to choose “Checkout Windows-style, commit
Unix-style” (they should be default values)

---

## Git Is…

* “free and open source distributed version control system designed to handle
everything from small to very large projects with speed and efficiency.”
* “easy to learn.”
* A busybody keeping track of all the changes to all your files and never
forgetting them.

Note: That part about “easy to learn” is probably not true. Git is insanely
powerful, and even people who use it every day probably don’t use more than a
tiny chunk of it. And that’s because what IS easy is learning just enough Git
to make it useful for you.

---

## Git Is…

<ol>
<li class="fragment">Part of a backup solution</li>
<li class="fragment">An intention tracker/writing journal</li>
<li class="fragment">A declutterer</li>
<li class="fragment">A multi-verse generator</li>
<li class="fragment">A collaboration engine</li>
</ol>

---

## The Four Main Steps to Git

<ol>
<li class="fragment">Save - continuous (with autosave). Not even part of Git.</li>
<li class="fragment">Stage - less frequent. Also known as `git add`.</li>
<li class="fragment">Commit - less frequent still.</li>
<li class="fragment">Push - less frequent still.</li>
</ol>

Note: Saving is what you already do. The files you work with have changes that
get saved to the disk. Then, in staging a file, you’re giving Git a heads up
to keep track of the changes you have made. In committing, you’re putting down
a milestone for the changes the files have undergone. And in pushing, you’re
syncing your new changes with a server.

---

![The four steps to git](https://i.imgur.com/mNfax2z.png)

--> Icons by Font Awesome. [License](https://fontawesome.com/license).

Note: Here’s a slightly more visual way to think about this. But you’ll notice
here that I’m talking about “changes,” not a “document.” This is a central
conceit of Git.

---

## You’re not working on a _document_.<br />You’re working on a _project_.

Note: For the rest of today, we’ll be working on a project that is your CV.
It’s not a single document. In fact, it’s many--it’s at least the html page
that is your online CV and the pdf that is the print version. In a project,
files come and go. They could be datasets, collections of text like chapters
or sections of an article, or even, like in today’s workshop, the various
parts of your CV.

---

## Back to VS Code & GitHub

1. Enable autosave.
1. Clone the [`black-sea-in-history`](https://github.com/black-sea-in-history/black-sea-in-history) repository from GitHub via VS Code’s
   Command Palette (cmd-shift-p or ctrl-shift-p).

---

![Screenshot of VS Code](https://i.imgur.com/8mUW5Hd.png)

---

## Key Files in _The Black Sea in History_

* 📁 `_chapters` (for different chapters)
* 📁 `_cities` (for different city pages written in markdown)
* 📁 `_contributors` (for different contributor pages written in markdown)
* `about.md` (About page, as a Markdown file)
* `bibliography.md` (Bibliography page, as a Markdown file)
* `chronology.md` (Chronology page, as a Markdown file)
* `maps.md` (Maps page, as a Markdown file)

---

## Markdown?

* Yes, [Markdown](https://guides.github.com/features/mastering-markdown/)

---

## Jekyll and Ruby

* [Jekyll](http://jekyllrb.com) is a Ruby-based static-site generator
* It can create pages that are hosted on GitHub for free
* It removes a lot of the maintenance in keeping sites active

---

## Install Remaining Dependencies

1. Install the bundler gem
1. Use bundler to install jekyll
1. Install volta, node, and yarn
1. Use yarn to install the javascript libraries

---

## Install Remaining Dependencies

In the terminal in vscode:

1. `gem install bundler`
1. `bundle install`
1. `curl https://get.volta.sh | bash` (close and reopen terminal, then:)
   `volta install node` and `volta install yarn`
1. `yarn install`

---

## Fire up Jekyll

`jekyll s` in the terminal in vscode

---

## Create your Contributor page

`_contributors/moacir.md`:

```markdown
---
name: Moacir P. de Sá Pereira
---

Moacir works at 
[Columbia University Libraries](http://library.columbia.edu).
```

---

![The four steps to git](https://i.imgur.com/mNfax2z.png)

--> Icons by Font Awesome. [License](https://fontawesome.com/license).

---


---

## Thanks!
### [@muziejus](http://twitter.com/muziejus) / moacir.p@columbia.edu
