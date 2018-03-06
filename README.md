# Preprint template
LaTeX template for preprint formatting. LaTeX does have a relatively steep learning curve but once you get the hang of it it'll be amazing. 

Feel free to edit according to your preferences. I give zero promise for correct typesetting or the absence of errors, but it should not give much troubles. I've used a memoir class document and I'm aware that this is may not be the right class for a scientific paper. But for me this gives a bit more freedom in typesetting (i.e. I've used this template to typeset my Phd thesis, requiring the possibility to have multiple chapters). 

The attached .tex file contains the minimum (maybe not the bare minimum) amount of packages, so in case you want to have more freedom add more packages to your needs. Doing so gives possibility to include page-spanning tables, for example, or have parts of the document printed in landscape format. 

## How to use:
1. Pretty simple: copy-paste each paragraph under the right header, replacing the \lipsum operator. Rename headers to your needs
2. Place figures in subfolder named 'Figures'. Rename to something concise, ie. 'Fig1_expression'. pdf, png, jpeg files work fine
3. Let your LateX editor do the job for you
4. Upload to BioRixv

Please note that copy-pasting from MS Word to Tex will remove all formatting. The easiest to do is to replace formatted words with the right operator:
1. Go to advanced Find & Replace in MS Word
2. Under 'Find what': select advanced options; select Format: italics
3. Under 'Replace with' type: \textit{^&}
4. Replace All
5. Repeat for all other necessary formatting you've used:

* For *italics*: \textit{^&}
* For **bold**: \textbf{^&}
* For underline: \underline{^&}

Refererring to figures and tables; use operon: ~\ref{fig1_map}. 'fig1_map' refers to assigned figure/table label. 

## Some tips/remarks:
* To typeset my documents I use PDFlatex under Texmaker on Mac. Other tex typesetting software should do the job equally well 
* There's a wealth of information available on [tex.stackexchange](https://tex.stackexchange.com/)
* For packages just Google around. There's millions
* For easy table typesetting I generally use [this page](https://www.tablesgenerator.com/) and copy-paste the output
* You may decide to use Bibtex for references. Gives you more freedom but may require a bit more work. In this template I've just copy-pasted them as text from MS Word.
* You can easily remove the \multicols operator just before the intro to have everything in one column. 
* By removing the \footnotesize operator just before the start of the M&M section you'll have all text in the same fontsize. 
* Current font is BT Charter. More fonts available via [TUG](http://www.tug.dk/FontCatalogue/)



Nb. The example figures are generated using own my own Strava data and [Marcus Volz](https://github.com/marcusvolz/strava)'s amazing R code. 
