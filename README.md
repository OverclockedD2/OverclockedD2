<h1 align="center"><img src="https://images.cooltext.com/5674198.png"></h1>
<font size="40"><P align="center">I'm a software engineer & developer, competitive programmer and investor</P></font>

<p align="center">
  <a href="https://github.com/overclockedd2?tab=repositories&sort=stargazers">
    <img src="https://img.shields.io/github/stars/overclockedd2?label=TOTAL STARS&style=for-the-badge&color=ffff00&labelColor=002045"/>
  </a>
  <a href="https://github.com/overclockedd2?tab=followers">
    <img src="https://img.shields.io/github/followers/overclockedd2?style=for-the-badge&color=ff0000&labelColor=002045"/>
  </a>
</p>


<br />
<p align="center">
  <img height="200" src="https://github-readme-stats.vercel.app/api?username=overclockedd2&theme=yeblu&show_icons=true" />
  <img height="200" src="https://github-readme-stats.vercel.app/api/top-langs/?username=overclockedd2&theme=yeblu" />
  <img height="200" src="https://github-readme-streak-stats.herokuapp.com/?user=overclockedd2&theme=yeblu"/>
</p>

<font size="400"><P align="center">Portfolio</P></font>

<input type="checkbox" id="difficulty" checked />
<input type="checkbox" id="sound" />
<input type="checkbox" id="first" />

<input type="checkbox" id="start" />

<form id="tictactoe">  
  <input type="radio" name="cell-0" id="cell-0-x" />
  <input type="radio" name="cell-0" id="cell-0-o" />
  <input type="radio" name="cell-1" id="cell-1-x" />
  <input type="radio" name="cell-1" id="cell-1-o" />
  <input type="radio" name="cell-2" id="cell-2-x" />
  <input type="radio" name="cell-2" id="cell-2-o" />
  <input type="radio" name="cell-3" id="cell-3-x" />
  <input type="radio" name="cell-3" id="cell-3-o" />
  <input type="radio" name="cell-4" id="cell-4-x" />
  <input type="radio" name="cell-4" id="cell-4-o" />
  <input type="radio" name="cell-5" id="cell-5-x" />
  <input type="radio" name="cell-5" id="cell-5-o" />
  <input type="radio" name="cell-6" id="cell-6-x" />
  <input type="radio" name="cell-6" id="cell-6-o" />
  <input type="radio" name="cell-7" id="cell-7-x" />
  <input type="radio" name="cell-7" id="cell-7-o" />
  <input type="radio" name="cell-8" id="cell-8-x" />
  <input type="radio" name="cell-8" id="cell-8-o" />

  <div id="menu" class="scrim">
    <div class="center">
      <h1>CSS Tic-Tac-Toe</h1>
      <div>
        <h2>Difficulty</h2>
        <div class="toggle-group">
          <span>Beginner</span>
          <label for="difficulty" class="toggle"></label>
          <span>Advanced</span>
        </div>
        <!-- Soon...
        <h2>Sound</h2>
        <div class="toggle-group">
          <span>Off</span>
          <label for="sound" class="toggle"></label>
          <span>On</span>
        </div>
        -->
        <h2>First turn</h2>
        <div class="toggle-group">
          <span>Player</span>
          <label for="first" class="toggle"></label>
          <span>Computer</span>
        </div>
        <label for="start" id="start-button" class="btn">Start Game</label>
      </div>
    </div>
  </div>

  <div id="board" class="center">
    <div class="tile" id="tile-0">
      <label for="cell-0-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-1">
      <label for="cell-1-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-2">
      <label for="cell-2-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-3">
      <label for="cell-3-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-4">
      <label for="cell-4-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-5">
      <label for="cell-5-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-6">
      <label for="cell-6-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-7">
      <label for="cell-7-x"></label>
      <div></div>
    </div>
    <div class="tile" id="tile-8">
      <label for="cell-8-x"></label>
      <div></div>
    </div>
  </div>
  <div id="label-computer" class="btn">
    Computer Move!
    <label for="cell-0-o"></label>
    <label for="cell-1-o"></label>
    <label for="cell-2-o"></label>
    <label for="cell-3-o"></label>
    <label for="cell-4-o"></label>
    <label for="cell-5-o"></label>
    <label for="cell-6-o"></label>
    <label for="cell-7-o"></label>
    <label for="cell-8-o"></label>
  </div>
  <div id="end" class="scrim">
    <div id="message" class="center">
      <div>
        <input type="reset" for="tictactoe" value="Play again" />
      </div>
    </div>
  </div>
</form>
