# Node Holiday BR 
> Brazilian holiday list and helper functions

[![Build Status](https://travis-ci.org/alexrochas/node-holiday-br.svg?branch=master)](https://travis-ci.org/alexrochas/node-holiday-br)
[![Coverage Status](https://coveralls.io/repos/github/alexrochas/node-holiday-br/badge.svg)](https://coveralls.io/github/alexrochas/node-holiday-br)

## Installing

	npm install holiday-br

## Usage

```node
var
    holidays = require('holiday-br');

// Get a list of holidays between two dates
curYearHolidays = holidays.between(new Date(2015,0,1),new Date(2016,0,1));

// Check if a specific date is a holiday
if ( holidays.isHoliday(new Date(2048,4-1,25)) ) {
    console.log("Long live freedom!");
}
```
