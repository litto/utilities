# Utilities Functions
Custom Functions for Generating slugs,passwords,parse string.etc.

## How to use?

Initialize Class Utilities by calling:-

$obj=new Utilities();
$encodedstr=$obj->encode($str);

Call each Function define in the Utilities Class like this. Below are some of functions available.

1) getRandom()  - get random string using current timestamp
2) getExtension($string) - Get extension of the file you pass into this function
3) setPattern($array) - Set pattern for Filter Function
4) filterChars($string) - Filter chars from string
5) dateDisplayFormat($date)-Convert Date to M-d-Y Format
6) dateTimeDisplayFormat($date) - Convert date time to M-d-Y H:i:s format
7) dateInsertFormat($date) - Convert date time to database date format for saving
8) encodeString($string) - Encode your string
9) decodeString($string) - Decode your string
10) priceFormat($price) - Convert to price format for display
11) addFilter($string)- Filtering string
12) encode($originalStr) - Password Encode
13) decode($decodedStr) - Decode Password
14) littoformattitle($text)- Generate slug variable passing string
15) getBaseUrl()- get base url of project
