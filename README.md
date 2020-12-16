# try_demo
## this subtitle ## is about 'doSome()'
*`code*()`
this***em* words** 
 
* * * 
**aa***bb*
some text  
aa``co```de``
## List
  - usage1
- usege2
1. feature1
2. feature2
good
3. feature3
9. feature11
## Fence Code Block
```java
public class TestBitOp {

	public static void main(String[] args) {
//		int a=Integer.parseInt("01011111000000000000000000100000", 2);
		int a=-3;
		  System.out.println(a);
		System.out.println(a<<1);
		System.out.println(a>>31);
		[A -+ aX·;3]
		System.out.println((a<<1)^(a>>31));
		
		
		
		
		
	}

}
``` 

  ## Block Quotes
some contents **which are  
not code**  
just # text
> some quote1
>     quote2
quote3  
quote4

some text

## Setext Headings can contain Hard Line Breaks
some words  
Foo *bar* some **bold**
=========


## Thematic breaks
Foo
   ***
hello

## table
| foo | bar |
| --- | --- |
| baz | bim |


 
## label model of link,label can be at anywhere
ccc*aa**bb*** 


[label_name]: /url "title"

[label link][label_name] 
 
## link text can't contain another link
[[link](/url "tilte")  

[[inner link](/url "tilte") outer_linker](/url "title2")
## link text can contain code_span 
[`foo222`](`mmmm`url "`tttt`title2")   
[`foo]333`]("ttttttttttitle2" )   

[out_a]( "a/in_a_url ) "out_a_title")
aaaa  
`[ggg]( a/in_a_url "aaaa")aa`  
[gg`g]( a/in_a_url "aaaa")aa`  
[ggg](`a/in_a_url "aaaa")aa`  

[gg`g](a/in_a_url "aaaa")aa
## link text can contain em ，but link tilte can't contain em
[*foo222*](/u*r*l "*title2*")  


## blank line can start a new paragraph
aa

bb

cc

## em contain code
aaa*[foo22](url)*
aaa *`doIt()`*
aaa*commcon_text `code`*
*`do*It()`*    
rules:em can contain code_span only if the left delimiter is `left-flanking delimiter run` and right delimiter is `right-flanking delimiter run` which can't be a both delimiter like aa\*aa.   
the same rule is for em-to-link

##  em can contain hard_line_break
this is a line***emspan  
a* b*
## the rule for left-em-delimiter about puncutaion
aa *+abc*  
aa+*+abc*  
aaa*+abc*
## how to deal with unclosed code when inline-parse phase end
begin*abc `code*abc*
## how to deal with unclosed link when inline-parse phase end
*[foo*222*22](/url "title2"
