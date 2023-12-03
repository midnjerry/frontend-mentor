# Frontend Mentor UI Challenges
UI Challenges from https://frontendmentor.io.  Extra practice and examples to further improve UI skill set.

# Tips and Tricks

## Installing Fonts
Fonts already come downloaded under the /fonts folder.  Custom fonts should be downloaded and included with the distributed site.  

Importing fonts
```
@import url('https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;600;700&display=swap');

/* The `*` represents all elements */
* {
    font-family: 'Work Sans', sans-serif;
}
```

## Initializing all elements - for better control
This is a nice trick.  Reset every element to padding: 0, margin: 0, and box-sizing: border-box so that every element is consistent.

```
/* The `*` represents all elements - every element is reset for better control */
* {
    margin: 0;
    padding: 0;
    /* https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing */
    box-sizing: border-box;
}
```
