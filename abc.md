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
 - hmm
    - indent
        - indent
- - double dash with spaces
-- double dash one space

 > not a block? is block! mismatch with vim hilite

>block no space


> > this is a turd too

>> is this a double too?

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

> blocks may not contain lists - whee
end block

> blocks may contain lists
- whee
end block

> blocks may not contain headings # mid-block
end block

> blocks may contain headings
# mid-block
end block

- list with block > nope

# heading with block > nope

mid sentence #heading haha
mid sentence # heading haha
mid sentence -dash more
mid sentence - dash more
mid sentence <block check
mid sentence < block check

[ok fine]: http://rufe.org

