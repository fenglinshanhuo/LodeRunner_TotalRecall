### NOTES
1. 游戏的入口函数应该是在`lodeRunner.main.js`里面，可以从这里开始调试
2. 地图资源存放在`lodeRunner.v.classic.js`里, 默认从第一关开始，关卡设置的函数大概在`lodeRunner.main.js:startGame`函数里，对于`levelMap`
3. 地图尺寸存放在`lodeRunner.def.js`里，`NO_OF_TILES_X` 决定了地图的宽，单位应该是tile，`BASE_TILE_X`应该是tile的宽度，单位估计是像素
4. 根据`lodeRunner.def.js`里的信息，如下，应该有11个tile类型。
```
var EMPTY_T  = 0x00; 
var BLOCK_T  = 0x01; 
var SOLID_T  = 0x02; 
var LADDR_T  = 0x03; 
var BAR_T    = 0x04; 
var TRAP_T   = 0x05; 
var HLADR_T  = 0x06; 
var GOLD_T   = 0x07;
var GUARD_T  = 0x08;
var RUNNER_T = 0x09;

var REBORN_T = 0x10; //template: for reborn
```
5. 速度应该是保存在`lodeRunner.preload.js:spriteSpeed`变量当中，水平移动速度应该是`xMoveBase`, 单位估计是`pixels/frame`，然后里面还有一个变量叫做`runnerSpeed`，这个定义的应该是动画速度，单位估计是`动画帧/游戏刷新帧`。