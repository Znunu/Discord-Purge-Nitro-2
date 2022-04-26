## About
Discord currently has a lof interface elements, which are rathes useless for those without nitro. 
They are mostly there to remind you that nitro is a thing.
Unfortunately they can get pretty annoying.
Thee goal of this project is remove as many of them as possible.

## How To
Run the script below in the console
```html
style = `<style>
  
button[aria-label="Open sticker picker"],                           /* Remove sticker picker */
button[aria-label="Send a gift"],                                   /* Remove gift button */
.containerExpanded-3MGTRr,                                          /* Remove sticker wave option in new DMs */
a[href='/store'],                                                   /* Remove the nitro tab next to friends */
div[aria-label="Close DM"],                                         /* Remove the X to close DMs */
.optionBox-1b4n4P:nth-child(2),                                     /* Remove the "try it out" avatar pickers */
none {display:none !important;}

</style>`
document.head.innerHTML += style
```

## Before & after
![image](https://user-images.githubusercontent.com/61394004/137299903-5f69d92b-229d-406f-82cc-5be4d294fa1f.png)
![image](https://user-images.githubusercontent.com/61394004/137299912-78929f6d-147b-4225-a346-1746b03768fa.png)


![image](https://user-images.githubusercontent.com/61394004/137299949-c9fef237-3a1d-46cb-9a0c-e196fa67308a.png)
![image](https://user-images.githubusercontent.com/61394004/137299968-4b21dd81-03d4-410e-bf19-8c4708e209c8.png)


![image](https://user-images.githubusercontent.com/61394004/137300327-45dff995-b006-4dd4-b16c-c14b6a93f992.png)
![image](https://user-images.githubusercontent.com/61394004/137300242-412519ac-3bae-489d-9da2-b19d3160e115.png)



