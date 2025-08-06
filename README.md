Wow & How is an offline, on-device iOS/iPadOS application designed to foster a healthy balance between play and learning. Powered by the Gemma 3n 2B model, the app intelligently interrupts extended screen time with engaging, personalized educational micro-experiences. In an age where children increasingly struggle with sustained attention, How & Wow aims to not only make screen time more enriching but also to rebuild focus, transforming passive consumption into active, curiosity-driven learning.

### Repository Structure ###

1. **Explore_Options** - Consists of notebooks, where we explore the basic usage, prompt engineering infrastructure and training data generation.
2. **Fine tune and Convert** - Consists of raw data folder we used to fine tune our model. The notebook that fine tunes it and conversion step that quantizes into a smaller size model.

### Notebook Description ### 

**Basic_Prompt_Engg** - This notebook uses the base Gemma 3n model and then applies prompt engineering depending on the input age group to provide response. In the end it generates a fun fact and MCQ based question, in the language agreeable to that age group and based on the subject of their choice.
**Generate_training_json** - Converts the raw docs file into json format more suited for LLM training.
**data_cleaning** - 
**fine_tune** - Exploratory fine tuning of the model.
**testing_gemma_3n** - 

**fine_tune_and_gguf_2b** -
**testing-gguf** - 
