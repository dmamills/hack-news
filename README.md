##H2 Installation

```javascript
$ npm install hack-news
```

##H2 Usage
The examples below show how to access the IDs of the top stories on Hacker News.

```javascript
var hn = require('hack-news');

//Returns an array of all the article ids for the top stories on hacker news
var all = hn.allTopStories();

/*Returns an array of article ids in the amount of your choice.
So if you wanted the top ten stories on Hacker News it would look like this.*/
var topTen = hn.numberOfTopStories(10);
```
This is it for now but stay tuned I will be adding alot more.