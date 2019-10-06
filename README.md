# logging-cm

```
from logging_cm import log_grouping

with log_grouping(prefix="[ACME]") as log:
    log.warning("Something is going on")
    log.info("Something good is on the way")
    log.debug("You got icecream!")
```

Output:

```
[ACME] WARN Something is going on
[ACME] INFO Something good is on the way
[ACME] DEBUG You got icecream!
```
