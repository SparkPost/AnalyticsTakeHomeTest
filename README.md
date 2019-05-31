# Analytics Take Home Test
A place to showcase your abilities

Take a look at the trigram kata from Dave Thomas http://codekata.com/kata/kata14-tom-swift-under-the-milkwood/

Sumbit a PR to this repo with a solution to the problem as stated, wrapped in an HTTP service. Your service should expose a POST endpoint that takes a .txt file. You should be able to list any files that you have uploaded, as well as get information about the file (file size, number of trigrams). You should also be able to generate trigrams from the files.

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
