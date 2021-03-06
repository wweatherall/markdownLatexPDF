# markdownLatexPDF

The goal of this project is to smooth some of the rough edges of writing academic papers through the use of multimarkdown and latex and smooth some of the rough edges of dealing with those.  

1. Install LaTeX and BibTeX:

   MacTeX (a latex package with everything you could ever need) is available here: http://www.tug.org/mactex/
   
   Or use ```'brew install mactex'``` in the terminal if you have home brew installed

2. Install multimarkdown 5, available here: https://github.com/fletcher/MultiMarkdown-5/releases/download/5.4.0/MultiMarkdown-Mac-5.4.0.dmg

   A mmd user's guide is available here: https://fletcher.github.io/MultiMarkdown-4/MMD_Users_Guide.pdf

3. Get the texmf.zip file from here and install it in your library folder. There's a script that may help you with that in the folder itself. This is where you'll find some basic templates to get you started.

4. Optional: Download the multimarkdown template files: https://github.com/fletcher/peg-multimarkdown-latex-support Fletcher T. Penny (the creator of MMD) has much more elaborate ones for you if you want them. 

5. Run the folder moving script while the folder you download from here is in your downloads folder or do it manually. 

   (If you use the script it will give you the option to create a shortcut on your desktop. This is useful while you calibrate your .tex template files to your liking)

6. Install the service

# more on the template files

The template files go into your hidden library directory under the home folder. To view it press <kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>.</kbd> while in your home folder. 

Folder Structure:

<img width="415" alt="FolderLayout" src="https://user-images.githubusercontent.com/84057259/119235024-b9abed80-baed-11eb-94b2-970b3a56c860.png">

The .tex files themselves will go into your mmd folder. The .bib file goes in the bib folder. If you make any .cls files, they can go in the latex folder. The .bst file (bibliography style) goes in the bst folder. If you want more styles and templates, you can find almost anything at https://ctan.org/

