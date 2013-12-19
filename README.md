# help.codecademy.com

The Codecademy Help Center is a collection of answers to frequently asked questions about Codecademy's products. 

## Directory structure

```
.
├── published
│   ├── article1.md
│   └── article2.md
├── proposed
│   ├── article3.md
│   └── article4.md
└── README.md
```

Here's an overview of what each directory is for:

### published/

These are the articles that show up on http://help.codecademy.com. These files are [Markdown](http://daringfireball.net/projects/markdown/basics) formatted text files and have YAML front-matter (see below).

### proposed/

These are unpublished articles that are in progress.

## Contributing

### Writing a new article

To contribute an article, [create a new file](https://github.com/blog/1327-creating-files-on-github) in the **proposed/** directory. Name your file after the title of your article. For example, if your article's title is `Does Codecademy have a mobile app?`, you would create a new file named `does-codecademy-have-a-mobile-app.md`.

Next, open up the file and write your content in the following format: 

```
---
title: Does Codecademy have a mobile app?
---
Codecademy for iPhone is available to [download from the App Store](https://itunes.apple.com/us/app/codecademy-hour-of-code/id762950096?mt=8). You'll need an iPhone with iOS 7 or later.

Codecademy for Android is planned for the future.
```

The article's title lives in the YAML front-matter block, followed by the article's body. The article's body is written in [Markdown](http://daringfireball.net/projects/markdown/basics).

Lastly, commit your new file and send a pull request. Once your article is approved, it will be moved to the **published/** folder, automatically be assigned an `article_id`, and [show up on the Codecademy Help Center](http://help.codecademy.com/customer/portal/articles/1397043-does-codecademy-have-a-mobile-app-) shortly after.

### Editing an existing article

To edit an existing article, [use GitHub](https://help.github.com/articles/creating-and-editing-files-in-your-repository) and send a pull request.