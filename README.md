# Jenny-AI-Experiment: Comparing Leonardo and ChatGPT

### What I did, the main focus

I compared two AI-models, Leonardo and ChatGPT, in the framework of generating an illustrative image for a nursery rhyme.

### Why I did, the aim

I needed an image where a girl with one bare foot is depicted. That picture was supposed to be the accompanying background during my reading on the video.

### Process

I made up the same prompts for both of them. I started off with the simpliest prompt which would be enough to grasp the main idea. The initial prompt sounded like "little girl with one bare foot, old English style, cosy vintage". In my following iterations I was adding some details every time in order to help the models pin the context and stick to the verisimilitude as I didn't want the image to be too childish or magical. 
Having simultaneous chats with two models I observed several *striking differences*:
- Leonardo
    - ignored the part of the prompt from the very beginning;
    - began to add its own lengthy description;
    - failed to retain the visual style and context, every iteration was like a new prompt with a new character;
    - failed to process numerals correctly (extra limbs, extra boots, incorrectly pictured "bare foot" partly with a sock on it);
    - constantly omitted the "bare foot" constraint, the negations *no,without*;
    - showed poor spatial reasoning (nail visible on the wrong side of the foot).
  
On the whole it took me more than 10 iterations to get more or less acceptable output. 

- ChatGPT
    - grasped the core conception and emotional tone immediatly;
    - retained the context, the heroine and the style were not subjected to drastic changes (in one chat);
    - generated slower but the outputs were more accurate;
    - didn't use memory from the previous chats but relied on the pattern of recent visible requests (one thread-several chats);
    - required fewer iterations.
 
At the end of my experiment I decided to test what the models could generate if I use the whole nursery rhyme as a prompt.

ChatGPT created a visually and contextually consistent four-scene image based on all the lines of the  nursery rhyme.
Leonardo remained miraculously unaware creating a young adult girl dressed in a national costume. No boot, no miller, no Jenny.


### Comparison

| Aspect | Leonardo | ChatGPT |
|:------ | :-------: | :-------: |
| Visual consistency | Poor | High |
| Context understanding | Very poor | Very high|
| Prompt efficiency | Very poor | Very high|
| Output history | Always visible | Always visible |
| Constraint Adherence | Very poor | High |

### *Interesting fact*

One of my prompts was "crying little girl with one bare foot, the other foot is in a shoe, old English style, cosy vintage cottage style, whimsical nursery rhyme". The first time I entered this prompt, ChatGPT refused to generate an image because it triggered the guardrail. I thought that the reason lay in the fact that the words *crying*, *whimsical* and *little girl* overlapped in one sentence, thus creating ambiguity. Then I decided to retest this prompt. Firstly I changed *crying* into less strong and provocative *upset*. Then after several iterations the same phrase no longer triggered the guardrail, and the image looked almost exactly like the previous one. I can conclude that the guardrail is conditional and does not necessarily depend on the choice of words. The cornerstone is the general context and the number of iterations.


### What I learned

* Different AI models require different strategies.
* Prompt generating is about precision.
* Guardrails are not static, there is always an option to expand a context.
* Leonardo is a visual model. It makes drastic changes omitting the previous uotputs, struggles with details. It can be hardly used for tasks requiring precision and narrative consistency.
* ChatGPT is faster to "communicate" with. It remembers, addapts to the context. It is not "afraid" of long, detailed prompts.
* 

### Files
Screenshots are in the repository.

> The result matters.
