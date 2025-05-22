1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed 
- Within a Github action, since in that way every change would be automatically tested before being merged into the main branch. This is exactly what we want, and it's a much better approach than manual testing which is prone to accidentally pushing broken code.

Manually run them locally before pushing code
Run them all after all development is completed

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   No

3) What is the difference between navigation and snapshot mode?
Navigation mode analyzes the performance of a webpage as it loads from scratch, giving insights into things like load time, first contentful paint, and overall performance, while snapshot takes a single screenshot of the current page state, mainly to check accessibility and static content.

1) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

Optimize image sizes to  improve performance scores.
Add alt text to images
Reduce any unnecessary JavaScript and CSS



