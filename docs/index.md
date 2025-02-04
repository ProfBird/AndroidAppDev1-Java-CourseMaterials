# Android App Development with Java

# Course Outline


[Syllabus](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Syllabus.html)
<!--- [Useful Links](https://lcc-cit.github.io/CIS195-CourseMaterials/CIS195_References.html) -->

[Course Material Repository](https://github.com/ProfBird/AndroidAppDev1-Java-CourseMaterials)
[Example Code Repository](https://github.com/ProfBird/AndroidAppExamples-Java)  

Textbook: [*Murach's Android Programming*](https://www.murach.com/shop/murach-s-android-programming-2nd-edition-detail) 2nd Ed. by Joel Murach, 2015, Murach,  ISBN 978-1-890774-93-6

## Topics

1. [Intro to App Development](#1.-intro-to-app-development)
2. [Activity Lifecycle](#2.-activity-lifecycle)
3. [Menus and Themes](#3.-menus-and-themes)
4. [Multiscreen Apps](#4.-multiscreen-apps)
5. [Fragments](#5.-fragments)
6. [Asynch Tasks](#6.-asynch-tasks)
7. [List Views](#7.-list-views)
8. [SQLite Databases](#8.-sqlite-databases)
9. [Consuming Web Services](#9.-consuming-web-services)
10. [Geolocation](#10.-geolocation)



## 1. Intro to App Development

- Objectives
  - Understand mobile development issues
  - Install and use Android Studio
  - Build and run an app
    - Understand app project structure
    - UI: XML Layout files, ConstraintLayout, Widgets
    - Code: subclass Activity, override onCreate, use an event listener
    - Emulator: create and run an AVD
- Reading
  - Textbook Chapters 1–3
    (Selected parts of 3?)
  - Android vs. iOS market share
    - [Kantar World Panel--iOS vs  Android users](https://www.kantarworldpanel.com/global/smartphone-os-market-share/intro)
    - [Statista--iOS vs. Android market share](https://www.statista.com/statistics/266572/market-share-held-by-smartphone-platforms-in-the-united-states/)
  - UI Layout
    - [Building a Responsive UI with ConstraintLayout](https://developer.android.com/training/constraint-layout/index.html)
  - Java programming
    - [Official Java Tutorials](https://docs.oracle.com/javase/tutorial/)
    - [Inheritance](https://docs.oracle.com/javase/tutorial/java/IandI/subclasses.html)
      - [Overriding base class methods](https://docs.oracle.com/javase/tutorial/java/IandI/override.html)
      - [Interfaces](https://docs.oracle.com/javase/tutorial/java/IandI/createinterface.html)
- Slides
  - [Intro to Mobile App Development](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Slides/1-Intro-1-Intro.pptx)
  - [Your First App: Creating the UI](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Slides/1-Intro-1-FirstApp.pptx)
  - [Your First App: Writing the Code](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Slides/1-Intro-3-FirstAppCode.pptx)
- Examples
  - [Rock, Paper, Scissors Game—Single Activity](https://github.com/ProfBird/AndroidAppExamples-Java/tree/master/RockPaperScissors-SingleActivity)
- Lab Assignment
  Click counter—a single activity app
  - [Lab 1: Instructions](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Labs/Lab01/Lab1Instructions-ClickCounter.html)
  - [Lab 1 Rubric](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Labs/Lab01/Lab1Rubric.html)

## 2. Activity Lifecycle

- Objectives
  - Understand the activity lifecycle
  - Save activity state: shared preferences, onSaveInstanceState
  - Test effectively
    - What to test: UI, functionality, exception handling (invalid input)
    - What to test on: Across required APIs and screens
  - Debug efficiently: Breakpoints, LogCat, Toasts
- Reading
  - Selected parts of Ch. 3 (lifecycle)?
  - Chapter 4: How to Test and Debug an Android App
- Slides
  - [Your First App: Lifecycle and More](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Slides/1-Intro-4-FirstAppCode+More.pptx)
  - [Your First App: Debugging](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Slides/1-Intro-5-Debugging.pptx)
- Lab Assignment
Single screen Pig game with just a portrait layout
  - [Lab 2 Instructions](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Labs/Lab02/Lab2Instructions.pdf)
  - Dice images to use in the game:  [DieImages.zip](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Labs/Lab02/DieImages.zip)
  - Example of a finished Pig game: [zipped pig game apk](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Labs/Lab02/pig-v1-release-5-apk.zip)  
    Download this file, unzip it, then drag and drop the apk file onto your emulator to install it.
  - [Lab 2 Rubric](https://profbird.github.io/AndroidAppDev1-Java-CourseMaterials/Labs/Lab02/Lab2Rubric.docx)

## 3. Menus and Themes

- Textbook
- Carey, Tutorial 2: Developing a Web Site
- Lecture Notes
- Example
- Lab Assignment

## 4. Multiscreen Apps

- Textbook

- - Carey, Tutorial 3: Designing a Web Page with CSS

- Lecture Notes

- - [Styling with CSS](https://lcc-cit.github.io/CIS195-CourseMaterials//LessonPlans/CIS195-LP-W04-D1-StylingWithCSS.html)
  - [Text Formatting, PseudoClasses](https://lcc-cit.github.io/CIS195-CourseMaterials//LessonPlans/CIS195-LP-W04-D2-TextFormatting+PseudoClasses.html)

- Example

- - [Guide to South India](https://lcc-cit.github.io/CIS195-Demos/Unit03/Finished/Index.htm)

- Lab Assignment

- - [Lab 4 Instructions](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab04/Lab4Instructions_W18.pdf)
  - [Lab 4 Rubric](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab04/Lab4Rubric_CS195.html)

## 5. Fragments

- Lecture Notes

- - [Publishing to a Web Server, Review](https://lcc-cit.github.io/CIS195-CourseMaterials/LessonPlans/CIS195-LP-W05-D1-UploadToWebServer+Review)
  - [How to upload your site to citstudent](https://lcc-cit.github.io/CIS195-CourseMaterials/Lessons/UploadingWebSites.html)

## 6. Getting Data from the Internet

(Reading XML files + Asynch Tasks)

- Textbook

- - Carey, Tutorial 4: Creating Page Layouts with CSS

- Lecture Notes

- - [CSS Layout, Float Property](https://lcc-cit.github.io/CIS195-CourseMaterials/LessonPlans/CIS195-LP-W06-D1-CssLayout-Float)
  - [CSS Box Model, Positioining](https://lcc-cit.github.io/CIS195-CourseMaterials/CIS195-LP-W06-D2-CssLayout-BoxModel+Position)

- Example

- - [Guide to South India](https://lcc-cit.github.io/CIS195-Demos/Unit04/Finished/Index.htm)
  - [Float Demo](https://lcc-cit.github.io/CIS195-Demos/Unit04/floatDemo.htm)

- Exercise

- - [CSS *f**loat* and *c**lear* Properties](https://lcc-cit.github.io/CIS195-CourseMaterials/Lessons/Unit04/cssFloat.html)

- Lab Assignment

- - [Lab 5 Instructions](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab05/Lab5Instructions.pdf)
  - [Lab 5 Rubric](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab05/Lab05Rubric.html)

## 7. List Views

- Textbook

- - Carey, Tutorial 5: Working with Tables and Columns

- Lecture Notes

- - [Tables](https://lcc-cit.github.io/CIS195-CourseMaterials/LessonPlans/CIS195-LP-W07-D1-Tables.html)

- Example

- - [Table Practice](https://lcc-cit.github.io/CIS195-Demos/Week5/TablePractice.html)

- Lab Assignment

- - [Lab 6 Instructions](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab06/Lab6Instructions.pdf)
  - [Lab 6 Rubric](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab06/Lab06Rubric.html)

## 8. SQLite Databases

- Textbook

- - Carey, Tutorial 6: Creating a Web Form

- Lecture Notes

- - https://lcc-cit.github.io/CIS195-CourseMaterials/LessonPlans/CIS195-LP-W08-D2-Forms.html)
  
- Lab Assignment


## 9. Consuming Web Services

- Textbook

- - Carey, Tutorial 7: Designing a Multimedia Web Site

- Lecture Notes

- - [Audio and Video for Web Sites](https://lcc-cit.github.io/CIS195-CourseMaterials/LessonPlans/CIS195-LP-W09-D1-Audio+Video.html)
  - [Embedding Multimedia Objects](https://lcc-cit.github.io/CIS195-CourseMaterials/LessonPlans/CIS195-LP-W09-D2-MultimediaObjects.html)

- Lab Assignment

- - [Lab 8 Instructions](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab08/Lab8Instructions.pdf)
  - [Lab 8 Rubric](https://lcc-cit.github.io/CIS195-CourseMaterials/LabStarters/Lab08/Lab08Rubric.html)

## 10. Geolocation

- Lecture Notes

- - [TBD](https://lcc-cit.github.io/CIS195-CourseMaterials/LessonPlans/CIS195-LP-W01-D1-IntroToCourse.html)

- Term Project Assignment

- - [Term Project Instructions](https://lcc-cit.github.io/CIS195-CourseMaterials/TermProject/CIS195TermProject.pdf)
  - [Term Project Code Review Form](https://lcc-cit.github.io/CIS195-CourseMaterials/TermProject/TermProjectCodeReview.docx)

## 

Written by [Brian Bird](https://profbird.online), summer 2019.