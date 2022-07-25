 #### Episode 1

 The output will be the string in the return statement with 'Miss Scarlet' as the variable. Nothing is being changed so the keyword const is okay. 
 The function is returning the object, calling on the murderer key and then being printed to the console.



 ### Episode 2 

This is will throw out an error. 'murderer' is being defined as a const, Professor Plumb with global scope and therefore cannot be reassigned anywhere else in the file.



 ### Episode 3

 The first verdict will return The murderer is Mrs Peacock. This is because murderer is redefined within the scope of the declareMurderer function. The second verdict will return Professor Plumb as this is declared outwith the function and the reassignment of Mrs. Peacock has been forgotten once the declareMurdere function has ran. 



 ### Episode 4

 The first console.log will print The suspects are Miss Scarlet, Professor Plum, Colonel Mustard. This is because suspect 3 is being reassigned within the scope of the function and then being called upon. The second console.log will print suspect 3 is Mrs Peacock as this is declared at the top of the file and the reassignment only happens within the scope of the function.



 ### Episode 5

 This will print the weapon is a revolver. This is because we can change the keys within an object even if its declared as a const. So the function can reassign the value of weapon using the changeWeapon function.



### Episode 6

 This will print the murderer is Mrs White. This is because when we call the changeMurderer function it runs the whole codeblock in the curlys, running the plot twist function as well and therefore reassigning the murderer to Mrs White from the plotTwist function.



 ### Episode 7

 This will print out The murderer is Mr Green as there is no key word when declaring that variable, therefore giving it global scope so any other functions using let tio declare variables are forgotten when that codeblock is finished. 

 ### Episode 8

My initial thought was candle stick, however, when i read futher I thought unexpectedOutcome was called before plotTwist therefore, the conditionals wouldn't be met and no reassigments would apply, leaving the weapon as Lead Pipe.

 ### Episode 9 

 This will print professor plumb as this exists globaly within the file. The reassignement only exists in that code block so the declare murderer function will look to the above 'let', not the one within the curlys on the if statement.