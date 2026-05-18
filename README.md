## Aarnav Gujjari - A19127921

# 1.  Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

## I would run it within a Github action that runs whenever code is pushed because this way the code is continuously being tested while being developed. If you only test locally, you don't know how your code will fare when running with the rest of the system with logic and dependecy discrepencies. If you just test everything at the end, then it will be very messy to debug. The best approach is to test often during development using Github Action so that faulty code will never even get merged to the main branch.

# 2. Would you use an end to end test to check if a function is returning the correct output?

## No, I wouldn't because we don't want to test the entire application's workflow just for testing a single function's output.

# 3. What is the difference between navigation and snapshot mode?

## Navigation mode analyzes a webpage after it initially loads, but can't analyze user interactions or any changes that happen to the page after it initially loads. Snapshot mode, on the other hand, let's you analyze the webpage in its current state but not JavaScript performace.

# 4. Name 3 things we could do to improve the CSE 110 shot site based on the Lighthosue results.

## I think we could compress the product images or use modern file formats so the page loads a lot faster. We can also add descriptive alt tags to the product images so that screen readers can actually read them, which fixes accessibility. Finally, we could add a meta description tag in the HTML header so that search engines can easily figure out what the shop site is for, which helps with SEO. 





