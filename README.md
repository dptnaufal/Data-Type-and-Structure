# Data-Type-and-Structure
Write Python code to determine whether a word "is a palindrome" or "is not a palindrome"
- Input: ‘malam’

  Output: ‘malam’ is a Palindrome
  
- Input: ‘Python’

  Output: ‘Python’ is not a Palindrome

## Maybe you can use this code for 'Polindrome'
`code` 
def isPalindrome(x):
    return x== x[::-1]

x = "malam"
ans = isPalindrome(x)
 
if ans:
    print( (x) , 'is a polindrome')
else:
    print( (x) , 'is not a polindrome')

### Answer
malam is a polindrome

## If you can use this code for ' Not a Polindrome'
`code`
def isPalindrome(y):
    return y == x[::-1]
 
 
x = "python"
ans = isPalindrome(x)
 
if ans:
    print( (x) , 'is a polindrome')
else:
    print( (x) , 'is not a polindrome')
    
### Answer
python is not a polindrome
