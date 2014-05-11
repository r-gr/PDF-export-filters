# OS X Preview.app PDF Export Filters

The built in filter for reducing the file size of a PDF reduces the quality far
too much, making them fuzzy and unreadable.

These are some additional quartz filters for OS X which reduce the file size of
PDF files with different qualities. I use them for compressing scanned
documents.

### Usage

They can be found in Preview.app, `File -> Export...`

- `Compress (Best)` is the equivalent of 300dpi at A4 size.
- `Compress (Better)` is 144dpi at A4 size.
- `Compress (Good)` is 72dpi at A4 size.

### Installation

I put them in `/System/Library/Filters` where the others are found. They may be overwritten here when updating - I don't know.

You could create a folder `/Library/Filters` and put them in there or `~/Library/Filters`. I haven't tried either but I assume they will work.


### Attributions

Original author [here](http://hints.macworld.com/article.php?story=20120629091437274).
