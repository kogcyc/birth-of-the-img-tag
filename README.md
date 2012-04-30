birthoftheimgtag
================

Marc Andreessen is the father of the <img> tag.  He is responsible for adding bitmaps to HTML.  Here is the email that Marc sent proposing the addition.

  	From: "Marc Andreessen" <marca@ncsa.uiuc.edu>
	Date: Thu, 25 Feb 93 21:09:02 -0800
	Subject: proposed new tag: IMG

	I'd like to propose a new, optional HTML tag:

	IMG

	Required argument is SRC="url".

	This names a bitmap or pixmap file for the browser to attempt to pull
	over the network and interpret as an image, to be embedded in the text
	at the point of the tag's occurrence.

	An example is:

	<IMG SRC="file://foobar.com/foo/bar/blargh.xbm">

	(There is no closing tag; this is just a standalone tag.)

	This tag can be embedded in an anchor like anything else; when that
	happens, it becomes an icon that's sensitive to activation just like a
	regular text anchor.

	Browsers should be afforded flexibility as to which image formats they
	support. Xbm and Xpm are good ones to support, for example. If a
	browser cannot interpret a given format, it can do whatever it wants
	instead (X Mosaic will pop up a default bitmap as a placeholder).

	This is required functionality for X Mosaic; we have this working, and
	we'll at least be using it internally. I'm certainly open to
	suggestions as to how this should be handled within HTML; if you have
	a better idea than what I'm presenting now, please let me know. I
	know this is hazy wrt image format, but I don't see an alternative
	than to just say ``let the browser do what it can'' and wait for the
	perfect solution to come along (MIME, someday, maybe).

	Let me know what you think.........

	Cheers,
	Marc
