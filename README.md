* {
  margin: 0;
  padding: 0;
}

html,
body {
  width: 100%;
  height: 100%;
  overflow: hidden;
}

body {
  background-color: #021027;
}

.container {
  width: 100%;
  height: 100%;
  overflow: hidden;
  position: relative;
}

.background {
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  -o-object-fit: cover;
     object-fit: cover;
  width: 100%;
  height: 100%;
  -webkit-mask-image: radial-gradient(white 0%, white 30%, transparent 80%, transparent);
          mask-image: radial-gradient(white 0%, white 30%, transparent 80%, transparent);
}

.circle-container {
  position: absolute;
  -webkit-transform: translateY(-10vh);
          transform: translateY(-10vh);
  -webkit-animation-iteration-count: infinite;
          animation-iteration-count: infinite;
  -webkit-animation-timing-function: linear;
          animation-timing-function: linear;
}
.circle-container .circle {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  mix-blend-mode: screen;
  background-image: radial-gradient(#99ffff, #99ffff 10%, rgba(153, 255, 255, 0) 56%);
  -webkit-animation: fadein-frames 200ms infinite, scale-frames 2s infinite;
          animation: fadein-frames 200ms infinite, scale-frames 2s infinite;
}
@-webkit-keyframes fade-frames {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0.7;
  }
  100% {
    opacity: 1;
  }
}
@keyframes fade-frames {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0.7;
  }
  100% {
    opacity: 1;
  }
}
@-webkit-keyframes scale-frames {
  0% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
  50% {
    -webkit-transform: scale3d(2.2, 2.2, 1);
            transform: scale3d(2.2, 2.2, 1);
  }
  100% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
}
@keyframes scale-frames {
  0% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
  50% {
    -webkit-transform: scale3d(2.2, 2.2, 1);
            transform: scale3d(2.2, 2.2, 1);
  }
  100% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
}
.circle-container:nth-child(1) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-1;
          animation-name: move-frames-1;
  -webkit-animation-duration: 34227ms;
          animation-duration: 34227ms;
  -webkit-animation-delay: 12123ms;
          animation-delay: 12123ms;
}
@-webkit-keyframes move-frames-1 {
  from {
    -webkit-transform: translate3d(96vw, 101vh, 0);
            transform: translate3d(96vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(79vw, -129vh, 0);
            transform: translate3d(79vw, -129vh, 0);
  }
}
@keyframes move-frames-1 {
  from {
    -webkit-transform: translate3d(96vw, 101vh, 0);
            transform: translate3d(96vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(79vw, -129vh, 0);
            transform: translate3d(79vw, -129vh, 0);
  }
}
.circle-container:nth-child(1) .circle {
  -webkit-animation-delay: 3711ms;
          animation-delay: 3711ms;
}
.circle-container:nth-child(2) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-2;
          animation-name: move-frames-2;
  -webkit-animation-duration: 28770ms;
          animation-duration: 28770ms;
  -webkit-animation-delay: 13031ms;
          animation-delay: 13031ms;
}
@-webkit-keyframes move-frames-2 {
  from {
    -webkit-transform: translate3d(25vw, 105vh, 0);
            transform: translate3d(25vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(29vw, -108vh, 0);
            transform: translate3d(29vw, -108vh, 0);
  }
}
@keyframes move-frames-2 {
  from {
    -webkit-transform: translate3d(25vw, 105vh, 0);
            transform: translate3d(25vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(29vw, -108vh, 0);
            transform: translate3d(29vw, -108vh, 0);
  }
}
.circle-container:nth-child(2) .circle {
  -webkit-animation-delay: 1312ms;
          animation-delay: 1312ms;
}
.circle-container:nth-child(3) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-3;
          animation-name: move-frames-3;
  -webkit-animation-duration: 30530ms;
          animation-duration: 30530ms;
  -webkit-animation-delay: 19835ms;
          animation-delay: 19835ms;
}
@-webkit-keyframes move-frames-3 {
  from {
    -webkit-transform: translate3d(76vw, 101vh, 0);
            transform: translate3d(76vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -124vh, 0);
            transform: translate3d(49vw, -124vh, 0);
  }
}
@keyframes move-frames-3 {
  from {
    -webkit-transform: translate3d(76vw, 101vh, 0);
            transform: translate3d(76vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -124vh, 0);
            transform: translate3d(49vw, -124vh, 0);
  }
}
.circle-container:nth-child(3) .circle {
  -webkit-animation-delay: 259ms;
          animation-delay: 259ms;
}
.circle-container:nth-child(4) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-4;
          animation-name: move-frames-4;
  -webkit-animation-duration: 28458ms;
          animation-duration: 28458ms;
  -webkit-animation-delay: 30861ms;
          animation-delay: 30861ms;
}
@-webkit-keyframes move-frames-4 {
  from {
    -webkit-transform: translate3d(71vw, 110vh, 0);
            transform: translate3d(71vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -114vh, 0);
            transform: translate3d(5vw, -114vh, 0);
  }
}
@keyframes move-frames-4 {
  from {
    -webkit-transform: translate3d(71vw, 110vh, 0);
            transform: translate3d(71vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -114vh, 0);
            transform: translate3d(5vw, -114vh, 0);
  }
}
.circle-container:nth-child(4) .circle {
  -webkit-animation-delay: 2001ms;
          animation-delay: 2001ms;
}
.circle-container:nth-child(5) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-5;
          animation-name: move-frames-5;
  -webkit-animation-duration: 34336ms;
          animation-duration: 34336ms;
  -webkit-animation-delay: 33136ms;
          animation-delay: 33136ms;
}
@-webkit-keyframes move-frames-5 {
  from {
    -webkit-transform: translate3d(33vw, 103vh, 0);
            transform: translate3d(33vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -130vh, 0);
            transform: translate3d(7vw, -130vh, 0);
  }
}
@keyframes move-frames-5 {
  from {
    -webkit-transform: translate3d(33vw, 103vh, 0);
            transform: translate3d(33vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -130vh, 0);
            transform: translate3d(7vw, -130vh, 0);
  }
}
.circle-container:nth-child(5) .circle {
  -webkit-animation-delay: 3784ms;
          animation-delay: 3784ms;
}
.circle-container:nth-child(6) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-6;
          animation-name: move-frames-6;
  -webkit-animation-duration: 34283ms;
          animation-duration: 34283ms;
  -webkit-animation-delay: 28654ms;
          animation-delay: 28654ms;
}
@-webkit-keyframes move-frames-6 {
  from {
    -webkit-transform: translate3d(65vw, 105vh, 0);
            transform: translate3d(65vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -122vh, 0);
            transform: translate3d(6vw, -122vh, 0);
  }
}
@keyframes move-frames-6 {
  from {
    -webkit-transform: translate3d(65vw, 105vh, 0);
            transform: translate3d(65vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -122vh, 0);
            transform: translate3d(6vw, -122vh, 0);
  }
}
.circle-container:nth-child(6) .circle {
  -webkit-animation-delay: 2495ms;
          animation-delay: 2495ms;
}
.circle-container:nth-child(7) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-7;
          animation-name: move-frames-7;
  -webkit-animation-duration: 30743ms;
          animation-duration: 30743ms;
  -webkit-animation-delay: 4869ms;
          animation-delay: 4869ms;
}
@-webkit-keyframes move-frames-7 {
  from {
    -webkit-transform: translate3d(12vw, 109vh, 0);
            transform: translate3d(12vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -112vh, 0);
            transform: translate3d(62vw, -112vh, 0);
  }
}
@keyframes move-frames-7 {
  from {
    -webkit-transform: translate3d(12vw, 109vh, 0);
            transform: translate3d(12vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -112vh, 0);
            transform: translate3d(62vw, -112vh, 0);
  }
}
.circle-container:nth-child(7) .circle {
  -webkit-animation-delay: 1519ms;
          animation-delay: 1519ms;
}
.circle-container:nth-child(8) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-8;
          animation-name: move-frames-8;
  -webkit-animation-duration: 30229ms;
          animation-duration: 30229ms;
  -webkit-animation-delay: 13890ms;
          animation-delay: 13890ms;
}
@-webkit-keyframes move-frames-8 {
  from {
    -webkit-transform: translate3d(85vw, 110vh, 0);
            transform: translate3d(85vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -117vh, 0);
            transform: translate3d(69vw, -117vh, 0);
  }
}
@keyframes move-frames-8 {
  from {
    -webkit-transform: translate3d(85vw, 110vh, 0);
            transform: translate3d(85vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -117vh, 0);
            transform: translate3d(69vw, -117vh, 0);
  }
}
.circle-container:nth-child(8) .circle {
  -webkit-animation-delay: 723ms;
          animation-delay: 723ms;
}
.circle-container:nth-child(9) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-9;
          animation-name: move-frames-9;
  -webkit-animation-duration: 32226ms;
          animation-duration: 32226ms;
  -webkit-animation-delay: 11330ms;
          animation-delay: 11330ms;
}
@-webkit-keyframes move-frames-9 {
  from {
    -webkit-transform: translate3d(49vw, 106vh, 0);
            transform: translate3d(49vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -117vh, 0);
            transform: translate3d(91vw, -117vh, 0);
  }
}
@keyframes move-frames-9 {
  from {
    -webkit-transform: translate3d(49vw, 106vh, 0);
            transform: translate3d(49vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -117vh, 0);
            transform: translate3d(91vw, -117vh, 0);
  }
}
.circle-container:nth-child(9) .circle {
  -webkit-animation-delay: 2869ms;
          animation-delay: 2869ms;
}
.circle-container:nth-child(10) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-10;
          animation-name: move-frames-10;
  -webkit-animation-duration: 28561ms;
          animation-duration: 28561ms;
  -webkit-animation-delay: 27619ms;
          animation-delay: 27619ms;
}
@-webkit-keyframes move-frames-10 {
  from {
    -webkit-transform: translate3d(90vw, 103vh, 0);
            transform: translate3d(90vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -109vh, 0);
            transform: translate3d(70vw, -109vh, 0);
  }
}
@keyframes move-frames-10 {
  from {
    -webkit-transform: translate3d(90vw, 103vh, 0);
            transform: translate3d(90vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -109vh, 0);
            transform: translate3d(70vw, -109vh, 0);
  }
}
.circle-container:nth-child(10) .circle {
  -webkit-animation-delay: 14ms;
          animation-delay: 14ms;
}
.circle-container:nth-child(11) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-11;
          animation-name: move-frames-11;
  -webkit-animation-duration: 33564ms;
          animation-duration: 33564ms;
  -webkit-animation-delay: 11786ms;
          animation-delay: 11786ms;
}
@-webkit-keyframes move-frames-11 {
  from {
    -webkit-transform: translate3d(90vw, 101vh, 0);
            transform: translate3d(90vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -117vh, 0);
            transform: translate3d(31vw, -117vh, 0);
  }
}
@keyframes move-frames-11 {
  from {
    -webkit-transform: translate3d(90vw, 101vh, 0);
            transform: translate3d(90vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -117vh, 0);
            transform: translate3d(31vw, -117vh, 0);
  }
}
.circle-container:nth-child(11) .circle {
  -webkit-animation-delay: 2613ms;
          animation-delay: 2613ms;
}
.circle-container:nth-child(12) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-12;
          animation-name: move-frames-12;
  -webkit-animation-duration: 32631ms;
          animation-duration: 32631ms;
  -webkit-animation-delay: 9229ms;
          animation-delay: 9229ms;
}
@-webkit-keyframes move-frames-12 {
  from {
    -webkit-transform: translate3d(22vw, 110vh, 0);
            transform: translate3d(22vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(22vw, -139vh, 0);
            transform: translate3d(22vw, -139vh, 0);
  }
}
@keyframes move-frames-12 {
  from {
    -webkit-transform: translate3d(22vw, 110vh, 0);
            transform: translate3d(22vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(22vw, -139vh, 0);
            transform: translate3d(22vw, -139vh, 0);
  }
}
.circle-container:nth-child(12) .circle {
  -webkit-animation-delay: 3319ms;
          animation-delay: 3319ms;
}
.circle-container:nth-child(13) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-13;
          animation-name: move-frames-13;
  -webkit-animation-duration: 30053ms;
          animation-duration: 30053ms;
  -webkit-animation-delay: 36578ms;
          animation-delay: 36578ms;
}
@-webkit-keyframes move-frames-13 {
  from {
    -webkit-transform: translate3d(84vw, 106vh, 0);
            transform: translate3d(84vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -108vh, 0);
            transform: translate3d(32vw, -108vh, 0);
  }
}
@keyframes move-frames-13 {
  from {
    -webkit-transform: translate3d(84vw, 106vh, 0);
            transform: translate3d(84vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -108vh, 0);
            transform: translate3d(32vw, -108vh, 0);
  }
}
.circle-container:nth-child(13) .circle {
  -webkit-animation-delay: 3285ms;
          animation-delay: 3285ms;
}
.circle-container:nth-child(14) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-14;
          animation-name: move-frames-14;
  -webkit-animation-duration: 28502ms;
          animation-duration: 28502ms;
  -webkit-animation-delay: 6335ms;
          animation-delay: 6335ms;
}
@-webkit-keyframes move-frames-14 {
  from {
    -webkit-transform: translate3d(58vw, 106vh, 0);
            transform: translate3d(58vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(64vw, -125vh, 0);
            transform: translate3d(64vw, -125vh, 0);
  }
}
@keyframes move-frames-14 {
  from {
    -webkit-transform: translate3d(58vw, 106vh, 0);
            transform: translate3d(58vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(64vw, -125vh, 0);
            transform: translate3d(64vw, -125vh, 0);
  }
}
.circle-container:nth-child(14) .circle {
  -webkit-animation-delay: 3345ms;
          animation-delay: 3345ms;
}
.circle-container:nth-child(15) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-15;
          animation-name: move-frames-15;
  -webkit-animation-duration: 32654ms;
          animation-duration: 32654ms;
  -webkit-animation-delay: 6685ms;
          animation-delay: 6685ms;
}
@-webkit-keyframes move-frames-15 {
  from {
    -webkit-transform: translate3d(58vw, 106vh, 0);
            transform: translate3d(58vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -120vh, 0);
            transform: translate3d(33vw, -120vh, 0);
  }
}
@keyframes move-frames-15 {
  from {
    -webkit-transform: translate3d(58vw, 106vh, 0);
            transform: translate3d(58vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -120vh, 0);
            transform: translate3d(33vw, -120vh, 0);
  }
}
.circle-container:nth-child(15) .circle {
  -webkit-animation-delay: 3396ms;
          animation-delay: 3396ms;
}
.circle-container:nth-child(16) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-16;
          animation-name: move-frames-16;
  -webkit-animation-duration: 30425ms;
          animation-duration: 30425ms;
  -webkit-animation-delay: 7637ms;
          animation-delay: 7637ms;
}
@-webkit-keyframes move-frames-16 {
  from {
    -webkit-transform: translate3d(70vw, 108vh, 0);
            transform: translate3d(70vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -126vh, 0);
            transform: translate3d(54vw, -126vh, 0);
  }
}
@keyframes move-frames-16 {
  from {
    -webkit-transform: translate3d(70vw, 108vh, 0);
            transform: translate3d(70vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -126vh, 0);
            transform: translate3d(54vw, -126vh, 0);
  }
}
.circle-container:nth-child(16) .circle {
  -webkit-animation-delay: 1960ms;
          animation-delay: 1960ms;
}
.circle-container:nth-child(17) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-17;
          animation-name: move-frames-17;
  -webkit-animation-duration: 30564ms;
          animation-duration: 30564ms;
  -webkit-animation-delay: 16244ms;
          animation-delay: 16244ms;
}
@-webkit-keyframes move-frames-17 {
  from {
    -webkit-transform: translate3d(47vw, 107vh, 0);
            transform: translate3d(47vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(97vw, -116vh, 0);
            transform: translate3d(97vw, -116vh, 0);
  }
}
@keyframes move-frames-17 {
  from {
    -webkit-transform: translate3d(47vw, 107vh, 0);
            transform: translate3d(47vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(97vw, -116vh, 0);
            transform: translate3d(97vw, -116vh, 0);
  }
}
.circle-container:nth-child(17) .circle {
  -webkit-animation-delay: 1731ms;
          animation-delay: 1731ms;
}
.circle-container:nth-child(18) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-18;
          animation-name: move-frames-18;
  -webkit-animation-duration: 36666ms;
          animation-duration: 36666ms;
  -webkit-animation-delay: 21863ms;
          animation-delay: 21863ms;
}
@-webkit-keyframes move-frames-18 {
  from {
    -webkit-transform: translate3d(58vw, 104vh, 0);
            transform: translate3d(58vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(1vw, -107vh, 0);
            transform: translate3d(1vw, -107vh, 0);
  }
}
@keyframes move-frames-18 {
  from {
    -webkit-transform: translate3d(58vw, 104vh, 0);
            transform: translate3d(58vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(1vw, -107vh, 0);
            transform: translate3d(1vw, -107vh, 0);
  }
}
.circle-container:nth-child(18) .circle {
  -webkit-animation-delay: 712ms;
          animation-delay: 712ms;
}
.circle-container:nth-child(19) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-19;
          animation-name: move-frames-19;
  -webkit-animation-duration: 32069ms;
          animation-duration: 32069ms;
  -webkit-animation-delay: 20309ms;
          animation-delay: 20309ms;
}
@-webkit-keyframes move-frames-19 {
  from {
    -webkit-transform: translate3d(56vw, 107vh, 0);
            transform: translate3d(56vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -109vh, 0);
            transform: translate3d(17vw, -109vh, 0);
  }
}
@keyframes move-frames-19 {
  from {
    -webkit-transform: translate3d(56vw, 107vh, 0);
            transform: translate3d(56vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -109vh, 0);
            transform: translate3d(17vw, -109vh, 0);
  }
}
.circle-container:nth-child(19) .circle {
  -webkit-animation-delay: 1975ms;
          animation-delay: 1975ms;
}
.circle-container:nth-child(20) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-20;
          animation-name: move-frames-20;
  -webkit-animation-duration: 33326ms;
          animation-duration: 33326ms;
  -webkit-animation-delay: 2035ms;
          animation-delay: 2035ms;
}
@-webkit-keyframes move-frames-20 {
  from {
    -webkit-transform: translate3d(7vw, 101vh, 0);
            transform: translate3d(7vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -107vh, 0);
            transform: translate3d(18vw, -107vh, 0);
  }
}
@keyframes move-frames-20 {
  from {
    -webkit-transform: translate3d(7vw, 101vh, 0);
            transform: translate3d(7vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -107vh, 0);
            transform: translate3d(18vw, -107vh, 0);
  }
}
.circle-container:nth-child(20) .circle {
  -webkit-animation-delay: 1330ms;
          animation-delay: 1330ms;
}
.circle-container:nth-child(21) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-21;
          animation-name: move-frames-21;
  -webkit-animation-duration: 28651ms;
          animation-duration: 28651ms;
  -webkit-animation-delay: 22891ms;
          animation-delay: 22891ms;
}
@-webkit-keyframes move-frames-21 {
  from {
    -webkit-transform: translate3d(80vw, 106vh, 0);
            transform: translate3d(80vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(58vw, -116vh, 0);
            transform: translate3d(58vw, -116vh, 0);
  }
}
@keyframes move-frames-21 {
  from {
    -webkit-transform: translate3d(80vw, 106vh, 0);
            transform: translate3d(80vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(58vw, -116vh, 0);
            transform: translate3d(58vw, -116vh, 0);
  }
}
.circle-container:nth-child(21) .circle {
  -webkit-animation-delay: 249ms;
          animation-delay: 249ms;
}
.circle-container:nth-child(22) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-22;
          animation-name: move-frames-22;
  -webkit-animation-duration: 31339ms;
          animation-duration: 31339ms;
  -webkit-animation-delay: 14699ms;
          animation-delay: 14699ms;
}
@-webkit-keyframes move-frames-22 {
  from {
    -webkit-transform: translate3d(84vw, 103vh, 0);
            transform: translate3d(84vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(59vw, -130vh, 0);
            transform: translate3d(59vw, -130vh, 0);
  }
}
@keyframes move-frames-22 {
  from {
    -webkit-transform: translate3d(84vw, 103vh, 0);
            transform: translate3d(84vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(59vw, -130vh, 0);
            transform: translate3d(59vw, -130vh, 0);
  }
}
.circle-container:nth-child(22) .circle {
  -webkit-animation-delay: 1383ms;
          animation-delay: 1383ms;
}
.circle-container:nth-child(23) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-23;
          animation-name: move-frames-23;
  -webkit-animation-duration: 35127ms;
          animation-duration: 35127ms;
  -webkit-animation-delay: 30896ms;
          animation-delay: 30896ms;
}
@-webkit-keyframes move-frames-23 {
  from {
    -webkit-transform: translate3d(98vw, 105vh, 0);
            transform: translate3d(98vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(56vw, -109vh, 0);
            transform: translate3d(56vw, -109vh, 0);
  }
}
@keyframes move-frames-23 {
  from {
    -webkit-transform: translate3d(98vw, 105vh, 0);
            transform: translate3d(98vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(56vw, -109vh, 0);
            transform: translate3d(56vw, -109vh, 0);
  }
}
.circle-container:nth-child(23) .circle {
  -webkit-animation-delay: 2899ms;
          animation-delay: 2899ms;
}
.circle-container:nth-child(24) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-24;
          animation-name: move-frames-24;
  -webkit-animation-duration: 35400ms;
          animation-duration: 35400ms;
  -webkit-animation-delay: 239ms;
          animation-delay: 239ms;
}
@-webkit-keyframes move-frames-24 {
  from {
    -webkit-transform: translate3d(22vw, 110vh, 0);
            transform: translate3d(22vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -135vh, 0);
            transform: translate3d(41vw, -135vh, 0);
  }
}
@keyframes move-frames-24 {
  from {
    -webkit-transform: translate3d(22vw, 110vh, 0);
            transform: translate3d(22vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -135vh, 0);
            transform: translate3d(41vw, -135vh, 0);
  }
}
.circle-container:nth-child(24) .circle {
  -webkit-animation-delay: 6ms;
          animation-delay: 6ms;
}
.circle-container:nth-child(25) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-25;
          animation-name: move-frames-25;
  -webkit-animation-duration: 33549ms;
          animation-duration: 33549ms;
  -webkit-animation-delay: 3514ms;
          animation-delay: 3514ms;
}
@-webkit-keyframes move-frames-25 {
  from {
    -webkit-transform: translate3d(64vw, 108vh, 0);
            transform: translate3d(64vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -110vh, 0);
            transform: translate3d(39vw, -110vh, 0);
  }
}
@keyframes move-frames-25 {
  from {
    -webkit-transform: translate3d(64vw, 108vh, 0);
            transform: translate3d(64vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -110vh, 0);
            transform: translate3d(39vw, -110vh, 0);
  }
}
.circle-container:nth-child(25) .circle {
  -webkit-animation-delay: 1659ms;
          animation-delay: 1659ms;
}
.circle-container:nth-child(26) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-26;
          animation-name: move-frames-26;
  -webkit-animation-duration: 30213ms;
          animation-duration: 30213ms;
  -webkit-animation-delay: 11461ms;
          animation-delay: 11461ms;
}
@-webkit-keyframes move-frames-26 {
  from {
    -webkit-transform: translate3d(26vw, 103vh, 0);
            transform: translate3d(26vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -121vh, 0);
            transform: translate3d(51vw, -121vh, 0);
  }
}
@keyframes move-frames-26 {
  from {
    -webkit-transform: translate3d(26vw, 103vh, 0);
            transform: translate3d(26vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -121vh, 0);
            transform: translate3d(51vw, -121vh, 0);
  }
}
.circle-container:nth-child(26) .circle {
  -webkit-animation-delay: 1968ms;
          animation-delay: 1968ms;
}
.circle-container:nth-child(27) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-27;
          animation-name: move-frames-27;
  -webkit-animation-duration: 32589ms;
          animation-duration: 32589ms;
  -webkit-animation-delay: 34289ms;
          animation-delay: 34289ms;
}
@-webkit-keyframes move-frames-27 {
  from {
    -webkit-transform: translate3d(33vw, 108vh, 0);
            transform: translate3d(33vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(90vw, -110vh, 0);
            transform: translate3d(90vw, -110vh, 0);
  }
}
@keyframes move-frames-27 {
  from {
    -webkit-transform: translate3d(33vw, 108vh, 0);
            transform: translate3d(33vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(90vw, -110vh, 0);
            transform: translate3d(90vw, -110vh, 0);
  }
}
.circle-container:nth-child(27) .circle {
  -webkit-animation-delay: 1744ms;
          animation-delay: 1744ms;
}
.circle-container:nth-child(28) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-28;
          animation-name: move-frames-28;
  -webkit-animation-duration: 34088ms;
          animation-duration: 34088ms;
  -webkit-animation-delay: 1162ms;
          animation-delay: 1162ms;
}
@-webkit-keyframes move-frames-28 {
  from {
    -webkit-transform: translate3d(78vw, 108vh, 0);
            transform: translate3d(78vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(9vw, -135vh, 0);
            transform: translate3d(9vw, -135vh, 0);
  }
}
@keyframes move-frames-28 {
  from {
    -webkit-transform: translate3d(78vw, 108vh, 0);
            transform: translate3d(78vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(9vw, -135vh, 0);
            transform: translate3d(9vw, -135vh, 0);
  }
}
.circle-container:nth-child(28) .circle {
  -webkit-animation-delay: 2186ms;
          animation-delay: 2186ms;
}
.circle-container:nth-child(29) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-29;
          animation-name: move-frames-29;
  -webkit-animation-duration: 34212ms;
          animation-duration: 34212ms;
  -webkit-animation-delay: 5108ms;
          animation-delay: 5108ms;
}
@-webkit-keyframes move-frames-29 {
  from {
    -webkit-transform: translate3d(80vw, 101vh, 0);
            transform: translate3d(80vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -103vh, 0);
            transform: translate3d(2vw, -103vh, 0);
  }
}
@keyframes move-frames-29 {
  from {
    -webkit-transform: translate3d(80vw, 101vh, 0);
            transform: translate3d(80vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -103vh, 0);
            transform: translate3d(2vw, -103vh, 0);
  }
}
.circle-container:nth-child(29) .circle {
  -webkit-animation-delay: 2177ms;
          animation-delay: 2177ms;
}
.circle-container:nth-child(30) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-30;
          animation-name: move-frames-30;
  -webkit-animation-duration: 30127ms;
          animation-duration: 30127ms;
  -webkit-animation-delay: 14382ms;
          animation-delay: 14382ms;
}
@-webkit-keyframes move-frames-30 {
  from {
    -webkit-transform: translate3d(9vw, 105vh, 0);
            transform: translate3d(9vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -131vh, 0);
            transform: translate3d(47vw, -131vh, 0);
  }
}
@keyframes move-frames-30 {
  from {
    -webkit-transform: translate3d(9vw, 105vh, 0);
            transform: translate3d(9vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -131vh, 0);
            transform: translate3d(47vw, -131vh, 0);
  }
}
.circle-container:nth-child(30) .circle {
  -webkit-animation-delay: 1597ms;
          animation-delay: 1597ms;
}
.circle-container:nth-child(31) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-31;
          animation-name: move-frames-31;
  -webkit-animation-duration: 32586ms;
          animation-duration: 32586ms;
  -webkit-animation-delay: 13930ms;
          animation-delay: 13930ms;
}
@-webkit-keyframes move-frames-31 {
  from {
    -webkit-transform: translate3d(80vw, 109vh, 0);
            transform: translate3d(80vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -136vh, 0);
            transform: translate3d(99vw, -136vh, 0);
  }
}
@keyframes move-frames-31 {
  from {
    -webkit-transform: translate3d(80vw, 109vh, 0);
            transform: translate3d(80vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -136vh, 0);
            transform: translate3d(99vw, -136vh, 0);
  }
}
.circle-container:nth-child(31) .circle {
  -webkit-animation-delay: 1511ms;
          animation-delay: 1511ms;
}
.circle-container:nth-child(32) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-32;
          animation-name: move-frames-32;
  -webkit-animation-duration: 34421ms;
          animation-duration: 34421ms;
  -webkit-animation-delay: 373ms;
          animation-delay: 373ms;
}
@-webkit-keyframes move-frames-32 {
  from {
    -webkit-transform: translate3d(68vw, 108vh, 0);
            transform: translate3d(68vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -128vh, 0);
            transform: translate3d(91vw, -128vh, 0);
  }
}
@keyframes move-frames-32 {
  from {
    -webkit-transform: translate3d(68vw, 108vh, 0);
            transform: translate3d(68vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -128vh, 0);
            transform: translate3d(91vw, -128vh, 0);
  }
}
.circle-container:nth-child(32) .circle {
  -webkit-animation-delay: 3941ms;
          animation-delay: 3941ms;
}
.circle-container:nth-child(33) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-33;
          animation-name: move-frames-33;
  -webkit-animation-duration: 36013ms;
          animation-duration: 36013ms;
  -webkit-animation-delay: 33409ms;
          animation-delay: 33409ms;
}
@-webkit-keyframes move-frames-33 {
  from {
    -webkit-transform: translate3d(26vw, 107vh, 0);
            transform: translate3d(26vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(27vw, -123vh, 0);
            transform: translate3d(27vw, -123vh, 0);
  }
}
@keyframes move-frames-33 {
  from {
    -webkit-transform: translate3d(26vw, 107vh, 0);
            transform: translate3d(26vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(27vw, -123vh, 0);
            transform: translate3d(27vw, -123vh, 0);
  }
}
.circle-container:nth-child(33) .circle {
  -webkit-animation-delay: 2683ms;
          animation-delay: 2683ms;
}
.circle-container:nth-child(34) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-34;
          animation-name: move-frames-34;
  -webkit-animation-duration: 32027ms;
          animation-duration: 32027ms;
  -webkit-animation-delay: 6252ms;
          animation-delay: 6252ms;
}
@-webkit-keyframes move-frames-34 {
  from {
    -webkit-transform: translate3d(50vw, 102vh, 0);
            transform: translate3d(50vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(85vw, -124vh, 0);
            transform: translate3d(85vw, -124vh, 0);
  }
}
@keyframes move-frames-34 {
  from {
    -webkit-transform: translate3d(50vw, 102vh, 0);
            transform: translate3d(50vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(85vw, -124vh, 0);
            transform: translate3d(85vw, -124vh, 0);
  }
}
.circle-container:nth-child(34) .circle {
  -webkit-animation-delay: 2837ms;
          animation-delay: 2837ms;
}
.circle-container:nth-child(35) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-35;
          animation-name: move-frames-35;
  -webkit-animation-duration: 32082ms;
          animation-duration: 32082ms;
  -webkit-animation-delay: 11674ms;
          animation-delay: 11674ms;
}
@-webkit-keyframes move-frames-35 {
  from {
    -webkit-transform: translate3d(81vw, 106vh, 0);
            transform: translate3d(81vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -135vh, 0);
            transform: translate3d(2vw, -135vh, 0);
  }
}
@keyframes move-frames-35 {
  from {
    -webkit-transform: translate3d(81vw, 106vh, 0);
            transform: translate3d(81vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -135vh, 0);
            transform: translate3d(2vw, -135vh, 0);
  }
}
.circle-container:nth-child(35) .circle {
  -webkit-animation-delay: 236ms;
          animation-delay: 236ms;
}
.circle-container:nth-child(36) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-36;
          animation-name: move-frames-36;
  -webkit-animation-duration: 31637ms;
          animation-duration: 31637ms;
  -webkit-animation-delay: 14944ms;
          animation-delay: 14944ms;
}
@-webkit-keyframes move-frames-36 {
  from {
    -webkit-transform: translate3d(46vw, 108vh, 0);
            transform: translate3d(46vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -129vh, 0);
            transform: translate3d(33vw, -129vh, 0);
  }
}
@keyframes move-frames-36 {
  from {
    -webkit-transform: translate3d(46vw, 108vh, 0);
            transform: translate3d(46vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -129vh, 0);
            transform: translate3d(33vw, -129vh, 0);
  }
}
.circle-container:nth-child(36) .circle {
  -webkit-animation-delay: 2891ms;
          animation-delay: 2891ms;
}
.circle-container:nth-child(37) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-37;
          animation-name: move-frames-37;
  -webkit-animation-duration: 31740ms;
          animation-duration: 31740ms;
  -webkit-animation-delay: 27743ms;
          animation-delay: 27743ms;
}
@-webkit-keyframes move-frames-37 {
  from {
    -webkit-transform: translate3d(52vw, 105vh, 0);
            transform: translate3d(52vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -128vh, 0);
            transform: translate3d(78vw, -128vh, 0);
  }
}
@keyframes move-frames-37 {
  from {
    -webkit-transform: translate3d(52vw, 105vh, 0);
            transform: translate3d(52vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -128vh, 0);
            transform: translate3d(78vw, -128vh, 0);
  }
}
.circle-container:nth-child(37) .circle {
  -webkit-animation-delay: 1485ms;
          animation-delay: 1485ms;
}
.circle-container:nth-child(38) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-38;
          animation-name: move-frames-38;
  -webkit-animation-duration: 31289ms;
          animation-duration: 31289ms;
  -webkit-animation-delay: 32297ms;
          animation-delay: 32297ms;
}
@-webkit-keyframes move-frames-38 {
  from {
    -webkit-transform: translate3d(11vw, 102vh, 0);
            transform: translate3d(11vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -114vh, 0);
            transform: translate3d(2vw, -114vh, 0);
  }
}
@keyframes move-frames-38 {
  from {
    -webkit-transform: translate3d(11vw, 102vh, 0);
            transform: translate3d(11vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -114vh, 0);
            transform: translate3d(2vw, -114vh, 0);
  }
}
.circle-container:nth-child(38) .circle {
  -webkit-animation-delay: 2631ms;
          animation-delay: 2631ms;
}
.circle-container:nth-child(39) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-39;
          animation-name: move-frames-39;
  -webkit-animation-duration: 30106ms;
          animation-duration: 30106ms;
  -webkit-animation-delay: 29126ms;
          animation-delay: 29126ms;
}
@-webkit-keyframes move-frames-39 {
  from {
    -webkit-transform: translate3d(7vw, 101vh, 0);
            transform: translate3d(7vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(64vw, -117vh, 0);
            transform: translate3d(64vw, -117vh, 0);
  }
}
@keyframes move-frames-39 {
  from {
    -webkit-transform: translate3d(7vw, 101vh, 0);
            transform: translate3d(7vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(64vw, -117vh, 0);
            transform: translate3d(64vw, -117vh, 0);
  }
}
.circle-container:nth-child(39) .circle {
  -webkit-animation-delay: 1274ms;
          animation-delay: 1274ms;
}
.circle-container:nth-child(40) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-40;
          animation-name: move-frames-40;
  -webkit-animation-duration: 30643ms;
          animation-duration: 30643ms;
  -webkit-animation-delay: 5394ms;
          animation-delay: 5394ms;
}
@-webkit-keyframes move-frames-40 {
  from {
    -webkit-transform: translate3d(44vw, 103vh, 0);
            transform: translate3d(44vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -120vh, 0);
            transform: translate3d(78vw, -120vh, 0);
  }
}
@keyframes move-frames-40 {
  from {
    -webkit-transform: translate3d(44vw, 103vh, 0);
            transform: translate3d(44vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -120vh, 0);
            transform: translate3d(78vw, -120vh, 0);
  }
}
.circle-container:nth-child(40) .circle {
  -webkit-animation-delay: 3530ms;
          animation-delay: 3530ms;
}
.circle-container:nth-child(41) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-41;
          animation-name: move-frames-41;
  -webkit-animation-duration: 35414ms;
          animation-duration: 35414ms;
  -webkit-animation-delay: 11699ms;
          animation-delay: 11699ms;
}
@-webkit-keyframes move-frames-41 {
  from {
    -webkit-transform: translate3d(15vw, 108vh, 0);
            transform: translate3d(15vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -112vh, 0);
            transform: translate3d(57vw, -112vh, 0);
  }
}
@keyframes move-frames-41 {
  from {
    -webkit-transform: translate3d(15vw, 108vh, 0);
            transform: translate3d(15vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -112vh, 0);
            transform: translate3d(57vw, -112vh, 0);
  }
}
.circle-container:nth-child(41) .circle {
  -webkit-animation-delay: 3254ms;
          animation-delay: 3254ms;
}
.circle-container:nth-child(42) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-42;
          animation-name: move-frames-42;
  -webkit-animation-duration: 36563ms;
          animation-duration: 36563ms;
  -webkit-animation-delay: 19533ms;
          animation-delay: 19533ms;
}
@-webkit-keyframes move-frames-42 {
  from {
    -webkit-transform: translate3d(87vw, 105vh, 0);
            transform: translate3d(87vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -127vh, 0);
            transform: translate3d(11vw, -127vh, 0);
  }
}
@keyframes move-frames-42 {
  from {
    -webkit-transform: translate3d(87vw, 105vh, 0);
            transform: translate3d(87vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -127vh, 0);
            transform: translate3d(11vw, -127vh, 0);
  }
}
.circle-container:nth-child(42) .circle {
  -webkit-animation-delay: 3822ms;
          animation-delay: 3822ms;
}
.circle-container:nth-child(43) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-43;
          animation-name: move-frames-43;
  -webkit-animation-duration: 30888ms;
          animation-duration: 30888ms;
  -webkit-animation-delay: 16698ms;
          animation-delay: 16698ms;
}
@-webkit-keyframes move-frames-43 {
  from {
    -webkit-transform: translate3d(94vw, 106vh, 0);
            transform: translate3d(94vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -110vh, 0);
            transform: translate3d(77vw, -110vh, 0);
  }
}
@keyframes move-frames-43 {
  from {
    -webkit-transform: translate3d(94vw, 106vh, 0);
            transform: translate3d(94vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -110vh, 0);
            transform: translate3d(77vw, -110vh, 0);
  }
}
.circle-container:nth-child(43) .circle {
  -webkit-animation-delay: 1582ms;
          animation-delay: 1582ms;
}
.circle-container:nth-child(44) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-44;
          animation-name: move-frames-44;
  -webkit-animation-duration: 31246ms;
          animation-duration: 31246ms;
  -webkit-animation-delay: 10609ms;
          animation-delay: 10609ms;
}
@-webkit-keyframes move-frames-44 {
  from {
    -webkit-transform: translate3d(61vw, 109vh, 0);
            transform: translate3d(61vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -124vh, 0);
            transform: translate3d(44vw, -124vh, 0);
  }
}
@keyframes move-frames-44 {
  from {
    -webkit-transform: translate3d(61vw, 109vh, 0);
            transform: translate3d(61vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -124vh, 0);
            transform: translate3d(44vw, -124vh, 0);
  }
}
.circle-container:nth-child(44) .circle {
  -webkit-animation-delay: 1315ms;
          animation-delay: 1315ms;
}
.circle-container:nth-child(45) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-45;
          animation-name: move-frames-45;
  -webkit-animation-duration: 35488ms;
          animation-duration: 35488ms;
  -webkit-animation-delay: 1138ms;
          animation-delay: 1138ms;
}
@-webkit-keyframes move-frames-45 {
  from {
    -webkit-transform: translate3d(14vw, 109vh, 0);
            transform: translate3d(14vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -118vh, 0);
            transform: translate3d(62vw, -118vh, 0);
  }
}
@keyframes move-frames-45 {
  from {
    -webkit-transform: translate3d(14vw, 109vh, 0);
            transform: translate3d(14vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -118vh, 0);
            transform: translate3d(62vw, -118vh, 0);
  }
}
.circle-container:nth-child(45) .circle {
  -webkit-animation-delay: 883ms;
          animation-delay: 883ms;
}
.circle-container:nth-child(46) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-46;
          animation-name: move-frames-46;
  -webkit-animation-duration: 28812ms;
          animation-duration: 28812ms;
  -webkit-animation-delay: 258ms;
          animation-delay: 258ms;
}
@-webkit-keyframes move-frames-46 {
  from {
    -webkit-transform: translate3d(66vw, 101vh, 0);
            transform: translate3d(66vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -107vh, 0);
            transform: translate3d(16vw, -107vh, 0);
  }
}
@keyframes move-frames-46 {
  from {
    -webkit-transform: translate3d(66vw, 101vh, 0);
            transform: translate3d(66vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -107vh, 0);
            transform: translate3d(16vw, -107vh, 0);
  }
}
.circle-container:nth-child(46) .circle {
  -webkit-animation-delay: 1591ms;
          animation-delay: 1591ms;
}
.circle-container:nth-child(47) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-47;
          animation-name: move-frames-47;
  -webkit-animation-duration: 32357ms;
          animation-duration: 32357ms;
  -webkit-animation-delay: 30367ms;
          animation-delay: 30367ms;
}
@-webkit-keyframes move-frames-47 {
  from {
    -webkit-transform: translate3d(29vw, 102vh, 0);
            transform: translate3d(29vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(1vw, -119vh, 0);
            transform: translate3d(1vw, -119vh, 0);
  }
}
@keyframes move-frames-47 {
  from {
    -webkit-transform: translate3d(29vw, 102vh, 0);
            transform: translate3d(29vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(1vw, -119vh, 0);
            transform: translate3d(1vw, -119vh, 0);
  }
}
.circle-container:nth-child(47) .circle {
  -webkit-animation-delay: 3548ms;
          animation-delay: 3548ms;
}
.circle-container:nth-child(48) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-48;
          animation-name: move-frames-48;
  -webkit-animation-duration: 28374ms;
          animation-duration: 28374ms;
  -webkit-animation-delay: 19276ms;
          animation-delay: 19276ms;
}
@-webkit-keyframes move-frames-48 {
  from {
    -webkit-transform: translate3d(72vw, 105vh, 0);
            transform: translate3d(72vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -127vh, 0);
            transform: translate3d(55vw, -127vh, 0);
  }
}
@keyframes move-frames-48 {
  from {
    -webkit-transform: translate3d(72vw, 105vh, 0);
            transform: translate3d(72vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -127vh, 0);
            transform: translate3d(55vw, -127vh, 0);
  }
}
.circle-container:nth-child(48) .circle {
  -webkit-animation-delay: 871ms;
          animation-delay: 871ms;
}
.circle-container:nth-child(49) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-49;
          animation-name: move-frames-49;
  -webkit-animation-duration: 33036ms;
          animation-duration: 33036ms;
  -webkit-animation-delay: 8361ms;
          animation-delay: 8361ms;
}
@-webkit-keyframes move-frames-49 {
  from {
    -webkit-transform: translate3d(55vw, 101vh, 0);
            transform: translate3d(55vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -128vh, 0);
            transform: translate3d(2vw, -128vh, 0);
  }
}
@keyframes move-frames-49 {
  from {
    -webkit-transform: translate3d(55vw, 101vh, 0);
            transform: translate3d(55vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -128vh, 0);
            transform: translate3d(2vw, -128vh, 0);
  }
}
.circle-container:nth-child(49) .circle {
  -webkit-animation-delay: 3405ms;
          animation-delay: 3405ms;
}
.circle-container:nth-child(50) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-50;
          animation-name: move-frames-50;
  -webkit-animation-duration: 33658ms;
          animation-duration: 33658ms;
  -webkit-animation-delay: 29706ms;
          animation-delay: 29706ms;
}
@-webkit-keyframes move-frames-50 {
  from {
    -webkit-transform: translate3d(96vw, 102vh, 0);
            transform: translate3d(96vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -109vh, 0);
            transform: translate3d(98vw, -109vh, 0);
  }
}
@keyframes move-frames-50 {
  from {
    -webkit-transform: translate3d(96vw, 102vh, 0);
            transform: translate3d(96vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -109vh, 0);
            transform: translate3d(98vw, -109vh, 0);
  }
}
.circle-container:nth-child(50) .circle {
  -webkit-animation-delay: 2560ms;
          animation-delay: 2560ms;
}
.circle-container:nth-child(51) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-51;
          animation-name: move-frames-51;
  -webkit-animation-duration: 29057ms;
          animation-duration: 29057ms;
  -webkit-animation-delay: 21352ms;
          animation-delay: 21352ms;
}
@-webkit-keyframes move-frames-51 {
  from {
    -webkit-transform: translate3d(23vw, 109vh, 0);
            transform: translate3d(23vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -119vh, 0);
            transform: translate3d(39vw, -119vh, 0);
  }
}
@keyframes move-frames-51 {
  from {
    -webkit-transform: translate3d(23vw, 109vh, 0);
            transform: translate3d(23vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -119vh, 0);
            transform: translate3d(39vw, -119vh, 0);
  }
}
.circle-container:nth-child(51) .circle {
  -webkit-animation-delay: 2211ms;
          animation-delay: 2211ms;
}
.circle-container:nth-child(52) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-52;
          animation-name: move-frames-52;
  -webkit-animation-duration: 35218ms;
          animation-duration: 35218ms;
  -webkit-animation-delay: 17255ms;
          animation-delay: 17255ms;
}
@-webkit-keyframes move-frames-52 {
  from {
    -webkit-transform: translate3d(46vw, 102vh, 0);
            transform: translate3d(46vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(63vw, -122vh, 0);
            transform: translate3d(63vw, -122vh, 0);
  }
}
@keyframes move-frames-52 {
  from {
    -webkit-transform: translate3d(46vw, 102vh, 0);
            transform: translate3d(46vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(63vw, -122vh, 0);
            transform: translate3d(63vw, -122vh, 0);
  }
}
.circle-container:nth-child(52) .circle {
  -webkit-animation-delay: 3789ms;
          animation-delay: 3789ms;
}
.circle-container:nth-child(53) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-53;
          animation-name: move-frames-53;
  -webkit-animation-duration: 36548ms;
          animation-duration: 36548ms;
  -webkit-animation-delay: 2257ms;
          animation-delay: 2257ms;
}
@-webkit-keyframes move-frames-53 {
  from {
    -webkit-transform: translate3d(81vw, 102vh, 0);
            transform: translate3d(81vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -128vh, 0);
            transform: translate3d(11vw, -128vh, 0);
  }
}
@keyframes move-frames-53 {
  from {
    -webkit-transform: translate3d(81vw, 102vh, 0);
            transform: translate3d(81vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -128vh, 0);
            transform: translate3d(11vw, -128vh, 0);
  }
}
.circle-container:nth-child(53) .circle {
  -webkit-animation-delay: 3041ms;
          animation-delay: 3041ms;
}
.circle-container:nth-child(54) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-54;
          animation-name: move-frames-54;
  -webkit-animation-duration: 35643ms;
          animation-duration: 35643ms;
  -webkit-animation-delay: 2769ms;
          animation-delay: 2769ms;
}
@-webkit-keyframes move-frames-54 {
  from {
    -webkit-transform: translate3d(85vw, 105vh, 0);
            transform: translate3d(85vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -117vh, 0);
            transform: translate3d(74vw, -117vh, 0);
  }
}
@keyframes move-frames-54 {
  from {
    -webkit-transform: translate3d(85vw, 105vh, 0);
            transform: translate3d(85vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -117vh, 0);
            transform: translate3d(74vw, -117vh, 0);
  }
}
.circle-container:nth-child(54) .circle {
  -webkit-animation-delay: 2068ms;
          animation-delay: 2068ms;
}
.circle-container:nth-child(55) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-55;
          animation-name: move-frames-55;
  -webkit-animation-duration: 32496ms;
          animation-duration: 32496ms;
  -webkit-animation-delay: 12405ms;
          animation-delay: 12405ms;
}
@-webkit-keyframes move-frames-55 {
  from {
    -webkit-transform: translate3d(14vw, 110vh, 0);
            transform: translate3d(14vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(25vw, -112vh, 0);
            transform: translate3d(25vw, -112vh, 0);
  }
}
@keyframes move-frames-55 {
  from {
    -webkit-transform: translate3d(14vw, 110vh, 0);
            transform: translate3d(14vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(25vw, -112vh, 0);
            transform: translate3d(25vw, -112vh, 0);
  }
}
.circle-container:nth-child(55) .circle {
  -webkit-animation-delay: 3097ms;
          animation-delay: 3097ms;
}
.circle-container:nth-child(56) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-56;
          animation-name: move-frames-56;
  -webkit-animation-duration: 28233ms;
          animation-duration: 28233ms;
  -webkit-animation-delay: 22377ms;
          animation-delay: 22377ms;
}
@-webkit-keyframes move-frames-56 {
  from {
    -webkit-transform: translate3d(44vw, 110vh, 0);
            transform: translate3d(44vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(10vw, -127vh, 0);
            transform: translate3d(10vw, -127vh, 0);
  }
}
@keyframes move-frames-56 {
  from {
    -webkit-transform: translate3d(44vw, 110vh, 0);
            transform: translate3d(44vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(10vw, -127vh, 0);
            transform: translate3d(10vw, -127vh, 0);
  }
}
.circle-container:nth-child(56) .circle {
  -webkit-animation-delay: 269ms;
          animation-delay: 269ms;
}
.circle-container:nth-child(57) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-57;
          animation-name: move-frames-57;
  -webkit-animation-duration: 33909ms;
          animation-duration: 33909ms;
  -webkit-animation-delay: 26518ms;
          animation-delay: 26518ms;
}
@-webkit-keyframes move-frames-57 {
  from {
    -webkit-transform: translate3d(2vw, 103vh, 0);
            transform: translate3d(2vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -126vh, 0);
            transform: translate3d(53vw, -126vh, 0);
  }
}
@keyframes move-frames-57 {
  from {
    -webkit-transform: translate3d(2vw, 103vh, 0);
            transform: translate3d(2vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -126vh, 0);
            transform: translate3d(53vw, -126vh, 0);
  }
}
.circle-container:nth-child(57) .circle {
  -webkit-animation-delay: 3949ms;
          animation-delay: 3949ms;
}
.circle-container:nth-child(58) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-58;
          animation-name: move-frames-58;
  -webkit-animation-duration: 32809ms;
          animation-duration: 32809ms;
  -webkit-animation-delay: 10585ms;
          animation-delay: 10585ms;
}
@-webkit-keyframes move-frames-58 {
  from {
    -webkit-transform: translate3d(16vw, 110vh, 0);
            transform: translate3d(16vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -137vh, 0);
            transform: translate3d(47vw, -137vh, 0);
  }
}
@keyframes move-frames-58 {
  from {
    -webkit-transform: translate3d(16vw, 110vh, 0);
            transform: translate3d(16vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -137vh, 0);
            transform: translate3d(47vw, -137vh, 0);
  }
}
.circle-container:nth-child(58) .circle {
  -webkit-animation-delay: 2940ms;
          animation-delay: 2940ms;
}
.circle-container:nth-child(59) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-59;
          animation-name: move-frames-59;
  -webkit-animation-duration: 32268ms;
          animation-duration: 32268ms;
  -webkit-animation-delay: 11749ms;
          animation-delay: 11749ms;
}
@-webkit-keyframes move-frames-59 {
  from {
    -webkit-transform: translate3d(10vw, 103vh, 0);
            transform: translate3d(10vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -120vh, 0);
            transform: translate3d(35vw, -120vh, 0);
  }
}
@keyframes move-frames-59 {
  from {
    -webkit-transform: translate3d(10vw, 103vh, 0);
            transform: translate3d(10vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -120vh, 0);
            transform: translate3d(35vw, -120vh, 0);
  }
}
.circle-container:nth-child(59) .circle {
  -webkit-animation-delay: 1101ms;
          animation-delay: 1101ms;
}
.circle-container:nth-child(60) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-60;
          animation-name: move-frames-60;
  -webkit-animation-duration: 32971ms;
          animation-duration: 32971ms;
  -webkit-animation-delay: 20136ms;
          animation-delay: 20136ms;
}
@-webkit-keyframes move-frames-60 {
  from {
    -webkit-transform: translate3d(30vw, 103vh, 0);
            transform: translate3d(30vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(75vw, -112vh, 0);
            transform: translate3d(75vw, -112vh, 0);
  }
}
@keyframes move-frames-60 {
  from {
    -webkit-transform: translate3d(30vw, 103vh, 0);
            transform: translate3d(30vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(75vw, -112vh, 0);
            transform: translate3d(75vw, -112vh, 0);
  }
}
.circle-container:nth-child(60) .circle {
  -webkit-animation-delay: 4ms;
          animation-delay: 4ms;
}
.circle-container:nth-child(61) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-61;
          animation-name: move-frames-61;
  -webkit-animation-duration: 35127ms;
          animation-duration: 35127ms;
  -webkit-animation-delay: 36792ms;
          animation-delay: 36792ms;
}
@-webkit-keyframes move-frames-61 {
  from {
    -webkit-transform: translate3d(35vw, 108vh, 0);
            transform: translate3d(35vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -109vh, 0);
            transform: translate3d(14vw, -109vh, 0);
  }
}
@keyframes move-frames-61 {
  from {
    -webkit-transform: translate3d(35vw, 108vh, 0);
            transform: translate3d(35vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -109vh, 0);
            transform: translate3d(14vw, -109vh, 0);
  }
}
.circle-container:nth-child(61) .circle {
  -webkit-animation-delay: 3024ms;
          animation-delay: 3024ms;
}
.circle-container:nth-child(62) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-62;
          animation-name: move-frames-62;
  -webkit-animation-duration: 28774ms;
          animation-duration: 28774ms;
  -webkit-animation-delay: 35318ms;
          animation-delay: 35318ms;
}
@-webkit-keyframes move-frames-62 {
  from {
    -webkit-transform: translate3d(46vw, 103vh, 0);
            transform: translate3d(46vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -130vh, 0);
            transform: translate3d(13vw, -130vh, 0);
  }
}
@keyframes move-frames-62 {
  from {
    -webkit-transform: translate3d(46vw, 103vh, 0);
            transform: translate3d(46vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -130vh, 0);
            transform: translate3d(13vw, -130vh, 0);
  }
}
.circle-container:nth-child(62) .circle {
  -webkit-animation-delay: 922ms;
          animation-delay: 922ms;
}
.circle-container:nth-child(63) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-63;
          animation-name: move-frames-63;
  -webkit-animation-duration: 33521ms;
          animation-duration: 33521ms;
  -webkit-animation-delay: 32413ms;
          animation-delay: 32413ms;
}
@-webkit-keyframes move-frames-63 {
  from {
    -webkit-transform: translate3d(4vw, 105vh, 0);
            transform: translate3d(4vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -115vh, 0);
            transform: translate3d(51vw, -115vh, 0);
  }
}
@keyframes move-frames-63 {
  from {
    -webkit-transform: translate3d(4vw, 105vh, 0);
            transform: translate3d(4vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -115vh, 0);
            transform: translate3d(51vw, -115vh, 0);
  }
}
.circle-container:nth-child(63) .circle {
  -webkit-animation-delay: 907ms;
          animation-delay: 907ms;
}
.circle-container:nth-child(64) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-64;
          animation-name: move-frames-64;
  -webkit-animation-duration: 34983ms;
          animation-duration: 34983ms;
  -webkit-animation-delay: 4412ms;
          animation-delay: 4412ms;
}
@-webkit-keyframes move-frames-64 {
  from {
    -webkit-transform: translate3d(69vw, 104vh, 0);
            transform: translate3d(69vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -127vh, 0);
            transform: translate3d(12vw, -127vh, 0);
  }
}
@keyframes move-frames-64 {
  from {
    -webkit-transform: translate3d(69vw, 104vh, 0);
            transform: translate3d(69vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -127vh, 0);
            transform: translate3d(12vw, -127vh, 0);
  }
}
.circle-container:nth-child(64) .circle {
  -webkit-animation-delay: 3090ms;
          animation-delay: 3090ms;
}
.circle-container:nth-child(65) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-65;
          animation-name: move-frames-65;
  -webkit-animation-duration: 32005ms;
          animation-duration: 32005ms;
  -webkit-animation-delay: 13881ms;
          animation-delay: 13881ms;
}
@-webkit-keyframes move-frames-65 {
  from {
    -webkit-transform: translate3d(13vw, 101vh, 0);
            transform: translate3d(13vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -123vh, 0);
            transform: translate3d(100vw, -123vh, 0);
  }
}
@keyframes move-frames-65 {
  from {
    -webkit-transform: translate3d(13vw, 101vh, 0);
            transform: translate3d(13vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -123vh, 0);
            transform: translate3d(100vw, -123vh, 0);
  }
}
.circle-container:nth-child(65) .circle {
  -webkit-animation-delay: 1172ms;
          animation-delay: 1172ms;
}
.circle-container:nth-child(66) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-66;
          animation-name: move-frames-66;
  -webkit-animation-duration: 36898ms;
          animation-duration: 36898ms;
  -webkit-animation-delay: 33362ms;
          animation-delay: 33362ms;
}
@-webkit-keyframes move-frames-66 {
  from {
    -webkit-transform: translate3d(32vw, 105vh, 0);
            transform: translate3d(32vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(76vw, -119vh, 0);
            transform: translate3d(76vw, -119vh, 0);
  }
}
@keyframes move-frames-66 {
  from {
    -webkit-transform: translate3d(32vw, 105vh, 0);
            transform: translate3d(32vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(76vw, -119vh, 0);
            transform: translate3d(76vw, -119vh, 0);
  }
}
.circle-container:nth-child(66) .circle {
  -webkit-animation-delay: 190ms;
          animation-delay: 190ms;
}
.circle-container:nth-child(67) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-67;
          animation-name: move-frames-67;
  -webkit-animation-duration: 32319ms;
          animation-duration: 32319ms;
  -webkit-animation-delay: 28475ms;
          animation-delay: 28475ms;
}
@-webkit-keyframes move-frames-67 {
  from {
    -webkit-transform: translate3d(49vw, 104vh, 0);
            transform: translate3d(49vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -128vh, 0);
            transform: translate3d(28vw, -128vh, 0);
  }
}
@keyframes move-frames-67 {
  from {
    -webkit-transform: translate3d(49vw, 104vh, 0);
            transform: translate3d(49vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -128vh, 0);
            transform: translate3d(28vw, -128vh, 0);
  }
}
.circle-container:nth-child(67) .circle {
  -webkit-animation-delay: 1961ms;
          animation-delay: 1961ms;
}
.circle-container:nth-child(68) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-68;
          animation-name: move-frames-68;
  -webkit-animation-duration: 36945ms;
          animation-duration: 36945ms;
  -webkit-animation-delay: 4173ms;
          animation-delay: 4173ms;
}
@-webkit-keyframes move-frames-68 {
  from {
    -webkit-transform: translate3d(18vw, 105vh, 0);
            transform: translate3d(18vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -128vh, 0);
            transform: translate3d(21vw, -128vh, 0);
  }
}
@keyframes move-frames-68 {
  from {
    -webkit-transform: translate3d(18vw, 105vh, 0);
            transform: translate3d(18vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -128vh, 0);
            transform: translate3d(21vw, -128vh, 0);
  }
}
.circle-container:nth-child(68) .circle {
  -webkit-animation-delay: 3717ms;
          animation-delay: 3717ms;
}
.circle-container:nth-child(69) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-69;
          animation-name: move-frames-69;
  -webkit-animation-duration: 28704ms;
          animation-duration: 28704ms;
  -webkit-animation-delay: 31120ms;
          animation-delay: 31120ms;
}
@-webkit-keyframes move-frames-69 {
  from {
    -webkit-transform: translate3d(69vw, 106vh, 0);
            transform: translate3d(69vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(63vw, -109vh, 0);
            transform: translate3d(63vw, -109vh, 0);
  }
}
@keyframes move-frames-69 {
  from {
    -webkit-transform: translate3d(69vw, 106vh, 0);
            transform: translate3d(69vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(63vw, -109vh, 0);
            transform: translate3d(63vw, -109vh, 0);
  }
}
.circle-container:nth-child(69) .circle {
  -webkit-animation-delay: 1603ms;
          animation-delay: 1603ms;
}
.circle-container:nth-child(70) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-70;
          animation-name: move-frames-70;
  -webkit-animation-duration: 35103ms;
          animation-duration: 35103ms;
  -webkit-animation-delay: 26501ms;
          animation-delay: 26501ms;
}
@-webkit-keyframes move-frames-70 {
  from {
    -webkit-transform: translate3d(43vw, 101vh, 0);
            transform: translate3d(43vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -122vh, 0);
            transform: translate3d(94vw, -122vh, 0);
  }
}
@keyframes move-frames-70 {
  from {
    -webkit-transform: translate3d(43vw, 101vh, 0);
            transform: translate3d(43vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -122vh, 0);
            transform: translate3d(94vw, -122vh, 0);
  }
}
.circle-container:nth-child(70) .circle {
  -webkit-animation-delay: 572ms;
          animation-delay: 572ms;
}
.circle-container:nth-child(71) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-71;
          animation-name: move-frames-71;
  -webkit-animation-duration: 36015ms;
          animation-duration: 36015ms;
  -webkit-animation-delay: 15838ms;
          animation-delay: 15838ms;
}
@-webkit-keyframes move-frames-71 {
  from {
    -webkit-transform: translate3d(59vw, 105vh, 0);
            transform: translate3d(59vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -135vh, 0);
            transform: translate3d(20vw, -135vh, 0);
  }
}
@keyframes move-frames-71 {
  from {
    -webkit-transform: translate3d(59vw, 105vh, 0);
            transform: translate3d(59vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -135vh, 0);
            transform: translate3d(20vw, -135vh, 0);
  }
}
.circle-container:nth-child(71) .circle {
  -webkit-animation-delay: 2063ms;
          animation-delay: 2063ms;
}
.circle-container:nth-child(72) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-72;
          animation-name: move-frames-72;
  -webkit-animation-duration: 31242ms;
          animation-duration: 31242ms;
  -webkit-animation-delay: 2721ms;
          animation-delay: 2721ms;
}
@-webkit-keyframes move-frames-72 {
  from {
    -webkit-transform: translate3d(97vw, 107vh, 0);
            transform: translate3d(97vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -125vh, 0);
            transform: translate3d(44vw, -125vh, 0);
  }
}
@keyframes move-frames-72 {
  from {
    -webkit-transform: translate3d(97vw, 107vh, 0);
            transform: translate3d(97vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -125vh, 0);
            transform: translate3d(44vw, -125vh, 0);
  }
}
.circle-container:nth-child(72) .circle {
  -webkit-animation-delay: 2932ms;
          animation-delay: 2932ms;
}
.circle-container:nth-child(73) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-73;
          animation-name: move-frames-73;
  -webkit-animation-duration: 32718ms;
          animation-duration: 32718ms;
  -webkit-animation-delay: 13151ms;
          animation-delay: 13151ms;
}
@-webkit-keyframes move-frames-73 {
  from {
    -webkit-transform: translate3d(52vw, 101vh, 0);
            transform: translate3d(52vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -116vh, 0);
            transform: translate3d(44vw, -116vh, 0);
  }
}
@keyframes move-frames-73 {
  from {
    -webkit-transform: translate3d(52vw, 101vh, 0);
            transform: translate3d(52vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -116vh, 0);
            transform: translate3d(44vw, -116vh, 0);
  }
}
.circle-container:nth-child(73) .circle {
  -webkit-animation-delay: 1816ms;
          animation-delay: 1816ms;
}
.circle-container:nth-child(74) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-74;
          animation-name: move-frames-74;
  -webkit-animation-duration: 34425ms;
          animation-duration: 34425ms;
  -webkit-animation-delay: 19847ms;
          animation-delay: 19847ms;
}
@-webkit-keyframes move-frames-74 {
  from {
    -webkit-transform: translate3d(57vw, 103vh, 0);
            transform: translate3d(57vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -124vh, 0);
            transform: translate3d(45vw, -124vh, 0);
  }
}
@keyframes move-frames-74 {
  from {
    -webkit-transform: translate3d(57vw, 103vh, 0);
            transform: translate3d(57vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -124vh, 0);
            transform: translate3d(45vw, -124vh, 0);
  }
}
.circle-container:nth-child(74) .circle {
  -webkit-animation-delay: 262ms;
          animation-delay: 262ms;
}
.circle-container:nth-child(75) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-75;
          animation-name: move-frames-75;
  -webkit-animation-duration: 33424ms;
          animation-duration: 33424ms;
  -webkit-animation-delay: 6698ms;
          animation-delay: 6698ms;
}
@-webkit-keyframes move-frames-75 {
  from {
    -webkit-transform: translate3d(12vw, 110vh, 0);
            transform: translate3d(12vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(4vw, -133vh, 0);
            transform: translate3d(4vw, -133vh, 0);
  }
}
@keyframes move-frames-75 {
  from {
    -webkit-transform: translate3d(12vw, 110vh, 0);
            transform: translate3d(12vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(4vw, -133vh, 0);
            transform: translate3d(4vw, -133vh, 0);
  }
}
.circle-container:nth-child(75) .circle {
  -webkit-animation-delay: 533ms;
          animation-delay: 533ms;
}
.circle-container:nth-child(76) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-76;
          animation-name: move-frames-76;
  -webkit-animation-duration: 29996ms;
          animation-duration: 29996ms;
  -webkit-animation-delay: 26300ms;
          animation-delay: 26300ms;
}
@-webkit-keyframes move-frames-76 {
  from {
    -webkit-transform: translate3d(97vw, 104vh, 0);
            transform: translate3d(97vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -132vh, 0);
            transform: translate3d(91vw, -132vh, 0);
  }
}
@keyframes move-frames-76 {
  from {
    -webkit-transform: translate3d(97vw, 104vh, 0);
            transform: translate3d(97vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -132vh, 0);
            transform: translate3d(91vw, -132vh, 0);
  }
}
.circle-container:nth-child(76) .circle {
  -webkit-animation-delay: 96ms;
          animation-delay: 96ms;
}
.circle-container:nth-child(77) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-77;
          animation-name: move-frames-77;
  -webkit-animation-duration: 31191ms;
          animation-duration: 31191ms;
  -webkit-animation-delay: 12285ms;
          animation-delay: 12285ms;
}
@-webkit-keyframes move-frames-77 {
  from {
    -webkit-transform: translate3d(59vw, 103vh, 0);
            transform: translate3d(59vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(96vw, -132vh, 0);
            transform: translate3d(96vw, -132vh, 0);
  }
}
@keyframes move-frames-77 {
  from {
    -webkit-transform: translate3d(59vw, 103vh, 0);
            transform: translate3d(59vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(96vw, -132vh, 0);
            transform: translate3d(96vw, -132vh, 0);
  }
}
.circle-container:nth-child(77) .circle {
  -webkit-animation-delay: 2253ms;
          animation-delay: 2253ms;
}
.circle-container:nth-child(78) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-78;
          animation-name: move-frames-78;
  -webkit-animation-duration: 35432ms;
          animation-duration: 35432ms;
  -webkit-animation-delay: 592ms;
          animation-delay: 592ms;
}
@-webkit-keyframes move-frames-78 {
  from {
    -webkit-transform: translate3d(94vw, 103vh, 0);
            transform: translate3d(94vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -123vh, 0);
            transform: translate3d(41vw, -123vh, 0);
  }
}
@keyframes move-frames-78 {
  from {
    -webkit-transform: translate3d(94vw, 103vh, 0);
            transform: translate3d(94vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -123vh, 0);
            transform: translate3d(41vw, -123vh, 0);
  }
}
.circle-container:nth-child(78) .circle {
  -webkit-animation-delay: 446ms;
          animation-delay: 446ms;
}
.circle-container:nth-child(79) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-79;
          animation-name: move-frames-79;
  -webkit-animation-duration: 35884ms;
          animation-duration: 35884ms;
  -webkit-animation-delay: 21626ms;
          animation-delay: 21626ms;
}
@-webkit-keyframes move-frames-79 {
  from {
    -webkit-transform: translate3d(99vw, 105vh, 0);
            transform: translate3d(99vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -133vh, 0);
            transform: translate3d(19vw, -133vh, 0);
  }
}
@keyframes move-frames-79 {
  from {
    -webkit-transform: translate3d(99vw, 105vh, 0);
            transform: translate3d(99vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -133vh, 0);
            transform: translate3d(19vw, -133vh, 0);
  }
}
.circle-container:nth-child(79) .circle {
  -webkit-animation-delay: 767ms;
          animation-delay: 767ms;
}
.circle-container:nth-child(80) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-80;
          animation-name: move-frames-80;
  -webkit-animation-duration: 31148ms;
          animation-duration: 31148ms;
  -webkit-animation-delay: 1365ms;
          animation-delay: 1365ms;
}
@-webkit-keyframes move-frames-80 {
  from {
    -webkit-transform: translate3d(70vw, 107vh, 0);
            transform: translate3d(70vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(68vw, -109vh, 0);
            transform: translate3d(68vw, -109vh, 0);
  }
}
@keyframes move-frames-80 {
  from {
    -webkit-transform: translate3d(70vw, 107vh, 0);
            transform: translate3d(70vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(68vw, -109vh, 0);
            transform: translate3d(68vw, -109vh, 0);
  }
}
.circle-container:nth-child(80) .circle {
  -webkit-animation-delay: 2871ms;
          animation-delay: 2871ms;
}
.circle-container:nth-child(81) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-81;
          animation-name: move-frames-81;
  -webkit-animation-duration: 32788ms;
          animation-duration: 32788ms;
  -webkit-animation-delay: 36006ms;
          animation-delay: 36006ms;
}
@-webkit-keyframes move-frames-81 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -123vh, 0);
            transform: translate3d(21vw, -123vh, 0);
  }
}
@keyframes move-frames-81 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -123vh, 0);
            transform: translate3d(21vw, -123vh, 0);
  }
}
.circle-container:nth-child(81) .circle {
  -webkit-animation-delay: 459ms;
          animation-delay: 459ms;
}
.circle-container:nth-child(82) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-82;
          animation-name: move-frames-82;
  -webkit-animation-duration: 35034ms;
          animation-duration: 35034ms;
  -webkit-animation-delay: 18933ms;
          animation-delay: 18933ms;
}
@-webkit-keyframes move-frames-82 {
  from {
    -webkit-transform: translate3d(19vw, 101vh, 0);
            transform: translate3d(19vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(27vw, -116vh, 0);
            transform: translate3d(27vw, -116vh, 0);
  }
}
@keyframes move-frames-82 {
  from {
    -webkit-transform: translate3d(19vw, 101vh, 0);
            transform: translate3d(19vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(27vw, -116vh, 0);
            transform: translate3d(27vw, -116vh, 0);
  }
}
.circle-container:nth-child(82) .circle {
  -webkit-animation-delay: 890ms;
          animation-delay: 890ms;
}
.circle-container:nth-child(83) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-83;
          animation-name: move-frames-83;
  -webkit-animation-duration: 36087ms;
          animation-duration: 36087ms;
  -webkit-animation-delay: 16924ms;
          animation-delay: 16924ms;
}
@-webkit-keyframes move-frames-83 {
  from {
    -webkit-transform: translate3d(21vw, 108vh, 0);
            transform: translate3d(21vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -116vh, 0);
            transform: translate3d(5vw, -116vh, 0);
  }
}
@keyframes move-frames-83 {
  from {
    -webkit-transform: translate3d(21vw, 108vh, 0);
            transform: translate3d(21vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -116vh, 0);
            transform: translate3d(5vw, -116vh, 0);
  }
}
.circle-container:nth-child(83) .circle {
  -webkit-animation-delay: 64ms;
          animation-delay: 64ms;
}
.circle-container:nth-child(84) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-84;
          animation-name: move-frames-84;
  -webkit-animation-duration: 33391ms;
          animation-duration: 33391ms;
  -webkit-animation-delay: 33879ms;
          animation-delay: 33879ms;
}
@-webkit-keyframes move-frames-84 {
  from {
    -webkit-transform: translate3d(90vw, 104vh, 0);
            transform: translate3d(90vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -115vh, 0);
            transform: translate3d(26vw, -115vh, 0);
  }
}
@keyframes move-frames-84 {
  from {
    -webkit-transform: translate3d(90vw, 104vh, 0);
            transform: translate3d(90vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -115vh, 0);
            transform: translate3d(26vw, -115vh, 0);
  }
}
.circle-container:nth-child(84) .circle {
  -webkit-animation-delay: 2929ms;
          animation-delay: 2929ms;
}
.circle-container:nth-child(85) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-85;
          animation-name: move-frames-85;
  -webkit-animation-duration: 35480ms;
          animation-duration: 35480ms;
  -webkit-animation-delay: 33775ms;
          animation-delay: 33775ms;
}
@-webkit-keyframes move-frames-85 {
  from {
    -webkit-transform: translate3d(68vw, 106vh, 0);
            transform: translate3d(68vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -109vh, 0);
            transform: translate3d(12vw, -109vh, 0);
  }
}
@keyframes move-frames-85 {
  from {
    -webkit-transform: translate3d(68vw, 106vh, 0);
            transform: translate3d(68vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -109vh, 0);
            transform: translate3d(12vw, -109vh, 0);
  }
}
.circle-container:nth-child(85) .circle {
  -webkit-animation-delay: 1298ms;
          animation-delay: 1298ms;
}
.circle-container:nth-child(86) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-86;
          animation-name: move-frames-86;
  -webkit-animation-duration: 33017ms;
          animation-duration: 33017ms;
  -webkit-animation-delay: 13590ms;
          animation-delay: 13590ms;
}
@-webkit-keyframes move-frames-86 {
  from {
    -webkit-transform: translate3d(13vw, 104vh, 0);
            transform: translate3d(13vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -133vh, 0);
            transform: translate3d(13vw, -133vh, 0);
  }
}
@keyframes move-frames-86 {
  from {
    -webkit-transform: translate3d(13vw, 104vh, 0);
            transform: translate3d(13vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -133vh, 0);
            transform: translate3d(13vw, -133vh, 0);
  }
}
.circle-container:nth-child(86) .circle {
  -webkit-animation-delay: 115ms;
          animation-delay: 115ms;
}
.circle-container:nth-child(87) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-87;
          animation-name: move-frames-87;
  -webkit-animation-duration: 32745ms;
          animation-duration: 32745ms;
  -webkit-animation-delay: 36109ms;
          animation-delay: 36109ms;
}
@-webkit-keyframes move-frames-87 {
  from {
    -webkit-transform: translate3d(74vw, 101vh, 0);
            transform: translate3d(74vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -106vh, 0);
            transform: translate3d(41vw, -106vh, 0);
  }
}
@keyframes move-frames-87 {
  from {
    -webkit-transform: translate3d(74vw, 101vh, 0);
            transform: translate3d(74vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -106vh, 0);
            transform: translate3d(41vw, -106vh, 0);
  }
}
.circle-container:nth-child(87) .circle {
  -webkit-animation-delay: 422ms;
          animation-delay: 422ms;
}
.circle-container:nth-child(88) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-88;
          animation-name: move-frames-88;
  -webkit-animation-duration: 35401ms;
          animation-duration: 35401ms;
  -webkit-animation-delay: 20247ms;
          animation-delay: 20247ms;
}
@-webkit-keyframes move-frames-88 {
  from {
    -webkit-transform: translate3d(24vw, 109vh, 0);
            transform: translate3d(24vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -122vh, 0);
            transform: translate3d(26vw, -122vh, 0);
  }
}
@keyframes move-frames-88 {
  from {
    -webkit-transform: translate3d(24vw, 109vh, 0);
            transform: translate3d(24vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -122vh, 0);
            transform: translate3d(26vw, -122vh, 0);
  }
}
.circle-container:nth-child(88) .circle {
  -webkit-animation-delay: 1868ms;
          animation-delay: 1868ms;
}
.circle-container:nth-child(89) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-89;
          animation-name: move-frames-89;
  -webkit-animation-duration: 35957ms;
          animation-duration: 35957ms;
  -webkit-animation-delay: 33781ms;
          animation-delay: 33781ms;
}
@-webkit-keyframes move-frames-89 {
  from {
    -webkit-transform: translate3d(73vw, 108vh, 0);
            transform: translate3d(73vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -130vh, 0);
            transform: translate3d(80vw, -130vh, 0);
  }
}
@keyframes move-frames-89 {
  from {
    -webkit-transform: translate3d(73vw, 108vh, 0);
            transform: translate3d(73vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -130vh, 0);
            transform: translate3d(80vw, -130vh, 0);
  }
}
.circle-container:nth-child(89) .circle {
  -webkit-animation-delay: 190ms;
          animation-delay: 190ms;
}
.circle-container:nth-child(90) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-90;
          animation-name: move-frames-90;
  -webkit-animation-duration: 36992ms;
          animation-duration: 36992ms;
  -webkit-animation-delay: 15864ms;
          animation-delay: 15864ms;
}
@-webkit-keyframes move-frames-90 {
  from {
    -webkit-transform: translate3d(97vw, 110vh, 0);
            transform: translate3d(97vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -134vh, 0);
            transform: translate3d(81vw, -134vh, 0);
  }
}
@keyframes move-frames-90 {
  from {
    -webkit-transform: translate3d(97vw, 110vh, 0);
            transform: translate3d(97vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -134vh, 0);
            transform: translate3d(81vw, -134vh, 0);
  }
}
.circle-container:nth-child(90) .circle {
  -webkit-animation-delay: 3888ms;
          animation-delay: 3888ms;
}
.circle-container:nth-child(91) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-91;
          animation-name: move-frames-91;
  -webkit-animation-duration: 35554ms;
          animation-duration: 35554ms;
  -webkit-animation-delay: 31017ms;
          animation-delay: 31017ms;
}
@-webkit-keyframes move-frames-91 {
  from {
    -webkit-transform: translate3d(54vw, 107vh, 0);
            transform: translate3d(54vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -111vh, 0);
            transform: translate3d(45vw, -111vh, 0);
  }
}
@keyframes move-frames-91 {
  from {
    -webkit-transform: translate3d(54vw, 107vh, 0);
            transform: translate3d(54vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -111vh, 0);
            transform: translate3d(45vw, -111vh, 0);
  }
}
.circle-container:nth-child(91) .circle {
  -webkit-animation-delay: 3380ms;
          animation-delay: 3380ms;
}
.circle-container:nth-child(92) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-92;
          animation-name: move-frames-92;
  -webkit-animation-duration: 28227ms;
          animation-duration: 28227ms;
  -webkit-animation-delay: 1347ms;
          animation-delay: 1347ms;
}
@-webkit-keyframes move-frames-92 {
  from {
    -webkit-transform: translate3d(25vw, 101vh, 0);
            transform: translate3d(25vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -126vh, 0);
            transform: translate3d(35vw, -126vh, 0);
  }
}
@keyframes move-frames-92 {
  from {
    -webkit-transform: translate3d(25vw, 101vh, 0);
            transform: translate3d(25vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -126vh, 0);
            transform: translate3d(35vw, -126vh, 0);
  }
}
.circle-container:nth-child(92) .circle {
  -webkit-animation-delay: 1360ms;
          animation-delay: 1360ms;
}
.circle-container:nth-child(93) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-93;
          animation-name: move-frames-93;
  -webkit-animation-duration: 29249ms;
          animation-duration: 29249ms;
  -webkit-animation-delay: 30890ms;
          animation-delay: 30890ms;
}
@-webkit-keyframes move-frames-93 {
  from {
    -webkit-transform: translate3d(58vw, 104vh, 0);
            transform: translate3d(58vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -124vh, 0);
            transform: translate3d(38vw, -124vh, 0);
  }
}
@keyframes move-frames-93 {
  from {
    -webkit-transform: translate3d(58vw, 104vh, 0);
            transform: translate3d(58vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -124vh, 0);
            transform: translate3d(38vw, -124vh, 0);
  }
}
.circle-container:nth-child(93) .circle {
  -webkit-animation-delay: 173ms;
          animation-delay: 173ms;
}
.circle-container:nth-child(94) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-94;
          animation-name: move-frames-94;
  -webkit-animation-duration: 28616ms;
          animation-duration: 28616ms;
  -webkit-animation-delay: 15905ms;
          animation-delay: 15905ms;
}
@-webkit-keyframes move-frames-94 {
  from {
    -webkit-transform: translate3d(88vw, 101vh, 0);
            transform: translate3d(88vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(23vw, -115vh, 0);
            transform: translate3d(23vw, -115vh, 0);
  }
}
@keyframes move-frames-94 {
  from {
    -webkit-transform: translate3d(88vw, 101vh, 0);
            transform: translate3d(88vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(23vw, -115vh, 0);
            transform: translate3d(23vw, -115vh, 0);
  }
}
.circle-container:nth-child(94) .circle {
  -webkit-animation-delay: 739ms;
          animation-delay: 739ms;
}
.circle-container:nth-child(95) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-95;
          animation-name: move-frames-95;
  -webkit-animation-duration: 32039ms;
          animation-duration: 32039ms;
  -webkit-animation-delay: 31617ms;
          animation-delay: 31617ms;
}
@-webkit-keyframes move-frames-95 {
  from {
    -webkit-transform: translate3d(89vw, 105vh, 0);
            transform: translate3d(89vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(82vw, -118vh, 0);
            transform: translate3d(82vw, -118vh, 0);
  }
}
@keyframes move-frames-95 {
  from {
    -webkit-transform: translate3d(89vw, 105vh, 0);
            transform: translate3d(89vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(82vw, -118vh, 0);
            transform: translate3d(82vw, -118vh, 0);
  }
}
.circle-container:nth-child(95) .circle {
  -webkit-animation-delay: 3791ms;
          animation-delay: 3791ms;
}
.circle-container:nth-child(96) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-96;
          animation-name: move-frames-96;
  -webkit-animation-duration: 31923ms;
          animation-duration: 31923ms;
  -webkit-animation-delay: 1347ms;
          animation-delay: 1347ms;
}
@-webkit-keyframes move-frames-96 {
  from {
    -webkit-transform: translate3d(83vw, 108vh, 0);
            transform: translate3d(83vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(15vw, -116vh, 0);
            transform: translate3d(15vw, -116vh, 0);
  }
}
@keyframes move-frames-96 {
  from {
    -webkit-transform: translate3d(83vw, 108vh, 0);
            transform: translate3d(83vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(15vw, -116vh, 0);
            transform: translate3d(15vw, -116vh, 0);
  }
}
.circle-container:nth-child(96) .circle {
  -webkit-animation-delay: 1705ms;
          animation-delay: 1705ms;
}
.circle-container:nth-child(97) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-97;
          animation-name: move-frames-97;
  -webkit-animation-duration: 31080ms;
          animation-duration: 31080ms;
  -webkit-animation-delay: 7622ms;
          animation-delay: 7622ms;
}
@-webkit-keyframes move-frames-97 {
  from {
    -webkit-transform: translate3d(71vw, 107vh, 0);
            transform: translate3d(71vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -112vh, 0);
            transform: translate3d(98vw, -112vh, 0);
  }
}
@keyframes move-frames-97 {
  from {
    -webkit-transform: translate3d(71vw, 107vh, 0);
            transform: translate3d(71vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -112vh, 0);
            transform: translate3d(98vw, -112vh, 0);
  }
}
.circle-container:nth-child(97) .circle {
  -webkit-animation-delay: 3020ms;
          animation-delay: 3020ms;
}
.circle-container:nth-child(98) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-98;
          animation-name: move-frames-98;
  -webkit-animation-duration: 29793ms;
          animation-duration: 29793ms;
  -webkit-animation-delay: 32285ms;
          animation-delay: 32285ms;
}
@-webkit-keyframes move-frames-98 {
  from {
    -webkit-transform: translate3d(95vw, 109vh, 0);
            transform: translate3d(95vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -122vh, 0);
            transform: translate3d(20vw, -122vh, 0);
  }
}
@keyframes move-frames-98 {
  from {
    -webkit-transform: translate3d(95vw, 109vh, 0);
            transform: translate3d(95vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -122vh, 0);
            transform: translate3d(20vw, -122vh, 0);
  }
}
.circle-container:nth-child(98) .circle {
  -webkit-animation-delay: 94ms;
          animation-delay: 94ms;
}
.circle-container:nth-child(99) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-99;
          animation-name: move-frames-99;
  -webkit-animation-duration: 35700ms;
          animation-duration: 35700ms;
  -webkit-animation-delay: 11101ms;
          animation-delay: 11101ms;
}
@-webkit-keyframes move-frames-99 {
  from {
    -webkit-transform: translate3d(12vw, 107vh, 0);
            transform: translate3d(12vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -111vh, 0);
            transform: translate3d(5vw, -111vh, 0);
  }
}
@keyframes move-frames-99 {
  from {
    -webkit-transform: translate3d(12vw, 107vh, 0);
            transform: translate3d(12vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -111vh, 0);
            transform: translate3d(5vw, -111vh, 0);
  }
}
.circle-container:nth-child(99) .circle {
  -webkit-animation-delay: 1607ms;
          animation-delay: 1607ms;
}
.circle-container:nth-child(100) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-100;
          animation-name: move-frames-100;
  -webkit-animation-duration: 28198ms;
          animation-duration: 28198ms;
  -webkit-animation-delay: 19571ms;
          animation-delay: 19571ms;
}
@-webkit-keyframes move-frames-100 {
  from {
    -webkit-transform: translate3d(64vw, 109vh, 0);
            transform: translate3d(64vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(75vw, -137vh, 0);
            transform: translate3d(75vw, -137vh, 0);
  }
}
@keyframes move-frames-100 {
  from {
    -webkit-transform: translate3d(64vw, 109vh, 0);
            transform: translate3d(64vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(75vw, -137vh, 0);
            transform: translate3d(75vw, -137vh, 0);
  }
}
.circle-container:nth-child(100) .circle {
  -webkit-animation-delay: 770ms;
          animation-delay: 770ms;
}
.circle-container:nth-child(101) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-101;
          animation-name: move-frames-101;
  -webkit-animation-duration: 35707ms;
          animation-duration: 35707ms;
  -webkit-animation-delay: 24474ms;
          animation-delay: 24474ms;
}
@-webkit-keyframes move-frames-101 {
  from {
    -webkit-transform: translate3d(30vw, 101vh, 0);
            transform: translate3d(30vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -122vh, 0);
            transform: translate3d(41vw, -122vh, 0);
  }
}
@keyframes move-frames-101 {
  from {
    -webkit-transform: translate3d(30vw, 101vh, 0);
            transform: translate3d(30vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -122vh, 0);
            transform: translate3d(41vw, -122vh, 0);
  }
}
.circle-container:nth-child(101) .circle {
  -webkit-animation-delay: 1095ms;
          animation-delay: 1095ms;
}
.circle-container:nth-child(102) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-102;
          animation-name: move-frames-102;
  -webkit-animation-duration: 35082ms;
          animation-duration: 35082ms;
  -webkit-animation-delay: 13150ms;
          animation-delay: 13150ms;
}
@-webkit-keyframes move-frames-102 {
  from {
    -webkit-transform: translate3d(35vw, 106vh, 0);
            transform: translate3d(35vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(84vw, -124vh, 0);
            transform: translate3d(84vw, -124vh, 0);
  }
}
@keyframes move-frames-102 {
  from {
    -webkit-transform: translate3d(35vw, 106vh, 0);
            transform: translate3d(35vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(84vw, -124vh, 0);
            transform: translate3d(84vw, -124vh, 0);
  }
}
.circle-container:nth-child(102) .circle {
  -webkit-animation-delay: 2823ms;
          animation-delay: 2823ms;
}
.circle-container:nth-child(103) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-103;
          animation-name: move-frames-103;
  -webkit-animation-duration: 33020ms;
          animation-duration: 33020ms;
  -webkit-animation-delay: 11988ms;
          animation-delay: 11988ms;
}
@-webkit-keyframes move-frames-103 {
  from {
    -webkit-transform: translate3d(28vw, 106vh, 0);
            transform: translate3d(28vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -132vh, 0);
            transform: translate3d(65vw, -132vh, 0);
  }
}
@keyframes move-frames-103 {
  from {
    -webkit-transform: translate3d(28vw, 106vh, 0);
            transform: translate3d(28vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -132vh, 0);
            transform: translate3d(65vw, -132vh, 0);
  }
}
.circle-container:nth-child(103) .circle {
  -webkit-animation-delay: 2884ms;
          animation-delay: 2884ms;
}
.circle-container:nth-child(104) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-104;
          animation-name: move-frames-104;
  -webkit-animation-duration: 31958ms;
          animation-duration: 31958ms;
  -webkit-animation-delay: 5407ms;
          animation-delay: 5407ms;
}
@-webkit-keyframes move-frames-104 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -133vh, 0);
            transform: translate3d(42vw, -133vh, 0);
  }
}
@keyframes move-frames-104 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -133vh, 0);
            transform: translate3d(42vw, -133vh, 0);
  }
}
.circle-container:nth-child(104) .circle {
  -webkit-animation-delay: 3606ms;
          animation-delay: 3606ms;
}
.circle-container:nth-child(105) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-105;
          animation-name: move-frames-105;
  -webkit-animation-duration: 35504ms;
          animation-duration: 35504ms;
  -webkit-animation-delay: 17667ms;
          animation-delay: 17667ms;
}
@-webkit-keyframes move-frames-105 {
  from {
    -webkit-transform: translate3d(66vw, 108vh, 0);
            transform: translate3d(66vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -129vh, 0);
            transform: translate3d(8vw, -129vh, 0);
  }
}
@keyframes move-frames-105 {
  from {
    -webkit-transform: translate3d(66vw, 108vh, 0);
            transform: translate3d(66vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -129vh, 0);
            transform: translate3d(8vw, -129vh, 0);
  }
}
.circle-container:nth-child(105) .circle {
  -webkit-animation-delay: 1014ms;
          animation-delay: 1014ms;
}
.circle-container:nth-child(106) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-106;
          animation-name: move-frames-106;
  -webkit-animation-duration: 28257ms;
          animation-duration: 28257ms;
  -webkit-animation-delay: 4327ms;
          animation-delay: 4327ms;
}
@-webkit-keyframes move-frames-106 {
  from {
    -webkit-transform: translate3d(76vw, 109vh, 0);
            transform: translate3d(76vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -110vh, 0);
            transform: translate3d(42vw, -110vh, 0);
  }
}
@keyframes move-frames-106 {
  from {
    -webkit-transform: translate3d(76vw, 109vh, 0);
            transform: translate3d(76vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -110vh, 0);
            transform: translate3d(42vw, -110vh, 0);
  }
}
.circle-container:nth-child(106) .circle {
  -webkit-animation-delay: 3179ms;
          animation-delay: 3179ms;
}
.circle-container:nth-child(107) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-107;
          animation-name: move-frames-107;
  -webkit-animation-duration: 36162ms;
          animation-duration: 36162ms;
  -webkit-animation-delay: 27199ms;
          animation-delay: 27199ms;
}
@-webkit-keyframes move-frames-107 {
  from {
    -webkit-transform: translate3d(12vw, 109vh, 0);
            transform: translate3d(12vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -127vh, 0);
            transform: translate3d(30vw, -127vh, 0);
  }
}
@keyframes move-frames-107 {
  from {
    -webkit-transform: translate3d(12vw, 109vh, 0);
            transform: translate3d(12vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -127vh, 0);
            transform: translate3d(30vw, -127vh, 0);
  }
}
.circle-container:nth-child(107) .circle {
  -webkit-animation-delay: 1433ms;
          animation-delay: 1433ms;
}
.circle-container:nth-child(108) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-108;
          animation-name: move-frames-108;
  -webkit-animation-duration: 28216ms;
          animation-duration: 28216ms;
  -webkit-animation-delay: 17309ms;
          animation-delay: 17309ms;
}
@-webkit-keyframes move-frames-108 {
  from {
    -webkit-transform: translate3d(11vw, 110vh, 0);
            transform: translate3d(11vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -121vh, 0);
            transform: translate3d(61vw, -121vh, 0);
  }
}
@keyframes move-frames-108 {
  from {
    -webkit-transform: translate3d(11vw, 110vh, 0);
            transform: translate3d(11vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -121vh, 0);
            transform: translate3d(61vw, -121vh, 0);
  }
}
.circle-container:nth-child(108) .circle {
  -webkit-animation-delay: 1051ms;
          animation-delay: 1051ms;
}
.circle-container:nth-child(109) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-109;
          animation-name: move-frames-109;
  -webkit-animation-duration: 28920ms;
          animation-duration: 28920ms;
  -webkit-animation-delay: 8010ms;
          animation-delay: 8010ms;
}
@-webkit-keyframes move-frames-109 {
  from {
    -webkit-transform: translate3d(38vw, 105vh, 0);
            transform: translate3d(38vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -132vh, 0);
            transform: translate3d(31vw, -132vh, 0);
  }
}
@keyframes move-frames-109 {
  from {
    -webkit-transform: translate3d(38vw, 105vh, 0);
            transform: translate3d(38vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -132vh, 0);
            transform: translate3d(31vw, -132vh, 0);
  }
}
.circle-container:nth-child(109) .circle {
  -webkit-animation-delay: 1128ms;
          animation-delay: 1128ms;
}
.circle-container:nth-child(110) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-110;
          animation-name: move-frames-110;
  -webkit-animation-duration: 35391ms;
          animation-duration: 35391ms;
  -webkit-animation-delay: 7690ms;
          animation-delay: 7690ms;
}
@-webkit-keyframes move-frames-110 {
  from {
    -webkit-transform: translate3d(20vw, 104vh, 0);
            transform: translate3d(20vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -120vh, 0);
            transform: translate3d(19vw, -120vh, 0);
  }
}
@keyframes move-frames-110 {
  from {
    -webkit-transform: translate3d(20vw, 104vh, 0);
            transform: translate3d(20vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -120vh, 0);
            transform: translate3d(19vw, -120vh, 0);
  }
}
.circle-container:nth-child(110) .circle {
  -webkit-animation-delay: 742ms;
          animation-delay: 742ms;
}
.circle-container:nth-child(111) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-111;
          animation-name: move-frames-111;
  -webkit-animation-duration: 34083ms;
          animation-duration: 34083ms;
  -webkit-animation-delay: 5863ms;
          animation-delay: 5863ms;
}
@-webkit-keyframes move-frames-111 {
  from {
    -webkit-transform: translate3d(32vw, 109vh, 0);
            transform: translate3d(32vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(29vw, -134vh, 0);
            transform: translate3d(29vw, -134vh, 0);
  }
}
@keyframes move-frames-111 {
  from {
    -webkit-transform: translate3d(32vw, 109vh, 0);
            transform: translate3d(32vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(29vw, -134vh, 0);
            transform: translate3d(29vw, -134vh, 0);
  }
}
.circle-container:nth-child(111) .circle {
  -webkit-animation-delay: 1980ms;
          animation-delay: 1980ms;
}
.circle-container:nth-child(112) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-112;
          animation-name: move-frames-112;
  -webkit-animation-duration: 36972ms;
          animation-duration: 36972ms;
  -webkit-animation-delay: 21741ms;
          animation-delay: 21741ms;
}
@-webkit-keyframes move-frames-112 {
  from {
    -webkit-transform: translate3d(72vw, 106vh, 0);
            transform: translate3d(72vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(93vw, -112vh, 0);
            transform: translate3d(93vw, -112vh, 0);
  }
}
@keyframes move-frames-112 {
  from {
    -webkit-transform: translate3d(72vw, 106vh, 0);
            transform: translate3d(72vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(93vw, -112vh, 0);
            transform: translate3d(93vw, -112vh, 0);
  }
}
.circle-container:nth-child(112) .circle {
  -webkit-animation-delay: 2019ms;
          animation-delay: 2019ms;
}
.circle-container:nth-child(113) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-113;
          animation-name: move-frames-113;
  -webkit-animation-duration: 36343ms;
          animation-duration: 36343ms;
  -webkit-animation-delay: 19310ms;
          animation-delay: 19310ms;
}
@-webkit-keyframes move-frames-113 {
  from {
    -webkit-transform: translate3d(73vw, 101vh, 0);
            transform: translate3d(73vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -122vh, 0);
            transform: translate3d(49vw, -122vh, 0);
  }
}
@keyframes move-frames-113 {
  from {
    -webkit-transform: translate3d(73vw, 101vh, 0);
            transform: translate3d(73vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -122vh, 0);
            transform: translate3d(49vw, -122vh, 0);
  }
}
.circle-container:nth-child(113) .circle {
  -webkit-animation-delay: 2015ms;
          animation-delay: 2015ms;
}
.circle-container:nth-child(114) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-114;
          animation-name: move-frames-114;
  -webkit-animation-duration: 32703ms;
          animation-duration: 32703ms;
  -webkit-animation-delay: 11654ms;
          animation-delay: 11654ms;
}
@-webkit-keyframes move-frames-114 {
  from {
    -webkit-transform: translate3d(86vw, 103vh, 0);
            transform: translate3d(86vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -117vh, 0);
            transform: translate3d(31vw, -117vh, 0);
  }
}
@keyframes move-frames-114 {
  from {
    -webkit-transform: translate3d(86vw, 103vh, 0);
            transform: translate3d(86vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -117vh, 0);
            transform: translate3d(31vw, -117vh, 0);
  }
}
.circle-container:nth-child(114) .circle {
  -webkit-animation-delay: 2627ms;
          animation-delay: 2627ms;
}
.circle-container:nth-child(115) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-115;
          animation-name: move-frames-115;
  -webkit-animation-duration: 34806ms;
          animation-duration: 34806ms;
  -webkit-animation-delay: 20044ms;
          animation-delay: 20044ms;
}
@-webkit-keyframes move-frames-115 {
  from {
    -webkit-transform: translate3d(90vw, 101vh, 0);
            transform: translate3d(90vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -129vh, 0);
            transform: translate3d(24vw, -129vh, 0);
  }
}
@keyframes move-frames-115 {
  from {
    -webkit-transform: translate3d(90vw, 101vh, 0);
            transform: translate3d(90vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -129vh, 0);
            transform: translate3d(24vw, -129vh, 0);
  }
}
.circle-container:nth-child(115) .circle {
  -webkit-animation-delay: 2647ms;
          animation-delay: 2647ms;
}
.circle-container:nth-child(116) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-116;
          animation-name: move-frames-116;
  -webkit-animation-duration: 30615ms;
          animation-duration: 30615ms;
  -webkit-animation-delay: 4044ms;
          animation-delay: 4044ms;
}
@-webkit-keyframes move-frames-116 {
  from {
    -webkit-transform: translate3d(31vw, 106vh, 0);
            transform: translate3d(31vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -113vh, 0);
            transform: translate3d(11vw, -113vh, 0);
  }
}
@keyframes move-frames-116 {
  from {
    -webkit-transform: translate3d(31vw, 106vh, 0);
            transform: translate3d(31vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -113vh, 0);
            transform: translate3d(11vw, -113vh, 0);
  }
}
.circle-container:nth-child(116) .circle {
  -webkit-animation-delay: 3409ms;
          animation-delay: 3409ms;
}
.circle-container:nth-child(117) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-117;
          animation-name: move-frames-117;
  -webkit-animation-duration: 31056ms;
          animation-duration: 31056ms;
  -webkit-animation-delay: 34048ms;
          animation-delay: 34048ms;
}
@-webkit-keyframes move-frames-117 {
  from {
    -webkit-transform: translate3d(93vw, 104vh, 0);
            transform: translate3d(93vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(83vw, -117vh, 0);
            transform: translate3d(83vw, -117vh, 0);
  }
}
@keyframes move-frames-117 {
  from {
    -webkit-transform: translate3d(93vw, 104vh, 0);
            transform: translate3d(93vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(83vw, -117vh, 0);
            transform: translate3d(83vw, -117vh, 0);
  }
}
.circle-container:nth-child(117) .circle {
  -webkit-animation-delay: 3143ms;
          animation-delay: 3143ms;
}
.circle-container:nth-child(118) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-118;
          animation-name: move-frames-118;
  -webkit-animation-duration: 34607ms;
          animation-duration: 34607ms;
  -webkit-animation-delay: 9562ms;
          animation-delay: 9562ms;
}
@-webkit-keyframes move-frames-118 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -111vh, 0);
            transform: translate3d(42vw, -111vh, 0);
  }
}
@keyframes move-frames-118 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -111vh, 0);
            transform: translate3d(42vw, -111vh, 0);
  }
}
.circle-container:nth-child(118) .circle {
  -webkit-animation-delay: 337ms;
          animation-delay: 337ms;
}
.circle-container:nth-child(119) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-119;
          animation-name: move-frames-119;
  -webkit-animation-duration: 32529ms;
          animation-duration: 32529ms;
  -webkit-animation-delay: 28826ms;
          animation-delay: 28826ms;
}
@-webkit-keyframes move-frames-119 {
  from {
    -webkit-transform: translate3d(26vw, 105vh, 0);
            transform: translate3d(26vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -135vh, 0);
            transform: translate3d(44vw, -135vh, 0);
  }
}
@keyframes move-frames-119 {
  from {
    -webkit-transform: translate3d(26vw, 105vh, 0);
            transform: translate3d(26vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -135vh, 0);
            transform: translate3d(44vw, -135vh, 0);
  }
}
.circle-container:nth-child(119) .circle {
  -webkit-animation-delay: 3503ms;
          animation-delay: 3503ms;
}
.circle-container:nth-child(120) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-120;
          animation-name: move-frames-120;
  -webkit-animation-duration: 29857ms;
          animation-duration: 29857ms;
  -webkit-animation-delay: 26331ms;
          animation-delay: 26331ms;
}
@-webkit-keyframes move-frames-120 {
  from {
    -webkit-transform: translate3d(18vw, 104vh, 0);
            transform: translate3d(18vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -133vh, 0);
            transform: translate3d(7vw, -133vh, 0);
  }
}
@keyframes move-frames-120 {
  from {
    -webkit-transform: translate3d(18vw, 104vh, 0);
            transform: translate3d(18vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -133vh, 0);
            transform: translate3d(7vw, -133vh, 0);
  }
}
.circle-container:nth-child(120) .circle {
  -webkit-animation-delay: 1361ms;
          animation-delay: 1361ms;
}
.circle-container:nth-child(121) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-121;
          animation-name: move-frames-121;
  -webkit-animation-duration: 29235ms;
          animation-duration: 29235ms;
  -webkit-animation-delay: 23288ms;
          animation-delay: 23288ms;
}
@-webkit-keyframes move-frames-121 {
  from {
    -webkit-transform: translate3d(97vw, 108vh, 0);
            transform: translate3d(97vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -110vh, 0);
            transform: translate3d(44vw, -110vh, 0);
  }
}
@keyframes move-frames-121 {
  from {
    -webkit-transform: translate3d(97vw, 108vh, 0);
            transform: translate3d(97vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -110vh, 0);
            transform: translate3d(44vw, -110vh, 0);
  }
}
.circle-container:nth-child(121) .circle {
  -webkit-animation-delay: 303ms;
          animation-delay: 303ms;
}
.circle-container:nth-child(122) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-122;
          animation-name: move-frames-122;
  -webkit-animation-duration: 35142ms;
          animation-duration: 35142ms;
  -webkit-animation-delay: 30349ms;
          animation-delay: 30349ms;
}
@-webkit-keyframes move-frames-122 {
  from {
    -webkit-transform: translate3d(71vw, 102vh, 0);
            transform: translate3d(71vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -111vh, 0);
            transform: translate3d(51vw, -111vh, 0);
  }
}
@keyframes move-frames-122 {
  from {
    -webkit-transform: translate3d(71vw, 102vh, 0);
            transform: translate3d(71vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -111vh, 0);
            transform: translate3d(51vw, -111vh, 0);
  }
}
.circle-container:nth-child(122) .circle {
  -webkit-animation-delay: 3880ms;
          animation-delay: 3880ms;
}
.circle-container:nth-child(123) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-123;
          animation-name: move-frames-123;
  -webkit-animation-duration: 35946ms;
          animation-duration: 35946ms;
  -webkit-animation-delay: 30504ms;
          animation-delay: 30504ms;
}
@-webkit-keyframes move-frames-123 {
  from {
    -webkit-transform: translate3d(31vw, 109vh, 0);
            transform: translate3d(31vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -110vh, 0);
            transform: translate3d(19vw, -110vh, 0);
  }
}
@keyframes move-frames-123 {
  from {
    -webkit-transform: translate3d(31vw, 109vh, 0);
            transform: translate3d(31vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -110vh, 0);
            transform: translate3d(19vw, -110vh, 0);
  }
}
.circle-container:nth-child(123) .circle {
  -webkit-animation-delay: 216ms;
          animation-delay: 216ms;
}
.circle-container:nth-child(124) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-124;
          animation-name: move-frames-124;
  -webkit-animation-duration: 35553ms;
          animation-duration: 35553ms;
  -webkit-animation-delay: 20074ms;
          animation-delay: 20074ms;
}
@-webkit-keyframes move-frames-124 {
  from {
    -webkit-transform: translate3d(83vw, 109vh, 0);
            transform: translate3d(83vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(85vw, -111vh, 0);
            transform: translate3d(85vw, -111vh, 0);
  }
}
@keyframes move-frames-124 {
  from {
    -webkit-transform: translate3d(83vw, 109vh, 0);
            transform: translate3d(83vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(85vw, -111vh, 0);
            transform: translate3d(85vw, -111vh, 0);
  }
}
.circle-container:nth-child(124) .circle {
  -webkit-animation-delay: 71ms;
          animation-delay: 71ms;
}
.circle-container:nth-child(125) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-125;
          animation-name: move-frames-125;
  -webkit-animation-duration: 30604ms;
          animation-duration: 30604ms;
  -webkit-animation-delay: 3069ms;
          animation-delay: 3069ms;
}
@-webkit-keyframes move-frames-125 {
  from {
    -webkit-transform: translate3d(94vw, 102vh, 0);
            transform: translate3d(94vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -104vh, 0);
            transform: translate3d(91vw, -104vh, 0);
  }
}
@keyframes move-frames-125 {
  from {
    -webkit-transform: translate3d(94vw, 102vh, 0);
            transform: translate3d(94vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -104vh, 0);
            transform: translate3d(91vw, -104vh, 0);
  }
}
.circle-container:nth-child(125) .circle {
  -webkit-animation-delay: 3359ms;
          animation-delay: 3359ms;
}
.circle-container:nth-child(126) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-126;
          animation-name: move-frames-126;
  -webkit-animation-duration: 32867ms;
          animation-duration: 32867ms;
  -webkit-animation-delay: 32996ms;
          animation-delay: 32996ms;
}
@-webkit-keyframes move-frames-126 {
  from {
    -webkit-transform: translate3d(18vw, 103vh, 0);
            transform: translate3d(18vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -122vh, 0);
            transform: translate3d(45vw, -122vh, 0);
  }
}
@keyframes move-frames-126 {
  from {
    -webkit-transform: translate3d(18vw, 103vh, 0);
            transform: translate3d(18vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -122vh, 0);
            transform: translate3d(45vw, -122vh, 0);
  }
}
.circle-container:nth-child(126) .circle {
  -webkit-animation-delay: 2553ms;
          animation-delay: 2553ms;
}
.circle-container:nth-child(127) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-127;
          animation-name: move-frames-127;
  -webkit-animation-duration: 32276ms;
          animation-duration: 32276ms;
  -webkit-animation-delay: 13506ms;
          animation-delay: 13506ms;
}
@-webkit-keyframes move-frames-127 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(15vw, -108vh, 0);
            transform: translate3d(15vw, -108vh, 0);
  }
}
@keyframes move-frames-127 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(15vw, -108vh, 0);
            transform: translate3d(15vw, -108vh, 0);
  }
}
.circle-container:nth-child(127) .circle {
  -webkit-animation-delay: 2862ms;
          animation-delay: 2862ms;
}
.circle-container:nth-child(128) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-128;
          animation-name: move-frames-128;
  -webkit-animation-duration: 36183ms;
          animation-duration: 36183ms;
  -webkit-animation-delay: 29746ms;
          animation-delay: 29746ms;
}
@-webkit-keyframes move-frames-128 {
  from {
    -webkit-transform: translate3d(6vw, 102vh, 0);
            transform: translate3d(6vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -131vh, 0);
            transform: translate3d(21vw, -131vh, 0);
  }
}
@keyframes move-frames-128 {
  from {
    -webkit-transform: translate3d(6vw, 102vh, 0);
            transform: translate3d(6vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -131vh, 0);
            transform: translate3d(21vw, -131vh, 0);
  }
}
.circle-container:nth-child(128) .circle {
  -webkit-animation-delay: 3125ms;
          animation-delay: 3125ms;
}
.circle-container:nth-child(129) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-129;
          animation-name: move-frames-129;
  -webkit-animation-duration: 32248ms;
          animation-duration: 32248ms;
  -webkit-animation-delay: 6855ms;
          animation-delay: 6855ms;
}
@-webkit-keyframes move-frames-129 {
  from {
    -webkit-transform: translate3d(47vw, 104vh, 0);
            transform: translate3d(47vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -117vh, 0);
            transform: translate3d(62vw, -117vh, 0);
  }
}
@keyframes move-frames-129 {
  from {
    -webkit-transform: translate3d(47vw, 104vh, 0);
            transform: translate3d(47vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -117vh, 0);
            transform: translate3d(62vw, -117vh, 0);
  }
}
.circle-container:nth-child(129) .circle {
  -webkit-animation-delay: 1634ms;
          animation-delay: 1634ms;
}
.circle-container:nth-child(130) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-130;
          animation-name: move-frames-130;
  -webkit-animation-duration: 29428ms;
          animation-duration: 29428ms;
  -webkit-animation-delay: 4492ms;
          animation-delay: 4492ms;
}
@-webkit-keyframes move-frames-130 {
  from {
    -webkit-transform: translate3d(54vw, 104vh, 0);
            transform: translate3d(54vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(22vw, -107vh, 0);
            transform: translate3d(22vw, -107vh, 0);
  }
}
@keyframes move-frames-130 {
  from {
    -webkit-transform: translate3d(54vw, 104vh, 0);
            transform: translate3d(54vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(22vw, -107vh, 0);
            transform: translate3d(22vw, -107vh, 0);
  }
}
.circle-container:nth-child(130) .circle {
  -webkit-animation-delay: 1908ms;
          animation-delay: 1908ms;
}
.circle-container:nth-child(131) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-131;
          animation-name: move-frames-131;
  -webkit-animation-duration: 28957ms;
          animation-duration: 28957ms;
  -webkit-animation-delay: 10901ms;
          animation-delay: 10901ms;
}
@-webkit-keyframes move-frames-131 {
  from {
    -webkit-transform: translate3d(15vw, 108vh, 0);
            transform: translate3d(15vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -112vh, 0);
            transform: translate3d(77vw, -112vh, 0);
  }
}
@keyframes move-frames-131 {
  from {
    -webkit-transform: translate3d(15vw, 108vh, 0);
            transform: translate3d(15vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -112vh, 0);
            transform: translate3d(77vw, -112vh, 0);
  }
}
.circle-container:nth-child(131) .circle {
  -webkit-animation-delay: 999ms;
          animation-delay: 999ms;
}
.circle-container:nth-child(132) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-132;
          animation-name: move-frames-132;
  -webkit-animation-duration: 35733ms;
          animation-duration: 35733ms;
  -webkit-animation-delay: 35884ms;
          animation-delay: 35884ms;
}
@-webkit-keyframes move-frames-132 {
  from {
    -webkit-transform: translate3d(74vw, 108vh, 0);
            transform: translate3d(74vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(4vw, -134vh, 0);
            transform: translate3d(4vw, -134vh, 0);
  }
}
@keyframes move-frames-132 {
  from {
    -webkit-transform: translate3d(74vw, 108vh, 0);
            transform: translate3d(74vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(4vw, -134vh, 0);
            transform: translate3d(4vw, -134vh, 0);
  }
}
.circle-container:nth-child(132) .circle {
  -webkit-animation-delay: 3796ms;
          animation-delay: 3796ms;
}
.circle-container:nth-child(133) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-133;
          animation-name: move-frames-133;
  -webkit-animation-duration: 35995ms;
          animation-duration: 35995ms;
  -webkit-animation-delay: 8576ms;
          animation-delay: 8576ms;
}
@-webkit-keyframes move-frames-133 {
  from {
    -webkit-transform: translate3d(39vw, 108vh, 0);
            transform: translate3d(39vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(97vw, -118vh, 0);
            transform: translate3d(97vw, -118vh, 0);
  }
}
@keyframes move-frames-133 {
  from {
    -webkit-transform: translate3d(39vw, 108vh, 0);
            transform: translate3d(39vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(97vw, -118vh, 0);
            transform: translate3d(97vw, -118vh, 0);
  }
}
.circle-container:nth-child(133) .circle {
  -webkit-animation-delay: 634ms;
          animation-delay: 634ms;
}
.circle-container:nth-child(134) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-134;
          animation-name: move-frames-134;
  -webkit-animation-duration: 31008ms;
          animation-duration: 31008ms;
  -webkit-animation-delay: 32288ms;
          animation-delay: 32288ms;
}
@-webkit-keyframes move-frames-134 {
  from {
    -webkit-transform: translate3d(90vw, 105vh, 0);
            transform: translate3d(90vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -124vh, 0);
            transform: translate3d(98vw, -124vh, 0);
  }
}
@keyframes move-frames-134 {
  from {
    -webkit-transform: translate3d(90vw, 105vh, 0);
            transform: translate3d(90vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -124vh, 0);
            transform: translate3d(98vw, -124vh, 0);
  }
}
.circle-container:nth-child(134) .circle {
  -webkit-animation-delay: 214ms;
          animation-delay: 214ms;
}
.circle-container:nth-child(135) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-135;
          animation-name: move-frames-135;
  -webkit-animation-duration: 33021ms;
          animation-duration: 33021ms;
  -webkit-animation-delay: 12805ms;
          animation-delay: 12805ms;
}
@-webkit-keyframes move-frames-135 {
  from {
    -webkit-transform: translate3d(53vw, 102vh, 0);
            transform: translate3d(53vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -125vh, 0);
            transform: translate3d(95vw, -125vh, 0);
  }
}
@keyframes move-frames-135 {
  from {
    -webkit-transform: translate3d(53vw, 102vh, 0);
            transform: translate3d(53vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -125vh, 0);
            transform: translate3d(95vw, -125vh, 0);
  }
}
.circle-container:nth-child(135) .circle {
  -webkit-animation-delay: 1293ms;
          animation-delay: 1293ms;
}
.circle-container:nth-child(136) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-136;
          animation-name: move-frames-136;
  -webkit-animation-duration: 34065ms;
          animation-duration: 34065ms;
  -webkit-animation-delay: 25714ms;
          animation-delay: 25714ms;
}
@-webkit-keyframes move-frames-136 {
  from {
    -webkit-transform: translate3d(10vw, 105vh, 0);
            transform: translate3d(10vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -123vh, 0);
            transform: translate3d(55vw, -123vh, 0);
  }
}
@keyframes move-frames-136 {
  from {
    -webkit-transform: translate3d(10vw, 105vh, 0);
            transform: translate3d(10vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -123vh, 0);
            transform: translate3d(55vw, -123vh, 0);
  }
}
.circle-container:nth-child(136) .circle {
  -webkit-animation-delay: 1421ms;
          animation-delay: 1421ms;
}
.circle-container:nth-child(137) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-137;
          animation-name: move-frames-137;
  -webkit-animation-duration: 28674ms;
          animation-duration: 28674ms;
  -webkit-animation-delay: 21030ms;
          animation-delay: 21030ms;
}
@-webkit-keyframes move-frames-137 {
  from {
    -webkit-transform: translate3d(41vw, 104vh, 0);
            transform: translate3d(41vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -114vh, 0);
            transform: translate3d(100vw, -114vh, 0);
  }
}
@keyframes move-frames-137 {
  from {
    -webkit-transform: translate3d(41vw, 104vh, 0);
            transform: translate3d(41vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -114vh, 0);
            transform: translate3d(100vw, -114vh, 0);
  }
}
.circle-container:nth-child(137) .circle {
  -webkit-animation-delay: 1085ms;
          animation-delay: 1085ms;
}
.circle-container:nth-child(138) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-138;
          animation-name: move-frames-138;
  -webkit-animation-duration: 30439ms;
          animation-duration: 30439ms;
  -webkit-animation-delay: 21873ms;
          animation-delay: 21873ms;
}
@-webkit-keyframes move-frames-138 {
  from {
    -webkit-transform: translate3d(71vw, 101vh, 0);
            transform: translate3d(71vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(73vw, -109vh, 0);
            transform: translate3d(73vw, -109vh, 0);
  }
}
@keyframes move-frames-138 {
  from {
    -webkit-transform: translate3d(71vw, 101vh, 0);
            transform: translate3d(71vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(73vw, -109vh, 0);
            transform: translate3d(73vw, -109vh, 0);
  }
}
.circle-container:nth-child(138) .circle {
  -webkit-animation-delay: 1631ms;
          animation-delay: 1631ms;
}
.circle-container:nth-child(139) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-139;
          animation-name: move-frames-139;
  -webkit-animation-duration: 34739ms;
          animation-duration: 34739ms;
  -webkit-animation-delay: 19845ms;
          animation-delay: 19845ms;
}
@-webkit-keyframes move-frames-139 {
  from {
    -webkit-transform: translate3d(35vw, 107vh, 0);
            transform: translate3d(35vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(15vw, -137vh, 0);
            transform: translate3d(15vw, -137vh, 0);
  }
}
@keyframes move-frames-139 {
  from {
    -webkit-transform: translate3d(35vw, 107vh, 0);
            transform: translate3d(35vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(15vw, -137vh, 0);
            transform: translate3d(15vw, -137vh, 0);
  }
}
.circle-container:nth-child(139) .circle {
  -webkit-animation-delay: 1199ms;
          animation-delay: 1199ms;
}
.circle-container:nth-child(140) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-140;
          animation-name: move-frames-140;
  -webkit-animation-duration: 32168ms;
          animation-duration: 32168ms;
  -webkit-animation-delay: 20488ms;
          animation-delay: 20488ms;
}
@-webkit-keyframes move-frames-140 {
  from {
    -webkit-transform: translate3d(82vw, 109vh, 0);
            transform: translate3d(82vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -135vh, 0);
            transform: translate3d(41vw, -135vh, 0);
  }
}
@keyframes move-frames-140 {
  from {
    -webkit-transform: translate3d(82vw, 109vh, 0);
            transform: translate3d(82vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -135vh, 0);
            transform: translate3d(41vw, -135vh, 0);
  }
}
.circle-container:nth-child(140) .circle {
  -webkit-animation-delay: 2635ms;
          animation-delay: 2635ms;
}
.circle-container:nth-child(141) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-141;
          animation-name: move-frames-141;
  -webkit-animation-duration: 30146ms;
          animation-duration: 30146ms;
  -webkit-animation-delay: 4689ms;
          animation-delay: 4689ms;
}
@-webkit-keyframes move-frames-141 {
  from {
    -webkit-transform: translate3d(72vw, 109vh, 0);
            transform: translate3d(72vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -134vh, 0);
            transform: translate3d(43vw, -134vh, 0);
  }
}
@keyframes move-frames-141 {
  from {
    -webkit-transform: translate3d(72vw, 109vh, 0);
            transform: translate3d(72vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -134vh, 0);
            transform: translate3d(43vw, -134vh, 0);
  }
}
.circle-container:nth-child(141) .circle {
  -webkit-animation-delay: 2121ms;
          animation-delay: 2121ms;
}
.circle-container:nth-child(142) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-142;
          animation-name: move-frames-142;
  -webkit-animation-duration: 28525ms;
          animation-duration: 28525ms;
  -webkit-animation-delay: 26261ms;
          animation-delay: 26261ms;
}
@-webkit-keyframes move-frames-142 {
  from {
    -webkit-transform: translate3d(62vw, 109vh, 0);
            transform: translate3d(62vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -123vh, 0);
            transform: translate3d(42vw, -123vh, 0);
  }
}
@keyframes move-frames-142 {
  from {
    -webkit-transform: translate3d(62vw, 109vh, 0);
            transform: translate3d(62vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -123vh, 0);
            transform: translate3d(42vw, -123vh, 0);
  }
}
.circle-container:nth-child(142) .circle {
  -webkit-animation-delay: 1291ms;
          animation-delay: 1291ms;
}
.circle-container:nth-child(143) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-143;
          animation-name: move-frames-143;
  -webkit-animation-duration: 28360ms;
          animation-duration: 28360ms;
  -webkit-animation-delay: 4549ms;
          animation-delay: 4549ms;
}
@-webkit-keyframes move-frames-143 {
  from {
    -webkit-transform: translate3d(75vw, 106vh, 0);
            transform: translate3d(75vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -115vh, 0);
            transform: translate3d(60vw, -115vh, 0);
  }
}
@keyframes move-frames-143 {
  from {
    -webkit-transform: translate3d(75vw, 106vh, 0);
            transform: translate3d(75vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -115vh, 0);
            transform: translate3d(60vw, -115vh, 0);
  }
}
.circle-container:nth-child(143) .circle {
  -webkit-animation-delay: 2072ms;
          animation-delay: 2072ms;
}
.circle-container:nth-child(144) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-144;
          animation-name: move-frames-144;
  -webkit-animation-duration: 30034ms;
          animation-duration: 30034ms;
  -webkit-animation-delay: 17427ms;
          animation-delay: 17427ms;
}
@-webkit-keyframes move-frames-144 {
  from {
    -webkit-transform: translate3d(50vw, 110vh, 0);
            transform: translate3d(50vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -124vh, 0);
            transform: translate3d(80vw, -124vh, 0);
  }
}
@keyframes move-frames-144 {
  from {
    -webkit-transform: translate3d(50vw, 110vh, 0);
            transform: translate3d(50vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -124vh, 0);
            transform: translate3d(80vw, -124vh, 0);
  }
}
.circle-container:nth-child(144) .circle {
  -webkit-animation-delay: 3160ms;
          animation-delay: 3160ms;
}
.circle-container:nth-child(145) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-145;
          animation-name: move-frames-145;
  -webkit-animation-duration: 35412ms;
          animation-duration: 35412ms;
  -webkit-animation-delay: 32340ms;
          animation-delay: 32340ms;
}
@-webkit-keyframes move-frames-145 {
  from {
    -webkit-transform: translate3d(29vw, 104vh, 0);
            transform: translate3d(29vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -134vh, 0);
            transform: translate3d(100vw, -134vh, 0);
  }
}
@keyframes move-frames-145 {
  from {
    -webkit-transform: translate3d(29vw, 104vh, 0);
            transform: translate3d(29vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -134vh, 0);
            transform: translate3d(100vw, -134vh, 0);
  }
}
.circle-container:nth-child(145) .circle {
  -webkit-animation-delay: 2535ms;
          animation-delay: 2535ms;
}
.circle-container:nth-child(146) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-146;
          animation-name: move-frames-146;
  -webkit-animation-duration: 31517ms;
          animation-duration: 31517ms;
  -webkit-animation-delay: 1649ms;
          animation-delay: 1649ms;
}
@-webkit-keyframes move-frames-146 {
  from {
    -webkit-transform: translate3d(79vw, 110vh, 0);
            transform: translate3d(79vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -123vh, 0);
            transform: translate3d(57vw, -123vh, 0);
  }
}
@keyframes move-frames-146 {
  from {
    -webkit-transform: translate3d(79vw, 110vh, 0);
            transform: translate3d(79vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -123vh, 0);
            transform: translate3d(57vw, -123vh, 0);
  }
}
.circle-container:nth-child(146) .circle {
  -webkit-animation-delay: 3592ms;
          animation-delay: 3592ms;
}
.circle-container:nth-child(147) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-147;
          animation-name: move-frames-147;
  -webkit-animation-duration: 30512ms;
          animation-duration: 30512ms;
  -webkit-animation-delay: 36604ms;
          animation-delay: 36604ms;
}
@-webkit-keyframes move-frames-147 {
  from {
    -webkit-transform: translate3d(73vw, 108vh, 0);
            transform: translate3d(73vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -123vh, 0);
            transform: translate3d(33vw, -123vh, 0);
  }
}
@keyframes move-frames-147 {
  from {
    -webkit-transform: translate3d(73vw, 108vh, 0);
            transform: translate3d(73vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -123vh, 0);
            transform: translate3d(33vw, -123vh, 0);
  }
}
.circle-container:nth-child(147) .circle {
  -webkit-animation-delay: 3918ms;
          animation-delay: 3918ms;
}
.circle-container:nth-child(148) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-148;
          animation-name: move-frames-148;
  -webkit-animation-duration: 36063ms;
          animation-duration: 36063ms;
  -webkit-animation-delay: 29401ms;
          animation-delay: 29401ms;
}
@-webkit-keyframes move-frames-148 {
  from {
    -webkit-transform: translate3d(51vw, 107vh, 0);
            transform: translate3d(51vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(34vw, -113vh, 0);
            transform: translate3d(34vw, -113vh, 0);
  }
}
@keyframes move-frames-148 {
  from {
    -webkit-transform: translate3d(51vw, 107vh, 0);
            transform: translate3d(51vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(34vw, -113vh, 0);
            transform: translate3d(34vw, -113vh, 0);
  }
}
.circle-container:nth-child(148) .circle {
  -webkit-animation-delay: 1050ms;
          animation-delay: 1050ms;
}
.circle-container:nth-child(149) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-149;
          animation-name: move-frames-149;
  -webkit-animation-duration: 28955ms;
          animation-duration: 28955ms;
  -webkit-animation-delay: 24938ms;
          animation-delay: 24938ms;
}
@-webkit-keyframes move-frames-149 {
  from {
    -webkit-transform: translate3d(2vw, 101vh, 0);
            transform: translate3d(2vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -111vh, 0);
            transform: translate3d(55vw, -111vh, 0);
  }
}
@keyframes move-frames-149 {
  from {
    -webkit-transform: translate3d(2vw, 101vh, 0);
            transform: translate3d(2vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -111vh, 0);
            transform: translate3d(55vw, -111vh, 0);
  }
}
.circle-container:nth-child(149) .circle {
  -webkit-animation-delay: 2447ms;
          animation-delay: 2447ms;
}
.circle-container:nth-child(150) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-150;
          animation-name: move-frames-150;
  -webkit-animation-duration: 32788ms;
          animation-duration: 32788ms;
  -webkit-animation-delay: 24722ms;
          animation-delay: 24722ms;
}
@-webkit-keyframes move-frames-150 {
  from {
    -webkit-transform: translate3d(26vw, 101vh, 0);
            transform: translate3d(26vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -106vh, 0);
            transform: translate3d(54vw, -106vh, 0);
  }
}
@keyframes move-frames-150 {
  from {
    -webkit-transform: translate3d(26vw, 101vh, 0);
            transform: translate3d(26vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -106vh, 0);
            transform: translate3d(54vw, -106vh, 0);
  }
}
.circle-container:nth-child(150) .circle {
  -webkit-animation-delay: 1371ms;
          animation-delay: 1371ms;
}
.circle-container:nth-child(151) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-151;
          animation-name: move-frames-151;
  -webkit-animation-duration: 32468ms;
          animation-duration: 32468ms;
  -webkit-animation-delay: 17733ms;
          animation-delay: 17733ms;
}
@-webkit-keyframes move-frames-151 {
  from {
    -webkit-transform: translate3d(3vw, 104vh, 0);
            transform: translate3d(3vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -133vh, 0);
            transform: translate3d(81vw, -133vh, 0);
  }
}
@keyframes move-frames-151 {
  from {
    -webkit-transform: translate3d(3vw, 104vh, 0);
            transform: translate3d(3vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -133vh, 0);
            transform: translate3d(81vw, -133vh, 0);
  }
}
.circle-container:nth-child(151) .circle {
  -webkit-animation-delay: 2266ms;
          animation-delay: 2266ms;
}
.circle-container:nth-child(152) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-152;
          animation-name: move-frames-152;
  -webkit-animation-duration: 29051ms;
          animation-duration: 29051ms;
  -webkit-animation-delay: 35140ms;
          animation-delay: 35140ms;
}
@-webkit-keyframes move-frames-152 {
  from {
    -webkit-transform: translate3d(96vw, 107vh, 0);
            transform: translate3d(96vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -123vh, 0);
            transform: translate3d(28vw, -123vh, 0);
  }
}
@keyframes move-frames-152 {
  from {
    -webkit-transform: translate3d(96vw, 107vh, 0);
            transform: translate3d(96vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -123vh, 0);
            transform: translate3d(28vw, -123vh, 0);
  }
}
.circle-container:nth-child(152) .circle {
  -webkit-animation-delay: 2698ms;
          animation-delay: 2698ms;
}
.circle-container:nth-child(153) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-153;
          animation-name: move-frames-153;
  -webkit-animation-duration: 31393ms;
          animation-duration: 31393ms;
  -webkit-animation-delay: 13690ms;
          animation-delay: 13690ms;
}
@-webkit-keyframes move-frames-153 {
  from {
    -webkit-transform: translate3d(27vw, 108vh, 0);
            transform: translate3d(27vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -114vh, 0);
            transform: translate3d(39vw, -114vh, 0);
  }
}
@keyframes move-frames-153 {
  from {
    -webkit-transform: translate3d(27vw, 108vh, 0);
            transform: translate3d(27vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -114vh, 0);
            transform: translate3d(39vw, -114vh, 0);
  }
}
.circle-container:nth-child(153) .circle {
  -webkit-animation-delay: 3295ms;
          animation-delay: 3295ms;
}
.circle-container:nth-child(154) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-154;
          animation-name: move-frames-154;
  -webkit-animation-duration: 31998ms;
          animation-duration: 31998ms;
  -webkit-animation-delay: 9147ms;
          animation-delay: 9147ms;
}
@-webkit-keyframes move-frames-154 {
  from {
    -webkit-transform: translate3d(72vw, 101vh, 0);
            transform: translate3d(72vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -111vh, 0);
            transform: translate3d(33vw, -111vh, 0);
  }
}
@keyframes move-frames-154 {
  from {
    -webkit-transform: translate3d(72vw, 101vh, 0);
            transform: translate3d(72vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -111vh, 0);
            transform: translate3d(33vw, -111vh, 0);
  }
}
.circle-container:nth-child(154) .circle {
  -webkit-animation-delay: 3297ms;
          animation-delay: 3297ms;
}
.circle-container:nth-child(155) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-155;
          animation-name: move-frames-155;
  -webkit-animation-duration: 35353ms;
          animation-duration: 35353ms;
  -webkit-animation-delay: 12674ms;
          animation-delay: 12674ms;
}
@-webkit-keyframes move-frames-155 {
  from {
    -webkit-transform: translate3d(6vw, 109vh, 0);
            transform: translate3d(6vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(93vw, -117vh, 0);
            transform: translate3d(93vw, -117vh, 0);
  }
}
@keyframes move-frames-155 {
  from {
    -webkit-transform: translate3d(6vw, 109vh, 0);
            transform: translate3d(6vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(93vw, -117vh, 0);
            transform: translate3d(93vw, -117vh, 0);
  }
}
.circle-container:nth-child(155) .circle {
  -webkit-animation-delay: 2996ms;
          animation-delay: 2996ms;
}
.circle-container:nth-child(156) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-156;
          animation-name: move-frames-156;
  -webkit-animation-duration: 32999ms;
          animation-duration: 32999ms;
  -webkit-animation-delay: 16521ms;
          animation-delay: 16521ms;
}
@-webkit-keyframes move-frames-156 {
  from {
    -webkit-transform: translate3d(61vw, 103vh, 0);
            transform: translate3d(61vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(9vw, -128vh, 0);
            transform: translate3d(9vw, -128vh, 0);
  }
}
@keyframes move-frames-156 {
  from {
    -webkit-transform: translate3d(61vw, 103vh, 0);
            transform: translate3d(61vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(9vw, -128vh, 0);
            transform: translate3d(9vw, -128vh, 0);
  }
}
.circle-container:nth-child(156) .circle {
  -webkit-animation-delay: 1599ms;
          animation-delay: 1599ms;
}
.circle-container:nth-child(157) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-157;
          animation-name: move-frames-157;
  -webkit-animation-duration: 35826ms;
          animation-duration: 35826ms;
  -webkit-animation-delay: 18963ms;
          animation-delay: 18963ms;
}
@-webkit-keyframes move-frames-157 {
  from {
    -webkit-transform: translate3d(55vw, 105vh, 0);
            transform: translate3d(55vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(56vw, -132vh, 0);
            transform: translate3d(56vw, -132vh, 0);
  }
}
@keyframes move-frames-157 {
  from {
    -webkit-transform: translate3d(55vw, 105vh, 0);
            transform: translate3d(55vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(56vw, -132vh, 0);
            transform: translate3d(56vw, -132vh, 0);
  }
}
.circle-container:nth-child(157) .circle {
  -webkit-animation-delay: 270ms;
          animation-delay: 270ms;
}
.circle-container:nth-child(158) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-158;
          animation-name: move-frames-158;
  -webkit-animation-duration: 28218ms;
          animation-duration: 28218ms;
  -webkit-animation-delay: 34887ms;
          animation-delay: 34887ms;
}
@-webkit-keyframes move-frames-158 {
  from {
    -webkit-transform: translate3d(41vw, 102vh, 0);
            transform: translate3d(41vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -108vh, 0);
            transform: translate3d(20vw, -108vh, 0);
  }
}
@keyframes move-frames-158 {
  from {
    -webkit-transform: translate3d(41vw, 102vh, 0);
            transform: translate3d(41vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -108vh, 0);
            transform: translate3d(20vw, -108vh, 0);
  }
}
.circle-container:nth-child(158) .circle {
  -webkit-animation-delay: 748ms;
          animation-delay: 748ms;
}
.circle-container:nth-child(159) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-159;
          animation-name: move-frames-159;
  -webkit-animation-duration: 35025ms;
          animation-duration: 35025ms;
  -webkit-animation-delay: 35408ms;
          animation-delay: 35408ms;
}
@-webkit-keyframes move-frames-159 {
  from {
    -webkit-transform: translate3d(30vw, 102vh, 0);
            transform: translate3d(30vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -104vh, 0);
            transform: translate3d(61vw, -104vh, 0);
  }
}
@keyframes move-frames-159 {
  from {
    -webkit-transform: translate3d(30vw, 102vh, 0);
            transform: translate3d(30vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -104vh, 0);
            transform: translate3d(61vw, -104vh, 0);
  }
}
.circle-container:nth-child(159) .circle {
  -webkit-animation-delay: 3420ms;
          animation-delay: 3420ms;
}
.circle-container:nth-child(160) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-160;
          animation-name: move-frames-160;
  -webkit-animation-duration: 32653ms;
          animation-duration: 32653ms;
  -webkit-animation-delay: 27732ms;
          animation-delay: 27732ms;
}
@-webkit-keyframes move-frames-160 {
  from {
    -webkit-transform: translate3d(90vw, 108vh, 0);
            transform: translate3d(90vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -135vh, 0);
            transform: translate3d(67vw, -135vh, 0);
  }
}
@keyframes move-frames-160 {
  from {
    -webkit-transform: translate3d(90vw, 108vh, 0);
            transform: translate3d(90vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -135vh, 0);
            transform: translate3d(67vw, -135vh, 0);
  }
}
.circle-container:nth-child(160) .circle {
  -webkit-animation-delay: 1494ms;
          animation-delay: 1494ms;
}
.circle-container:nth-child(161) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-161;
          animation-name: move-frames-161;
  -webkit-animation-duration: 29116ms;
          animation-duration: 29116ms;
  -webkit-animation-delay: 33787ms;
          animation-delay: 33787ms;
}
@-webkit-keyframes move-frames-161 {
  from {
    -webkit-transform: translate3d(35vw, 106vh, 0);
            transform: translate3d(35vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -117vh, 0);
            transform: translate3d(32vw, -117vh, 0);
  }
}
@keyframes move-frames-161 {
  from {
    -webkit-transform: translate3d(35vw, 106vh, 0);
            transform: translate3d(35vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -117vh, 0);
            transform: translate3d(32vw, -117vh, 0);
  }
}
.circle-container:nth-child(161) .circle {
  -webkit-animation-delay: 27ms;
          animation-delay: 27ms;
}
.circle-container:nth-child(162) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-162;
          animation-name: move-frames-162;
  -webkit-animation-duration: 34879ms;
          animation-duration: 34879ms;
  -webkit-animation-delay: 35187ms;
          animation-delay: 35187ms;
}
@-webkit-keyframes move-frames-162 {
  from {
    -webkit-transform: translate3d(52vw, 106vh, 0);
            transform: translate3d(52vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -135vh, 0);
            transform: translate3d(14vw, -135vh, 0);
  }
}
@keyframes move-frames-162 {
  from {
    -webkit-transform: translate3d(52vw, 106vh, 0);
            transform: translate3d(52vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -135vh, 0);
            transform: translate3d(14vw, -135vh, 0);
  }
}
.circle-container:nth-child(162) .circle {
  -webkit-animation-delay: 2927ms;
          animation-delay: 2927ms;
}
.circle-container:nth-child(163) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-163;
          animation-name: move-frames-163;
  -webkit-animation-duration: 30252ms;
          animation-duration: 30252ms;
  -webkit-animation-delay: 16403ms;
          animation-delay: 16403ms;
}
@-webkit-keyframes move-frames-163 {
  from {
    -webkit-transform: translate3d(8vw, 109vh, 0);
            transform: translate3d(8vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(72vw, -133vh, 0);
            transform: translate3d(72vw, -133vh, 0);
  }
}
@keyframes move-frames-163 {
  from {
    -webkit-transform: translate3d(8vw, 109vh, 0);
            transform: translate3d(8vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(72vw, -133vh, 0);
            transform: translate3d(72vw, -133vh, 0);
  }
}
.circle-container:nth-child(163) .circle {
  -webkit-animation-delay: 499ms;
          animation-delay: 499ms;
}
.circle-container:nth-child(164) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-164;
          animation-name: move-frames-164;
  -webkit-animation-duration: 29844ms;
          animation-duration: 29844ms;
  -webkit-animation-delay: 7432ms;
          animation-delay: 7432ms;
}
@-webkit-keyframes move-frames-164 {
  from {
    -webkit-transform: translate3d(45vw, 110vh, 0);
            transform: translate3d(45vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -132vh, 0);
            transform: translate3d(6vw, -132vh, 0);
  }
}
@keyframes move-frames-164 {
  from {
    -webkit-transform: translate3d(45vw, 110vh, 0);
            transform: translate3d(45vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -132vh, 0);
            transform: translate3d(6vw, -132vh, 0);
  }
}
.circle-container:nth-child(164) .circle {
  -webkit-animation-delay: 1109ms;
          animation-delay: 1109ms;
}
.circle-container:nth-child(165) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-165;
          animation-name: move-frames-165;
  -webkit-animation-duration: 36691ms;
          animation-duration: 36691ms;
  -webkit-animation-delay: 26617ms;
          animation-delay: 26617ms;
}
@-webkit-keyframes move-frames-165 {
  from {
    -webkit-transform: translate3d(99vw, 107vh, 0);
            transform: translate3d(99vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -132vh, 0);
            transform: translate3d(20vw, -132vh, 0);
  }
}
@keyframes move-frames-165 {
  from {
    -webkit-transform: translate3d(99vw, 107vh, 0);
            transform: translate3d(99vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -132vh, 0);
            transform: translate3d(20vw, -132vh, 0);
  }
}
.circle-container:nth-child(165) .circle {
  -webkit-animation-delay: 1325ms;
          animation-delay: 1325ms;
}
.circle-container:nth-child(166) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-166;
          animation-name: move-frames-166;
  -webkit-animation-duration: 29652ms;
          animation-duration: 29652ms;
  -webkit-animation-delay: 30462ms;
          animation-delay: 30462ms;
}
@-webkit-keyframes move-frames-166 {
  from {
    -webkit-transform: translate3d(2vw, 108vh, 0);
            transform: translate3d(2vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(34vw, -134vh, 0);
            transform: translate3d(34vw, -134vh, 0);
  }
}
@keyframes move-frames-166 {
  from {
    -webkit-transform: translate3d(2vw, 108vh, 0);
            transform: translate3d(2vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(34vw, -134vh, 0);
            transform: translate3d(34vw, -134vh, 0);
  }
}
.circle-container:nth-child(166) .circle {
  -webkit-animation-delay: 2147ms;
          animation-delay: 2147ms;
}
.circle-container:nth-child(167) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-167;
          animation-name: move-frames-167;
  -webkit-animation-duration: 33386ms;
          animation-duration: 33386ms;
  -webkit-animation-delay: 2189ms;
          animation-delay: 2189ms;
}
@-webkit-keyframes move-frames-167 {
  from {
    -webkit-transform: translate3d(53vw, 108vh, 0);
            transform: translate3d(53vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -135vh, 0);
            transform: translate3d(12vw, -135vh, 0);
  }
}
@keyframes move-frames-167 {
  from {
    -webkit-transform: translate3d(53vw, 108vh, 0);
            transform: translate3d(53vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -135vh, 0);
            transform: translate3d(12vw, -135vh, 0);
  }
}
.circle-container:nth-child(167) .circle {
  -webkit-animation-delay: 1605ms;
          animation-delay: 1605ms;
}
.circle-container:nth-child(168) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-168;
          animation-name: move-frames-168;
  -webkit-animation-duration: 29621ms;
          animation-duration: 29621ms;
  -webkit-animation-delay: 1095ms;
          animation-delay: 1095ms;
}
@-webkit-keyframes move-frames-168 {
  from {
    -webkit-transform: translate3d(26vw, 110vh, 0);
            transform: translate3d(26vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -123vh, 0);
            transform: translate3d(61vw, -123vh, 0);
  }
}
@keyframes move-frames-168 {
  from {
    -webkit-transform: translate3d(26vw, 110vh, 0);
            transform: translate3d(26vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -123vh, 0);
            transform: translate3d(61vw, -123vh, 0);
  }
}
.circle-container:nth-child(168) .circle {
  -webkit-animation-delay: 1814ms;
          animation-delay: 1814ms;
}
.circle-container:nth-child(169) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-169;
          animation-name: move-frames-169;
  -webkit-animation-duration: 36111ms;
          animation-duration: 36111ms;
  -webkit-animation-delay: 14006ms;
          animation-delay: 14006ms;
}
@-webkit-keyframes move-frames-169 {
  from {
    -webkit-transform: translate3d(89vw, 104vh, 0);
            transform: translate3d(89vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -128vh, 0);
            transform: translate3d(61vw, -128vh, 0);
  }
}
@keyframes move-frames-169 {
  from {
    -webkit-transform: translate3d(89vw, 104vh, 0);
            transform: translate3d(89vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -128vh, 0);
            transform: translate3d(61vw, -128vh, 0);
  }
}
.circle-container:nth-child(169) .circle {
  -webkit-animation-delay: 1306ms;
          animation-delay: 1306ms;
}
.circle-container:nth-child(170) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-170;
          animation-name: move-frames-170;
  -webkit-animation-duration: 30774ms;
          animation-duration: 30774ms;
  -webkit-animation-delay: 25400ms;
          animation-delay: 25400ms;
}
@-webkit-keyframes move-frames-170 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -123vh, 0);
            transform: translate3d(78vw, -123vh, 0);
  }
}
@keyframes move-frames-170 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -123vh, 0);
            transform: translate3d(78vw, -123vh, 0);
  }
}
.circle-container:nth-child(170) .circle {
  -webkit-animation-delay: 1066ms;
          animation-delay: 1066ms;
}
.circle-container:nth-child(171) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-171;
          animation-name: move-frames-171;
  -webkit-animation-duration: 30900ms;
          animation-duration: 30900ms;
  -webkit-animation-delay: 27007ms;
          animation-delay: 27007ms;
}
@-webkit-keyframes move-frames-171 {
  from {
    -webkit-transform: translate3d(23vw, 106vh, 0);
            transform: translate3d(23vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -107vh, 0);
            transform: translate3d(62vw, -107vh, 0);
  }
}
@keyframes move-frames-171 {
  from {
    -webkit-transform: translate3d(23vw, 106vh, 0);
            transform: translate3d(23vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -107vh, 0);
            transform: translate3d(62vw, -107vh, 0);
  }
}
.circle-container:nth-child(171) .circle {
  -webkit-animation-delay: 793ms;
          animation-delay: 793ms;
}
.circle-container:nth-child(172) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-172;
          animation-name: move-frames-172;
  -webkit-animation-duration: 29345ms;
          animation-duration: 29345ms;
  -webkit-animation-delay: 14853ms;
          animation-delay: 14853ms;
}
@-webkit-keyframes move-frames-172 {
  from {
    -webkit-transform: translate3d(31vw, 107vh, 0);
            transform: translate3d(31vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -133vh, 0);
            transform: translate3d(53vw, -133vh, 0);
  }
}
@keyframes move-frames-172 {
  from {
    -webkit-transform: translate3d(31vw, 107vh, 0);
            transform: translate3d(31vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -133vh, 0);
            transform: translate3d(53vw, -133vh, 0);
  }
}
.circle-container:nth-child(172) .circle {
  -webkit-animation-delay: 2077ms;
          animation-delay: 2077ms;
}
.circle-container:nth-child(173) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-173;
          animation-name: move-frames-173;
  -webkit-animation-duration: 36790ms;
          animation-duration: 36790ms;
  -webkit-animation-delay: 9330ms;
          animation-delay: 9330ms;
}
@-webkit-keyframes move-frames-173 {
  from {
    -webkit-transform: translate3d(27vw, 108vh, 0);
            transform: translate3d(27vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -130vh, 0);
            transform: translate3d(67vw, -130vh, 0);
  }
}
@keyframes move-frames-173 {
  from {
    -webkit-transform: translate3d(27vw, 108vh, 0);
            transform: translate3d(27vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -130vh, 0);
            transform: translate3d(67vw, -130vh, 0);
  }
}
.circle-container:nth-child(173) .circle {
  -webkit-animation-delay: 3267ms;
          animation-delay: 3267ms;
}
.circle-container:nth-child(174) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-174;
          animation-name: move-frames-174;
  -webkit-animation-duration: 30160ms;
          animation-duration: 30160ms;
  -webkit-animation-delay: 1028ms;
          animation-delay: 1028ms;
}
@-webkit-keyframes move-frames-174 {
  from {
    -webkit-transform: translate3d(34vw, 109vh, 0);
            transform: translate3d(34vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -121vh, 0);
            transform: translate3d(49vw, -121vh, 0);
  }
}
@keyframes move-frames-174 {
  from {
    -webkit-transform: translate3d(34vw, 109vh, 0);
            transform: translate3d(34vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -121vh, 0);
            transform: translate3d(49vw, -121vh, 0);
  }
}
.circle-container:nth-child(174) .circle {
  -webkit-animation-delay: 3485ms;
          animation-delay: 3485ms;
}
.circle-container:nth-child(175) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-175;
          animation-name: move-frames-175;
  -webkit-animation-duration: 28238ms;
          animation-duration: 28238ms;
  -webkit-animation-delay: 10107ms;
          animation-delay: 10107ms;
}
@-webkit-keyframes move-frames-175 {
  from {
    -webkit-transform: translate3d(24vw, 108vh, 0);
            transform: translate3d(24vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -131vh, 0);
            transform: translate3d(53vw, -131vh, 0);
  }
}
@keyframes move-frames-175 {
  from {
    -webkit-transform: translate3d(24vw, 108vh, 0);
            transform: translate3d(24vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -131vh, 0);
            transform: translate3d(53vw, -131vh, 0);
  }
}
.circle-container:nth-child(175) .circle {
  -webkit-animation-delay: 3403ms;
          animation-delay: 3403ms;
}
.circle-container:nth-child(176) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-176;
          animation-name: move-frames-176;
  -webkit-animation-duration: 34994ms;
          animation-duration: 34994ms;
  -webkit-animation-delay: 9024ms;
          animation-delay: 9024ms;
}
@-webkit-keyframes move-frames-176 {
  from {
    -webkit-transform: translate3d(26vw, 108vh, 0);
            transform: translate3d(26vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(40vw, -136vh, 0);
            transform: translate3d(40vw, -136vh, 0);
  }
}
@keyframes move-frames-176 {
  from {
    -webkit-transform: translate3d(26vw, 108vh, 0);
            transform: translate3d(26vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(40vw, -136vh, 0);
            transform: translate3d(40vw, -136vh, 0);
  }
}
.circle-container:nth-child(176) .circle {
  -webkit-animation-delay: 3085ms;
          animation-delay: 3085ms;
}
.circle-container:nth-child(177) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-177;
          animation-name: move-frames-177;
  -webkit-animation-duration: 35892ms;
          animation-duration: 35892ms;
  -webkit-animation-delay: 34632ms;
          animation-delay: 34632ms;
}
@-webkit-keyframes move-frames-177 {
  from {
    -webkit-transform: translate3d(60vw, 101vh, 0);
            transform: translate3d(60vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -110vh, 0);
            transform: translate3d(44vw, -110vh, 0);
  }
}
@keyframes move-frames-177 {
  from {
    -webkit-transform: translate3d(60vw, 101vh, 0);
            transform: translate3d(60vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -110vh, 0);
            transform: translate3d(44vw, -110vh, 0);
  }
}
.circle-container:nth-child(177) .circle {
  -webkit-animation-delay: 244ms;
          animation-delay: 244ms;
}
.circle-container:nth-child(178) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-178;
          animation-name: move-frames-178;
  -webkit-animation-duration: 33566ms;
          animation-duration: 33566ms;
  -webkit-animation-delay: 15031ms;
          animation-delay: 15031ms;
}
@-webkit-keyframes move-frames-178 {
  from {
    -webkit-transform: translate3d(68vw, 106vh, 0);
            transform: translate3d(68vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(89vw, -136vh, 0);
            transform: translate3d(89vw, -136vh, 0);
  }
}
@keyframes move-frames-178 {
  from {
    -webkit-transform: translate3d(68vw, 106vh, 0);
            transform: translate3d(68vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(89vw, -136vh, 0);
            transform: translate3d(89vw, -136vh, 0);
  }
}
.circle-container:nth-child(178) .circle {
  -webkit-animation-delay: 1126ms;
          animation-delay: 1126ms;
}
.circle-container:nth-child(179) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-179;
          animation-name: move-frames-179;
  -webkit-animation-duration: 31253ms;
          animation-duration: 31253ms;
  -webkit-animation-delay: 34450ms;
          animation-delay: 34450ms;
}
@-webkit-keyframes move-frames-179 {
  from {
    -webkit-transform: translate3d(44vw, 106vh, 0);
            transform: translate3d(44vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -127vh, 0);
            transform: translate3d(54vw, -127vh, 0);
  }
}
@keyframes move-frames-179 {
  from {
    -webkit-transform: translate3d(44vw, 106vh, 0);
            transform: translate3d(44vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -127vh, 0);
            transform: translate3d(54vw, -127vh, 0);
  }
}
.circle-container:nth-child(179) .circle {
  -webkit-animation-delay: 2556ms;
          animation-delay: 2556ms;
}
.circle-container:nth-child(180) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-180;
          animation-name: move-frames-180;
  -webkit-animation-duration: 35587ms;
          animation-duration: 35587ms;
  -webkit-animation-delay: 32096ms;
          animation-delay: 32096ms;
}
@-webkit-keyframes move-frames-180 {
  from {
    -webkit-transform: translate3d(18vw, 110vh, 0);
            transform: translate3d(18vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(96vw, -136vh, 0);
            transform: translate3d(96vw, -136vh, 0);
  }
}
@keyframes move-frames-180 {
  from {
    -webkit-transform: translate3d(18vw, 110vh, 0);
            transform: translate3d(18vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(96vw, -136vh, 0);
            transform: translate3d(96vw, -136vh, 0);
  }
}
.circle-container:nth-child(180) .circle {
  -webkit-animation-delay: 2928ms;
          animation-delay: 2928ms;
}
.circle-container:nth-child(181) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-181;
          animation-name: move-frames-181;
  -webkit-animation-duration: 29684ms;
          animation-duration: 29684ms;
  -webkit-animation-delay: 6739ms;
          animation-delay: 6739ms;
}
@-webkit-keyframes move-frames-181 {
  from {
    -webkit-transform: translate3d(98vw, 104vh, 0);
            transform: translate3d(98vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -112vh, 0);
            transform: translate3d(81vw, -112vh, 0);
  }
}
@keyframes move-frames-181 {
  from {
    -webkit-transform: translate3d(98vw, 104vh, 0);
            transform: translate3d(98vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -112vh, 0);
            transform: translate3d(81vw, -112vh, 0);
  }
}
.circle-container:nth-child(181) .circle {
  -webkit-animation-delay: 2145ms;
          animation-delay: 2145ms;
}
.circle-container:nth-child(182) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-182;
          animation-name: move-frames-182;
  -webkit-animation-duration: 34049ms;
          animation-duration: 34049ms;
  -webkit-animation-delay: 24752ms;
          animation-delay: 24752ms;
}
@-webkit-keyframes move-frames-182 {
  from {
    -webkit-transform: translate3d(94vw, 106vh, 0);
            transform: translate3d(94vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -134vh, 0);
            transform: translate3d(44vw, -134vh, 0);
  }
}
@keyframes move-frames-182 {
  from {
    -webkit-transform: translate3d(94vw, 106vh, 0);
            transform: translate3d(94vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -134vh, 0);
            transform: translate3d(44vw, -134vh, 0);
  }
}
.circle-container:nth-child(182) .circle {
  -webkit-animation-delay: 2551ms;
          animation-delay: 2551ms;
}
.circle-container:nth-child(183) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-183;
          animation-name: move-frames-183;
  -webkit-animation-duration: 35515ms;
          animation-duration: 35515ms;
  -webkit-animation-delay: 11041ms;
          animation-delay: 11041ms;
}
@-webkit-keyframes move-frames-183 {
  from {
    -webkit-transform: translate3d(16vw, 103vh, 0);
            transform: translate3d(16vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(76vw, -105vh, 0);
            transform: translate3d(76vw, -105vh, 0);
  }
}
@keyframes move-frames-183 {
  from {
    -webkit-transform: translate3d(16vw, 103vh, 0);
            transform: translate3d(16vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(76vw, -105vh, 0);
            transform: translate3d(76vw, -105vh, 0);
  }
}
.circle-container:nth-child(183) .circle {
  -webkit-animation-delay: 788ms;
          animation-delay: 788ms;
}
.circle-container:nth-child(184) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-184;
          animation-name: move-frames-184;
  -webkit-animation-duration: 33201ms;
          animation-duration: 33201ms;
  -webkit-animation-delay: 11834ms;
          animation-delay: 11834ms;
}
@-webkit-keyframes move-frames-184 {
  from {
    -webkit-transform: translate3d(42vw, 110vh, 0);
            transform: translate3d(42vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(71vw, -126vh, 0);
            transform: translate3d(71vw, -126vh, 0);
  }
}
@keyframes move-frames-184 {
  from {
    -webkit-transform: translate3d(42vw, 110vh, 0);
            transform: translate3d(42vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(71vw, -126vh, 0);
            transform: translate3d(71vw, -126vh, 0);
  }
}
.circle-container:nth-child(184) .circle {
  -webkit-animation-delay: 3544ms;
          animation-delay: 3544ms;
}
.circle-container:nth-child(185) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-185;
          animation-name: move-frames-185;
  -webkit-animation-duration: 34807ms;
          animation-duration: 34807ms;
  -webkit-animation-delay: 789ms;
          animation-delay: 789ms;
}
@-webkit-keyframes move-frames-185 {
  from {
    -webkit-transform: translate3d(13vw, 104vh, 0);
            transform: translate3d(13vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -122vh, 0);
            transform: translate3d(16vw, -122vh, 0);
  }
}
@keyframes move-frames-185 {
  from {
    -webkit-transform: translate3d(13vw, 104vh, 0);
            transform: translate3d(13vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -122vh, 0);
            transform: translate3d(16vw, -122vh, 0);
  }
}
.circle-container:nth-child(185) .circle {
  -webkit-animation-delay: 779ms;
          animation-delay: 779ms;
}
.circle-container:nth-child(186) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-186;
          animation-name: move-frames-186;
  -webkit-animation-duration: 28085ms;
          animation-duration: 28085ms;
  -webkit-animation-delay: 20882ms;
          animation-delay: 20882ms;
}
@-webkit-keyframes move-frames-186 {
  from {
    -webkit-transform: translate3d(73vw, 105vh, 0);
            transform: translate3d(73vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(68vw, -125vh, 0);
            transform: translate3d(68vw, -125vh, 0);
  }
}
@keyframes move-frames-186 {
  from {
    -webkit-transform: translate3d(73vw, 105vh, 0);
            transform: translate3d(73vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(68vw, -125vh, 0);
            transform: translate3d(68vw, -125vh, 0);
  }
}
.circle-container:nth-child(186) .circle {
  -webkit-animation-delay: 2104ms;
          animation-delay: 2104ms;
}
.circle-container:nth-child(187) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-187;
          animation-name: move-frames-187;
  -webkit-animation-duration: 32274ms;
          animation-duration: 32274ms;
  -webkit-animation-delay: 3587ms;
          animation-delay: 3587ms;
}
@-webkit-keyframes move-frames-187 {
  from {
    -webkit-transform: translate3d(69vw, 109vh, 0);
            transform: translate3d(69vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(64vw, -111vh, 0);
            transform: translate3d(64vw, -111vh, 0);
  }
}
@keyframes move-frames-187 {
  from {
    -webkit-transform: translate3d(69vw, 109vh, 0);
            transform: translate3d(69vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(64vw, -111vh, 0);
            transform: translate3d(64vw, -111vh, 0);
  }
}
.circle-container:nth-child(187) .circle {
  -webkit-animation-delay: 3247ms;
          animation-delay: 3247ms;
}
.circle-container:nth-child(188) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-188;
          animation-name: move-frames-188;
  -webkit-animation-duration: 33250ms;
          animation-duration: 33250ms;
  -webkit-animation-delay: 13784ms;
          animation-delay: 13784ms;
}
@-webkit-keyframes move-frames-188 {
  from {
    -webkit-transform: translate3d(29vw, 101vh, 0);
            transform: translate3d(29vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -113vh, 0);
            transform: translate3d(74vw, -113vh, 0);
  }
}
@keyframes move-frames-188 {
  from {
    -webkit-transform: translate3d(29vw, 101vh, 0);
            transform: translate3d(29vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -113vh, 0);
            transform: translate3d(74vw, -113vh, 0);
  }
}
.circle-container:nth-child(188) .circle {
  -webkit-animation-delay: 1798ms;
          animation-delay: 1798ms;
}
.circle-container:nth-child(189) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-189;
          animation-name: move-frames-189;
  -webkit-animation-duration: 30514ms;
          animation-duration: 30514ms;
  -webkit-animation-delay: 2212ms;
          animation-delay: 2212ms;
}
@-webkit-keyframes move-frames-189 {
  from {
    -webkit-transform: translate3d(70vw, 106vh, 0);
            transform: translate3d(70vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -122vh, 0);
            transform: translate3d(57vw, -122vh, 0);
  }
}
@keyframes move-frames-189 {
  from {
    -webkit-transform: translate3d(70vw, 106vh, 0);
            transform: translate3d(70vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -122vh, 0);
            transform: translate3d(57vw, -122vh, 0);
  }
}
.circle-container:nth-child(189) .circle {
  -webkit-animation-delay: 3104ms;
          animation-delay: 3104ms;
}
.circle-container:nth-child(190) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-190;
          animation-name: move-frames-190;
  -webkit-animation-duration: 33369ms;
          animation-duration: 33369ms;
  -webkit-animation-delay: 476ms;
          animation-delay: 476ms;
}
@-webkit-keyframes move-frames-190 {
  from {
    -webkit-transform: translate3d(93vw, 106vh, 0);
            transform: translate3d(93vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(27vw, -124vh, 0);
            transform: translate3d(27vw, -124vh, 0);
  }
}
@keyframes move-frames-190 {
  from {
    -webkit-transform: translate3d(93vw, 106vh, 0);
            transform: translate3d(93vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(27vw, -124vh, 0);
            transform: translate3d(27vw, -124vh, 0);
  }
}
.circle-container:nth-child(190) .circle {
  -webkit-animation-delay: 572ms;
          animation-delay: 572ms;
}
.circle-container:nth-child(191) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-191;
          animation-name: move-frames-191;
  -webkit-animation-duration: 29433ms;
          animation-duration: 29433ms;
  -webkit-animation-delay: 7587ms;
          animation-delay: 7587ms;
}
@-webkit-keyframes move-frames-191 {
  from {
    -webkit-transform: translate3d(33vw, 106vh, 0);
            transform: translate3d(33vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -125vh, 0);
            transform: translate3d(51vw, -125vh, 0);
  }
}
@keyframes move-frames-191 {
  from {
    -webkit-transform: translate3d(33vw, 106vh, 0);
            transform: translate3d(33vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -125vh, 0);
            transform: translate3d(51vw, -125vh, 0);
  }
}
.circle-container:nth-child(191) .circle {
  -webkit-animation-delay: 1959ms;
          animation-delay: 1959ms;
}
.circle-container:nth-child(192) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-192;
          animation-name: move-frames-192;
  -webkit-animation-duration: 29060ms;
          animation-duration: 29060ms;
  -webkit-animation-delay: 4017ms;
          animation-delay: 4017ms;
}
@-webkit-keyframes move-frames-192 {
  from {
    -webkit-transform: translate3d(36vw, 109vh, 0);
            transform: translate3d(36vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(58vw, -111vh, 0);
            transform: translate3d(58vw, -111vh, 0);
  }
}
@keyframes move-frames-192 {
  from {
    -webkit-transform: translate3d(36vw, 109vh, 0);
            transform: translate3d(36vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(58vw, -111vh, 0);
            transform: translate3d(58vw, -111vh, 0);
  }
}
.circle-container:nth-child(192) .circle {
  -webkit-animation-delay: 566ms;
          animation-delay: 566ms;
}
.circle-container:nth-child(193) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-193;
          animation-name: move-frames-193;
  -webkit-animation-duration: 29178ms;
          animation-duration: 29178ms;
  -webkit-animation-delay: 36223ms;
          animation-delay: 36223ms;
}
@-webkit-keyframes move-frames-193 {
  from {
    -webkit-transform: translate3d(94vw, 109vh, 0);
            transform: translate3d(94vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -119vh, 0);
            transform: translate3d(13vw, -119vh, 0);
  }
}
@keyframes move-frames-193 {
  from {
    -webkit-transform: translate3d(94vw, 109vh, 0);
            transform: translate3d(94vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -119vh, 0);
            transform: translate3d(13vw, -119vh, 0);
  }
}
.circle-container:nth-child(193) .circle {
  -webkit-animation-delay: 450ms;
          animation-delay: 450ms;
}
.circle-container:nth-child(194) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-194;
          animation-name: move-frames-194;
  -webkit-animation-duration: 32982ms;
          animation-duration: 32982ms;
  -webkit-animation-delay: 20650ms;
          animation-delay: 20650ms;
}
@-webkit-keyframes move-frames-194 {
  from {
    -webkit-transform: translate3d(55vw, 103vh, 0);
            transform: translate3d(55vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -119vh, 0);
            transform: translate3d(20vw, -119vh, 0);
  }
}
@keyframes move-frames-194 {
  from {
    -webkit-transform: translate3d(55vw, 103vh, 0);
            transform: translate3d(55vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -119vh, 0);
            transform: translate3d(20vw, -119vh, 0);
  }
}
.circle-container:nth-child(194) .circle {
  -webkit-animation-delay: 478ms;
          animation-delay: 478ms;
}
.circle-container:nth-child(195) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-195;
          animation-name: move-frames-195;
  -webkit-animation-duration: 32615ms;
          animation-duration: 32615ms;
  -webkit-animation-delay: 29709ms;
          animation-delay: 29709ms;
}
@-webkit-keyframes move-frames-195 {
  from {
    -webkit-transform: translate3d(87vw, 102vh, 0);
            transform: translate3d(87vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(46vw, -123vh, 0);
            transform: translate3d(46vw, -123vh, 0);
  }
}
@keyframes move-frames-195 {
  from {
    -webkit-transform: translate3d(87vw, 102vh, 0);
            transform: translate3d(87vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(46vw, -123vh, 0);
            transform: translate3d(46vw, -123vh, 0);
  }
}
.circle-container:nth-child(195) .circle {
  -webkit-animation-delay: 302ms;
          animation-delay: 302ms;
}
.circle-container:nth-child(196) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-196;
          animation-name: move-frames-196;
  -webkit-animation-duration: 30692ms;
          animation-duration: 30692ms;
  -webkit-animation-delay: 34524ms;
          animation-delay: 34524ms;
}
@-webkit-keyframes move-frames-196 {
  from {
    -webkit-transform: translate3d(57vw, 106vh, 0);
            transform: translate3d(57vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -119vh, 0);
            transform: translate3d(16vw, -119vh, 0);
  }
}
@keyframes move-frames-196 {
  from {
    -webkit-transform: translate3d(57vw, 106vh, 0);
            transform: translate3d(57vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -119vh, 0);
            transform: translate3d(16vw, -119vh, 0);
  }
}
.circle-container:nth-child(196) .circle {
  -webkit-animation-delay: 3409ms;
          animation-delay: 3409ms;
}
.circle-container:nth-child(197) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-197;
          animation-name: move-frames-197;
  -webkit-animation-duration: 32652ms;
          animation-duration: 32652ms;
  -webkit-animation-delay: 12741ms;
          animation-delay: 12741ms;
}
@-webkit-keyframes move-frames-197 {
  from {
    -webkit-transform: translate3d(56vw, 104vh, 0);
            transform: translate3d(56vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(83vw, -131vh, 0);
            transform: translate3d(83vw, -131vh, 0);
  }
}
@keyframes move-frames-197 {
  from {
    -webkit-transform: translate3d(56vw, 104vh, 0);
            transform: translate3d(56vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(83vw, -131vh, 0);
            transform: translate3d(83vw, -131vh, 0);
  }
}
.circle-container:nth-child(197) .circle {
  -webkit-animation-delay: 2214ms;
          animation-delay: 2214ms;
}
.circle-container:nth-child(198) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-198;
          animation-name: move-frames-198;
  -webkit-animation-duration: 34472ms;
          animation-duration: 34472ms;
  -webkit-animation-delay: 32516ms;
          animation-delay: 32516ms;
}
@-webkit-keyframes move-frames-198 {
  from {
    -webkit-transform: translate3d(63vw, 103vh, 0);
            transform: translate3d(63vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -111vh, 0);
            transform: translate3d(81vw, -111vh, 0);
  }
}
@keyframes move-frames-198 {
  from {
    -webkit-transform: translate3d(63vw, 103vh, 0);
            transform: translate3d(63vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -111vh, 0);
            transform: translate3d(81vw, -111vh, 0);
  }
}
.circle-container:nth-child(198) .circle {
  -webkit-animation-delay: 3945ms;
          animation-delay: 3945ms;
}
.circle-container:nth-child(199) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-199;
          animation-name: move-frames-199;
  -webkit-animation-duration: 29933ms;
          animation-duration: 29933ms;
  -webkit-animation-delay: 9713ms;
          animation-delay: 9713ms;
}
@-webkit-keyframes move-frames-199 {
  from {
    -webkit-transform: translate3d(88vw, 102vh, 0);
            transform: translate3d(88vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(89vw, -111vh, 0);
            transform: translate3d(89vw, -111vh, 0);
  }
}
@keyframes move-frames-199 {
  from {
    -webkit-transform: translate3d(88vw, 102vh, 0);
            transform: translate3d(88vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(89vw, -111vh, 0);
            transform: translate3d(89vw, -111vh, 0);
  }
}
.circle-container:nth-child(199) .circle {
  -webkit-animation-delay: 3054ms;
          animation-delay: 3054ms;
}
.circle-container:nth-child(200) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-200;
          animation-name: move-frames-200;
  -webkit-animation-duration: 35459ms;
          animation-duration: 35459ms;
  -webkit-animation-delay: 8483ms;
          animation-delay: 8483ms;
}
@-webkit-keyframes move-frames-200 {
  from {
    -webkit-transform: translate3d(91vw, 101vh, 0);
            transform: translate3d(91vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -125vh, 0);
            transform: translate3d(43vw, -125vh, 0);
  }
}
@keyframes move-frames-200 {
  from {
    -webkit-transform: translate3d(91vw, 101vh, 0);
            transform: translate3d(91vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -125vh, 0);
            transform: translate3d(43vw, -125vh, 0);
  }
}
.circle-container:nth-child(200) .circle {
  -webkit-animation-delay: 840ms;
          animation-delay: 840ms;
}

.message {
  position: absolute;
  right: 20px;
  bottom: 10px;
  color: white;
  font-family: "Josefin Slab", serif;
  line-height: 27px;
  font-size: 18px;
  text-align: right;
  pointer-events: none;
  -webkit-animation: message-frames 1.5s ease 5s forwards;
          animation: message-frames 1.5s ease 5s forwards;
  opacity: 0;
}
@-webkit-keyframes message-frames {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@keyframes message-frames {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
