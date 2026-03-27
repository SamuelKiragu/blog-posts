### Why I built this site.
The 'why' and the 'what' that make this site a reality.
Azure, GitHub, GitHub Actions, GitHub Copilot

### A Digital Garden!
The digital garden manifesto is inspiring! Having a small space in the Internet that gradually grows as you grow is comforting to me; its a place to comfortably make mistakes and learn from them. This site is my implementation of this old yet gold notion of a digital garden. I will use this space to share helpful findings. I will also gradually improve the look and feel of the site :) 

As I find and share, I hope that you'll benefit (and perhaps be entertained). If this inspires you to start something of your own, Great!

### And the tools I used are ...
Are you interested in *what* and perhaps *how* this came to be? 

```
If yes: read on :)
If no:  read on ;)
```

#### 1. The GitHub Platform!
[The GitHub Platform](https://github.com/) provides different products. Collectively, the use of GiHub's products has impacted every development step I've undertaken.

GitHub allows users to host their repositories and make them publicly available. [Astro Nano](https://github.com/markhorn-dev/astro-nano), the parent of this blog's interface, is an example of a publicly available repository.  In the same spirit, I've made this modified template [publicly available](https://github.com/SamuelKiragu/blog-template), too! 

[My blog posts](https://github.com/SamuelKiragu/blog-posts) are publicly available, too! The blog posts are formatted in markdown. Markdown makes them have a consistent look across different platforms. The creative commons license governs the use of the posts. 

> *To save you the reading, you can use my blog posts freely :)*

#### 2. GitHub Copilot
[GitHub Copilot](https://docs.github.com/en/copilot), a product of GitHub, has been helpful in the development iterations while developing this site. GitHub Copilot has been instrumental in planning changes, explaining code blocks in the cloned repository, quickly iterating over ideas, bootstrapping GitHub Action Workflows, and fixing errors along the way. 

Leveraging GitHub's Issues and PRs (Pull Requests), developers can easily collaborate with multiple AI agents across different repositories. 

> **For example:** I encountered an issue building the static app on Azure. I had deleted some unneeded modules and code from the cloned GitHub repository. This left some broken links that raised Typescript exceptions while running a deployment workflow. To solve this:
>  
>  1. I used GitHub Copilot to explain the issue encountered.
> 2. I used the error logs generated in the workflow's failing job and the suggested explanation from the explain request prompt to GitHub Copilot to create an issue. 
> 3. I assigned the created issue to GitHub Copilot. GitHub Copilot created a PR and I interacted with the agent using code reviews.

#### 3. GitHub Actions
[GitHub Actions](https://docs.github.com/en/actions), another product of GitHub, has provided a communication pipeline across the project. 

First, GitHub Copilot Cloud sessions run as action workflows. Therefore, this tool has supported all my GitHub Copilot interaction on the cloud.

Secondly, I have used GitHub Actions to create workflows to upload blog posts. After uploading a blog post using git, my custom workflow commits  the post to the respective repositories. 

Thirdly, VS Code's, Static Web App extension leverages GitHub Actions to deploy the site with Microsoft Azure’s [Static Web Apps](https://aka.ms/staticwebapps) service.

### Finally ...
In as much as I've interacted with other development tools like astro, react, git, and typescript (only to name a few), the tools mentioned above have been foundational. To get a better overview of the tools used in this blog, feel free to **fork the [blog-template repository](https://github.com/SamuelKiragu/blog-template)** 
