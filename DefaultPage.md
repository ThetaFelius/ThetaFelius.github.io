## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ThetaFelius/ThetaFelius.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ThetaFelius/ThetaFelius.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


<details> 
  <summary>Q1: What is the best Language in the World? </summary>
   A1: JavaScript 
</details>

a[href="#spoiler"] {
  text-decoration: none !important;
  cursor: default;
  margin-bottom: 10px;
  padding: 10px;
  background-color: #FFF8DC;
  border-left: 2px solid #ffeb8e;
  display: inline-block;
}
a[href="#spoiler"]::after {
  content: attr(title);
  color: #FFF8DC;
  padding: 0 0.5em;
}
a[href="#spoiler"]:hover::after,
a[href="#spoiler"]:active::after {
  cursor: auto;
  color: black;
  transition: color .5s ease-in-out;
}


	

If editing the CSS is an option for you, you can simply use

[](#spoiler "Spoiler Filled Text")

and then use (pure) CSS to give the correct appearance.

a[href="#spoiler"] {
  text-decoration: none !important;
  cursor: default;
  margin-bottom: 10px;
  padding: 10px;
  background-color: #FFF8DC;
  border-left: 2px solid #ffeb8e;
  display: inline-block;
}
a[href="#spoiler"]::after {
  content: attr(title);
  color: #FFF8DC;
  padding: 0 0.5em;
}
a[href="#spoiler"]:hover::after,
a[href="#spoiler"]:active::after {
  cursor: auto;
  color: black;
  transition: color .5s ease-in-out;
}

<p>
  <a href="#spoiler" title="Spoiler Filled Text"></a>
</p>
