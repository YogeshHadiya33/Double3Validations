<p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br />
<!--[if !supportLineBreakNewLine]--><br />
<!--[endif]--></span><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;"><o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This package is specially created for basic validation which we
use in our regular programming. Using this package you can validate a couple of
things. There are the following methods in this Package.<o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">IsBothPasswordMatch<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">IsValidBoolean<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">IsValidDouble<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">IsValidInteger<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">IsValidFloat<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">IsValidEmail<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">IsValidPassword<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Now look at these methods one by one.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsBothPasswordMatch<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method is use for compare that entered both
password is similar or not. Before comparing both strings first its check if
both string has value.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameter</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">firstPassword: Accept string as
     this parameter for first password.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">secondPassword: Accept string
     as this parameter for second password.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value true or false. If both password
are match than its return true otherwise return false. And also if any string
is empty or null it will return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidBoolean</span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description: This method takes string parameter and check entered
string is valid Boolean value which is true or false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameters</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">value: Accept string as a
     parameter.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value. If entered string is valid
Boolean type value then return true otherwise return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidDouble<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes string parameter and check
entered string is valid double value.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameters.</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;value: Accept string as a
     parameter.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value. If entered string is valid
double type value then return true otherwise return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidInteger<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes string parameter and check
entered string is valid integer value.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameters</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">value: Accept string as a
     parameter.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return: This method return Boolean value. If entered string is
valid integer type value then return true otherwise return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidFloat</span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes string parameter and check
entered string is valid float value.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameters</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">value: Accept string as a
     parameter.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value. If entered string is valid float
type value then return true otherwise return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidEmail<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes email string as a parameter
and check is email is valid or not. For checking valid email it use regular
expression.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameter</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">value: Accept string as a
     parameter.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return: This method return Boolean value. If email pattern is
match with regular expression pattern then it return true otherwise false. In
case if email string is null or empty then it’s also return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 2;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 22pt;">IsValidPassword<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method has six overloaded methods with different parameters.
All methods details are below.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidPassword Method 1<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes two parameter password and min
length value. Its check password is not empty and has the same length as given
length.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameters:</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">password: Accept string value
     as a password<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;minLength: Accept integer
     as a min length parameter.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value. If password string is not empty
and it has same length as given min length parameter then return true otherwise
return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidPassword Method 2<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes three parameter passwords, min
length value and isContainUpperCase. Its check password is not empty, has same
length as given length and if isContainUpperCase is true then check if password
string is contain at least one upper case character.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameters:</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;password: Accept string
     value as a password.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;minLength: Accept integer
     as a min length parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;isContainUpperCase: Accept
     Boolean value as true or false.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;This method return Boolean value. First check password
string is not empty and has same length as given min length parameter and then
if isContainUpperCase parameter has true value then also check password string
at least contain one uppercase character and if this parameter is false then
only check first two conditions. If all conditions are satisfied then return
true otherwise false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidPassword Method 3<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes four parameters password
string, min length, isContainUpperCase and isContainLowerCase. Its check if
password is not empty and same length as given min length parameter and if
isContainUpperCase or isContainLowerCase parameter’s value is true then also
check password string contain at least one upper case and one lower case
character respectfully.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameter:</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;password: Accept string
     value as a password.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;minLength: Accept integer
     as a min length parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;isContainUpperCase:
     Accept Boolean value as true or false.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">isContainLowerCase: Accept
     Boolean value as true or false.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value true or false. First its check if
password is not empty and has same length as given min length parameter then if
isContainUpperCase is true then check password string contain at least one
upper case character and isContainLowerCase is true then check password string
contain at least one lower case character if all conditions are true then
return true otherwise return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidPassword Method 4<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes five parameters password
string, min length, isContainUpperCase , isContainLowerCase and
isContainNubers. Its check if password is not empty and same length as given
min length parameter and if isContainUpperCase , isContainLowerCase or
isContainNubers&nbsp;&nbsp;parameter’s value is true then also check password
string contain at least one upper case , one lower case character and one
number respectfully.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameter:</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">password: Accept string value
     as a password.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;minLength: Accept integer
     as a min length parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">&nbsp;isContainUpperCase:
     Accept Boolean value as true or false.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">isContainLowerCase: Accept
     Boolean value as true or false.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">isContainNubers : Accept
     Boolean value as true or false.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value true or false. First its check if
password is not empty and has same length as given min length parameter then if
isContainUpperCase is true then check password string contain at least one
upper case character and isContainLowerCase is true then check password string
contain at least one lower case character and if isContainNumber is true then
check password string contain at least one numeric character if all conditions
are true then return true otherwise return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><br /></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidPassword Method 5<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes six parameters password
string, min length, isContainUpperCase , isContainLowerCase , isContainNubers,
isContainSpecialCharacter. Its check if password is not empty and same length
as given min length parameter and if isContainUpperCase , isContainLowerCase ,
isContainNubers&nbsp;&nbsp;or isContainSpecialCharacter parameter’s value is
true then also check password string contain at least one upper case , one
lower case character , one number and one special character respectfully.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Parameter:</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">password: Accept string value
     as a password<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">minLength: Accept integer as a
     min length parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">isContainUpperCase: Accept
     Boolean value as true or false.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">isContainLowerCase: Accept
     Boolean value as true or false.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">isContainNubers: Accept Boolean
     value as true or false.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 13.5pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">isContainSpecialCharacter: Accept
     Boolean value as true or false.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value true or false. First its check if
password is not empty and has same length as given min length parameter then if
isContainUpperCase is true then check password string contain at least one
upper case character and isContainLowerCase is true then check password string
contain at least one lower case character and if isContainNumber is true then
check password string contain at least one numeric character and if
isContainSpecialCharacter is true then check password string contain at least
one special character&nbsp;&nbsp;if all conditions are true then return true
otherwise return false.<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;"><o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; mso-outline-level: 3;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">IsValidPassword Method 6<o:p></o:p></span></b></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Description:&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method takes six parameters password,
minLength, minUpperCaseCharacter, minLowerCaseCharacter, minSpecialCharacter,
minNumbericCharacter. Its first check password string is not empty and has
minimum length as given min length parameter and then check password contains
minimum lengths of upper case character, lower case character, special
character and numbers character as given in parameters.<o:p></o:p></span></p><ul type="disc">
 <li class="MsoNormal" style="line-height: normal; mso-list: l3 level1 lfo13; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; tab-stops: list .5in;"><b><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">Parameters</span></b><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;"><o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal; mso-list: l3 level1 lfo13; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; tab-stops: list .5in;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">Password: Accept string value
     as a parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal; mso-list: l3 level1 lfo13; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; tab-stops: list .5in;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">minLength: Accept integer value
     as a parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal; mso-list: l3 level1 lfo13; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; tab-stops: list .5in;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">minUpperCaseCharacter: Accept
     integer value as a parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal; mso-list: l3 level1 lfo13; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; tab-stops: list .5in;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">minLowerCaseCharacter: Accept
     integer value as a parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal; mso-list: l3 level1 lfo13; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; tab-stops: list .5in;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">minSpecialCharacter: Accept
     integer value as a parameter.<o:p></o:p></span></li>
 <li class="MsoNormal" style="line-height: normal; mso-list: l3 level1 lfo13; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; tab-stops: list .5in;"><span style="font-family: &quot;Times New Roman&quot;,&quot;serif&quot;; font-size: 16pt; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: &quot;Times New Roman&quot;;">minNumbericCharacter: Accept
     integer value as a parameter.<o:p></o:p></span></li>
</ul><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto;"><b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">Return:&nbsp;&nbsp;</span></b><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">This method return Boolean value true or false.
If all conditions are fulfill like not empty, min length, min uppercase
character, in lowercase character, min special character, min numeric character
then return true otherwise false.&nbsp;&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; text-indent: 0.5in;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; text-indent: 0.5in;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; text-indent: 0.5in;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="line-height: normal; mso-margin-bottom-alt: auto; mso-margin-top-alt: auto; text-indent: 0.5in;"><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt;">&nbsp;<o:p></o:p></span></p><p>





















































































































































<span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16pt; line-height: 107%;">&nbsp;</span></p>
