# Alfred to Readwise
This [Alfred](https://www.alfredapp.com) workflow saves a highlight to [Readwise](https://readwise.io) with the URL of the frontmost browser window as the source.

**[Download workflow](https://github.com/danphilibin/alfred-to-readwise/blob/00d1df6e55533fd973a4c7406e7470ab9e8960a7/Alfred%20to%20Readwise.alfredworkflow)**

## Installation

1. Sign up for a [Readwise](https://readwise.io) account
2. [Get your API key here](https://readwise.io/access_token)
3. Copy & paste your API key into the `api_key` workflow variable
4. Done!

## Usage

Type "rw" (or set your own custom trigger) and paste the text you want to save as a highlight. The extension will grab the URL from your frontmost browser window, save the highlight to Readwise, and post a notification when finished.

You can also type "rw review" to open your Daily Review screen.

Safari and Google Chrome are supported.

## Acknowledgements
- The [Copy URL](https://github.com/fallroot/copy-url-for-alfred) workflow by fallroot
- [This gist](https://gist.github.com/vitorgalvao/5392178) for getting the title and URL from your browser
