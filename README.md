# recursioncheckpoint


Palindrome Checker
This is a JavaScript function that checks if a word is a palindrome. The function uses a loop to compare the characters at the beginning and end of the word. If they are not equal, it returns "false". If the loop completes without finding any differences, it returns "true".

Usage
To use the function, call isPalindrome(word) with a word as an argument. The function returns "true" if the word is a palindrome, and "false" otherwise.

console.log(isPalindrome("racecar")); // true
console.log(isPalindrome("hello")); // false

Implementation

The function uses a loop to compare the characters at the beginning and end of the word. If they are not equal, it returns "false". If the loop completes without finding any differences, it returns "true".

The function is designed to work with any word, regardless of its length or content. It can also be easily integrated into other JavaScript programs or applications.

function isPalindrome(word) {
// Loop through the characters at the beginning and end of the word
for (let i = 0; i < word.length / 2; i++) {
// If the characters are not equal, the word is not a palindrome
if (word[i] !== word[word.length - 1 - i]) {
return false;
}
}
// If the loop completes without finding any differences, the word is a palindrome
return true;
}

