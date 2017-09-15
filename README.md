# katch
This repository is used for high-level design artifacts for the Test Framework for the Katch healthcare websites.

Description of repository folders:

Spreadsheets:
There is one main sheet - this is a sheet showing all sites and elements on pages. The top row indicates the “names” of each site.  Always look at the latest one – this is done this for historical purposes rather than writing over the sheet with changes.
Each row of the sheet contains one site screen “element”.  An “x” in a column denotes presence of that element on a specific site. 

Images:
This is a collection of screenshots of various “pieces” of  site screens.  Each of these screenshots maps to “elements” in the rows of the spreadsheet mentioned above.  In some cases, there may be more than one screenshot which maps to an element.   In some cases the names aren't exactly matching the spreadsheet row names, but - but they are close enough to determine what is meant.

Documents: 
PDF files: some of these show examples of differences in “controls” and formatting for major site elements.  In the future a separate folder will be created for this purpose. showing an example of some big differences
PNG files: Currently used for diagrams of templates which will be used as design plan to create automation framework.  Each element will represent a placeholder fo rthe name of a specific screen element to be used and in addition presence or absence of the element will map to presence or absence of element on a specific site. Also, a scheme should be implemented which will allow major elements of a site to be encoded into the framework including: text font, txt size, site colors, etc.
Also, minor templates will be included which further refine use of the major templates.
