# Kelvin-Weather-Converter-Project
This project is a basic weather converter from Kelvin to Celsius and then to Fahrenheit.

const kelvin = 293; // Kelvin stays constant

// Kelvin to Celsius conversion
// Celsius is Kelvin minus 273
const celsius = kelvin - 273;

// Fahrenheit calculation from Celsius
// Fahrenheit = Celsius * 9/5 + 32
let fahrenheit = celsius * (9 / 5) + 32;

// Round Fahrenheit down to an integer value
fahrenheit = Math.floor(fahrenheit);

console.log(`The temperature is ${fahrenheit} degrees Fahrenheit.`);
