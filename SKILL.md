# PetMemeGenerator Skill v2.0


# Overview


PetMemeGenerator is an AI pet meme sticker generation system.


Purpose:

Transform user's real pet photos into cute internet meme stickers.


The system must preserve the original pet identity and apply predefined meme templates.



# Core Pipeline


User Upload Pet Photo

↓

Pet Recognition

↓

Pet Identity Lock

↓

Pet Extraction

↓

Action Adaptation

↓

Template Selection

↓

Meme Composition

↓

Quality Check

↓

Export PNG 240×240



# 1. Pet Identity Lock


The user's pet identity is the highest priority.


Always preserve:


- species

- breed characteristics

- fur color

- fur pattern

- eye color

- ear shape

- face structure

- unique markings


The same pet must remain recognizable across multiple generated images.



Never change:


- animal species

- face identity

- natural markings



# 2. Pet Extraction Engine


Before applying templates:


Extract the pet subject.


Keep:


- eyes

- ears

- nose

- fur edges

- paws


Remove:


- background

- furniture

- humans

- unrelated objects



Create a clean pet layer.



# 3. Meme Transformation Rules


Apply subtle meme style:


Default transformation:


Head:

horizontal:
105%-115%


vertical:
85%-95%



Purpose:


- rounder face

- cuter appearance

- internet meme feeling



Do not distort identity.



# 4. Animal Action Adapter


Animals cannot use human anatomy.


Rules:


Cats:

Use paws.


Dogs:

Use paws or mouth.


Birds:

Use claws.


Small pets:

Use natural paws.



Never generate:


- human fingers

- human hands

- human arms

- extra limbs



# 5. Template System



## Template001

Coffee Office Pet


Theme:

Business pet working


Elements:


- suit

- coffee

- briefcase


Action:

Holding coffee



---


## Template002

Computer Explosion Pet


Theme:

Work breakdown


Elements:


- computer

- keyboard

- explosion


Action:

Working on keyboard



---


## Template003

Rose Side Pet


Theme:

Cute emotional meme


Elements:


- red rose

- white background


Action:

Standing beside rose



---


## Template004

Thumbs Up Pet


Theme:

Reaction sticker


Elements:


- speech bubble

- 棒


Action:

Pet approval gesture



---


## Template005

Work Cycle Pet


Theme:

Employee life


States:


不想干

烦死了

不干了



---


## Template006

Keyboard Surfing Pet


Theme:

上班的意义是下班


Elements:


- ocean

- keyboard

- simple tie


Action:

Standing on keyboard



---


## Template007

Blanket Phone Pet


Theme:

Secret phone usage


Elements:


- blanket

- smartphone

- bedroom


Action:

Looking at phone



# 6. Batch Generation Mode


When user requests a pet meme set:


Generate:


001 Coffee

002 Explosion

003 Rose

004 Thumbsup

005 Work Cycle

006 Keyboard Surf

007 Blanket Phone



All images must keep the same pet identity.



# 7. Quality Check


Before output:


Check:


Identity:

✓ Same pet


Anatomy:

✓ No human hands

✓ No extra limbs

✓ No extra eyes


Composition:

✓ Pet fits template

✓ Correct position


Style:

✓ Meme style

✓ Slight blur

✓ Casual image feeling


Output:


Format:

PNG


Size:

240×240



If failed:

Regenerate.



# 8. Template Loading Rules


Each template folder contains:


background image


config.json


action.json


prompt.txt



Template files define:


- composition

- position

- action

- style



# Final Goal


Create:

"My pet became an internet meme."


The result should feel like a real shared pet sticker,

not a random AI animal image.
