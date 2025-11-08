<p align="center">
  <img src="https://wakatime.com/badge/user/839267df-3912-44c6-97f4-9e3f0425b716.svg" alt="Total time coded since Feb 28 2023" />
</p>

<p align="center">
  <img height="25" src="https://api.visitorbadge.io/api/VisitorHit?user=gpt4omni&countColor=%234a12ba" alt="Profile Views"/>
  <img height="25" src="https://img.shields.io/github/followers/gpt4omni?color=4a12ba&style=for-the-badge&logo=github&label=Follow" alt="Followers"/>
  <img height="25" src="https://img.shields.io/github/stars/gpt4omni?color=4a12ba&style=for-the-badge&logo=github&label=Stars" alt="Stars"/>
</p>

<p align="center"> 
    <img src="https://github-readme-streak-stats-eta-three.vercel.app?user=gpt4omni&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="60%">
</p>

```python
from abc import ABCMeta, abstractmethod


class GPT4Omni(metaclass=ABCMeta):
    
    @staticmethod
    @abstractmethod
    def contact():
        discord = "virutal"
        return discord


class Attributes(GPT4Omni):

    @staticmethod
    def life() -> tuple:
        langs = ("English")
        return langs

    @staticmethod
    def coding() -> tuple:
        text_editors = ["VSCode"]
        specialities = ["AI systems", "API engineering", "automation"]
        langs = {
            "pro": "Python, C++",
            "intermediate": "Rust, Go",
            "learning": "JS"
        }
        return langs, specialities, text_editors
