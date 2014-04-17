# NICAR15 - The Great Scrape-Off

## The general idea

Given a set of data, one team (black hats) is in charge of presenting it in a human-readable but hard-to-scrape form.  The other team must scrape it within a certain time limit (white hats).

## Tentative guidelines

The method for constructing the page has to be deterministic.  You must write a script (or scripts) that, given a data file, produces the same page each time it's run.  Basically, no random numbers.

As the test of human readability, a designated user must be able to copy and paste the dataset, or an arbitrary subset of it, into a spreadsheet in a reasonable amount of time.  So, e.g., no PDFs, no text in images.

## Open questions

Should hosting be static, or is requiring logins, obfuscating by user-agent, etc. fair game?  If dynamic hosting is OK we would need some boundaries for this.

Should there be multiple scraping teams competing against each other for time?

Should we also make the data format really screwy to further handicap the black hat team?
