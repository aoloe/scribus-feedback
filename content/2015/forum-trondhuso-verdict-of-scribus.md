For two days now my oldest daughter (9 years old) has been playing around with Scribus. We have created a small "newspaper" and it has been fun for her to create this four page publication. The version we've used (until we found there was a way to upgrade to 1.4.5 under Ubuntu 14.04) was 1.4.2 (I think, it's the one in the repository) has some clear bugs.
1) When writing in the text area, the editor like to keep the style to Fixed Linespacing and not to Automatic line spacing. Even when we changed it, it stuck to (for instance 19pt and 15pt line spacing). We ended up just write the articles in Writer and copy/paste it into the text frame. Then we marked all the text and re-formated it. I could see that the cursor still wanted the following style to be in a different size and different line spacing. 
I have tested it again, and I see that scribus is insisting that the following style/format shall be (currently Arial 12pt + fixed linespacing set to 15pt).

2) Printing. Today the paper was done. Mom was interviewed and photographed and so my daughter wanted to print the paper. In the printer window/box coming up there are a lot of choices and I set most of it to what I hoped our Brother printer would accept. It's not a postscript-printer.
When printing we got an error. After the upgrade the error is gone, but the page is now blank. 

I have now installed 1.4.5 on my computer as well, and I to get the blank page when trying to print a page with less dummy text and no pictures.

Searching for Scribus and printing I see that it is a common problem and that most people "fix" this by exporting the document into PDF and print it from Document Viewer or Acrobat Reader. Some has found a program called bookbinder (java-program so can run on any platform).

After this experience I cannot really say that Scribus is a mature program. I'd love to use it for some project, but when key features like the ones described above does not work or seem buggy, I cannot use it for anything. And it seems kind of dumb to create a document (with spreads for instance) in Scribus. Export it, then merge it again in another program (like bookbinder or Gimp or even InDesign).

I read on the mailinglist some suggestions for Google Summer of Code. None of the suggestions was related to the above findings. If I could suggest one low hanging fruit for GSOC: 
Fix printing

If you want another one:
Correct the bug in the text frame editor.
