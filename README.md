
![Repo Size][repo-size]
![Language][GitHub-language]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
![MIT License][license-shield]

<br />
<p align="center">



<h3 align="center" id="tech-blog">Tech Blog</h3>

<p align="center">
As a developer who writes about tech
I want CMS-style blog site so that I can<br> publish articles, blog posts, and my thoughts and opinions.

<br />
<a href="#how-to-download"><strong>Explore the docs »</strong></a>
<br />
<br />
<a href="https://drive.google.com/file/d/1ggIDJ1sTgvgWuuaisFTNsTJscwkWbCde/view?usp=sharing">View Demo</a>
.
<a href="https://github.com/Derimarg/tech-blog/issues">Report Bug</a>
·
<a href="https://github.com/Derimarg/tech-blog/issues">Request Feature</a>
</p>
</p>
<br />
<br />

> Link web page: https://tech-blog-dg.herokuapp.com/

<details open="open">
<summary>Table of Contents</summary>
<ul>
<li><a href="#description">Description</a></li>
<li><a href="#technologies">Technologies</a></li>
<li><a href="#how-to-download">Download</a></li>
<li><a href="#installation">Installation</a></li>
<li><a href="#prerequisites">Prerequisites</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="#roadmap">Roadmap</a></li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#questions">Questions</a></li>
<li><a href="#license">License</a></li>
</ul>
</details>

---
  
## Description
  
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments


### Example:
  
  ![Demo](/public/assets/images/demo.gif)


## Technologies

- <p><a href="https://nodejs.org/">Node.js</a></p>
- <p><a href="https://dev.mysql.com">MySQL</a></p>
- <p><a href="https://www.npmjs.com/">NPM</a></p>
- <p><a href="https://www.npmjs.com/package/mysql2">NPM Node MySQL 2</a></p>
- <p><a href="https://www.npmjs.com/package/sequelize">NPM Sequelize</a></p>
- <p><a href="https://www.npmjs.com/package/dotenv">NPM Dotenv</a></p>
- <p><a href="https://www.npmjs.com/package/heroku">Heroku CLI</a></p>

[Back To Top](#tech-blog)

---

## How to Download

- Simply copy the **SSH** to the terminal or Download the **ZIP File**:

## Installation

- Use the follow command at your terminal, **git clone** (Create a working copy at your local repository):

  ```
  git clone git@github.com:Derimarg/tech-blog.git
  ```

- After cloned the repository, create your own repository, copy the files to your repository and type in your terminal the follow commands. 

  ```
  git status

  git add -A

  git commit -m "Message to commit."

  git push or git push origin main
  ```

## Prerequisites

Before of using this application, is require to install dependencies, run the following command in your terminal:

  ```
  npm i
  ```

[Back To Top](#tech-blog)

---


## Usage

This is a open source program, feel free to use it, contact me to request features
    

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Derimarg/tech-blog/issues) for a list of proposed features (and known issues).

[Back To Top](#tech-blog)

---

<!-- CONTRIBUTORS -->
## Contributing

Contributions are part of this open source project. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/name-of-feature`)
3. Commit your Changes (`git commit -m "Add some feature"`)
4. Push to the Branch (`git push origin feature/name-of-feature`)
5. Open a Pull Request



## Questions

For additional help or questions about collaboration, contact me at: derimargray@gmail.com

- GitHub - [Derimarg](https://github.com/Derimarg/)
- Linkedin - [Derimar Gray](https://www.linkedin.com/in/derimar-gray-676275132/)
- Project Repository Link: https://github.com/Derimarg/tech-blog
- Video demo: https://drive.google.com/file/d/1ggIDJ1sTgvgWuuaisFTNsTJscwkWbCde/view?usp=sharing

[Back To Top](#tech-blog)

---


## License

MIT License

Copyright (c) 2021 Derimar Gray

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  

[repo-size]: https://img.shields.io/github/repo-size/Derimarg/tech-blog?style=for-the-badge
[GitHub-language]: https://img.shields.io/github/languages/top/Derimarg/tech-blog?color=yellow&style=for-the-badge
[contributors-shield]: https://img.shields.io/github/contributors/Derimarg/tech-blog.svg?style=for-the-badge
[contributors-url]: https://github.com/Derimarg/tech-blog/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Derimarg/tech-blog.svg?color=9cf&style=for-the-badge
[forks-url]: https://github.com/Derimarg/tech-blog/network/members
[stars-shield]: https://img.shields.io/github/stars/Derimarg/tech-blog.svg?color=blueviolet&style=for-the-badge
[stars-url]: https://github.com/Derimarg/tech-blog/stargazers
[issues-shield]: https://img.shields.io/github/issues/Derimarg/tech-blog.svg?style=for-the-badge
[issues-url]: https://github.com/Derimarg/tech-blog/issues
[license-shield]: https://img.shields.io/static/v1?label=license&message=MIT&color=yellowgreen.svg&style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/derimar-gray-676275132/
  