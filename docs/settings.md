# Settings, explained

Press **I** in the game to open the settings. (On NeoForge they also open from the Mods screen, on Fabric from Mod Menu.)
Every setting is saved as soon as you change it. The value in **bold** is the default.

New to the mod? Start with [the four settings most players change](#the-four-settings-most-players-change).

## The four settings most players change

1. **Question every** — how often the teacher quizzes you. The default is every 60 seconds. If the questions get in your way, raise it to 120 or 180. If you want more practice, lower it to 15 or 30.
2. **Penalty** — what a wrong answer costs. The default is two bad effects for a while. Choose *none* to learn in peace, or *hardcore* if one mistake should kill you.
3. **Quiz** — how you answer: with buttons, on the keyboard, or with your voice.
4. **Same phrase again** — if the teacher repeats the same phrase too often while you mine or build, set it to 30 s or 1 min.

## Main page

| Setting | What it does | Values |
|---|---|---|
| **Teacher** | Switches the teacher on or off. Off: no voice, no text, no questions. The key **N** does the same. | **ON**, OFF |
| **Language** | The language the teacher speaks and asks about. The list shows the language files you installed. | the installed languages |
| **Translations** (English, Chinese and German teachers) | The language of the translation under the teacher's lines. *Game language* follows your Minecraft language; when the teacher has no translation in it, you get English. | **game language**, or one of the teacher's translation languages |
| **Teacher's look** *(from 0.6.1, Chinese)* | Which drawing of the teacher you see. | **pixel**, Linnle210 |
| **Speed** | How fast the teacher speaks. The key **K** switches it too. | **normal**, slow |
| **Volume** | How loud the teacher is. | 0–100 %, **100 %** |
| **Sound** | OFF: you do not hear the teacher, but her text still appears and the questions still come. What you ask for is still spoken: the name of what you look at (**V**), a listening question, *Play* in the Dictionary. The key **M** does the same. | **ON**, OFF |
| **Repeat every** | While you keep doing the same thing (you hold the button and keep mining), the teacher says its phrase again this often. *Never*: she says it once when you start. | **never**, 3 s … 60 s |
| **Same phrase again** *(from 0.6.1)* | How soon the teacher may say a phrase she has already said. *At once*: every time you start the action again. *10 s*: you mine cobblestone all the time, and she says it once in 10 seconds at most. A phrase you hear for the first time is never held back. If she repeats herself too much, set 30 s or 1 min. | at once, **10 s**, 30 s, 1 min, 5 min |
| **Text size** | Size of the teacher's text on the screen. | 1×–3×, **2×** |
| **Pinyin** (Chinese, Japanese) | Shows how the words are read above them. With it off, hold **Right Shift** to see the reading for a moment. | **ON**, OFF |
| **English** | Shows the translation under each line. | **ON**, OFF |
| **Quiz** | How the teacher tests you. *choice*: pick one of four answers (keys 1–4 or the mouse). *typing*: type the phrase. *speech*: say it into the microphone. *mixed*: all three by turns (from 0.6.1; before it, choice and speech). *off*: no questions. | **choice**, typing, speech, mixed, off |
| **Penalty** | What a wrong answer costs. *none*: nothing. *debuff*: two bad effects for a while. *hearts*: you lose a heart for good; ten mistakes and you die. *hardcore*: one mistake and you die. | none, **debuff**, hearts, hardcore |
| **Question every** | Time between two questions. A question with buttons waits until you stop mining, fighting or eating. | 15–300 s, **60 s** |
| **Answer time** | Seconds you have to answer. Running out of time counts as a wrong answer. | 5–30 s, **12 s** |
| **Speech strictness** | How exact a spoken answer must be. *0.5*: half of the sounds right. *1*: every sound right. The new word of the phrase (usually the last one) must always be at least half right. | 0.5–1, **0.5** |
| **Voice answers** | Sets up and starts the helper program that listens to your microphone. See [Voice answers](#voice-answers). | |
| **Exam…** | Opens the exam page. The button shows whether the exam is on. | |
| **Advanced settings…** | Opens the second page. | |
| **How it works…** | The short guide from your first world. The key **U** opens it too. | |

## Typed answers (Quiz: typing)

- Capital letters, punctuation and extra spaces never matter.
- A missing accent is forgiven (*recogi* for *recogí*), and so is a small typo in a long word. The right spelling is shown after your answer.
- A different word is not forgiven: *roja* is not *rosa*.
- **Chinese:** type characters or pinyin. Tones are optional, as marks (*wǒ*) or numbers (*wo3*). If you type them, they must be right. Type *ü* as *v* (*nv* for *nǚ*).
- **Japanese:** type kanji, kana or romaji, the way a Japanese keyboard takes it: *shi* or *si*, *tsu* or *tu*.
- Enter with an empty box does nothing. When the time runs out, an empty box counts as no answer.

## Exam page

The exam asks the phrases that came up most: up to 20 questions, one right after another. At the end you see your score and every answer you gave.

| Setting | What it does | Values |
|---|---|---|
| **Exam** | ON: an exam comes by itself after every stretch of play. OFF: no exam unless you press *Start the exam*. | **ON**, OFF |
| **Exam every** | Minutes of play between two exams. Time in menus does not count. | 5–60 min, **20 min** |
| **Buttons** | Exam questions where you pick one of four answers. | **ON**, OFF |
| **Typing** | Exam questions where you type the phrase. | **ON**, OFF |
| **Voice** | Exam questions you answer into the microphone. Needs voice answers. | ON, **OFF** |
| **Exam penalties** | OFF: the exam only keeps the score. ON: a wrong answer is punished like in a usual question. | ON, **OFF** |
| **Start the exam** | Starts the questions now, about the phrases that came up most in this world. | |

## Advanced page

| Setting | What it does | Values |
|---|---|---|
| **Font** | The font of the teacher's text: the language's own font or Minecraft's. | **language pack**, Minecraft |
| **Spoken hint** | Shows how to say the phrase during a spoken question. *new*: only for phrases you never answered right. | **new**, always, never |
| **Portrait** | Where the teacher's picture is on the screen. | **bottom right**, bottom left, top right, top left, off |
| **Portrait size** | Size of the teacher's picture. | 0.5×–4×, **1.5×** |
| **Score corner** | Where the counter of learned words and deaths is. | **top left**, top right, bottom left, bottom right, off |
| **Score size** | Size of that counter. | 0.5×–3×, **1×** |
| **Position** | The teacher's text at the bottom (above the hotbar) or at the top of the screen. | **bottom**, top |
| **Learned words** | A phrase you answered right is learned. *forever*: the teacher never says or asks it again in this world. *until death*: it comes back after you die. *back in 60 min*: it comes back after an hour. | **forever**, until death, back in 60 min |
| **Rewards** | Good effects (speed, regeneration, jump boost, haste) for a right answer. | **ON**, OFF |
| **Pause on question** | Pauses the game while a question with buttons is open (singleplayer only). Spoken questions never pause. | **ON**, OFF |
| **Angry teacher** | What the teacher does after too many wrong answers in a row. *drops all*: everything you carry falls on the ground, armour too; pick it up again. *takes all*: it is gone for good. *off*: she never gets angry. | **drops all**, takes all, off |
| **Angry after N wrong** | How many wrong answers in a row make her angry. | 1–10, **5** |
| **Question timer** | Shows "Next question in N s" under the counter. | **ON**, OFF |
| **Jingle** | The sound when a phrase becomes learned. | **xp**, fanfare, soft, off |
| **Translation in tooltips** | Adds the word in the language you learn to the item tooltips in your inventory. | **ON**, OFF |
| **Character icons** (Chinese, Japanese) | Item pictures in the teacher's text turn into the written word: after you learned it, after your first right answer, or never. | **learned**, known, off |
| **Text backdrop** | A dark band behind the teacher's text, for easier reading. | **ON**, OFF |
| **What the teacher talks about…** | Opens the list below. | |

## What the teacher talks about

Switch whole groups of phrases on or off.

| Group | Phrases | Default |
|---|---|---|
| **Movement** | Walking, running, sneaking, swimming, flying, climbing, jumping, riding. | OFF |
| **Combat** | Hitting, killing, being hurt, falling, burning. | ON |
| **Blocks** | Breaking, placing, opening and using blocks. | ON |
| **Items** | Holding, picking up, dropping, eating and drinking items. | ON |
| **World** | Day and night, weather, hot and cold places, dimensions, hunger, sleep, fishing. | ON |
| **Held item** | The name of the item you switch to in your hotbar. | ON |
| **Kills** | "I killed the …" when a creature you hit dies. | ON |
| **Damage** | "Ouch!" when you are hurt, and "I died". | ON |

## Voice answers

1. Open the settings (**I**) and press **Voice answers: set up…**, then **Yes**.
2. A helper window opens and downloads what it needs. Keep the window open.
3. When the chat says the voice answers are ready, set **Quiz** to *speech* or *mixed*. When a spoken question appears, hold **B** and say the phrase.

If the helper does not answer, press the **Voice answers** button in the settings again: it starts the helper again.
Your voice is recognised on your own computer and never leaves it.

## Keys

| Key | What it does |
|---|---|
| N | Teacher on / off |
| M | Teacher's sound off / on (text and questions stay) |
| K | Normal / slow speech |
| V | Say the name of the block or creature you are looking at |
| J | Dictionary of the phrases you have learned |
| U | The guide |
| I | Settings |
| Right Shift (hold) | Show the reading (pinyin, romaji) |
| 1–4 or mouse | Answer a question with buttons |
| B (hold) | Answer a spoken question |

Change any key in Options → Controls → Key Binds → Learn or Die: Language Teacher.
