<div class="center">
  <video controls src="https://ahacverhpougzlzojfyo.supabase.co/storage/v1/object/public/Uncategorized/gael-logo-mv.mp4" title="Gaël Animated Logo" autoplay muted playsinline loop></video>

  <br>
  <br>
</div>


# 🌠 Intro
<p class="intro-text">
  Hi
  <img src="https://ahacverhpougzlzojfyo.supabase.co/storage/v1/object/public/Uncategorized/waving-hand.gif" alt="Waving hand GIF" width=16>
  my name is
  <span class="gael-green tooltip" aria-describedby="gaelTooltip">
    Gaël
    <span class="tooltiptext" id="gaelTooltip" role="tooltip">
      It's pronounced 'Gayle' 😉
    </span>
  </span>
  and I'm a Canadian software engineer based in Toronto 🍁
</p>

<br>

# 🚀 Current hijinks
<ul>
  <li>Actively building <a href="https://github.com/gaeljacquin/yt-dlp-gui">yt-dlp GUI</a> - a cross platform audio/video downloader and client for <a href="https://github.com/yt-dlp/yt-dlp">yt-dlp</a></li>
  <li>Working out</li>
  <li>Learning Go</li>
  <li>Finding the best deals on Steam 🤑</li>
  <li>Gaming</li>
  <li>Working with a designer on an upcoming project</li>
</ul>

<br>

# 🔭 Tentative 2024 plans
<ul>
  <li>Take drawing lessons</li>
  <li>Outline ideas for my first game</li>
  <li>Test the Unreal Engine waters</li>
  <li>Start a blog</li>
</ul>

<br>

# 📫 Let's chat
You may connect with me on [LinkedIn <image src="https://ahacverhpougzlzojfyo.supabase.co/storage/v1/object/public/Uncategorized/linkedin2.svg" width=16>](https://linkedin.com/in/gaeljacquin)

<!-- I'm also looking for SSBU sparring partners online so feel free to DM me your friend code! I main 🤖 btw -->

<style>
  :root {
    --primary-color: #4CAF50;
  }

  .center {
    text-align: center;
  }

  .strikethrough {
    text-decoration: line-through;
  }

  .hover-container {
    position: relative;
    display: inline-block;
  }

  .hidden-text {
    visibility: hidden;
    opacity: 0;
    transition: visibility 0s, opacity 0.5s;
    position: relative;
    z-index: 1;
  }

  .hover-container::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: black;
    opacity: 0.7;
    transition: opacity 0.5s;
    z-index: 2;
  }

  .hover-container:hover::before {
    opacity: 0;
  }

  .hover-container:hover .hidden-text {
    visibility: visible;
    opacity: 1;
  }

  .gael-green {
    color: var(--primary-color)
  }

  ul {
    list-style-type: none;
  }

  ul li::before {
    content: "★";
    color: var(--primary-color);
    display: inline-block;
    width: 2em;
    margin-left: -3em;
  }

  .intro-text {
    font-size: 1.2em;
  }

  .tooltip {
    position: relative;
    display: inline-block;
  }

  .tooltip .tooltiptext {
    visibility: hidden;
    opacity: 0;
    width: 120px;
    background-color: black;
    color: #fff;
    text-align: center;
    padding: 5px 0;
    border-radius: 6px;
    position: absolute;
    z-index: 1;
    bottom: 100%;
    left: 50%;
    margin-left: -60px;
    transition: opacity 0.3s;
  }

  .tooltip:hover .tooltiptext {
    visibility: visible;
    opacity: 1;
  }
</style>
