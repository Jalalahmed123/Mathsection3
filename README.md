# Mathsection3
# Math Program for Demonstrating TDD
//tell the test where to find the code
//This is a short program that does basic arithmatic and demonstrates used of test-driven development file

var math = require('../math')
describe("A simple program that does arithmatic", function() {it("can add two numbers", function() {
	expect(add(3,5)). toBe(8);
});
);
it("can subtract two numbers", function(){
	expect(math.subtract(3,5)) .  tobe(-2);
});
