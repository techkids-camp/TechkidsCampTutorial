### @hideIteration true
# TechkidsCAMP

## エージェントを使って、ブロックを設置しよう！

エージェントを使ってブロックをこわすには、
``||agent.エージェントに前を破壊させる||``ブロックを使うよ！
方向を選んで、エージェントがどの方向のブロックを破壊するか決めよう！

右下の![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)を押して、「run」とチャット欄に入力してプログラムを動かしてみよう！

```template
player.onChat("run", function () {
    agent.destroy(LEFT)
    agent.destroy(FORWARD)
    agent.destroy(RIGHT)
})

```