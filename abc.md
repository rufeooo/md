a
b
c

# heading with link [ [mm](http://rufe.org/)
# heading with # hash
#hash no space
# # double hash with spaces

d
<
> foo
this is & fair
[ single
] matched next line
-arg
--ddarg

-one
-two

- li
- -dashli
- [ok fine][]
 - list one whitespace indent
    - list four whitespace indent
        - list eight whitespace indent
- - double dash with space separation
-- double dash single trailing space

 > not a block? is block! mismatch with vim hilite

>block no space


> > this is a turd too

>> is this a double too?

> starts a block
> then another block on the next line
what happens?

> a quote happens
> > that contains a quote!
> then it concludes with an observation

```C
int main()
{
  return 0;
}
```

``` one-line code block ```

this is text with a `single tick` example

> blocks may not contain - same line list
end block

> blocks may not contain # same line heading
end block

> blocks may contain code on same line ```C int main() { return 0; } ``` 
end block

> block with
- next line list
is strange

> block with
# next line heading
is strange

- list may not contain > same line block
- list may not contain # same line heading

# heading may not contain > same line block
# heading may not contain - same line list 

mid sentence #heading haha
mid sentence # heading haha
mid sentence -dash more
mid sentence - dash more
mid sentence <block check
mid sentence < block check

blob of text with split [ of mine ]
( http://rufe.org/mine ) link

blob of text with space [ space_link ] ( http://rufe.org/space_link ) link

blob of text no space [ my_link ]( http://rufe.org/my_link ) link

yet whitespace doesn't matter interior to [link](http://rufe.org/link) blah

[ok fine]: http://rufe.org

