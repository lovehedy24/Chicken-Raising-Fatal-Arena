# Chicken-Raising-Fatal-Arena
Like a traditional Tamagotchi game, which is based on NuMaker TRIO.

## Product  Introduce
就像大家以前熟悉的電子雞，透過走路與按鈕等來餵食，可以讓寵物雞長大。
我的作品希望做出一種懷舊遊戲的感覺，會透過NuMaker TRIO，做出基本電子雞的功能，並在另外加上一些自己的創意。
遊戲主要是透過維護電子雞環境，讓電子雞慢慢成長。
如果環境髒亂，電子雞就會生病、停止成長，甚至會死掉。遊戲進行一段時間後，環境會變髒亂，此時要透過甩動版子的加速度整理環境，並會透過LED燈顯示環境等級。
將ADC光源遮住會盡到黑夜模式，此模式下不能與電子雞互動。在白天模式下可以運用傾斜板子跟電子雞互動。
當電子雞成長到最高階時，可進入戰鬥模式，獲得額外獎勵。

## Function Introduce
*	LCD – 畫出整張電子雞的圖案，並會有蛋、小雞、鬥雞等階段性成長，並會有開心、生病、睡眠、死亡等表情。
*	LED – 紅燈顯示環境髒亂、綠燈表示環境良好、藍燈表示黑夜狀態。
*	ADC – 遮住光源五秒會進入黑夜模式，timer運算過一定時間會回復到白天。升高到一定溫度，電子雞會死亡。
*	Accelerometer – 甩動板子到一定的加速度會清理環境。
*	Gyroscope – 傾斜板子可以與電子雞互動。 
*	Timer – 用來計時、讓電子雞成長。
* Music – 環境髒亂到變成紅燈時、從黑夜模式回復白天時會發出警訊，電子雞成長會有音效，與電子雞互動也會有音效。

# Example LCD
開始遊戲畫面
![Start](/pic/start.bmp "Start")

最高階chicken
![Big Chicken](/pic/bigChecken1.bmp "Big Chicken")
![Big Chicken sick](/pic/bigChecken_sick.bmp "Big Chicken sick")3

中階chicken
![Chicken](/pic/chicken1.bmp "Chicken")
![Chicken sick](/pic/chicken_sick.bmp "Chicken sick")
![Chicken sleep](/pic/chicken_sleep.bmp "Chicken sleep")

低階chicken(egg)
![Egg](/pic/egg2.bmp "Egg")
![Egg sick](/pic/egg_sick2.bmp "Egg sick")
![Egg sleep](/pic/egg_sleep2.bmp "Egg sleep")
