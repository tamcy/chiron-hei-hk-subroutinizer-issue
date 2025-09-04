### Attempt 4

```sh
tx -cff +S -g /28195-/28553,/28557-/28657 test.otf cid28195-28553,28557-28657_OK.cff
tx -cff +S -g /28195-/28554,/28557-/28657 test.otf cid28195-28554,28557-28657_FAIL.cff
```

### Attempt 3

```sh
tx -cff +S -g /28195-/28647 test.otf cid28195-28647_OK.cff
tx -cff +S -g /28195-/28657 test.otf cid28195-28657_FAIL.cff
```

## Files not in repo

### Attempt 2

```sh
tx -cff +S -g /28185-/28557 test.otf cid28185-28557_OK.cff
tx -cff +S -g /28185-/28657 test.otf cid28185-28657_FAIL.cff
tx -cff +S -g /28285-/28657 test.otf cid28285-28657_OK.cff
```

### Attempt 1

```sh
# postscript format
tx -t1 -g /28100-/28700 test.otf cid28100-28700.ps

# No subroutinization
tx -cff -S -g /28100-/28700 test.otf cid28100-28700-S_OK.cff

# With subroutinization
tx -cff +S -g /28100-/28700 test.otf cid28100-28700+S_FAIL.cff
```

