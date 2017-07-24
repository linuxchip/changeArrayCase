# changeArrayCase

Description
-----------

Change the letters in the supplied array to the specified case ( Lower or Upper )

Parameters to this function are :

Array which has to be modified

Case ( Accepted values are "tolower" / "toupper" )

Return value will be modified array based on the supplied case parameter

Install
-------

npm install changeArrayCase

Usage
-----

const stringToModify = require('changeArrayCase');

var upperStringArray = ["APPLE", "ORANGE", "LEMON"];

var lowerStringArray = ["apple", "orange", "lemon"];


stringToModify(upperStringArray, "tolower");

// ["apple", "orange", "lemon"]


stringToModify(lowerStringArray, "toupper");

// ["APPLE", "ORANGE", "LEMON"];

API
---

changeArrayCase(inputStringArray, value)

inputStringArray

Type: string Array

String array to modify the letters in the array


value

Type: string

Allowed values are tolower / toupper

Tests
-----

'npm test'

LICENSE
-------

MIT 

