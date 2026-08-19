# Paw & Order: The Broken Pipe Unit

An interactive dog-themed mystery game developed in R and Quarto during the RaukR 2026 Data Science With R course.

## Premise of the game

The international RuffR Data Science Conference is taking place at Campus Gotland in Visby. At 02:13, the conference’s R pipeline suddenly stops working. Someone has chewed the > from the native pipe operator:

suspects |
  filter(has_alibi == FALSE)

Twenty-five dogs are attending the conference, but only five members of the overnight Pipeline Response Team had access to the restricted project room.

The player must examine the evidence, test the suspects’ alibis and identify who broke the R code.

## The suspects
1. Sava Sniffer — a Serbian Hound from Serbia
2. Klara Cache — a Karst Shepherd Dog from Slovenia
3. Byte Biter — a Chihuahua from Mexico
4. Kommissar RegEx — a German Shepherd Dog with German–Austrian citizenship
5. Vera Vector — a Swedish Vallhund from Sweden

Each suspect has a different programming speciality, travel history and explanation for their whereabouts at the time of the crime.

## Gameplay

The investigation progresses through several stages:

On the landing page the player is introduced to the set up of the game and can see a map showing the suspects’ journeys to Visby.
On the next page, the player meets the five suspects and learns about their backgrounds, personalities and reasons for attenting the conference. 
Now the actual fun begins, the player can start to investigate and examine evidence from Git, the targets cache and server logs. This way the player can eliminate suspects. If unsure the player can reveal the clue and see the results to eliminate innocent suspects. 
However, the digital evidence is not sufficient for the final verdict, so the player sends of forensic evidence of bite-marks, hair and paw-prints found at the crime seen. 
With all this evidence the player will be able to identify the culprit. On the final page the player can enter their verdict and see if they were right or a criminal was set free ...

## Features

1. Multi-page Quarto website
2. World map showing the dogs origin
3. Suspect profile pages
4. Expandable clues with hidden findings
5. Simulated forensic datasets: bite-mark, dog-hair and paw-print
6. Shinylive dropdown menu to cast the verdict

## The fictional investigation uses four categories of evidence:

1. Git commit history and reflog
2. targets cache and workstation metadata
3. Conference server logs
4. Simulated forensic analysis of bite marks, hair and paw prints

All forensic measurements used in the game are fictional and created for educational/entertainment purposes.
