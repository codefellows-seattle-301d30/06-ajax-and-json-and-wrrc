Call Stack

LIFO  last in first out

FILO  first in last out

How code order runs (bottom up!)

...
articleView.initIndexPage
localStorage.rawData
new Article
Article.all.push()
callback (articleObject)
.forEach
new Date()a
new Date ()b
callback(a,b)
.sort()
Article.loadAll()
function (rawData)  --call back
.then
$.getJSON
Article.fetch all()
_________________________