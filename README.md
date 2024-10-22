# GitHub Enterprise Foundations

Class Date: October 22 - 23, 2024
Facilitator: Connor Bottum, @c4llmeco4ch

Feedback for this course can be left in this survey: https://www.surveymonkey.com/r/CCBKQF2

## Actions/Workflows we have created

For the purposes of either the Platform tutorial or things we have found to be common asks from clients, we are storing actions and workflows we have created here

-   enforce-favorite-number: A simple action that takes the Issue event that triggered the workflow and checks to see if the Favorite Number field has an appropriate value (used in ADOE 2023)
-   repo-name-complaince: Will pull all repos for a specific organization and determine if the name matches the pattern passed in. Housed in it's own repo as it is published to the marketplace (will include url once that is done)
-   tell-me-a-joke: Based on the input for the favorite number in the introduction activity, will prompt them with a new issue to tell them jokes.
-   pass-variables-linux: Shows different ways that you can pass job and environment variables between a workflow and an action in a linux environment.
-   pass-variables-windows: Shows different ways that you can pass job and environment variables between a workflow and an action in a windows environment.
-   ghas-alert-collection: Use the Octokit Javascript library to pull all alerts for a specific organization and then upload those alerts as a single JSON file as an artifact on the workflow run.
