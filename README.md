# Analytics Take Home Test

The purpose of this test is to show off your ability to solve an interesting problem using Node.js. There are no 'correct' or 'incorrect' answers, and a complete solution is not expected; we will also be looking at how you choose to approach a problem and the tradeoffs you decide to make. Go through the problem and identify any potential issues you see. Set aside about 3 hours and put together as much of the solution as you can, focusing on having something useful to your users.

# Problem statement

Take a look at the trigram kata from Dave Thomas http://codekata.com/kata/kata14-tom-swift-under-the-milkwood/

Create a Node.js service that wraps a solution to the above problem in an command line interface. Your service should expose a upload command that takes a .txt file. You should be able to list any files that you have uploaded, as well as get information about the file (file size, number of trigrams). You should also be able to generate trigrams from the files.

Here's an example interface using a `trigram.js` file:
* `node trigram upload` -> uploads a new file
* `node trigram files` -> returns list of files that have been uploaded   
* node trigram file id=<id> -> returns info about a single file
* node trigram generate file=<file-id> maxSize=<size> seedWords=<words> > returns generated text based on the contents of a given file

## Required Technologies:
* Node.js
* Git

## Recommended (optional) technologies:
Typescript
Postgres  

# Stretch Goals

If you finish that, try one of these stretch goals:

## Calculate Number of Trigrams Per file
Have the `file id=<id>` command return the number of unique trigrams in the file.

## Write an express app with the following routes:
```
POST /upload
GET /texts -> returns list of texts that have been uploaded
GET /texts/:id -> returns info about the text
GET /texts/:id/generate?maxSize&seedWords -> returns generated text
```

## Write Tests
Add linting, style checks, unit, and/or integration tests

## Optimize
Make it bigger faster stronger!

# Submission
Create a Github repo and respond to this email with a link to it. Gitlab or BitBucket repos are also fine, but please use git for version control.
