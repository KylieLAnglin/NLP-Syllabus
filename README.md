# Natural Language Processing for Social Problems
Credit Hours: 3


Instructor: Kylie Anglin
 

# Course Description

The ability to efficiently analyze text data is a skill that is highly-desired in industry, non-profits, and the social sciences. When combined with domain-specific knowledge, Natural Language Processing (NLP) provides users with the ability to transform large-scale textual data into understanding: understanding about the people generating the text and their social contexts. Throughout the course, we will consider how NLP may be applied to generate insights in education, public policy, and psychology. Are students more likely to engage in critical thinking when working on an assignment alone or with a partner? How is the content of bi-partisan laws different from those passed on party lines? To what extent do therapists employ effective therapeutic practices? 

This course provides a theoretical and technical introduction to common methods and toolkits for NLP in the Python ecosystem. By the end of the course, you will have planned and implemented textual analysis projects in Python from beginning (collect text) to end (communicate new understandings). And, because replication is the "coin of the scientific realm (Loscalzo, 2012)", you will practice writing code that is organized, documented, and reproducible. 
 
# Course Learning Objectives

By the end of the course, you will...
* understand methods of structuring unstructured data
* connect text analysis methods to principles from another discipline
* communicate NLP findings, uncertainty, and assumptions
* use Python to process text, extract features, classify, and describe topics
* plan and implement multiple coding projects
* write code that is good for the long-term and for the community

# Course Resources

## Required Texts

* Bird, Steven, Ewan Klein, and Edward Loper. Natural Language Processing with Python. 

This book is a combination of an introductory NLP textbook and documentation for the NLTK library. Following the book will give you plenty of hands-on practice solving NLP problems using Python and NLTK. 

* Sarkar, D. (2016). Natural Language Processing with Python. 

This book provides practical applications using several NLP frameworks, including NLTK, spaCy, and Gensim. The book also provides a useful theoretical introduction to natural language concepts. By reading this book, you'll gain an understanding of the NLP landscape as it stands today.

Note: In addition to these texts, we will also read several articles applying NLP to the social sciences. See the course schedule for details. 

## Other Useful Resources

* Manning, Christopher D., and Hinrich. Schütze. (1999) Foundations of Statistical Natural Language Processing.
If you’d like to go more in depth on the theory of NLP, this book is the go-to. 

* Downey, Allen. (2015) Think Python. 
If you’d like a more thorough introduction to Python, I recommend Think Python. It provides concise course in the Python programming language, with an emphasis on good programming practices. This book is best for those with little programming experience.

* Dickson, Nate. (2019) Painless Git: A Sane Person’s Guide to Distributed Development. 
Want to learn more about Git? This is my favorite resource. 


# Assessments

## Individual, Partner, and Group Assignments (60%, 20% each)

Throughout the course, you will complete three longer-form coding projects: one on your own, one with a partner, and one in a group of four (20% each). These projects will ask you to generate insights from messy data, while maintaining a documented, version-controlled, organized, clean, and reproducible codebase. On each project, assessment will be broken into three pieces: project plan, code cleanliness and reproducibility, and a written report, each worth 5% with your highest grade of these assessments worth 10%. The group project will also include a presentation. 

### Individual Project: Psychology in Movie Discourse

Choose one finding from the psychology literature regarding word use and test whether this finding is also reflected in some manner in one or more movie scripts. For example, Kacewicz, Pennebaker, Davis, Jeon, & Graesser (2009) find that use of the first-person singular is a good predictor of social status. You might ask, do the children of The Incredibles use the first-person singular more than the adults? To answer your research question, you can choose script(s) from IMSDb. I will provide resources and guidance (including Python snippets you can use) to extract plain text from the website, segment the script, and delete narrator text. Note: If you have an idea of some other text data that you would like to explore, you are welcome to use that data for this assignment. See Tausczik and Pennebaker (2010) and Schwartz et al. (2013) for potential research questions.
Partner Project: Predicting Teacher Prompts for Textual Evidence
A key skill in elementary and middle school reading discussions is for students to "refer to details and examples in a text when explaining what the text says explicitly and when drawing inferences from the text (CCSS Grade 4)". You've been provided a set of transcriptions of teachers practicing leading reading discussions in a simulated classroom environment (with actors playing animated students). The transcripts are segmented by turns of talk and labelled as either "prompting for textual evidence" or not. Your task is to train a series of classifiers to identify teacher prompts for textual evidence. You should take two NLP approaches. In the first, you will extract the textual features and apply a naïve Bayes classifier. In the second, you will use a deep learning approach which does not require feature engineering. 

### Group Project: Topics in Education Reform

One important tool in education reform is the School Improvement Plan. You will be provided with a corpus of School Improvement Plans from across the state of Georgia. Within these plans, schools answer the following question: Provide a general description of the Title I instructional program being implemented at this Title I School. Specifically define the subject areas to be addressed and the instructional strategies/methodologies to be employed to address the identified needs of the most academically at-risk students in the school. Your task is to use topic modelling to gain a greater understanding of the school strategies employed to improve student learning. Note: If there is a different document which interests you (corporate responsibility statements, union contracts, news articles, etc.) you are welcome to use that data instead but will need to consider how you will collect your corpus. 
## In-Class Coding Assignments (15%)

For many course concepts, the best way to learn is to get hands-on practice. In-class coding assignments are designed to give you the opportunity to explore texts and Python libraries without worrying about messy data or managing a complicated code base (you'll practice those skills through individual, partner, and group projects). These assignments will mostly use tidy data and will be completed in Jupyter Notebooks. 

## Code Reviews (10%)

Seeing and engaging with others' work (and having your work engaged with) is one of the best ways to improve your coding skills. To that end, at three points during the semester, you will provide constructive feedback on the clarity and reproducibility of a peer's code. 


## Reading Checks (10%)

Every week, you will be given an out-of-class assignment based on the scheduled readings for the upcoming class period to help you more fully digest the readings and prepare for class. 

In-Class Participation and Reflections (5%)

At the end-of-class, I will commonly ask you to write a one-minute paper reflecting on the day's lessons. These are graded for completeness. 


# Course Calendar

A tentative schedule of topics, reading assignments, and due dates is shown below. Nothing will be due earlier than indicated but some things may be pushed back or eliminated altogether, depending on time. All changes will be announced in class and on the course website.

| Question                                                                                                      | Topics                                                                                                 | Pre-Readings                                                                                                                                  | Assignments                             |
|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------|
| How and why do we analyze language?                                                                           |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Linguistics, symbolism, Big Data for good                                                              |                                                                                                                                               |                                         |
| What can Python do for you?                                                                                   |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | A Whirlwind Tour of Python                                                                             | Sarkar, Ch 2                                                                                                                                  | In-Class Coding Assignment # 1          |
|                                                                                                               |                                                                                                        | Bird, Klein, & Loper, Ch 1                                                                                                                    |                                         |
|                                                                                                               | A Whirlwind Tour of Python, Cont.                                                                      | Bird, Klein, & Loper, Ch 3 & 4                                                                                                                | In-Class Coding Assignment # 2          |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
| What do the words that people use tell us about who they are, how they are doing, and what they are thinking? |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Dictionaries                                                                                           | Tausczik & Pennebaker (2010) The Psychological Meaning of Words: LIWC and Computerized Text Analysis Methods                                  |                                         |
|                                                                                                               | Dictionaries                                                                                           | Sarkar, Ch 3                                                                                                                                  | In-Class Coding Assignment # 3          |
|                                                                                                               |                                                                                                        | Young & Soroka (2012) Affective News: The Automated Coding of Sentiment in Political Texts                                                    |                                         |
| How can you be a force for replicable social science?                                                         |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Reproducible Research Practices                                                                        | Gentzkow & Shapiro. (2014) Code and Data for the Social Sciences                                                                              |                                         |
|                                                                                                               |                                                                                                        | Perkel. (2018) Git: The Reproducibility Tool Scientists Love to Hate                                                                          |                                         |
|                                                                                                               |                                                                                                        | https://learngitbranching.js.org/                                                                                                             |                                         |
| How do we structure unstructured information?                                                                 |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Feature Engineering                                                                                    | Sarkar, Ch 4                                                                                                                                  | DUE: Individual Project Plan            |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               |                                                                                                        |                                                                                                                                               | In-Class Coding Assignment # 4          |
|                                                                                                               | Feature Engineering                                                                                    | Grimmer & Stewart. (2013) Text as Data: The Promise and Pitfalls of Automatic Content                                                         |                                         |
|                                                                                                               |                                                                                                        | Analysis Methods for Political Texts                                                                                                          |                                         |
|                                                                                                               |                                                                                                        | Schwartz et al. (2013) Personality, Gender, and Age in the Language of Social Media                                                           |                                         |
|                                                                                                               | In-Class Work Time                                                                                     | Bird, Klein, & Loper, Ch 5                                                                                                                    |                                         |
| How do NLP methods help us conduct research at scale?                                                         |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Classification Models                                                                                  | Bird, Klein, & Loper, Ch 6                                                                                                                    | DUE: Individual Project Code and Report |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               |                                                                                                        |                                                                                                                                               | In-Class Coding Assignment # 5          |
|                                                                                                               | In-Class Code Review and Partner Revisions                                                             |                                                                                                                                               | DUE: Drafted Individual Project         |
|                                                                                                               | Python: Efficiency Tips and Tricks                                                                     |                                                                                                                                               | DUE: Final Individual Project           |
|                                                                                                               |                                                                                                        |                                                                                                                                               | In-Class Coding Assignment # 6          |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Classification Models                                                                                  | Sarkar, Ch 5                                                                                                                                  | DUE: Partner Project Plan               |
|                                                                                                               |                                                                                                        |                                                                                                                                               | In-Class Coding Assignment # 7          |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Advanced Classification Models                                                                         | https://jakevdp.github.io/PythonDataScienceHandbook/05.03-hyperparameters-and-model-validation.html                                           |                                         |
|                                                                                                               |                                                                                                        | Can et al. (2016) “It sounds like...”: A natural language processing approach to detecting counselor reflections in motivational interviewing |                                         |
|                                                                                                               | In-class Work Time                                                                                     | Gentzkow, Kelly, & Teddy. (2017) Text as Data (Economics)                                                                                     |                                         |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Advanced Feature Engineering                                                                           | Sarkar, Ch 8                                                                                                                                  |                                         |
|                                                                                                               |                                                                                                        | Manning & Schütze (1999) Linguistic Essentials                                                                                                |                                         |
|                                                                                                               | In-Class Code Review                                                                                   |                                                                                                                                               | DUE: Drafted Code for Partner Project   |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
| How can we use NLP to extract topics and themes from large amounts of text?                                   |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Topic Modelling                                                                                        | Sarkar, Ch 6                                                                                                                                  | In-Class Coding Assignment # 8          |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               | Topic Modelling                                                                                        | Sun et al. (2019) Using a Text-as-Data Approach to Understand Reform Processes: A Deep Exploration of School Improvement Strategies           | DUE: Partner Project Code and Report    |
|                                                                                                               | Topic Modelling                                                                                        | Wilkerson & Casas (2017) Large-Scale Computerized Text Analysis in Political Science: Opportunities and Challenges                            | In-Class Coding Assignment # 9          |
|                                                                                                               | Students Choice: Modern sentiment analysis, text similarity and clustering, or automated transcription |                                                                                                                                               |                                         |
|                                                                                                               | Class choice                                                                                           | Depends on topic choice                                                                                                                       | In-Class Coding Assignment # 10         |
|                                                                                                               |                                                                                                        |                                                                                                                                               |                                         |
|                                                                                                               |                                                                                                        |                                                                                                                                               | DUE: Group Project Plan                 |
|                                                                                                               |                                                                                                        | In-Class Work Time                                                                                                                            |                                         |
|                                                                                                               | Class choice                                                                                           | Depends on topic choice                                                                                                                       |                                         |
|                                                                                                               |                                                                                                        | In-Class Code Review                                                                                                                          | DUE: Drafted Group Code                 |
|                                                                                                               | Class choice                                                                                           | Depends on topic choice                                                                                                                       | In-Class Coding Assignment # 11         |
|                                                                                                               |                                                                                                        | Presentations                                                                                                                                 | DUE: Group Project Code and Report      |
|                                                                                                               |                                                                                                        | Presentations                                                                                                                                 |                                         |
|                                                                                                               |                                                                                                        | Course Review                                                                                                                                 | In-Class Coding Assignment # 12         |
|                                                                                                               |                                                                                                        | Course Review                                                                                                                                 |                                         |


# Expectations

You can expect me: 
* to start and end class on time 
* to respond to emails within 24 hours on weekdays, and by Monday evening if sent on the weekend 
* to be open to any discussion during office hours, and to be flexible when scheduling office hours 
* to design assignments that are aligned to course goals and which you can successfully complete with reasonable effort and resources 
* to be fair and objective when grading

I can expect you: 
* to come to class on time 
* to be attentive and engaged in class 
* to spend an adequate amount of time on out-of-class assignments 
* to seek help when appropriate, being prepared to discuss what you have tried

# Attendance

Because in-class time is an important part of course learning, regular attendance in all classes is required. To encourage your presence and active class participation, in-class assignments cannot be made-up outside of class. However, unforeseen events can and do occur. So, I will drop two missing in-class assignments, no questions asked. Although it is not required, most students send their professor a brief e-mail to explain their absence in advance. If you exceed two missed assignments, we can discuss which absences are excused. Absences traditionally excused are those that occur because of death in a student's family, important religious holidays, authorized University activities, sickness, and emergencies.

# Grading and Late Work

Assignments will be graded according to the following scale: A+ 97-100; A: 93-96; A-90-92; B+ 88-89; B: 83-87; B-: 80-82; C+: 78-79; C: 73-77; C-: 70-72; D+: 68-69; D: 63-67; D-: 60-62; F: < 60.
 
Each course assignment builds on the last, so it is important to complete all assignments on time. For this reason, a letter grade will be deducted for each day an out-of-class assignment is late (Note that in-class assignments cannot be submitted late. See the attendance policy.) Assignments more than 3 days late will not be accepted unless approved by the instructor in advance.

# Accessibility and Inclusion

This course is designed to be welcoming to and usable by everyone, including English language learners, students with disabilities, and students facing difficult out-of-class circumstances. I am committed to ensuring that each student has equal access to this course, and that the course builds off of each student’s unique set of strengths and abilities. If you have been approved for disability accommodations, please meet with me within the first two weeks of the term so we can develop an implementation plan together. It is important to meet as early in the term as possible; this will ensure that your accommodations are implemented early on. If you have accommodations for test-taking, please remember that arrangements must be made at least a week before the date of the test or exam. And, if at any time you encounter an aspect of the course that is not accessible to you, please let me know as soon as possible and we can consider solutions. 
 
 
 



