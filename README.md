- 
c
## blank line
line1
line2

line4
## this subtitle ## is about 'doSome()'
*`code*()`
this ***em* words** 

* * * 
**aa***bb*
some text  
aa``co```de``
## some List example
- item1
- item2

I need some thing below:
- an apple
- an orange
may be more

may be less
- an almond
- a tree

  a cat
  ## inner h2
 ## not right indented h2 can break list
- a dog
## how indent next to list line
-  first item
      ## heading can't continue
 
## thematic break in list line
- --  
- aaa
  bb
  *****  
  ccc
## list and quote mix exmaple
3. list item1 aa
4. ## heading 2
       inner code
       inner code continue
6. list item2

   > quote text
quote text contiue

> ## 引用中的标题

## Indented code blocks
     function create(){
    var a='text';
     var b=1;

 
     
     var c=3
description
     function modify
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
``
``` 

  ## Block Quotes
 paragraph text before
 >some contents **which are  
not code**  
just # text
> some quote1
>     quote2
quote3  
quote4

some text

>```
>abc
>```
>  def
lazy texts  
>## head def
lazy texts don't work not after paragraph 

quote in quote
>  > >inner text
continue1
>continue2
>### head3
>out text

>```
>> ## can't be a head



## Setext Headings can contain Hard Line Breaks
some words  
Foo *bar* some **bold**
=========


## Thematic breaks
Foo
   ***
hello
## table can break paragraph??
this is paragraph
foo | bar
--- | --- 
|cell1|cell2|

## table example
foo | bar
-|-|
foo2 | bar2 
 --- | --- 
 --- | --- 
| baz | bim |

 --- | --- 
 --- | --- 
| cell1 | cell2 |

## table and list mix example
 - list item1 
|head1 | head2|
|--- | --- |
|cell1|cell2|
- list item2 
  |head1 | head2|
  |--- | --- |
  |cell1|cell2|
- list item3 
  |head1 | head2|
|--- | --- |
  |cell1|cell2|
- list item4 

|head1 | head2|
|--- | --- |
|cell1|cell2|

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

