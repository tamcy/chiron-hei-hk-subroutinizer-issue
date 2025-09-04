
Commands

```sh
# postscript format
tx -t1 -g /28100-/28700 test.otf cid28100-28700.ps

# No subroutinization
tx -cff -S -g /28100-/28700 test.otf cid28100-28700-S_OK.cff2

# With subroutinization
tx -cff +S -g /28100-/28700 test.otf cid28100-28700+S_FAIL.cff2
```

```sh
tx -cff +S -g /28185-/28557 test.otf cid28185-28557+S_OK.cff2
tx -cff +S -g /28185-/28657 test.otf cid28185-28657+S_FAIL.cff2
tx -cff +S -g /28285-/28657 test.otf cid28285-28657+S_OK.cff2
```

```sh
tx -cff +S -g /28195-/28647 test.otf cid28195-28647+S_OK.cff2
tx -cff +S -g /28195-/28657 test.otf cid28195-28657+S_FAIL.cff2
```
 