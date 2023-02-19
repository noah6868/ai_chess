# ai_chess

项目介绍：本项目实现了一个能够在象棋游戏中自我控制的AI系统，通过蒙特卡洛树搜索和策略价值网络，AI系统能够根据蒙特卡洛树的搜索结构从当前盘面中预测出最优化的行动。

collect.py：自我对弈收集数据

config.py：项目配置文件

game.py：棋盘逻辑控制以及盘面的数据收集

mcts.py：蒙特卡洛树的实现

pytorch.py：策略价值网络的实现

train.py：模型训练（模型已经训练好）

模型文件太大上传不了，需要现运行collect.py,再运行train.py,最后运行UIplay.py开始和AI象棋对弈



