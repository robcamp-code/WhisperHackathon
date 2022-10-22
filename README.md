# WhisperHackathon
Speech style transfer model for the whisper hackathon

## Dataset --> BaseTone
- Modality (01 = full-AV, 02 = video-only, 03 = audio-only).

- Vocal channel (01 = speech, 02 = song).

- Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).

- Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.

- Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").

- Repetition (01 = 1st repetition, 02 = 2nd repetition).

- Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

File name example:

03-01-01-01-01-01-01 --> Audio only, speech neutral emotion, normal intensity, statement -> "The kids are talking by the door", 1st repetition, 1st actor


## Related Research
- Whisper
    - https://cdn.openai.com/papers/whisper.pdf

- Emotional Speech Dataset
EmoV-DB
https://arxiv.org/pdf/1901.04276v1.pdf
https://github.com/lowerquality/gentle
https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio
