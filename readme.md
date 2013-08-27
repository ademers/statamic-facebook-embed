# Statamic Facebook Embed Plugin

This plugin allows you to quickly & easily embed public Facebook Posts.

To learn more, check out the Facebook developers [Embedded Posts documentation](https://developers.facebook.com/docs/plugins/embedded-posts/).

## Installation

1. Download the zip file (or clone via git) and unzip it or clone the repo into `/_add-ons/`.
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
