# dylan-happy
Find happy numbers in a range of numbers.

From [Wikipedia: Happy number](https://en.wikipedia.org/wiki/Happy_number):
---
> In number theory, a happy number is a number which eventually reaches 1 
> when replaced by the sum of the square of each digit. For instance, 
> 13 is a happy number because 1^2 + 3^2 = 10 , 
> and 1^2 + 0^2 = 1. On the other hand, 4 is 
> not a happy number because the sequence starting with 4^2 = 16 
> and 1^2 + 6^2 = 37 eventually reaches 2^2 + 0^2 = 4, 
> the number that started the sequence, and so the process continues in an 
> infinite cycle without ever reaching 1. A number which is not happy is 
> called sad or unhappy. 

## Usage

    dylan-happy-app <from:integer> <to:integer>

### Example

    $ dylan-happy-app 1 10
    #(1, 7, 10)
