*Skylab Coders - BootCamp Summer 2016*

# Exercises Javascript

Some exercises to practice
**Date Javascript**

---

## Dates
Write a JavaScript function to check whether an `input` is a date object or not

    console.log(is_date("October 13, 2014 11:13:00")); // false 
    console.log(is_date(new Date(86400000))); // true

## Current Date
Write a JavaScript function to get the current date
Hint: *Pass a separator as an argument.*
    
    console.log(curday('/')); // "11/13/2014" 

## Get Days
Write a JavaScript function to get the number of days in a month.

    console.log(getDaysInMonth(1, 2012)); // 31

## Get Month
Write a JavaScript function to get the month name from a particular date

    console.log(month_name(new Date("10/11/2009"))); // October

## Compare
Write a JavaScript function to compare dates 

## Add Minutes
Write a JavaScript function to add specified minutes to a Date object

    console.log(add_minutes(new Date(2014,10,2), 30).toString()); // "Sun Nov 02 2014 00:30:00 GMT+0530 (India Standard Time)"

## Weekend
Write a JavaScript function to test whether a date is a weekend.

    console.log(is_weekend('Nov 15, 2014')); // Is Weekend

## Days between two dates
Write a JavaScript function to get difference between two dates in days.

    console.log(date_diff_indays('04/02/2014', '11/04/2014')); // 216

## Last Day
Write a JavaScript function to get the last day of a month.

    console.log(lastday(2014,11)); // 31

## Yesterday
Write a JavaScript function to calculate **'yesterday day'**.
Hint: *(dt.getDate()-1) can be used...*

    console.log(yesterday('Nov 15, 2014')); // "Fri Nov 14 2014 00:00:00 GMT+0100 (CET)"

## Maximum date
Write a JavaScript function to get the maximum date from an array of dates.

## Minimum date
Write a JavaScript function to get the minimum date from an array of dates.

## Minutes to hours 
Write a JavaScript function that will return the number of minutes in hours and minutes.

    console.log(timeConvert(200)); // 200 minutes = 3 hour(s) and 20 minute(s).

## Get days in year
Write a JavaScript function to get the amount of days of a year.
    
    days_of(2015); = //365

## Quarter of the year
Write a JavaScript function to get the quarter (1 to 4) of the year. 

## Count from beginnning of the year
Write a JavaScript function to count the number of days passed **since beginning** of the year
    
    Hint: new Date(dt.getFullYear(), 0, 1); can be used

## How many years?
Write a JavaScript program to calculate age.

    Hint: Date.now() - dob.getTime(); 

## Day of the month
Write a JavaScript function to get the day of the month, 2 digits with leading zeros.

    console.log(day_of_the_month(d)); // 06;

## Sun, Mon, Tue, Wed, Thu, Fri, Sat
Write a JavaScript function to get a textual representation of a day (three letters, Mon through Sun)

    dt = new Date(2015, 10, 1); 
    console.log(short_Days(dt));
    // "Sun"

## Like previous exercise, long version of the names.
Write a JavaScript function to get a full textual representation of the day of the week **(Sunday through Saturday)**.

## ISO-8601 day of the week
Write a JavaScript function to get ISO-8601 numeric representation of the day of the week (1 (for Monday) to 7 (for Sunday))

    dt = new Date(2015, 10, 1); console.log(ISO_numeric_date(dt)); // 7

## Ordinal suffix
Write a JavaScript function to get English ordinal suffix for the day of the month, 2 characters (st, nd, rd or th.).

    (english_ordinal_suffix(dt)); // "1st"

## ISO-8601 week numer of year
Write a JavaScript function to get ISO-8601 week number of year, weeks starting on Monday.

## Full representation of months
Write a JavaScript function to get a full textual representation of a month, such as January or June

    new Date(2015, 10, 1); console.log(full_month(dt)); // "November"

## Full representation of months with zeros
Write a JavaScript function to get a numeric representation of a month, with leading zeros **(01 through 12)**

## Months with 3 letters
Write a JavaScript function to get a short textual representation of a month, three letters (Jan through Dec).

## Years
Write a JavaScript function to get a full numeric representation of a year (4 digits).

    console.log(full_year(dt)); // 2015

## Years in two numbers
Write a JavaScript function to get a two digit representation of a year.

    new Date(1989, 10, 1); console.log(sort_year(dt)); // "89"

## AM & PM
Write a JavaScript function to get lowercase Ante meridiem and Post meridiem.

## Internet Time
Write a JavaScript function to swatch Internet time (000 through 999).

## Hours
Write a JavaScript function to get 12-hour format of an hour with leading zeros.
    
        dt = new Date(1989, 10, 1); console.log(hours_with_zeroes(dt)); // 12

## Hours II
Write a JavaScript function to get 24-hour format of an hour with leading zeros.

## Seconds
Write a JavaScript function to get seconds with leading zeros (00 through 59).

## Timezone
Write a JavaScript function to get Timezone.

    dt = new Date(1989, 10, 1); console.log(seconds_with_leading_zeros(dt)); // CEST

## Daylights
Write a JavaScript function to find whether or not the date is in daylights savings time.

## GMT
Write a JavaScript function to get difference to Greenwich time (GMT) in hours.

        console.log(diff_to_GMT(dt)); // "+05.500"

## Timezone
Write a JavaScript function to get timezone offset in seconds.

Hint: *The offset for timezones west of UTC is always negative, and for those east of UTC is always positive.*

##Add years I
Write a JavaScript function to add specified years to a date.

    dt = new Date(2014,10,2);console.log(add_years(dt, 10).toString())
    // "Sat Nov 02 2024 00:00:00 GMT+0100 (CET)"

## Add weeks II
The same as previous exercise, but with weeks.

## Add months III
The same as previous exersice, but with months.

## Differences in minutes between two dates I
Write a JavaScript function to get time differences in minutes between two dates.

    dt1 = new Date("October 13, 2014 11:11:00"); 
    dt2 = new Date("October 13, 2014 11:13:00"); 
    console.log(diff_minutes(dt1, dt2)); 
    // 2

## Differences in hours between two dates II
The same as previous exersice, but in hours

## Differences in days between two dates III
The same as previous exersice, but in days

## Differences in weeks between two dates IV
The same as previous exersice, but in weeks

## Differences in months between two dates V 
The same as previous exersice, but in months

## Differences in years between two dates VI
The same as previous exersice, but in years

## Start Date I
Write a JavaScript function to get the week start date. 

## Start Date II
Write a JavaScript function to get the week end date.

## Start Date III
Write a JavaScript function to get the month start date.

##Start Date IV
Write a JavaScript function to get the month end date. 