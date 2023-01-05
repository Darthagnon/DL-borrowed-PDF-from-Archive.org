# DL borrowed PDF from Archive.org
Download borrowed PDFs from Archive.org, including 1-hour loans.

[How to download books from Archive org and how to remove d r m protection of the downloaded book using Calibre](https://old.reddit.com/r/Piracy/comments/l9exis/how_to_download_books_from_archive_org_and_how_to/) ([Archive.today](https://archive.today/Slgse)) was a tutorial detailing how to download books from Archive.org, which offers DRMed PDF downloads of many books with 14 day time limits, or no-download-read-online of 1 hour time limit books.

## YouTube video

### [Archive org bookmarklet](https://www.youtube.com/watch?v=7drDaWWIwR0)
*03 Jan 2022, uploaded after several people contacted me, asking for help downloading books, as the script is finicky*

You can download any book, including 1-hour borrow books, from Archive.org. Here's a short example using my bookmarklet.

Here's the bookmarklet code:
```js
javascript:window.location=window.location.protocol+'//'+window.location.hostname+'/services/loans/loan/?action=media_url&identifier='+window.location.pathname.split("/").pop()+'&format=pdf&redirect=1'
```

Here's the Reddit thread:
https://old.reddit.com/r/Piracy/comments/l9exis/how_to_download_books_from_archive_org_and_how_to/gxmln00/


## Reddit post
*10 May 2021 17:57:42 GMT+0100 by u/Darth_Agnon*

I made a bookmarklet to help simplify the process:

1. Create account with Archive.org

2. Install [Adobe Digital Editions](https://www.adobe.com/solutions/ebook/digital-editions/download.html) and authorise your PC (Adobe account optional)

3. Borrow the book you want.

4. If it can be borrowed for 14 days, then you're fine - click on the "Download PDF" link, you'll get a link file that opens with Adobe Digital Editions to download your PDF (with DRM).

5. If it can be borrowed for only 1 hour, then no PDF download options are available. Solution: Make a new bookmark in your bookmarks bar with the following code as the URL:

### DL borrowed PDF from Archive.org

```
javascript:window.location=window.location.protocol+'//'+window.location.hostname+'/services/loans/loan/?action=media_url&identifier='+window.location.pathname.split("/").pop()+'&format=pdf&redirect=1'
```

Now go and borrow your book, click the bookmarklet, and a linkfile for Adobe Digital Editions to download the PDF should download (works with 99% of the books I tried).

Use Calibre and DeDRM Tools to liberate the PDFs and read them at your leisure.

Edit: fixed the bookmarklet code, should work now.
