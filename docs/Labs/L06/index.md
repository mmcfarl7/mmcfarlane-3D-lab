# L6 - Design Fit for an Artifact

## Documentation

### Parametrically Design

The requirements for this lab were to design a snap fit for an artifact taken from class using a gauge read imperial measurement caliper on said artifact. My artifact I selected was a Stepper Motor as shown in the images below, followed by the measurements used to guide my design. It was a simple cylindrical snap fit, as shown below.

<img width="500" height="570" alt="IMG_2553" src="https://github.com/user-attachments/assets/480462da-9b49-4dae-95bd-8a695e0efc87" />

Image displays 1.06 inches circular diameter.

<img width="500" height="570" alt="IMG_2554" src="https://github.com/user-attachments/assets/62cb01b3-d6c4-4b5c-9298-532a6bb73e22" />

Image displays 1.10 inches diameter with rectangular notch, which adds 0.04 inches from the circular diameter. I noted this for the model.

<img width="500" height="570" alt="IMG_2555" src="https://github.com/user-attachments/assets/0617901b-4d38-41a5-bcad-f9567b44fc43" />

Image displays 0.74 inches height.

<img width="500" height="570" alt="IMG_2556" src="https://github.com/user-attachments/assets/a660a1a4-9ce8-4e7a-8851-a74e059b1f5e" />

<img width="500" height="570" alt="IMG_2557" src="https://github.com/user-attachments/assets/3b04d97a-438d-4964-bfbe-e6d7eefa178a" />

Images of Stepper Motor.

### Modeling

I didn't change many values other than trying to parametrically logic my way through designing the snap fit to "entrap" the artifact. My professor stated that this will be tested and it's tested to see if the fit works or not, not if the fit is practical or can be removed, so I decided to ensure the fit would FIT around the artifact. While aesthetically pleasing, the CAD model I created in Creo was somewhat difficult to make, requiring many mirrors across the front and side planes of the model. As shown below you can follow the process I took to design the snap fit in Creo. First, I created the base, a round circular cylinder that was wider than the artifact to aid with the development of the pegs of the snap fit, which would fit around the perimeter of the artifact. I then mirrored the extrusions and designs across the central Front and Side planes to ensure symmetry.

<img width="400" height="500" alt="Screenshot 2026-09-23 111644" src="https://github.com/user-attachments/assets/202562b0-ab51-49f8-aa6b-4cf44a59608f" />

First is the base.

<img width="400" height="400" alt="Screenshot 2026-09-23 112118" src="https://github.com/user-attachments/assets/679f77a9-a0ad-4267-aaaa-325e8a4ddc15" />

Then I added the dimensions for the pegs to extrude later.

<img width="400" height="400" alt="Screenshot 2026-09-23 112653" src="https://github.com/user-attachments/assets/0a3b8fbf-8ae4-4eea-9993-fd19f90523e7" />

Mirroring the dimensions for symmetry.

<img width="400" height="566" alt="Screenshot 2026-09-23 113147" src="https://github.com/user-attachments/assets/eb4aa7d4-3b7c-4b99-b96d-f2a1ae8f04c4" />

Designing the cliff-edge where the snap would be audible and well ensnared around the artifact. Removal was planned to be difficult.

<img width="400" height="500" alt="Screenshot 2026-09-23 113426" src="https://github.com/user-attachments/assets/61ba244c-ec3f-4f64-911f-0ee64bcd1ebd" />

Revolving the extrusion sketch and later mirroring the revolution around the central Z-axis.

<img width="400" height="500" alt="Screenshot 2026-09-23 113613" src="https://github.com/user-attachments/assets/ce8a79d3-74ec-45ce-befb-7606f5056fc1" />

Final Model.

<img width="400" height="500" alt="Screenshot 2026-09-23 113622" src="https://github.com/user-attachments/assets/d7770d62-aed9-4684-b038-f1231bf0ba29" />

Final Model Tree of progress including all the mirroring done for the dimensions around the central Z-axis.

### Printing

Using Prusa Slicer, I uploaded the G-Code to a thumb drive and used a Prusa Core ONE printer with a 0.4mm nozzle. I used orange PLA filament and printed out my final model, which was roughly one and a half inches in diameter and two and a half inches in height. I used the default settings on the print including 15% infill and a rectilinear infill pattern. The printing itself had one minor hiccup where I originally used a faulty printer that wasn't feeding filament correctly, so I had to switch printers and try again after a quick catch. Otherwise, the printing went through smoothly and originally, I was worried the painted organic supports would mess with the final print, but to my surprise they not only were super easy and clean to remove, but they also barely affected the final model at all aside from one little clump on a peg, but otherwise, the model was complete and as you can observe below in both the video and images, you can follow the G-code of the print and the printing process to the final product.

<img width="400" height="500" alt="IMG_2629" src="https://github.com/user-attachments/assets/613db6f5-d938-446b-a94e-7a3533026f34" />

<img width="400" height="500" alt="IMG_2630" src="https://github.com/user-attachments/assets/f664213b-6328-408d-82e2-390a359d8914" />

<img width="400" height="500" alt="IMG_2631" src="https://github.com/user-attachments/assets/678f5628-bd48-4e62-8025-d9580f0b0648" />

<img width="400" height="500" alt="IMG_2632" src="https://github.com/user-attachments/assets/ae0ffd70-c8f1-46a6-8aa3-ffb09080b819" />




## Lessons Learned/Resources

The only real mistake was making the pegs a bit too wide, it would've been wiser to make the pegs thinner so they wouldn't catch on the blue rectangular notch on the stepper motor, which the final test did show it was slightly in the way, but it also would've aided in flexibility to have something less bulky. In the part's defense though, it is snapped together really secured. Thankfully, my testing did prove it does snap fit with a bit of effort. Again, this design wasn't supposed to be pretty or practical, it just had to work. While removal of the stepper motor proved difficult, the part does pass the snap-fit test and thus I have achieved a new level of understanding for tolerances and clearance fits when designing parts.


https://www.freeconvert.com/mov-to-mp4   (Used to convert files for video)
