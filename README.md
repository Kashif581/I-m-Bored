![Screenshot (721)](https://github.com/Kashif581/I-m-Bored/assets/114382367/963cc67c-f5d3-4b9e-9add-887c6d24dc65)
![Screenshot (720)](https://github.com/Kashif581/I-m-Bored/assets/114382367/bb703f7a-b476-45f6-b5db-8f0abc41076e)
![Screenshot (719)](https://github.com/Kashif581/I-m-Bored/assets/114382367/da470367-5168-494e-8d33-b279b2619261)
![Screenshot (718)](https://github.com/Kashif581/I-m-Bored/assets/114382367/f8396fae-1a8b-4a70-8c4b-64e5d4aa258e)

This is a website called, "I'm Bored" and it's going to help you find something to do when you're bored.
When you first load up the homepage, when you make the first GET request, it's going to fetch a random activity from that endpoint which was "bored-api.appbrewery.com/random"
Another thing that you can do with this website hitting up a different route on our server is to make a POST request and say, "I want to find activities that have a type of education that are for a single
person to do." Now, there are cases where this fails.
So for example, in our bored API, there actually are no educational-type activities that are for two people. So if you hit Go in this case, you'll get an error back and we handle that error and pass a relevant
message for the user. So in this case, it says. "No activities that match your criteria."
That's pretty much the entire website.
