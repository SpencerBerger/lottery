This assignment is asking me to fix the record-keeping of lottery data in order to account for the different dates that new lottery numbers were introduced.

The intuitive way to do this is by setting a simple date limit.

When the dates are read from 'megamilllions.csv', I can add an 'if' statement to check if the date is after 2014, when the numbers 57-75 were introduced.

if (given date) is before (9 years from the most recent date)
    then skip this step.
If not, then copy the row.