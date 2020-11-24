# Progressive Budget Trackers (Online/Offline Capability) 

## Overview

This application allows the user to track their finances through adding expenses and deposits to their budget with or without a connection. When entering transactions offline, the user can populate the total when brought back online.

## Details

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story

As an avid traveller, the user is able to track their budget throughout their trip. During a trip, the user will not consistently have access to the internet. This application allows the user to track withdrawals and deposits with or without a data/internet connection. When the user is reconnected, the offline content will populate and show an accurate account balance.

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.