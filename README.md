# Modanisa-Bootcamp-Assignments

## [Week 1 : FrontEnd / HTML - CSS - Javascript](https://github.com/152-Modanisa-FullStack-Bootcamp/week-1-assignment-nidadinch)

Project has 3 different braches with 3 different applications.

#### Login Page

![LoginPage](https://github.com/nidadinch/Modanisa-Bootcamp-Assignments/blob/37d08dfefb3501f3d4dd930cfd5f40301904accf/images/week-1-loginpage.png)

#### Linkedin Post

![LinkedinPost](https://github.com/nidadinch/Modanisa-Bootcamp-Assignments/blob/ceb3e3463c0194ff8fdabc296210ca46cea209ae/images/week-1-linkedinpost.png)

#### JS Practice

Get data from API and manipulate it using Axios

## [Week 2 : FrontEnd / Vue.js](https://github.com/152-Modanisa-FullStack-Bootcamp/week-2-assignment-nidadinch)

An application similiar to Youtube that can user add a video to favorites using Vue, Axios, Vuex, Router. Application has 3 pages, main page, favorites & watch.

![VideoSiteProject](https://github.com/nidadinch/Modanisa-Bootcamp-Assignments/blob/37d08dfefb3501f3d4dd930cfd5f40301904accf/images/week-2-youtube.png)

## [Week 3 : TDD / Unit Tests with Jest](https://github.com/152-Modanisa-FullStack-Bootcamp/week-3-assignment-nidadinch)

Unit tests using Jest for simple daily corona cases in Turkey app.

![CoronaCasesProject](https://github.com/nidadinch/Modanisa-Bootcamp-Assignments/blob/6fe4eb474aa3ee3b6f20c6bb2c2b8681f47c7130/images/week-3-dailycoronacases.png)

## [Week 4 : TDD / Acceptance Tests](https://github.com/152-Modanisa-FullStack-Bootcamp/week-4-assignment-nidadinch)

ATDD cycle video site project. Unit tests has been written for video site Vue project using Jest and acceptance tests has been written using Cucumber, Puppeteer & Pact. Pact is a code-first tool for testing HTTP and message integrations using contract tests.

```gherkin
Feature: Video Site Project
  As Product Owner I want to surf on our video site project

  Scenario: User should see some videos on main page
    Given that User goes to Video Site Project's HomePage
    When page is loaded
    Then User can see some of videos' title like
      | Vue.js Course for Beginners [2021 Tutorial] |
      | Vue JS Crash Course                         |
      | ue 3 - What's New? What Changed?            |

  Scenario: User should navigate to watch page on click to video
    Given that User is on Video Site Project's HomePage
    When User clicks "Vue JS Crash Course" video
    Then User should see watch url correctly

  Scenario: User should see video image change on hover
    Given that User is on Video Site Project's HomePage
    When User hovers "Vue.js Explained in 100 Seconds" video
    Then User should see hovered image
```
