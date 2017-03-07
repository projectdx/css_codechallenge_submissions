Renew Financial: css-code-challenge
=================================

Hi there! We're ecstatic that you're interested in working for Renew Financial's dev team. To get a better idea of your current development skills, we'd like for you to complete a code challenge - build one or more webpages according to a set of requirements. The actual business requirements are listed further down, but here are the general tech requirements:

1. Create one or more webpages.
1. Make sure your webpages render properly in Chrome and Firefox.
1. Do not require any for-pay software.
1. Include instructions for setting up and running your application locally.

We currently use Bootstrap, Foundation and a home-spun UI pattern library but you may use any libraries or frameworks you wish.

Feel free to email us at [devteam@renewfund.com](devteam@renewfund.com) if you have any questions.

## Submission Instructions

1. Clone this repository.
1. Create (and switch to) a new branch in your local repository:

 ```bash
 git checkout -b new-branch-name
 ```

1. Complete the project as described below within your local repository.
1. Create patches from your commits, and place them in a directory:

 ```bash
 git format-patch master -o submission_patches
 ```

1. Create a .zip file with the contents of the patches directory:

 ```bash
 zip -r submission_patches.zip submission_patches
 ```

1. Email the .zip file to [devteam@renewfund.com](devteam@renewfund.com), and put the position you are applying for in the email's subject.

If you have any questions about this submission process, feel free to email us.

#### Why can't I just fork, and submit a pull request?

Unfortunately, Github no longer allows you to fork a public repo and make it private, so your submission would be visible to the entire world. We'd love to keep this fair and not give the last responders a possible unfair advantage (since they'd be able to see all prior submissions); hence the patch method.

## Project Description

Renewable Funding has decided to enter the lucrative market of apparent-solar-time analysis.

We want a user to be able to use our site to view an engaging design representing the sunrise and sunset in Portland for:

1. The month of July 2017
1. The week of July 2, 2017
1. July 4, 2017

These times can be viewed at [sunrise/sunset](https://www.timeanddate.com/sun/usa/portland-or).

The design should:

1. make data easy to understand
1. be visually cohesive
1. be responsive (small and large viewports)
1. demonstrate well-structured CSS/SASS

It does not:

1. have to be dynamic (no API calls, user interactions, etc.)
1. have to be a single webpage

#### Bonus options:

1. effective use of css transitions to enhance the user experience
1. use of BEM notation
1. appropriate use of css precompiler (SASS/LESS) features (mixins, etc.)

## Evaluation

Reviewers will assess your familiarity with standard libraries and single-page app best practices.

1. Did your application fulfill the requirements?
1. Did you document the method for setting up and running your application?
1. Did you follow the instructions for submission?
