

<!-- Given what you already know about SQL, can you spot our vulnerability? -->
it is vulnerable to SQL injection in the password field 



<!-- Mount the attack
What happened? -->
i got an error has occurred message......

Second try. This time it worked, i had to restart the server. It gave me access as Administrator


<!-- Taking your best guess, what do you think happened? -->
i entered unknown' OR '1'='1 into the password field and i think the first ' after unknown helped close the stirng for password and open up the OR '1'='1' which gave us a truthy value giving us access to the login.