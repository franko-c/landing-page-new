# My Landing Page

Welcome to my solution for the Landing Page project, as part of the curriculum and guidance provided by [The Odin Project](https://www.theodinproject.com/dashboard).

Feel free to connect with me on Discord: dar1en. I would love to connect with fellow learners and more experienced folks, too.

## Focus of the project
In addition to applying what I have learned from TOP up until now, I also tried to: 

  - Reuse classes as often as possible.
    - In practice, I found myself mostly reusing containers in the form of my 'wrapper' class, though typography classes are also scattered throughout.
    - I would have liked to significantly reduce the amount of HTML/CSS used overall whilst retaining the design and functionality of features such as the wrap...
  - Replace all content with a themed idea or company
  - Emulate as much as possible the kind of striking designs seen on landing pages, whilst adhering (..mostly) to the spec.
  - Inspired by [Josh Comeau](https://www.joshwcomeau.com/css/interactive-guide-to-flexbox/) and his wizard-like mastery of Flexbox, I made attempts at achieving some form of responsiveness with my own page.
  - I cannot say that I have even begun to scratch the surface of understanding with regards to his blog-post, and indeed the GIF of Homer Simpson f*cking about with the draw blinds kept popping up into my head, to hilarious effect.

## Challenges
As mentioned above, I found myself in a pinch, especially with the 'hero' and 'info-box' sections, making attempts with what felt like every CSS property known to man. I have been especially troubled by the `justify-content` line in this block of CSS:

```css
.wrapper {
    display: flex;
    align-items: center;
    justify-content: space-around;
    max-width: 900px;
    margin: 0 auto;
}
```

I would like to have set it to `space-between`, which would present the header and hero sections in a uniform manner, however, upon resizing the window to the point where wrapping takes place, the layout is no longer center and is instead aligned left. 

Pretty stumped on the above if anyone would like to offer some guidance or advice.

## Further notes
I used ChatGPT for the Animations and the RGB text styles. I would like to look into keyframes and what seems to be a form of masking in the future, however, I wanted to add some creative flair and as it was outside of the scope of the project, I consulted our A.I overlords!


# Credits

Mjolnir icon: 
<a href="https://www.flaticon.com/free-icons/thor" title="thor icons">Thor icons created by Freepik - Flaticon</a>

Block icon:
<a href="https://www.flaticon.com/free-icons/toy" title="toy icons">Toy icons created by Freepik - Flaticon</a>

Lightning icon:
<a href="https://www.flaticon.com/free-icons/thunder" title="thunder icons">Thunder icons created by Freepik - Flaticon</a>


Animations, RGB text:

[ChatGPT](https://chatgpt.com/)
