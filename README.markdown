Makefile based pdf presentation for handouts and slides, cloned into repository from [lmullen's gist](https://gist.github.com/lmullen/c3d4c7883f081ed8692a)


Files to create slides and handouts from the same Markdown files using
Pandoc and a custom Beamer template. Lots of ideas borrowed from [Karl
Browman's post][]. The Makefile will turn any `*.md` in the directory 
into PDF slides (`*.md.slides.pdf`) and PDF slides with notes for 
speaking or a handout (`*.md.handout.pdf`). The file `default.beamer` 
belongs in `~/.pandoc/templates`. Use the metadata in the YAML header of 
the Markdown file to control various options. To get the handout to look 
right, use the `\note{}` macro after each slide in the Markdown file.

  [Karl Browman's post]: http://kbroman.wordpress.com/2013/10/07/better-looking-latexbeamer-slides/
