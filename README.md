## Desktop Assistant

### Introduction
This python code is an realization of openai's api to make a desktop assistant that handles jobs based on user's text command.  
It was developed around November of 2022 in AI club of HAFS, Hankuk Academy of Foreign Studies, by Gyeongseok Shin and Yewon Seo.

### History
GPT 3.0 has just been released and chatgpt didn't exist at that time.  
And api used in this code utilizies ai's ability to predict upcoming texts based on given task.  
The initial repository was deleted because of security problems regarding api key, and now it's uploaded again after fix.

### How it works
So, we prompt_engineered it by adding role playing situation conversation before user input, as a talk between an ai assistant and human master.  
It handles task in following order.

#### Read user text input, and classify if a user asks for certain tasks for which we've made the agentic functions.
The pre_build agentic functions include informing current time, weather, or playing youtube videos, searching up internet for short informations.

#### If not, print gpt model's answer in appropriate manners.
Also, google text to speech model was used for reading chatbot's answer out loud for user.

### Remarks
For now, spring of 2026, this type of api is **no longer supported by openai, and current code is stored for historic purposes, for future reference.**

#### Required API keys are as followed for use of this code
- `OPENAI_API_KEY`
- `OPENWEATHERMAP_API`
