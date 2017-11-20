# Snapshot report for `test\generated\commands\persist.test.js`

The actual snapshot is saved in `persist.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/persist.md example 1

> Snapshot 1

    [
      'await handy.set("mykey", "Hello")  => "OK"',
      'await handy.expire("mykey", 10)    => 1',
      'await handy.ttl("mykey")           => 10',
      'await handy.persist("mykey")       => 1',
      'await handy.ttl("mykey")           => -1',
    ]