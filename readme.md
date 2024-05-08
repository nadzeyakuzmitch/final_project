## IS 219
## Nadzeya Kuzmitch
## User Management
# Course reflection

During the course of the class we’ve learned crucial industry practices for organizing the development process. We’ve covered important topics for an efficient collaborative flow for implementing programming projects. We’ve learned the following valuable skills:
1. Debugging and issues identification
2. Unit testing for supporting the functionality
3. CI/CD Workflows for continuous development, testing and deployment
4. Overall programming practicing, patterns and standards which are crucial for the modern development
As a result I was able to transform my knowledge of programming and development to adapt it for modern day professional workflow which will be very helpful during the job search.

# Final Project
[![Actions Status](https://github.com/nadzeyakuzmitch/final_project/workflows/CI%2FCD%20Pipeline/badge.svg)](https://github.com/nadzeyakuzmitch/final_project/actions)
This is a repository with the final project for our course. We were provided with the base app for user management and registration. During the work on the project I was thoroughly reviewing the code to identify issues for later fix, I was adding unit tests to improve the testing coverage and implemented new feature from the list of ideas.

As a feature I’ve selected to implement advanced user profile management. I’ve added API endpoints for updating user names, user bio, user professional status. I’ve also implemented functionality to notify user about the change via email.
[Here is the link for the pull request with the feature](https://github.com/nadzeyakuzmitch/final_project/pull/14)

Issues in the project varied from actual bugs that prevented app from functioning properly, as well as there where some things that could be improved for better functionality and also few development and testing issues. Here is the list of the issues I’ve addressed:

[Issue with duplicated login endpoint](https://github.com/nadzeyakuzmitch/final_project/issues/1)
[Populating fields for user response endpoint](https://github.com/nadzeyakuzmitch/final_project/issues/3)
[Issue with timing for user role logging](https://github.com/nadzeyakuzmitch/final_project/issues/5)
[Issue that sent email before actually creating the user](https://github.com/nadzeyakuzmitch/final_project/issues/7)
[Issue or improvement to check the length of the various user fields length](https://github.com/nadzeyakuzmitch/final_project/issues/9)
[Issue with running email tests on GitHub workflows:](https://github.com/nadzeyakuzmitch/final_project/issues/15)

I also added unit tests to improve coverage for the project, resolved issue as well as a new implemented feature. Here are some of them:
[Test 1](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L85)
[Test 2](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L97) 
[Test 3](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L134)
[Test 4](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L189)
[Test 5](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L197)
[Test 6](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L205)
[Test 7](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L213)
[Test 8](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L221)
[Test 9](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L229)
[Test 10](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_api/test_users_api.py#L237)
[Test 11](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_schemas/test_user_schemas.py#L52)
[Test 12](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_schemas/test_user_schemas.py#L70)
[Test 13](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_schemas/test_user_schemas.py#L110)
[Test 14](https://github.com/nadzeyakuzmitch/final_project/blob/0177292af16387c27339cccaad45abaf8bbad343/tests/test_schemas/test_user_schemas.py#L128)
