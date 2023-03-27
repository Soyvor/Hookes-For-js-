# HookeJs

![](https://github.com/oekshido/HookeJs/workflows/Node.js%20CI/badge.svg)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

An open source plagiarism detector built in node.

## Installation

```
npm install hookejs
```

## Usage

For plagiarism detection:

```javascript
hooke = require("hookejs")
plagiarisedText = `Sherlock Holmes (/ˈʃɜːrlɒk ˈhoʊmz/ or /-ˈhoʊlmz/) is a fictional private detective created by British author Sir Arthur Conan Doyle. Referring to himself as a "consulting detective" in the stories, Holmes is known for his proficiency with observation, deduction, forensic science, and logical reasoning that borders on the fantastic, which he employs when investigating cases for a wide variety of clients, including Scotland Yard.`
hooke.matchPrint({text: plagiarisedText})
```

## Functions

-   `match`:
    Returns `Source` objects with a list of `Match` objects, which include the matched text start, end, a calculated score and a few more variables.

-   `matchPrint`: Prints `match` results in an understandable manner.

## Note

This package can a google custom search API key and engine id, which can be accessed through function parameters or the G_API_KEY and G_ENGINE_ID environment variables. If not provided, it will scrape the results (use at your own risk)


# Read The readme File for Better Overview 

Thank you , Soyvor at your service for any issues that come in the run.


Hooke JS is a JavaScript tool that is designed to help users detect plagiarism and ensure the uniqueness of their content. It is an easy-to-use and powerful solution for web developers, bloggers, content creators, and anyone who is concerned about the originality of their work.

With Hooke JS, you can quickly and accurately check your content for plagiarism, and get instant results that highlight any potential issues. The tool uses advanced algorithms and machine learning techniques to identify and compare your content with other online sources, making it easy to detect any similarities or copied content.

Hooke JS is built with simplicity in mind, and it can be easily integrated into your existing workflow. The tool is compatible with all major web browsers, and it works seamlessly with popular content management systems like WordPress and Drupal.

In addition to its plagiarism detection capabilities, Hooke JS also offers a range of other useful features. For example, it can help you to optimize your content for search engines by suggesting relevant keywords and providing insights into your content's readability and SEO-friendliness.

Overall, Hooke JS is an essential tool for anyone who wants to ensure the originality and quality of their online content. Whether you're a blogger, journalist, or business owner, this powerful JavaScript tool can help you to create content that is unique, engaging, and effective.
