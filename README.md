# Link2Apk
A simple app generator for links using Github Actions

# Instructions:
1. Edit the values in `info.text` file.
2. Wait for a minute or two.
3. Navigate to `Actions` tab. 
4. Then click on the last workflow run. The apk will be on the `Artifacts` section.
5. Enjoy!

# How it works:

Here I'm parsing the values (`NAME` & `URL`) from `info.text` which is then passed into `/app/build.gradle` by Github Actions. The debug apk file is built by Github Actions and it's stored in zip format. In this way, we do not need to clone the code or need a pc to build the apk files.

# Why:
I've seen people using online services for building an app from url, so I tried to do something similar using Github.

# Special Thanks:
[Mamunur Rashid](https://github.com/seekermind) for helping me writing that shell script.
