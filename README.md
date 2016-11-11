# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
x Post -> date:date rationale:text
x User -> Devise
x AdminUser -> STI
x Auditlog

## Features:
x Approval Workflow
x SMS Sending -> link to approval or overtime input
x Administrate admin dashboard
x Block non admin and guest users
x Email summary to managers for approval
x Needs to be documented if employee did not log overtime
x Create audit log for each text message
x Need to update end date when confirmed
x Need to update audit log status when an overtime request is denied
x Update buttons on employee homepage so they show on mobile
x Update buttons to include time span
- Update button sort order on homepage
- Remove "entries" and "Request overtime" buttons for managers.
- Fix a bug in admin dashboard. I think this should be more a configuration setting we need to update.
- Implement honeybadger for error reporting
- Implement new relic for keeping the site alive
- Check on data issue and make sure correct hours are being tracked

## TODOS:
