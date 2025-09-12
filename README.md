Task 1 : Operation SILENT CHAIN 0   
The raw patrol reports contained a suspicious string that stood out as Base64. 
Decoding it revealed the hidden codeword.
<img width="973" height="78" alt="image" src="https://github.com/user-attachments/assets/2f7b9983-fbfc-41fa-a3ef-b2942d8772b9" />  
Flag : FL1TZ{SC_Alpha15}  

  
Task 2: Operation SILENT CHAIN 1  
The folder password is the previous flag : SC_Alpha15
The recovered email dated [2025-07-10 22:50Z] – Comms Channel Update referenced a secondary channel for secure comms.
This alias was identified as the handler’s online identity for covert updates.
<img width="940" height="284" alt="image" src="https://github.com/user-attachments/assets/6526e056-e670-4e02-834a-39d63ef97f4c" />  
Flag: FL1TZ{@syriaobserver}


Task 3: Operation SILENT CHAIN 2  
The alias @syriaobserver was mentioned as active on technical forums, hinting at a digital footprint tied to code or tool distribution.
Following this trail led to a GitHub account with multiple repositories. One repository, net_watchdog, contained a lightweight Python tool for sysadmins.
Inside the source code and configs, a file named OPSEC_Notes.txt revealed the operative’s real identity 
<img width="959" height="558" alt="image" src="https://github.com/user-attachments/assets/be550776-4a5a-4807-901f-52e025aa37b5" />  
Flag : FL1TZ{David_Holmes}


Task 4 : Operation SILENT CHAIN 3  
David Holmes’s GitHub account contained a repository AstraNet (Corporate Solution), which included a contact file revealing the CEO’s first name (Richard) and that his last name starts with V.
<img width="998" height="665" alt="image" src="https://github.com/user-attachments/assets/5800799e-9a6b-403a-8a9e-6264e95fcc13" />
Using David’s full name and the company name, and following the instruction to “follow Holmes’s professional footprint and technical contributions,” his LinkedIn account was located.
<img width="975" height="672" alt="image" src="https://github.com/user-attachments/assets/0e507637-f448-4334-8355-2d2c51bc8859" />  
In the project section, the AstraNet repo was linked, along with a thank-you message for Mr. Vance, revealing the CEO’s full name: Richard Vance.
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/ba0ad5b2-13e5-4463-8740-01aa26b3b1bf" />  
Flag: FL1TZ{Richard_Vance}



  
Task 5: Operation SILENT CHAIN 4  
A leaked email from Richard Vance authorized a high-priority air transfer.
The aircraft was a Gulfstream G650, chartered through Gama Aviation.
Following the trail, the key was Gama Aviation’s website: searching for the G650 led to an article showing the plane with its registration number N650GA.
<img width="975" height="522" alt="image" src="https://github.com/user-attachments/assets/d5b561b9-b560-4203-8610-86b5899f1764" />  
From there, all other details about the aircraft, including its registered owner and manufacturer serial number, were easily traceable(just google it).  
Flag: FL1TZ{Gulfstream_Aerospace_Corp_6424}



Task 6: Operation SILENT CHAIN 5  
The final task provided a corrupted image. Opening it in a hex editor and removing all junk data outside the JPEG header (FF D8) and footer (FF D9) revealed a photo of an abandoned house in the desert. 
<img width="1013" height="624" alt="image" src="https://github.com/user-attachments/assets/edaf57c7-a097-41e4-b521-675cc8640dcf" />  
At the bottom of the image, a code was visible 37SBV3944144639 , which turned out to be MGRS coordinates. Decoding these coordinates with any online tool gave the latitude and longitude, yielding the last flag.
<img width="975" height="817" alt="image" src="https://github.com/user-attachments/assets/95f99596-006f-416a-a4f7-7e7ddbb20305" />  
Flag: : FL1TZ{35.611226_36.123452}













