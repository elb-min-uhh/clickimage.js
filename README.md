# clickImage.js

clickImage.js is a plugin for elearn.js


## Documentation

At first add required *.css* and *.js* files to your *.html*-Document.

1. `<link rel="stylesheet" type="text/css" href="assets/css/clickimage.css">`
2. `<script type="text/javascript" src="assets/js/clickimage.js"></script>`


### Code-Snippet

Replace variables with your content:

1. $IMAGEPATH (Path to your image)
2. $IMAGEALT (Alternative text of your image)
3. $PINCOORDS ([[x,y],[x,y],...] Values: 0-100 (percent) of image width/height, like: [[30,30],[80,60],[66,10]]

```html
<div class="clickimage">
    <div class="imagebox">
        <img src="$IMAGEPATH" alt="$IMAGEALT" onload="clickimagePins(this,$PINCOORDS)">
    </div>
    <div class="pininfo">
        <div>
            <h3><span class="highlight">Task 1</span> Headline</h3>
            <p class="task">Lorem ipsum...</p>
            <ul class="links">
                <li><a href="http://example.org">http://example.org"</a><br>Lorem ipsum</li>
                <li><a href="http://example.org">http://example.org"</a><br>Lorem ipsum</li>
            </ul>
        </div>
        <div class="inline">
            <h3>Headline</h3>
            <p>Lorem ipsum...</p>
        </div>
    </div>
</div>
```


#### Inline-Content

To create an inline content, simply use `<div class="inline">` instead of `<div>`.


## License

clickImage.js was developed from [eLearning-Büro MIN](https://www.min.uni-hamburg.de/studium/elearning.html) of Universität Hamburg.

This software is licensed under [MIT-License](http://opensource.org/licenses/mit-license.php).

Copyright (c) 2016 Michael Heinecke, eLearning-Büro MIN, Universität Hamburg