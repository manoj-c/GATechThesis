# Georgia Tech - Thesis Template

*Georgia Institute of Technology*

*Graduate Student Government Association*

*Department of Graduate Studies*

*2016*

This is a thesis template that meets the official institute formatting requirements from the Georgia Institute of Technology.
While no official support is provided, this template was developed by Georgia Tech's Graduate Student Government Association (Grad SGA),
in cooperation with the Department of Graduate Students. Technical questions regarding the thesis template can be directed
to Graduate SGA, and formatting questions to the Department of Graduate Studies.

#Usage of the Template

The default and most common LaTeX packages were utilized to enable many of the features in this theme.
As such, modifications of the template is easily accomplished by leveraging the capabilities of the utilized packages.

However, the template is designed to require minimal modification for a standard PhD/Masters thesis.
By following these steps, the blank template can be customized to a specific individual person and thesis topic.
Note that the percent sign "%", is the comment character for LaTeX, and any text following this symbol will
not be read by the LaTeX compiler. Including in the template are many such comments containing
instructions and relevant context, so be sure to read these as needed.

1. Open the "titePage.tex" file, and input your information in the designated section.
2. Open the "approvalPage.tex" file, and input your information in the designated section.
3. Open the "epigraph.tex", "dedication.tex", "acknowledgments.tex", "summary.tex", and "vita.tex" pages and enter your information.
4. Open the "references.tex" file, and input your citations, in BiBTeX format.

After these steps are complete, the main content of the thesis can be entered into the various "chapter<#>.tex" files, along with any appendices in the "appendix.tex" file.

To compile the template, using your preferred TeX editor, run the following commands in sequence:

1. pdflatex
2. bibtex
3. pdflatex
4. pdflatex

Note that occasionally this sequence will need to be run twice in order to correctly update the Table of Contents.
In the popular TeX editor TeXstudio, the default preview and compile options appear to correctly compile the template.

An excellent resource for general LaTeX questions can be found in this document: https://www.ctan.org/tex-archive/info/lshort/english/?lang=en.
