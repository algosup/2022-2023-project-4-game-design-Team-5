# Test Plan

## Introduction

The purpose of this test plan is to ensure the quality of the game "Dextrose" developed on Unreal Engine 4.
The testing team includes the Quality Assurance team and developers.
The testing methodology used is the Agile Scrum approach.

## Scope

The game's features and functionalities to be tested include:
- Gameplay mechanics, such as movement, and level progression
- UI/UX elements, such as menus, HUD, and tutorial screens
- Compatibility with hardware and software, including Windows and macOS operating systems
The testing environment includes:
- A minimum of 4GB RAM
- Windows 8 or above or/ macOS 10.14 or above

## Test Strategy

The testing approach includes functional, performance, and security testing (especially crash).
The testing team will use the Unreal Engine 4 built-in testing tools along with external tools such as other recommended tools listed in the [official Unreal Engine 4.27 documentation](https://docs.unrealengine.com/4.27/en-US/TestingAndOptimization/) to support testing.

The roles and responsibilities of the testing team are defined as follows:
- Quality Assurance team: responsible for executing test cases and reporting defects
- Developers: responsible for fixing defects and performing regression testing

## Test Cases

Test cases will be defined and executed for the following areas:
- Movement and dealing with mechanics
- Level progression
- UI/UX elements, including menus and HUD
- Compatibility with Windows and macOS operating systems

Each test case will include detailed steps and expected results, along with any acceptance criteria or pass/fail thresholds.

## Test Data

The test data for the game will consist of a variety of scenarios to ensure comprehensive testing. This includes, but is not limited to:

- User input data for various game mechanics
- Data for different game levels and environments
- All test data will not contain any personally identifiable information. The test data will be reviewed and approved by the QA team prior to use to ensure its relevance and accuracy.

## Test Execution

The testing will be conducted in the following phases:
- Functional testing: QA team will perform functional testing to ensure the game mechanics and features are working as expected.
- Regression testing: After each iteration, the QA team will perform regression testing to ensure no new defects have been introduced and that previously fixed defects have not resurfaced.
- Performance testing: QA team will perform performance testing to ensure the game performs smoothly under various loads and conditions.
- User Acceptance testing (UAT): The game should be tested by end-users to ensure it meets their expectations and requirements.

Testing will be conducted on PC, and on a variety of hardware configurations. The testing team will use a combination of manual and automated testing methods.

## Test Reporting

The QA team will use Github Issue to report on the testing progress and results, and provide reports to the project stakeholders. The following information will included in each issue:

- Defect reports: A description of each defect found during testing, including severity and priority levels, steps to reproduce, and any relevant screenshots or videos.
- Status of testing: A summary of the progress of testing against the project timeline, including any delays or risks identified.
- Summary of test results: A summary of the overall test results, including any recommendations for improvements or areas that require further testing.

Each Github Issue will be tagged with appropriate labels, such as "bug", "enhancement", or "performance", to allow for easy categorization and sorting. The QA team will also use Github's @mention feature to notify relevant stakeholders of issues that require their attention.

You can find the *Test Database* and bug report [here](https://github.com/algosup/2022-2023-project-4-game-design-Team-5/issues?q=is%3Aissue+label%3Abug).

## Risks and Mitigation

Potential risks associated with testing the game include:

- Testing environment and hardware issues
- Data corruption or loss
- Lack of testing resources
- Delays in testing and bug fixing

To mitigate these risks, the QA team will:

- Regularly review the testing environment and hardware to ensure it is optimal for testing
- Implement backup and recovery measures to prevent data loss or corruption
- Regularly monitor and adjust the testing resources as necessary
- Continuously communicate and collaborate with the development team to identify and address potential delays in testing and bug fixing.

## Sign-Off

The game will be considered ready for release when the following criteria are met:

- All critical and high-severity defects have been resolved
- The game has passed user acceptance testing
- The game meets all functional and performance requirements
- The game has been approved by all relevant stakeholders

Once these criteria are met, the QA team will provide a sign-off on the game's readiness for release.

## Glossary

Agile scrum methodology: is a project management system that relies on incremental development. Each iteration consists of delimited periods of sprints, where the goal of each sprint is to build the most important features first and come out with a Potentially Shippable Product.
