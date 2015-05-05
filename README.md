# FA to Fontello

Personal project in which I'll use some JavaScript to automate as much as I can the import of Font Awesome 4.3.0 into Fontello.

## What about the existing 4.1.0?

Font Awesome version 4.1.0 on Fontello exists but I do not know if it is possible to update it to version 4.3.0.

I decided to import it all from scratch but copy over the keywords for matching elements.

## What about alias?

I do not know how we are supposed to deal with aliases in Fontello.

I decided to omit the aliases for now, then I'll see we could bring them on board.

## Starting point

The starting point will be made from an exported section of Font Awesome's `_variables.scss` file...