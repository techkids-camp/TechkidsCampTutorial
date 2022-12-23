### @hideIteration true
# TechkidsCAMP

## エージェントのまわりにブロックがあるか確認しよう！ @unplugged
まえに「エージェントのまわりのブロックの種類」によってエージェントの動きを変えたね！
ここでは「エージェントのまわりにブロックがあるか」によってエージェントの動きを変えるよ！

## エージェントの前にブロックが無かったらブロックを置こう！

``||agent.エージェントにブロックがあるか、前を確認させる||``ブロックでエージェントのまわりにブロックがあるか確認することができるよ！
ここではエージェントの前にブロックがないときに鉄ブロックを置くから、``|||logic.ではない|``ブロックを使っているよ！

```template
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        if (!(agent.detect(AgentDetection.Block, FORWARD))) {
            agent.place(FORWARD)
        }
        agent.turn(RIGHT_TURN)
    }
})
