# AI-Handwrite-Grader
The objective of this initiative is to assist educators in assessing their pupils' handwriting tasks with the aid of artificial intelligence. The notebook comes equipped with a pre-designed file for teachers to input their class roster and correct responses. Afterward, computer vision technology is utilized to examine the students' scanned assignments and generate a website for the instructor to record grades. Additionally, the notebook features post-analysis procedures to produce score reports and annotated scripts, and it also enables the option to send the grades back to the students via email. This tool can help reduce the amount of time teachers spend grading and deliver more precise and uniform evaluations.

## Template File
1. NamelistAndAnswerTemplate.xlsx - the template of your class name list and standard answers.
2. smtp-template.config - Rename it to smtp-template.config and provide the GMAIL SMTP Server information

## High level steps
1. Begin by forking this repository.
2. Create a CodeSpaces to work in.
3. Upload your scanned assignment or test scripts to the "data/" folder.
4. Fill in the name list and standard answer and upload to the same "data/" folder.
5. Run "question_annotations.ipynb" and highlight the position of each question.
6. Run "scoring_preprocessing.ipynb" to validate the ID and question, then generate the scoring website.
7. Start the web server and provide the score for each question.
8. Run "scoring_preprocessing.ipynb" to post-validate any missing questions.
9. Run "scoring_postprocessing.ipynb" to generate score reports and annotated scripts.
10. Finally, run "email_score.ipynb" to send the script back to the students.


## Demo and Explanation in Cantonese
[![Watch the video](https://img.youtube.com/vi/yhNc9sm9ks0/default.jpg)](https://youtu.be/yhNc9sm9ks0)
