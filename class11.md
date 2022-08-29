# Readings: Audio, Video, Images

Why is this topic important? it's helpful to provide imagery to attract clients to video and audio. Makes a webpage more dynamic and interesting

## Reading Questions

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.


2. Describe the use of the src and controls attributes in the < video element.
**src**
In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

**control**
Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.
  
3. Why is it important to have fallback content inside the <video> element?
  this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers
  
4. Write a very short story where <audio> and <video> are characters.
    There once was a person, named Audio, who did not have the ability to see. One day, they met someone, whose name was Video. They could see and hear, which made Audio very upset. In the end, Audio realized that they could be just as powerful since lacking sight enhances auditorial senses through their poetry.

[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

5. How does Grid layout differ from Flex?
grid has a 3d layout, flex is 2d. 

6. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
The element on which display: grid is applied. It’s the direct parent of all the grid items

Grid Item The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t

Grid Line The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. 
  
[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

7. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  Responsive images improve performance across different devices. 

8. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
srcset defines the set of images we will allow the browser to choose between, and what size each image is.
sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true
  
9. How is srcset more helpful for responsive images than CSS or JavaScript?
srcset is more helpful because the images in the srcset do not load by the browser immediately. In fact, the browser will only load one of them based on the users view port and the conditions we set. With JavaScript, all the images would load and therefor take up resources, causing slower load times for the user.
  
# Bookmark and Review
[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
  
This article is review from Class 05.

[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
  
  ## Things I wanna know more about
  Using the grid
