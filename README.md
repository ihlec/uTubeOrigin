# uTubeOrigin

## uBlock Origin YouTube Filters: More Distraction-Less Content

Simple List                 |  Multicolumn List 
:-------------------------:|:-------------------------:
![](horizontal.png)        |  ![](vertical.png)


### Add these lines to the "My filters" tab in the uBlock Origin settings

```
*ytimg.com*
#*yt3.ggpht*

! 2021-01-25 https://www.youtube.com
www.youtube.com##ytd-thumbnail.ytd-rich-grid-media.style-scope > .ytd-thumbnail.style-scope.inline-block.yt-simple-endpoint
www.youtube.com##ytd-thumbnail.ytd-rich-grid-media.style-scope
www.youtube.com##.ytd-rich-section-renderer.style-scope > .ytd-rich-shelf-renderer.style-scope
www.youtube.com##ytd-thumbnail.ytd-video-renderer.style-scope > .ytd-thumbnail.style-scope.inline-block.yt-simple-endpoint
www.youtube.com##ytd-thumbnail.ytd-video-renderer.style-scope
www.youtube.com###sub-menu > .ytd-section-list-renderer.style-scope
www.youtube.com###scroll-container > .ytd-feed-filter-chip-bar-renderer.style-scope
www.youtube.com###header > .ytd-rich-grid-renderer.style-scope
www.youtube.com##ytd-thumbnail.ytd-grid-video-renderer.style-scope > .ytd-thumbnail.style-scope.inline-block.yt-simple-endpoint
www.youtube.com##ytd-thumbnail.ytd-grid-video-renderer.style-scope
www.youtube.com###thumbnail > .ytd-thumbnail.style-scope.inline-block.yt-simple-endpoint
www.youtube.com###thumbnail
```
