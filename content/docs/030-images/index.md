---
title: Figures
weight: 30
---

# Figures

Figures (both pictures and video clips) could have been included in the [Markdown](../020-markdown) chapter. But there are  techical and style issues about how figures are treated in these online documents which merit a separate chapter.

## Style for Figures and Captions

When work started on *Belfry Upkeep* - the first online document - our 'model' was the *Manual of Belfry Maintenance*. This printed document does not reference figures by number, and figures have no captions. This makes for ugly text, such as “The figure below...” or the “The figure on the previous page...”. A decision was made, therefore, that figures (including video clips) should have a numbered caption to allow reference and additional explanation in the text. This decision has been carried on to the two further online documents.

There is an exception to the 'numbered figures' style. In some cases, we had attractive images which supported the 'feel' of a chapter without being technically critical. These have been used at the top of some chapters as 'Title Figures' without a caption.

{{< hint info >}}
There is a 'figure' [shortcode](../020-markdown/#shortcodes) which includes a caption and allows the image to be floated left or right, with text continuing beside it. The use of this was considered and rejected because:

 - The rendering of the caption is not attractive and seems to be impossible to control.
 - More seriously, the 'floating' may not work well if there are several figures close together, especially if using a narrow screen.
{{< /hint >}}

## Pictures and Drawings

The Markdown code to insert an image file is:

```
![alt text](link to image)
```

 - Note the exclamation mark at the start.
 - The 'alt text' is intended to provide accessability as it can be read by a 'screen reader' application.
 - The image link could be to an image file anywhere in the system (which might include a path). For simplicity, image files in the chapters of these documents are held in the same folder as the index file.

To illustrate this, the favicon used for *Online Documents* has been loaded into the '030-images' folder. The code to show this, with a caption, as Figure 1 in this chapter is:

```
![Favicon for online documents](favicon.png)

*Figure 1: Favicon for Online Documents*
```

This renders as:

![Favicon for online documents](favicon.png)

*Figure 1: Favicon for 'Online Documents'*

{{< hint warning >}}
In case you don't know, the favicon is a 'logo' for the document, appearing at the top left and on a browser tab. You will see other examples in the three online documents. A good logo should not need an explanation but, just in case, the 'e' represents that fact that this is an electronic document and the scroll reflects that a chapter is read by scrolling down, rather than turning a page.
{{< /hint >}}

Images will usually be from photographs, ideally initially in high resolution. The image files are processed using a graphics application (Adobe Elements or gimp, for example) as follows:

 - The photograph is cropped as necessary and possibly enhanced to improve brightness or contrast.
 - Annotations are added if necessary. To avoid cluttering images with text, key points are identified by a letter and an arrow. The points are then described in the text. For example “*... secured by a locknut – shown at (D) on Figure 2*”. If an image has only one key point it will usually be shown just by an arrow and the reference in the text might be “*These are metal rods fitted between wheel and headstock to brace the wheel (arrowed on Figure 4).*”
 - The image size is reduced, usually to 500px width, to improve download speed.
 - The file is saved in jpg format, using a 'Save for web' option if available.


{{< hint info  >}}
**Style Tip**: Initially, the images in each chapter were named to include the chapter name and figure number - for example, 'introduction_fig-3.jpg'. But it became clear that this caused difficulties if figures were added or removed. The recommendation now is to use descriptive, non-numbered file names. For example, in figure 1 of this document the file name (as you will see above) is 'favicon.png'.
{{< /hint >}}

## Video Clips

### YouTube

Many videos of interest are now available through YouTube - there is a YouTube index available on the [Central Council website](https://cccbr.org.uk/youtube-index/). This resource has clickable links which open the YouTube site in a new browser window. If you try this, you will see that, while YouTube is free, you pay for it by having to watch advertisements.

Sending a user away from your site to another one is never a good idea - they may get interested and not come back. A better solution is to embed the link and Hugo has a [shortcode for this](https://gohugo.io/content-management/shortcodes/#youtube). This requires you only to enter the YouTube video ID - the code that follows 'v=' in the video's url.

This is used in [*Belfry Projects*](https://belfryprojects.cccbr.org.uk/docs/040-managing-project/#undertaking-the-work) to show short (and very professional) videos taken at the start and end of the Eastnor bells project. This is much better (although you may still see advertisements) but if you watch to the end you will see that it finishes with suggestions of other YouTube videos "that might be of interest". Again, not ideal in our view.

### Vimeo

An alternative is Vimeo. This does not include advertisements. The [shortcode](https://gohugo.io/content-management/shortcodes/#vimeo) for this, like YouTube, needs only the ID of the Vimeo video. As an example, taken from *Belfry Upkeep*, the  code:

![Traditional stay & slider](i-1.png)

produces Figure 2 (try clicking the triangular 'start' icon at bottom left):

{{< vimeo 727296663 >}}

*Figure 2: Operation of a traditional stay and slider*

There is a free version of Vimeo but this has few options for how to show a video. The next upgrade (used here) provides more options - for example, when finished, the video returns to the opening screen. Our current subscription only allows access to one person but the next higher level will allow access to three users.

{{< hint info >}}
Our view is that Vimeo provides a much more professional appearance and we would suggest the use of a three-user subscription for  developments of the existing three documents and any further ones.
{{< /hint >}}

## Attribution

Acknowledgement of the producers of images is given in an 'Image credits' section at the end of each chapter. This is not needed for most of this document, as almost all of the images have been produced by the author but, as an example, the code for the two images used in this chapter (one of which was taken from *Belfry Upkeep* and was not produced by the author) is as follows:

```
| Figure | Details |
| :---: | --- | 
| 1 | Favicon for 'Online Documents'. (Design: Robin Shipp) |
| 2 | Operation of a traditional stay and slider. 
(Video: James Joynson) |
```

The rendering of this code can be seen in the following section.

## Image Credits

| Figure | Details | 
| :---: | --- | 
| 1 | Favicon for 'Online Documents'. (Design: Robin Shipp) |
| 2 | Operation of a traditional stay and slider. (Video: James Joynson) |

----

{{<hint info>}}
**[Previous Chapter](../020-markdown/)** - **[Next Chapter](../040-navigation-menus)**
{{</hint>}}

----

## Disclaimer
 
*Whilst every effort has been made to ensure the accuracy of this information, neither contributors nor the Central Council of Church Bell Ringers can accept responsibility for any inaccuracies or for any activities undertaken based on the information provided.*

Version 0.1, September 2023

© 2023 Central Council of Church Bell Ringers
