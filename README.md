# Mastodon CSS Tweaks
### *Quality-of-life & aesthetic improvements for Mastodon, through custom CSS*

<br />

Mastodon offers server administrators the ability to add custom CSS, and that provides a good opportunity to make some different design choices.

## Details

**The custom CSS in `custom.css` can make the following changes**:

* **Realigned Post Content**
  - Moves the left margin of the text to align with the username. Twitter takes a similar approach.
  - Media (whether it's images, cards for external links, or videos) still take up the full width.
  - Cards for external links have had their preview images shrunk, so that the titles align with the post text.
* **Prominent Privacy Indicators**
  - If the post's privacy is not public, make the indicator icon brighter. Locked & DM privacy states are a bright pink, while unlisted is still gray, but a bit brighter.
* **Different Avatar Image Shape**
  - Avatar photos are rounded - though not in a perfect circle. They're in more of a blob shape. It just looks more fun 😊
  
## Installation

Open your site settings (under `https://{{ your instance }}/admin/settings/appearance`), paste the contents in, and save. 


## Examples

These tweaks are currently running on [@chirpycora](https://github.com/chirpycora)'s personal Mastodon instance, https://mstr.cloud. Note that it uses a custom font, which (because of CSRF restrictions) requires additional work to implement, not yet documented here.
