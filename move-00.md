# TechkidsCAMP

## エージェントを動かしてみよう！

![](https://raw.githubusercontent.com/maple-1031/TechkidsCampTutorial/master/images/move-tutorial.gif)
エージェントをダイヤモンドブロックの場所まで移動させよう！

![](https://raw.githubusercontent.com/maple-1031/TechkidsCampTutorial/master/images/move-reset.gif)
スタートのとなりのボタンを押せばリセットできるよ！

```ghost
player.onChat("start", function () {
    agent.move(FORWARD, 1)
})
```

```template
player.onChat("start", function () {})
```