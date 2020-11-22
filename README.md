# hello-world
test hello world


eerste projet :
maak een tesseract-ocr spéciaal om de chambers jpg texten te "lezen", dus

1) Training of Tenserflow om de
   volgende ROI (regio of interest) défineren per bladzijde :
   + top-page    ex. 48: ABA (3) ABA" ; 56: "ABS (11) ABS" -> ocr training à part
   + left-kolom  ex. 48 : ABATEMENT   ; 56: ABSTRACTION
   + right-kolom ex. 48 : ABBOT       ; 56: 
   + bottom-page ex. 48 : "I   the"   ; 56: "The"  -> geen ocr
2) Extract and enhance relevant image segments with OpenCV   
3) een Tenseract training database créeren op basis van al gemaakte bladzijden
   blz 0048.jpg  (>ABATEMENT<)  tot en met 0056.jpg  "ABS (11) ABS" (>ABSYNTHIUM<)
4) Use Tesseract to extract, export text data vanf blz 0057 tot ....
