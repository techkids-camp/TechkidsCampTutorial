### @hideIteration true
# TechkidsCAMP

## ダンジョンを探検！ @unplugged

プログラムを使ってエージェントに命令して、ダンジョンをクリアしよう！
まずはエージェントを動かす方法を学んでみよう！

## エージェントを動かしてみよう！

``||agent.エージェントを前に１ブロック移動させる||``ブロックは、エージェントを動かすことができるよ！
右下の![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)を押してプログラムを動かしてみよう！

プログラムを動かすにはどのようにすればよかったかな？

```template
player.onChat("start", function () {
    agent.move(FORWARD, 1)
})
```