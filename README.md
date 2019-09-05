## Usage
Usage:  peoplegen [-s][-f][-m][-l][d][a][u][p][P][e][E][r][x][c][S][z][A][h] 
<--customlastname file> <--cusommalename file> <--customfemalename>
<--customcities file> <--customstreets file> <--help> <numbertoGenerate>
-s      --ssn           generate a social security number
-f      --firstname     generate a first name
-m      --middlename    generate a middle name
-l      --lastname      generate a last name
-d      --birthdate     generate a date of birth
-a      --address       generate a street address
-u      --username      generate a user name
-p      --phone         generate a phone number
-P      --phone2        generate a second phone number
-e      --email         generate an email address
-E      --email2        generate a second email address
-r      --race          generate a race
-x      --sex           generate a sex
-c      --city          generate a city name
-S      --state         generate a state
-z      --zip           generate a zip code
-A      --all           generate everything available

--customlastname file   use a different name list
--customfemalename file use a different name list for females
--custommalename file   use a different name list for males
--customdomain file     use a custom email domain list

-h      --help          print this help message
Example:   ./peoplegen -saup --customlastname /tmp/mynames

