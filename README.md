In The First Step, I connected the ports I will work with, which are divided into two, input and output ports :
Output Ports : 
  1.aservo1 attached to port (11).
  2.aservo1 attached to port (10).
  3.aservo1 attached to port (9).
  4.aservo1 attached to port (6).
  5.aservo1 attached to port (5).
 	Note: Servo use a PWM signal which works only for Ports (11,10,9,6,5,3). 


Input Ports : 
        5 Variable Resistors connected to (A0,A1,A2,A3,A4).








In The Second Step, I modified the Input values using function i=(analogRead(A0)-10)*0.18 to match the degree scale for the servo. 




In The Third Step, I  used Serial Monitor code to show the values for the test issue.  



In The Fourth Step, I send the values that matched with the servo scale to servos.
