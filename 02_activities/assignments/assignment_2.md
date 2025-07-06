# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      *Bad visualization example:* https://assets.sbnation.com/assets/2977907/horrible_bar_graph_-_july_28_2nd_inning_medium.jpg

      This is a very poor representation of data because for starters there is no clear classification of the data units. We are led to assume that '7' is just a little higher than .452! Also, these stat categories can be confusing for people not already familiar with them. For example, OPS stands for 'on-base plus slugging percentage'. Through a more academic lens, this example lacks any clear axes and labels, which makes it hard to tell what’s being measured or which category each bar represents.
      It's also a poor use of volume encoding, which misrepresents the magnitude of the player's achivements over the homestand. The gridlines do little other than make it more confusing (visual noise) and chart “junk” distracts from key insights and undermines clarity. Overall, it fails to communicate anything meaningful. 

      *Good visualization example:* https://schoolofcities.github.io/transportation-tomorrow-survey/line-2-trips

      The author (Jeff Allen) turns thousands of trips between Toronto subway stations into a visually-striking flow diagram without sacrificing clarity. It uses colour, curvature, and density to communicate travel volume, encoding trips between stations with visual weight and flow directionality

      I loved this piece when it scrolled across my timeline on BlueSky. Visually, it's beautiful and immediately invokes a curiosity to further understand the representation. All this despite the data not neccesarily revealing anything suprising about the volume of trips. We can instantly grasp where the action is (e.g., heavy traffic at St. George, Yonge-Bloor, Kennedy) while also spotting asymmetries in movement across the eastbound and westbound sections of track. The scale legend at the top right uses clean gradients to show trip volume bands (<100 to 1000+), letting viewers interpret density without confusion. I noted that Jeff Allen provided a link to the R script he used, so that's something I am looking forward to playing with! 













      ```
    - How could this data visualization have been improved?  
      ```
     *For the bad example:*
     Choose better data: These stats can be confusing to casual viewers, and they offer very little in comparibility. Find something to compare, simplify the message

     Clear Labels & Axes: Label bars directly, use a properly scaled y‑axis (starting at zero), and add gridlines only as needed for readability

     Title & Annotations: Add a concise title stating what the chart’s about (e.g., Reyes drives up his percentage stats on homestand) and consider a simple annotation to highlight the main takeaway

     *For the good example:*
     It takes a moment to orient yourself, especially for people unfamiliar with Toronto’s TTC map. A small base map inset, or a note about what the curved arcs mean (like "Each arc represents average weekday trips between stations, curved for legibility")








      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 06/07/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
