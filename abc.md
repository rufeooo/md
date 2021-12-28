a
b
c

# heading with link [ [mm](http://rufe.org/)
# heading with # hash
#hash no space
mid #heading haha
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
 - hmm
    - indent
        - indent
- - double dash with spaces
-- double dash one space

mid -dash more

 > not a block? is block! mismatch with vim hilite

>block no space

mid <block sentence

> > this is a turd too

```C
int main()
{
  return 0;
}
```

``` one-line code block ```

this is text with a `single tick` example

> blocks may contain code on a single line ```C int main() { return 0; } ``` 
end block

trailing text after closing ticks changes the closing block meaning
trailing whitespace after closing ticks does not change a closing block

[ok fine]: http://rufe.org

