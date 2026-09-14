# L4 - Benchmark a Parameter

## Parameter
For this lab, we were tasked with designing a model that would push the 3D printers to the test. Our teacher explained some of the parameters such as dimension calibration, pull strength, tolerance gauge, and even overhang angles. Using a small structure known as "Benchy" the tugboat, he explained that if you could print the small tugboat model on your printer, then it was calibrated and would function well with most modeling tasks. He then asked us to test the parameters of our printers. The printers we have access to are known as "Prusa CORE One" with HF0.4 mm nozzles. I decided to test the tolerance gauge of the printer, how well the printer can print two or more items designed to fit together in an assembly. I took inspiration for my design with this example given in class.

<img width="500" height="155" alt="image" src="https://github.com/user-attachments/assets/f2f3b58c-9fc3-4cb9-9be2-09d182731281" />

I predicted that my model would NOT pass the tolerance test to the 0.3 mm guidelines stated in the documentation. I predicted that it would maybe reach 0.4 mm before it wouldn't be able to fit.

## Design + Print

Using inspiration from the tolerance test provided by my instructor I decided to modify the design to be more simplistic, going back to my preschool days of sorting blocks into block-shaped holes. The test was to make all the holes a smaller and smaller diameter while the blocks remained the same. For neatness, I decided to print 5 blocks that were EXACTLY ALIKE and just as a measure in case I lost a peg. At the same time, I didn't realize this until later, I was testing another function of the printer: its ability to recreate the same item multiple times, then I could observe the differences between the pegs. I wasn't sure what benchmark that would test, exactly, but I thought it was a good sub-benchmark to add onto the main parameter I was testing.

<img width="500" height="600" alt="IMG_2400" src="https://github.com/user-attachments/assets/bc332a8c-ff98-4132-844d-37c0b9bb6bc8" />

<img width="500" height="600" alt="IMG_2402" src="https://github.com/user-attachments/assets/bea6148e-0968-449f-a72c-97f2c3fd6f8a" />

As you can see in the images around this text, I had decided to make the holes 0.5 mm wide on the far left and decreased the square peg's diameter by 0.1 mm for each peg going right until it reached just 0.1 mm over the square block's diameter.

<img width="500" height="600" alt="IMG_2403" src="https://github.com/user-attachments/assets/7aaf9fcd-8473-405d-bd0c-4b4b7714c19f" />

<img width="500" height="600" alt="IMG_2404" src="https://github.com/user-attachments/assets/638e4cfc-2426-403e-b016-7e5089244a68" />

<img width="300" height="300" alt="IMG_2405" src="https://github.com/user-attachments/assets/ae2e3bf3-c28f-4c92-91a0-332adaa43674" />

The design was very simplistic and would be good enough to put the printer to the test. Unfortunately, I did need to scale down the design to get the printout quickly, also leading me to alter the infill pattern to triangular and reduced the model to 75% scale compared to its original size to try and reduce the estimated 30 minutes to half that time so other people could use the printer after me. I would've felt really bad for hogging a printer when other students needed it too. Thankfully, however, these changes would be minimal and wouldn't affect the prints purpose, only the scale. If anything, I felt it would better the test by reducing the gap at which I set the parameters.

<img width="300" height="400" alt="IMG_2433" src="https://github.com/user-attachments/assets/d1f66b48-ea35-4721-a4c0-541a7a54bca0" />

<img width="200" height="200" alt="Screenshot 2026-09-10 123705" src="https://github.com/user-attachments/assets/e99cf830-7d13-4778-b2fb-99b5f663cf79" />

<img width="300" height="300" alt="Screenshot 2026-09-10 123716" src="https://github.com/user-attachments/assets/b479e0ae-8c0e-4ca8-9102-6a3fe9802a72" />

<img width="200" height="200" alt="Screenshot 2026-09-10 123726" src="https://github.com/user-attachments/assets/ae57dcdd-551e-4d8f-9506-c811ce559eba" />

Here you can see the final print and even a video I took of the printing process. I used PETG filament, which took longer but it was stronger than PLA, so I didn't mind the cost.

<img width="300" height="400" alt="IMG_2434" src="https://github.com/user-attachments/assets/18a8813d-2539-48ad-9fe4-6a5f8ad6c7e4" />

<img width="300" height="400" alt="IMG_2435" src="https://github.com/user-attachments/assets/078d20b9-dd3a-4dd4-99eb-b9bc51dce2b6" />

https://github.com/user-attachments/assets/da9a34a2-81fa-476e-af2d-c9f369f0336d

## Lessons Learend

<img width="300" height="400" alt="IMG_2438" src="https://github.com/user-attachments/assets/39677c15-8e96-4e63-96ba-58f831a2617a" />

<img width="300" height="400" alt="IMG_2439" src="https://github.com/user-attachments/assets/75348dca-952c-44f8-8e0f-4aac1b1237ca" />

As you can see in the images provided above, the print was a success to a degree. As I stated before, I had to scale the print down to 75% of what the dimensions originally were in millimeters. Upon testing my print, I discovered that all the pegs were not only identical to the melted plastic marks on the flat bottom surfaces, but they all only managed to fit into the very left hole, the biggest one of the five I created. It was a tight fit, but it did pass the test. I was originally a little disappointed but then I remembered my prediction and the scale at which I toned down the model. See what I'm getting at here? 75% of 0.5 if 0.375, and 75% of 0.4 millimeters is 0.3 millimeters. As it would turn out, my prediction was almost exactly accurate. I predicted that my print would fail around the 0.4 mm mark of my ORIGINAL model, not the scaled down version. Thus, when I did the test, the print failed at the 0.4 mm mark, or the 0.3+ mm added diameter hole. Ergo, my print did indeed pass the printer standard guidelines of 0.3 mm plus tolerance of holes and pegs between assembled parts. 

While there are many factors as to why my results matched the guidelines, it's difficult to say exactly which factor had the most part. The nozzle might've been too wide, the printer might've had a blip or an error and thus made the holes too wide, for all I know there is human error in my test and I could've overlooked something. I believe that I covered all grounds, but the fact is that while something may design to fit together on paper, it doesn't work like that with printed filaments because you're melting something and expecting it to make a perfect shape, which isn't realistic.

A mistake I made along the way was reaching a hiccup when starting a print. I accidentally used the wrong label in the G-code to put PLA instead of PETG, which would've resulted in a horrible collapse or a disastrous print since PETG and PLA are two completely different filaments. It would've been like using ink instead of pencil on a scantron sheet, it just wouldn't work out for most jobs. Another mistake is the text on the final print, which isn't neat or clean. Next time I should widen the numbers and letters, so the printed filament won't accidentally stick together and end up looking like the mess you see in the image above.

After all this was said and done, this whole project took me 3-4 hours over the span of 3 different days to complete from design to printing to coding this portfolio.

## Resources

https://www.3dbenchy.com/dimensions/ (Benchy Website for standardized guidelines and printer testing)

[PL_3DP_Design_Rules_EN.pdf](https://github.com/user-attachments/files/32198644/PL_3DP_Design_Rules_EN.pdf)  (Guidelines for standardized printer benchmarks)


