# try_demo
## this subtitle ## is about 'doSome()'
some description about `doSome()`
##another subtitle 
  - usage1
- usege2
1. feature1
2. feature2
good
3. feature3
9. feature11
## some code
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
## h2 next to code block


> Lorem ipsum dolor
sit amet.
> - Qui *quodsi iracundia*
> - aliquando id
  ## contet
some contents **which are  
not code**  
just # text
> some quote1
>     quote2
quote3  
quote4

some text



Foo *bar* some **bold**
=========
some words

Foo
   ***
hello

| foo | bar |
| --- | --- |
| baz | bim |

abc *de* fg
hij
ab*cd'e*fg'  
* adbf*  
***abc***  
****abc****  
*****abc*****  
*****abc**  
aa+*+abc*  


# 
abc  
*foo`*  
**foo **bar  
*[foo*](url)  
*[*foo*](url)  
 aaaa     
# 2 this is h2
af

[bar]: /url "title"

  
ccc*aa**bb***  
aa+*+abc* 
``
code()
## link text can contain code_span 
[`foo222`](`mmmm`url "`tttt`title2")   
[`foo]333`]("ttttttttttitle2" )   

[out_a]( "a/in_a_url ) "out_a_title")
aaaa  
`[ggg]( a/in_a_url "aaaa")aa`

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
## how to deal with unclosed item when inline-parse phase end
begin*abc `code*abc*`
