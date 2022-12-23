### @hideIteration true
# TechkidsCAMP

## エージェントのまわりのブロックによって命令を変えよう！ @unplugged
エージェントはまわりのブロックの種類にによって動き方を変えることができるよ！
プログラムを見てみよう！

## エージェントのまわりのブロックによって命令を変えよう！

エージェントの前のブロックがダイヤモンドブロックの時にダイヤモンドブロックをこわそう！

``||logic.もし～なら||``ブロックを使えば、エージェントのまわりのブロックに応じて、ブロックをこわすかこわさないかを決めることができるんだね！


```template
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        if (agent.inspect(AgentInspection.Block, FORWARD) == DIAMOND_BLOCK) {
            agent.destroy(FORWARD)
        }
        agent.turn(RIGHT_TURN)
    }
})


```