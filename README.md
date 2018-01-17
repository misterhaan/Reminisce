# Reminisce
Reminisce is a photo slideshow skin for [Rainmeter](https://www.rainmeter.net/).  It randomly shows a photo from your pictures folder and its subfolders, can launch that photo in the default photo viewing application, and can go back to the previous photo in case you wanted to launch that one but missed it.

The following settings can be configured by editing the ini file (right-click on the skin and choose edit skin from the menu).  Find them in the [Variables] section:

<dl>
<dt>PhotosPath</dt>
<dd>Set to the base directory containing photos.  Default is your windows Pictures folder.</dd>
<dt>ChangeSeconds</dt>
<dd>How long to display a photo before moving on to the next random photo.  Default is 180 (3 minutes).</dd>
<dt>SizeW and SizeH</dt>
<dd>Width and height in pixels of the photo part of the skin.  Use to make the skin larger or smaller.  It's best to set them to the aspect ratio of most of your photos (commonly 4:3 or 16:9).  Default 200 × 150 (4:3 aspect ratio).</dd>
<dt>BorderSize</dt>
<dd>Width of the border around photos in pixels.  Default 4.</dd>
<dt>BorderColor</dt>
<dd>Color of the border around photos.  Default is white with 80% opacity (ffffffcc).</dd>
<dt>BackColor</dt>
<dd>Color of the background space between photos and the border (only visible for photos that do not match the aspect ratio).  Default is black with 47% opacity (00000077).</dd>
</dl>

## Revision History

### 1.0
* Initial release.

## External Libraries
Reminisce includes icons from [Material Design](https://material.io/icons/).