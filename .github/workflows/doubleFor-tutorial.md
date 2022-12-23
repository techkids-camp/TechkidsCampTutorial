### @hideIteration true
# TechkidsCAMP

## くり返しを組み合わせよう！ @unplugged
``||loops.くりかえし||``ブロックで同じ動きを繰り返させることができたね！
くり返しを組み合わせると、もっとふくざつな動きをさせることができるよ！
プログラムを確認しよう！

## くり返しを２つ組み合わせよう！

``||loops.くりかえし||``ブロックの中に``||loops.くりかえし||``ブロックを入れよう！
ここでは、ブロックをこわすプログラムを４回くり返したら、1つ上に行って同じことをもう一度くり返しているね！

```template
player.onChat("run", function () {
    for (let index = 0; index < 2; index++) {
        for (let index = 0; index < 4; index++) {
            agent.destroy(FORWARD)
            agent.turn(RIGHT_TURN)
        }
        agent.move(UP, 1)
    }
})

```