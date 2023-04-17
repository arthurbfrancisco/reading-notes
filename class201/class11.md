# 201-Class:11

## Audio History 2000's

* The ability to use video and audio on the web has evolved significantly since the early 2000s. Initially, developers relied on third-party plugins like Adobe Flash for multimedia content, leading to compatibility and security issues. The introduction of HTML5 provided native multimedia elements, such as video> and audio>, allowing easier integration and better compatibility across browsers

* In the video> element, the 'src' attribute specifies the video file's URL, and the 'controls' attribute displays default video controls for users to play, pause, and adjust volume. These attributes make it easy for developers to embed video content on web pages.

* Fallback content inside the video> element is essential because it ensures users with incompatible browsers or unsupported video formats can still access meaningful content. This may include a text description, download link, or alternative video player.

### Grid

**Grid layout** differs from Flex in that it's a two-dimensional system, handling both rows and columns, while Flex is a one-dimensional system focused on either rows or columns.

A **grid container** is the parent element containing grid items; grid items are the child elements positioned within the grid. Grid lines are the dividing lines that separate rows and columns, defining the boundaries of grid items.

### Responsive Images:

* Developers should make images responsive not only for visual appeal but also for performance optimization, as it helps reduce loading times and saves bandwidth by serving appropriately sized images for each device.

The **'srcset'** attribute in the img element allows developers to provide multiple image sources with different resolutions. The 'sizes' attribute defines the width of the displayed image relative to the viewport. Together, they enable the browser to choose the most suitable image based on the device's screen size and resolution.

**ex:**
img srcset="small.jpg 480w, medium.jpg 800w, large.jpg 1200w"
     sizes="(max-width: 480px) 480px, (max-width: 800px) 800px, 1200px"
     src="medium.jpg" alt="Example image
