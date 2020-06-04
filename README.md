# resume-template

*A simple Jekyll + GitHub Pages powered resume template.*

# Running locally

To test locally, run the following in your terminal:

1. Clone repo locally
1. `bundle install`
2. `bundle exec jekyll serve`
3. Open your browser to `localhost:4000`
4. Spell check `lynx -dump http://localhost:4000 | grep -v -E 'http|tel:|mailto' | aspell --add-extra-dicts=./resume.pws list`

# Generating new PDF

1. Open FireFox
2. Browse to `localhost:4000`
3. Command-P
4. Change Header and Footers to `blank`
5. Change right Footer to `Page # of #`
6. Change left Footer to `Title`
7. Save as PDF
8. Add PDF file to this repository at `./images/resume.pdf`
