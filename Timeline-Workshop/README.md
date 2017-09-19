# Timeline-Workshop
Materials for workshop to create temporal visualizations using <a href="https://timeline.knightlab.com/">Timeline JS</a>

### Step 1: 

  Build a new Google Spreadsheet using the <a  href="https://drive.google.com/previewtemplate?id=1pHBvXN7nmGkiG8uQSUB82eNlnL8xHu6kydzH_-eguHQ&mode=public">template</a> created by the Timeline JS folks or use the SampleTimeline.xlsx data and template for this workshop.

+ What kind of data will you need to include in the template? 
  Open the template and review the column headers.
  
  Data is required in at least one of these columns:
  
  | Year | Month | Day | Time | 
  
+ Data is not required in these columns, but can be included if you want to display a duration or period on timeline:
 
  | End Year | End Month | End Day | End Time | 

+ | Display Date | 
  
  + Date will be displayed in your timeline as a heading
  + Can be entered as a free-text (i.e. April 4, 1790), year(s) 1768 – 1772 

+ | Headline | 
 
  + Brief descriptive heading for timeline item 

+ | Text |
  
  + Longer narrative about the timeline item 
 
  + Use `<a href="URL" target="_blank">text</a>` within text to insert hyperlinks

+ | Media | Media Credit | Media Caption | Media Thumbnail | 
  
  + Use a simple URL to pull in an image, video, or other media in “Media”
  + Can use an `<iframe>` if URL does not work
  + Provide attribution for the work as well as an optional caption
  + Thumbnail for item will display image pulled from URL in “Media Thumbnail” 

+ | Type | 
 
  + Use "title” for a title slide (shown before others, doesn’t require date)
  + Use “era” for span of time with distinct color (no content)

+ | Group |
  
  + Create group or category for similar events
  + Groups them within one band/layer of timeline 

+ | Background |
  
  + Use RGB hex values or <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/color_value#Color_keywords ">keywords</a>
  
### Step 2: Back to Google Spreadsheets 
  
+ Select “File” and “Publish to the Web” 
+ Select “Publish” and copy the URL for use with Timeline JS.

### Step 3: Generate Timeline
   
+ Paste the URL on the Timeline JS page under Step 3 to generate your timeline
+ Review optional settings for your timeline where you can select from a list of fonts, languages, and change the zoom level for your timeline

### Step 4: Publish your timeline
	
+ Preview your timeline
+ Embed the code into your website 

### Additional Resources

+ <a href="https://timeline.knightlab.com/docs/index.html">Timeline JS Documentation</a>
+ Supported <a href="https://timeline.knightlab.com/docs/media-types.html">media types</a> in Timeline JS
+ <a href="https://github.com/NUKnightLab/TimelineJS-Wordpress-Plugin">Plugin</a> to embed a timeline in WordPress
+ Create timeline using <a href="https://timeline.knightlab.com/docs/json-format.html">JSON</a> instead of Google Spreadsheets
  
  + See example for formatting: TimelineExample.json