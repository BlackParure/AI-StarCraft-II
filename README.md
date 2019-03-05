# AI-StarCraft-II
![](https://github.com/BlackParure/AI-StarCraft-II/blob/master/img/header.png)

Final project of CS181 in ShanghaiTech. Focus on experiments with different opponent setting policy with basis of DQN method on StarCraft 2.

You can find a overview of this project in our powerpoint.(https://github.com/BlackParure/AI-StarCraft-II/blob/master/Project%20Presentation_new.pptx)

**Teammate:** Keyi-Yuan, Qin-QI, Ruiqi-Liu, Yintao-Xu

For the reason that we do slight modification to the pysc2, i include pysc2 lib in this repository([pysc2](https://github.com/deepmind/pysc2)) under Apache License 2.0. 

### **Quick Start**

1. Copy `map/SimpleContest.SC2Map` to your map directory. (e.g: on my PC, it is: `E:\billizard\StarCraft II\Maps\Melee`, it depends on where you install the game)
2. IMPORTANT: Modify the log file path in `lib\pysc2_info_saver.py`, the recorder class! 

### Reference documentation

General idea of pysc2: [[Portal](https://github.com/deepmind/pysc2)]

Environment in pysc2: [[Portal](https://github.com/deepmind/pysc2/blob/master/docs/environment.md)]

