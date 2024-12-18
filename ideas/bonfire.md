# Bonfire

Bonfire is a Discord bot that plays suitable background music for voice channel conversations by analyzing the emotional context of interactions.

## Why

Existing music bots require manual input to play songs and fail to adapt to the flow of conversation, resulting in a static and disconnected experience. There are no bots that analyze real-time voice chats to understand the mood and automatically adjust the music. While current bots play pre-queued tracks without context awareness, Bonfire dynamically selects music based on the conversation's mood, enhancing the ambiance to a more 'cinematic' experience.

## How

- Obtain individual user camera feed and conversation through Discord voice channel
- Use AI models for analyzing both facial expressions through user cam and conversational sentiments through voice input.
- Implement algorithm to integrate output from both the models and use Spotify's emotionally scored music data, to choose the next song in the queue.

## Challenges Faced

- Lack of image datasets that are labeled with subtle variations in facial expressions.
- Analyzing expressions from a single image is challenging unless the expression is particularly strong.
- Sarcasm in conversations can confuse the models and lead to inaccurate interpretations.

## Good to Have Features

- Models that better understand sarcasm.
- Could use cool visualizations.

contributed by [Ishaan Sawant](https://github.com/KAMEHAMEHA-05)