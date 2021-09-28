### [Team H: The outsiders] PinPlace: CNN based location image search and its adaptation to social network

#### Feedback (from other teams)
- [+] study of previous work (CNN) looks great
- [+] well-presented solution
- [+] well-defined problem
- [+] clear role distribution
- [-] how to select a dataset (e.g., 10 hot places for MZ generation)
- [-] unrealistic solution
- [-] hard to say a proper semester-long project
- [-] role/collaboration are not well presented
- [-] lack of merits (maybe hashtags are sufficient?)
- [-] lack of explanation why the service is needed

#### Suggestions / Questions (from other teams)
* Choosing the right dataset is needed
* Can you think of additional features? 
* Can you clarify why we need this service other than GPS?
* The proposal is about to find a location; but it looks a simple image classification problem
* How do you recognize pictures in the same place, but looking quite different?
* There are people who do not want to disclose their locations for privacy

#### Comments
* Overall, the proposal looks fine, but questionable in usage.
  Is this approach expandable by design? In Seoul, maybe we have hundreds of 
  well-known places. There are hundreds of thousands of popular places in the world.
  Can the proposed technique have a good performance when classifying
  such a large number of labels?
* Hot places with a sorting algorithm lead to change rankings (page 12 in the slides).
  Then you should rebuild the model each time? 
* In slide p9, does Russia’s tourism application employ three models at the same time?
  Or did they make a comparison between those models? 
  I think proposing the best empirical model can be a nice contribution itself.
* Can you clarify if you leverage location information (page 13) from other resources
  into determining a location? If so, how does it help when building a model?
* Can you provide a project plan in detail with a timeline 
  (e.g., week1, week2, ...) as well as members and roles?
