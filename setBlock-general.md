### @hideIteration true

# TechkidsCAMP

## エージェントを使って、ブロックを設置しよう！

エージェントを使ってブロックを設置するには、
``||agent.エージェントに前へ置かせる||``ブロックを使うよ！
右下の![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)を押して、「run」とチャット欄に入力してプログラムを動かしてみよう！


```ghost
player.onChat("run", function () {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
})
```

```template
player.onChat("run", function () {
})

```