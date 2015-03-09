# OpenCleveland.Github.io

The website for the Open Cleveland Brigade

### Forked from [Code for San Franciso Repo](https://github.com/sfbrigade/sfbrigade.github.io) ([Website](http://codeforsanfrancisco.org/))

## Blogging Instructions
If you are tasked with writing posts for the site blog, follow these instructions:

What you'll need:
- a github account with access to the opencleveland github organization.
(ask @skorasaurus for this)

To create a new post:
- go to http://prose.io/#opencleveland/opencleveland.github.io/tree/master/_posts/blog
- if the page asks you to "authorize with github", click the authorize button
note: ensure you are signed in with your github account
- create a new blog post by clicking the "new file" button
- you'll be taken to a page where you can create your new blog post
- once you're done writing your blog post using markdown, set published to true in the metadata to make the file appear on the blog. 

There are various controls for formatting text, links and creating images:

To add an image:
- click on the add image button.
- click "selecting one".
- pick a file on your local computer.
- in the "image url" field, ensure to change the url from something like
"_posts/blog/yourimagename.jpg"
to
"images/blog/yourimagename.jpg"
this is changing the path of the image to be images/blog/ rather then _posts/blog.
!this is important, as the image will not work if this is not done!
- add in alt text for the image. alt text is important for user's that browse by websites using text readers.
 
Blog details
- the blog master page itself is in /blog/. This page grabs Markdown files (.md) from /_posts/blog/ and turns them into blog posts based on the filename.
- each blog post gets its own file in /_posts/blog/. The filename should begin with the blog entry's date in YYY-MM-DD format. The prose.io page linked above automatically does this.

### Tech

Built using [Jekyll](http://jekyllrb.com/), [Bootstrap](http://getbootstrap.com/), and the [CfAPI](https://github.com/codeforamerica/cfapi).

## Contributing

### <a name="issues"></a>Submitting an Issue

We use [GitHub Issues](https://github.com/) `//fix link` to track bugs and features. We've included several of our open GitHub Issues right on our homepage using the [Civic Tech Issue Finder](http://www.codeforamerica.org/geeks/civicissues).


### Running the Site Locally on Your Computer

To run the site locally on your own computer (most helpful for previewing your own changes), you will need Jekyll installed ([click here for Jekyll installation instructions](http://jekyllrb.com/docs/installation/).)

Fork and clone the repository, then run the following command in the root directory of the repo:

`jekyll serve`

or

`jekyll serve --watch` which will watch for changes to files.

Your computer should now be serving your local copy of the site at:

[http://0.0.0.0:4000](http://0.0.0.0:4000).

### Sharing Your Changes Using Jekit

You can use the nifty [Jekit](https://jekit.codeforamerica.org/) app to preview changes you make to this site.

To do this, fork this repo, and commit your changes on a branch to your fork. You can then preview what your changes look like by navigating to:

https://jekit.codeforamerica.org/USERNAME/sfbrigade.github.io/BRANCHNAME/ `fix link`

For a basic example of its usage, if GitHub user **@lolname** has made changes to the projects page on their fork (on the `master` branch), they can preview their changes using Jekit by going to:

https://jekit.codeforamerica.org/lolname/sfbrigade.github.io/master/projects

### Submitting a Pull Request

1. Fork the project.
2. Create a topic branch.
3. Implement your feature or bug fix.
4. Commit and push your changes.
5. Submit a pull request.
