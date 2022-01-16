# StoryDataset_AMT

Story creation is a complex and challenging task. 
Making an interesting story is even de003 manding. In this paper, we present a novel approach to build an illustration-based text story dataset. 
We collect 384 illustration006 based text stories, where each story is clas007 sified with its ending type - either a happy ending or a sad ending.


### Two examples of illustration-based text stories
<img src="https://user-images.githubusercontent.com/46912893/149653869-81ad8cc5-3fb4-4f56-8825-426f2e36a07a.JPG" width="100%" height="100%">

To collect an illustration-based text story dataset by crowdsourcing, we utilized Amazon’s Mechanical Turk (MTurk).
The sequence of cards used in the story building represents time ordering (1: Introduction and Setup; 2: Actions and Development; 3: Ending). 
The text for each card is requested to write a sentence at least containing one event.

### Figure 2: An example of matching words for an illustration card (A_8: Return home in glory)
<img src="https://user-images.githubusercontent.com/46912893/149653938-c5d2766a-9aa8-4df0-b5ae-9c109f2ea6b1.JPG" width="40%" height="40%">

As people can interpret a same illustration differently, we collected a list of representing words for each illustration card for better understanding.


### Figure 3: Sentimental Patterns of the Illustration Cards according to the Ending Type
<img src="https://user-images.githubusercontent.com/46912893/149653914-37baa21b-b284-4761-ae7b-b3ed02eb58d7.JPG" width="40%" height="40%">

The most frequently appearing sentiment pattern in happy ending stories is P-P-P.
And the second most frequently appearing pattern is N-P-P.

As for sad ending stories, the three most frequently appearing sentimental patterns are P-P-N(25.50%; 51/200), P-N-N (24.50%; 49/200), and N-N-N (21.50%; 43/200).
