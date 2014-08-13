# otfeatures


A SASS mix-in for turning OpenType features on and off in your embedded web fonts. (Only useful if you're using a web font with embedded OpenType features such as ligatures, swashes, etc)
  
  
Easy to use by only passing in the flags you want - so if you only want to turn on common ligatures, you could use:  
  
@include otfeatures($liga: 1);  
  
## OpenType Features Key

@mixin otfeatures($c2sc: 0, $calt: 0, $clig: 0, $dlig: 0, $frac: 0, $hist: 0, $hlig: 0, $kern: 0, $liga: 0, $nalt: 0, $ncase: 0, $nspace: 0, $salt: 0, $smcp: 0, $ss01: 0, $ss02: 0, $ss03: 0, $ss04: 0, $ss05: 0, $swsh: 0, $zero: 0)

## Ligatures 

"liga" : common ligatures 
"dlig" : discretionary ligatures 
"clig" : contextual ligatures 
"hlig" : historical ligatures 

## Alternate Characters

"swsh" : swashes  
"calt" : contextual alternates  
"hist" : historical character alternatives  
"salt" : stylistic alternatives  

## Kerning

"kern" : enable use of embedded kerning table  

## Letter Case

"smcp" : small caps  
"c2sc" : small caps from caps  

## Stylistic Alternates

"ss01" : alternate stylistic set 1  
"ss02" : alternate stylistic set 2   
"ss03" : alternate stylistic set 3  
"ss04" : alternate stylistic set 4  
"ss05" : alternate stylistic set 5  

## Numeric Extras

"zero" : slashed-zero  
"nalt" : alternate annotation  

The following OT Features are either/or rather than single choices, so require some 'if/else' logic  

## Number Case

"ncase" : number case  
>		0: default  
>		lnum: lining figures  
>		onum: old style figures  

## Number Spacing

"nspace": number spacing
>		0: default
>		pnum: proportional spacing
>		tnum: tabuplar spacing

"frac"	: fractions
>		0: off
>		frac: normal fractions
>		afrc: alternate fractions
