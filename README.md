# Control Flow Exit Ticket

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## Question 1

What will happen when the code below is run?

```swift
var x = 10
if x = 15 {
 print("x is 15")
} else {
 print("x is not 15")
}
```

- It will print "x is 15"
- It will print "x is not 15"
- It will given an error because x is a var instead of a let
- It will give an error because it has "else" and not "else if"
- It will give an error because x = 15 uses the assignment operator instead of the comparison operator

***
## Question 2

Test if number is divisible by 3, 5 and 7. For example 105 is divisible by 3, 5 and 7, but 120 is divisible only by 3 and 5 but not by 7. If number is divisible by 3, 5 and 7 print `"number is divisible by 3, 5 and 7"` otherwise print `"number is not divisible by 3, 5 and 7"`.

```swift
let number = 210

// enter code below
```

***
## Question 3

What will happen when the code below is run?

```swift
var numberOfBagels = 15
let isOverADozen: Bool
if numberOfBagels > 12 {
    isOverADozen = true
} else {
    isOverADozen = false
}
if isOverADozen {
    print("You have more than 12!")
} else {
    print("You have less than 12!")
}
```

- It will print "You have more than 12!
- It will print "You have less than 12!
- It will not compile because numberOfBagels should be a constant
- It will not compile because isOverADozen should be a variable
