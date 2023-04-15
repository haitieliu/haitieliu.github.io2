
# Creating a Github Website

Creating a website using R markdown to showcase your project


## Installation

1. Creating a github repository using your [username].github.io

2. Creating a home page in r markdown and knit in html, name in the file index.html
```{r}
ABOUT ME

Hi， My name is [name]
```
3. Redner your project file in r and knit them in html!
```bash
Project 1
project 2
project 3
```
4. Creating a yml file, and yaml them into one website, with navbar, tabs are created to navigate between your home page and projects page
```
name: "my-website"
always_allow_html: true
navbar:
  title: "My Website"
  left:
    - text: "Home"
      href: index.html
    - text: "Project1"
      href: Project1.html
```
5. Log into your website username.github.io to check out your new website!



## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

