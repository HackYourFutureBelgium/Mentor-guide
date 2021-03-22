# Homework Mentor

All our students hand in homework every week by using pull requests on GitHub. In order for the students to improve as much as possible we aim to review every pull request thoroughly. This review process imitates the real world and can really help the students to improve their skills significantly.

## Responsibility

As a Homework Helper it is your responsibility to review homework. It is also your responsibility that all the homework gets reviewed! It is not you that has to do all the reviewing, but you have the responsibility to make sure all submitted homeworks get a review. Normally the Homework Helper gets help from the Teacher Assistant and sometimes also the Main Teacher. If you need additional hands - some of our alumni can help out too.

## How students hand in homework

The students receive homework every Sunday and hand in homework using pull requests during the week. The process goes like this:

1. The students create a pull request \(PR\) on their `hyf-homework` repo, fx [https://github.com/panivita/hyf-homework](https://github.com/panivita/hyf-homework)
2. The PR now needs to be reviewed by a mentor. We always aim to get this done within 7 days of submission
3. When the review has been received the students need to make changes based on the feedback
4. When changes have been made they can merge their PR and they are now fully done with their homework

There is a [video here](https://www.youtube.com/watch?v=XYlgh9hSWtw) that explains and shows how it works. There is an extra step which is that the students also need to review another class members homework \(peer feedback\).

## How to find the right homework PR's

To keep track of the homeworks and their status \(mentioned above\) we have made a tool that makes this process easier: [https://hyf-homework-assesment.herokuapp.com/](https://hyf-homework-assesment.herokuapp.com/)

Here you can select the class number you are responsible for \(fx class 17\), then choose the module \(fx nodejs\) and then the status \(needs mentor feedback is the one you will be using\). Then you have an overview of all the students that still need feedback for a specific module. Then you can just go to their PR and give feedback there. The website updates the student homework status by itself. In the bottom of the website there is a description for the different statuses.

Every week our staff also tends to post an overview of all hoemwork PR's that need reviewing in the respective Slack channel for mentors in the class \(fx mentors-class17\). Use this space to communicate with the rest of the teacher team and staff about anything that might be unclear.

## Communication with HYF or Lead Teacher

It's quite important that you communicate with your teacher team and the staff. That could be if you get busy or something comes up that impedes your volunteering capacity. If you communicate with us then we can find another helper or get the other teachers to help out :\) Everyone gets busy sometimes, but it's really important that all students can get feedback in good time.

## Giving feedback

Give the review on the PR. You can see how to give feedback on a PR using github [here](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request). [Here is an example](https://github.com/sofiiadidovych/hyf-homework/pull/9) of some review given by mentor RassiBassi \(Rasmus\)

Try to keep the review at maximum 3 points the students can work on. There is no need to overdo it! Remember that you are responsible for up to 16 homeworks this week. Therefore try and manage your available time with the homeworks.

## Giving an overview of general misconceptions

It can be _super helpful_ for the Lead Teacher to get an overview of how the class is doing with the homework. So if you notice things that the class is collectively getting wrong - then make an overview of those misconceptions so they can be addressed in the next session.

Here is an **example** of a Homework Helper's overview of the class:

After following class14 homework for Javascript 1 - Week 2 here are some notes:

* Many students have a problem with understanding return at functions.
* The most difficult question for them was the fourth student manager
* Some students copied the other students' homework.
* Many students don't know that they can use &lt;= and &gt;= is available when they compare at if condition.
* There is still a problem with understanding the goal of functions. What is the function, why do we use it, and when?
* When I told students at the feedback that they can give the parameter at the function a default value at:

  function getFullname\(firstname, surname, useFormalName = false\) {

  I noticed confusion and difficulty understanding this.

* Using a lot of redundant `console.log` even if not mentioned in the question to log something. Also, I've seen at many homework that the return it like

  return console.log\(..\)

* Using unclear or non-expressive names for the variables like x, a and I have told them that it is preferable to use clear, meaningful names for variables and functions.
* At question 4 to check if the student exists or not. Very few were thinking of using includes of indexOf at the array. Many used complex loops to implement it.

  -There was no clear understanding of how to use codepen to test the code. \(edited\)

## Anything else?

If we left any questions unanswered - reach out to one of our staff on Slack :\)

