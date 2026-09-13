# 💕 Pixelated Love - Typing Animation

<svg width="500" height="120" viewBox="0 0 500 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
      
      #char1 { animation: typeIn 0.15s steps(1) forwards; }
      #char2 { animation: typeIn 0.15s steps(1) 0.15s forwards; }
      #char3 { animation: typeIn 0.15s steps(1) 0.3s forwards; }
      #char4 { animation: typeIn 0.15s steps(1) 0.45s forwards; }
      #char5 { animation: typeIn 0.15s steps(1) 0.6s forwards; }
      #char6 { animation: typeIn 0.15s steps(1) 0.75s forwards; }
      #char7 { animation: typeIn 0.15s steps(1) 0.9s forwards; }
      #char8 { animation: typeIn 0.15s steps(1) 1.05s forwards; }
      #char9 { animation: typeIn 0.15s steps(1) 1.2s forwards; }
      #char10 { animation: typeIn 0.15s steps(1) 1.35s forwards; }
      
      #cursor { animation: blink 1s infinite 1.5s; }
      
      @keyframes typeIn {
        from { opacity: 0; }
        to { opacity: 1; }
      }
      
      @keyframes blink {
        0%, 49% { opacity: 1; }
        50%, 100% { opacity: 0; }
      }
      
      .text { 
        font-family: 'Press Start 2P', cursive;
        font-size: 48px;
        fill: #ff1493;
        letter-spacing: 3px;
      }
    </style>
  </defs>
  
  <!-- Each character with individual animation -->
  <text id="char1" class="text" x="20" y="70">I</text>
  <text id="char2" class="text" x="55" y="70"></text>
  <text id="char3" class="text" x="75" y="70">l</text>
  <text id="char4" class="text" x="100" y="70">o</text>
  <text id="char5" class="text" x="135" y="70">v</text>
  <text id="char6" class="text" x="165" y="70">e</text>
  <text id="char7" class="text" x="200" y="70"></text>
  <text id="char8" class="text" x="220" y="70">y</text>
  <text id="char9" class="text" x="255" y="70">o</text>
  <text id="char10" class="text" x="290" y="70">u</text>
  
  <!-- Blinking cursor -->
  <rect id="cursor" x="320" y="30" width="4" height="50" fill="#ff1493"/>
</svg>

---

✨ **Pure CSS + SVG Animation** - Works everywhere, no JavaScript needed!

This typing animation shows "I love you" with pixelated text using the Press Start 2P font and pure CSS animations.
