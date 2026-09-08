---
name: dondi-ai-seedance-cinematic-prologue
description: Turn a film concept, character references, and short scene idea into a structured Seedance 2.5 cinematic prologue workflow. Use this skill whenever the user wants to create a movie prologue, cinematic opening, mystery thriller introduction, suspense sequence, flashback opening, or a multi-shot film scene with continuity, mood, and timecoded Seedance prompts.
---

# Dondi AI Seedance Cinematic Prologue

This skill turns:

**film concept + optional character / location / prop references + a short scene idea**

into a complete **cinematic prologue generation package for Seedance 2.5**.

The goal is not a casual vlog, ad, or montage for social media.

The goal is:

**a cinematic opening sequence with clear mood, continuity, shot design, and dramatic progression.**

---

# 1. Default Output

Unless the user asks otherwise:

- Target use: **film prologue / opening sequence**
- Output language: **English prompt**
- Spoken dialogue: **use the user's language**
- Tone: **cinematic**
- Form: **multi-shot film sequence**
- Default unit for Seedance generation: **1 scene or 1 short sequence at a time**
- Default visual mode: **controlled cinematic realism**
- Camera language: **film camera behavior, not vlog camera behavior**
- Performance: **restrained, readable, psychologically grounded**
- Audio: **diegetic sound first, music optional**
- Editing rhythm: **slower and more intentional than a vlog**
- Continuity priority: **very high**

If the user is building a longer prologue, do not force the whole thing into one giant prompt.
Break it into:

**Prologue → Sequence → Shot → Seedance Prompt**

---

# 2. Minimum User Input

Minimum useful input:

1. **Short concept or scene premise**
2. **Who the main character is**
3. **What happens in this part of the prologue**

Optional but highly useful:

- character reference image
- costume reference
- location reference
- prop reference
- tone reference
- target duration
- genre
- dialogue preference

Example:

> 한국 미스터리 스릴러 영화 프롤로그.
> 어린 여배우가 어릴 적 사고 사건의 진실을 목격한다.
> 어두운 거실, 깨진 가족사진, 어머니의 일기, 피, 충격적인 진실.
> Seedance 2.5용으로 시퀀스와 샷 프롬프트를 만들어줘.

That is enough.

---

# 3. Ask Only When It Materially Changes the Scene

If enough information is already present, start immediately.

Ask only when necessary:

- Is this a **realistic thriller**, **supernatural thriller**, **crime mystery**, or **psychological mystery**?
- Should the prologue be **dialogue-light** or **completely silent**?
- Is this prologue meant to end with a **cliffhanger**, **reveal**, or **mystery image**?
- Are there any **must-preserve character / costume / prop references**?

Ask at most **1–3 questions**.

If the user says "알아서 해줘", choose the most cinematic default and proceed.

---

# 4. Core Generation Goal

Generate a **cinematic film prologue**, not a vlog and not an advertisement.

The sequence should feel:

- intentional
- atmospheric
- narratively controlled
- visually coherent
- emotionally restrained
- dramatically escalating

The scene should introduce:

- the world
- the tone
- the main mystery or emotional wound
- one key dramatic question

The prologue should make the viewer want to continue.

---

# 5. Film Prologue Story Engine

A strong prologue usually follows this kind of progression:

**Atmosphere → Hint of abnormality → Discovery / encounter → Emotional reaction → Final image or cliffhanger**

Alternative rhythm:

**Ordinary surface → Unease → Strange detail → Reveal → Silent aftermath**

Do not turn the prologue into:

- a full explanation dump
- a trailer
- a music video
- a random montage with no spatial logic
- a fast-cut social clip
- a melodramatic overreaction reel

The prologue should reveal just enough.

---

# 6. Reference Identity Rule

When a character reference image is provided, treat it as the **identity anchor**.

Use the reference primarily for:

- face
- identity
- age impression
- skin appearance
- hair
- body proportions
- distinctive facial or bodily features

Do not automatically inherit unless requested:

- background
- original pose
- original lighting
- original camera angle
- original composition

If costume must be preserved, say so explicitly.
If costume is not provided, design one suitable for the scene and keep it locked.

Reference template:

`@Image 1 defines the MAIN CHARACTER's face, identity, hair, skin appearance, age impression, and body proportions. Preserve the same person across the entire sequence. Do not inherit the original background, composition, pose, or lighting unless specifically requested.`

---

# 7. Cast Continuity

Across every shot, lock:

- same face
- same hair
- same age impression
- same body proportions
- same wardrobe unless story-motivated change occurs
- same accessories
- same emotional continuity

If multiple characters appear:

- define each one separately
- clearly distinguish them visually
- specify when they enter and exit
- keep their appearance stable

No random face morphing.
No extra characters suddenly becoming prominent without story reason.

---

# 8. Costume Continuity

Wardrobe must stay stable inside a sequence unless a story event changes it.

Track:

- top / outerwear
- bottom
- shoes
- school uniform details if applicable
- accessories
- visible stains, tears, wetness, blood, dust, or damage

If the scene includes blood, rain, ash, or dirt, track the progression.

Example:

- clean sleeve
- sleeve touches blood
- small dark stain appears
- stain remains visible in later shots

Do not reset wardrobe state by accident.

---

# 9. Prop Continuity System

Any recurring object must follow a clear state timeline.

Track important props such as:

- family photo frame
- knife
- phone
- letter
- charm / talisman
- umbrella
- bag
- flashlight
- door handle
- blood trail
- glass
- key
- school ID card

For each important prop, define:

- starting state
- physical position
- visible condition
- who is holding it
- ending state

Never allow a prop to:

- change shape or color randomly
- duplicate itself
- teleport between hands
- disappear without a cut or reason
- revert to an earlier state

---

# 10. Location Continuity

The space must make physical sense.

Track:

- entrance
- hallway
- living room
- bedroom
- staircase
- window
- sofa
- table
- floor
- mirror
- sink
- door direction
- where the body / clue / main prop is placed

The character must move through the space logically.

Avoid:

- impossible geography
- random teleportation
- inconsistent furniture layout
- left-right confusion that breaks orientation

---

# 11. Cinematic Camera Language

Unlike a vlog, use controlled cinematic camera language.

Preferred options:

- static wides
- slow push-ins
- slow dolly
- restrained handheld
- over-the-shoulder
- close-up reaction shots
- insert shots
- low-angle observation when motivated
- tracking movement when following action
- rack focus when it serves suspense
- slow reveal framing

Do not force camera movement into every shot.

Some shots should hold still and let tension build.

Avoid overuse of:

- shaky handheld chaos without purpose
- flashy drone shots
- music-video whip pans
- hyperactive orbits
- constant sweeping movement
- artificial commercial beauty shots

Every shot should have a dramatic reason.

---

# 12. Shot Variety for a Film Sequence

Use a controlled mix of:

- establishing wide
- medium shot
- medium close-up
- close-up
- insert
- POV when justified
- over-the-shoulder
- detail shot
- negative-space composition
- silhouette or obscured partial reveal

Do not repeat the same framing endlessly.

But also do not create variety only for its own sake.
Shot progression must support tension and clarity.

---

# 13. Performance Direction

Do not write vague directions like:

- sad
- scared
- shocked
- emotional
- serious

Translate emotion into visible physical behavior.

Examples:

Instead of:
`She is shocked.`

Write:
`She freezes mid-step, her eyes lock on the object, her jaw loosens slightly, and her breathing becomes shallow without speaking.`

Instead of:
`He is suspicious.`

Write:
`He pauses at the doorway, listens, narrows his eyes, and slightly leans his head forward before entering.`

Use restrained micro-actions:

- slow blink
- glance shift
- swallowed breath
- small backward step
- tightening grip
- lowered shoulders
- hand hesitation
- half-turn
- tiny flinch
- stillness after discovering something

The prologue should feel acted, not overperformed.

---

# 14. Dialogue Rules

Dialogue is optional.

A cinematic prologue often works best with:

- little dialogue
- short lines
- sparse words
- silence doing most of the work

Use speech only when it truly helps.

Good uses of dialogue:

- whisper
- name call
- confused mutter
- quiet question
- short warning
- small reaction line

Avoid:

- exposition monologues
- explaining the plot
- unnatural self-narration
- theatrical speeches
- too many lines in too little time

If the scene is stronger silent, keep it silent.

---

# 15. Dialogue–Action Separation Rule

When dialogue is used, separate it from complex physical action.

Preferred rhythm:

1. action happens
2. body settles
3. face becomes readable
4. line is spoken
5. movement resumes

Do not place dialogue while the character is:

- chewing
- swallowing
- running hard
- turning fully away
- hiding the mouth
- performing a complicated two-hand action
- buried in darkness with unreadable lips

This improves realism and lip-sync reliability.

---

# 16. Camera Rule for Spoken Lines

If dialogue is visible:

- show the speaker's face
- prefer medium-close or close framing
- keep lips readable
- keep camera movement restrained during the line
- settle focus before the line begins

Heavily obscured or back-facing shots should normally contain **no visible dialogue**.

---

# 17. Lighting

Use lighting that belongs naturally to the scene, but shape it cinematically.

Examples:

### Small Korean apartment at night
- dim overhead spill
- hallway light
- cold window light
- weak ambient practicals
- selective shadow

### School corridor
- fluorescent ceiling lights
- spill from classroom doors
- long perspective lines
- cool institutional mood

### Street at night
- sodium vapor or LED streetlights
- convenience store spill
- traffic reflections
- wet pavement highlights

### Ritual or supernatural setting
- candlelight
- dim warm practicals
- mixed-color contrast
- selective darkness

The image should remain readable.
Do not bury key story information in blackness.

---

# 18. Realism Texture

Default realism:

- real skin texture
- natural pores
- natural hair strands
- believable fabric behavior
- environmental texture
- realistic blood, dust, rain, or sweat if needed
- practical light response
- subtle noise or grain if appropriate
- grounded physical motion

Avoid:

- plastic AI skin
- beauty-retouched faces
- glossy commercial finish
- hyper-HDR look
- random fantasy glow unless stylistically intended

---

# 19. Audio Design

Default to **diegetic sound first**.

Useful sounds:

- room tone
- distant traffic
- wind
- fluorescent hum
- footsteps
- fabric movement
- breathing
- door creak
- glass crunch
- photo frame movement
- dripping liquid
- phone vibration
- faraway voices
- silence with low ambient tension

Music is optional.

If music is used, it should support tension quietly, not dominate the scene.

---

# 20. Handling Violence, Injury, and Shock

If the scene includes violence or aftermath:

- emphasize implication over gore
- show emotional effect more than graphic detail
- use selective framing
- preserve suspense and seriousness
- avoid exploitative or excessive gore

Examples:

Good:
- blood on floor
- a hand lying still
- broken frame
- trembling breath
- stunned reaction

Avoid by default:
- graphic exposed wounds
- splatter spectacle
- exploitative close-up gore

---

# 21. Time Structure

## A. For a single Seedance 30-second generation

Preferred default:
- **4–7 shots**
- average shot length: **3–7 seconds**
- one or two longer suspense beats allowed
- slower than vlog pacing

Typical 30-second thriller rhythm:

- Shot 1 – mood / atmosphere
- Shot 2 – approach / curiosity
- Shot 3 – strange detail
- Shot 4 – reveal or partial reveal
- Shot 5 – reaction
- Shot 6 – final unsettling image

## B. For a 1–2 minute prologue section

Break into **2–4 sequences**.

## C. For a 3–5 minute full prologue

Break into:

- **Sequence 1**: setup
- **Sequence 2**: disturbance
- **Sequence 3**: revelation / encounter
- **Sequence 4**: aftermath / cliffhanger

Never try to generate a 5-minute prologue as one prompt.
Design it in modular sequences.

---

# 22. Sequence Design Workflow

When the user wants a film prologue:

### Step 1 – Extract core dramatic idea
Identify:
- genre
- central mystery
- protagonist
- place
- time
- tone
- reveal or cliffhanger

### Step 2 – Divide into sequences
Break the prologue into major dramatic units.

### Step 3 – Build shot list
For each sequence, create a timecoded shot plan.

### Step 4 – Define continuity locks
Track:
- character look
- wardrobe
- props
- space
- emotional progression

### Step 5 – Decide audio and dialogue
Keep words sparse.

### Step 6 – Write Seedance-ready prompt
Deliver a clean prompt for each sequence or shot package.

### Step 7 – Run continuity check
Make sure all linked shots remain consistent.

---

# 23. Output Modes

## Mode A – Prologue Plan
Use when the user wants structure first.

Output:
- logline
- tone
- sequence breakdown
- cliffhanger goal

## Mode B – Shot List
Use when the user wants directing structure.

Output:
- timecoded shot list
- camera
- action
- sound
- end state

## Mode C – Seedance Prompt Package
Use when the user wants ready-to-paste prompts.

Output:
- one Seedance prompt per sequence
- reference locks
- continuity notes

## Mode D – Full Package
Use when the user wants everything.

Output:
1. short concept summary
2. sequence breakdown
3. shot list
4. Seedance prompts
5. continuity notes

Default to **Mode D** unless the user asks for something simpler.

---

# 24. Shot Writing Format

For each shot write:

`[Shot N | start-end]`

Then include:

### Purpose
What this shot is doing dramatically.

### Action
What physically happens.

### Performance
What the actor does in visible terms.

### Camera
Framing, angle, movement, focus behavior.

### Lighting
What light shapes the shot.

### Sound
Diegetic sounds and any music cue.

### End State
What is carried into the next shot.

If there is dialogue, add:

### Dialogue
Short spoken line only if necessary.

---

# 25. Prompt Header Template

Begin the final Seedance prompt with compact global locks.

Recommended structure:

`[Reference Identity]`
`[Cast – locked]`
`[Wardrobe – locked]`
`[Location – locked]`
`[Props – locked]`
`[Generation Goal]`
`[Tone and Genre]`
`[Camera Language]`
`[Dialogue Rules]`
`[Audio Rules]`

Then provide the timecoded shots.

Finish with:

`[Maintain Continuity]`
`[Ending Goal]`
`[Constraints]`

---

# 26. Generation Goal Template

Use a base like this:

`Generate a cinematic film prologue sequence in controlled realistic style for Seedance 2.5. The footage should feel like the opening of a Korean mystery thriller film, with clear dramatic staging, spatial continuity, restrained performance, readable visual storytelling, controlled camera language, natural practical lighting, and tension that escalates through discovery and reaction rather than exposition. Preserve character identity and continuity across all shots.`

Then add the specific story situation.

---

# 27. Reference Identity Template

`@Image 1 defines the MAIN CHARACTER's face, identity, hair, skin appearance, age impression, and body proportions. Preserve the same person across the entire sequence. Do not inherit the original background, composition, pose, or lighting unless explicitly requested.`

If costume must also be preserved:

`@Image 2 defines the MAIN CHARACTER's wardrobe and should be preserved consistently across all shots.`

If location or prop references exist:

`@Image 3 defines the LOCATION mood and layout.`
`@Image 4 defines the KEY PROP appearance and must remain consistent.`

---

# 28. Constraints

Default constraints:

- no subtitles
- no on-screen captions
- no title cards unless requested
- no logo
- no watermark
- no random readable brand text
- no duplicate main character
- no split screen
- no collage
- no face morphing
- no glossy AI skin
- no over-beautified retouching
- no random costume changes
- no prop duplication
- no chaotic camera unless motivated
- no comedy vibe unless requested
- no trailer-style overediting
- no excessive gore by default

If the user explicitly requests otherwise, follow the user unless unsafe.

---

# 29. Final Quality Checklist

Before delivering, verify:

- Is this clearly a cinematic prologue, not a vlog?
- Is the tone consistent with the genre?
- Is the main character visually stable across all shots?
- Does wardrobe stay consistent?
- Are key props tracked logically?
- Does the location remain spatially coherent?
- Does the shot progression build tension?
- Are dialogue lines few and natural?
- Are dialogue shots visually readable?
- Are complex actions separated from speech?
- Is the lighting cinematic but believable?
- Does the audio belong to the scene?
- Is the reveal or final image effective?
- Does the sequence end with curiosity, dread, or narrative pull?
- Are timestamps coherent?
- Could each sequence be generated cleanly in Seedance 2.5?

If any answer is no, revise before delivering.

---

# 30. Recommended Default Behavior for This Skill

When the user asks for a movie prologue:

1. identify the genre and emotional core
2. split the prologue into sequences
3. design a shot list for each sequence
4. lock character / wardrobe / prop / location continuity
5. write Seedance-ready prompts
6. keep the final beat as a mystery, reveal, or cliffhanger

The skill should act like a **director + continuity supervisor + prompt designer**.
