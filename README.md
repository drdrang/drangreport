The `drangreport.sty` file is a redacted version of the LaTeX style file for reports I discussed in these two blog posts ([first][1] and [second][2]). It includes provisions for:

* Plates, as distinct from figures.
* A title page.
* A digitized signature.
* A variety of font combinations.
* The sort of paragraph spacing, margins, and heading styles I prefer.

Most of the font combinations use the Mathematica fonts. You'll need both [these virtual font files][3] and the [version 4.1 PostScript files][4]. To get the fonts on a non-Windows machine, use the link at the bottom of the page to download the .exe file and unzip "by hand."

    unzip MathFonts_Type1_42.exe

You'll need to know a fair amount about how a TeX system uses fonts to install these correctly and get your system to know they're there.

The `drangsymbols.sty` file is a set of convenient commands for units and small fractions.


[1]: http://www.leancrew.com/all-this/2011/04/text-files-and-me-part-3/
[2]: http://www.leancrew.com/all-this/2011/04/text-files-and-me-part-3-5/
[3]: http://library.wolfram.com/infocenter/MathSource/3200/
[4]: http://support.wolfram.com/technotes/fonts/windows/latestfonts.html
