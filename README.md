# superwhisper-dictation-prompts
This is a repository for my [Superwhisper](https://superwhisper.com) dictation prompts. XML headers are not included due to them not really being needed for the models to process. My goal is as little information in context as needed.
All prompts can be found [here](/Prompts). These have been customized heavily for Superwhisper. They also use the suggested language found [here](https://superwhisper.com/docs/modes/custom).


- **Claude 4 Sonnet - Accuracy - Speech to Emoji - Internet Slang**
    - This allows for dictation of Emojis.
    - Dictation of common internet slang: eg. "ftw", "lol", "lmao", "rofl". Say the letters and they will be output in lowercase.
    - It has a high focus on accuracy.
    - It works best with Claude 4 Sonnet and has been validated in Superwhisper.


-  **Summarize**
      - The goal of this is summarization of text while maintaining personal perspective as well as the person's voice and tone.
      - When artificial intelligence normally summarizes something, it  uses phrases like "the author states....", there's also usually very formal English that doesn't sound like a real person. It sounds like AI.
      - The goal of this was to shorten emails, text messages, etc. while also maintaining a natural tone that a human being would use to the best of my ability.
      - I find that when I dictate, I tend to lack brevity, and this is helpful for maintaining that.
        - **Usage**
            - This is meant for use in Superwhisper.
            - One must make sure clipboard context is turned on or this will not work.
            - The correct usage is to copy the text to your clipboard, switch to the summarize mode you've set up using these instructions, and then ask it to summarize, and that's it. It'll paste in summarized text of whatever you copied to your clipboard.
            - If you copied some nonsense or something that obviously can't be summarized, it will output simply: "No text to summarize."
    - I have only tested this with English. It probably will only work in English because all the examples are in English. It involves a lot of English grammar as well, so I'm not sure that this will work for other languages. It mayy however be a good starting point to use for other languages. It would have to be adapted to instruct the model with the specific grammatical needs of that language.
    - It may also work in other tools as well. I have not tested it. If another tool has clipboard context, it should work. I also don't see why it wouldn't work in a regular AI tool if it's modified without all the clipboard stuff and just given as instructions for a specific prompt.
    
