### @hideIteration true
# TechkidsCAMP

## ダンジョンを探検！ @unplugged

プログラムを使ってエージェントに命令して、ダンジョンをクリアしよう！
まずはエージェントを動かす方法を学んでみよう！

## エージェントを動かしてみよう！

``||agent.エージェントを前に１ブロック移動させる||``ブロックは、エージェントを動かすことができるよ！
ここではプログラムができているから、右下の![](https://raw.githubusercontent.com/maple-1031/TechkidsCampTutorial/master/images/playbutton.png)を押してプログラムを動かしてみよう！

プログラムを動かすにはどのようにすればよかったかな？

```template
player.onChat("start", function () {
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 10; index++) {
        agent.move(FORWARD, 1)
    }
    for (let index = 0; index < 4; index++) {
        agent.move(UP, 1)
        agent.move(FORWARD, 1)
    }
    for (let index = 0; index < 3; index++) {
        agent.move(FORWARD, 1)
    }
    agent.destroy(DOWN)
    agent.move(DOWN, 1)
    agent.destroy(RIGHT)
    agent.destroy(LEFT)
    for (let index = 0; index < 2; index++) {
        agent.destroy(FORWARD)
        agent.move(FORWARD, 1)
        agent.destroy(RIGHT)
        agent.destroy(LEFT)
    }
})
```