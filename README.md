# secured_message
a way to send our message using our own created password.
.
.
.
.


C is a compiled language. 
After successful compilation of source code, we get executable file (.exe on windows and .out on linux) . 
Getting source code from executable file is .. . . . . 

.
.
.
.




SENDER SIDE.

We have to create a c file having format like "message.c".
   Put your message @ " your message is here.".
   put your passwords @  "password_1".

   
Compile this file, using command
   "gcc -o message message.c".

Now a executable file named " message " will be created. 

send/share this file to receiver via any possible medium.
.
.
.
.
.
.





RECEIVER SIDE.

receive this file.

run on your system using command
   " ./message required_password "  Here required_password = password set by sender.
   
now, your message will be shown on terminal. 
.
.
.
.
.
.



DEMO:-
   i have uploaded both files,
   download file named "message" (executable file),
   run on your linux system using command,
   "./message password_1 ".
   you will get "your message is here." ( message which i was willing to send ).
   if you have entered wrong password, then you will not get correct passwords...
   .
   .
   .
   .
   .
   .
   
   
   
Benefits : -
 
no way, such that third party can see your message, nor,  the parties through
which you are sending, such as, google services, whatsapp etc. They only can executable file,  not it's internal 
Contents.
Because, recovering source code from executable file is very tough ( almost impossible ) . 

After little customization to your code...
You can set a large number of passwords, each password can have a large number of characters.
resulting, in more secured ( cracking password will be very* tough ). 

"corruption of message" , "when wrong password is entered" is also possible.
any many more....
.
.
.
.
.



