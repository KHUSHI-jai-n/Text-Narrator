# Text-Narrator

A serverless solution that automates the conversion of text files into speech using AWS S3, Lambda, and Polly. This project demonstrates how to use AWS services to create a seamless workflow for converting text into audio.

Architecture:


![diagram-export-9-12-2024-9_15_18-AM](https://github.com/user-attachments/assets/41787036-cefd-4fc1-a5a8-b5baa20dcf19)

Features:

1. Serverless Architecture- Powered by AWS Lambda and Polly, with S3 as storage.
2. Automated Workflow- Upload a .txt file to the source S3 bucket to trigger the process.
3. Text-to-Speech Conversion- Amazon Polly converts the text into an MP3 audio file.
4. Storage- The generated MP3 file is stored in a destination S3 bucket.
