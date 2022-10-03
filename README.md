# Blog posts
Tech blog posts.
This repository contains a list of tech blog posts.
<br>

### Read this documentation in : <kbd>[<img title="Française" alt="Française" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/fr.svg" width="22">](./README.fr.md)</kbd> [Francais](./README.fr.md)
<br>

# 🎃 HacktoberFest 2022 🎃

If you came here for Hacktoberfest 🦇️:

Celebrate [Hacktoberfest](https://hacktoberfest.com/) by getting involved in the open source community by completing some tasks in this project.

## What is Hacktoberfest?

 HacktoberFest is digitalocean’s annual event that encourages people to contribute to open source throughout october. Much of modern tech infrastructure—including some of digitalocean’s own products—relies on open-source projects built and maintained by passionate people who often don’t have the staff or budgets to do much more than keep the project alive. HacktoberFest is all about giving back to those projects, sharpening skills, and celebrating all things open source, especially the people that make open source so special.

[https://hacktoberfest.com/](https://hacktoberfest.com/)

This repository is open to all members of the GitHub community. Any member may contribute to this project without being a collaborator.

## How can I contribute?

You can contribute to this repository, but before contributing, please go through our [CODE_OF_CONDUCT](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/CODE_OF_CONDUCT.md)

Feel free to contribute!
PS: Your contributions must follow the contribution guidline:

- Fork this repository (Click the Fork button in the top right of this page, click your Profile Image)
- Clone your fork down to your local machine

```markdown
git clone https://github.com/your-username/blog-posts.git
```

- Create a branch

```markdown
git checkout -b blog main
```

- Make your changes. Create a file(filename=`<your-githubusername.json>` in the `blogs` directory
- List any tech blog posts (you can google any), as many as you want. It should respect the format:
  
## For a single blog post. 
Use this format if your want to submit a single blog post. [Example](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/blogs/example-single.json)

```json
 {
    "Title": "Title of blog post",
    "Description": "A short description",
    "URL": "Link to blog post",
    "Author": "Author of the blog content"
  }
```
## For multiple blog posts. 
Use this format if your want to submit a multiple blog posts. [Example](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/blogs/example-multiple.json)
```json
{
  "posts": [
    {
    "Title": "Title of blog post",
    "Description": "A short description",
    "URL": "Link to blog post",
    "Author": "Author of the blog content"
  },
    {
    "Title": "Setting up an apache server on Ubuntu",
    "Description": "A summarized process of installing an apache server",
    "Link": "https://onecode.hashnode.dev/setting-up-an-apache-server-on-ubuntu",
    "Author": "Ndi Lionel"
  }
   ]
}
```
# Examples
1. [Single](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/blogs/example-single.json)
2. [Multiple](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/blogs/example-multiple.json)

# Committing
Please note the following before committing
1. Blog post links must be live and public.
2. All authors must be the real author(s) of the blog post.
3. All public domains are accepted.
4. Your PR will be closed if you provide an invalid blog post author.
5. No editing existing files on purpose. If you notice any problem with a file, please create an [Issue](https://github.com/Developer-Student-Clubs-UBa/blog-posts/issues/new)

```markdown
git add .
git commit -m 'feat: added my blog post: <github-username>'
git push origin blog
```

- Create a new pull request from your forked repository (Click the `New Pull Request` button located at the top of your repo). Make sure to compare across forks, then select this repository as target
- Add reviewers(optional)
- Wait for your PR review and merge approval!

- **Please STAR this repository** if you had fun!

### Thanks to all our contributors

![contibutors](./CONTRIBUTORS.svg)

Made with :purple_heart: 
