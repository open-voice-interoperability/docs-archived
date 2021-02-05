# Suzanne Case Study
A user, Suzanne, would like to plan a trip to an international conference and she needs visa information and airline reservations. 
This is a futuristic scenario in which Suzanne has a personal agent named Jeeves inspired by the in BBC TV series Jeeves and Wooster based on a series of books by P. G. Woodhouse. For the next few years when Jeeves is not available, Suzanne would need to do all the tasks perform by Jeeves.
This scenario features issues of privacy, security, and component behavior.    
1.	Suzanne begins by pressing a button on her cell phone to begin her conversation with her Jeeves.  Jeeves is local to Susan’s phone and has permission to access Susan’s personal data.
2.	Jeeves:  Hi, I’m Jeeves, your personal assistant. Could you please say your name? Jeeves will use three forms of user authentication based on Susan’s personal data.  Suzanne can change this if she wants.
3.	Suzanne:  I’m Suzanne
4.	Jeeves invokes speaker authentication component to verify that it really is Suzanne. 
5.	Jeeves also uses the camera on the cell phone to do a face recognition of Suzanne.
6.	Jeeves: I think you might be Suzanne, but to be sure, please apply your secret calculation to the number 13
7.	Suzanne applies her secret calculation, subtract 3, and responds by saying 3.  This is also a type of challenge dialog that uses something the user knows to verify who the user is.  It also verifies that the user is not a robot. Note that a password is not used because I hate passwords 
8.	Jeeves:  Hi Suzanne, how can I help you?
9.	Suzanne: I will be speaking at the EuroSpeech Conference in Paris, and I need want to check about visa information Jeeves uses the dialog broker to discover the visa agent.
10.	Jeeves: I can connect you with a visa agent.  Do you want me to share your personal information with the Visa agent?  Before the visa agent can access Suzanne’s personal data, Susan must grant permission. 
11.	Suzanne: OK Jeeves passes Susann’s request to the visa agent.
12.	Jeeves:  Hello Suzanne, I’m the visa agent.  I understand that you are traveling to Paris to the EuroSpeech conference.  I see that you have a US passport that expires on February 12, 2021.  The visa agent checks EuroSpeech web page to determine the dates of the conference. 
13.	Visa agent: The  EuroSpeech  conference is February 20-23, 2021.  Your passport will expire before then.  Would you like help to renew your passport?
14.	Suzanne: yes
15.	Jeeves: the cost of a renewed passport will be $150 plus my service fee of $25 for a total cost to you of $175.  Is that OK? Jeeves always checks with Suzanne about estimated costs of services
16.	Jeeves looks at the computing devices available to Suzanne and located a large display screen.  In the past, Suzanne has used the large screen to display large chunks of data rather than the screen on her cell phone.  Jeeves displays the passport renew form on the large screen and enters information from Susan’s personal data into the form.
17.	  Jeeves: a passport renewal form is on the large screen in your office.  I have inserted your personal information into that form.  Except for question 14, are the answers to the questions correct?  Question 14 requests the names of countries Suzanne plans to visit. This info is not in Suzanne’s personal data.
18.	Suzanne: yes
19.	Jeeves: Thanks, Please speak the answer to question 14 into the microphone or type the answer on your cell phone keyboard
20.	Suzanne: I only plan to visit France in the next year
21.	Jeeves places the answer France into question 14
22.	Jeeves:  Good.  Now I need to take your picture and scan your current passport or valid driver license.   
23.	Jeeves instructs Suzanne to look straight at the camera, adjusts the focus of the camera, zooms the camera appropriately, then takes Suzanne’s picture.
24.	Jeeves: your picture is displayed on your phone screen.  Does it look OK  
25.	Suzanne:  yes
26.	Jeeves:  Excellent, next we need scan your passport or driver’s license.  Please open your passport to the page with your picture and place it on the scanner in your office
27.	Suzanne places her passport on the scanner.  Scanner captures the image passport holder information
28.	Visa agent exams the scanned data to verify that it is legible
29.	Jeeves:  Do you want to use your default charge card or PayPal to pay $150.00 to the US Department of State?
30.	Suzanne:  my default  charge card
31.	Jeeves: Do you want to use your charge card ending in 4443 to pay of $150.00 plus service fee of $25 for a total of $275?
32.	Suzanne: yes
33.	Jeeves: Done.  I have sent a receipt to your e-mail address.  
34.	Jeeves: Can I now help you with airline reservations?
35.	Suzanne:  I’d like to arrive the day before the conference begins, and return two days after the end of the conference
36.	Jeeves: so you would like fly from your hometown of Portland Oregon to arrive in Parris France n February 19, 2021 and return from Paris France to Portland Oregon on February 25, 2021? Jeeves uses information from Suzanne’s airline flight history to determine the departure airport. 
37.	Suzanne: yes.  Jeeves uses the dialog broker to locate the airlines wizard. 
38.	Jeeves:  I will connect you with Fred the flight scheduler who will assist you with this reservation.  If you need me, just call my name, Jeeves invokes the airlines wizard.
39.	Fred the flight scheduler:  Hi, this is Fred the flight scheduler. Jeeves tells me that you are looking for flight from Portland Oregon to arrive in Parris France n February 19, 2021 and return from Paris France to Portland Oregon on February 25, 2021.  I will display available flights from Portland Oregon on the large screen in your office.  Do you see a flight you would like to book?
40.	Susanne:  yes, this one (and clicks her desired flight)
41.	Fred: Jeeves tells me that you prefer an aisle seat, is that correct?
42.	Susanne: yes
43.	Fred: I have reserved seat 22B.  I will display available flights from Paris France on the large screen.  Do you see a flight you would like to book?  
44.	Suzanne:  yes, that one (and clicks her desired flight)
45.	Fred:  I’ve reserved that flight as well as isle seat 23B.  Would you like to purchase the flights now?
46.	Suzanne: No, I want to purchase the flights directly from the airlines.
47.	Jeeves: Do you want me to connect you to fly-by-night airlines so you can book your flight to Paris?
48.	Suzanne, no I’ll do that later.  Make a note to remind me about this tomorrow.
49.	Jeeves:  Noted
50.	Suzanne pauses to drink a cup of coffee.  During this pause, she hears an advertisement 
51.	Sound Cloud agent: This is Sound Cloud.  Here is a new posting from your favorite jazz band, two five, one   A preview of music is presented.  
52.	Sound cloud agent: Would you like to download it for a price of 8 membership points?
53.	Suzanne: Yes, I like it.

Once the user has found out about the visa, she tells the PA that she wants to make airline reservations. She specifies her dates of travel and airline preferences and the PA then interacts with her to find appropriate flights.
A similar process will be repeated if the user wants to book a hotel, find a rental car, or find out about local attractions in the destination city. Booking a hotel as part of attending a conference could also involve finding out about a designated conference hotel or special conference rates.

