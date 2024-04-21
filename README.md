//Leap Year Checker
function isLeapYear(year) {
  // Check if the year is divisible by 4
  if (year % 4 === 0) {
    // If the year is also divisible by 100, check if it's divisible by 400
    if (year % 100 === 0) {
      return year % 400 === 0;
    } else {
      return true;
    }
  } else {
    return false;
  }
}


//Weather Clothing Adviser
temperature = int(input("Please enter the current temperature: "))
raining = input("Is it raining? (yes/no) ")

if raining.lower() == "yes":
    if temperature <= 10:
        print("You should wear a warm coat, hat, gloves, and waterproof shoes.")
    elif temperature <= 20:
        print("You should wear a waterproof jacket, pants, and shoes.")
    else:
        print("You should wear a light jacket and waterproof shoes.")
else:
    if temperature <= 5:
        print("You should wear a warm coat, hat, gloves, and shoes.")
    elif temperature <= 15:
        print("You should wear a jacket and shoes.")
    else:
        print("You should wear a t-shirt and shoes.")



  //Palindrome Checker
function isPalindrome(s) {
  s = s.replace(/[^a-z0-9]/gi, '').toLowerCase(); // remove spaces, punctuation, and convert to lowercase
  if (s.length <= 1) {
    return true;
  } else if (s[0] === s[s.length - 1]) {
    return isPalindrome(s.slice(1, -1));
  } else {
    return false;
  }
}


//Power Function

function power(base, exponent) {
  if (exponent === 0) {
    return 1;
  } else {
    return base * power(base, exponent - 1);
  }
}

console.log(power(2, 3)); 

















  
