### @hideIteration true
# TechkidsCAMP

## くり返しってなにかな？ @unplugged

プログラミングでは、めんどうな作業をくり返すことができるよ！
「くり返し」を使えば、同じ作業を100回でも1000回でもやらせることができるよ！

## エージェントにくり返させてみよう！

エージェントに「くり返し」のプログラムをやらせるには、``||agent.くり返し 4回||``ブロックを使うよ！
ブロックの中の数字を変えて、くり返す回数を決めることができるよ！

右下の![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)を押してプログラムを動かしてみよう！

```template
player.onChat("start", function () {
    agent.setItem(IRON_BLOCK, 4, 1)
    for (let index = 0; index < 4; index++) {
        agent.place(FORWARD)
        agent.turn(RIGHT_TURN)
    }
})

```