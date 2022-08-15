[Home](/README.md)

# Class 11 - Audio, Video, Images

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.  
    Early 2000s plug-in technologies had security and accesibility issues. They have been replaced by using HTML elements `<audio>`, `<video>` and JavaScript APIs.
2. Describe the use of the `src` and `controls` attributes in the `<video>` element.  
    `src` attribute works the same way it does for `<img>` element, and contains the file path for the video. `controls` attribute provides the playback options for the user, such as play, pause and volume control.
3. Why is it important to have fallback content inside the `<video>` element?  
    Fallback content provides the user with a paragraph and a link to the video if their browser is unable to load the video.

## A Complete Guide To Grid

1. How does Grid layout differ from Flex?  
    Grid wrapping differs from Flex in that the elements wrap in same gridlines as other elements before them. Grid is two-dimensional; we can position the items in rows and colums rather than one or the other as we can do with Flex. Grid is better at overlapping and more stable.
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.  
    Grid container is the parent element for the grid items.
    Grid items are children of the grid container.
    Grid lines are the lines dividing the grid container and giving it structure. They can be horizontal or vertical.

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?  
    Displaying smaller images when needed reduces the amount of bandwidth the image takes up.
2. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.  
    `srcset` includes the filepaths and sizes of the images we want the browser to choose from.
    `sizes` defines the condition for the browser to choose one image over the other based on its size.

    ```html
    <img srcset="example-480w.jpg 480w,
             example-800w.jpg 800w"
     sizes="(max-width: 600px) 480px,
            800px"
     src="example-800w.jpg"
     alt="example image">
     ```

3. How is `srcset` more helpful for responsive images than CSS or JavaScript?  
    Because the `<img>` elements load with the HTML before CSS and JavaScript load. 