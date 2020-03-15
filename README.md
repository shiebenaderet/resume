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


# Todo


- update the header so that it gets added into the pdf
-- remove no-print from title-bar
-- add the following so the icons dont show up during print

<div class="title-bar-icons no-print">
{% include icon-links.html %}
</div>




- things to add to resume
-- New Palo Alto network design
-- offline testing environment
-- built up 6 scrum teams 



“I’m happy in my role, and while I’m open to new opportunities, wouldn’t be interested in moving for less than $X.”

don't name your price but instead make it clear that you're not actively looking to move but would be open to it if offered a better opportunity and then ask what salary the employer has in mind. It's a very reasonable opportunity to get them to show their hand first.


"that sounds like an interesting opportunity. I would be looking for $x to motivate me to leave my current role. How does that align with the budget for this role?"

