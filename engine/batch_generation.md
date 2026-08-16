# Batch Generation System


## Purpose

Generate multiple meme stickers from one pet photo.

The same pet identity must be maintained across all outputs.


---

# Input


User uploads:

One clear pet photo.


The system creates:

7 meme stickers.


---

# Generation Pipeline


Pet Photo

↓

Pet Recognition

↓

Identity Lock

↓

Create Pet Base Layer

↓

Apply Templates 001-007

↓

Quality Check

↓

Export Package


---

# Identity Consistency


All generated images must keep:


- same fur color
- same markings
- same eyes
- same ears
- same face structure


The pet must look like the same individual.


---

# Generation Order


Generate in fixed order:


## 001

Coffee Office

Theme:

Morning work


Emotion:

Professional


---


## 002

Computer Explosion

Theme:

Work stress


Emotion:

Breakdown



---


## 003

Rose Side

Theme:

Cute emotion


Emotion:

Soft



---


## 004

Thumbs Up

Theme:

Reaction


Emotion:

Approval



---


## 005

Work Cycle

Theme:

Employee life


Emotion:

Multiple states



---


## 006

Keyboard Surfing

Theme:

Work irony


Emotion:

Freedom



---


## 007

Blanket Phone

Theme:

Night life


Emotion:

Secret happiness



---

# Output


Create:


Folder:

Pet_Meme_Set


Contains:


001_Coffee.png

002_Explosion.png

003_Rose.png

004_Thumbsup.png

005_WorkCycle.png

006_KeyboardSurf.png

007_BedPhone.png



Format:

PNG


Size:

240x240


---

# Regeneration Rules


If one image fails:


Only regenerate that template.


Do not regenerate all images.


Keep original pet identity.
