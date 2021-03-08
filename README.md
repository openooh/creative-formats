# creative-formats

----
(DRAFT) Working standards around OOH creative formats
----

Goals:
* Reduce the difficulty of larger buys in OOH (esp. multi-publisher)

Stategy: Define the smallest reasonable set of currently accepted OOH creative aspects to allow execution at scale across multiple publishers

## What is an OOH Creative?

A Creative is a unit of advertising to create a single exposure. Creatives are specified as a set of options for:

* Dimensions or physical space an ad will occupy
* A duration (time window) an ad will be displayed for
* File formats an ad can be transferred as

## Key Creative Aspects

### Dimensions

**Resolution** - Height and width of a creative defined in Device Independent Pixels. Candidates for standard sizes:

* 1080x1920 (1080p landscape - can be upscaled to 4K or downscaled to 768x1366, 720x1280)
* 1920x1080 (1080p portrait - can be upscaled to 4K or downscaled to 1366x768, 1280x720)
* 1024x768 (landscape - can be downscaled to 800x600, 640x480)
* 1400x400 (landscape - can be upscaled to 1920x540 or downscaled to 720x208, 560x160)
* 840x400 (landscape)

Handling mis-matches. Upscaling or downsampling 250?-50?% of the original resolution is an acceptable way for publishers to handle mis-matches between a creatives resolution and native screen resolution w/o prior coordination with buyers

**Aspect Ratio** - Width vs. height of a creative defined as a ratio. Candidates for standard aspect ratios:

* 16x9 (landscape)
* 9x16 (portrait)
* 4x3
* 7x2

Handling mis-matches. Letterboxing up to 10%? of the area of a screen is an acceptable way for publishers to handle mis-matches between creative and native screen sizes w/o prior coordination with buyers. Cropping creatives is *not* an acceptable way to handle mis-matches.

### Duration

**Duration** - amount of time an ad can/will play for. In practice, can be defined as a range for the purpose of sizes a publisher or advertiser will accept (e.g. in the case of display creatives). Candidates for standard durations:

* 6s
* 10s
* 15s
* 30s

Handling mis-matches. If a publisher allows a shorter video in a longer slot (e.g. a 10s video in a 15s slot) advertisers are expected to provide a video creative suitable for freezing the last frame for display until the end of the slot.

### File Formats

**Media Containers** 

* HTML5 (text/html) - as either a zip file or web link. May also include: HTML, Javascript, image, and video tags consistent with containers, and codecs specified below
* JPG (image/jpeg)
* PNG (image/png)
* MP4 (video/mp4)

Items we could consider, but may want to choose not to standardize/promote:
* WebM
* Ogg
* MOV
* Flash
* PDF
* PPT/Microsoft Office

**Video Codecs**

* AVC (H.264)

Items we could consider, but may want to choose not to standardize/promote:

* MPEG2
* VP8
* VP9

**Audio Codecs**

* AAC
* MP3

Items we could consider, but may want to choose not to standardize/promote:

* FLAC
* Vorbis

**File sizes**

* May be up to 5MB? in size

### Questions

* Event Handling (e.g. quartiles)
* Audio ads?

## References

* https://www.iab.com/wp-content/uploads/2019/07/IABNewAdPortfolio_FINAL_0719.pdf
* https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types
