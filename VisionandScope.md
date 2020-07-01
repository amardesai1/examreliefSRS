# Vision and Scope for ExamRelief
## **Part 1: Business Requirements**
#### 1.1 Background

This project aims to create an app for Students to managing their mental health and deadlines in the run-up, and during, their exam periods. This product can provide help to a group of people very susceptible to mental health issues in times of high stress and pressure. A premium but low one-time charge for this app can keep it accessible to students and return the investment made to the project by sponsors. This money will also help developers and deployers maintain the app.

#### 1.2 Business Opportunity

Apps such as 'Mind' or 'Calm' offer extensive mental health management features to a wide audience of users such as guided meditation. However, the main shortcoming of this app is it's wide audience. Many users of these apps would benefit from having an experience personal to them, as mental health issues are very personal. The app would occupy a clear gap in the Mental Health app market as it specialises for students, but has a large audience nonetheless. Furthermore, University campus's offer easy ways to access and advertise to potential users. Students need help manging their stress, anxiety along with their workload. This app offers a way to somewhat alleviate or ease these issues.

#### 1.3 Business Objectives

|                          Financial                           |                        Non- Financial                        |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| Aim for 25,000 users within 3 months, 1% of the UK Student population | Aim for brand presence at 50 University Welcome Student unions within 3 Months |
| Aim for 120,000 users within 9 months, 5% of the UK Student population | Aim for 3.5* or above on the Google Play and Apple App Stores |
|      Achieve a 20% return on investment within 9 months      |  Aim for daily updates to recipe and exercise feed sections  |
|                                                              | Aim for bi-monthly updates of the app for bug fixing and feature improvements |
|                                                              | Aim for 6 months or high user retention, as this demonstrates use outside exam periods |

#### 1.4 Success metrics

###### Mid-project

- Initial set of features will be completed within its assigned sprint or the following sprint.
- Product champions will be involved at the end of Sprints to gain feedback on new features

###### Post-project

- We will see an increase in User retention from 2 weeks to several months
- Users feedback will be responded to, to push up App store scores
- The project will stick to its total budget of £50,000
- The project will be completed in no longer than 6 months
- The downloads will increase linearly by approximately 10,000 users each month after welcome week

#### 1.5 Vision statement

For Students who struggle with anxiety and/or stress during their exam periods or have issues managing their deadlines, ExamRelief is a mobile application that will provide services that assist students in the run up and during exam periods. Features include, study scheduling, deadline tracking, a feed or recipes, exercises and anxiety managing techniques. These techniques include guided meditation and grounding activities. This feed will be customizable and will refresh daily. The app will also include study tips such as advice for flashcards or past exam papers. Unlike current competitors such as Calm or Mind, our product is tailored towards students to give the audience a more tailored experience. The study aspect of our product aims to provide users with the tools to combat a significant source of student anxiety and stress. The mental health focus gives our product an edge above other study or exam apps.

#### 1.6 Business Risks

| Risks                   | Consequences                                                 | Contingencies                                           |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------- |
| Low initial downloads   | Less money to spend on maintenance and extra features        | Lowering cost at launch to attract high amount of users |
| High maintenance costs  | Lower profit in the long run. Could cause project failure over a long enough time period. | Offering premium features to increase revenue           |
| Low user retention rate | Reduces growth of users due to less referrals and lower reviews. | Focus on bug fixing and respond to user feedback        |

  

#### 1.7 Business Assumptions and Dependencies

- Student union presence is effective for gaining users.
  - If this is incorrect, user targets will not be met. May need to approach different forms of advertisement.
- Students see the 99p price as reasonable.
  - If incorrect, users targets wont be met. Price could be lowered or free and premium tiers could be explored.
- Growth in users in consistent month on month.
  - While growth may be exponential, it may also drop after launch. Advertising efforts may need to be increased, or other methods to grow users, such as referrals, may need to be explored.
- Users continue to use outside of exam periods
  - If incorrect, this could result in fluctuations in usage quarterly. This results in an unstable revenue stream. May need to focus on features attractive to users who aren't studying for exams.

## **Scope and Limitations**
#### 2.1 Major features

##### Target user - UK Students

##### Features:

- FR002&3 : A home screen with imminent deadlines and pinned items from the other 4 pages
- FR004: A deadline page which shows progress bars and countdowns of all deadlines
- FR006: A study planner page which shows study plan for the current week
- FR005&7: Forms for the two above pages to add deadlines or a study plan, respectively
- FR009: A modifiable feed of help tips, including stress and anxiety managing tips, recipes and exercise tips
- FR0010: A less frequently updated list of study techniques on the final screen.
- FR012: The Study list and health list will be refreshable to access new items from the server
- FR011: A menu bar for navigating these 5 screens
- NFR001 : A consistent UI should be used across the app to make use as easy as possible

#### 2.2 Scope of initial release

- The initial release of the product is aimed to release 2 months before the start of the University term in July.
- The initial release will be aimed at Students taking their first set of exams in December.
- Use storied used for this release will include; Students needing to record and track their deadlines and Users wanting to plan their subsequent week with a revision timetable.
- Use cases will include; adding a study activity to a certain date or time in the next week, and finding a healthy recipe on the health feed page.
- Initial target features includes; All 5 aforementioned pages. Basic functionality of deadline and study table screens, including presentations of study plan and deadlines and forms for setting these. Non-refreshable feed of some sample exercises and recipes. Small list of study activities.

#### 2.3 Scope of subsequent releases

- First Sprint after launch
  - NFR002: The study list should be updated weekly or biweekly
  - NFR003: The health feed of recipes, physical exercises and mental health exercises will be refreshed daily
- Third Sprint after launch
  - FR013: Any new slots added to the timetable will be able to be tagged with certain deadlines and certain study techniques from other pages.
  - FR015 Different countdown alerts should be able to be set in run up to deadline using form
- Fifth Sprint after Launch
  - FR017: Articles and posts from the feed will have a "save to phone" option for permanent storage or printing
  - FR016: Study calendar items will be able to be exported to 3rd party calendars such as Apple Calendar or Google calendar
- Seventh Sprint after launch
  - FR0014: Study timetable will allow import of University timetable calendar
    - Makes extra revision outside of exam periods easier to plan
    - Targets non-primary users

##### Feature tree for target software after 8 weeks
![](/assets/FeatureTree.png)

## **Business Context**
#### 3.1 Stakeholder profiles

|              | Major Value                           | Attitudes                                                    | Constraints                                                  |
| ------------ | ------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Students     | Better exam performance               | See app as tool to improve results while maintaining mental health | Must be low cost and run on most mobiles                     |
| Universities | Better results and healthier students | Boost in results is good PR, and could reduce surge in pressure on student services | Must be approved by university admin and mental health professionals |



#### 3.2 Project profiles

|          | Driver                                                       | Constraints                                                  | Freedom                                                      |
| -------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Features | Aiming for core features or more by initial release.         | Core features outlined in section 2.1 must be included for minimum working version. | Only core features need to be implemented for first full release, extension features aren't required. |
| Quality  | Stable second release before advertisement.                  | App must have gone through beta phase and been fixed before release. | No freedom. Lower stability will result in low user retention. |
| Schedule | Release 1.0 by July, release 1.1 by October.                 | First release must be completed by September, start of University term. | No flexibility. Software must be stable and released before it is the best time to advertise. |
| Cost     | Keep the cost strictly within budget.                        | Strict budget of £50000.                                     | Can get more investment, but this reduces profit in the long term. |
| People   | The app only needs a small team, with an adequate amount of time. | maximum team size is 3 developers + 2 tester.                | Team can be expanded as scope expands after the first few releases. |



#### 3.3 Deployment Consideration

- App will be deployed onto the Android google play store.
- Client computers will be mobile phones running Android Lollipop 5.0.0+.
- All users of initial release will be operating within the U.K. timezone.
- Userbase of initial release may be up to 10000.
- System must be able to cope with access at all hours.