# Tracker App

## Key requirement: company needs documentation that salaried employees did or dit not get overtime each week

## Models:
  - Post -> date:date rational:text
  - User -> Devise
  - AdminUser -> STI

## Features:
  - Approval Workflow
  - SMS Sending -> link to approval or overtime input
  - Administrate admin dashboard
  - Email summary to manage for Approval
  - Need to be documented if employee did not log overtime

## UI:
  - Bootstrap -> Formatting
## Refactor TODOS
  - Add full_name method for users
  - Refactor user Association integration test in post_spec
