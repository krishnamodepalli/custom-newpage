# custom-newpage

An all new New_Tab for chrome that is able to make searches.

## Changes for different search-engines:
1. duckduckgo
```html
<form action="https://duckduckgo.com/" class="searchform" method="get" name="searchform">
```
2. google
```html
<form action="https://google.com/search?q=" class="searchform" method="get" name="searchform">
```
3. bing
```html
<form action="https://bing.com/search?q=" class="searchform" method="get" name="searchform">
```

## How to add to Chrome
1. (3 dots on top-right corner) > Settings.
2. Settings > On start-up > Open a specific page.
3. Paste the index.html path in there.
4. Settings > Show Home button > In' Enter custom web address' paste index.html path.

Click the Home button on left-top corner to go to the custom New_tab page.

## TODO's
- [X] Dark Mode (Adapts to the system theme.)
- [ ] Showing time in the Web-Page.
- [ ] Greeting User.