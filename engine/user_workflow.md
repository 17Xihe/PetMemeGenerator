# PetMemeGenerator User Workflow


## Step 1 — User Upload

User uploads a pet photo.


Supported:

- cat
- dog
- rabbit
- hamster
- bird
- other small pets


The system analyzes:

- species
- face
- fur color
- unique markings
- body position


---

# Step 2 — Pet Confirmation


Before generation:

Confirm the detected pet.


Example:

"检测到这是一只三花猫。

是否使用这只宠物生成表情包？"


If identity is unclear:

Ask user to upload a clearer photo.


---

# Step 3 — Template Selection


Provide available templates:


1.
Coffee?

Business pet meme


2.
Computer Explosion

Work breakdown meme


3.
Rose Side

Cute emotional meme


4.
Thumbs Up

Approval reaction


5.
Work Cycle

Employee life cycle


6.
Keyboard Surfing

Work meaning meme


7.
Blanket Phone

Secret phone meme


---

# Step 4 — Generation Process


After template selection:


Execute:


Pet Extraction

↓

Identity Lock

↓

Action Adaptation

↓

Template Composition

↓

Meme Style Adjustment

↓

Quality Check


---

# Step 5 — Output


Generate:

- PNG
- 240×240


Suitable for:

- WeChat sticker
- social sharing


---

# Step 6 — Multiple Generation


When generating multiple stickers:


The same pet identity must remain unchanged.


Only change:

- scene
- action
- emotion


Do not change:

- pet appearance

- ## Output Mode Lock（输出模式锁）

默认输出：

MODE = FULL_PACK


当用户上传宠物图片时：

必须生成完整宠物表情包套组。


默认数量：

TEMPLATE_COUNT = 7


生成：

Template 1
Template 2
Template 3
Template 4
Template 5
Template 6
Template 7


除非用户明确指定：

- 只生成某一个模板
- 单张测试
- 生成第X张


否则禁止：

❌ 单张输出

❌ 随机选择模板

❌ 跳过模板


---

## Full Pack Consistency

所有模板必须保持：

同一只宠物

保持：

- 毛色
- 花纹
- 眼睛
- 耳朵
- 脸型
- 体型


禁止：

不同模板出现不同宠物。
