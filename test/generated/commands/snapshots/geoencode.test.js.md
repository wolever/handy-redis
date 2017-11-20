# Snapshot report for `test\generated\commands\geoencode.test.js`

The actual snapshot is saved in `geoencode.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/geoencode.md example 1

> Snapshot 1

    [
      'await handy.geoadd("Sicily", [13.361389, 38.115556, "Palermo"], [15.087269, 37.502669, "Catania"])                       => 2',
      'await handy.zscore("Sicily", "Palermo")                                                                                  => "3479099956230698"',
      '// not implemented by node redis: await handy.geoencode(`Couldn\'t format arguments: Couldn\'t find command "geoencode"`)  => "// not implemented by node redis: await handy.geoencode(`Couldn\'t format arguments: Couldn\'t find command \\"geoencode\\"`)"',
    ]