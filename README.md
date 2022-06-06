# Credit-card-checker
This program was one of the first projects on a full-stack developer career course on Codecademy
Overall this program's purpose is to take in a batch of credit card numbers and return if they are valid or not. 
As well as returning the invalid card numbers it also returns the companies that are tied to each batch, without repeats
The directions for this program were a series of open-ended tasks that I had to perform any way without specific guidelines
The tasks were as follows
  1.Create a function, validateCred() that has a parameter of an array. The purpose of validateCred() is to return true when an array contains digits of a valid credit 
  card number and false when it is invalid. This function should NOT mutate the values of the original array. To find out if a credit card number is valid or not, use 
  the Luhn algorithm.
  2.Create another function, findInvalidCards() that has one parameter for a nested array of credit card numbers. The role of findInvalidCards() is to check through the 
    nested array for which numbers are invalid, and return another nested array of invalid cards.
  3.After finding all the invalid credit card numbers, it’s also necessary to identify the credit card companies that have possibly issued these faulty numbers. Create a 
    function, idInvalidCardCompanies() that has one parameter for a nested array of invalid numbers and returns an array of companies.Currently, there 4 accepted 
    companies which each have unique first digits. The following table shows which digit is unique to which company:
        3-Amex
        4-Visa
        5-Mastercard
        6-Discover
  
  The focus of this project was to cement the understanding of basic syntax concerning JavaScript while learning habits such as using comments to depict what each 
  function was for
