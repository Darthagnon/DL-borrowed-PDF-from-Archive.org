# DL borrowed PDF from Archive.org
Bookmarklet to download borrowed PDFs from Archive.org, including 1-hour loans.

## Bookmarklet: [DL borrowed PDF from Archive.org](javascript:window.location=window.location.protocol+'//'+window.location.hostname+'/services/loans/loan/?action=media_url&identifier='+window.location.pathname.split("/")[2]+'&format=pdf&redirect=1';)

Drag the above link to your web browser's bookmarks bar...

... or make a new bookmark and replace the URL field with the following script:

```js
javascript: window.location = window.location.protocol + '//' + window.location.hostname + '/services/loans/loan/?action=media_url&identifier=' + window.location.pathname.split("/")[2] + '&format=pdf&redirect=1';
```

## How to download books from Archive.org

[Here's a YouTube tutorial](https://www.youtube.com/watch?v=7drDaWWIwR0) for the following process:

1. Create account with [Archive.org](https://archive.org/)

2. Install [Adobe Digital Editions](https://www.adobe.com/solutions/ebook/digital-editions/download.html) and authorise your PC (Adobe account optional).

3. Borrow the book you want.

  - If it can be borrowed for **14 days**, then you're fine - click on the "Download PDF" link and you'll get a link file `URLLink.acsm` that opens with Adobe Digital Editions to download your PDF (with DRM).

  -  If it can be borrowed for **only 1 hour**, then no PDF download options are available.
  
4. **Solution:** Add the bookmarklet to your browser:
### Draggable link: [DL borrowed PDF from Archive.org](javascript:window.location=window.location.protocol+'//'+window.location.hostname+'/services/loans/loan/?action=media_url&identifier='+window.location.pathname.split("/")[2]+'&format=pdf&redirect=1';)
Code:
```
javascript: window.location = window.location.protocol + '//' + window.location.hostname + '/services/loans/loan/?action=media_url&identifier=' + window.location.pathname.split("/")[2] + '&format=pdf&redirect=1';
```
5. Now go and borrow your book, **but do not browse any pages** (or the bookmarklet won't work).

6. Click the bookmarklet, and the `URLLink.acsm` linkfile for Adobe Digital Editions to download your 1-hour loan PDF should download (works with 99% of the books I tried). 

7. In Adobe Digital Editions, right-click on the book >> `Show file in Explorer` >> Drag'n'drop the PDF into Calibre. Use Calibre [v4.23](https://download.calibre-ebook.com/4.23.0/) or [v5.44](https://download.calibre-ebook.com/5.44.0/) with [noDRM's updated fork of the DeDRM Tools plugin](https://github.com/noDRM/DeDRM_tools/releases) installed to liberate the PDFs and read them at your leisure.


## History

### 02 Jan 2023 - Bookmarklet fixed via Reddit PM
[u/elite_minority-616](https://old.reddit.com/user/elite_minority-616) contacted me via Reddit PM with an update to the bookmarklet that fixed the bug where you couldn't browse pages in the book before downloading, a constant source of grief for users.

### 03 Jan 2022 - YouTube tutorial [Archive org bookmarklet](https://www.youtube.com/watch?v=7drDaWWIwR0) uploaded
Several people contacted me asking for help downloading books, as the bookmarklet script is finicky

### 10 May 2021 - Bookmarklet released
Bookmarklet code written to automate the download process of 1-hour loan books from Archive.org [Reddit post](https://old.reddit.com/r/Piracy/comments/l9exis/how_to_download_books_from_archive_org_and_how_to/gxmln00/) (last edited 10 May 2021 17:57:42 GMT+0100 by [u/Darth_Agnon](https://www.reddit.com/user/Darth_Agnon))

### 31 Jan 2021 - Tutorial written
[How to download books from Archive org and how to remove d r m protection of the downloaded book using Calibre](https://old.reddit.com/r/Piracy/comments/l9exis/how_to_download_books_from_archive_org_and_how_to/) ([Archive.today](https://archive.today/Slgse)) tutorial written by [u/silentshot546](https://old.reddit.com/user/silentshot546), covering the workarounds used to download 1-hour loan books (last edited 18 May 2021)
