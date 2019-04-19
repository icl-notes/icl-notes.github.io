# ICL Collaborative Student Notes

This is the homepage for the Imperial College London student-run collaborative notes project. The goal of the project is to provide students with a way to collectively write and rewrite notes for courses. The project is run by the [ICL notes organisation](https://github.com/icl-notes) on GitHub. It was started by [Mayeul (Mike) Fournial](https://www.doc.ic.ac.uk/~mmf115/), a 2016 JMC student who hosts the links to the notes for all the courses on [his website](http://mayeul.ninja).

## Current topics

The project currently has some notes in
  * Maths
  * Computer Science

Students are encouraged to add other notes.

## How do I...

### Edit some existing notes?

#### LaTeX notes

You will need
  * A [GitHub account](https://github.com/join)
  * An (Imperial) [Overleaf account](https://www.overleaf.com/edu/imperial) (i.e. at least on the _collaborator_ price plan)
  * The accounts to be [linked](#link-my-github-and-overleaf-accounts)

  1. Go to the [icl-notes repository on GitHub](https://github.com/icl-notes) for the notes you want to edit.
  1. [Fork the repository](https://help.github.com/en/articles/fork-a-repo#fork-an-example-repository).
  1. Import the repository into Overleaf:

    1. Go to your [projects page](https://www.overleaf.com/project).
    2. Click "New Project".
    3. From the drop-down menu, click "Import from GitHub".

At this point, you now have a full personal copy of the notes. Edit them in Overleaf as much as you want - all the changes will only affect you.

Once you have an edit you want to contribute back to the project
  1. Open the Overleaf menu in the notes, and click on "GitHub" under "Sync".
  1. Click on "Push Overleaf changes to GitHub" - you'll be asked to provide a message explaining your changes. There are lots of guides online to writing good commit messages, but anything clear is fine.
  1. Click "Commit".
  1. [Make a pull request on GitHub](https://help.github.com/en/articles/creating-a-pull-request) for the repository you want to edit.

You're done! Someone from the project can now review your changes, and if they're accepted, merge them into the notes.

### Add my new notes?

#### LaTeX notes

Create a repository for your notes. If your notes are on Overleaf ([and you have a linked GitHub account](#link-my-github-and-overleaf-accounts)) then you can do this directly from your notes
  1. Open the Overleaf menu in the notes, and click on "GitHub" under "Sync".
  1. Follow the steps to create your repository.

Otherwise, you can [create a repository manually](https://help.github.com/en/articles/creating-a-new-repository), and push your notes to it using Git. Explaining how to use Git is out of the scope of this page - but there are plenty of tutorials online.

Once your notes are on GitHub, you can ask someone from the [ICL notes organisation](https://github.com/icl-notes) to consider adding it to the project - if they accept, the organisation will *fork* a copy of your notes, and they can then be edited collaboratively. 

### Link my GitHub and Overleaf accounts?

You will need
  * A [GitHub account](https://github.com/join)
  * A _collaborator_ Overleaf account ([Imperial provides such accounts for free](https://www.overleaf.com/edu/imperial))

  1. Go to your [Overleaf account settings](https://www.overleaf.com/user/settings).
  1. Click on "Link to your GitHub account".
  1. Understand the access Overleaf requests, then click "Authorize Overleaf".

### Contact us

#### You found a small mistake in the notes

You will need
  * A [GitHub account](https://github.com/join)

  1. Go to the relevant repository (the full list is available [here](https://github.com/icl-notes))
  1. Go to the _issues_ tab and try and see if there is an open issue that already exists for it in the list. If so give it a **thumbs up** to tell the maintainer that it's important!
  1. If no issue exists, create a new issue. Describe precisely what's the problem to help the maintainer understand the necessary changes that he/she will have to do. You can include screenshots or even paste some LaTeX inside [backticks quotes](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#quoting-code). _For anything longer than a paragraph, consider [editing the existing notes](#edit-some-existing-notes) straight away_.

#### Any other business

Contact us by sending an email to the shortcode **mmf115** (Mayeul Fournial).
