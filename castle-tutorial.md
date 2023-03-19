### @hideIteration true
# TechkidsCAMP

## コマンドを実行する

右下の「▶」ボタンを押してから、「t」キーを押して「run」とチャットに入力してエージェントに命令してみよう！

エージェントがスタートポータルを開いてくれるよ！

```template
player.onChat("run", function () {
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 2; index++) {
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