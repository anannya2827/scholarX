# Usability Testing Report



## 1. Project Overview

* **Application Name:** Expense Tracker Web Application

* **Objective:** Evaluate the user onboarding, authentication flow, and core data management features to ensure intuitive navigation and accessibility.




## 2. Methodology & Test Setup

* **Number of Participants:** 3 (Peers)

* **Testing Environment:** Laptop web browsers (Chrome)

* **Format:** Moderated, think-aloud sessions (in-person and remote)



### Core Tasks Tested:

1. **Account Registration:** Navigate to the registration page and successfully create a new user profile.

2. **Authentication:** Log out and successfully log back in using the newly created credentials.

3. **Core Feature Usage:** Add, categorize, and track a sample data entry (e.g., logging a daily expense).

4. **Dashboard Navigation:** Review the main dashboard interface and interpret summarized metrics or charts.





## 3. Executive Summary of Findings



### Success Metrics & Completion Rates

| Task | Success Rate | Avg. Time Taken | Difficulty Rating (1-5, 1=Easy) |

| :--- | :---: | :---: | :---: |

| Task 1: User Registration | 100% | 45 seconds | 1.2 |

| Task 2: Login Authentication | 100% | 20 seconds | 1.0 |

| Task 3: Managing Entries/Data | 66% | 90 seconds | 2.8 |

| Task 4: Dashboard Review | 100% | 30 seconds | 1.5 |



### Major Insights & Friction Points:

* **Friction Point 1 (Task 3):** Users occasionally hesitated when selecting categories from the dropdown menu, noting that the input labels could be more distinct.

* **Friction Point 2 (UI Layout):** On smaller laptop screens, some interface text fields required minor vertical scrolling, indicating a need for optimized responsive design constraints.



## 4. Actionable Recommendations & Next Steps



Based on user feedback, the following design and functional modifications will be implemented:

* **UI/UX Enhancement:** Increase the contrast of placeholder text inside form inputs to improve readability.

* **Responsive Styling:** Apply updated CSS media queries to ensure the dashboard fits perfectly within standard viewport heights without unexpected scrolling.

* **Error Handling:** Add immediate validation feedback messages if a user leaves a mandatory form field blank during registration.
