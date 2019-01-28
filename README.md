# arduinoCalc
Arduino(UNO) based calculator 

This calculator is built using Arduino and 4x4 keypad 

Consists of following features: 

1) Username and password for secure login of the users. Login is prompted when starting the calculator.
2) Username 0 can be used for changing the password corresponding to the users.
3) Calculation mode : Can be accessed after the user login
                      Can calculate the expression entered for all three operator formats : inline, prefix, postfix
                      History of calculation can be accessed by passing string as " *** "
                      Any of the calculation from history can be used for recalculation by "=" key
                      
keymap for using the 4x4 arduino compatible keypad :  {'1','2','3','+'}
                                                      {'4','5','6','-'}
                                                      {'7','8','9','* '}
                                                      {'C','0','=','/'}
Arduino connection present in resources folder.

--Saurav 

  


                      
