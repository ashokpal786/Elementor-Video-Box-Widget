# Elementor-Video-Box-Widget
Elementor video widget with YouTube/self-hosted support, dynamic thumbnails, ACF URL tags, hover preview, click playback, loop, and auto-stop.

BDDEX Elementor Video Widget
BDDEX Elementor Video Widget is a lightweight WordPress plugin that adds a custom Elementor video widget for YouTube and self-hosted videos. It is designed for video cards, course pages, portfolios, galleries, and dynamic listing layouts where each item needs a thumbnail, hover preview, and full video playback.

Description
Create clean, interactive video cards in Elementor with YouTube or self-hosted videos, custom thumbnails, muted hover previews, full click-to-play playback, loop settings, Dynamic Tags support, and automatic stopping of other videos on the same page. The widget is useful for listing templates, course grids, portfolios, landing pages, and any layout where videos should feel lightweight until a visitor chooses to watch.

Short Description
An Elementor video widget for YouTube and self-hosted videos with custom thumbnails, hover preview, click playback, Dynamic Tags, loop, and auto-stop behavior.

GitHub Repository Description
Elementor video widget with YouTube/self-hosted support, dynamic thumbnails, ACF URL tags, hover preview, click playback, loop, and auto-stop.

Features
YouTube video support
Self-hosted video support
Custom video thumbnail
Elementor Dynamic Tags support for video URLs
Elementor Dynamic Tags support for thumbnails
Short muted video preview on hover
Custom play button over the preview
Full video playback on click
Custom stop button during full playback
Auto-stop other duplicate widget videos when a new widget starts playing
Video loop option
YouTube related-video reduction using rel=0
Responsive aspect ratio control
Border radius styling control
Native video controls hidden for a cleaner design
Requirements
WordPress
Elementor
Elementor Pro is required for Elementor Dynamic Tags such as ACF fields
ACF or another custom field plugin is optional
Installation
Download or clone this repository.

Upload the bddex-video-widget folder to:

wp-content/plugins/
In WordPress Admin, go to Plugins.

Activate BDDEX Elementor Video Widget.

Open a page with Elementor.

Search for the widget named BDDEX Video.

You can also install the generated bddex-video-widget.zip file from Plugins > Add New > Upload Plugin.

Elementor Controls
Video
Video Source: Choose YouTube or Self Hosted.
YouTube URL: Add a YouTube URL manually or with Dynamic Tags.
Self Hosted Video URL: Add a direct video URL manually or with Dynamic Tags.
Self Hosted Video File: Choose a video file from the media library.
Video Thumbnail: Choose a thumbnail image manually or with Dynamic Tags.
Preview on Hover: Enable or disable muted hover preview.
Hover Preview Time: Set how long the hover preview should play.
Full Video on Click: Enable or disable full playback on click.
Loop Video: Loop the video.
No Suggested Videos: Adds YouTube rel=0 to reduce unrelated suggestions.
Style
Aspect Ratio: Choose 16:9, 4:3, 1:1, or 9:16.
Border Radius: Adjust widget corner radius.
Dynamic Tags
The widget supports Elementor Dynamic Tags for:

YouTube URL
Self-hosted video URL
Self-hosted video file
Thumbnail image
For ACF video links, use an ACF field type such as URL or Text, then select it from the Dynamic Tags picker in Elementor. If the ACF option does not appear, confirm that Elementor Pro is active and that the field is available for the current post/template context.

Playback Behavior
Hovering over the thumbnail starts a short muted preview.
The play button remains visible during hover preview.
Clicking the widget starts full video playback.
When full playback starts, other BDDEX video widgets on the same page automatically stop.
During full playback, a stop button appears in the top-right corner.
Clicking stop returns the widget to the thumbnail state.
Moving the mouse out during hover preview stops the preview and restores the thumbnail.
Notes
YouTube no longer allows completely disabling all suggested videos. The widget uses rel=0, which limits suggested videos to the same YouTube channel.

Browser autoplay rules require hover previews to be muted. Full playback is started from a user click.

File Structure
bddex-video-widget/
  assets/
    css/
      bddex-video-widget.css
    js/
      bddex-video-widget.js
  includes/
    class-bddex-elementor-video-widget.php
  bddex-video-widget.php
Version
Current version: 1.0.8
