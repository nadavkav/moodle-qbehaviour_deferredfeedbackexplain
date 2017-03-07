# Deferred feedback with explanation which mark only flagged question (question behaviour)


### Overview
A simple hack to get students answer X out of Y questions in a quiz, given they marked the relevant questions they choose 
to get a grade for with a flag.

 **Do note! quiz total sum of all question points/weights should exceed 100pt/%
          if all questions are flagged, so please advise students.**

### Setup
* Quiz settings: choose this question behaviour ('Deferred feedback, grade only flagged')
* Quiz settings: better hide all "Marks" under "Review options" from students as they do not show the proper filnal grades, but a confusing calculate which is good for a regular quiz without these hacking ;-)
* Quiz edit: make sure that "Maximum grade" and "Total of marks" as the same, and probably exceed 100 points 
  * Example1: For 2 out of 3 questions, where visual to the students max grade is 100, set each question to 50 (points/weight)
  * Example2: For 10 out of 12 questions, where visual to the students max grade is 100, set each question to 10 (points/weight)

    ### Feedback
    Most welcome :-)

## Still existing, original behaviour

This question behaviour is just like deferred feedback, but with an additional
text box where students can give a reason why they gave the answer they did.

No attempt is made to automatically grade the explanation, nor is it required.
However, it may be used in various ways, for example

1. The teacher may want to manually edit the grades where the student gave a wrong answer, to give partial credit if the student used the right method or approach.
2. The student might want to explain their thinking, so that later, when the results and feedback are revealed, they are reminded of what they were thinking at the time, and so can reflect more deeply.

## How to install

You can download the zip file from here:
https://github.com/nadavkav/moodle-qbehaviour_deferredfeedbackexplainonlyflagged/archive/only_flagged.zip
Unzip that, rename the folder to `deferredfeedbackexplainonlyflagged`, and copy it to be
`question/behaviour/deferredfeedbackexplainonlyflagged` in your Moodle instal.

Alternatively, you can install it using git. In the top of your Moodle instal
type:
```
git clone git://github.com/nadavkav/moodle-qbehaviour_deferredfeedbackexplainonlyflagged.git question/behaviour/deferredfeedbackexplainonlyflagged
echo '/question/behaviour/deferredfeedbackexplainonlyflagged/' >> .git/info/exclude
```

Once you have copied the files into place, visit **Site administration** ->
**Notifications** in your Moodle site to allow plugin to instal itself.

## Credit
This Moodle question behaviour was created by Tim Hunt (@timhunt), and current wip hacks by Nadav Kavalerchik
