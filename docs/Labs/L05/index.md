# L5 – Designing a Snap-Fit

## Instructions

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/367d5d43-3b64-4245-bbf2-e515d9b1c454" />

## Modeling/Documentation

I began my research into searching for common young modulus and elasticity of common PLA filaments using the "matweb" website. I found the density and other various data I needed to input into my design and thus I moved onto the next task of marking down all the listed "known variables". I knew the Safety Factor was 3.5, so I chose a transverse load of 2 lbf and an axial load of 7.5 lbf. I chose a thickness of 3 mm and worked the FBD around that, thus beginning my many sketches of the project. 

As you can see, the sketches originally started out with a box shape in mind. I wanted to be creative and design something silly but as I continued working, I started thinking ahead and realized the design would be cumbersome to model, and it would have an increased chance of failing due to human error. I designed the same sketch twice before scrapping the creative idea entirely and deciding to go for something much simpler: A Snap-On fit buckle. Using a rectangular design, I worked the math out to a point I was satisfied, but after the sketch was completed, I woke up the next morning to work on the model in Creo and suddenly started questioning my math.

Despite what these images state, the process goes top to bottom with the first design, then onto the final design (which is a lie, don't trust it), and finally the real design (final chosen design) with the calculations centered around the real design.

<img width="500" height="800" alt="IMG_2540" src="https://github.com/user-attachments/assets/f013a144-1c6e-4fa1-a6d9-43f419208030" />
<img width="500" height="800" alt="IMG_2541" src="https://github.com/user-attachments/assets/9707daae-8787-4aef-90ba-5da35242002c" />
<img width="500" height="800" alt="IMG_2542" src="https://github.com/user-attachments/assets/cdad1aee-dbb0-458f-9a6b-c2a30d4c9da0" />
<img width="500" height="800" alt="IMG_2543" src="https://github.com/user-attachments/assets/965eafd5-7a6a-44bb-9cf2-21e65315162e" />



## Parametrically Design

It was at this point I opened Creo and started to question how my measurements would appear in a modeling program, so I inputted everything I calculated and thus my model appeared... questionably shaped. The shape of the Snap-On fit was fine, there were no issues with the buckle itself, it was the notches that I had the visual issues with. I rechecked my math and everything seemed to work out unless I had made an error somewhere and failed to notice. There was a mistake I caught later, however, in the model. I should've added fillets to the inner corners of the buckle, which is a great way to help reduce the strain of the buckles themselves rather than leave everything rectangular.

<img width="250" height="250" alt="Screenshot 2026-09-16 140926" src="https://github.com/user-attachments/assets/3e41a694-df57-4f79-afc1-3a97aaa7921a" />
<img width="500" height="500" alt="Screenshot 2026-09-16 140920" src="https://github.com/user-attachments/assets/f4a79644-23e5-4ae8-9ae7-8ab7d2dea7e1" />
<img width="500" height="300" alt="Screenshot 2026-09-16 140823" src="https://github.com/user-attachments/assets/ca21f0fa-eeac-4c00-8e0a-7d47637699c2" />
<img width="300" height="300" alt="Screenshot 2026-09-16 140808" src="https://github.com/user-attachments/assets/6716bf47-89bc-499c-a933-5aec9cd379f1" />
<img width="500" height="400" alt="Screenshot 2026-09-16 135832" src="https://github.com/user-attachments/assets/4d026d53-93fc-4085-8e94-e1dd7e88fbe3" />
<img width="500" height="250" alt="Screenshot 2026-09-16 135819" src="https://github.com/user-attachments/assets/9a5248c7-88b2-4f09-bdab-1c1374a3516d" />



## 3D Print and Test

Here was the point I decided to start printing using the PLA filament. At first, the G-code seemed fine, and I decided to completely remove the infill as per a hint in the assignment stating it would be better to use a "hollow box beam" rather than a solid beam. I then started printing and tested out my first model, which was a 1:1 scale of what I modeled in mm. It failed because the model was so small that when it printed the 2 mm notches, the printer was too large and bulky and couldn't make the minute detailing of my design. To counter this, and retest, I scaled up my model from 100% to 200%, changed the infill to a default 15% and changed the pattern to gyroid as per a classmate recommended in lab, and thus printed again. 2 issues arose. Issue A) the printer ran out of filament halfway through the print. Issue B) The model itself, even when scaled up, revealed the biggest rookie mistake that hit me right in the pride: a measurement that was 1 mm too short. I had made the clasp, the thing that the buckle would SNAP to, the same length as the inner length of the buckle, making a perfect sliding fit rather than a snap fit. I was furious but it was a minor error to fix and, in the end, it simply was just a rookie mistake, but it does show how just one small millimeter can make or break the whole design.

The model itself was flat, so I did not use supports or painted anything similar since it was a simple design. Painting on supports did seem useful when I was taught about it in class, but I have yet to see any need for such supports yet. The printing time varied but on the first print the time was 4 minutes with no infill and the 200% scale model was 14 minutes with a gyroid infill pattern of 15%.

<img width="1000" height="600" alt="Screenshot 2026-09-17 173922" src="https://github.com/user-attachments/assets/564d78f4-8f24-4f8b-987e-62a1f0cbf7f8" />
<img width="500" height="180" alt="Screenshot 2026-09-17 173822" src="https://github.com/user-attachments/assets/49e3423f-884b-4cbf-9fc6-25a91f342b13" />
<img width="600" height="300" alt="Screenshot 2026-09-17 173333" src="https://github.com/user-attachments/assets/527af01d-0fa1-4618-bcda-bd1c56aa41a1" />
<img width="750" height="400" alt="Screenshot 2026-09-17 120718" src="https://github.com/user-attachments/assets/e223eaf9-bec3-4e1c-98cb-0a19043ff369" />

First model printing (100% size no infill): 

https://github.com/user-attachments/assets/cbd92fec-30cc-4e89-89cc-fc36c46d5c30

Second model printing (200% with infill): 

https://github.com/user-attachments/assets/7480db76-4cb1-4198-b9fe-9c053534c83b

Here you can see the final models with the 200% scale model on the left and the normal model on the right. The right model, as you can observe was too small for the printer to print the notches while the 200% model does have the notches, but as you can see because of my error in measurements, the notches don't touch.

<img width="1000" height="750" alt="IMG_2545" src="https://github.com/user-attachments/assets/aa7209e5-2d85-4508-a40e-385345cfb08f" />

## Lessons Learned

By the end of this 4–5-hour project over the course of 2-3 days, I had made a total of 3 or 4 mistakes. The first mistake was not using the fillets in the inner corners which would've helped reduce the strain-stress of the bending of the beams. The second mistake was printing without checking to see if the printer was almost out of filament (rookie mistake), and the last mistake was making the measurements of the clasp the same as the inner length of the buckle instead of adding just 1 or 2 measly millimeters. That rookie mistake will always be around, and everyone makes them, which is an unfortunate truth that I'm only human and can still make errors even when the model might suggest otherwise. 

## Resources

https://www.matweb.com/search/DataSheet.aspx?MatGUID=ab96a4c0655c4018a8785ac4031b9278&ckck=1  (PLA Spreadsheet)

https://www.freeconvert.com/mov-to-mp4 (For uploading videos)
