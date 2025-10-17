# LaTeX Template for theses
### Chair of Information Systems III 
Dear students, below you will find the LaTeX template for academic work at the Chair of Information Systems III.

Please note that you can change the template as you wish as long as you adhere to the formalities of the professorship.

If there are any errors in the template, please point them out to us.

Best regards
Your Professorship Team.

### Word count
We are using word count to make different formats (e.g. Word) better comparable. For this we are counting the words in these document.

The current LaTeX version supports word counting, using LuaLaTeX.

### Prerequisites
Two settings must be made for the template to work properly.
- Instead of pdflatex use lualatex
- Use biber instead of bibtex

### Additional Information
We are using the package _glossaries_ to make the creation of abbreviations simpler. Be aware that you have to run makeglossarieslite to update the glossarie. 

### Citation
In text cite use the command `\textcite{bibtexcode}`. And with brackets you should use `\parencite{bibtexcode}`.

### Issues
One person reported compiling the document with the word counter active created issues. In this version everything works, but you always can just comment out the wordcount.

### Contact persons
Managed by: Dr. Pascal Heßler [Pascal.Hessler@kit.edu](mailto:Pascal.Hessler@kit.edu).
