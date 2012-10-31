EventScraper
============

Scrapes Events.

------------

Cashes event on disk every definible amount of minutes upon request from a JSON file.

Event includes pictures, text, video links.

```html
<div id="events_wrapper">


<div class="events_container">
<div class="events_image_left"><img src="{flyers url}" alt="" width="{flyers width}" height="{flyers height}"></div>
<div class="events_text_right">
<p class="events_h1">{name}</p>
<hr>
<p class="events_h2"><br>{startdate format="Thursday, October 25, 2012"}</p>
<p><span class="events_h2">Time:</span> <span class="events_h3">{startdate format="23.00"} - {enddate format="03.00"}</span><br> <span class="events_h2">Minimum Age:</span> <span class="events_h3">{minimumage}</span><br> <span class="events_h2">Entry Fee:</span> <span class="events_h3">CHF {entryfee}</span></p>
<p>{description}</p>
</div>
</div>

<div class="events_container">
<div class="events_image"><div class="video_placeholder">{video}</div></div>
<div class="events_text"><p><span class="events_h2">{videodate format="Thursday, October 25, 2012 00:00"} {video text}</p>
</div>
</div>


<div class="events_container">
<div class="events_image"><div class="video_placeholder">{image}</div></div>
<div class="events_text"><p><span class="events_h2">{imagedate format="Thursday, October 25, 2012 00:00"} {image text}</p>
</div>
</div>
</div>


</div>
```