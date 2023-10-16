---
title: psuedocode
description: this is my first attempt at psuedocode
date: 2023/10/16
---
here is my psuedocode for the task 

// Create an array of objects to store book information
// Each object should have properties: title (string), author (string), and alreadyRead (boolean)
//books = [
 //   { title: "The Hobbit", author: "J.R.R. Tolkien", alreadyRead: true },
 //   { title: "The Lord of the Rings", author: "J.R.R. Tolkien", alreadyRead: false }


// Iterate through the array of books
//for each book in books {
    // Log the book title and author for each book
 //   print book.title + " by " + book.author
    
    // Use if/else statement to check if the book has been read or not
  //  if book.alreadyRead is true {
        // If read, log a message indicating it has been read
    //    print "You already read \"" + book.title + "\" by " + //book.author
   // } else {
        // If not read, log a message indicating it needs to be read
   //     print "You still need to read \"" + book.title + "\" by " + book.author
//    }
//}

// Function: fixStart
// Parameters: inputString (string)
// Returns: modifiedString (string)

/*function fixStart(inputString) {
    // Get the first character of the input string
    firstChar = inputString[0]
    
    // Initialize an empty string to store the modified version
    modifiedString = ""
    
    // Iterate through the input string starting from the second character
    for each character in inputString from index 1 to end {
        // If the character matches the first character, replace it with '*'
        // Otherwise, keep the character unchanged
        if character is equal to firstChar {
            modifiedString += '*' // Replace matching characters with '*'
        } else {
            modifiedString += character // Keep non-matching characters unchanged
        }
    }
    
    // Return the modified string
    return modifiedString
}

// Example usage:
// fixStart('babble') should return 'ba**le'
// fixStart('turtle') should return 'tur*le*/