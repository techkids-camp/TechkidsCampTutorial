### @hideIteration true
### @explicitHints true
# TechKidsCampEvent

## スイカ割りをしよう！
ブロックをつかって、エージェントをスイカまでいどうさせよう！！

もし、さいしょからやりなおしたいとき・クリアしたときは、ロボットにはなしかけてね。

```ghost
player.onChat("run", function () {
    agent.move(FORWARD, 1)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
        
    if (!(agent.detect(AgentDetection.Block, DOWN))) {
    	
    }else{
        
    }
})
```

```template
function ここのなかにブロックをいれよう () {
	
}
function ここは触らないでね () {
    player.execute(
    "function agent/agentcheck"
    )
}
player.onChat("run", function () {
    ここのなかにブロックをいれよう()
    ここは触らないでね()
})

```