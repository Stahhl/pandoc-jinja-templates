pandoc -s --number-sections --template=template.tex --table-of-contents -V documentclass=report doc1.md doc2.md -o book.pdf

pandoc -s -N --template=template.tex doc1.md -o doc.pdf