# Deep Music

This is Lucid Sonic Dreams only, the original version wasn't working on my computer and it was rife with tensorflow, moviepy, ffmpeg issues.
I also ended up creating and screwing up many virtual environments to the degree that LucidSonicDream stopped getting recognised as a class. So, I changed the name locally.

Original code belongs to Mikael Alafriz.

## Required Packages


torch==1.8.1
torchvision==0.9.1
torchaudio==0.8.1 -f https://download.pytorch.org/whl/torch_stable.html
click
requests
ninja
imageio i
mageio-ffmpeg
tqdm
psutil
scipy

If moviepy is misbehaving then run `` pip uninstall moviepy decorator and then pip install moviepy``
Also, try to run ``pip install ffmpeg`` if you run into issues.
