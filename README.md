# Gmail
The customized JavaMail Api for better performance.
Please remember to do the following steps
1. give JavaMail API to access your account
  since it is an old method to set email client by default the Gmail server prevents the sign-in from API
  so you need to allow this
2. Initialise your username and passwor using the parameterised constructor Gmail(String user, String pass);
 please note that username refers to the part before @gmail.com annotation
3. get the list of recipient addresses as a String array. 
4. get the subject as a String
5 Get the meesage also as a String.

  Then call the method private String sendFromGMail( String[] to, String subject, String body)
  which will return you the reply of the operation as a String
