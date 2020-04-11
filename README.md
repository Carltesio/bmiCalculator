### THE BMI CALCULATOR ( pedagogic exercise)

Body mass index (BMI) is a simple tool that is generally used to estimate the total amount of body fat. In this challenge we will write a JavaScript program that calculates a individuals BMI index.

How To Calculate BMI
To calculate BMI, you need to know your weight and height in kilograms and centimeters or meters (Metric Method). The weight of a person is then divided by the height.

If you know your height and weight in inches and pounds the calculation is a little more complex (Imperial Method).

METRIC METHOD
The metric formula accepts height measurements in meters and weight in kilograms. If you know your height in centimeters only, simply divide the number of centimeters by 100 convert it to meters.

For example, a person who is 183 cm tall is 1.83 m tall (183 cm / 100 = 1.83 m)

Multiply your height by itself.
Divide your weight in kilograms by the value calculated in step 1.
The resulting number is your BMI. Compare this BMI value with the weight status table below.
Classification	BMI
Underweight	<18.5
Normal weight	18.5-24.9
Overweight	25-29.9
Obesity Class 1	30-34.9
Obesity Class 2	35-39.9
Extreme Obesity Class 3	>40


## Installation

Install the rspec Gem to run the tests with rspec:
in your terminal run:
```bash
 gem "rspec"
```
then run the bundle command:
```bash
 bundle
```


## Usage

Try out your program again in irb. Remember that you have to load or require the source file. 
Now any number should work. That’s why we wrote our tests - so that we could be confident it would work under any scenario.

In your IRB console run the following examples to see it make it work:

```bash
$ irb
2.2.0 :001 > load './lib/fizz_buzz.rb'
 => true 
2.2.0 :002 > fizz_buzz(23)
 => 23 
2.2.0 :003 > fizz_buzz(3)
 => "fizz" 
2.2.0 :004 > fizz_buzz(6)
 => "fizz" 
2.2.0 :005 > fizz_buzz(10)
 => "buzz" 
2.2.0 :006 > fizz_buzz(45)
 => "fizz buzz" 
2.2.0 :007 >
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
