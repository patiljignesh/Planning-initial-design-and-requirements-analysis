# Connecting the dots

## Requirements 
## Story Received

As a user I want the app to load the feed so I can see the feed.

## Better Story would be:

## Requirements:
###### Image Feed Feature
###### BDD Specs (Behaviour Driven Development)
###### Story: Customer requets to see the feed

###### Narrative 1
> As an online customer, I want the app to automatically load my latest image feed. So I can always enjoy the newest image of my friends. 

###### Scenarios (Acceptance criteria)
After asking the rigt questions, we improve the requirements further
> Given the customer has connectivity, wehen the customer requests to see the feed then the app should display the latest feed from remote and replace the cache with the new feed. 

Now the narrative improves. 
###### Narrative 2 
> As an offline customer, I want the app to show the latest saved version of my image feed, so I can alway enjoy images of my friends.

Further improvements of Scenarios will be :
###### Scenarios (Acceptance criteria)
> Given the customer doesn't have connectivity, when the customer requests to see the feed then the app should display the latest feed saved. BUT given the customer doesn't have connectivity and the cache is empty when the customer requets to see the feed then the app should display an error message. 

## Use Case Modeling Technique by Ivar Jacobson 

## Use Cases 
- A use case is an agnostic of delivery mechanisms; for example UI
- A Use case encapsulates application specific business rules
- 
###### Load Feed
###### Data: 
- URL
- 
###### Primary Course: Happy Path

###### Sad Path 
