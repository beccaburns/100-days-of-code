# 100 Days Of Code - Log

### Day 0: November 4, 2019

**Today's Progress**: Full stack web applicationed "Classy News". Today I pair programmed with two others in my cohort at CraftAcademy. We worked on the backend, incorporating Stripe. And on the front end, we included i18n for internationalization. 

**Thoughts:** Tomorrow we are having a sprint review with our coaches to review our progress. Plan for Sprint Review with client:

We're currently on schedule
- Deployment (done)
- User can log in (api & client - done)
- Journalist can create an article (api & client - done)
- Journalist can add images when they create an article (api & client - done)
- Payment functionality for 1 year with Stripe (api - done, client 80 % done)

 Currently working on & to do this sprint:
- User can see full article (api - done /client done but not merged)
- User can read articles in English and/or Swedish (client)
- User can navigate through the site with a navbar (client)
- Newsite changes language depending on browser language settings (client).
- Final part of client-side Stripe-functionality
- Mobil eapplication!

(So far we've completed 11 features + setup, working on 5 features (backend & frontend). )

Since you requested a mobileapp we need to re-allocate resources and won't be able to complete the planned features for the desktop application. We're going to reprioritize and focus on creating a mobile application and a desktop application with focus on news delivery. 

**Link to work:** [ClassyNews - Frontend](https://github.com/beccaburns/classy_news_client) [ClassyNews - Backend](https://github.com/beccaburns/classy_news_backend)

### Day 1: November 5, 2019

**Today's Progress**: We started today with a scrum at 9am to review yesterdays progress and to-dos for today. Today we worked on the Stripe cypress tests. We were having issues with the user authorization - 
**For context:**
- A visitor can subscribe
- A subscriber can view articles
- A journalist can write articles
- An editor can publish journalist articles

To fix this issue, we had to make some changes to the test to make sure that a subscriber and a journalist was actually being created. 
We also updated the seed file on the backend to display articles in a list format.
And on the front end, we created happy & sad paths for viewing a single article. 

**Thoughts**: Today was a challenging day. As projects become more complex, and more features are added, I realize the importance of organized pair-programming and teamwork/collaboration. My team consists of individuals at varying skill levels. This is beneficial as it promotes teaching and growth, but as fast-paced individuals gain traction, it can leave others behind without an understanding of what the code does/or how to test it. 

We recognized this half way through the day and took some time to communicate with one another about the code that we wrote and made a plan for next steps. The second half of the day was very productive and I sensed a collaborative environment that was lacking prior to our discussion.

**Link(s) to work**: 
- [Classy News - Frontend](https://github.com/CraftAcademy/classy_news_client)
- [Classy News - Backend](https://github.com/CraftAcademy/classy_news_backend)


### Day 2: November 6, 2019

**Today's Progress**: Yesterday was a good day! So good, I spent the whole day in code mode and forgot to take time to write my summary of the day.

So, here it is. 

Yesterday, my pair-programming team worked with REACT Native to create a mobile app for our "clients." I worked primarily on the front end in ReactJS to refactor our code and create a navbar component. We updated the routes with user authorization so that, depending on the user role, we are able to direct them to the right place.

**Thoughts** I went to a meetup last night for a product called Encore. A software engineer from Spotify developed a way to simplify the backend programming process. It was encouraging to be there and understand his references and makes me realize how much I learned in such a short period of time.

**Link(s) to work**
1. [User can view Navbar](https://github.com/CraftAcademy/classy_news_client/pull/18)

### Day 3: November 7, 2019

**Today's Progress**: Today I started the day with an online Kattis Logical Thinking Test for an application. I then began doing a bit of research on Kubernetes since this seems to be commonly used. Kubernetes is an open source container-orchestration system developed by Google and now maintained by Cloud Native Computing Foundation. It automates the distribution and scheduling of application containers across a cluster in a more efficient way.

I used the [Kubernetes Documentation](https://kubernetes.io/docs/tutorials/kubernetes-basics/)and tutorials to learn the following; 
- Deploy a containerized application on a cluster.
- Scale the deployment.
- Update the containerized application with a new software version.
- Debug the containerized application.

The rest of the day was spent working on the navbar branch, making sure of the right route paths for the user experience.

**Thoughts** 

**Link(s) to work**
1. [ClassyNews](https://github.com/beccaburns/classy_news_client/tree/navbar)

### Day 4: November 8, 2019

**Today's Progress**: Today was the day of debugging! I worked with my partner on debugging a new branch that we created for Classy News called navbar. After updating the semantic ui and css, we ran our tests through Cypress and almost all of them failed. YAY! So we went to town with "debugger" and worked through each test until we found the solutions. In our case, we needed to update the id's and create messaging for the user. 

**Thoughts** It has been a good experience to work with my partner and to use the debugger. The more I use debugger or in the case of RoR(binding.pry), the more comfortable I feel and the better I understand the problem and in turn, the right solution.

**Link(s) to work**
1. [ClassyNews](https://github.com/beccaburns/classy_news_client/tree/navbar)


### Day 4: November 9, 2019

**Today's Progress**: 
The day of debugging and presentation prep.

**Thoughts** 
Three weeks is too short to "finish" a fullstack web application.

**Link(s) to work**

### Day 5: November 10, 2019

**Today's Progress**: 

Practice JS tests on Qualified today.
ie. For this practice challenge, write a simple greeter function.
- If it is passed in a name NAME, return 'Hello, NAME!.
- If it is called without a name, return 'Hello there!.

```js
function sayHello (name) {
  if(name) {
    return "Hello, " + name + "!";
  } else {
    return "Hello there!"
  }
  
  console.log(name);
  return name; 
}
```
```js
let assert = require("chai").assert;
describe('Challenge', function() {
  it('should say hello', function() {
    assert.equal(sayHello("name"), "Hello, name!");
  });
  it('should handle blank input', function() {
    assert.equal(sayHello(""), "Hello there!");
  });
});
```

My new team for the final project spent the full day creating lofi's and setting up our PT with user stories and tasks for the weeks ahead.

**Thoughts** 
I am eager to get started with applications and interviews for a role as a junior developer. The coding tests are quite a challenge, so I am going to start dedicating myself to codewars throughout the week.

**Link(s) to work**

1. [PT-Link](https://www.pivotaltracker.com/n/projects/2417177)

### Day 6: January 7, 2020

**Today's Progress**: 
First day back to coding after a bit of a break. I took time off during my application process and during the holiday break. Today, I started slow by beginning with ReactJS. I am going to create a ReactJS portfolio blog for a project I would like to work on over the next couple of months.

**Link(s) to work**

1. [GitHub Link](https://github.com/beccaburns/react_portfolio_100Days)

### Day 7: January 8, 2020

**Today's Progress**: 

**Thoughts** 

**Link(s) to work**