# Snapshot report for `test\generated\commands\hkeys.test.js`

The actual snapshot is saved in `hkeys.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/hkeys.md example 1

> Snapshot 1

    [
      'await handy.hset("myhash", "field1", "Hello")  => 1',
      'await handy.hset("myhash", "field2", "World")  => 1',
      'await handy.hkeys("myhash")                    => ["field1","field2"]',
    ]
