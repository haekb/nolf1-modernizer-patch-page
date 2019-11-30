---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
{::options parse_block_html="true" /}
<div class="content-block">
{::options parse_block_html="false" /}
The NOLF modernization patch fixes performance issues, and attempts to adapt the original classic for larger resolutions. 

## Key Changes

- Fixes slowdown with some UI elements (such as looking down scope, or picking items up)
- HUD scaling options for most HUD elements
- Replaced mouse input code for a more responsive experience
- Optional framerate cap to 60fps
- Optional 4:3 mode for cutscenes
- New Jukebox menu in Options

## Latest Patch

- Added `NoRawInput` to disable mouse raw input
- Fixed missing continue button on mission summary screen
- Improved loading screen time (...that I broke, oops!)
- Fixed some invisible impassible geometry.
- Added a experimental developer console, can be toggled on/off with tilde. (`~`)
- Fixed a crash in the weapons hotkey screen.

## Installation

Extract the archive file over your NOLF directory. 

Then in the launcher, go to `Advanced` -> `Customize` and add the Modernizer.rez file.

Don't forget to check "Always load these rez files"!

## Support

Please note this is an unofficial patch, it's NOT developed by Monolith Interactive

## Download

You can download it on [itch.io](https://haekb.itch.io/nolf-modernizer)!

{::options parse_block_html="true" /}
</div>
<div class="screenshot-block">
<h2 id="screenshots">Screenshots</h2>
{% include screenshot_loop.html %}
</div>
{::options parse_block_html="false" /}
