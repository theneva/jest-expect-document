# Large snapshots break Jest

1. Run `yarn jest` to execute a test that expects `document` to match an inline snapshot
2. Wait
3. Get error messages about Jest running out of heap space

![image](https://github.com/theneva/jest-expect-document/tree/master/image.png)
