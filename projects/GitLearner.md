---
title: Sprint 4 GitLearner
layout: page
---

# 🎄 GitLearner

![main](https://i.imgur.com/8cVL1Pm.jpg)

A CLI app to make you learn Git in a playful way! 
Stop making resolutions, start making them true!

## 🎁 History behind

![team](https://i.imgur.com/agzEEh2.jpg)

Santa Claus teams have a lot to take care of to make Christmas awesome. 
His teams started using Git to make work easier for everyone. 
Santa needs your help in order to be set on time.

## ⛄ Find out more
Find more on https://git-learner.netlify.app/

## 🎅 Get it

Clone this repository by running the following command inside your terminal:

```sh
git clone https://github.com/MLH-Fellowship/Git-learn.git
```

## 💻 How it works

![example1](https://i.imgur.com/d6qDjly.png)


Starting point of the application - `lessonManager.js`. Start it with `node .` or `node lessonManager.js`.  Lessons are organized into separate files and imported into `lessonManager`. `lessonManager` repeatedly prints a list of available lessons, checks for user input and starts the lesson user selected. Example is present in `fillEmail` file.

### 📑 Lesson format:

![example2](https://i.imgur.com/24eEqxr.png)

In order to be compatible with `lessonManager`, you have to create an object with string field `description` and `startLesson` method, and append it to `lessons` global variable in `lessonManager.js`.
`description` is used when printing a list of lessons, and `startLesson` is invoked when user selects lesson by printing corresponging number.


### 📝 TODO
Implement a possibility to install it globally, making it invokable with `lessonManager`, not `node lessonManager`.
