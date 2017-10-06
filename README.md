# fiction_novel

Everything I have learned for formatting a novel with LaTeX.

## Prequiste

Install latest texlive package (this will include all add on packages like memoir, plus much more.) the texlive package that is included with Ubuntu is old and does not support everything, it is highly recommended to download the full source from https://www.tug.org/texlive/ and install manually.  

I prefer TeXWorks as my compiler of choice, just update the path to reflect the local install of texlive. Edit -> Preferences -> Typesetting -> "Paths for TeX and related Programs" -> add


## Notes

main.tex - everything for setup and formatting should go in this document. This includes scripts, macros, includes, font selection, header/footer formatting, etc.

main.tex is the skeleton and brain of your document, with the content in sepearte sub documents that will make it much easier for organizing and once you get used to the syntax much clearer where things should be changed and how that effects the document as a whole.

frontmatter.tex - This includes title page, dedication, copywrite info, and anything that should proceed the novel. With all of these files it is important to visualize and understand how the viewere will see each page (front page, back page) in relation ot where content goes. I recommend comparing with other books in your home to see which pages are commonly included.

prologue.tex and chapter-one.tex - these files will hold your novel seperated by chapter. I've set them up to auto fill with Lorem Ipsum. which you can see in the included main.pdf

backmatter.tex - this inculdes any extra information at the end of your book.

main.pdf - this is the result of all the above files complied together and published to a pdf.


Please just use this as a framework and reference, I am still very new to LaTeX so there could be many things that I am not doing entirely correctly.
