# ytdlpwrapperforfunsies
yt-dlp wrapper for funsies.
chatgpt assisted.
i include the packed exe (no dependencies needed i think, file an issue here if something goes wrong (dependency related)) and the source file, the .py one.
tested on a 1920x1080 laptop screen.
opens a 560x640 window.
requires ttkbootstrap (for anyone who decides to dig in the source file).
Feel free to skid this one too :)

virustotal result (false positives i suppose):
![Screenshot](Снимок%20экрана%20%285%29.png)
https://www.virustotal.com/gui/file/34e1091248f6fb348b22f457d5fa5fbd1d03f961450b280fadd3a2f4929fc0f2/detection

notice (important): this was packed using pyinstaller which bundles it all into one executable, and unpacks in memory when launched, which triggers some antiviruses.
1. I published the source code for you all to verify its safety if needed.
2. This has no backdoors/malicious intent.
3. Credits to https://github.com/yt-dlp/yt-dlp for making yt-dlp.
Built using Python 3.10 from ms store, on windows 10.
