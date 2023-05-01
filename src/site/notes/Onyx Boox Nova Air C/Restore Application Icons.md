---
{"dg-publish":true,"permalink":"/onyx-boox-nova-air-c/restore-application-icons/","created":"2023-04-27T22:09:14.468-05:00","updated":"2023-04-28T10:12:32.113-05:00"}
---


# Restore Application Icons on Onyx Boox Nova Air C

_[[Epistemic status\|Epistemic status]]_: This worked for me on my own device.
_[[Epistemic effort\|Epistemic effort]]_: I asked support, they recommended this solution. I wrote it up, along with the steps I took afterwards to get back to where I wanted to be.

I recently reset my [[Onyx Boox Nova Air C\|Onyx Boox Nova Air C]] to factory defaults. I use [[calibre\|calibre]] to manage all my ebooks and I think I had a bad USB-C cable that kept dropping connection between my laptop and my Boox, which in turn seemed to leave [[calibre\|calibre]] confused about what files were actually on my device. I also seemed to be accumulating additional files that were eating up storage. So I did the reset, and copied everything back over fresh. As a bonus, I was able to put more books on and the total collection is still using less space than before I reset.

However, I did run into a problem. I use [[Moon+ Reader\|Moon+ Reader]] as my default reader, because it automatically syncs my highlights to [[Readwise\|Readwise]] which the built-in reader does not. I also have a [[Libby\|Libby]] account to borrow books from my library. After the reset, I re-installed both apps from the Google Play Store. Play said they were installed, and I could select Moon+ as the default, but neither Moon+ nor Libby showed up in my apps view - that view just stubbornly stayed showing the default apps.

The solution was to clear the storage for the ContentBrowser app. To do that, I went to Apps > Upper Right List Icon Menu > App Management, then chose App Info. I chose ContentBrowser > Storage and Cache and clicked the Clear Storage button.

When I went back out to the Apps view, [[Libby\|Libby]] and [[Moon+ Reader\|Moon+ Reader]] both showed up! Success!

Then I went back to the library view. I only keep a few books at a time in the main folder because the cover display doesn't track progress when I use Moon+ and so can't sort the active books to the beginning. The rest are hidden away. Moon+, for reasons I haven't yet figured out, makes a duplicate copy of every book I open (anyone know how to stop this??? This is almost enough to make me switch back to [[KO Reader\|KO Reader]] which also does Readwise, but there was some reason, which I now forget, why I went with Moon+ over KO). When I went to library view, all my covers were gone and the books were back to listing by filename instead of title, and I had duplicate entries for the books - one for the Moon+ copy and one for the main copy. Selecting Upper Right List Icon menu > Scan Covers brought back all the book covers and the titles. I had to change a few settings (like the Sort option to sort Alphabetically by title).

Using [[calibre\|calibre]], I was able to delete the file from the MoonReader attachments folder which removed them from the Library view. Reopening them in Moon+ made a new duplicate, but it did remember my position.  Really wish I could make Moon+ not make copies though...


