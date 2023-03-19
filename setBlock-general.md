# TechkidsCAMP

## エージェントを使って、ブロックを設置しよう！

ブロックを使ってエージェントにブロックを設置してもらおう！

```ghost
player.onChat("run", function () {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.turn(LEFT_TURN)
})
```

```template
player.onChat("run", function () {})
```
