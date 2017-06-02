# KC Technology Group Blog
Welcome to the KC Technology Group Blog!  This blog is created using [Hexo](https://hexo.io), and uses the [Beautiful-Hexo](https://github.com/twoyao/beautiful-hexo) theme.

## Environment Setup

Initially, this guide will focus on getting the website up and running on macOS; in the future I'll expand the guide with information on Windows and Linux platforms.  

In order to build the Blog, you must first get your Node.js environment setup.  We'll do this locally, specific for this project.  First, start with cloning the repository:

```bash
git clone https://github.com/kctechgroup/kctechgroup.blog
```

Next, change into the directory and retrieve all of the dependencies:

```bash
cd kctechgroup.blog
npm install
```

The above will setup the dependencies for the Hexo base installation.  Since the `blog/` folder is already present in the repository, you only need to install its dependencies next:

```bash
cd blog/
npm install
```

At this point, your Node.js host installation will have installed all of the proper dependencies for using Hexo with the KC Tech Group Blog.  If you'd like to ensure that you're able to utilize the local project's package set, you can add the following alias to your `~/.bash_profile` or `.zshrc` (depending on your shell):

```bash
alias npm-exec='PATH=$(npm bin):$PATH'
```

## Previewing the Site

You can use (combined with the `npm-exec` alias defined above) Hexo to preview the site on your local machine:

```bash
npm-exec hexo server
```

This will launch a local server on port `4000` that you can open in your browser with [http://localhost:4000](http://localhost:4000). 

## Building the Static Output

You can use (combined with the `npm-exec` alias defined above) Hexo to generate the site:

```bash
npm-exec hexo generate
```

## Deploying the Site

Once you're happy with the modifications (and assuming you have the appropriate privileges to publish to the _master_ branch on GitHub Pages), you can use Hexo to deploy the site as well:

```bash
npm-exec hexo publish
```

This will utilize your system-stored Git credentials in order to process the deploy functions.

# Conclusion

Typically, the deployment phase will be completed by approved members of KC Tech Group.  The rest of the steps can be utilized on a branch of the website to add content and evaluate it.  Submit a pull request once you've got your post ready and we'll merge it in and deploy!

If you have any issues or comments/suggestions, submit a GitHub issue: https://github.com/kctechgroup/kctechgroup.github.io/issues

Thanks and Happy Coding!