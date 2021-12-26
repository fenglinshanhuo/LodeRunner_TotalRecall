<a target="_blank" href="http://loderunnerwebgame.com/LodeRunner/">Lode Runner - Total Recall</a>
=======================================
## (超級運動員 - 全面回憶)

This program build with Javascript + [CreateJS](http://www.createjs.com).

### * 3 GAME Mode & 1 DEMO Mode
<table>
<tr>
<td><b>(1) Challenge Mode</b></td> 
<td>Compete with other players.</td>
</tr>
<tr>
<td><b>(2) Training Mode</b></td> 
<td>Player can select any levels</td>
</tr>
<tr>
<td><b>(3) Edit Mode</b></td> 
<td>Player can create custom levels</td>
</tr>
<tr>
<td><b>(4) Demo Mode</b></td> 
<td>Demo passed levels</td>
</tr>

</table>

### * Include 5 Game Versions
<table>
<tr>
<td><b>(1) <a target="_blank" href="https://en.wikipedia.org/wiki/Lode_Runner">Classic Lode Runner</a></b></td>
<td>(150 Levels)</td>
<td>Difficulty: 3</td>
</tr>

<tr>
<td><b>(2) <a target="_blank" href="http://www.gb64.com/game.php?id=5906&d=42">Professional Lode Runner</a></b></td> 
<td>(150 Levels)</td>
<td>Difficulty: 4</td>
</tr>

<tr>
<td><b>(3) <a target="_blank" href="http://www.vizzed.com/play/revenge-of-lode-runner-appleii-online-apple-ii-6223-game">Revenge of Lode Runner</a></b></td> 
<td>(17 Levels)</td>
<td>Difficulty: 4</td>
</tr>

<tr>
<td><b>(4) <a target="_blank" href="http://www.spoonbillsoftware.com.au/loderunner.htm">Lode Runner Fan Book</a></b></td> 
<td>(66 Levels)</td>
<td>Difficulty: 5</td>
</tr>

<tr>
<td><b>(5) <a target="_blank" href="https://en.wikipedia.org/wiki/Championship_Lode_Runner">Championship Lode Runner</a></b></td> 
<td>(51 Levels)</td>
<td>Difficulty: 5</td>
</tr>
</table>

### * Provide 2 Theme
<table>
<tr>
<td valign="middle">(1)</td>
<td valign="middle"><img src="image/apple2.png" height="23" width="20"></td>
<td><b>APPLE-II</b></td> 
</tr>
<tr>
<td valign="middle">(2)</td>
<td valign="middle"><img src="image/commodore64.png" height="23" width="20"></td>
<td valign="middle"><b>Commodore 64</b></td> 
</tr>
</table>

### * 2 Keyboard control mode

<table>
<tr>
<td valign="middle">(1)</td>
<td valign="middle"><img src="image/repeatOn.png" height="24" width="24"></td>
<td valign="middle"><b>Repeat Actions On:</b> Like APPLE-II keyboard behavior</td> 
</tr>
<tr>
<td valign="middle">(2)</td>
<td valign="middle"><img src="image/repeatOff.png" height="24" width="24"></td>
<td valign="middle"><b>Repeat Actions Off:</b> Like NES keyboard behavior</td> 
</tr>
</table>


### * PLAY
<a target="_blank" href="http://loderunnerwebgame.com/game/">http://loderunnerwebgame.com/game/</a>

------------------------------------


### vs-code debug 方式
1. vs-code安装live-server
2. 填写配置文件如下
```
{
    "version": "0.2.0",
    "configurations": [
        {
            "type": "chrome",
            "request": "launch",
            "name": "chrome 调试",
            "url": "http://localhost:5500",
            "webRoot": "${workspaceFolder}"
        }
    ]
}
```
3. 点击右下角的go live，vscode会自动在后台开启一个进程运行server，注意如果要关闭的话得再点击一下，关闭网页是没有用的
4. 然后再vscode的debug里点击一下就可以开始debug这个项目了

