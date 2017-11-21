# RegExs
Reg Ex patterns that I have found useful

## Comma Finder
RegEx to find the commas for a comma seperated file - ignores commans that are in a set of quotes. 

Bad:
(?!\B["'][^"']*),(?![^"']*["']\B)

Good:
(?!\B"[^"]*),(?![^"]*"\B)
