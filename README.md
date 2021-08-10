# Blockchain based Immutable Attendance Tracker POC
This is a POC project to demonstrate the immutable data recording capabilities of public blockchains.
visit the live version on https://blackcurrantapps.github.io/AttendanceTracker/

## Problem Statement
Have an immutable record of employees, queryable from frontend and polygonscan.
Checkin - Checkout employees and create logs.
Query attendance logs by employee id.

## Roles and Permissions
The contract is designed such that a whitelisted set of addresses have access to enter new data.
Only the owner can add new addresses to whitelist
Owner can also remove addresses from whitelist

## Deployment
Live version is deployed to the polygon mumbai testnet at https://mumbai.polygonscan.com/address/0xE8Be7162CA383Abe338A81e1e30f3b579E390580
