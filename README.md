
Commands

```sh
# postscript format
tx -t1 -g /28100-/28700 test.otf cid28100-28700.ps

# No subroutinization
tx -cff -S -g /28100-/28700 test.otf cid28100-28700-S.cff2

# With subroutinization
tx -cff +S -g /28100-/28700 test.otf cid28100-28700+S.cff2
```