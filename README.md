Yifei Xue

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
1. Within a Github action that runs whenever code is pushed 
2. Manually run them locally before pushing code
3. Run them all after all development is completed
   
We should fit the tests Within a GitHub Action that runs whenever code is pushed because it provides immediate feedback, ensures consistency across environments, supports team collaboration by catching issues early, and aligns with the project's GitHub Pages deployment and Gradescope submission requirements.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   
   No

4) What is the difference between navigation and snapshot mode?
   
   Navigation mode analyzes a webpage immediately after it loads, focusing on initial performance metrics like load time, rendering, and resource usage. It evaluates the overall performance but does not account for user interactions or dynamic content changes. Snapshot mode analyzes the webpage in its current state, focusing on accessibility and static content. It’s ideal for identifying accessibility issues but cannot evaluate JavaScript performance or dynamic DOM changes.

6) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   
1. Add a <meta name="viewport"> tag to the <head> section to improve mobile responsiveness and SEO.
2. Convert images to next-gen formats to save 165 KiB, improving load times and Performance.
3. Serve images that are appropriately-sized to save cellular data and improve load time by 549 KiB.


