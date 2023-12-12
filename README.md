# Node & Express Bug Hunt!

**READ ALL INSTRUCTIONS BEFORE STARTING**

There are 10 bugs in total, can you find them all? There are hints throughout (???), you should only need to make minor modifcations to 10 lines of code.

**Don't race through the files looking for the issues!** They should all have a console log or error that help you identify them. Read the console so that you know what error will cause each bug. The last one is tricky since it doesn't throw any errors. Document the error, line number and your fix in this README for each of the bugs.

## Setup
```
npm install
npm start
```

> NOTE: A couple of bugs prevent the server from starting.

## Error List

TODO: Add the error here followed by the line of code you fixed.

### Bug 0

`ReferenceError: app is not defined`

Fixed `quote.router.js` line 28: switch `app` to `router`. _This is the solution to the first bug._

### Bug 1
changed `'/quotes` to `/` in line 8 and 15 inside `quote.router.js`

### Bug 2
Added `server` to file path on line 17 in `script.js`

### Bug 3
Line 21 in `quote.router.js` it is suppose to be `quoteList` and not `quotesList` small changes in variables can cause the code to break

### Bug 4
Line 5 in `quote.router.js` is an empty `object` and changed it to an empty `array` to be able to store objects in it

### Bug 5


### Bug 6
Added `module.exports = router` to line 28 in `quote.router.js`

### Bug 7


### Bug 8
Removed the `}` in line 7 from `client.js`

### Bug 9
Line 52 in client.js missing `s` when `getQuotes()` is called 

### Bug 10
In `index.html` the `onSubmit="submitForm(event)"` the S, is supposed to be lower case. Line 17.

## Extra Practice (Optional)

Complete the JS debugging exercises at:

- https://education.launchcode.org/intro-to-professional-web-dev/chapters/errors-and-debugging/exercises.html
