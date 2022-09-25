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

## Use a virtual environment

In my various experiments, I found out that conda based virtual environment worked better than the pip one. You might have a different experience but it's safe to create a virtual env before trying out any experiments.

``
conda create --name env_1 python=3.9 ``
<br>
``
conda activate env_1
``

And after the work is done

`` conda deactivate``
