# Using Images in HTML

## Getting Started

The ability to add images to webpages was in the very first HTML specification.
That's how important it is. The best part is that adding images is both
important, and easy. What a great combination!

## What We’ll Cover

- The `<img` tag
- Tag attributes

## Images in HTML

When we bring an image into an HTML document, we’re essentially telling the
browser where to find it so that it can be displayed. We do this by adding some
more information into the HTML tag, and, when it comes to images, the tag we
want to use is the `img` tag.

<iframe height='265' scrolling='no' title='HTML Images' src='//codepen.io/joemburgess/embed/rwjooK/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/rwjooK/'>HTML Images</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

On the left you will see the following code:

```html
<img src="https://curriculum-content.s3.amazonaws.com/web-development/FIS_New_Logo.png">
```

On the right, you see our logo. This tag has something you've never seen before:
an __attribute__. The image tag has one attribute called the `src` attribute. To
load an image, we set the `src` attribute to equal the URL (wrapped in quotation
marks) of the image we want. In this specific case the URL is:

```url
https://curriculum-content.s3.amazonaws.com/web-development/FIS_New_Logo.png
```

If we wanted to change the image to something else, we just need to change the
URL to be a different image. Here is another URL to use:

```url
https://curriculum-content.s3.amazonaws.com/web-development/circle_logo.jpg
```

Go ahead and change the HTML code to use this new URL like this:

```html
<img src="https://curriculum-content.s3.amazonaws.com/web-development/circle_logo.jpg">
```

You should now see our circle logo instead of the full logo. Congratulations!
You now know how to add images to websites using the `img` tag with a src
attribute.

## Summary

Some HTML tags have extra information or instructions embedded in them, which we
call attributes. We use the src attribute in an `img` tag to point the browser to
the location of an image we want to display.

## Key Terms to Review

- Attribute

## Resources

- [Mozilla Developer Network `img` tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)

## What’s Next

Next, we’ll take a look at one of the other most-used HTML tags: the link tag.
