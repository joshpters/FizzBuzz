# FizzBuzz Challenge Minisite

This is a complete minisite that contains a visual representation of the "FizzBuzz" challenge.

![Screenshot](/Images/screenshot.jpg)

This project was created using Bootstrap 4.5, HTML5, CSS3, and JavaScript. All logic & JavaScript DOM changes were custom coded for this project.

## What is the "FizzBuzz" challenge?

"FizzBuzz" is a well known challenge about detecting multiples. Multiples of 3 are labeled a "Fizz", multiples of 5 a "Buzz", and the multiples of both a "FizzBuzz"! In this minisite you have the option of selecting value 1 and value 2.

Since its conception the Fizzbuzz challenge has been used by Facebook and Microsoft as interview tools and has also been taught at Stanford, Berkley, Caltech and countless other universities.

## Installation

You can view this site [live](https://fizz-buzz-challenge.netlify.app/).

To download and run locally, clone this repository and open index.html.

``` sourceCode
git clone https://github.com/joshpters/FizzBuzz
```

## Core Function

This is a basic form of the function that detects Fizz, Buzz, and FizzBuzz and returns a long string of output.

The minisite has a modified version of this function to work with the page animations & grid generation.

```javascript
function buzzItA(value1, value2) {
	let output = "";
	for (let i = 1; i <= 100; i++) {
		output += `${i.toString()}: `
		if (i % value1 == 0) {
                    output += 'Fizz';
                }
                if (i % value2 == 0) {
                    output += 'Buzz';
                }
                output += '\n';
	}
	return output;
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.