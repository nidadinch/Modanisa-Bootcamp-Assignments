# Modanisa-Bootcamp-Assignments

## [Week 1 : FrontEnd / HTML - CSS - Javascript](https://github.com/152-Modanisa-FullStack-Bootcamp/week-1-assignment-nidadinch)

Project has 3 different braches with 3 different applications.

#### Login Page

#### Linkedin Post

#### JS Practice

Get data from API and manipulate it using Axios

## [Week 2 : FrontEnd / Vue.js](https://github.com/152-Modanisa-FullStack-Bootcamp/week-2-assignment-nidadinch)

An application similiar to Youtube that can user add a video to favorites using Vue, Axios, Vuex, Router. Application has 3 pages, main page, favorites & watch.

## [Week 3 : TDD / Unit Tests with Jest](https://github.com/152-Modanisa-FullStack-Bootcamp/week-3-assignment-nidadinch)

Unit tests using Jest

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
