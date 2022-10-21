### @hideIteration true
# TechkidsCAMP

## エージェントを動かしてみよう！

エージェントをダイヤモンドブロックの場所まで移動させよう！

スタートのとなりのボタンを押せばリセットできるよ！

```ghost
player.onChat("start", function () {
    agent.move(FORWARD, 1)
})
```

```template
player.onChat("start", function () {})
```