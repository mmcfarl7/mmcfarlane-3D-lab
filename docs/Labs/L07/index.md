# L07 - Linkage Mechanisms

## Research

<img width="800" height="104" alt="image" src="https://github.com/user-attachments/assets/4f2ce3e8-8f02-4836-aaff-4286487b01b6" />

For the first item I researched was called a "Variable Length Four-Bar Safety Joint" which was created around 2022 with the purpose of this linkage was to aid with absorption during drop tests between bars.

<img width="424" height="326" alt="image" src="https://github.com/user-attachments/assets/3c361099-81a7-4680-9884-f0f5746b6de2" />

This type of linkage can be used in the robotics industry and the agriculture industry according to this cited source: 

Baek, S. G., Moon, H., Choi, H. R., & Koo, J. C. (2022). “A New Cam-Follower Safety Joint Mechanism Design Based on Variable-Length Four-Bar Linkage for Robot Safety.” Journal of Mechanisms and Robotics, 14(1), 011004. DOI: 10.1115/1.4051518. Sungkyunkwan University
ASME/University publication record

The second researched linkage is a "Passive-Flexion Linkage Mechanism for a Robotic Finger". This device is used to allow the robotic finger to move actively when commanded but also flex passively when it encounters an external force.

<img width="608" height="355" alt="image" src="https://github.com/user-attachments/assets/d86b1b48-d4c8-45af-aa1d-9695d6d306f4" />

This linkage is used in the robotics industry as well as the automative warehouse/logistics industry. The cited sources are as follows:

UBTECH Robotics Corp. (2023). “Linkage mechanism, robotic finger and robot.” U.S. Patent Application US20230415354A1. Priority date March 10, 2021; publication December 28, 2023. Google Patents
US20230415354A1 patent record

(https://www.nature.com/articles/s41467-021-27261-0)

## Design & 3D Print

I jumped straight into my design and worked around the issues immediately when I started up Creo. Follow the images and the captions below them to learn the design process.

<img width="510" height="506" alt="Screenshot 2026-10-04 194957" src="https://github.com/user-attachments/assets/74a58e45-dfd2-4a6b-886d-41fedd70b5f6" />

I first started the design of a linked box on an axial hinge. I created the bottom of the cubic box with a 4.5-inch by 4.5-inch design where I shelled out the inside to create a hollow box.

<img width="474" height="620" alt="Screenshot 2026-10-04 195545" src="https://github.com/user-attachments/assets/08d5d353-6acc-4c23-8c64-82b651cb0728" />

Next, I created a face on the inside bottom part of the chest at the centroid. Yes, this part was absolutely necessary for creativity and whimsy purposes.

<img width="596" height="472" alt="Screenshot 2026-10-04 195943" src="https://github.com/user-attachments/assets/3548341d-c259-4d84-bb85-9ffd9995d689" />

Then, I created the lid of the box. I purposefully made it upside down since I was making it in the same part file, so I wouldn't be able to rotate these parts independently of one another. I used the same dimensions as the cubic base, but I shortened the lid to half the height of the box.

<img width="426" height="360" alt="Screenshot 2026-10-04 201342" src="https://github.com/user-attachments/assets/d9d82c11-315f-49f3-af21-36ddf8e39be5" />

Then, I designed the brackets where the box lid would rotate around an axle. This was the only tolerance in the design to be this size or 0.2-inches larger. But as you can see in the design, I created a flaw. While leaving a slot for the axle, I left the slot bulky and with no degrees of freedom to rotate. I did not discover this until later after printing. I extruded this design symmetrically to be 0.2-inches wide.

<img width="632" height="402" alt="Screenshot 2026-10-04 202737" src="https://github.com/user-attachments/assets/5b3b84ac-6b1b-44ce-948c-f9cd4c087869" />

Here is the segment where I mirrored the brackets to be across the middle plane of the chest. I did the same for the lid of the chest, only I made the distance between the two slightly larger, so they didn't overlap on top of each other, but instead fit right next to each other.

<img width="634" height="404" alt="Screenshot 2026-10-04 210718" src="https://github.com/user-attachments/assets/9c04af84-a3a5-4f2f-bab0-2dab8985c0a2" />

Lastly, I uploaded all my designs to Prusa Slicer and put the G-Code in my thumb drive. I didn't realize until later how unpractical but necessary those organic supports were. I had to end up cutting them out instead of tugging, removing piece by piece to prevent damage to the part. This was when I ran into 2 problems. Notice I designed the axle for the chest, I used a tolerance to prevent it from being too large but even when translating from the design to the printer, the printer is only capable of doing so much and thus a 0.1-inch difference between the two was unfortunately too large to fit. There was also another issue where a bracket broke off of the chest lid due to the organic supports taking the bracket off with them during removal. Thankfully, due to another brilliant stroke of genius, I was cleaning my ears when I looked at the Q-tip in my hands and had an idea! I rushed to grab a new one and snipped the ends off to create the final product shown below, very proud of the ingenuity on this one, simple, but even practical solutions pop up in everyday tasks when you take a step back.

<img width="684" height="812" alt="IMG_2688" src="https://github.com/user-attachments/assets/12921ba2-bbdc-4457-a4f1-a71f3e9c010d" />

Below you can see a video of the active G-Code and a snippet of the printing process. You can visibly see the organic supports that were printed to keep the part from collapsing in on itself.

https://github.com/user-attachments/assets/e88334a6-eb75-48ec-a5e6-edb83c051683

## Lessons Learned

Fortunately or unfortunately, there were 2 lessons learned and are as follows in order of discovery along with a possible remedy for each:
- Firstly, I designed the hinges to be to lose and flimsy and thus leading to one of them breaking off during the removal of the supports. This is fixed by two methods: More material to support the part or glue, but obviously that's only a temporary solution.
- Secondly, I had an issue with the tolerances around the hinges/brackets and the axle diameter, which led to the axle being too large to fit into the design. The remedy was comedic but using a Q-tip as the axle proved useful and hilarious. Another remedy was making the axle smaller or the holes bigger in order to mend the clearances.
I would argue my biggest failure could be either of the two since these two both dealt with an important function of the design itself. One being about a lesson we learned from lecture (tolerances) and the other being the main part of the design.



