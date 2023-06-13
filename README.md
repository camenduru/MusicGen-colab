🐣 Please follow me for new updates https://twitter.com/camenduru <br />
🔥 Please join our discord server https://discord.gg/k5BwmmvJJU

## 🦒 Colab

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/MusicGen-colab/blob/main/MusicGen_colab.ipynb) | MusicGen_colab (vanilla)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/MusicGen-colab/blob/main/MusicGen_long_colab.ipynb) | MusicGen_long_colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/MusicGen-colab/blob/main/MusicGen_rkfg_colab.ipynb) | MusicGen_rkfg_colab <br /> (Thanks to @rkfg ❤ https://github.com/rkfg/audiocraft/tree/long)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/MusicGen-colab/blob/main/MusicGen_Oncorporation_colab.ipynb) | MusicGen_Oncorporation_colab <br /> (Thanks to @Oncorporation ❤ https://github.com/Oncorporation/audiocraft)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/MusicGen-colab/blob/main/MusicGen_longgen_colab.ipynb) | MusicGen_longgen_colab <br /> (Thanks to @adefossez (author) ❤ https://github.com/facebookresearch/audiocraft)

## Tutorial
https://www.youtube.com/watch?v=EGfxuTy9Eeo

```
Some prompting info from @Duemellon

But, here's a generality:

120bpm - beats per minute. Typical dance songs are 120. Most ballads are 90-100. A real slow song is 70-85. 140+ is the kinda stuff for raves, techno, & dub

320kbps 48khz - these ensure quality of the recordings, reducing hiss & usually expanding the sound range. These numbers are just rather high for an MP3 recording but not near the values of a raw audio recording. Don't apply this to sound that is supposed to be LOFI (like Lofi hip hop) because it undoes their intent : ) 22kbps quality should start sounding like you're listening to a song through a telephone or through a megaphone

4/4, 3/4, 5/4, 2/4, etc -- This would have to get into a bit more about music theory that would be applicable here. Just know the majority of American pop songs (the huge VAST majority) is 4/4. Slow jams & waltz are 3/4 (ballads & such). 5/4 & others are more for non-US audiences that have a Spanish influence. 13/8, 11/8, 10/7, etc. "weird" numbers would be for jazz

Have fun with that stuff!

All together it looks like:

* 4/4 100bpm 320kbps 48khz motown groove
* 3/4 105bpm 320kbps 48khz piano only baroque
* 110bpm 64kbps 16khz lofi hiphop summer smooth

More info about Top-k, Top-p, Temperature and Classifier Free Guidance from ChatGPT

Top-k: Top-k is a parameter used in text generation models, including music generation models. It determines the number of most likely next tokens to consider at each step of the generation process. The model ranks all possible tokens based on their predicted probabilities, and then selects the top-k tokens from the ranked list. The model then samples from this reduced set of tokens to determine the next token in the generated sequence. A smaller value of k results in a more focused and deterministic output, while a larger value of k allows for more diversity in the generated music.

Top-p (or nucleus sampling): Top-p, also known as nucleus sampling or probabilistic sampling, is another method used for token selection during text generation. Instead of specifying a fixed number like top-k, top-p considers the cumulative probability distribution of the ranked tokens. It selects the smallest possible set of tokens whose cumulative probability exceeds a certain threshold (usually denoted as p). The model then samples from this set to choose the next token. This approach ensures that the generated output maintains a balance between diversity and coherence, as it allows for a varying number of tokens to be considered based on their probabilities.

Temperature: Temperature is a parameter that controls the randomness of the generated output. It is applied during the sampling process, where a higher temperature value results in more random and diverse outputs, while a lower temperature value leads to more deterministic and focused outputs. In the context of music generation, a higher temperature can introduce more variability and creativity into the generated music, but it may also lead to less coherent or structured compositions. On the other hand, a lower temperature can produce more repetitive and predictable music.

Classifier-Free Guidance: Classifier-Free Guidance refers to a technique used in some music generation models where a separate classifier network is trained to provide guidance or control over the generated music. This classifier is trained on labeled data to recognize specific musical characteristics or styles. During the generation process, the output of the generator model is evaluated by the classifier, and the generator is encouraged to produce music that aligns with the desired characteristics or style. This approach allows for more fine-grained control over the generated music, enabling users to specify certain attributes they want the model to capture.

These parameters, such as top-k, top-p, temperature, and classifier-free guidance, provide different ways to influence the output of a music generation model and strike a balance between creativity, diversity, coherence, and control. The specific values for these parameters can be tuned based on the desired outcome and user preferences.
```

## Main Repo
https://github.com/facebookresearch/audiocraft

## Page
https://ai.honu.io/papers/musicgen/

## Paper
https://arxiv.org/abs/2306.05284

## License
[LICENSE](LICENSE) <br />
[LICENSE_weights](LICENSE_weights)

