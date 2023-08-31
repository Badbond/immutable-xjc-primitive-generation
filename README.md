# `sabomichal:immutable-xjc` primitive field bug reproduction

Minimal reproduction case for bug https://github.com/sabomichal/immutable-xjc/issues/107.

Requires Maven and JDK 17. 

Run with:

```bash
mvn clean compile
```

And inspect logs and `target/generated-sources/xjc/me/soels/model/` classes.
