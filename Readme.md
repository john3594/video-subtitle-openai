# introdution
In this tutorial, you will build a Python application capable of extracting audio from an input video, transcribing the extracted audio, generating a subtitle file based on the transcription, and then adding the subtitle to a copy of the input video.

To build this application, you will use FFmpeg to extract audio from an input video. You will use OpenAI’s Whisper to generate a transcript for the extracted audio and then use this transcript to generate a subtitle file. Additionally, you will use FFmpeg to add the generated subtitle file to a copy of the input video.

FFmpeg is a powerful and open-source software suite for handling multimedia data, including audio and video processing tasks. It provides a command-line tool that allows users to convert, edit, and manipulate multimedia files with a wide range of formats and codecs.

OpenAI’s Whisper is an automatic speech recognition (ASR) system designed to convert spoken language into written text. Trained on a vast amount of multilingual and multitasking supervised data, it excels at transcribing diverse audio content with high accuracy.

By the end of this tutorial, you will have an application capable of adding subtitles to a video:

# Prerequisites
In order to follow this tutorial the reader will need the following tools:

Python version 3.9+ and corresponding venv installed

FFmpeg installed.

A basic understanding of Python. You can follow this tutorial series to learn how to code in Python.