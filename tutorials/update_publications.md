## Template
Copy the following template to "pages/publications.md"

```
<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="https://groups.csail.mit.edu/cgs/pubs/PDF_FILENAME">
        TITLE
        </a></b></p>
        <p><font size="2">
        ABSTRACT
        </font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/FIGURE_FILE" alt="">
        <p> <font size="2">
        AUTHOR_LIST
        <br> 
        CITATION
        </font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

```

## Update the details

### Text

Replace the following keywords in the template with the actual information from the new paper:

* TITLE:  title
* ABSTRACT: abstract
* AUTHOR_LIST:  the authors 
* CITATION:  journal name (make it italic by `<i>JOURNAL NAME</i>`), volume, chapter, doi, and other related information 

### Figure

* Save an impressive figure from the paper to "images" folder and name it in a nice way (e.g. `Author_Year_Journal.png`)

* Update "FIGURE_FILE" in the template with the image name above.

### Hyperlink to PDF file

* Save the PDF version of the paper to "pdfs" folder and name it in a nice way. (e.g. `Author_Year_Journal.pdf`)

* Replace "PDF_FILENAME" in the template with the file name above.

* Open a terminal, run the following to upload the PDF files to our cluster:

	```
	cd ~/gifford-lab.github.io/pdfs
	scp * lindalynch@sox2.csail.mit.edu:/afs/csail.mit.edu/group/cgs/www/data/pubs/
	```

