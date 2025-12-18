![QA Portfolio](https://img.shields.io/badge/QA%20Portfolio-SauceDemo-blue)

# QA Portfolio: SauceDemo Web App

This repository contains a QA portfolio project focused on testing the [SauceDemo web app](https://www.saucedemo.com). The project demonstrates test planning, test case design, and bug reporting for a functional e-commerce workflow.

## Goals
- Showcase QA skills, including exploratory testing, test case creation, and bug reporting
- Practice identifying edge cases and negative scenarios
- Lay the foundation for future test automation

## Scope
- Functional testing of core user flows (login, cart, checkout)
- Negative and edge-case testing
- Documentation of test artifacts including test cases and bug reports

## Tools & Technologies
- Manual testing
- Browser Developer Tools
- Git for version control

## Project Structure
- `test_cases/` – Contains login and cart test case files
- `bugs/` – Contains individual bug reports in markdown format
- `screenshots/` – Contains screenshots and other attachments for bug documentation
- `README.md` – Project overview and instructions

## Test Execution Summary

| Area Tested | Test Cases | Passed | Failed | Related Bugs |
|------------|------------|--------|--------|--------------|
| Login      | 6          | 2      | 4      | BUG-001, BUG-003, BUG-004 |
| Cart       | 5          | 2      | 3      | BUG-002, BUG-005 |
| **Total**  | **11**     | **4**  | **7**  | **5 Bugs Logged** |

### Notes
- Test cases were executed manually against the SauceDemo web application
- Failed tests correspond to documented defects in the `/bugs` directory
- SauceDemo is a known demo application containing intentional defects for testing practice
- Passed test cases met expected behavior and revealed no defects during execution

## How to Review This Project
1. Read the test plan
2. Explore test cases by feature
3. View bug reports with screenshots

## Future Improvements
1. Automation scripts
2. Frameworks