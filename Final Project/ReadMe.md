**NAMES OF COLLABORATORS HERE**
Big Coop (CJM424) , Martin Eckardt (me424)

## Project Plan can be found on this notion:
https://www.notion.so/martineckardt/IDD-Final-Project-Physical-Bound-Tokens-06b33dad5666426f9ae2378c47a4595d

## Design Process

Here is the story board that would be the ideal interaction of a succesful package being delivered:

![Copy of Note Nov 29, 2022](https://user-images.githubusercontent.com/112036223/205970907-e0778724-4273-4379-9f92-fd699730b72f.jpg)

Storyboard showing the package going above the temperture agreed upon all the parties for a temperature sensitive package:

Storyboard showing the package reaching the threshold of accelaration agreed upon the two parties for a fragile package:

![Note Nov 29, 2022 (2)](https://user-images.githubusercontent.com/112036223/205971469-3cbad939-2d9a-4a3d-bc0d-2eed2ea74bc7.jpg)


## Functioning Project

Code for the project is in the following files:

Code that has the library for the NFC reader and writer to be translated from C to Python so our Pi can interact with the writer. Also has the correct protocol for an iphone to be able to read the chip.

https://github.com/JacobEverly/Interactive-Lab-Hub/blob/Fall2022/Final%20Project/adafruit_st25dv16.py

Code that generates the report and writes it to the NFC chip for the scanner to read:

https://github.com/JacobEverly/Interactive-Lab-Hub/blob/Fall2022/Final%20Project/writer.py

Code that creates the Private and Public Keys and makes the database that is able to verifty the reports authenticity:

https://github.com/JacobEverly/Interactive-Lab-Hub/blob/Fall2022/Final%20Project/verifier.py

Video of the reports being Generated Properly



https://user-images.githubusercontent.com/112036223/205968464-9f75841c-ee38-4975-8290-1de0c72a671e.mov


Video of a report being verified



https://user-images.githubusercontent.com/112036223/205968704-84977046-f95a-4536-b7a4-6a09e5f0b2b9.mov


Video of a report being denied due to the wrong signature being provided



https://user-images.githubusercontent.com/112036223/205968848-76414c57-22be-47b4-af8e-965002b6218d.mov


# Interactions with User

Video of the package being delivered


https://drive.google.com/drive/folders/11y1TmAnFA99VmxU-SccPMnDfu82Z8mN5?ths=true


Video of the package being delivered and being dropped

https://drive.google.com/drive/folders/11y1TmAnFA99VmxU-SccPMnDfu82Z8mN5?ths=true
