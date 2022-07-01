# B2Brain Frontend Challenge

## Who is this for?

This challenge is meant for candidates who wish to work / intern at B2Brain and work with our engineering teams.

## Who we are?

At B2Brain, we are solving real problems for Sales leaders in B2B SaaS companies, by providing them intelligence and information not available otherwise. B2Brain is saving sales teams countless hours daily, and helping improve companies bottom line.

We are a fast paced environment, that believes in delivering impact to our end users fast. 


## Challenge Outline

The challenge has three deliverables

1. Setting up a blank Django app (on local, with no db)
2. Serving a single page with all relevant HTML/CSS that visually matches the specs linked below
3. Interaction on the page, and fetching data from the live API, and submitting the data.


## Specs

We are making a single page which would act as a user's primary dashboard to interact with B2Brain.
Along with that, we have a search-interaction which can search our company database using the API detailed below.

### Visual Specs
Figma Prototype: [Link](https://www.figma.com/file/ajoMUTBD4az0yUymEdJUN8/Specs-for-Frontend-Assignment?node-id=0%3A1)

Clickable Prototype: [Link](https://www.figma.com/proto/ajoMUTBD4az0yUymEdJUN8/Specs-for-Frontend-Assignment?node-id=0%3A1&viewport=709%2C461%2C0.15&scaling=min-zoom&starting-point-node-id=3%3A150)

Make sure you go through all comments on Figma as well. 

### Search API
API Endpoint: `https://staging.staging.b2brain.com/search/autocomplete_org_all/`

Method: `GET`

Data: `q=<search-term>`

Example: `https://staging.staging.b2brain.com/search/autocomplete_org_all/?q=b2brain`

Output Schema:
```javascript
{
    "company": "B2Brain", // Company name
    "slug": "credibase-inc", // Company unique ID
    "logo": "https://cbandrey2static.s3.amazonaws.com/media/logos/credibase-inc_20200323155513",
    "website": "b2brain.com" // Company website
}
```
(You can ignore all other fields)


## Constraints
1. HTML/CSS properties to be used should work across Chrome v80 or above
2. Knockout.js framework to be used for javascript interactivity
3. CSS preferrably should be written via Less/Scss/Sass


## Submission

You can submit your assignment by pushing your code to your public github repository. 
Once you do, don't forget to [fill the form here](https://forms.gle/PN3m4JVFgZ1wzTRA7).


## What happens next?

You will hear back from us via email. We may request for some changes based on reviewing your code.

Subsequently, we will schedule a phone interview with someone from ur team, and if that goes well, we'll make an offer. 


## Help?

Do not hesitate to ask questions about the assignment to get clarity. Good questions help us understand you better, than bad code :)
We are available on hiring@b2brain.com (Make sure you put "Frontend Challenege" in the subject)
