# Analytics Take Home Test

The purpose of this test is to show off your ability to create an API. There are no 'correct' or 'incorrect' answers, and a complete solution is not expected. Go through the problem and identify any potential issues you see. Set aside 2-3 hours and put together as much of the solution as you can, focusing on the project dev setup (i.e. getting an express server stood up, setting up your DB, how will you accept multipart form uploads, how tests will run, etc.)

# Problem statement

Take a look at the trigram kata from Dave Thomas http://codekata.com/kata/kata14-tom-swift-under-the-milkwood/

Create a service that wraps a solution to the above problem in an HTTP service. Your service should expose a POST endpoint that takes a .txt file. You should be able to list any files that you have uploaded, as well as get information about the file (file size, number of trigrams). You should also be able to generate trigrams from the files.

Example endpoints:  
POST /upload  
GET /texts -> returns list of texts that have been uploaded   
GET /texts/:id -> returns info about the text  
GET /texts/:id/generate?maxSize&seedWords -> returns generated text  

Recommended technologies:  
Node.js  
express  
Typescript (optional)  
postgres  

# Submission
Create a compressed archive file of your project and email it to timothy.ecklund@sparkpost.com
