# RegExs
Reg Ex patterns that I have found useful

## Comma Finder
RegEx to find the commas or a comma seperator file - ignores commans that are in a set of quotes. 

(?!\B["'][^"']*),(?![^"']*["']\B)
