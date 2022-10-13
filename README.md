### @hideIteration true
# TechKidsCamp

## コマンドを実行する

右下の「▶」ボタンを押してから、
「start」とチャットに入力してエージェントに命令してみよう！``||agent.moe(FORWARD, 1)||``

エージェントがスタートポータルを開いてくれるよ！


```template
player.onChat("run", function () {
    agent.move(FORWARD, 1)
})
```