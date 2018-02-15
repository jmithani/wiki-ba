# Gender Discrepencies in the Production of Wikipedia Biographical Articles

For my bachelor's thesis, I measured one aspect of subject matter based gender bias on Wikipedia. Wikipedia has a notability clause defining what makes someone 'worthy' of a Wikipedia entry. For my experiment, I compared men and women of the reasonably same notability to see if there were differences in the likelihood of them having their own biographical Wikipedia article.

I defined "objectively same notability" by parsing the corresponding authors from publications in the journal *Nature* from 2015 to ~2007. (Data from ealier was not available in a format usable for the experiment.) I then used the Genderize.io API to code first names as male or female. I queried Wikipedia using the wikpedia python package for articles whose title matched at least the last name of the author, and referenced "Nature."

Overall, men are more likely to have biographical Wikipedia pages than women, although the rates vary depending on how many citations they have. The most prominant disparities were between very junior or extremely senior scientists. 

This experiment is by no means complete. It is possible that a biographical page could have been created, but then deleted. All articles are not of the same quality.

There is much work to be done -- I'm excited.
