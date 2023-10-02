# audio-video-images

#### Explain how the ability to use video and audio on the web has evolved since the early 2000s.

The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions < video > and < audio > elements and the availability of JavaScript APIs for controlling them.

#### Describe the use of the _src_ and _controls_ attributes in the < video > element.

- _src_ works the same way it does for images
- _controls_ must be included in the browser's own control interface (or via a JavaScript API). At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

#### Why is it important to have fallback content inside the < video > element?

Fallback content will be displayed if the browser accessing the page doesn't support the < video > element.

#### How does Grid layout differ from Flex?

Grid is the first CSS module created specifically to solve the layout problems innate to core HTML and Flexbox.

#### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- Grid container: the element on which _display: grid_ is applied. It’s the direct parent of all the grid items.
- Grid item: the children of the grid container.
- Grid line: the dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

#### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Images look different across different devices, which causes problems with accessibility and navigation. Responsive images solve this issue.

#### Define the < img > attributes _srcset_ and _sizes_. Write an example of how they are used.

- _srcset_ defines the set of images we will allow the browser to choose between, and what size each image is.
- _sizes_ defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true.

#### How is srcset more helpful for responsive images than CSS or JavaScript?

When the browser starts to load a page, it starts to preload images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images hence the need to implement solutions like _srcset_. By the time JavaScript has kicked in, the original image would already have been loaded, and you would load the small image as well.
