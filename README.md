# Guided-Project_8_Star-Wars-survey

Star Wars Survey

While waiting for [Star Wars: The Force Awakens](https://en.wikipedia.org/wiki/Star_Wars:_The_Force_Awakens "Star_Wars:_The_Force_Awakens"), the team at [FiveThirtyEight](http://fivethirtyeight.com/ "FiveThirtyEight") was interested in answering some questions about Star Wars fans. One question that particularly interested the team was: *Does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?*

The team needed to collect data before they could get started answering this question. They used SurveyMonkey, an online survey tool, to survey Star Wars fans. They received 835 responses total, which you can find [here](https://github.com/fivethirtyeight/data/tree/master/star-wars-survey).

In this project, we'll be cleaning and exploring the dataset in Jupyter.

The data has several columns, including:

- RespondentID -- An anonymized ID of the person taking the survey.
- Gender -- Gender of the respondent.
- Age -- Age of the respondent.
- Household Income -- Income of the respondent.
- Education -- Education level of the respondent.
- Location (Census Region) -- Location of the respondent.
- Have you seen any of the 6 films in the Star Wars franchise? -- Yes or No response.
- Do you consider yourself to be a fan of the Star Wars film franchise? -- Yes or No response.

There are several other columns, which involve questions about the Star Wars movies. Some questions involved checkboxes, where someone was asked which of several options they liked, and to check all the ones they did like. This type of data is hard to represent in columnar format, and we'll be cleaning up the columns extensively in this project.
