---
# Do not edit the text between these lines!
layout: default
---

# {{ site.title }}

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="{{ '/static/imgs/selfie.png' | relative_url }}" alt="Image of Matt and Will. "  width="250"/>

By: Will & Matt

## About This Project

{{ site.description }}

## Question & Available Data

Our idea was that the course should include more interactive questions in class (ie poll questions) to keep the lessons more engaging because students get distracted sometimes by doing work in lecture and polls would keep them more engaged. The specific stakeholders which would benefit is the lecturers because they could guarantee more student engagement.

The data suited this question because we could compare the lesson ratings compared to other aspects of the course, as well as analyze what opinions students had overall about the course to determine if there was an engagement issue.

## Method

We used Python to create a table of the aspects students rated in the survey which we considered to be important to our analysis. The table can be seen below:

<img src="{{ '/static/imgs/table.png' | relative_url }}" alt="Table of survey data" width="500"/>

Next, we created two charts to compare the aspects we were looking at. The first one compared how students rated different aspects of the class, such as quizzes, assignments, and lessons. The chart can be seen below:

<img src="{{ '/static/imgs/components.png' | relative_url }}" alt="Chart comparing class aspects" width="500"/>

The other chart compared the average rating of lessons to how students rated their feelings about the class on categories such as interest level, effectiveness, and value. The chart can be seen below:

<img src="{{ '/static/imgs/experience.png' | relative_url }}" alt="Chart of student opinions" width="500"/>

As seen in the table/charts, both lesson and interest ratings ranked near the bottom of their respective categories.

## Analysis

The data supported our idea of adding poll questions to lessons to increase engagement. First off, 'lessons' was the second lowest average rated category of the aspects of the class behind 'lesson questions'. This demonstrates how lessons are one of the biggest potential areas of improvement in the class. Secondly, of the opinions of aspects on the course, students rated the 'interesting' category lowest on average. This demonstrates how an improvement in the class' engagement levels is the biggest gap to address in the overall class experience.

## Enhancements

Rather than simple multiple choice polls, use them as a collaboration opportunity. Make a poll, have people answer, then have them work with a neighbor and redo the poll to see how answers change. You can also use the polls as a decision point for lectures. For example, if >80% answer correctly, spend less time on this topic, otherwise spend more time. This is a great way to make sure lecture is focused on the most important things without needing a quiz or a pre-class activity to assess knowledge levels.

## Tradeoffs

The biggest tradeoff is time, since each poll can take up to 3-5 minutes which adds up quickly in an hour class period. It also requires careful design from the instructor to make sure that a: the questions are effective and b: they are designed in a way which prevents students simply answering performatively. The stakeholder in this is mainly the instructor, since the polls can provide valuable real time information about the students but also require time and careful design which takes away from other aspects of the lecture. However, with careful design, this can be mitigated as it is an effective way to keep students engaged. Another stakeholder is the students, but this would mainly be a benefit because it would increase interest levels in lecture as reflected by the data.

## Conclusion

Overall, the data supported our idea to add polls to lecture to increase engagement because both lessons and interest levels ranked low compared to other categories, and live polls are a good way to increase class engagement, thus increasing interest levels and raising lesson ratings.
