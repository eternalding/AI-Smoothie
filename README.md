![icon](https://github.com/eternalding/AI-Smoothie/blob/main/images/icon.png?raw=true)

# AI-Smoothie
An GPT4o-mini based summarization pipeline for automatic huggingFace daily paper summarization

## Introduction
As an engineer specializing in AI algorithms, staying up-to-date requires reading a large number of research papers every day.<br> However, with new papers being published constantly, it can be challenging to find the time to carefully digest each one.<br> Wouldn't it be great if there were a tool to help us quickly summarize the key points of these papers?

"AI Smoothie" is a simple summarization tool that provides a "smoothie" of AI insights, as the name suggests. <br>It collects papers daily from Hugging Face's Daily Papers, processes them with GPT-4o-mini for summarization, extracts the most essential points, and organizes them into a structured format. These notes are then published on HackMD for readers to access.

Additionally, if you'd like to join this project, you can provide your email address to receive the latest paper summaries daily.

## Methodology
The entire workflow is automated using APIs from various platforms. It is designed to fetch new papers on a scheduled basis and send email summaries to all subscribers.

![icon](https://github.com/eternalding/AI-Smoothie/blob/main/images/pipeline.png?raw=true)

## Links
Since HackMD has MAX_LENGTH of 100,000 constraint, if the total length of summary is longer than this number, it will be divided into several episodes.

### 2024/11/20
Ep 1. https://hackmd.io/@eternalding/SyJXZKjf1x <br>
Ep 2. https://hackmd.io/@eternalding/S1lQZKjfye <br>

## Notes
1. All summarization were done by GPT-4o-mini (or any other AI models in the future). 
2. This project is 