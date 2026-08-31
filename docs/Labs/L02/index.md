# L2 – Truss Stress Analysis

For a few minutes research some guidelines/rules for Design for Additive Manufacturing. I used this website: https://www.addmangroup.com/wp-content/uploads/2024/08/ADDMAN_DfAM-Guide2024.pdf

From my research I have determined that some basic guidelines to follow are on page 9 of this website, listed here in this image:<img width="403" height="500" alt="Screenshot 2026-08-25 133536" src="https://github.com/user-attachments/assets/361fc261-518c-42e2-a3ab-efa7ae3af672" />

Further guidelines can be found on the following pages in chapter 1 from pages 8 to 16 for further rules/guidelines that DfAM in simple textbook terms.


For a few minutes research one FDM specific consideration and in 2-3 sentences describe how engineers work around it. Here is my source: https://www.hubs.com/knowledge-base/selecting-optimal-shell-and-infill-parameters-fdm-3d-printing/

Infill is my chosen consideration. Infill, according to my source, states that it is the inner structure of a model that is NOT solid. This creates a sort of "woven" structure like a chain-link fence or a spider web, holding the shells in place and adding strength to a printed model without having to waste too much material or time. Designers get around this by varying infill percentages and shapes.

When speaking with other students, I was told about orientation and how it keeps things neat, self-supporting angles are recommended to be 45 degrees to add strength prints. I explained how infill works and why it's more ethical than having a completely solid model.

# Project #2 Research 
Project #2 started with an in-depth bit of research that took about 19 minutes, my journey on this simple project was all about looking for a simple 3D SLA file that could be printed via a PrusaSlicer program. Looking on https://www.printables.com/ I managed to find all sorts of interesting prints. But the main parameters filtered through my mind as a constant reminder of what I had to obey by. The guidelines of this assignment stated as follows:
"No more than .25 inches tall; Print in PLA; No more than 2 inches by 2 inches; Print time < 1.5 hours; Must have a flat surface to build on; The print farm only has 18 workable printers, therefore you must get with a partner and print 2-3 on the same platform."
These guidelines reminded me I had to pick something mostly flat to not disobey the height restriction and I also had to pick something that could be printed fairly quickly. After a simple 4-minute long brainstorm of "what's flat enough to stay within the guidelines? Oh- I know, a coin!" I settled on the very first option I spotted, instantly hooked with the design. While ordinarily this would be a HORRIBLE idea to just pick the very first option and not investigate possible better or, this is a very simple assignment and any mistakes made along the way would only make for a better lesson learned.

<img width="357" height="268" alt="IMG_2244" src="https://github.com/user-attachments/assets/d0022740-b493-4aff-87e3-d7b6b0cf0a35" />
<img width="357" height="268" alt="IMG_2246" src="https://github.com/user-attachments/assets/1569dde8-f9c2-46d9-a8cf-8c252457fef9" />
<img width="357" height="268" alt="IMG_2245" src="https://github.com/user-attachments/assets/ca6d80b8-b049-4206-ba4d-deb0894cafd5" />

These images above were of the design I chose for this assignment. It was a thin fan-made token from a popular game that me and my little sister played together. I knew she would love having a fun knick-knack like this after I was done with this project so my inspiration for this chosen design was to give my little sister a gift after the assignment was completed.
# Project #2 Design/Printing
Shortly after class began on August 27th, I was paired up with 3 other students and we all agreed to pick our designs and print them at the same time. One student in the group chose a triangular satisfaction triggering device, another student picked a small rectangular whistle, and the final student picked a diamond pickaxe from the popular game of Minecraft. We all loaded up our G-code (fancy name for a special code that the printer can read on a flashdrive in order to print a STL file) to the program of PrusaSlicer. My model was very simple, a flat coin, so I did not need to use anything super advanced yet like supports and I used the default infill pattern and percentage of 15%. Thankfully my coin model was the perfect diameter of just below 2 inches so I had no need to scale it. The printer chosen was using a dark blue PETG polymer spool and was on the second back shelf of the printing lab. The estimated time for all of our prints displayed a rough guess of 32 minutes.

<img width="378" height="504" alt="IMG_2252" src="https://github.com/user-attachments/assets/0f587ff5-717f-46aa-9a24-ca8e03050a7a" />
<img width="536" height="714" alt="IMG_2253" src="https://github.com/user-attachments/assets/0a5dda36-86b5-4cd8-9ebd-8e2495645847" />

However, there was where a mistake made during this class period. As you can see in the images below of my sliced model, it stated 7 minutes estimation to print my model ALONE. Pairing up all 4 of our designs together into a flash drive and uploading it to G-Code for the 3D printer to read and decrypt and print, we learned that the total print time allocated was nearly 47 minutes and we were rapidly approaching the end of the class period.

<img width="5712" height="4284" alt="IMG_2249" src="https://github.com/user-attachments/assets/30ab9772-2254-4b82-b1d1-3add8a20d0b0" />
<img width="378" height="268" alt="IMG_2248" src="https://github.com/user-attachments/assets/0b7f114d-b3a5-466a-9a7a-57c3dfb0cb1f" />
<img width="378" height="268" alt="IMG_2247" src="https://github.com/user-attachments/assets/cc2207f6-5b34-4ee5-8e93-0e414e4b7fec" />
<img width="378" height="504" alt="IMG_2250" src="https://github.com/user-attachments/assets/f956c611-dc48-49e6-b029-7205cf529bd8" />

We were all greatly confused but upon further inspection with the aid of the professor of the class, we discovered that the culprit of the print time exceeding estimated expectations was... ME! As it would turn out, my print was within parameters, but it was too detailed compared to the other group memebers prints, and thus having to print multiple things at once, the machine had to optimize printing everything layer by layer, not all at once. This end result caused the optimized print time to add up from our estimated total of 32 minutes to being 15 extra minutes long. 
Below, you can see two recorded videos of the printing process and a recording of the G-Code on the display of the 3D printer. The printer used was a FDM from the UNCC print lab using a PETG polymer spool in a dark blue color. Copy and paste the links to see the videos.

https://github.com/user-attachments/assets/bf623bee-fee1-4a04-9a37-193a3212899d
https://github.com/user-attachments/assets/9569509a-3116-4cef-9150-96064b5ff19e

# Project #2 Outcome/Results
What resulted from the printing process came a hard lesson learned and some key notes for future prints. The first mistake was obviously discussed earlier with how the estimated time varies from printing alone vs printing multiple things at the same time. Another lesson can be observed from the final results of the print as seen below. You'll notice some straggling plastic strands and how some of the letters didn't come out very sharply. Research confirmed that due to the excess detail of the print and how it was downscaled resulted in small errors in the printing process, chaning the condition of the print from "mint" to "near mint" if you need a symbolic metaphor to compare.

<img width="2142" height="2856" alt="IMG_2293" src="https://github.com/user-attachments/assets/36249912-481b-414d-a3cb-4f19c6408cba" />
<img width="2142" height="2856" alt="IMG_2292" src="https://github.com/user-attachments/assets/4f5e08da-90a4-4dbe-9c73-1a75bf02300b" />

The final results were very good, but not precise. However, I settle for accuracy rather than precision as it is simply nature that can drastically affect how a print can develop. Bubbles, a loose spool fragment, a faulty nozzle, even human error can affect a print, so at the end of the day, I was very satisfied with the end results.

# Project #2 Lessons learned

I learned 4 things from this simple lab project. Firstly, NEVER settle for the first thing you find. There were hundreds, maybe even THOUSANDS of other options that could've given even better results than the first thing I found in my research. That lesson is purely on me and me alone. The second and third lesson came about during the printing process in the Thursday lab on August 27th. I discussed the mistake of assuming my print would be simple and easy and fast to print but not considering the fact that it wasn't a LONE PRINT was the second lesson while the third lesson came about after holding the finished project and leaving the laboratory. The third lesson was that not to rush things and assume the print is a valuable treasure. The file exists on the internet, so it's not like I can lose it, and the print is made of a plastic-type polymer that is fairly hard to destroy or damage, even intentionally. So, for me to try "gently" removing the print from the tray of the printer was a bit excessive and my professor quickly demonstrated that there is no need to view the final result as something fragile as a feather, it is plastic after all, so it's built to last. The fourth, and final, lesson I learned was actually learned on Friday August 28th. I was holding the print in my hands after my class that morning and I looked at all the errors in the print. I realized that it wasn't perfect, nor would it probably ever be. Not to sound like a Debbie downer or "glass half empty" style of thinking, I took a quick philosophical thought process and remembered the morning lecture on the 27th where my professor explained a bit about additive manufacturing and 3D printers and how they can be fallible. Anything can happen that can result in a ruined print, but you can always start over. Who knows? Maybe it takes 3 failed prints to make 1 perfect one? Maybe if I printed my small model 1000 times, I'd have one that would be perfect and 100 that have flaws? It's just the nature of statistics, probabilities, and the machine, anything can happen, but it's never too big of an issue to try and hit that "reset" button.

# Resources

https://www.addmangroup.com/wp-content/uploads/2024/08/ADDMAN_DfAM-Guide2024.pdf
https://www.hubs.com/knowledge-base/selecting-optimal-shell-and-infill-parameters-fdm-3d-printing/
https://www.printables.com/
https://www.printables.com/model/623366-five-nights-at-freddys-coin/files
