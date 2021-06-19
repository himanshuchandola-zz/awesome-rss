# Contribution Guide
[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)  [![Pull Requests Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

# Content

- [Adding rss feeds url](#adding-rss-feeds-url)
- [Adding New Category] (#adding-new-category)



## Adding Rss Feeds Url

You can contribute to this repository very easily!

1. Get the rss feed you want to add.

2. Fork Repository First.

3. Go to [OPML Lists](https://github.com/himanshuchandola/awesome-rss/tree/main/OPML%20Files) Folder in your forked Repository.

4. Select Folder according to the feeds category that you want to add.

5. Go to the .OMPL file in that selected folder and edit it.
 
  
  Go to the bottom of the file and copy paste this line before `</outline>` line.
  
  ```
  <outline title="enter-feed-title-here" text="enter-feed-title-here" type="rss" xmlUrl="enter-feed-url-here"/>
  
 ```
 
6. Enter feed title and enter feed url by replacing above text with appropriate info of your feed.

7. Once you're done, scroll to the bottom of the list to commit the change. Make sure the title of the commit is relevant. For example: Added RSS Feeds in Technology Category.

8. After adding the commit title, click on propose changes and follow the steps to create a pull request.

<hr><hr>

## Adding New Category

To add a new category, go to the Go to the [README](https://github.com/himanshuchandola/awesome-rss/blob/main/README.md) file of your forked Repository

Edit it and add a list item with the name of the category and the URL to it (hash of the slug of the name). For example:

```
- [New Category](#new-category)
```

9. Once you're done, scroll to the bottom of the list to commit the change. Make sure the title of the commit is relevant. For example: Added How to Contribute under New Category.

10 After adding the commit title, click on propose changes and follow the steps to create a pull request.

**That's it! Congratulations on making your contribution!**