Reading Class 05: 

# [What is CSS? Reading](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

**CSS** *(Cascading Style Sheets)*: 
+ Controls how documents are presented to users. 
+ Rule based language. 
    + Define rules by specifying groups of styles to be applied to element(s).
+ Browsers may implement features at the same time, however new features won't break previous ones.


**Example:**  
h1 {  
  color: red;  
  font-size: 5em;  
}   
**Key:**   
Selector- h1  
Set of Brackets {}  
Inside: Declarations (Property: Value)  
color: red;

# [CSS How To](https://www.w3schools.com/css/css_howto.asp)
*Ways to Insert:*   
+ External: Any text editor with .css. No html tags.
+ Internal: Used if one HTML sheet has a unique style.
+ Inline: Apply style to a single element. Use method sparingly.    

*Order of Specificity:*  
If there is more than one style sppecified for an HTML element it will follow...
1. Inline
2. Exernal and Internal
3. Browser Default

*Colors:*  
**Hexadecimal Colors:**  
#p1 {background-color: #ff0000;} /red/  
#p2 {background-color: #00ff00;} /green/  
#p3 {background-color: #0000ff;} /blue/  
**Hex with Transparency:**
#p1a {background-color: #ff000080;}   /* red transparency */  
#p2a {background-color: #00ff0080;}   /* green transparency */  
#p3a {background-color: #0000ff80;}   /* blue transparency */  

Example: 
To make a paragraph's text red, you would open a .css sheet and type:  
p {  
color: red or #ff0000 

