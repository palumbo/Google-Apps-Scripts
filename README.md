# Google-Apps-Scripts

## nameGenerator
This script requires a list of names to be in a range. 

I pulled the names from https://www.ssa.gov/oact/babynames/decades/century.html using `=IMPORTHTML('https://www.ssa.gov/oact/babynames/decades/century.html','table'1)` and then put them into a single column using `=TOCOL( {RANGE1 ; RANGE2} )`

The script will list the names startingn from the active cell. 
