# Attila - Dark

Dark theme for [Ghost](http://github.com/tryghost/ghost/) based on [Attila theme](https://github.com/zutrinken/attila) by [zutrinken](http://attila.zutrinken.com/).

## Demo

I'm unable to host a dedicated demo at the moment, but you can see the theme in action on my personal blog [loglevel-blog.com](https://loglevel-blog.com). Also take a look at the demo of the original light theme "Attila" by zutrinken [here](https://attila.zutrinken.com/).

## Screenshots

<table>
<tr>
<td valign="top">
<img src="https://raw.githubusercontent.com/kuper-adrian/attila-dark/master/src/screenshot-desktop.PNG" />
</td>
<td valign="top">
<img src="https://raw.githubusercontent.com/kuper-adrian/attila-dark/master/src/screenshot-mobile.PNG" />
</td>
</tr>
</table>

## Features

* It's dark!
* Responsive layout
* Navigation support
* Paralax cover images for posts, author archives and blog
* Author informations for posts and author archives
* Featured posts
* Reading progress for posts
* Automatic code syntax highlight and line numbers based on [Dracula Theme](https://draculatheme.com/highlightjs/)
* Disqus support
* Subscribers support
* Sharing buttons

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus = 'YOUR_DISQUS_SHORTNAME';</script>` to your blog header.

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt dependencies:

	npm install

Build Grunt project:

	grunt build

## Copyright & License

Copyright (C) 2015-2018 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/attila/blob/master/LICENSE).
