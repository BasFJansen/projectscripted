# Test


<style>
@keyframes shake-animation {
  0% { transform: translate(1px, 1px) rotate(0deg); }
  10% { transform: translate(-1px, -2px) rotate(-1deg); }
  20% { transform: translate(-3px, 0px) rotate(1deg); }
  30% { transform: translate(3px, 2px) rotate(0deg); }
  40% { transform: translate(1px, -1px) rotate(1deg); }
  50% { transform: translate(-1px, 2px) rotate(-1deg); }
  60% { transform: translate(-3px, 1px) rotate(0deg); }
  70% { transform: translate(3px, 1px) rotate(-1deg); }
  80% { transform: translate(-1px, -1px) rotate(1deg); }
  90% { transform: translate(1px, 2px) rotate(0deg); }
  100% { transform: translate(1px, -2px) rotate(0deg); }
}

.markdown-shake {
  display: inline-block;
  animation: shake-animation 0.5s infinite;
}
</style>

<span class="markdown-shake">⚠️ WARNING: This text is actively shaking! ⚠️</span>


<style>
.tooltip-container {
  position: relative;
  display: inline-block;
  border-bottom: 2px dashed #888;
  cursor: pointer;
}
.tooltip-box {
  visibility: hidden;
  width: 160px;
  background-color: #ff7575;
  color: #000000;
  text-align: center;
  border-radius: 6px;
  padding: 8px;
  position: absolute;
  z-index: 1;
  bottom: 125%; /* Position above the text */
  left: 50%;
  margin-left: -80px;
  opacity: 0;
  transition: opacity 0.3s;
}
.tooltip-container:hover .tooltip-box {
  visibility: visible;
  opacity: 1;
}
</style>

Check out this <span class="tooltip-container">interactive word<span class="tooltip-box">**Surprise! Here is your custom tooltip message.**</span></span> inside a sentence.
