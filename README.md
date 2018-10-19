# Futhark-language
Adds support for the language Futhark in Atom.

## Segmented scan
The snippet sgmscan inserts the code from weekly1 converted to handle i32. The complete code is inserted every time, and because it handles both the flag and array it inserts code for unzipping and extracting the vals, keep this in mind while naming

### Test
The snippet test is to be used in combination with futharki. The snippet inserts a map function with a built in trace, to iterate through an array, thus printing the values to the terminal.

#### syntax highlighting
Highlights commonly used operators, control keywords and the functions scan, sgmscan, zip, unzip, map, reduce, iota, replicate, map2, scatter

#### Snippets
Autocomplete for map, iota, replicate, scan, sgmscan, makeFlag, makeFlag1
#####mkFlag
Two snippets added which creates flag arrays for flattened matrices, mkFlag1 creates a flag array with ones, mkFlag makes it from the shape array. Needs a shape array, number of rows, and number of elements.
