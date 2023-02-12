![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white 'Python')
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252 'Colab')

# youtube-transcriber
A simple Python Notebook using Whisper to transcribe Youtube videos in plain text

**Why?**

I wanted to use Whisper to transcript some youtube videos but all the implementations I found were including timestamps like subtitles and I just wanted the plain transcript text.

So I made it myself with a Python Notebook in Google Colab (which gives me better hardware to run the model than my home computer) using the Whisper library + Pytube.

It’s really simple but I’m proud of it, lol.

With the “medium” model using the default GPU that Colab gives you, it transcribes at ~ 3X the speed of the video. So, a 10min video will transcribe in around 3min.

---

Download the Python Notebook to run it yourself or you can also use it directly in Google Colab: 

https://colab.research.google.com/drive/19Wla7NpTbr_nJOSoVJ-ezyfSX1Q6UuR-
