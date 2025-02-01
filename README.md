# Algorithms and Data Structures Cheat Sheet

A comprehensive LaTeX-based cheat sheet covering fundamental algorithms and data structures concepts, including:
- Computational Complexity and Big-O Notation
- Sorting Algorithms
- Binary Search Trees
- Red-Black Trees
- Graph Algorithms
- And more...

## Latest Version
<object data="FTP_Algorithms_HS24_CheatSheet.pdf" type="application/pdf" width="100%" height="600px">
    <embed src="FTP_Algorithms_HS24_CheatSheet.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: 
        <a href="FTP_Algorithms_HS24_CheatSheet.pdf">Download PDF</a>.</p>
    </embed>
</object>

You can also directly [download the latest version](FTP_Algorithms_HS24_CheatSheet.pdf) of the cheat sheet.

## Structure
- `main.tex`: Main document that includes all other files
- `weeks1-7.tex`: Theoretical content for weeks 1-7
- `weeks8-14.tex`: Theoretical content for weeks 8-14
- `exercises.tex`, `exercises-part2.tex`, `exercises-part3.tex`: Practice exercises with detailed solutions

## Building the Document
1. Ensure you have a LaTeX distribution installed (e.g., MiKTeX, TeX Live)
2. Compile using pdflatex:
   ```bash
   pdflatex -jobname=FTP_Algorithms_HS24_CheatSheet main.tex
   pdflatex -jobname=FTP_Algorithms_HS24_CheatSheet main.tex  # Run twice for proper TOC generation
   ```

## Contributing
Feel free to submit issues and enhancement requests!
