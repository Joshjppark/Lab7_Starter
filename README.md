Joshua Park A16966614

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed, because manual run can be unpredictable when errors occur from local bugs. Running them after development is a bad idea since you have to repeat many debugging cycles at the later stages. Testing when pushing is ideal since it is in a controlled environment before new code reaches "safe" code

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No, since a unit test is better suited for that

3) Navigation mode provides metrics for the page load, such as how quickly/smoothly the page loads. It shows how good/efficient the JS is along with rendering parts. Good for analytics in the 'read-world' since users will be interacting with the website

Snapshot mode analyzes the current state of a page without page reload. Does not render itself or analyze JS performance. Better to understand a state of the page due to JS scripts and analyze what happens "in between" Navigation mode steps.

   
4) 
* Including the `meta name="viewport">` tag would be a lot friendlier for mobile users
* Reducing image size would be easier for the website to render images, since they are being reduced anyways in the website
* A lot of JS is not being used, so cutting down the JS code would improve website loading speed