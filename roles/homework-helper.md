# Homework helper

All our students hand in homework every week. In order for the students to improve all homeworks gets a review. This review can really help the students improve their skills.

## Responsibility

As a homework helper it is your responsibility to review homework. It is also your responsibility that all the homework gets reviewed! It is not you that has to do all the reviewing, but you have the responsibility do review all homeworks. Normally the homework helper gets help from the teacher assistant and sometimes also the main teacher or maybe someone from alumni.

## How students hand in homework

The students hand in homework using pull requests. The process goes like this:

1. The students create a pull request (PR) on their `hyf-homework` repo, fx https://github.com/panivita/hyf-homework
2. The PR now needs to be reviewed by a mentor
3. When the review has been received the students need to make changes based on the feedback
4. When changes has been made they can merge their PR and they are now fully done with their homework

There is a [video here](https://www.youtube.com/watch?v=XYlgh9hSWtw) that explains and shows how it works. There is an extra step which is that the students also need to review another class members homework.

## Homework assesment tool

To keep track of the homeworks and their status (mentioned above) we have made a tool that makes this process easier: https://hyf-homework-assesment.herokuapp.com/

Here you can select the class number you are responsible for (fx class 17), then choose the module (fx nodejs) and then the status (needs mentor feedback is the one you will be using). Then you have an overview of all the students that still need feedback for a specific module. Then you can just go to their PR and give feedback there. The website updates the student homework status by itself. In the bottom of the website there is a description for the different statuses

## Communication with HYF or lead teacher

It's quite important that you communicate with us. That could be if you get busy or something comes up. If you communicate with us then we can find another helper or get the other teachers to help :)

## Giving feedback

Give the review on the PR. You can see how to give feedback on a PR using github [here](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request). [Here is an example](https://github.com/sofiiadidovych/hyf-homework/pull/9) of some review given by mentor RassiBassi (Rasmus)

Try to keep the review at maximum 3 points the students can work on. There is no need to overdo it! Remember that you are responsible for 16 homeworks this week. Therefore try and adjust your available time with the homeworks.

## Giving an overview of general misconceptions

It can be super helpful for the lead teacher to get an over of how the class is doing with the homework. So if you notice things the class in general is struggling with the make an overview of those misconceptions

Here is an example of a homework helpers overview of the class:

After following class 14 homework for javascript 1 week 2 here are some notes:

- Many students have a problem with understanding return at functions.
- The most difficult question for them was the fourth student manager
- Some students copied the other students' homework.
- Many students don't know that they can use <= and >= is available when they compare at if condition.
- There is still a problem with understanding the goal of functions. What is the function, why do we use it, and when?
- When I told students at the feedback that they can give the parameter at the function a default value at:
  function getFullname(firstname, surname, useFormalName = false) {
  I noticed confusion and difficulty understanding this.
- Using a lot of redundant `console.log` even if not mentioned in the question to log something. Also, I've seen at many homework that the return it like
  return console.log(..)
- Using unclear or non-expressive names for the variables like x, a and I have told them that it is preferable to use clear, meaningful names for variables and functions.
- At question 4 to check if the student exists or not. Very few were thinking of using includes of indexOf at the array. Many used complex loops to implement it.
  -There was no clear understanding of how to use codepen to test the code. (edited)
