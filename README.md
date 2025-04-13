## Urban Routes QA Testing Project

## Project Overview
The Urban Routes QA Testing Project is designed to ensure the quality and functionality of the route planning application. 
The application allows users to enter a departure point and destination, choose a preferred route mode (Optimal, Fastest, or Custom), and select different transport options such as walking, car, car-sharing, taxi, scooter, or bicycle. 

This testing project contains requirement analysis (decomposition of complex requirements into manageable atomic blocks), test planning, test case creation using fundamentals of test design (equivalence partitioning, boundary value analysis), environment setup, test execution, test closure, navigating the pages of a test plan.

## Testing Strategy

Testing was conducted using a structured approach:
Test Cases: Created and documented in Google Sheets, covering functional and boundary value tests.
Bug Tracking: While Jira was not required for this project, defects were noted in the test case documentation.
Techniques Used: Equivalence partitioning, boundary value analysis, and negative testing to validate input handling and error messages.

## Bug Summary

Major Issues Identified:
All valid addresses(except for suggested in layouts) incorrectly triggered error messages.

Key Learnings:
Effective boundary and negative testing improve the reliability of input validation
