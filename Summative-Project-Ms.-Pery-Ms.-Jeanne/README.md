# Summative-Project-Ms.-Pery-Ms.-Jeanne


**Project Description

WEBSITE FOR WELLNESS CENTRE
Our project will be based on the Mental health field and focusing on students majorly either in our institution or any other institution but in this case we might just consider our institution for it to be more practical to us.
We are looking to start a website where there would be different offerings on wellness.
We are taking it from a point where for example we have a wellness centre department and they have been having a low turnout since we moved to online maybe because they were not prepared and having a website where we have all the offerings together then it would be easier even for a student to be aware of what they offer incase of a new student who doesn't really understand how the system works.
We will have a login with the student email address because every student have that plus a passcode
From that the student is able to access the offerings and select only one at a time from life coaching to planner and counselling and also testimonials pin which different videos will have been uploaded for them to watch
So it's going to be user friendly as students are choosing for themselves the type of offering they want at that moment 
With time we might be able to improve it to an app as we get more acquainted with programming.

**Classes and Methods

Class Wellness_Center:
 Initiate: self, email, password
Output: 

def Login_Credentials:
Output: personal login credentials
Output2: email: self.email
Output3: password: self.password

def Testimonials:
Output: watch and listen to these beautiful stories by some of your peers who have used our website

def Coaching:
Input: are you a new or a returning student?
If input new:
Output: Name of the assigned coach
Elif returning: 
Output: choose a regular coach
Else:
Output: choose a new coach

def planner:
Input: are you a new or a returning student?
If input new:
Output: Name of the assigned expert planner
Elif returning: 
Output: choose a regular planner
Else:
Output: choose a new planner

def Counselling:
Input: are you a new or a returning student?
If input new:
Output: Name of the assigned counselor
Elif returning: 
Output: choose a regular counselor
Else:
Output: choose a new counselor





Class Communication(Wellness_Center):
 Initiate: self, email, password
super()

def Login_Credentials:
Output: personal login credentials
Output2: email: self.email
Output3: password: self.password

def Hangout_Chats:
Input = Yes or No
If Input Yes:
Output: Given email to chat on hangout
Else:
Output: Choose a different communication channel

def Hangout_Calls:
Input = Yes or No
If Input No:
Output: Choose a different communication channel
Elif Yes:
Output: Schedule a Video Call
Else:
Output: Schedule an audio call

def WhatsApp_Chats:
Input = Yes or No
If Input Yes:
Output: Given number to chat
Else:
Output: Choose a different communication channel

def WhatsApp_Calls:
Input = Yes or No
If Input No:
Output: Choose a different communication channel
Elif Yes:
Output: Schedule a Video Call
Else:
Output: Schedule an audio call




Def Phone_Calls:
Input = Yes or No
If Input No:
Output: Choose a different communication channel
Else:
Output: Schedule a phone call




 
 
TEST SCENARIOS
**Class Wellness_Center:

Test no.1
Test description:Login credentials
Test data:Correct email
Expected result:…..@alustudent.com
Actual result:….@alustudent.com
Pass/Fail:Pass

Test no.1
Test description:Login credentials
Test data:Correct password
Expected result:Login successful
Actual result:Login successful
Pass/Fail:Pass

Test no.2
Test description:Input answer
Test data: New or returning student 
Expected result: New / Returning
Actual result: New / Returning
Pass/Fail: Pass

Test no.3
Test description: Assignment of counsellors
Test data: Contacts of counsellors 
Expected result: Email, Name, Phone number
Actual result: Email, Name, Phone number
Pass/Fail: Pass

Test no.4
Test description: Choosing of counsellors
Test data: List of counsellors
Expected result: Chosen counsellor
Actual result: Chosen counsellor
Pass/Fail: Pass


**Class Communication:

Test no.1
Test description:Login credentials
Test data:Correct email
Expected result:…..@alustudent.com
Actual result:….@alustudent.com
Pass/Fail:Pass

Test no.1
Test description: Login credentials
Test data: Correct password
Expected result: Login successful
Actual result: Login successful
Pass/Fail: Pass

Test no.2
Test description: Check if Yes or No is case sensitive
Test data: Whichever case yes or no should be able to be recognized
Expected result: Yes/YES/yes
                 No/NO/no
Actual result: Yes/YES/yes
               No/NO/no
Pass/Fail: Pass


Test no.3
Test description: Check if option Yes leads to scheduling a video call/audio call
Test data: Does it lead you to choose a date and month
Expected result: Choose date and month
Actual result: Choose date and month
Pass/Fail: Pass

Test no.4
Test description: Check if No option leads you to choose a different communication channel
Test data: Leads you to choose a communication channel
Expected result: How would you prefer to be reached
Actual result: How would you prefer to be reached
Pass/Fail: Pass


