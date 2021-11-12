## Bug Description
When using fast-horizontal-scroll in a simple application, the flipper didn't appear when it should

## How to replicate the bug?
- npm install
- npm run start
- try to reduce the width of the browser until some of the buttons were hidden. The expectation is that the flipper should appear whenever any button becomes invisible. But it didn't.