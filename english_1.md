---
layout: default_and_nav
title: Downloads
---
## Аудирование
<p><audio id="ID091" source src="assets/audio/page_91_ex_1.mp3"></audio>стр.91, упр.1&nbsp;<button onclick="playAudio('ID091')" type="button">слушать</button> </p>
<p><audio id="ID093" source src="assets/audio/page_93_ex_1.mp3"></audio>стр.93, упр.1&nbsp;<button onclick="playAudio('ID093')" type="button">слушать</button> </p>

<p>
  <audio id="ID098" source src="assets/audio/page_98_ex_1.mp3"></audio>
  стр.98, упр.1&nbsp;
  <button onclick="playAudio('ID098')" type="button">слушать</button>
  &nbsp;<a href='assets/audio/page_98_ex_1.mp3' download>скачать</a>
</p>

<p>
  <audio id="ID105" source src="assets/audio/page_105_ex_5_6.mp3"></audio>
  стр.105, упр.5-6&nbsp;
  <button onclick="playAudio('ID105')" type="button">слушать</button>
  &nbsp;<a href='assets/audio/page_105_ex_5_6.mp3' download>скачать</a>
</p>

<script>
function playAudio(audio_element) {
	var x = document.getElementById(audio_element);
	x.play();
}
</script>
