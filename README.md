# Horiseon Social Solution Services, Inc.

<!-- ![Horiseon Logo](./assets/images/logo.PNG) -->

<img src="./assets/images/logo.PNG" width=40% height=40%>

## About This Webpage

This webpage is the homepage of Horiseon Social Services, Inc. Horiseon is a company that provides services regarding `Social Media Marketing`, `Search Engine Optimization`, and `Online Reputation Management`

## Sourcecode Problems

While working with this company, upon reviewing their sourcecode we were left with errors within the HTML code. Our criteria to fix this problem is as followed:

* **View the source code to find HTML elements** - To make sure the webpage's source exists with HTML elements
* **Review & Revise HTML structure** - This is to make sure the structure is followed logically
* **Review & Revise image alt attributes** - Makes sure images are correctly identifiable in the code
* **Correct header content & add title** - The header content in the code needs to be in sequential order and a title for the page must be added

### Finding The Errors

Upon reviewing the code we did find `HTML elements`. However, the structure was incorrect and the `image attributes` showed up missing as show below:

```
<div class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
```

Further reviewing the code, we also found the `header` section which was incorrectly ordered and missing a unique descriptive title as show below:

```
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>
```

### Approaching the problems