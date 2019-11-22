# skill-demo-voiceprofiles
A demo to show how to identify a speaker with Voice Profiles. Once a speaker is identified the incoming request will include a personId in the request context. With the personId you can then use SSML to extract the name (see the sample's lambda)
Prerequisites:
- Train a voice in your Alexa app
- As a developer enable the Personalization permission in your skill
- As a user enable Personalization in the skill settings
- Talk to the skill using a trained voice (very short utterances are not very good at recognizing the speaker)
