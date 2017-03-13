# Statamic Facebook Embed Plugin

**NOTE: Tested on Statamic 1.x only. This plugin is no longer under development. If it still has any value, please feel free to fork and take over.**

This plugin allows you to quickly & easily embed public Facebook Posts into [Statamic](http://statamic.com)-powered websites.

You can [see it in action](http://andreademers.com/statamic-facebook-embed-plugin) on my personal site, andreademers.com.

To learn more, check out the Facebook developers [Embedded Posts documentation](https://developers.facebook.com/docs/plugins/embedded-posts/).

## Installation

1. Download the files, and copy them to `/_add-ons/facebook_embed`.
2. Make sure that the folder name is `facebook_embed`.

## Usage

### Tag
    
    {{ facebook_embed:post }}

### Parameter

`url` (required)

This is the URL of the public Facebook Post you wish to embed.

For example: `https://www.facebook.com/andrea.demers/posts/10152163567674815`

### Example

    {{ facebook_embed:post url="https://www.facebook.com/andrea.demers/posts/10152163567674815" }}
