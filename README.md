# DTMF
DTMF Home Automation

DTMF BASED HOME AUTOMATION
Srividhya Sutharsan (2019504592)
Amrin Fathima (2019504004)
R. Nandhini (2019504552)


Introduction:
This project presents an effective technique for the user to monitor and control the house appliances and other equipments via the mobile phone. Generally, appliances used in our home are controlled with the help of switches. These days, you can see many technologies used in home automation projects. This project presents the controlling of home appliances using DTMF technology.

DTMF and it’s transmission:
DTMF is a tone composed of two sine waves of given frequencies. Individual frequencies are chosen so that it is quite easy to design frequency filters, and so that they can easily pass through telephone lines. Dual Tone Multiple Frequency is used to send signals when we press the telephone buttons. The data is typically sent over voice channels so in order to distinguish from human voice.

Tone generation in telephone:
 When one hits a button in the phone keypad, the phone generates two tones of different frequencies - one lower frequency and one higher frequency.The DTMF telephone keypad is laid out as a matrix of push buttons in which each row represents the low frequency component and each column represents the high frequency component of the DTMF signal. The commonly used keypad has four rows and three columns, but a fourth column is present for some applications. Pressing a key sends a combination of the row and column frequencies. For example, the 1 key produces a superimposition of a 697 Hz low tone and a 1209 Hz high tone. Initial pushbutton designs employed levers, enabling each button to activate one row and one column contact. The tones are decoded by the switching center to determine the keys pressed by the user.

Working:
DTMF (dual tone multi frequency) is the signal to the phone company that you generate when you press an ordinary telephone's touch keys. In this project “DTMF Based Home Automation System” we are going to control our home appliances wirelessly. Another important feature of this project is, that we are not going to use any microcontroller in it. DTMF controlled home appliances project works over mobile DTMF technology.
Here we have connected a cell phone using aux wire to the DTMF decoder circuit. Before explaining the further working of project, we need to know about the output of DTMF decoder for every key pressed.

CIRCUIT DIAGRAM:
In circuit diagram at Q1 LIGHT is connected, at Q2 FAN is connected and at Q3 TV is connected through relay driver IC. We have left Q4. Now when we press key 1 at the dial pad of mobile phone DTMF decodes this tone and generates a digital output given in table.

Now According to given output in table Q1 is HIGH and Q1 is connected with light so LIGHT is turned ON. If we want to turn OFF the LIGHT, we need to press key number 8. Because in the output of key 8, Q1, Q2 and Q3 LOW and Q4 are HIGH and we have not used Q4. So, it doesn’t matter that Q4 is HIGH or LOW. But our operation has been performed because Q1 is LOW in key 8’s output and rest of appliances not affected. Now is we want to turn on FAN so we need to press key 2 because by pressing key 2, Q2 is activated and rest of output are remain same. Now if we to OFF the FAN then we need to press key 8 again like before for as LIGHT. Now if we want to turn ON TV, we need to press key 4 and for tuning it OFF we need to press 8 like before. Now suppose we want to turn ON all of the appliances so we need to press key 7 (see table) and for turning OFF all the appliances, we need to press key 8 (see table).

Now if we need to ON LIGHT and FAN so we need to press key3 (see table). And now we want to ON TV so we need to press key 7 not key4 because we should keep the remaining appliances in the previous condition (ON). Now if we want to turn OFF only LIGHT so we need to press key6. Because we should again keep the other appliances turned ON except LIGHT.

So, we can control each of the appliances according to table output.

CONCLUSION:
This project describes the design and implementation of a home automation system using DTMF based communication technology. The system also provides a security system by way of adding auto answering system detecting DTMF inputs from the remote mobile and controls devices accordingly. This project gave us opportunity to understand, explore various communication technologies, especially DTMF tone detection, other discreet component circuits using relays, driver ICs, and process of making printed circuit boards.





Submitted for :
Project Display Competition organized by Electronics Engineers Association
At Madras Institute of Technology, Chennai
