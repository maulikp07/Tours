Tours incorporates Advanced CSS and SASS concepts with Flexbox, Grid, Animation and many more to explore!!!

This project is developed using the 7-1 pattern ( 7 different folders for partial Sass files and 1 main Sass file to import all other files into a compiled CSS stylesheet.

The 7 Folders:
  base/
  components/
  layout/
  pages/
  themes/
  abstracts/
  vendors/

***********************Behind the Scene Value Processing.******************************************************************
  1. Each property has an initial value, even though it is not declared.
  2. Browsers specify a root foont-size for each page ( user agent declaration usually 16px).
  3. Percentages and relative values are always converted to pixels.
  4. Percentages are measured relative to their parent's font-size, if used to specify font-size
  5. Percentages are measured relative to their parent's width, if used to specify lengths.
  6. em are measured relative to their parent font-size, if used to specify font-sixe
  7. em are measured relative to the current font-size, if used to specify lengths.
  8. rem are always measured relative to the document's root font-size.
  9. vh and vw are simply percentage measurements of the viewport's height and width.
  
  
  ************************************************CSS Cascading********************************************************************
  
  ********* Importance************ >>> ************ Specificity********************* >>> ************** Source Order****************
  1. User !important Declaration    1. Inline styles                      1. The last declaration in the code will 
  2. Author !important Declaration  2. IDs                                2. Override all other declarations and will be
  3. Author Declaration             3.Classes, psuedo-classess, attribute    applied.
  4. User Declaration               4. Elements, psuedo-elements
  5. Default Browser Declaration
