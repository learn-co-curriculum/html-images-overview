# Creating Images in HTML

You've seen them everywhere. Images make the internet engaging and fun. The ability to add images to webpages was in the very first HTML specification. That's how important it is. The best part is that adding images is both important, _and easy_. What a great combination. 

Images are added to a webpage with the `img` tag. Let's look at the below CodePen interface.

<iframe height='265' scrolling='no' title='HTML Images' src='//codepen.io/joemburgess/embed/rwjooK/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/rwjooK/'>HTML Images</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

On the left you will see the following code:

```html
<img src="https://curriculum-content.s3.amazonaws.com/web-development/FIS_New_Logo.png">
```

On the right you see our logo. This tag has something you've never seen before: an attribute. The image tag has one attribute called the `src` attribute. To load an image, we set the `src` attribute to equal the URL (wrapped in `"`) of the image we want. In this specific case the URL is:

```
https://curriculum-content.s3.amazonaws.com/web-development/FIS_New_Logo.png
```

If we wanted to change the image to something else, we just need to change the URL to be a different image. Here is another URL to use:

```
https://curriculum-content.s3.amazonaws.com/web-development/circle_logo.jpg
```

Go ahead and change the HTML code to use this new URL like this:


```html
<img src="https://curriculum-content.s3.amazonaws.com/web-development/circle_logo.jpg">
```

You should now see our circle logo instead of the full logo. Congratulations! You now know how to add images to websites using the `img` tag with a `src` attribute. Pretty cool :)
