### @hideIteration true
# TechkidsCAMP

## ここから先は、自分でプログラムを作ってみよう！
分からないことがあったらメンターさんを呼んでね！

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        if (!(agent.detect(AgentDetection.Block, FORWARD))) {
            agent.place(FORWARD)
        }
        agent.turn(RIGHT_TURN)
    }
})


```

```template
player.onChat("run", function () {})

```