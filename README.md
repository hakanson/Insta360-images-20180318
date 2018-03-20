# Insta360-images-20180318
Insta360 ONE images from 2018-03-18

## Overview
Depending on the software workflow, the metadata and sizes of stiched images from the Insta360 ONE vary significantly.

## Software
- Insta360 ONE Camera firmware v1.16.7
- iPhone 7 running iOS 11.2.6
- Insta360 ONE app v2.3.0 (App Store version)
- Insta360 ONE app v3.0.0 (Enterprise App preview)
- [Insta360 Studio Windows v2.12.1](https://www.insta360.com/download/insta360-one)
- [Exif Pilot 5.2](http://www.colorpilot.com/exif.html)
- Google Photos app v3.15.187419394

## Details
With the Insta360 connected to the iPhone 7 running Insta360 ONE app v3.0.0, a 360 photo was taken on 2018-03-18 at 8:58:51pm.

The `.insp` file format appears to be compatible with the `.jpg` format so a copy of `IMG_20180318_205851_239.insp` (5,228 KB) was saved as `IMG_20180318_205851_239.insp.jsp` for inspection
- the EXIF/IPTC/XMP data was exported to `IMG_20180318_205851_239.insp.jsp.xml`
- `/Exif/Image/Make` = 'Arashi Vision' and `/Exif/Image/Model` = 'Insta360 ONE'
- many other `/Exif/Image/*` tags are set
- `/Exif/Gps/*` values are not set correctly (so where do the correct values come from below?)

Used Insta360 ONE app v3.0.0 to save `IMG_20180318_205851_239.insp` to iOS Photos as `tempImageDataFile.jpg` but the photo synced over iCloud Photos as `tempImageDataFile(37).jpg` 
- the EXIF/IPTC/XMP data was exported to `tempImageDataFile(37).jpg.xml`
- `/Exif/Image/Make` = 'Insta360' and `/Exif/Image/Model` = 'Insta360 ONE'
- `/Exif/DateTimeOriginal` is not set so iOS displays GMT value of `creation date`
- file size is huge (12,831 KB) compared to insp (5,228 KB)
- `/Exif/Gps/*` values are set correctly
- `/Xmp/GooglePhotoSphere/Projection Type` is set to `equirectangular`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `True`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `100`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `2018-03-19 01:58:51 +0000`
- iOS Photos app did not display with a 360 viewer

Used [JPEGMini](http://www.jpegmini.com/main/shrink_photo) to shrink `tempImageDataFile(37).jpg`  as `tempImageDataFile(37)_mini.jpg`
- file size is small (1,888 KB) compared to original jpg (12,831 KB) or insp (5,228 KB)

Used Google Photos app to upload to cloud then downloaded as `tempImageDataFile.jpg` from Google Photos web application.
- file size is small (1,004 KB) compared to original jpg (12,831 KB) or insp (5,228 KB)
- Google Photos app did not display with a 360 viewer, but web did

Used Insta360 Studio Windows to export `IMG_20180318_205851_239.insp` as `IMG_20180318_205851_239.jsp`
- the EXIF/IPTC/XMP data was exported to `IMG_20180318_205851_239.jsp.xml`
- `/Exif/Image/Make` = 'Insta360' and `/Exif/Image/Model` = 'Insta360 ONE'
- no other `/Exif/Image/*` tags are set
- `/Xmp/GooglePhotoSphere/Projection Type` is set to `equirectangular`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `True`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `95`

Used Insta360 ONE app v2.3.0, `IMG_20180318_205851_239.insp` was saved to iOS photos album as `tempImageDataFile.jpg` but the photo synced over iCloud Photos as `tempImageDataFile(38).jpg` 
- the EXIF/IPTC/XMP data was exported to `tempImageDataFile(38).jpg.xml`. 
- `/Exif/Image/Make` = 'Insta360' and `/Exif/Image/Model` = 'Insta360 ONE'
- `/Exif/DateTimeOriginal` is not set so iOS displays GMT value of `creation date`
- file size is huge (12,834 KB) compared to insp (5,228 KB)
- `/Exif/Gps/Latitude` is set correctly but `/Exif/Gps/Longitude` is set to 0
- `/Xmp/GooglePhotoSphere/Projection Type` is set to `equirectangular`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `True`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `100`
- one copy of `/Xmp/GooglePhotoSphere/Use Panorama Viewer` is set to `2018-03-19 01:58:51 +0000`

## Recomendations
- set `/Exif/DateTimeOriginal`
- set iOS filename similar to Insta360 Studio Windows
- set a single instance of `/Xmp/GooglePhotoSphere/Use Panorama Viewer`
- reduce file sizes on iOS similar to Windows