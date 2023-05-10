#Testing Cheat-List

## Users
- Investors
- Lovers (Hobby)
- Researchers/Marketologs/Journalists

## Data
**String:**
- 3 base values
- Min and Max count
- Allowable and invalid characters
	- Some languages
	- Spaces
	- Empty
	- Script / SQL/NoSQL Injections

**Number:**
-   Most correct numbers (correct with scenario)
    -   With some currencies
    -   With point and comma
    -   Negative numbers
    -   Numbers with e
-   Incorrect numbers
    -   Symbols / Letters
    -   Numbers with several points or commas
    -   Number with space
-   Range of acceptable numbers
    -   Math subsets of acceptable values
    -   Logic subsets of acceptable values
    -   Null

**Date/Time:**
-   Current Date
-   With many formats
    -   AM/PM and 24 hours
    -   With year / Without year
    -   With 4 year numbers / With 2 year numbers
    -   DD.MM.YYYY / MM.DD.YYYY / YYYY.MM.DD ...
    -   12 March
    -   12 03 2023
    -   Presence of minutes and seconds
-   With some time zones
-   Range of acceptable dates and times
    -   In the Past
    -   In the Future
    -   The last value in a unit of time
    -   Logic (e.g. BTC in 2006)

## Operations

**Add:**
-   Add with default state
-   Add with valid data
-   Add with only optional data
-   Add without optional data
-   Add with invalid data
-   Add many time (DDOS)

**Edit:**
-   Remove something
-   Add something
-   Change all/something
-   Save without change

**Delete:**
-   Delete
-   Delete not deletable

**Search:**
-   Search with all word
-   Search with part of word
-   Search with word combination
-   Search with lower/upper cases
-   Search with some languages
-   Search with numbers
-   Search with symbols
-   Check automatic removal of end spaces
-   Check saving search parameters when switching pages
-   Check turning on the search tooltip

**Reordering:**
-   Create a group
-   Move the group
-   Move inside of group
-   Remove from group
-   Remove from group and add to another group
-   Remove from group and create another group
-   Move inside to group
-   Try to move group into another group

## Functionality

**Loader:**
-   Disabling all page
-   Logout Login and check loader
-   New Tab / Window
-   Refresh
-   Loader existing after finish
-   The impact of loading on user experience

**Network:**
-   Network is down
-   Server is down
-   Response is not come
-   JS is disabled
-   Some custom settings for browser

**Upload a file:**
-   Upload file with a valid format
-   Upload file with invalid format
-   Upload file with invalid name and valid format
-   Upload file with MAX size
-   Upload file with MIN size
-   Upload file and refresh
-   Upload file and change page / tab
-   Upload file and check request/response
-   Upload several files
-   Upload several files in the same time
-   Upload big file

## Technologies
**UI:**
-   Accessbility
-   ISO
-   Title, Favicon, https, link, h1
-   Enter key for Submit
-   Tab key for go next
-   Ctrl+C and Ctrl+V for all texts and fields
-   Tooltip for eclipsed texts
-   Hints
-   Placeholders for all fields
-   Some tags - arial, alt, meta ...
-   Hover on element mouse should focus
-   All buttons should be clickable and some of them should open in the new tab
-   404 page when link is invalid
-   Zoom in/out
-   All browsers (Chrome, Mozilla, Safari)

**API:**
-   All Requests validation
-   Requests count per page
-   All Response validation
-   Response time
