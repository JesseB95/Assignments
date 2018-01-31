# Assignments
Assignments for Applied Economic Analysis 1

<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<title>FinalPython</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
[dir="rtl"] #ipython_notebook {
  float: right !important;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
[dir="rtl"] #tabs li {
  float: right;
}
ul#tabs {
  margin-bottom: 4px;
}
[dir="rtl"] ul#tabs {
  margin-right: 0px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons {
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-right {
  padding-top: 1px;
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-left {
  float: right !important;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
[dir="rtl"] #tree-selector a {
  float: right;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
[dir="rtl"] #new-menu {
  text-align: right;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
[dir="rtl"] #running .col-sm-8 {
  float: right !important;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}

@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='Boven'></a></p>
<h1 id="Global-Value-Chains:-NAFTA">Global Value Chains: NAFTA<a class="anchor-link" href="#Global-Value-Chains:-NAFTA">&#182;</a></h1><table>
<thead><tr>
<th>Name</th>
<th>examnr.</th>
</tr>
</thead>
<tbody>
<tr>
<td>Adelina Sharipova</td>
<td>2018931</td>
</tr>
<tr>
<td>Jesse Bijnen</td>
<td>1258985</td>
</tr>
</tbody>
</table>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Table-of-Contents">Table of Contents<a class="anchor-link" href="#Table-of-Contents">&#182;</a></h1><p><a href="#Introduction">1. Introduction</a></p>
<p><a href="#Terminology_and_concepts">2. Terminology and Concepts</a></p>
<p><a href="#Global_Value_Chains_and_World_Input_Output_Tables">2.1 Global Value Chains and World Input Output Tables</a></p>
<p><a href="#NAFTA_and_Standardization">2.2 NAFTA and Standardization</a></p>
<p><a href="#Input_-_Outputanalysis">3. Input Outputanalysis</a></p>
<p><a href="#Regional_Trade_Flows_in_Intermediate_Manufacturing_Goods">3.1 Regional Trade Flows in Intermediate Manufacturing Goods</a></p>
<p><a href="#North_American_Global_Chain">3.2 North American Global Value Chain</a>
<a href='#Introduction'>1. Introduction</a>&lt;/pre&gt;</p>
<p><a href='#Terminology_and_concepts'>2. Terminology and concepts</a>&lt;/pre&gt;</p>
<p><pre><a href='#GVC'>2.1. Global Value Chains and World Input-Output Tables</a> </pre></p>
<p><pre><a href='#NAFTA'>2.2. NAFTA and Standardization</a></pre>
<a href='#InputOutput'>3. Input-Output Analysis</a>&lt;/pre&gt;</p>
<p><pre><a href='#Regional'>3.1 Regional Trade Flows in Intermediate Manufacturing Goods </a></pre></p>
<p><pre><a href='#NAGVC'>3.2 North American Global Value Chain</a></pre>
<a href='#RCA'>4. Relation to Revealed Comparative Advantage</a></p>
<p><a href='#Conclusion'>5. Conclusion</a></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Research-question">Research question<a class="anchor-link" href="#Research-question">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Can we identify a North-American value chain, and if yes, what role did NAFTA play in the realization of this regional value chain?</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='Introduction'></a></p>
<h2 id="1-Introduction">1 Introduction<a class="anchor-link" href="#1-Introduction">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>More than half of the global exports manufactured imports are intermediate goods (primary goods, parts and components, and semi-finished products), and more than 70 percent of world services imports are intermediate goods <a href="https://www.ecb.europa.eu/pub/pdf/scpwps/ecbwp1677.pdf?11ce331dcdb55ca6ba38f8b0c288c4a4">(De Backer and Miroudot, 2013)</a> . These products within world production and world trade fall under “global value chains” (GVCs), where the different stages of the production (and trade) process are located across different countries <a href="http://www.oecd.org/sti/ind/global-value-chains.htm">(OECD)</a>. The GVCs are production chains where every step of the production process adds a certain value to the product.</p>
<p>The most important feature of the GVCs is that companies restructure their operations internationally, so that the dispersion of value chain activities is located across different countries. <a href="http://www.nber.org/papers/w18957">Baldwin and Lopez-Gonzalez (2014)</a> show that the GVCs are not spread globally, as they are spread more regionally. The authors argue that there is a distinctive European, Asian and North-American value chain, that is concentrated respectively around Germany, Japan and the United States (US). This is the motivation behind this research project: we want to analyze the existence of the (regional) North-American value chain and its evolution through time. Furthermore, we investigate whether or not the North American Free Trade Agreement (NAFTA) has played an important role. The research question of this project is: can we identify a North-American value chain, and if yes, what role did NAFTA play in the realization of this regional value chain?</p>
<p>The methodology to answer the research question is mainly an input-output analysis, from the World Input-Output Database  <a href="http://onlinelibrary.wiley.com/doi/10.1111/roie.12178/epdf">(WIOD, 2015)</a>. Because NAFTA originated in 1994, we analyse the trade evolution from 1995 to 2015. In this paper we will solemnly focus on intermediate trade flows of goods from manufacturing, because these are the main components of any GVC.</p>
<p>We start in the next section by a short terminology and explanation of some concepts. Next, we present the actual input-output analysis for 1995 and for 2011. Thereby we are interested in what kind of products (from which sectors) are being traded within the GVC context, and how the individual North-American countries relate to one another. Lastly, we look whether or not the found results match with the evolution of the Revealed Comparative Advantage (RCA) index. But first, let us take a quick look at what NAFTA stands for.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">IPython.display</span> <span class="k">import</span> <span class="n">YouTubeVideo</span>

<span class="n">YouTubeVideo</span><span class="p">(</span><span class="s1">&#39;DwKR08t5BGA&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[1]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">

        <iframe
            width="400"
            height="300"
            src="https://www.youtube.com/embed/DwKR08t5BGA"
            frameborder="0"
            allowfullscreen
        ></iframe>
        
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='Terminology_and_concepts'></a></p>
<h2 id="2-Terminology-and-concepts">2 Terminology and concepts<a class="anchor-link" href="#2-Terminology-and-concepts">&#182;</a></h2><p><a id='GVC'></a></p>
<h3 id="2.1-Global-Value-Chains-and-World-Input-Output-Tables">2.1 Global Value Chains and World Input Output Tables<a class="anchor-link" href="#2.1-Global-Value-Chains-and-World-Input-Output-Tables">&#182;</a></h3><p>GVCs split the production process into separate phases and spread those across different countries. The rise of the GVCs is characterized by the strong globalisation in the past decades of foreign direct investments, trade and manufacturing <a href="http://hdl.handle.net/11540/286">(Felipe, 2012)</a>. Typical for the GVCs is the vertical supply chain structure, where different vertical steps of the production process are geographically separated from each other.</p>
<p>The GVCs connect consumers in developed countries with low skilled labor force in the developing countries. Mostly, the developed countries outsource the parts of the production process that require relatively more low skilled labor to the developing countries. Consecutively, they focus then on the parts that require relatively more of the high skilled labor.  This way, there develops a divergence between the headquarters economies that focus on core businesses and manufacturing economies that focus on partly fabricating the by them imported intermediate inputs. After the outsourcing of those low skilled labor intensive production steps, the developed countries re-import the partly fabricated intermediate inputs, where the value added by the developing countries is not very large. The next step of the production process by the developed countries is the completion of the manufactured goods. The re-imports by the developed countries are the re-exports by the developing countries and are thus the opposite of each other.</p>
<p>To detect the presence and to analyze the characteristics of the North-American value chain we use the world input-output tables by  <a href="http://onlinelibrary.wiley.com/doi/10.1111/roie.12178/epdf">(WIOD, 2015)</a>. Such a table gives us the quantities of the inputs in different countries and from which sectors these come from. Rows show us how the output of a sector is divided between the intermediate inputs from other sectors and from the final consumption. The columns represent the quantities of the intermediate inputs from other sectors. Shortly put, input-outputtables prove the state of the interdependence between the production in different countries and different sectors.</p>
<p><a id='NAFTA'></a></p>
<h3 id="2.2-NAFTA-and-Standardization">2.2 NAFTA and Standardization<a class="anchor-link" href="#2.2-NAFTA-and-Standardization">&#182;</a></h3><p>As the introductory video already mentioned, NAFTA is an agreement between Canada, Mexico and the US, introducing a free trade zone between the countries. The main goal is to facilitate trade by mutually importing and exporting goods. The agreement in 1994 eliminated almost all tariff barriers and a lot of  non-tariff barriers. An important component of the NAFTA agreement are the rules on standardization. Specifically that brought harmonisation of productstandards and mutual quality controles. The thought behind this standardization is to bring parallel standards to the markets and to ease this way the trade between the countries.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='InputOutput'></a></p>
<h2 id="3-Input-Outputanalysis">3 Input Outputanalysis<a class="anchor-link" href="#3-Input-Outputanalysis">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Historically, the three partner countries have known a big increase in trade (see the interactive map here below).</p>
<p>For the actual analysis of the GVC in North-America, we are using the data from the World Input-Output Tables from 1995 to 2011 (the latest release from 2013 for the period 1995-2011 with the same classification according to the International Standard Industrial Classification revision 3, ISIC Rev. 3).</p>
<p>Firstly, we will observe the internal trade flows within the three countries (Canada, US and Mexico). This is a descriptive part of the analysis, because we only focus on the trade flows in intermediate manufacturing goods between these countries mutually and versus the world. I.e. we look at how much they trade in manufacturing intermediate products with each other, both for 1995 and 2011.</p>
<p>Secondly, we compute the actual GVC for the three countries by calculating the bilateral re-exports for each country. This is a necessary step to look at the evolution of the trade flows between the three countries and to pin down the regional North-American value chain. After that, we can conclude what role NAFTA played in the regional value chain.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[27]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">plotly</span>
<span class="n">plotly</span><span class="o">.</span><span class="n">tools</span><span class="o">.</span><span class="n">set_credentials_file</span><span class="p">(</span><span class="n">username</span><span class="o">=</span> <span class="s1">&#39;adelina1789&#39;</span><span class="p">,</span> <span class="n">api_key</span><span class="o">=</span> <span class="s1">&#39;Nx5SiPRVHGivzzFIjcnL&#39;</span><span class="p">)</span>
<span class="kn">import</span> <span class="nn">plotly.plotly</span> <span class="k">as</span> <span class="nn">py</span>
<span class="kn">import</span> <span class="nn">plotly.graph_objs</span> <span class="k">as</span> <span class="nn">go</span>

<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">math</span>

<span class="n">dataExp</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;Exports (p of GDP).csv&quot;</span><span class="p">,</span> <span class="n">delimiter</span> <span class="o">=</span> <span class="s1">&#39;,&#39;</span><span class="p">)</span>
<span class="n">dataImp</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;Imports (p of GDP).csv&quot;</span><span class="p">,</span> <span class="n">delimiter</span> <span class="o">=</span> <span class="s1">&#39;;&#39;</span><span class="p">)</span>


<span class="n">dataExp</span> <span class="o">=</span> <span class="n">dataExp</span><span class="o">.</span><span class="n">sort_values</span><span class="p">([</span><span class="s1">&#39;Year&#39;</span><span class="p">,</span> <span class="s1">&#39;Country&#39;</span><span class="p">])</span>
<span class="n">dataImp</span> <span class="o">=</span> <span class="n">dataImp</span><span class="o">.</span><span class="n">sort_values</span><span class="p">([</span><span class="s1">&#39;Year&#39;</span><span class="p">,</span> <span class="s1">&#39;Country&#39;</span><span class="p">])</span>

<span class="n">trace0</span> <span class="o">=</span> <span class="n">go</span><span class="o">.</span><span class="n">Scatter</span><span class="p">(</span>
    <span class="n">x</span><span class="o">=</span><span class="n">dataImp</span><span class="p">[</span><span class="s1">&#39;Imports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">][</span><span class="n">dataImp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Canada&#39;</span><span class="p">],</span>
    <span class="n">y</span><span class="o">=</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Exports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">][</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Canada&#39;</span><span class="p">],</span>
    <span class="n">mode</span><span class="o">=</span><span class="s1">&#39;markers&#39;</span><span class="p">,</span>
    <span class="n">name</span><span class="o">=</span><span class="s1">&#39;Canada&#39;</span><span class="p">,</span>
    <span class="n">text</span><span class="o">=</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">][</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Canada&#39;</span><span class="p">],</span>
    <span class="n">marker</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
        <span class="n">symbol</span><span class="o">=</span><span class="s1">&#39;circle&#39;</span><span class="p">,</span>
        <span class="n">sizemode</span><span class="o">=</span><span class="s1">&#39;area&#39;</span><span class="p">,</span>
        <span class="n">sizeref</span><span class="o">=</span> <span class="mi">2</span><span class="p">,</span>
        <span class="n">size</span><span class="o">=</span><span class="mi">10</span><span class="p">,</span>
        <span class="n">line</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
            <span class="n">width</span><span class="o">=</span><span class="mi">2</span>
        <span class="p">),</span>
    <span class="p">)</span>
<span class="p">)</span>

<span class="n">trace1</span> <span class="o">=</span> <span class="n">go</span><span class="o">.</span><span class="n">Scatter</span><span class="p">(</span>
    <span class="n">x</span><span class="o">=</span><span class="n">dataImp</span><span class="p">[</span><span class="s1">&#39;Imports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">][</span><span class="n">dataImp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Mexico&#39;</span><span class="p">],</span>
    <span class="n">y</span><span class="o">=</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Exports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">][</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Mexico&#39;</span><span class="p">],</span>
    <span class="n">mode</span><span class="o">=</span><span class="s1">&#39;markers&#39;</span><span class="p">,</span>
    <span class="n">name</span><span class="o">=</span><span class="s1">&#39;Mexico&#39;</span><span class="p">,</span>
    <span class="n">text</span><span class="o">=</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">][</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Mexico&#39;</span><span class="p">],</span>
    <span class="n">marker</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
        <span class="n">symbol</span><span class="o">=</span><span class="s1">&#39;circle&#39;</span><span class="p">,</span>
        <span class="n">sizemode</span><span class="o">=</span><span class="s1">&#39;area&#39;</span><span class="p">,</span>
        <span class="n">sizeref</span><span class="o">=</span> <span class="mi">2</span><span class="p">,</span>
        <span class="n">size</span><span class="o">=</span><span class="mi">10</span><span class="p">,</span>
        <span class="n">line</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
            <span class="n">width</span><span class="o">=</span><span class="mi">2</span>
        <span class="p">),</span>
    <span class="p">)</span>
<span class="p">)</span>

<span class="n">trace2</span> <span class="o">=</span> <span class="n">go</span><span class="o">.</span><span class="n">Scatter</span><span class="p">(</span>
    <span class="n">x</span><span class="o">=</span><span class="n">dataImp</span><span class="p">[</span><span class="s1">&#39;Imports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">][</span><span class="n">dataImp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;United States&#39;</span><span class="p">],</span>
    <span class="n">y</span><span class="o">=</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Exports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">][</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;United States&#39;</span><span class="p">],</span>
    <span class="n">mode</span><span class="o">=</span><span class="s1">&#39;markers&#39;</span><span class="p">,</span>
    <span class="n">name</span><span class="o">=</span><span class="s1">&#39;United States&#39;</span><span class="p">,</span>
    <span class="n">text</span><span class="o">=</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">][</span><span class="n">dataExp</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;United States&#39;</span><span class="p">],</span>
    <span class="n">marker</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
        <span class="n">symbol</span><span class="o">=</span><span class="s1">&#39;circle&#39;</span><span class="p">,</span>
        <span class="n">sizemode</span><span class="o">=</span><span class="s1">&#39;area&#39;</span><span class="p">,</span>
        <span class="n">sizeref</span><span class="o">=</span> <span class="mi">2</span><span class="p">,</span>
        <span class="n">size</span><span class="o">=</span><span class="mi">10</span><span class="p">,</span>
        <span class="n">line</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
            <span class="n">width</span><span class="o">=</span><span class="mi">2</span>
        <span class="p">),</span>
    <span class="p">)</span>
<span class="p">)</span>

<span class="n">data</span> <span class="o">=</span> <span class="p">[</span><span class="n">trace0</span><span class="p">,</span> <span class="n">trace1</span><span class="p">,</span> <span class="n">trace2</span><span class="p">]</span>

<span class="n">layout</span> <span class="o">=</span> <span class="n">go</span><span class="o">.</span><span class="n">Layout</span><span class="p">(</span>
    <span class="n">title</span> <span class="o">=</span> <span class="s1">&#39;Imports vs. Exports Historical Evolution&#39;</span><span class="p">,</span>

    <span class="n">xaxis</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
        <span class="n">title</span><span class="o">=</span><span class="s1">&#39;Imports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">,</span>
        <span class="n">gridcolor</span><span class="o">=</span><span class="s1">&#39;rgb(255, 255, 255)&#39;</span><span class="p">,</span>
        <span class="n">autorange</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
        <span class="n">zerolinewidth</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span>
        <span class="n">ticklen</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
        <span class="n">gridwidth</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span>
    <span class="p">),</span>
    <span class="n">yaxis</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span>
        <span class="n">title</span><span class="o">=</span><span class="s1">&#39;Exports of goods and services (</span><span class="si">% o</span><span class="s1">f GDP)&#39;</span><span class="p">,</span>
        <span class="n">gridcolor</span><span class="o">=</span><span class="s1">&#39;rgb(255, 255, 255)&#39;</span><span class="p">,</span>
        <span class="n">autorange</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span>
        <span class="n">zerolinewidth</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span>
        <span class="n">ticklen</span><span class="o">=</span><span class="mi">5</span><span class="p">,</span>
        <span class="n">gridwidth</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span>
    <span class="p">),</span>
    <span class="n">paper_bgcolor</span><span class="o">=</span><span class="s1">&#39;rgb(243, 243, 243)&#39;</span><span class="p">,</span>
    <span class="n">plot_bgcolor</span><span class="o">=</span><span class="s1">&#39;rgb(243, 243, 243)&#39;</span><span class="p">,</span>
<span class="p">)</span>


<span class="n">fig</span> <span class="o">=</span> <span class="n">go</span><span class="o">.</span><span class="n">Figure</span><span class="p">(</span><span class="n">data</span><span class="o">=</span><span class="n">data</span><span class="p">,</span> <span class="n">layout</span> <span class="o">=</span> <span class="n">layout</span><span class="p">)</span>
<span class="n">py</span><span class="o">.</span><span class="n">iplot</span><span class="p">(</span><span class="n">fig</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[27]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plot.ly/~adelina1789/24.embed" height="525px" width="100%"></iframe>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='Regional'></a></p>
<h3 id="3.1-Regional-Trade-Flows-in-Intermediate-Manufacturing-Goods">3.1 Regional Trade Flows in Intermediate Manufacturing Goods<a class="anchor-link" href="#3.1-Regional-Trade-Flows-in-Intermediate-Manufacturing-Goods">&#182;</a></h3><p>When we count all the cells except for the final goods-column in a global input-output table, we get as a result the total intermediate inputs that a country uses in a year. When we do this for every sector in the manufacturing column (20-39 SIC codes), then we have as a final result the total amount of intermediate goods (in millions US$) that the manufacturing industry uses per country per year. Analoguesly, we can use the same method to calculate all the numbers for every column, which results in the total quantity of intermediate inputs from one country. The next table represents the caclulated total intermediate inputs from each of the three partner countries, for both years 1995 and 2011.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[28]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>



<span class="n">WIOT1995</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">ExcelFile</span><span class="p">(</span><span class="sa">r</span><span class="s2">&quot;C:\Users\Jesse\Downloads\PythonFinal\WIOT_Cleaned_1995.xlsx&quot;</span><span class="p">)</span>
<span class="n">pd</span><span class="o">.</span><span class="n">to_numeric</span><span class="p">(</span><span class="n">WIOT1995</span><span class="p">,</span> <span class="n">errors</span><span class="o">=</span><span class="s1">&#39;coerce&#39;</span><span class="p">)</span>

<span class="n">TRFLOWS</span> <span class="o">=</span> <span class="n">WIOT1995</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;TOT-Intermed 95-11&#39;</span><span class="p">)</span>
<span class="n">TRFLOWS</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[28]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>CAN 1995</th>
      <th>CAN 2011</th>
      <th>MEX 1995</th>
      <th>MEX 2011</th>
      <th>USA 1995</th>
      <th>USA 2011</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>From CAN</th>
      <td>129957</td>
      <td>283107</td>
      <td>736</td>
      <td>3763</td>
      <td>51736</td>
      <td>82685</td>
    </tr>
    <tr>
      <th>From MEX</th>
      <td>1288</td>
      <td>3907</td>
      <td>101643</td>
      <td>219361</td>
      <td>19960</td>
      <td>55523</td>
    </tr>
    <tr>
      <th>From USA</th>
      <td>40740</td>
      <td>49811</td>
      <td>25024</td>
      <td>42668</td>
      <td>2062271</td>
      <td>2492590</td>
    </tr>
    <tr>
      <th>Total from North-America</th>
      <td>171985</td>
      <td>336825</td>
      <td>127403</td>
      <td>265792</td>
      <td>2133967</td>
      <td>2630798</td>
    </tr>
    <tr>
      <th>From BRA</th>
      <td>404</td>
      <td>1699</td>
      <td>405</td>
      <td>1282</td>
      <td>3946</td>
      <td>4384</td>
    </tr>
    <tr>
      <th>Total from World</th>
      <td>193775</td>
      <td>393409</td>
      <td>137380</td>
      <td>311848</td>
      <td>2343772</td>
      <td>3013386</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We observe for the US in 1995 the total value for the intermediate inputs was 2.343.772 (coming from everywhere in the world). Here was 51.736 coming from Canada, 19.960 from Mexico and 2.062.271 from the national American manufacturing industries. A total of 91% from the intermediate inputs used in the US originated from the inputs from North-America, where 88% was nationally manufactured inputs. When we compare this composition to that of 2011, we can see a decline in the nationally produced inputs and an increase in the both the Canadian inputs as Mexican. Especially, the rise of the Mexican inputs is noticeable: almost three times bigger in absolute terms (from 19.960 to 55.523) and relatively increases from 0% to 2%.</p>
<p>When we apply the same logic for Mexico, we get a similar evolution. Overall, in absolute terms the inputs have increased from the three countries into Mexico. Relatively, the US and Canada both have become a much stronger input provider for the Mexican manufacturing industry. in 1995 were 90% of the inputs produced in North-America, out of zhich 73% from Mexico itself and 15% from the US. In 2011 are the terms different from the American situation. Mexico imports now only 13.5% of her total inputs from the US.</p>
<p>On the contrary to the US and Mexico, was Canada not as strong in providing nationally produced inputs to the manufacturing sector. In 1995 came about 89% from the inputs from North-America, but only 67% of those inputs were nationally produced. Even when compared to Mexico, Canada imported a big part of the inputs from the US, 21%. The trade between Canada and Mexico was almost negligible. In 2011 the situation has changed quite a lot for Canada. Still, the country imports 86% from North-America, but remarkably much more nationally produced inputs, 72%. This is also a direct consequence of the lowered inputs from the US (only 13.5% now). The intermediate manufacturing inputtrade with Mexico goes up by factor three and is now 1% of the total import of inputs.</p>
<p>Out of these descriptives, we can preliminary conclude that the US is central to the trade between the three countries. Both Mexico and Canada are strongly dependent on their inputs from the US, while the US itself is relatively independent. Secondly, we observe that the trade from the rest of the world has not played as big role as the North-American trade. Even in 1995, at the start of the NAFTA agreement the mutual trade between the three countries was already big.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='NAGVC'></a></p>
<h3 id="3.2-North-American-Global-Value-Chain">3.2 North American Global Value Chain<a class="anchor-link" href="#3.2-North-American-Global-Value-Chain">&#182;</a></h3><p>In this section, we compute the actual GVC for the three countries by calculating the bilateral re-exports for each country. This is a necessary step to look at the evolution of the trade flows between the three countries and to pin down the regional North-American value chain. We start by looking at the inputs from Mexico to the US (US-MEX). An individual celnumber gives us the quantity of intermediate inputs that the columncountry re-exports (supplies) to the rowcountry. So the first two tables here (US-MEX in 1995 and in 2011) give us the re-exports from Mexico into the US, respectively in 1995 and in 2011. After that, the third table gives us the evolution of the two input tables. This is when we substract the trade inputs in 1995 from the inputs in 2011 and analyze whether or not the inputs have increased over time and if yes, in which sectors it happened most.</p>
<p>Consequetively, we do the same for US-CAN (inputs into the US from Canada), CAN-MEX (inputs in Canada from Mexico), MEX-US (inputs in Mexico from US), MEX-CAN (inputs in Mexico from Canada) and lastly, CAN-US (inputs in Canada from US).</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>



<span class="n">WIOT1995</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">ExcelFile</span><span class="p">(</span><span class="sa">r</span><span class="s1">&#39;C:\Users\Jesse\Downloads\PythonFinal\WIOT_Cleaned_1995.xlsx&#39;</span><span class="p">)</span>
<span class="n">pd</span><span class="o">.</span><span class="n">to_numeric</span><span class="p">(</span><span class="n">WIOT1995</span><span class="p">,</span> <span class="n">errors</span><span class="o">=</span><span class="s1">&#39;coerce&#39;</span><span class="p">)</span>
<span class="n">WIOT2011</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">ExcelFile</span><span class="p">(</span><span class="sa">r</span><span class="s1">&#39;C:\Users\Jesse\Downloads\PythonFinal\WIOT_Cleaned_2011.xlsx&#39;</span><span class="p">)</span>
<span class="n">pd</span><span class="o">.</span><span class="n">to_numeric</span><span class="p">(</span><span class="n">WIOT2011</span><span class="p">,</span> <span class="n">errors</span><span class="o">=</span><span class="s1">&#39;coerce&#39;</span><span class="p">)</span>

<span class="n">IOTUM1995</span> <span class="o">=</span> <span class="n">WIOT1995</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;US-MEX&#39;</span><span class="p">)</span>
<span class="n">IOTUM1995</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[4]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco USA</th>
      <th>Textiles and Textile Products USA</th>
      <th>Leather, Leather and Footwear USA</th>
      <th>Wood and Products of Wood and Cork USA</th>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <th>Chemicals and Chemical Products USA</th>
      <th>Rubber and Plastics USA</th>
      <th>Other Non-Metallic Mineral USA</th>
      <th>Basic Metals and Fabricated Metal USA</th>
      <th>Machinery, Nec USA</th>
      <th>Electrical and Optical Equipment USA</th>
      <th>Transport Equipment USA</th>
      <th>Manufacturing, Nec; Recycling USA</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco MEX</td>
      <td>69.072125</td>
      <td>0.286647</td>
      <td>1.304437</td>
      <td>0.174204</td>
      <td>1.256982</td>
      <td>0.393879</td>
      <td>2.251308</td>
      <td>0.416952</td>
      <td>0.326658</td>
      <td>0.722350</td>
      <td>0.707443</td>
      <td>0.298765</td>
      <td>0.707264</td>
      <td>0.153979</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products MEX</td>
      <td>1.424176</td>
      <td>122.572248</td>
      <td>1.440026</td>
      <td>2.290070</td>
      <td>13.671359</td>
      <td>0.102436</td>
      <td>0.906050</td>
      <td>7.531088</td>
      <td>0.862272</td>
      <td>28.057259</td>
      <td>1.973784</td>
      <td>4.048838</td>
      <td>20.598424</td>
      <td>12.653600</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear MEX</td>
      <td>0.416352</td>
      <td>27.333149</td>
      <td>19.081049</td>
      <td>0.019861</td>
      <td>29.779187</td>
      <td>0.020221</td>
      <td>0.095678</td>
      <td>0.099278</td>
      <td>0.026105</td>
      <td>0.964686</td>
      <td>0.275287</td>
      <td>0.140565</td>
      <td>27.459922</td>
      <td>0.817871</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork MEX</td>
      <td>0.901305</td>
      <td>0.419004</td>
      <td>0.007329</td>
      <td>38.613922</td>
      <td>16.832020</td>
      <td>0.011981</td>
      <td>0.678459</td>
      <td>1.626246</td>
      <td>1.525008</td>
      <td>28.019537</td>
      <td>1.186578</td>
      <td>1.078355</td>
      <td>3.453230</td>
      <td>13.451615</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing MEX</td>
      <td>42.255230</td>
      <td>3.116897</td>
      <td>0.202043</td>
      <td>1.233381</td>
      <td>183.369923</td>
      <td>0.432632</td>
      <td>11.715630</td>
      <td>11.648166</td>
      <td>5.567015</td>
      <td>39.914721</td>
      <td>6.973963</td>
      <td>10.624021</td>
      <td>8.068645</td>
      <td>5.288988</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel MEX</td>
      <td>1.883379</td>
      <td>0.912314</td>
      <td>0.019086</td>
      <td>0.446242</td>
      <td>2.597929</td>
      <td>18.888070</td>
      <td>21.792648</td>
      <td>2.659400</td>
      <td>0.583377</td>
      <td>2.283341</td>
      <td>1.438588</td>
      <td>2.184284</td>
      <td>0.532017</td>
      <td>0.444657</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products MEX</td>
      <td>24.146442</td>
      <td>62.743594</td>
      <td>1.110642</td>
      <td>5.698359</td>
      <td>73.639660</td>
      <td>4.664579</td>
      <td>363.989254</td>
      <td>126.384366</td>
      <td>9.310149</td>
      <td>105.108434</td>
      <td>13.383200</td>
      <td>35.858507</td>
      <td>21.384665</td>
      <td>12.725448</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics MEX</td>
      <td>51.413835</td>
      <td>3.752769</td>
      <td>1.834727</td>
      <td>4.667477</td>
      <td>32.982788</td>
      <td>0.561338</td>
      <td>39.542002</td>
      <td>59.359467</td>
      <td>3.801666</td>
      <td>50.993049</td>
      <td>47.204884</td>
      <td>45.732947</td>
      <td>88.867340</td>
      <td>30.259365</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral MEX</td>
      <td>28.562491</td>
      <td>3.765409</td>
      <td>0.003942</td>
      <td>9.281822</td>
      <td>1.686782</td>
      <td>1.990925</td>
      <td>10.320019</td>
      <td>10.851052</td>
      <td>81.075384</td>
      <td>25.451388</td>
      <td>17.323303</td>
      <td>37.830414</td>
      <td>32.514818</td>
      <td>6.279441</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal MEX</td>
      <td>74.984278</td>
      <td>4.464549</td>
      <td>0.399067</td>
      <td>8.554522</td>
      <td>31.670837</td>
      <td>1.684245</td>
      <td>27.996055</td>
      <td>23.336745</td>
      <td>12.605001</td>
      <td>1032.741626</td>
      <td>325.611561</td>
      <td>258.851814</td>
      <td>423.602135</td>
      <td>85.068909</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec MEX</td>
      <td>7.641859</td>
      <td>1.469767</td>
      <td>0.042235</td>
      <td>4.274217</td>
      <td>25.620550</td>
      <td>0.287012</td>
      <td>16.056103</td>
      <td>9.035516</td>
      <td>1.720324</td>
      <td>56.192141</td>
      <td>123.593932</td>
      <td>17.836802</td>
      <td>91.327980</td>
      <td>3.715874</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment MEX</td>
      <td>59.957222</td>
      <td>24.695364</td>
      <td>0.697132</td>
      <td>26.050574</td>
      <td>106.462428</td>
      <td>4.551468</td>
      <td>98.383256</td>
      <td>88.684113</td>
      <td>20.990358</td>
      <td>357.421698</td>
      <td>499.888927</td>
      <td>1705.146256</td>
      <td>474.243528</td>
      <td>37.678648</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment MEX</td>
      <td>22.396400</td>
      <td>5.330583</td>
      <td>0.421647</td>
      <td>11.012045</td>
      <td>19.762587</td>
      <td>1.245471</td>
      <td>13.596087</td>
      <td>10.267547</td>
      <td>4.341744</td>
      <td>56.563550</td>
      <td>132.851999</td>
      <td>97.883152</td>
      <td>2464.311316</td>
      <td>6.378479</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling MEX</td>
      <td>1.859857</td>
      <td>18.722085</td>
      <td>0.094421</td>
      <td>2.040064</td>
      <td>501.213954</td>
      <td>0.076921</td>
      <td>26.721356</td>
      <td>26.797505</td>
      <td>18.729525</td>
      <td>1945.476814</td>
      <td>7.437543</td>
      <td>8.260158</td>
      <td>9.352804</td>
      <td>9.984785</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTUM2011</span> <span class="o">=</span> <span class="n">WIOT2011</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;US-MEX&#39;</span><span class="p">)</span>
<span class="n">IOTUM2011</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[5]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco USA</th>
      <th>Textiles and Textile Products USA</th>
      <th>Leather, Leather and Footwear USA</th>
      <th>Wood and Products of Wood and Cork USA</th>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <th>Chemicals and Chemical Products USA</th>
      <th>Rubber and Plastics USA</th>
      <th>Other Non-Metallic Mineral USA</th>
      <th>Basic Metals and Fabricated Metal USA</th>
      <th>Machinery, Nec USA</th>
      <th>Electrical and Optical Equipment USA</th>
      <th>Transport Equipment USA</th>
      <th>Manufacturing, Nec; Recycling USA</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco MEX</td>
      <td>234.332722</td>
      <td>0.165361</td>
      <td>0.482207</td>
      <td>0.149977</td>
      <td>2.418315</td>
      <td>0.273132</td>
      <td>6.606596</td>
      <td>0.729631</td>
      <td>0.335022</td>
      <td>0.859330</td>
      <td>1.829134</td>
      <td>0.305009</td>
      <td>1.830922</td>
      <td>0.220839</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products MEX</td>
      <td>3.761809</td>
      <td>153.130301</td>
      <td>0.492564</td>
      <td>3.139776</td>
      <td>75.427252</td>
      <td>0.288251</td>
      <td>0.916930</td>
      <td>21.038253</td>
      <td>2.859956</td>
      <td>3.343998</td>
      <td>9.177048</td>
      <td>8.935144</td>
      <td>37.419050</td>
      <td>26.232449</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear MEX</td>
      <td>0.755269</td>
      <td>20.050763</td>
      <td>7.376856</td>
      <td>0.014122</td>
      <td>24.278846</td>
      <td>0.159220</td>
      <td>0.122535</td>
      <td>0.128141</td>
      <td>0.016069</td>
      <td>0.163235</td>
      <td>0.358284</td>
      <td>0.130253</td>
      <td>42.305342</td>
      <td>0.607121</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork MEX</td>
      <td>0.888211</td>
      <td>0.279124</td>
      <td>0.001137</td>
      <td>23.918730</td>
      <td>8.430352</td>
      <td>0.009001</td>
      <td>0.787494</td>
      <td>1.626246</td>
      <td>0.791360</td>
      <td>1.895931</td>
      <td>1.196396</td>
      <td>0.855320</td>
      <td>4.300308</td>
      <td>11.438549</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing MEX</td>
      <td>96.838627</td>
      <td>1.975189</td>
      <td>0.042652</td>
      <td>1.500002</td>
      <td>256.185289</td>
      <td>0.938687</td>
      <td>18.951194</td>
      <td>14.793493</td>
      <td>7.778205</td>
      <td>13.488391</td>
      <td>8.098706</td>
      <td>9.669617</td>
      <td>16.031217</td>
      <td>6.611584</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel MEX</td>
      <td>17.138852</td>
      <td>2.744831</td>
      <td>0.024537</td>
      <td>3.796057</td>
      <td>29.142687</td>
      <td>223.440849</td>
      <td>183.209721</td>
      <td>14.036315</td>
      <td>5.661275</td>
      <td>12.727471</td>
      <td>7.319606</td>
      <td>5.720961</td>
      <td>5.219248</td>
      <td>1.990225</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products MEX</td>
      <td>38.598742</td>
      <td>59.050456</td>
      <td>0.462835</td>
      <td>7.748226</td>
      <td>92.477827</td>
      <td>30.279373</td>
      <td>1001.504515</td>
      <td>245.292396</td>
      <td>17.133417</td>
      <td>48.795995</td>
      <td>20.411230</td>
      <td>36.089866</td>
      <td>45.557858</td>
      <td>24.150641</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics MEX</td>
      <td>288.802310</td>
      <td>5.392589</td>
      <td>1.740520</td>
      <td>7.816682</td>
      <td>76.083948</td>
      <td>2.475232</td>
      <td>151.323242</td>
      <td>188.626604</td>
      <td>14.853852</td>
      <td>43.339848</td>
      <td>148.877925</td>
      <td>85.525999</td>
      <td>345.803519</td>
      <td>87.489620</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral MEX</td>
      <td>99.757501</td>
      <td>1.116905</td>
      <td>0.000934</td>
      <td>12.747412</td>
      <td>3.189237</td>
      <td>6.539599</td>
      <td>24.694473</td>
      <td>22.421451</td>
      <td>187.759205</td>
      <td>62.722936</td>
      <td>37.019889</td>
      <td>37.743781</td>
      <td>104.634281</td>
      <td>6.123051</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal MEX</td>
      <td>492.279288</td>
      <td>9.391771</td>
      <td>0.387591</td>
      <td>27.580829</td>
      <td>136.914820</td>
      <td>15.975228</td>
      <td>148.814102</td>
      <td>107.202961</td>
      <td>95.303621</td>
      <td>7219.043276</td>
      <td>2027.831978</td>
      <td>1233.599310</td>
      <td>2843.972270</td>
      <td>521.246582</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec MEX</td>
      <td>59.391369</td>
      <td>1.244721</td>
      <td>0.020992</td>
      <td>12.651199</td>
      <td>59.928499</td>
      <td>1.735573</td>
      <td>71.865793</td>
      <td>31.254653</td>
      <td>7.066810</td>
      <td>118.245917</td>
      <td>513.990035</td>
      <td>64.508443</td>
      <td>529.965783</td>
      <td>27.766043</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment MEX</td>
      <td>445.328902</td>
      <td>71.270967</td>
      <td>1.586626</td>
      <td>81.337237</td>
      <td>721.069974</td>
      <td>32.717963</td>
      <td>625.039216</td>
      <td>436.123193</td>
      <td>193.518099</td>
      <td>1347.317234</td>
      <td>1922.453736</td>
      <td>6021.468945</td>
      <td>3762.918269</td>
      <td>265.037266</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment MEX</td>
      <td>120.094891</td>
      <td>11.143199</td>
      <td>0.497458</td>
      <td>20.308810</td>
      <td>85.295723</td>
      <td>6.865581</td>
      <td>62.456854</td>
      <td>39.413376</td>
      <td>23.614205</td>
      <td>165.275369</td>
      <td>518.452490</td>
      <td>257.432311</td>
      <td>12945.944069</td>
      <td>29.173522</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling MEX</td>
      <td>20.278599</td>
      <td>16.034214</td>
      <td>0.168511</td>
      <td>3.265819</td>
      <td>59.957308</td>
      <td>0.799334</td>
      <td>21.768941</td>
      <td>20.057038</td>
      <td>7.677213</td>
      <td>302.452194</td>
      <td>47.334636</td>
      <td>41.529862</td>
      <td>86.911395</td>
      <td>83.821405</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTUM2011</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">subtract</span><span class="p">(</span><span class="n">IOTUM1995</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">),</span> <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[6]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Food, Beverages and Tobacco USA</th>
      <th>Textiles and Textile Products USA</th>
      <th>Leather, Leather and Footwear USA</th>
      <th>Wood and Products of Wood and Cork USA</th>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <th>Chemicals and Chemical Products USA</th>
      <th>Rubber and Plastics USA</th>
      <th>Other Non-Metallic Mineral USA</th>
      <th>Basic Metals and Fabricated Metal USA</th>
      <th>Machinery, Nec USA</th>
      <th>Electrical and Optical Equipment USA</th>
      <th>Transport Equipment USA</th>
      <th>Manufacturing, Nec; Recycling USA</th>
    </tr>
    <tr>
      <th>Sectors</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Food, Beverages and Tobacco MEX</th>
      <td>165.260596</td>
      <td>-0.121287</td>
      <td>-0.822230</td>
      <td>-0.024227</td>
      <td>1.161333</td>
      <td>-0.120747</td>
      <td>4.355288</td>
      <td>3.126789e-01</td>
      <td>0.008364</td>
      <td>0.136980</td>
      <td>1.121691</td>
      <td>0.006244</td>
      <td>1.123658</td>
      <td>0.066860</td>
    </tr>
    <tr>
      <th>Textiles and Textile Products MEX</th>
      <td>2.337633</td>
      <td>30.558053</td>
      <td>-0.947462</td>
      <td>0.849706</td>
      <td>61.755893</td>
      <td>0.185814</td>
      <td>0.010880</td>
      <td>1.350717e+01</td>
      <td>1.997684</td>
      <td>-24.713261</td>
      <td>7.203264</td>
      <td>4.886306</td>
      <td>16.820626</td>
      <td>13.578849</td>
    </tr>
    <tr>
      <th>Leather, Leather and Footwear MEX</th>
      <td>0.338917</td>
      <td>-7.282386</td>
      <td>-11.704193</td>
      <td>-0.005739</td>
      <td>-5.500341</td>
      <td>0.138999</td>
      <td>0.026856</td>
      <td>2.886285e-02</td>
      <td>-0.010036</td>
      <td>-0.801451</td>
      <td>0.082997</td>
      <td>-0.010313</td>
      <td>14.845421</td>
      <td>-0.210749</td>
    </tr>
    <tr>
      <th>Wood and Products of Wood and Cork MEX</th>
      <td>-0.013094</td>
      <td>-0.139880</td>
      <td>-0.006192</td>
      <td>-14.695193</td>
      <td>-8.401668</td>
      <td>-0.002980</td>
      <td>0.109035</td>
      <td>1.261464e-07</td>
      <td>-0.733648</td>
      <td>-26.123606</td>
      <td>0.009818</td>
      <td>-0.223036</td>
      <td>0.847078</td>
      <td>-2.013066</td>
    </tr>
    <tr>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <td>54.583397</td>
      <td>-1.141708</td>
      <td>-0.159391</td>
      <td>0.266621</td>
      <td>72.815366</td>
      <td>0.506055</td>
      <td>7.235564</td>
      <td>3.145327e+00</td>
      <td>2.211190</td>
      <td>-26.426330</td>
      <td>1.124743</td>
      <td>-0.954404</td>
      <td>7.962572</td>
      <td>1.322596</td>
    </tr>
    <tr>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <td>15.255473</td>
      <td>1.832517</td>
      <td>0.005451</td>
      <td>3.349815</td>
      <td>26.544758</td>
      <td>204.552778</td>
      <td>161.417074</td>
      <td>1.137691e+01</td>
      <td>5.077898</td>
      <td>10.444130</td>
      <td>5.881019</td>
      <td>3.536677</td>
      <td>4.687231</td>
      <td>1.545568</td>
    </tr>
    <tr>
      <th>Chemicals and Chemical Products MEX</th>
      <td>14.452299</td>
      <td>-3.693139</td>
      <td>-0.647806</td>
      <td>2.049867</td>
      <td>18.838167</td>
      <td>25.614794</td>
      <td>637.515261</td>
      <td>1.189080e+02</td>
      <td>7.823268</td>
      <td>-56.312439</td>
      <td>7.028030</td>
      <td>0.231360</td>
      <td>24.173194</td>
      <td>11.425194</td>
    </tr>
    <tr>
      <th>Rubber and Plastics MEX</th>
      <td>237.388475</td>
      <td>1.639820</td>
      <td>-0.094207</td>
      <td>3.149205</td>
      <td>43.101160</td>
      <td>1.913894</td>
      <td>111.781240</td>
      <td>1.292671e+02</td>
      <td>11.052186</td>
      <td>-7.653201</td>
      <td>101.673042</td>
      <td>39.793052</td>
      <td>256.936179</td>
      <td>57.230255</td>
    </tr>
    <tr>
      <th>Other Non-Metallic Mineral MEX</th>
      <td>71.195010</td>
      <td>-2.648503</td>
      <td>-0.003008</td>
      <td>3.465590</td>
      <td>1.502455</td>
      <td>4.548674</td>
      <td>14.374454</td>
      <td>1.157040e+01</td>
      <td>106.683821</td>
      <td>37.271548</td>
      <td>19.696585</td>
      <td>-0.086633</td>
      <td>72.119463</td>
      <td>-0.156389</td>
    </tr>
    <tr>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <td>417.295010</td>
      <td>4.927222</td>
      <td>-0.011475</td>
      <td>19.026307</td>
      <td>105.243982</td>
      <td>14.290983</td>
      <td>120.818047</td>
      <td>8.386622e+01</td>
      <td>82.698620</td>
      <td>6186.301650</td>
      <td>1702.220417</td>
      <td>974.747496</td>
      <td>2420.370135</td>
      <td>436.177673</td>
    </tr>
    <tr>
      <th>Machinery, Nec MEX</th>
      <td>51.749510</td>
      <td>-0.225046</td>
      <td>-0.021243</td>
      <td>8.376983</td>
      <td>34.307950</td>
      <td>1.448562</td>
      <td>55.809690</td>
      <td>2.221914e+01</td>
      <td>5.346486</td>
      <td>62.053776</td>
      <td>390.396104</td>
      <td>46.671641</td>
      <td>438.637803</td>
      <td>24.050169</td>
    </tr>
    <tr>
      <th>Electrical and Optical Equipment MEX</th>
      <td>385.371680</td>
      <td>46.575603</td>
      <td>0.889494</td>
      <td>55.286663</td>
      <td>614.607546</td>
      <td>28.166495</td>
      <td>526.655959</td>
      <td>3.474391e+02</td>
      <td>172.527740</td>
      <td>989.895535</td>
      <td>1422.564810</td>
      <td>4316.322689</td>
      <td>3288.674741</td>
      <td>227.358618</td>
    </tr>
    <tr>
      <th>Transport Equipment MEX</th>
      <td>97.698492</td>
      <td>5.812616</td>
      <td>0.075810</td>
      <td>9.296765</td>
      <td>65.533136</td>
      <td>5.620110</td>
      <td>48.860767</td>
      <td>2.914583e+01</td>
      <td>19.272462</td>
      <td>108.711819</td>
      <td>385.600491</td>
      <td>159.549159</td>
      <td>10481.632753</td>
      <td>22.795043</td>
    </tr>
    <tr>
      <th>Manufacturing, Nec; Recycling MEX</th>
      <td>18.418742</td>
      <td>-2.687871</td>
      <td>0.074090</td>
      <td>1.225755</td>
      <td>-441.256646</td>
      <td>0.722414</td>
      <td>-4.952415</td>
      <td>-6.740467e+00</td>
      <td>-11.052312</td>
      <td>-1643.024621</td>
      <td>39.897093</td>
      <td>33.269704</td>
      <td>77.558591</td>
      <td>73.836620</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>When we analyze the evolution of the intermediate inputs from Mexico to the USA (US-MEX), we can see that almost all inputs from the Mexican sectors 'Textiles and Textile Products', 'Chemicals and Chemical Products', 'Basic Metals and Fabricated Metal', 'Electrical and Optical Equipment' and 'Transport Equipment' have known the biggest increase between 1995 and 2011 (the very last column). Especially the latter two show enormous numbers. If we compare the first two tables, we see that the two sectors ('Electrical and Optical Equipment' and 'Transport Equipment') have always known a big input provision into the US, but after the NAFTA agreement the absolute numbers increased. Next, follows the same analysis for the US-CAN, i.e. inputs into US from Canada.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTUC1995</span> <span class="o">=</span> <span class="n">WIOT1995</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s2">&quot;US-CAN&quot;</span><span class="p">)</span>
<span class="n">IOTUC1995</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[7]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco USA</th>
      <th>Textiles and Textile Products USA</th>
      <th>Leather, Leather and Footwear USA</th>
      <th>Wood and Products of Wood and Cork USA</th>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <th>Chemicals and Chemical Products USA</th>
      <th>Rubber and Plastics USA</th>
      <th>Other Non-Metallic Mineral USA</th>
      <th>Basic Metals and Fabricated Metal USA</th>
      <th>Machinery, Nec USA</th>
      <th>Electrical and Optical Equipment USA</th>
      <th>Transport Equipment USA</th>
      <th>Manufacturing, Nec; Recycling USA</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco CAN</td>
      <td>339.230954</td>
      <td>11.764715</td>
      <td>6.596169</td>
      <td>1.297615</td>
      <td>14.751797</td>
      <td>0.921024</td>
      <td>72.629716</td>
      <td>23.156150</td>
      <td>2.154078</td>
      <td>6.162900</td>
      <td>4.242165</td>
      <td>9.343689</td>
      <td>5.808093</td>
      <td>3.010013</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products CAN</td>
      <td>3.589550</td>
      <td>357.644615</td>
      <td>3.962469</td>
      <td>6.195299</td>
      <td>24.446692</td>
      <td>0.220829</td>
      <td>1.065719</td>
      <td>19.510172</td>
      <td>1.614693</td>
      <td>0.513879</td>
      <td>3.415646</td>
      <td>10.297924</td>
      <td>38.630897</td>
      <td>34.718883</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear CAN</td>
      <td>1.923019</td>
      <td>15.851648</td>
      <td>10.855051</td>
      <td>0.151692</td>
      <td>17.475621</td>
      <td>0.100766</td>
      <td>1.365024</td>
      <td>1.989250</td>
      <td>0.117190</td>
      <td>0.392128</td>
      <td>1.421696</td>
      <td>1.340556</td>
      <td>18.118987</td>
      <td>1.469236</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork CAN</td>
      <td>42.601335</td>
      <td>6.615896</td>
      <td>0.280132</td>
      <td>1474.657317</td>
      <td>411.529161</td>
      <td>0.302197</td>
      <td>14.893421</td>
      <td>50.541391</td>
      <td>49.292783</td>
      <td>39.646359</td>
      <td>44.936847</td>
      <td>42.111465</td>
      <td>141.316970</td>
      <td>513.819647</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing CAN</td>
      <td>1493.827446</td>
      <td>68.892555</td>
      <td>6.887225</td>
      <td>40.405878</td>
      <td>5630.754621</td>
      <td>11.636334</td>
      <td>380.972814</td>
      <td>395.344104</td>
      <td>186.029464</td>
      <td>255.139088</td>
      <td>223.659521</td>
      <td>321.842622</td>
      <td>213.718120</td>
      <td>185.713969</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel CAN</td>
      <td>30.496107</td>
      <td>2.347804</td>
      <td>0.155303</td>
      <td>3.113770</td>
      <td>84.196649</td>
      <td>126.208436</td>
      <td>123.451913</td>
      <td>13.297074</td>
      <td>5.759733</td>
      <td>16.828064</td>
      <td>11.680170</td>
      <td>16.219032</td>
      <td>4.991317</td>
      <td>4.485264</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products CAN</td>
      <td>142.588999</td>
      <td>459.965252</td>
      <td>7.554983</td>
      <td>37.497280</td>
      <td>323.637460</td>
      <td>24.472691</td>
      <td>2164.231495</td>
      <td>751.935102</td>
      <td>52.056266</td>
      <td>159.138437</td>
      <td>76.858564</td>
      <td>218.536691</td>
      <td>141.277242</td>
      <td>84.757898</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics CAN</td>
      <td>232.606875</td>
      <td>16.011951</td>
      <td>6.218804</td>
      <td>20.505731</td>
      <td>286.087044</td>
      <td>3.369457</td>
      <td>169.565098</td>
      <td>221.433512</td>
      <td>19.588336</td>
      <td>59.583280</td>
      <td>167.542179</td>
      <td>151.439656</td>
      <td>474.091712</td>
      <td>115.441742</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral CAN</td>
      <td>51.776169</td>
      <td>7.431361</td>
      <td>0.028767</td>
      <td>16.749693</td>
      <td>4.322569</td>
      <td>3.751514</td>
      <td>24.152893</td>
      <td>20.698781</td>
      <td>147.349126</td>
      <td>47.566858</td>
      <td>25.939948</td>
      <td>60.917865</td>
      <td>57.493286</td>
      <td>11.774123</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal CAN</td>
      <td>289.903929</td>
      <td>16.289288</td>
      <td>1.162178</td>
      <td>31.186645</td>
      <td>125.543990</td>
      <td>4.888935</td>
      <td>122.239275</td>
      <td>82.878296</td>
      <td>49.290918</td>
      <td>4548.113914</td>
      <td>1343.976532</td>
      <td>1029.923151</td>
      <td>1829.240209</td>
      <td>360.616448</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec CAN</td>
      <td>33.510961</td>
      <td>5.052376</td>
      <td>0.139559</td>
      <td>13.517786</td>
      <td>47.784330</td>
      <td>1.133015</td>
      <td>44.661834</td>
      <td>30.716531</td>
      <td>6.025208</td>
      <td>306.633785</td>
      <td>403.623259</td>
      <td>229.542073</td>
      <td>293.814841</td>
      <td>30.142086</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment CAN</td>
      <td>63.823394</td>
      <td>24.152540</td>
      <td>0.829536</td>
      <td>25.036766</td>
      <td>129.793315</td>
      <td>3.941910</td>
      <td>110.958340</td>
      <td>81.348513</td>
      <td>24.896406</td>
      <td>237.332078</td>
      <td>436.218120</td>
      <td>2439.727088</td>
      <td>653.318622</td>
      <td>48.158048</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment CAN</td>
      <td>47.173573</td>
      <td>4.858342</td>
      <td>0.109094</td>
      <td>23.862601</td>
      <td>30.107772</td>
      <td>2.504713</td>
      <td>22.603809</td>
      <td>10.306765</td>
      <td>8.843632</td>
      <td>76.469608</td>
      <td>256.919733</td>
      <td>70.856623</td>
      <td>6561.295772</td>
      <td>9.451913</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling CAN</td>
      <td>7.000970</td>
      <td>40.172845</td>
      <td>0.680583</td>
      <td>93.425995</td>
      <td>26.797483</td>
      <td>0.889919</td>
      <td>25.208872</td>
      <td>11.151749</td>
      <td>9.123877</td>
      <td>45.580889</td>
      <td>48.872972</td>
      <td>43.798162</td>
      <td>58.836955</td>
      <td>138.322383</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTUC2011</span> <span class="o">=</span> <span class="n">WIOT2011</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;US-CAN&#39;</span><span class="p">)</span>
<span class="n">IOTUC2011</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[8]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco USA</th>
      <th>Textiles and Textile Products USA</th>
      <th>Leather, Leather and Footwear USA</th>
      <th>Wood and Products of Wood and Cork USA</th>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <th>Chemicals and Chemical Products USA</th>
      <th>Rubber and Plastics USA</th>
      <th>Other Non-Metallic Mineral USA</th>
      <th>Basic Metals and Fabricated Metal USA</th>
      <th>Machinery, Nec USA</th>
      <th>Electrical and Optical Equipment USA</th>
      <th>Transport Equipment USA</th>
      <th>Manufacturing, Nec; Recycling USA</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco CAN</td>
      <td>1347.231867</td>
      <td>8.667634</td>
      <td>2.849499</td>
      <td>2.139337</td>
      <td>32.850945</td>
      <td>3.681635</td>
      <td>169.036637</td>
      <td>35.555491</td>
      <td>4.142173</td>
      <td>11.668932</td>
      <td>8.548819</td>
      <td>11.833578</td>
      <td>19.407322</td>
      <td>5.207414</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products CAN</td>
      <td>6.060455</td>
      <td>233.364733</td>
      <td>1.086679</td>
      <td>6.860948</td>
      <td>93.451020</td>
      <td>0.606729</td>
      <td>0.882733</td>
      <td>44.864861</td>
      <td>5.999720</td>
      <td>0.395846</td>
      <td>17.249447</td>
      <td>18.393620</td>
      <td>54.451255</td>
      <td>56.170861</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear CAN</td>
      <td>1.366890</td>
      <td>9.459140</td>
      <td>3.420200</td>
      <td>0.030571</td>
      <td>11.582024</td>
      <td>0.107042</td>
      <td>0.596050</td>
      <td>0.733390</td>
      <td>0.057376</td>
      <td>0.128279</td>
      <td>0.530739</td>
      <td>0.300923</td>
      <td>20.591163</td>
      <td>0.589868</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork CAN</td>
      <td>51.196525</td>
      <td>7.567845</td>
      <td>0.057281</td>
      <td>767.673727</td>
      <td>306.215355</td>
      <td>0.512436</td>
      <td>32.998167</td>
      <td>56.218991</td>
      <td>26.212761</td>
      <td>32.127335</td>
      <td>38.600476</td>
      <td>30.809740</td>
      <td>142.410766</td>
      <td>367.136893</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing CAN</td>
      <td>1617.755959</td>
      <td>26.826871</td>
      <td>0.750239</td>
      <td>23.358565</td>
      <td>3502.885962</td>
      <td>17.273102</td>
      <td>310.562811</td>
      <td>251.026206</td>
      <td>129.702125</td>
      <td>201.402268</td>
      <td>123.015679</td>
      <td>131.050519</td>
      <td>229.561936</td>
      <td>111.893114</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel CAN</td>
      <td>125.173217</td>
      <td>14.439824</td>
      <td>0.141995</td>
      <td>20.906054</td>
      <td>227.749369</td>
      <td>1122.718035</td>
      <td>928.834541</td>
      <td>76.414910</td>
      <td>31.849731</td>
      <td>69.478151</td>
      <td>40.185581</td>
      <td>32.698351</td>
      <td>33.077991</td>
      <td>13.323500</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products CAN</td>
      <td>281.572125</td>
      <td>480.482475</td>
      <td>3.565966</td>
      <td>58.037362</td>
      <td>692.503298</td>
      <td>192.068034</td>
      <td>7406.632576</td>
      <td>1823.285018</td>
      <td>126.711503</td>
      <td>349.540120</td>
      <td>141.695667</td>
      <td>264.077917</td>
      <td>335.364859</td>
      <td>190.120610</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics CAN</td>
      <td>847.607534</td>
      <td>10.526754</td>
      <td>4.053487</td>
      <td>24.189921</td>
      <td>494.468109</td>
      <td>10.317372</td>
      <td>395.185091</td>
      <td>475.635155</td>
      <td>47.654266</td>
      <td>116.701750</td>
      <td>376.802216</td>
      <td>184.881866</td>
      <td>1096.850602</td>
      <td>223.197379</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral CAN</td>
      <td>89.462504</td>
      <td>1.396619</td>
      <td>0.007821</td>
      <td>11.058363</td>
      <td>6.276161</td>
      <td>6.502786</td>
      <td>30.719971</td>
      <td>20.706129</td>
      <td>167.243684</td>
      <td>55.104852</td>
      <td>29.357820</td>
      <td>30.602073</td>
      <td>91.866268</td>
      <td>5.782348</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal CAN</td>
      <td>731.426673</td>
      <td>17.542219</td>
      <td>0.472918</td>
      <td>38.430156</td>
      <td>196.101895</td>
      <td>20.287759</td>
      <td>302.051961</td>
      <td>169.211093</td>
      <td>143.133374</td>
      <td>11591.845674</td>
      <td>3150.405899</td>
      <td>1899.947846</td>
      <td>4467.359846</td>
      <td>818.521521</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec CAN</td>
      <td>113.393701</td>
      <td>4.095683</td>
      <td>0.066010</td>
      <td>23.329137</td>
      <td>99.698865</td>
      <td>4.973119</td>
      <td>123.519823</td>
      <td>68.693095</td>
      <td>25.263788</td>
      <td>391.570708</td>
      <td>901.149742</td>
      <td>441.676412</td>
      <td>808.292986</td>
      <td>54.056809</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment CAN</td>
      <td>121.396136</td>
      <td>9.700498</td>
      <td>0.221871</td>
      <td>22.513061</td>
      <td>158.796845</td>
      <td>6.440047</td>
      <td>159.078160</td>
      <td>79.528658</td>
      <td>32.324385</td>
      <td>293.676915</td>
      <td>729.669118</td>
      <td>707.701014</td>
      <td>1003.037943</td>
      <td>70.086903</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment CAN</td>
      <td>78.242982</td>
      <td>2.981279</td>
      <td>0.044783</td>
      <td>12.596559</td>
      <td>58.720717</td>
      <td>4.359163</td>
      <td>48.535855</td>
      <td>14.496174</td>
      <td>13.219912</td>
      <td>74.628939</td>
      <td>299.569788</td>
      <td>43.238786</td>
      <td>8735.863397</td>
      <td>13.509516</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling CAN</td>
      <td>13.652602</td>
      <td>18.371679</td>
      <td>0.131477</td>
      <td>52.565269</td>
      <td>37.615522</td>
      <td>0.536048</td>
      <td>33.846323</td>
      <td>15.486622</td>
      <td>7.234144</td>
      <td>77.489022</td>
      <td>65.413462</td>
      <td>40.806822</td>
      <td>105.465806</td>
      <td>206.085678</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTUC2011</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">subtract</span><span class="p">(</span><span class="n">IOTUC1995</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">),</span> <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[9]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Food, Beverages and Tobacco USA</th>
      <th>Textiles and Textile Products USA</th>
      <th>Leather, Leather and Footwear USA</th>
      <th>Wood and Products of Wood and Cork USA</th>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <th>Chemicals and Chemical Products USA</th>
      <th>Rubber and Plastics USA</th>
      <th>Other Non-Metallic Mineral USA</th>
      <th>Basic Metals and Fabricated Metal USA</th>
      <th>Machinery, Nec USA</th>
      <th>Electrical and Optical Equipment USA</th>
      <th>Transport Equipment USA</th>
      <th>Manufacturing, Nec; Recycling USA</th>
    </tr>
    <tr>
      <th>Sectors</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Food, Beverages and Tobacco CAN</th>
      <td>1008.000913</td>
      <td>-3.097081</td>
      <td>-3.746670</td>
      <td>0.841722</td>
      <td>18.099148</td>
      <td>2.760611</td>
      <td>96.406921</td>
      <td>12.399342</td>
      <td>1.988095</td>
      <td>5.506032</td>
      <td>4.306654</td>
      <td>2.489889</td>
      <td>13.599229</td>
      <td>2.197401</td>
    </tr>
    <tr>
      <th>Textiles and Textile Products CAN</th>
      <td>2.470904</td>
      <td>-124.279881</td>
      <td>-2.875789</td>
      <td>0.665650</td>
      <td>69.004328</td>
      <td>0.385900</td>
      <td>-0.182986</td>
      <td>25.354689</td>
      <td>4.385027</td>
      <td>-0.118033</td>
      <td>13.833801</td>
      <td>8.095696</td>
      <td>15.820358</td>
      <td>21.451978</td>
    </tr>
    <tr>
      <th>Leather, Leather and Footwear CAN</th>
      <td>-0.556129</td>
      <td>-6.392507</td>
      <td>-7.434852</td>
      <td>-0.121121</td>
      <td>-5.893597</td>
      <td>0.006276</td>
      <td>-0.768974</td>
      <td>-1.255860</td>
      <td>-0.059814</td>
      <td>-0.263850</td>
      <td>-0.890957</td>
      <td>-1.039633</td>
      <td>2.472175</td>
      <td>-0.879368</td>
    </tr>
    <tr>
      <th>Wood and Products of Wood and Cork CAN</th>
      <td>8.595190</td>
      <td>0.951949</td>
      <td>-0.222852</td>
      <td>-706.983590</td>
      <td>-105.313807</td>
      <td>0.210239</td>
      <td>18.104746</td>
      <td>5.677600</td>
      <td>-23.080022</td>
      <td>-7.519024</td>
      <td>-6.336371</td>
      <td>-11.301725</td>
      <td>1.093795</td>
      <td>-146.682754</td>
    </tr>
    <tr>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <td>123.928514</td>
      <td>-42.065684</td>
      <td>-6.136986</td>
      <td>-17.047314</td>
      <td>-2127.868659</td>
      <td>5.636767</td>
      <td>-70.410002</td>
      <td>-144.317898</td>
      <td>-56.327339</td>
      <td>-53.736819</td>
      <td>-100.643842</td>
      <td>-190.792103</td>
      <td>15.843816</td>
      <td>-73.820855</td>
    </tr>
    <tr>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <td>94.677110</td>
      <td>12.092020</td>
      <td>-0.013308</td>
      <td>17.792284</td>
      <td>143.552719</td>
      <td>996.509599</td>
      <td>805.382628</td>
      <td>63.117836</td>
      <td>26.089998</td>
      <td>52.650086</td>
      <td>28.505410</td>
      <td>16.479319</td>
      <td>28.086674</td>
      <td>8.838236</td>
    </tr>
    <tr>
      <th>Chemicals and Chemical Products CAN</th>
      <td>138.983126</td>
      <td>20.517223</td>
      <td>-3.989016</td>
      <td>20.540082</td>
      <td>368.865838</td>
      <td>167.595343</td>
      <td>5242.401082</td>
      <td>1071.349915</td>
      <td>74.655237</td>
      <td>190.401683</td>
      <td>64.837102</td>
      <td>45.541225</td>
      <td>194.087617</td>
      <td>105.362712</td>
    </tr>
    <tr>
      <th>Rubber and Plastics CAN</th>
      <td>615.000659</td>
      <td>-5.485196</td>
      <td>-2.165317</td>
      <td>3.684189</td>
      <td>208.381066</td>
      <td>6.947915</td>
      <td>225.619993</td>
      <td>254.201643</td>
      <td>28.065929</td>
      <td>57.118470</td>
      <td>209.260038</td>
      <td>33.442211</td>
      <td>622.758890</td>
      <td>107.755637</td>
    </tr>
    <tr>
      <th>Other Non-Metallic Mineral CAN</th>
      <td>37.686334</td>
      <td>-6.034742</td>
      <td>-0.020945</td>
      <td>-5.691329</td>
      <td>1.953592</td>
      <td>2.751273</td>
      <td>6.567078</td>
      <td>0.007347</td>
      <td>19.894558</td>
      <td>7.537994</td>
      <td>3.417872</td>
      <td>-30.315791</td>
      <td>34.372983</td>
      <td>-5.991775</td>
    </tr>
    <tr>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <td>441.522745</td>
      <td>1.252931</td>
      <td>-0.689260</td>
      <td>7.243511</td>
      <td>70.557905</td>
      <td>15.398824</td>
      <td>179.812687</td>
      <td>86.332796</td>
      <td>93.842456</td>
      <td>7043.731760</td>
      <td>1806.429367</td>
      <td>870.024695</td>
      <td>2638.119637</td>
      <td>457.905073</td>
    </tr>
    <tr>
      <th>Machinery, Nec CAN</th>
      <td>79.882741</td>
      <td>-0.956693</td>
      <td>-0.073549</td>
      <td>9.811351</td>
      <td>51.914535</td>
      <td>3.840104</td>
      <td>78.857989</td>
      <td>37.976564</td>
      <td>19.238580</td>
      <td>84.936923</td>
      <td>497.526483</td>
      <td>212.134339</td>
      <td>514.478144</td>
      <td>23.914723</td>
    </tr>
    <tr>
      <th>Electrical and Optical Equipment CAN</th>
      <td>57.572741</td>
      <td>-14.452041</td>
      <td>-0.607665</td>
      <td>-2.523705</td>
      <td>29.003530</td>
      <td>2.498136</td>
      <td>48.119819</td>
      <td>-1.819856</td>
      <td>7.427979</td>
      <td>56.344837</td>
      <td>293.450998</td>
      <td>-1732.026074</td>
      <td>349.719321</td>
      <td>21.928855</td>
    </tr>
    <tr>
      <th>Transport Equipment CAN</th>
      <td>31.069409</td>
      <td>-1.877063</td>
      <td>-0.064311</td>
      <td>-11.266042</td>
      <td>28.612944</td>
      <td>1.854449</td>
      <td>25.932046</td>
      <td>4.189409</td>
      <td>4.376281</td>
      <td>-1.840668</td>
      <td>42.650056</td>
      <td>-27.617836</td>
      <td>2174.567625</td>
      <td>4.057603</td>
    </tr>
    <tr>
      <th>Manufacturing, Nec; Recycling CAN</th>
      <td>6.651632</td>
      <td>-21.801166</td>
      <td>-0.549106</td>
      <td>-40.860726</td>
      <td>10.818039</td>
      <td>-0.353871</td>
      <td>8.637451</td>
      <td>4.334872</td>
      <td>-1.889732</td>
      <td>31.908133</td>
      <td>16.540490</td>
      <td>-2.991340</td>
      <td>46.628850</td>
      <td>67.763295</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>If we look at the evolution of the trade of inputs for the US-CAN (inputs into US from Canada), we see that in 1995 the biggest sectors for inputs were 'Wood and Products of Wood', 'Pulp, Paper, Printing and Publishing', 'Transport Equipment', 'Electrical and Optical Equipment', 'Chemicals and Chemical Products', 'Basic Metals and Fabricated Metal' and 'Rubber and Plastic'. In 2011 however, the biggest losses are endured in the 'Transport Equipment' and 'Electrical and Optical Equipment' sectors. We will see in the next part that it is due to the Mexican production in those sectors. Next, we look at the inputs into Canada from Mexico.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTCM1995</span> <span class="o">=</span> <span class="n">WIOT1995</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;CAN-MEX&#39;</span><span class="p">)</span>
<span class="n">IOTCM1995</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[10]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco CAN</th>
      <th>Textiles and Textile Products CAN</th>
      <th>Leather, Leather and Footwear CAN</th>
      <th>Wood and Products of Wood and Cork CAN</th>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <th>Chemicals and Chemical Products CAN</th>
      <th>Rubber and Plastics CAN</th>
      <th>Other Non-Metallic Mineral CAN</th>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <th>Machinery, Nec CAN</th>
      <th>Electrical and Optical Equipment CAN</th>
      <th>Transport Equipment CAN</th>
      <th>Manufacturing, Nec; Recycling CAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco MEX</td>
      <td>6.130200</td>
      <td>0.001709</td>
      <td>0.034274</td>
      <td>0.000864</td>
      <td>0.023783</td>
      <td>0.001214</td>
      <td>0.060584</td>
      <td>0.015333</td>
      <td>0.000554</td>
      <td>0.003682</td>
      <td>0.006416</td>
      <td>0.014942</td>
      <td>0.013277</td>
      <td>0.003653</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products MEX</td>
      <td>0.185047</td>
      <td>22.478058</td>
      <td>0.353997</td>
      <td>0.061122</td>
      <td>0.704802</td>
      <td>0.002452</td>
      <td>0.582411</td>
      <td>1.010379</td>
      <td>0.028731</td>
      <td>0.131654</td>
      <td>0.161999</td>
      <td>0.092118</td>
      <td>3.762016</td>
      <td>2.671665</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear MEX</td>
      <td>0.005361</td>
      <td>0.522726</td>
      <td>1.581082</td>
      <td>0.000876</td>
      <td>0.002449</td>
      <td>0.000306</td>
      <td>0.003326</td>
      <td>0.006522</td>
      <td>0.000511</td>
      <td>0.004779</td>
      <td>0.004323</td>
      <td>0.019199</td>
      <td>0.694981</td>
      <td>0.757608</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork MEX</td>
      <td>0.007077</td>
      <td>0.011064</td>
      <td>0.000407</td>
      <td>0.302566</td>
      <td>0.370993</td>
      <td>0.002735</td>
      <td>0.005169</td>
      <td>0.012946</td>
      <td>0.005354</td>
      <td>0.028583</td>
      <td>0.007654</td>
      <td>0.010251</td>
      <td>0.031528</td>
      <td>0.108601</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing MEX</td>
      <td>0.715542</td>
      <td>0.141617</td>
      <td>0.007971</td>
      <td>0.055706</td>
      <td>3.345305</td>
      <td>0.039132</td>
      <td>0.158206</td>
      <td>0.102513</td>
      <td>0.091398</td>
      <td>0.094682</td>
      <td>0.183366</td>
      <td>0.177942</td>
      <td>0.336367</td>
      <td>0.132982</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel MEX</td>
      <td>0.019285</td>
      <td>0.007335</td>
      <td>0.001544</td>
      <td>0.013295</td>
      <td>0.068010</td>
      <td>0.171248</td>
      <td>0.286117</td>
      <td>0.092888</td>
      <td>0.015028</td>
      <td>0.057747</td>
      <td>0.019279</td>
      <td>0.005480</td>
      <td>0.021571</td>
      <td>0.006356</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products MEX</td>
      <td>0.847102</td>
      <td>0.511302</td>
      <td>0.101865</td>
      <td>0.481836</td>
      <td>3.247316</td>
      <td>0.814289</td>
      <td>13.110639</td>
      <td>6.728223</td>
      <td>0.337547</td>
      <td>1.244288</td>
      <td>0.804971</td>
      <td>0.278706</td>
      <td>1.033449</td>
      <td>0.354335</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics MEX</td>
      <td>4.530323</td>
      <td>0.418146</td>
      <td>0.298790</td>
      <td>0.684797</td>
      <td>1.427328</td>
      <td>0.270167</td>
      <td>2.654549</td>
      <td>5.323222</td>
      <td>0.421220</td>
      <td>1.522240</td>
      <td>2.138936</td>
      <td>1.934502</td>
      <td>10.592984</td>
      <td>2.067838</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral MEX</td>
      <td>0.768036</td>
      <td>0.040055</td>
      <td>0.000188</td>
      <td>0.272009</td>
      <td>0.091115</td>
      <td>0.148033</td>
      <td>0.483556</td>
      <td>0.373381</td>
      <td>4.364733</td>
      <td>1.842324</td>
      <td>2.193337</td>
      <td>0.465103</td>
      <td>2.785054</td>
      <td>0.156105</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal MEX</td>
      <td>4.762618</td>
      <td>0.100236</td>
      <td>0.005500</td>
      <td>0.835927</td>
      <td>0.356774</td>
      <td>0.066449</td>
      <td>0.934013</td>
      <td>1.273116</td>
      <td>0.598958</td>
      <td>71.734643</td>
      <td>13.993608</td>
      <td>14.149966</td>
      <td>26.765288</td>
      <td>3.744716</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec MEX</td>
      <td>0.109072</td>
      <td>0.009163</td>
      <td>0.001125</td>
      <td>0.037208</td>
      <td>0.030441</td>
      <td>0.002658</td>
      <td>0.033106</td>
      <td>0.101851</td>
      <td>0.011210</td>
      <td>0.840779</td>
      <td>1.745102</td>
      <td>3.567757</td>
      <td>6.272970</td>
      <td>0.122812</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment MEX</td>
      <td>0.175494</td>
      <td>0.357430</td>
      <td>0.009567</td>
      <td>0.166928</td>
      <td>1.157800</td>
      <td>0.011496</td>
      <td>0.303941</td>
      <td>0.412038</td>
      <td>0.094949</td>
      <td>0.741993</td>
      <td>66.844183</td>
      <td>136.754602</td>
      <td>26.209923</td>
      <td>1.371652</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment MEX</td>
      <td>0.248301</td>
      <td>0.429745</td>
      <td>0.041910</td>
      <td>0.122103</td>
      <td>0.114363</td>
      <td>0.011686</td>
      <td>0.159731</td>
      <td>4.778689</td>
      <td>0.027343</td>
      <td>4.003999</td>
      <td>5.309975</td>
      <td>11.006899</td>
      <td>698.519098</td>
      <td>0.353032</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling MEX</td>
      <td>0.169618</td>
      <td>0.598369</td>
      <td>0.016576</td>
      <td>0.028591</td>
      <td>0.067457</td>
      <td>0.007333</td>
      <td>0.123182</td>
      <td>0.146734</td>
      <td>0.030510</td>
      <td>0.245132</td>
      <td>0.353847</td>
      <td>0.533742</td>
      <td>1.933433</td>
      <td>0.918116</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[11]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTCM2011</span> <span class="o">=</span> <span class="n">WIOT2011</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;CAN-MEX&#39;</span><span class="p">)</span>
<span class="n">IOTCM2011</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[11]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco CAN</th>
      <th>Textiles and Textile Products CAN</th>
      <th>Leather, Leather and Footwear CAN</th>
      <th>Wood and Products of Wood and Cork CAN</th>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <th>Chemicals and Chemical Products CAN</th>
      <th>Rubber and Plastics CAN</th>
      <th>Other Non-Metallic Mineral CAN</th>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <th>Machinery, Nec CAN</th>
      <th>Electrical and Optical Equipment CAN</th>
      <th>Transport Equipment CAN</th>
      <th>Manufacturing, Nec; Recycling CAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco MEX</td>
      <td>18.616173</td>
      <td>0.025908</td>
      <td>0.000240</td>
      <td>0.004166</td>
      <td>0.082654</td>
      <td>0.012863</td>
      <td>0.193446</td>
      <td>0.059912</td>
      <td>0.001690</td>
      <td>0.010293</td>
      <td>0.054391</td>
      <td>0.086254</td>
      <td>0.092132</td>
      <td>0.007767</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products MEX</td>
      <td>0.543482</td>
      <td>37.945055</td>
      <td>0.219794</td>
      <td>0.012249</td>
      <td>1.162393</td>
      <td>0.010079</td>
      <td>0.663257</td>
      <td>5.768420</td>
      <td>0.010436</td>
      <td>0.397346</td>
      <td>1.464609</td>
      <td>0.067527</td>
      <td>4.853630</td>
      <td>12.254054</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear MEX</td>
      <td>0.012783</td>
      <td>0.377273</td>
      <td>0.782742</td>
      <td>0.001594</td>
      <td>0.005190</td>
      <td>0.001284</td>
      <td>0.005151</td>
      <td>0.023663</td>
      <td>0.001028</td>
      <td>0.009862</td>
      <td>0.010347</td>
      <td>0.016180</td>
      <td>0.034851</td>
      <td>1.140611</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork MEX</td>
      <td>0.030650</td>
      <td>0.023408</td>
      <td>0.000563</td>
      <td>1.933230</td>
      <td>1.072136</td>
      <td>0.004947</td>
      <td>0.018063</td>
      <td>0.100435</td>
      <td>0.024948</td>
      <td>0.091132</td>
      <td>0.026604</td>
      <td>0.019398</td>
      <td>0.081457</td>
      <td>0.970155</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing MEX</td>
      <td>6.041249</td>
      <td>0.458024</td>
      <td>0.016738</td>
      <td>0.312035</td>
      <td>21.289310</td>
      <td>0.347233</td>
      <td>1.235566</td>
      <td>0.917141</td>
      <td>0.706098</td>
      <td>0.346865</td>
      <td>1.218970</td>
      <td>0.369196</td>
      <td>0.957847</td>
      <td>0.843801</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel MEX</td>
      <td>1.771219</td>
      <td>0.296551</td>
      <td>0.032349</td>
      <td>1.697600</td>
      <td>4.533215</td>
      <td>39.789976</td>
      <td>64.027357</td>
      <td>2.462773</td>
      <td>2.956511</td>
      <td>8.742276</td>
      <td>1.019142</td>
      <td>1.028279</td>
      <td>0.942143</td>
      <td>1.362578</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products MEX</td>
      <td>2.221906</td>
      <td>1.417879</td>
      <td>0.066350</td>
      <td>2.280410</td>
      <td>5.476605</td>
      <td>8.738063</td>
      <td>67.619907</td>
      <td>32.968750</td>
      <td>0.816894</td>
      <td>4.280103</td>
      <td>3.765310</td>
      <td>1.095149</td>
      <td>3.643371</td>
      <td>2.765520</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics MEX</td>
      <td>22.658009</td>
      <td>0.921865</td>
      <td>0.877175</td>
      <td>2.821921</td>
      <td>4.599578</td>
      <td>2.374456</td>
      <td>8.684916</td>
      <td>38.651786</td>
      <td>1.765871</td>
      <td>5.350366</td>
      <td>3.420641</td>
      <td>5.807788</td>
      <td>40.983594</td>
      <td>13.773790</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral MEX</td>
      <td>1.886884</td>
      <td>0.007553</td>
      <td>0.000340</td>
      <td>0.639489</td>
      <td>0.180381</td>
      <td>0.003928</td>
      <td>0.569942</td>
      <td>1.180766</td>
      <td>22.063829</td>
      <td>4.571684</td>
      <td>1.747426</td>
      <td>0.672050</td>
      <td>11.499187</td>
      <td>0.645217</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal MEX</td>
      <td>8.176582</td>
      <td>0.326368</td>
      <td>0.023671</td>
      <td>2.097078</td>
      <td>0.901465</td>
      <td>0.937379</td>
      <td>8.538191</td>
      <td>6.772064</td>
      <td>4.931294</td>
      <td>746.822566</td>
      <td>159.855312</td>
      <td>84.963555</td>
      <td>240.431262</td>
      <td>29.577158</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec MEX</td>
      <td>0.290202</td>
      <td>0.018855</td>
      <td>0.004892</td>
      <td>0.077092</td>
      <td>0.130371</td>
      <td>0.024339</td>
      <td>0.141126</td>
      <td>0.556220</td>
      <td>0.030651</td>
      <td>2.641175</td>
      <td>17.361575</td>
      <td>26.975651</td>
      <td>43.849722</td>
      <td>0.695376</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment MEX</td>
      <td>0.967917</td>
      <td>0.394235</td>
      <td>0.034852</td>
      <td>4.742877</td>
      <td>5.834646</td>
      <td>0.126804</td>
      <td>0.794825</td>
      <td>7.125025</td>
      <td>0.389547</td>
      <td>8.135451</td>
      <td>492.019352</td>
      <td>635.828376</td>
      <td>328.451627</td>
      <td>20.881213</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment MEX</td>
      <td>1.368819</td>
      <td>1.984469</td>
      <td>0.093441</td>
      <td>0.489535</td>
      <td>0.602319</td>
      <td>0.135550</td>
      <td>0.584029</td>
      <td>19.092151</td>
      <td>0.131729</td>
      <td>4.261266</td>
      <td>27.724335</td>
      <td>33.352928</td>
      <td>3171.559313</td>
      <td>2.424795</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling MEX</td>
      <td>1.185398</td>
      <td>5.196600</td>
      <td>0.066403</td>
      <td>0.237093</td>
      <td>0.570884</td>
      <td>0.157831</td>
      <td>0.802867</td>
      <td>2.638443</td>
      <td>0.377290</td>
      <td>1.974750</td>
      <td>3.561754</td>
      <td>3.881253</td>
      <td>9.691578</td>
      <td>11.399816</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[12]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTCM2011</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">subtract</span><span class="p">(</span><span class="n">IOTCM1995</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">),</span> <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[12]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Food, Beverages and Tobacco CAN</th>
      <th>Textiles and Textile Products CAN</th>
      <th>Leather, Leather and Footwear CAN</th>
      <th>Wood and Products of Wood and Cork CAN</th>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <th>Chemicals and Chemical Products CAN</th>
      <th>Rubber and Plastics CAN</th>
      <th>Other Non-Metallic Mineral CAN</th>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <th>Machinery, Nec CAN</th>
      <th>Electrical and Optical Equipment CAN</th>
      <th>Transport Equipment CAN</th>
      <th>Manufacturing, Nec; Recycling CAN</th>
    </tr>
    <tr>
      <th>Sectors</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Food, Beverages and Tobacco MEX</th>
      <td>12.485973</td>
      <td>0.024200</td>
      <td>-0.034034</td>
      <td>0.003302</td>
      <td>0.058871</td>
      <td>0.011650</td>
      <td>0.132862</td>
      <td>0.044579</td>
      <td>0.001136</td>
      <td>0.006612</td>
      <td>0.047975</td>
      <td>0.071312</td>
      <td>0.078855</td>
      <td>0.004114</td>
    </tr>
    <tr>
      <th>Textiles and Textile Products MEX</th>
      <td>0.358435</td>
      <td>15.466997</td>
      <td>-0.134203</td>
      <td>-0.048873</td>
      <td>0.457591</td>
      <td>0.007627</td>
      <td>0.080846</td>
      <td>4.758042</td>
      <td>-0.018296</td>
      <td>0.265692</td>
      <td>1.302610</td>
      <td>-0.024590</td>
      <td>1.091614</td>
      <td>9.582390</td>
    </tr>
    <tr>
      <th>Leather, Leather and Footwear MEX</th>
      <td>0.007422</td>
      <td>-0.145453</td>
      <td>-0.798340</td>
      <td>0.000718</td>
      <td>0.002741</td>
      <td>0.000978</td>
      <td>0.001825</td>
      <td>0.017141</td>
      <td>0.000517</td>
      <td>0.005084</td>
      <td>0.006024</td>
      <td>-0.003019</td>
      <td>-0.660130</td>
      <td>0.383003</td>
    </tr>
    <tr>
      <th>Wood and Products of Wood and Cork MEX</th>
      <td>0.023572</td>
      <td>0.012344</td>
      <td>0.000157</td>
      <td>1.630665</td>
      <td>0.701143</td>
      <td>0.002212</td>
      <td>0.012894</td>
      <td>0.087489</td>
      <td>0.019594</td>
      <td>0.062550</td>
      <td>0.018951</td>
      <td>0.009147</td>
      <td>0.049930</td>
      <td>0.861554</td>
    </tr>
    <tr>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <td>5.325706</td>
      <td>0.316407</td>
      <td>0.008768</td>
      <td>0.256329</td>
      <td>17.944005</td>
      <td>0.308101</td>
      <td>1.077360</td>
      <td>0.814629</td>
      <td>0.614700</td>
      <td>0.252183</td>
      <td>1.035604</td>
      <td>0.191255</td>
      <td>0.621480</td>
      <td>0.710820</td>
    </tr>
    <tr>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <td>1.751934</td>
      <td>0.289216</td>
      <td>0.030805</td>
      <td>1.684305</td>
      <td>4.465205</td>
      <td>39.618728</td>
      <td>63.741241</td>
      <td>2.369886</td>
      <td>2.941483</td>
      <td>8.684530</td>
      <td>0.999863</td>
      <td>1.022799</td>
      <td>0.920572</td>
      <td>1.356222</td>
    </tr>
    <tr>
      <th>Chemicals and Chemical Products MEX</th>
      <td>1.374805</td>
      <td>0.906577</td>
      <td>-0.035515</td>
      <td>1.798574</td>
      <td>2.229289</td>
      <td>7.923774</td>
      <td>54.509268</td>
      <td>26.240528</td>
      <td>0.479347</td>
      <td>3.035815</td>
      <td>2.960339</td>
      <td>0.816443</td>
      <td>2.609922</td>
      <td>2.411185</td>
    </tr>
    <tr>
      <th>Rubber and Plastics MEX</th>
      <td>18.127686</td>
      <td>0.503720</td>
      <td>0.578385</td>
      <td>2.137124</td>
      <td>3.172249</td>
      <td>2.104289</td>
      <td>6.030366</td>
      <td>33.328563</td>
      <td>1.344651</td>
      <td>3.828127</td>
      <td>1.281705</td>
      <td>3.873286</td>
      <td>30.390609</td>
      <td>11.705952</td>
    </tr>
    <tr>
      <th>Other Non-Metallic Mineral MEX</th>
      <td>1.118848</td>
      <td>-0.032502</td>
      <td>0.000152</td>
      <td>0.367480</td>
      <td>0.089266</td>
      <td>-0.144105</td>
      <td>0.086386</td>
      <td>0.807384</td>
      <td>17.699096</td>
      <td>2.729359</td>
      <td>-0.445911</td>
      <td>0.206947</td>
      <td>8.714133</td>
      <td>0.489112</td>
    </tr>
    <tr>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <td>3.413964</td>
      <td>0.226133</td>
      <td>0.018171</td>
      <td>1.261151</td>
      <td>0.544691</td>
      <td>0.870930</td>
      <td>7.604178</td>
      <td>5.498947</td>
      <td>4.332335</td>
      <td>675.087923</td>
      <td>145.861705</td>
      <td>70.813589</td>
      <td>213.665974</td>
      <td>25.832442</td>
    </tr>
    <tr>
      <th>Machinery, Nec MEX</th>
      <td>0.181130</td>
      <td>0.009692</td>
      <td>0.003767</td>
      <td>0.039883</td>
      <td>0.099930</td>
      <td>0.021682</td>
      <td>0.108020</td>
      <td>0.454369</td>
      <td>0.019440</td>
      <td>1.800395</td>
      <td>15.616474</td>
      <td>23.407894</td>
      <td>37.576752</td>
      <td>0.572565</td>
    </tr>
    <tr>
      <th>Electrical and Optical Equipment MEX</th>
      <td>0.792423</td>
      <td>0.036805</td>
      <td>0.025285</td>
      <td>4.575949</td>
      <td>4.676846</td>
      <td>0.115307</td>
      <td>0.490885</td>
      <td>6.712987</td>
      <td>0.294598</td>
      <td>7.393459</td>
      <td>425.175169</td>
      <td>499.073774</td>
      <td>302.241704</td>
      <td>19.509561</td>
    </tr>
    <tr>
      <th>Transport Equipment MEX</th>
      <td>1.120518</td>
      <td>1.554724</td>
      <td>0.051531</td>
      <td>0.367432</td>
      <td>0.487955</td>
      <td>0.123864</td>
      <td>0.424298</td>
      <td>14.313461</td>
      <td>0.104386</td>
      <td>0.257267</td>
      <td>22.414359</td>
      <td>22.346029</td>
      <td>2473.040215</td>
      <td>2.071763</td>
    </tr>
    <tr>
      <th>Manufacturing, Nec; Recycling MEX</th>
      <td>1.015780</td>
      <td>4.598231</td>
      <td>0.049826</td>
      <td>0.208503</td>
      <td>0.503428</td>
      <td>0.150498</td>
      <td>0.679686</td>
      <td>2.491709</td>
      <td>0.346779</td>
      <td>1.729618</td>
      <td>3.207907</td>
      <td>3.347512</td>
      <td>7.758145</td>
      <td>10.481700</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>When we observe the re-exports of inputs from Mexico into Canada, two things are very remarkable. First of all, in comparison with the previous tables, the absolute numbers are extremely small. This points to the small size of the regional value chain between the two countries. As mentioned before, it is the US that plays a central role in the North-American value chain and thus NAFTA. Secondly, even with those smaller absolute numbers, we see that the inputs have increased from Mexico into Canada for the following sectors: '', 'Wood and Products of Wood', 'Chemicals and Chemical Products', 'Basic Metals and Fabricated Metal', 'Transport Equipment' and 'Manufacturing and Recycling'. This will also be very visible in the last part, when we look at the evolution of the Revealed Comparative Advantage where Mexico will have gained a lot of RCA in the last four sectors. Following, we look at the inputs into Mexico from US.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[13]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTMU1995</span> <span class="o">=</span> <span class="n">WIOT1995</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;MEX-US&#39;</span><span class="p">)</span>
<span class="n">IOTMU1995</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[13]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco MEX</th>
      <th>Textiles and Textile Products MEX</th>
      <th>Leather, Leather and Footwear MEX</th>
      <th>Wood and Products of Wood and Cork MEX</th>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <th>Chemicals and Chemical Products MEX</th>
      <th>Rubber and Plastics MEX</th>
      <th>Other Non-Metallic Mineral MEX</th>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <th>Machinery, Nec MEX</th>
      <th>Electrical and Optical Equipment MEX</th>
      <th>Transport Equipment MEX</th>
      <th>Manufacturing, Nec; Recycling MEX</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco USA</td>
      <td>474.055486</td>
      <td>1.013759</td>
      <td>24.548005</td>
      <td>0.112326</td>
      <td>2.506574</td>
      <td>0.620265</td>
      <td>9.697550</td>
      <td>2.554098</td>
      <td>0.695823</td>
      <td>1.017196</td>
      <td>0.315003</td>
      <td>1.546330</td>
      <td>1.025472</td>
      <td>0.680626</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products USA</td>
      <td>14.822504</td>
      <td>559.498658</td>
      <td>97.862225</td>
      <td>0.703434</td>
      <td>43.092407</td>
      <td>1.635693</td>
      <td>17.404670</td>
      <td>25.434460</td>
      <td>3.779261</td>
      <td>11.965316</td>
      <td>2.583619</td>
      <td>31.693799</td>
      <td>184.229958</td>
      <td>64.236329</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear USA</td>
      <td>0.533773</td>
      <td>1.936898</td>
      <td>11.745915</td>
      <td>0.040788</td>
      <td>0.159474</td>
      <td>0.022301</td>
      <td>0.183629</td>
      <td>0.158496</td>
      <td>0.245987</td>
      <td>0.645560</td>
      <td>0.104469</td>
      <td>0.216696</td>
      <td>4.280031</td>
      <td>0.686674</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork USA</td>
      <td>2.281526</td>
      <td>1.219766</td>
      <td>0.897064</td>
      <td>46.199511</td>
      <td>1.574420</td>
      <td>0.157534</td>
      <td>1.584911</td>
      <td>1.080079</td>
      <td>3.066053</td>
      <td>4.206885</td>
      <td>0.850409</td>
      <td>16.148494</td>
      <td>6.348133</td>
      <td>47.233209</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing USA</td>
      <td>230.463068</td>
      <td>36.561683</td>
      <td>7.328261</td>
      <td>2.359635</td>
      <td>693.609456</td>
      <td>2.100375</td>
      <td>79.356210</td>
      <td>40.101686</td>
      <td>49.003144</td>
      <td>35.692949</td>
      <td>13.162720</td>
      <td>220.097013</td>
      <td>65.698740</td>
      <td>70.010354</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel USA</td>
      <td>36.876270</td>
      <td>5.511692</td>
      <td>1.424459</td>
      <td>2.488358</td>
      <td>9.024548</td>
      <td>9.102673</td>
      <td>51.704477</td>
      <td>14.876317</td>
      <td>16.805196</td>
      <td>38.006352</td>
      <td>1.909072</td>
      <td>7.795355</td>
      <td>8.221020</td>
      <td>5.346422</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products USA</td>
      <td>239.456504</td>
      <td>57.689906</td>
      <td>26.886212</td>
      <td>8.479493</td>
      <td>104.759648</td>
      <td>105.085404</td>
      <td>955.534091</td>
      <td>405.852691</td>
      <td>66.559268</td>
      <td>71.428341</td>
      <td>28.522225</td>
      <td>169.313184</td>
      <td>129.732860</td>
      <td>64.855559</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics USA</td>
      <td>367.534829</td>
      <td>50.664200</td>
      <td>22.947489</td>
      <td>2.712237</td>
      <td>74.770105</td>
      <td>9.024263</td>
      <td>52.727649</td>
      <td>129.235817</td>
      <td>14.139955</td>
      <td>61.964508</td>
      <td>27.706118</td>
      <td>403.613262</td>
      <td>660.326962</td>
      <td>154.232161</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral USA</td>
      <td>50.297323</td>
      <td>1.463973</td>
      <td>0.355058</td>
      <td>0.762113</td>
      <td>2.969845</td>
      <td>0.347356</td>
      <td>4.936336</td>
      <td>2.137756</td>
      <td>56.316089</td>
      <td>12.686012</td>
      <td>2.220088</td>
      <td>36.079689</td>
      <td>24.364018</td>
      <td>9.210731</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal USA</td>
      <td>91.857935</td>
      <td>38.040120</td>
      <td>7.235857</td>
      <td>8.452010</td>
      <td>29.790799</td>
      <td>28.698441</td>
      <td>32.063802</td>
      <td>74.837953</td>
      <td>24.110148</td>
      <td>1248.764239</td>
      <td>151.264488</td>
      <td>528.386781</td>
      <td>675.583161</td>
      <td>161.712093</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec USA</td>
      <td>19.364323</td>
      <td>16.591657</td>
      <td>4.307866</td>
      <td>4.550821</td>
      <td>8.673636</td>
      <td>22.133720</td>
      <td>10.327323</td>
      <td>25.565169</td>
      <td>7.133391</td>
      <td>98.693373</td>
      <td>166.962929</td>
      <td>505.865195</td>
      <td>376.496295</td>
      <td>59.649820</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment USA</td>
      <td>9.070112</td>
      <td>16.268063</td>
      <td>1.371503</td>
      <td>0.569810</td>
      <td>14.902217</td>
      <td>5.654130</td>
      <td>13.797326</td>
      <td>29.238367</td>
      <td>5.865276</td>
      <td>116.886448</td>
      <td>182.036843</td>
      <td>6068.962569</td>
      <td>1203.047694</td>
      <td>198.024062</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment USA</td>
      <td>69.932726</td>
      <td>36.094122</td>
      <td>5.100406</td>
      <td>2.784207</td>
      <td>20.320296</td>
      <td>1.380947</td>
      <td>22.537631</td>
      <td>19.650422</td>
      <td>23.287624</td>
      <td>88.582916</td>
      <td>18.129117</td>
      <td>135.948674</td>
      <td>2243.405489</td>
      <td>32.149714</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling USA</td>
      <td>2.299746</td>
      <td>4.939731</td>
      <td>0.592666</td>
      <td>0.365950</td>
      <td>1.629212</td>
      <td>0.257362</td>
      <td>1.568800</td>
      <td>1.668512</td>
      <td>0.456448</td>
      <td>3.546101</td>
      <td>1.562115</td>
      <td>48.296099</td>
      <td>10.620830</td>
      <td>10.574104</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[14]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTMU2011</span> <span class="o">=</span> <span class="n">WIOT2011</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;MEX-US&#39;</span><span class="p">)</span>
<span class="n">IOTMU2011</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[14]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco MEX</th>
      <th>Textiles and Textile Products MEX</th>
      <th>Leather, Leather and Footwear MEX</th>
      <th>Wood and Products of Wood and Cork MEX</th>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <th>Chemicals and Chemical Products MEX</th>
      <th>Rubber and Plastics MEX</th>
      <th>Other Non-Metallic Mineral MEX</th>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <th>Machinery, Nec MEX</th>
      <th>Electrical and Optical Equipment MEX</th>
      <th>Transport Equipment MEX</th>
      <th>Manufacturing, Nec; Recycling MEX</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco USA</td>
      <td>2193.904067</td>
      <td>5.222084</td>
      <td>70.633487</td>
      <td>0.562273</td>
      <td>12.565073</td>
      <td>8.351173</td>
      <td>64.686528</td>
      <td>30.168689</td>
      <td>5.531307</td>
      <td>8.817011</td>
      <td>4.058755</td>
      <td>18.346827</td>
      <td>12.691485</td>
      <td>7.004021</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products USA</td>
      <td>31.575676</td>
      <td>971.423068</td>
      <td>97.506927</td>
      <td>0.778450</td>
      <td>82.903264</td>
      <td>2.959866</td>
      <td>22.940972</td>
      <td>54.200658</td>
      <td>5.478390</td>
      <td>24.488090</td>
      <td>7.299244</td>
      <td>95.784247</td>
      <td>556.390561</td>
      <td>176.619385</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear USA</td>
      <td>0.568223</td>
      <td>1.807424</td>
      <td>8.163677</td>
      <td>0.025686</td>
      <td>0.186848</td>
      <td>0.020433</td>
      <td>0.126154</td>
      <td>0.184126</td>
      <td>0.212639</td>
      <td>0.732697</td>
      <td>0.157369</td>
      <td>0.333010</td>
      <td>6.253682</td>
      <td>0.921604</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork USA</td>
      <td>5.406275</td>
      <td>2.254897</td>
      <td>1.262506</td>
      <td>52.717548</td>
      <td>2.415519</td>
      <td>0.353858</td>
      <td>2.501420</td>
      <td>2.290464</td>
      <td>5.008617</td>
      <td>9.747749</td>
      <td>2.648770</td>
      <td>43.196937</td>
      <td>17.821119</td>
      <td>108.705153</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing USA</td>
      <td>537.669843</td>
      <td>83.027844</td>
      <td>12.437259</td>
      <td>2.975941</td>
      <td>1182.515744</td>
      <td>5.166375</td>
      <td>118.210867</td>
      <td>83.875559</td>
      <td>90.270249</td>
      <td>85.366861</td>
      <td>37.805018</td>
      <td>440.254660</td>
      <td>180.780734</td>
      <td>177.351079</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel USA</td>
      <td>793.831897</td>
      <td>62.059012</td>
      <td>12.516272</td>
      <td>32.753887</td>
      <td>116.955978</td>
      <td>157.048429</td>
      <td>483.197237</td>
      <td>118.254690</td>
      <td>299.986255</td>
      <td>913.548510</td>
      <td>38.943969</td>
      <td>121.097064</td>
      <td>148.881065</td>
      <td>103.487308</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products USA</td>
      <td>1047.352573</td>
      <td>164.426812</td>
      <td>74.184003</td>
      <td>21.300585</td>
      <td>332.513742</td>
      <td>437.098781</td>
      <td>2756.570860</td>
      <td>1545.626628</td>
      <td>234.984496</td>
      <td>325.330790</td>
      <td>165.520544</td>
      <td>799.754564</td>
      <td>622.727726</td>
      <td>301.019121</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics USA</td>
      <td>721.493465</td>
      <td>69.776693</td>
      <td>28.298585</td>
      <td>3.038672</td>
      <td>107.576528</td>
      <td>17.741818</td>
      <td>74.653764</td>
      <td>219.742807</td>
      <td>22.236438</td>
      <td>107.889033</td>
      <td>72.428923</td>
      <td>955.205238</td>
      <td>1565.414259</td>
      <td>327.821763</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral USA</td>
      <td>66.806531</td>
      <td>2.401695</td>
      <td>0.400439</td>
      <td>0.583279</td>
      <td>2.990724</td>
      <td>0.700225</td>
      <td>5.563214</td>
      <td>3.295755</td>
      <td>57.779989</td>
      <td>17.797584</td>
      <td>4.232731</td>
      <td>58.911881</td>
      <td>41.591021</td>
      <td>14.591469</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal USA</td>
      <td>183.938781</td>
      <td>69.381279</td>
      <td>11.785542</td>
      <td>10.025356</td>
      <td>80.933723</td>
      <td>51.544797</td>
      <td>65.873572</td>
      <td>178.592623</td>
      <td>59.662802</td>
      <td>4825.771030</td>
      <td>633.696248</td>
      <td>1924.008367</td>
      <td>2264.443485</td>
      <td>539.982706</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec USA</td>
      <td>49.948072</td>
      <td>22.775594</td>
      <td>6.264093</td>
      <td>6.214583</td>
      <td>14.968379</td>
      <td>50.072408</td>
      <td>18.084471</td>
      <td>51.058170</td>
      <td>13.390461</td>
      <td>248.114462</td>
      <td>526.579824</td>
      <td>1046.730888</td>
      <td>880.999751</td>
      <td>136.239253</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment USA</td>
      <td>23.093237</td>
      <td>24.735043</td>
      <td>2.068865</td>
      <td>0.878214</td>
      <td>17.151884</td>
      <td>11.752945</td>
      <td>29.619694</td>
      <td>43.940944</td>
      <td>7.737482</td>
      <td>165.318412</td>
      <td>308.602964</td>
      <td>7994.551693</td>
      <td>1796.352563</td>
      <td>239.341672</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment USA</td>
      <td>173.112524</td>
      <td>56.651467</td>
      <td>8.132514</td>
      <td>3.922944</td>
      <td>36.541864</td>
      <td>3.871152</td>
      <td>39.346204</td>
      <td>43.205211</td>
      <td>45.221334</td>
      <td>223.112301</td>
      <td>60.114482</td>
      <td>303.463819</td>
      <td>6658.403850</td>
      <td>94.123517</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling USA</td>
      <td>8.615303</td>
      <td>7.667430</td>
      <td>0.761826</td>
      <td>0.965284</td>
      <td>3.709826</td>
      <td>2.295021</td>
      <td>13.055084</td>
      <td>8.958515</td>
      <td>1.631905</td>
      <td>8.962977</td>
      <td>5.307482</td>
      <td>119.919286</td>
      <td>29.303818</td>
      <td>19.534330</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[15]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTMU2011</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">subtract</span><span class="p">(</span><span class="n">IOTMU1995</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">),</span> <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[15]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Food, Beverages and Tobacco MEX</th>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <th>Chemicals and Chemical Products MEX</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <th>Electrical and Optical Equipment MEX</th>
      <th>Food, Beverages and Tobacco MEX</th>
      <th>Leather, Leather and Footwear MEX</th>
      <th>Machinery, Nec MEX</th>
      <th>Manufacturing, Nec; Recycling MEX</th>
      <th>Other Non-Metallic Mineral MEX</th>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <th>Rubber and Plastics MEX</th>
      <th>Textiles and Textile Products MEX</th>
      <th>Transport Equipment MEX</th>
      <th>Wood and Products of Wood and Cork MEX</th>
    </tr>
    <tr>
      <th>Sectors</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Food, Beverages and Tobacco USA</th>
      <td>2193.904067</td>
      <td>7.799816</td>
      <td>54.988978</td>
      <td>7.730908</td>
      <td>16.800497</td>
      <td>-474.055486</td>
      <td>46.085482</td>
      <td>3.743752</td>
      <td>6.323396</td>
      <td>4.835484</td>
      <td>10.058498</td>
      <td>27.614591</td>
      <td>4.208325</td>
      <td>11.666012</td>
      <td>0.449946</td>
    </tr>
    <tr>
      <th>Textiles and Textile Products USA</th>
      <td>31.575676</td>
      <td>12.522774</td>
      <td>5.536302</td>
      <td>1.324172</td>
      <td>64.090448</td>
      <td>-14.822504</td>
      <td>-0.355299</td>
      <td>4.715625</td>
      <td>112.383057</td>
      <td>1.699129</td>
      <td>39.810857</td>
      <td>28.766198</td>
      <td>411.924409</td>
      <td>372.160603</td>
      <td>0.075016</td>
    </tr>
    <tr>
      <th>Leather, Leather and Footwear USA</th>
      <td>0.568223</td>
      <td>0.087137</td>
      <td>-0.057474</td>
      <td>-0.001868</td>
      <td>0.116314</td>
      <td>-0.533773</td>
      <td>-3.582239</td>
      <td>0.052900</td>
      <td>0.234930</td>
      <td>-0.033348</td>
      <td>0.027374</td>
      <td>0.025630</td>
      <td>-0.129474</td>
      <td>1.973651</td>
      <td>-0.015101</td>
    </tr>
    <tr>
      <th>Wood and Products of Wood and Cork USA</th>
      <td>5.406275</td>
      <td>5.540864</td>
      <td>0.916509</td>
      <td>0.196324</td>
      <td>27.048443</td>
      <td>-2.281526</td>
      <td>0.365443</td>
      <td>1.798362</td>
      <td>61.471945</td>
      <td>1.942565</td>
      <td>0.841099</td>
      <td>1.210385</td>
      <td>1.035131</td>
      <td>11.472986</td>
      <td>6.518037</td>
    </tr>
    <tr>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <td>537.669843</td>
      <td>49.673911</td>
      <td>38.854657</td>
      <td>3.066000</td>
      <td>220.157647</td>
      <td>-230.463068</td>
      <td>5.108997</td>
      <td>24.642299</td>
      <td>107.340725</td>
      <td>41.267105</td>
      <td>488.906289</td>
      <td>43.773872</td>
      <td>46.466161</td>
      <td>115.081994</td>
      <td>0.616306</td>
    </tr>
    <tr>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <td>793.831897</td>
      <td>875.542158</td>
      <td>431.492760</td>
      <td>147.945755</td>
      <td>113.301709</td>
      <td>-36.876270</td>
      <td>11.091813</td>
      <td>37.034897</td>
      <td>98.140886</td>
      <td>283.181059</td>
      <td>107.931430</td>
      <td>103.378373</td>
      <td>56.547320</td>
      <td>140.660045</td>
      <td>30.265529</td>
    </tr>
    <tr>
      <th>Chemicals and Chemical Products USA</th>
      <td>1047.352573</td>
      <td>253.902448</td>
      <td>1801.036768</td>
      <td>332.013377</td>
      <td>630.441380</td>
      <td>-239.456504</td>
      <td>47.297791</td>
      <td>136.998319</td>
      <td>236.163561</td>
      <td>168.425229</td>
      <td>227.754093</td>
      <td>1139.773937</td>
      <td>106.736906</td>
      <td>492.994866</td>
      <td>12.821092</td>
    </tr>
    <tr>
      <th>Rubber and Plastics USA</th>
      <td>721.493465</td>
      <td>45.924525</td>
      <td>21.926115</td>
      <td>8.717556</td>
      <td>551.591977</td>
      <td>-367.534829</td>
      <td>5.351096</td>
      <td>44.722806</td>
      <td>173.589602</td>
      <td>8.096483</td>
      <td>32.806423</td>
      <td>90.506990</td>
      <td>19.112493</td>
      <td>905.087297</td>
      <td>0.326436</td>
    </tr>
    <tr>
      <th>Other Non-Metallic Mineral USA</th>
      <td>66.806531</td>
      <td>5.111572</td>
      <td>0.626878</td>
      <td>0.352869</td>
      <td>22.832192</td>
      <td>-50.297323</td>
      <td>0.045381</td>
      <td>2.012643</td>
      <td>5.380739</td>
      <td>1.463900</td>
      <td>0.020879</td>
      <td>1.158000</td>
      <td>0.937722</td>
      <td>17.227004</td>
      <td>-0.178834</td>
    </tr>
    <tr>
      <th>Basic Metals and Fabricated Metal USA</th>
      <td>183.938781</td>
      <td>3577.006791</td>
      <td>33.809770</td>
      <td>22.846356</td>
      <td>1395.621586</td>
      <td>-91.857935</td>
      <td>4.549685</td>
      <td>482.431761</td>
      <td>378.270612</td>
      <td>35.552654</td>
      <td>51.142924</td>
      <td>103.754670</td>
      <td>31.341159</td>
      <td>1588.860324</td>
      <td>1.573346</td>
    </tr>
    <tr>
      <th>Machinery, Nec USA</th>
      <td>49.948072</td>
      <td>149.421090</td>
      <td>7.757147</td>
      <td>27.938688</td>
      <td>540.865693</td>
      <td>-19.364323</td>
      <td>1.956227</td>
      <td>359.616895</td>
      <td>76.589433</td>
      <td>6.257070</td>
      <td>6.294743</td>
      <td>25.493002</td>
      <td>6.183937</td>
      <td>504.503456</td>
      <td>1.663762</td>
    </tr>
    <tr>
      <th>Electrical and Optical Equipment USA</th>
      <td>23.093237</td>
      <td>48.431964</td>
      <td>15.822368</td>
      <td>6.098815</td>
      <td>1925.589123</td>
      <td>-9.070112</td>
      <td>0.697362</td>
      <td>126.566121</td>
      <td>41.317609</td>
      <td>1.872206</td>
      <td>2.249667</td>
      <td>14.702577</td>
      <td>8.466980</td>
      <td>593.304869</td>
      <td>0.308404</td>
    </tr>
    <tr>
      <th>Transport Equipment USA</th>
      <td>173.112524</td>
      <td>134.529385</td>
      <td>16.808573</td>
      <td>2.490205</td>
      <td>167.515146</td>
      <td>-69.932726</td>
      <td>3.032108</td>
      <td>41.985365</td>
      <td>61.973803</td>
      <td>21.933711</td>
      <td>16.221568</td>
      <td>23.554789</td>
      <td>20.557345</td>
      <td>4414.998362</td>
      <td>1.138737</td>
    </tr>
    <tr>
      <th>Manufacturing, Nec; Recycling USA</th>
      <td>8.615303</td>
      <td>5.416875</td>
      <td>11.486284</td>
      <td>2.037660</td>
      <td>71.623188</td>
      <td>-2.299746</td>
      <td>0.169161</td>
      <td>3.745367</td>
      <td>8.960226</td>
      <td>1.175456</td>
      <td>2.080614</td>
      <td>7.290003</td>
      <td>2.727700</td>
      <td>18.682987</td>
      <td>0.599334</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>While taking a look at the inputs from the US into Mexico, we observe that it is mostly the US that uses inputs from Mexico and not the other way around. The US exports relatively a lot in the sectors 'Food and Beverages', 'Coke, Refined Petroleum', 'Chemicals and Chemical Products', 'Rubber and Plastics', 'Bqsic Metals and Fabricated Metals' and 'Transport Equipment'. The evolution in those sectors is similar as before, in sectors where the trade already was large, it increased in absolute terms between the countries. We will see in part 4 that the RCA for the US has increased in the 'Coke, Refined Petroleum' and 'Transport Equipment' sectors. Following is the evolution of the inputs from Canada into Mexico.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[16]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTMC1995</span> <span class="o">=</span> <span class="n">WIOT1995</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;MEX-CAN&#39;</span><span class="p">)</span>
<span class="n">IOTMC1995</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[16]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco MEX</th>
      <th>Textiles and Textile Products MEX</th>
      <th>Leather, Leather and Footwear MEX</th>
      <th>Wood and Products of Wood and Cork MEX</th>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <th>Chemicals and Chemical Products MEX</th>
      <th>Rubber and Plastics MEX</th>
      <th>Other Non-Metallic Mineral MEX</th>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <th>Machinery, Nec MEX</th>
      <th>Electrical and Optical Equipment MEX</th>
      <th>Transport Equipment MEX</th>
      <th>Manufacturing, Nec; Recycling MEX</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco CAN</td>
      <td>41.605515</td>
      <td>0.075936</td>
      <td>2.125337</td>
      <td>0.009696</td>
      <td>0.211511</td>
      <td>0.052381</td>
      <td>0.821044</td>
      <td>0.211110</td>
      <td>0.058424</td>
      <td>0.088827</td>
      <td>0.034367</td>
      <td>0.132849</td>
      <td>0.076199</td>
      <td>0.053000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products CAN</td>
      <td>0.149844</td>
      <td>9.493911</td>
      <td>0.341767</td>
      <td>0.005082</td>
      <td>0.700784</td>
      <td>0.001963</td>
      <td>0.052686</td>
      <td>0.323927</td>
      <td>0.020235</td>
      <td>0.105333</td>
      <td>0.027202</td>
      <td>0.489314</td>
      <td>2.597325</td>
      <td>0.968037</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear CAN</td>
      <td>0.144063</td>
      <td>0.037953</td>
      <td>1.795557</td>
      <td>0.006585</td>
      <td>0.023264</td>
      <td>0.004561</td>
      <td>0.034471</td>
      <td>0.042460</td>
      <td>0.038965</td>
      <td>0.103584</td>
      <td>0.019935</td>
      <td>0.094876</td>
      <td>0.738234</td>
      <td>0.108997</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork CAN</td>
      <td>0.165328</td>
      <td>0.028116</td>
      <td>0.016678</td>
      <td>0.654811</td>
      <td>0.321707</td>
      <td>0.007288</td>
      <td>0.051839</td>
      <td>0.046585</td>
      <td>0.064248</td>
      <td>0.109376</td>
      <td>0.031686</td>
      <td>0.335732</td>
      <td>0.240356</td>
      <td>0.686090</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing CAN</td>
      <td>14.809471</td>
      <td>1.824142</td>
      <td>0.428588</td>
      <td>0.130770</td>
      <td>47.047584</td>
      <td>0.125570</td>
      <td>4.385661</td>
      <td>2.521630</td>
      <td>3.199258</td>
      <td>2.083545</td>
      <td>0.831856</td>
      <td>8.413193</td>
      <td>3.163704</td>
      <td>3.675561</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel CAN</td>
      <td>0.203575</td>
      <td>0.024513</td>
      <td>0.005772</td>
      <td>0.002802</td>
      <td>0.603284</td>
      <td>0.005028</td>
      <td>0.071457</td>
      <td>0.035074</td>
      <td>0.048670</td>
      <td>0.043032</td>
      <td>0.008868</td>
      <td>0.085319</td>
      <td>0.036339</td>
      <td>0.047142</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products CAN</td>
      <td>3.443282</td>
      <td>3.241533</td>
      <td>0.467244</td>
      <td>0.123814</td>
      <td>1.659804</td>
      <td>1.528097</td>
      <td>13.917510</td>
      <td>5.951097</td>
      <td>0.964681</td>
      <td>1.041482</td>
      <td>0.438301</td>
      <td>3.695475</td>
      <td>2.427570</td>
      <td>1.178823</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics CAN</td>
      <td>7.598944</td>
      <td>0.999218</td>
      <td>0.452621</td>
      <td>0.058908</td>
      <td>3.017254</td>
      <td>0.204011</td>
      <td>1.250421</td>
      <td>2.610518</td>
      <td>0.386217</td>
      <td>1.262899</td>
      <td>0.585321</td>
      <td>8.066657</td>
      <td>13.189623</td>
      <td>2.993673</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral CAN</td>
      <td>0.336606</td>
      <td>0.010138</td>
      <td>0.003642</td>
      <td>0.005187</td>
      <td>0.024995</td>
      <td>0.007704</td>
      <td>0.065041</td>
      <td>0.031029</td>
      <td>0.380732</td>
      <td>0.182417</td>
      <td>0.028360</td>
      <td>0.290836</td>
      <td>0.198121</td>
      <td>0.068602</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal CAN</td>
      <td>2.439943</td>
      <td>0.698790</td>
      <td>0.140786</td>
      <td>0.224608</td>
      <td>1.291624</td>
      <td>0.803547</td>
      <td>0.997374</td>
      <td>2.401883</td>
      <td>2.025881</td>
      <td>56.039751</td>
      <td>5.915176</td>
      <td>18.160100</td>
      <td>22.847635</td>
      <td>4.060967</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec CAN</td>
      <td>0.322610</td>
      <td>0.283503</td>
      <td>0.061301</td>
      <td>0.076625</td>
      <td>0.183132</td>
      <td>0.399151</td>
      <td>0.139119</td>
      <td>0.673729</td>
      <td>0.143353</td>
      <td>4.412327</td>
      <td>3.927939</td>
      <td>26.807206</td>
      <td>16.301954</td>
      <td>1.244645</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment CAN</td>
      <td>0.605487</td>
      <td>0.363219</td>
      <td>0.079063</td>
      <td>0.102018</td>
      <td>0.260486</td>
      <td>0.489718</td>
      <td>0.269533</td>
      <td>0.645406</td>
      <td>0.186843</td>
      <td>3.359908</td>
      <td>4.172308</td>
      <td>69.181546</td>
      <td>11.842051</td>
      <td>3.114883</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment CAN</td>
      <td>0.656950</td>
      <td>0.257370</td>
      <td>0.038580</td>
      <td>0.032807</td>
      <td>0.163136</td>
      <td>0.058578</td>
      <td>0.180805</td>
      <td>0.215659</td>
      <td>0.200338</td>
      <td>1.185662</td>
      <td>0.355495</td>
      <td>1.592957</td>
      <td>19.170878</td>
      <td>0.177978</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling CAN</td>
      <td>0.119864</td>
      <td>0.729200</td>
      <td>0.050075</td>
      <td>0.036031</td>
      <td>0.080317</td>
      <td>0.015263</td>
      <td>0.104052</td>
      <td>0.073573</td>
      <td>0.469770</td>
      <td>1.126398</td>
      <td>0.127891</td>
      <td>2.809029</td>
      <td>1.077651</td>
      <td>0.329944</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[17]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTMC2011</span> <span class="o">=</span> <span class="n">WIOT2011</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;MEX-CAN&#39;</span><span class="p">)</span>
<span class="n">IOTMC2011</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[17]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco MEX</th>
      <th>Textiles and Textile Products MEX</th>
      <th>Leather, Leather and Footwear MEX</th>
      <th>Wood and Products of Wood and Cork MEX</th>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <th>Chemicals and Chemical Products MEX</th>
      <th>Rubber and Plastics MEX</th>
      <th>Other Non-Metallic Mineral MEX</th>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <th>Machinery, Nec MEX</th>
      <th>Electrical and Optical Equipment MEX</th>
      <th>Transport Equipment MEX</th>
      <th>Manufacturing, Nec; Recycling MEX</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco CAN</td>
      <td>116.919913</td>
      <td>0.227275</td>
      <td>3.730962</td>
      <td>0.025566</td>
      <td>0.584850</td>
      <td>0.346932</td>
      <td>2.793432</td>
      <td>1.245750</td>
      <td>0.240266</td>
      <td>0.414273</td>
      <td>0.230775</td>
      <td>0.841524</td>
      <td>0.566681</td>
      <td>0.307373</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products CAN</td>
      <td>1.377875</td>
      <td>69.428933</td>
      <td>2.239135</td>
      <td>0.031052</td>
      <td>5.707087</td>
      <td>0.006470</td>
      <td>0.345074</td>
      <td>3.104236</td>
      <td>0.158418</td>
      <td>1.145216</td>
      <td>0.353943</td>
      <td>6.229556</td>
      <td>35.798998</td>
      <td>12.034475</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear CAN</td>
      <td>0.106824</td>
      <td>0.028584</td>
      <td>0.104463</td>
      <td>0.000695</td>
      <td>0.015440</td>
      <td>0.002429</td>
      <td>0.010194</td>
      <td>0.031922</td>
      <td>0.005425</td>
      <td>0.022887</td>
      <td>0.011320</td>
      <td>0.133914</td>
      <td>0.292429</td>
      <td>0.055117</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork CAN</td>
      <td>1.273414</td>
      <td>0.141420</td>
      <td>0.099679</td>
      <td>3.646585</td>
      <td>1.112395</td>
      <td>0.039770</td>
      <td>0.241929</td>
      <td>0.348204</td>
      <td>0.406018</td>
      <td>0.760280</td>
      <td>0.246403</td>
      <td>3.609931</td>
      <td>2.509173</td>
      <td>7.311185</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing CAN</td>
      <td>36.408578</td>
      <td>3.910178</td>
      <td>0.705162</td>
      <td>0.174170</td>
      <td>81.451924</td>
      <td>0.261315</td>
      <td>6.729104</td>
      <td>5.459416</td>
      <td>6.025405</td>
      <td>5.088608</td>
      <td>2.339119</td>
      <td>21.312199</td>
      <td>11.284311</td>
      <td>10.040914</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel CAN</td>
      <td>3.482400</td>
      <td>0.309108</td>
      <td>0.083776</td>
      <td>0.108686</td>
      <td>2.407244</td>
      <td>0.640481</td>
      <td>2.778036</td>
      <td>1.171729</td>
      <td>1.069168</td>
      <td>2.650323</td>
      <td>0.225059</td>
      <td>1.121477</td>
      <td>0.841025</td>
      <td>0.646730</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products CAN</td>
      <td>43.303364</td>
      <td>21.173975</td>
      <td>3.537533</td>
      <td>0.886130</td>
      <td>14.997340</td>
      <td>18.193560</td>
      <td>114.941700</td>
      <td>65.078086</td>
      <td>9.765629</td>
      <td>15.570725</td>
      <td>7.143312</td>
      <td>34.135860</td>
      <td>33.379273</td>
      <td>15.010434</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics CAN</td>
      <td>66.676902</td>
      <td>5.504120</td>
      <td>2.492296</td>
      <td>0.297579</td>
      <td>15.832571</td>
      <td>1.525239</td>
      <td>6.154510</td>
      <td>19.351290</td>
      <td>2.493267</td>
      <td>11.200950</td>
      <td>7.056790</td>
      <td>85.319205</td>
      <td>161.825706</td>
      <td>28.794204</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral CAN</td>
      <td>1.898792</td>
      <td>0.026136</td>
      <td>0.008618</td>
      <td>0.014609</td>
      <td>0.056289</td>
      <td>0.025751</td>
      <td>0.177095</td>
      <td>0.096588</td>
      <td>1.676757</td>
      <td>0.485475</td>
      <td>0.154663</td>
      <td>1.575995</td>
      <td>1.076291</td>
      <td>0.361906</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal CAN</td>
      <td>14.624960</td>
      <td>3.137798</td>
      <td>0.589641</td>
      <td>0.865246</td>
      <td>11.400230</td>
      <td>4.510970</td>
      <td>5.909563</td>
      <td>21.888304</td>
      <td>7.812870</td>
      <td>781.919474</td>
      <td>92.725393</td>
      <td>257.663143</td>
      <td>310.838400</td>
      <td>48.596875</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec CAN</td>
      <td>1.748243</td>
      <td>0.963920</td>
      <td>0.206366</td>
      <td>0.231172</td>
      <td>0.711720</td>
      <td>1.980798</td>
      <td>0.489297</td>
      <td>2.949082</td>
      <td>0.679816</td>
      <td>22.309980</td>
      <td>28.476999</td>
      <td>191.582421</td>
      <td>101.030127</td>
      <td>7.885181</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment CAN</td>
      <td>2.184386</td>
      <td>0.885002</td>
      <td>0.221730</td>
      <td>0.253778</td>
      <td>0.649990</td>
      <td>2.017640</td>
      <td>0.589985</td>
      <td>2.064413</td>
      <td>0.566456</td>
      <td>12.197931</td>
      <td>22.819485</td>
      <td>198.487544</td>
      <td>42.801909</td>
      <td>9.832206</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment CAN</td>
      <td>15.596329</td>
      <td>3.921576</td>
      <td>0.553692</td>
      <td>0.347825</td>
      <td>3.036077</td>
      <td>0.370100</td>
      <td>2.811139</td>
      <td>3.483479</td>
      <td>4.049479</td>
      <td>19.843885</td>
      <td>5.957368</td>
      <td>18.639811</td>
      <td>629.680784</td>
      <td>1.837155</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling CAN</td>
      <td>1.237933</td>
      <td>5.184064</td>
      <td>0.197987</td>
      <td>0.243199</td>
      <td>0.681073</td>
      <td>0.047132</td>
      <td>0.321568</td>
      <td>0.443422</td>
      <td>1.919253</td>
      <td>5.903095</td>
      <td>0.838561</td>
      <td>22.110267</td>
      <td>7.311073</td>
      <td>4.224189</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[18]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTMC2011</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">subtract</span><span class="p">(</span><span class="n">IOTMC1995</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">),</span> <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[18]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Food, Beverages and Tobacco MEX</th>
      <th>Textiles and Textile Products MEX</th>
      <th>Leather, Leather and Footwear MEX</th>
      <th>Wood and Products of Wood and Cork MEX</th>
      <th>Pulp, Paper, Paper , Printing and Publishing MEX</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel MEX</th>
      <th>Chemicals and Chemical Products MEX</th>
      <th>Rubber and Plastics MEX</th>
      <th>Other Non-Metallic Mineral MEX</th>
      <th>Basic Metals and Fabricated Metal MEX</th>
      <th>Machinery, Nec MEX</th>
      <th>Electrical and Optical Equipment MEX</th>
      <th>Transport Equipment MEX</th>
      <th>Manufacturing, Nec; Recycling MEX</th>
    </tr>
    <tr>
      <th>Sectors</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Food, Beverages and Tobacco CAN</th>
      <td>75.314397</td>
      <td>0.151339</td>
      <td>1.605625</td>
      <td>0.015870</td>
      <td>0.373339</td>
      <td>0.294551</td>
      <td>1.972388</td>
      <td>1.034640</td>
      <td>0.181842</td>
      <td>0.325446</td>
      <td>0.196408</td>
      <td>0.708675</td>
      <td>0.490482</td>
      <td>0.254374</td>
    </tr>
    <tr>
      <th>Textiles and Textile Products CAN</th>
      <td>1.228031</td>
      <td>59.935022</td>
      <td>1.897368</td>
      <td>0.025969</td>
      <td>5.006304</td>
      <td>0.004507</td>
      <td>0.292388</td>
      <td>2.780309</td>
      <td>0.138183</td>
      <td>1.039883</td>
      <td>0.326742</td>
      <td>5.740241</td>
      <td>33.201672</td>
      <td>11.066439</td>
    </tr>
    <tr>
      <th>Leather, Leather and Footwear CAN</th>
      <td>-0.037239</td>
      <td>-0.009369</td>
      <td>-1.691095</td>
      <td>-0.005890</td>
      <td>-0.007824</td>
      <td>-0.002132</td>
      <td>-0.024276</td>
      <td>-0.010538</td>
      <td>-0.033541</td>
      <td>-0.080697</td>
      <td>-0.008615</td>
      <td>0.039037</td>
      <td>-0.445805</td>
      <td>-0.053880</td>
    </tr>
    <tr>
      <th>Wood and Products of Wood and Cork CAN</th>
      <td>1.108086</td>
      <td>0.113304</td>
      <td>0.083002</td>
      <td>2.991774</td>
      <td>0.790688</td>
      <td>0.032482</td>
      <td>0.190090</td>
      <td>0.301619</td>
      <td>0.341770</td>
      <td>0.650905</td>
      <td>0.214717</td>
      <td>3.274199</td>
      <td>2.268817</td>
      <td>6.625096</td>
    </tr>
    <tr>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <td>21.599107</td>
      <td>2.086035</td>
      <td>0.276574</td>
      <td>0.043400</td>
      <td>34.404340</td>
      <td>0.135746</td>
      <td>2.343444</td>
      <td>2.937786</td>
      <td>2.826147</td>
      <td>3.005063</td>
      <td>1.507263</td>
      <td>12.899006</td>
      <td>8.120607</td>
      <td>6.365353</td>
    </tr>
    <tr>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <td>3.278825</td>
      <td>0.284595</td>
      <td>0.078003</td>
      <td>0.105884</td>
      <td>1.803960</td>
      <td>0.635452</td>
      <td>2.706579</td>
      <td>1.136655</td>
      <td>1.020498</td>
      <td>2.607292</td>
      <td>0.216191</td>
      <td>1.036159</td>
      <td>0.804687</td>
      <td>0.599588</td>
    </tr>
    <tr>
      <th>Chemicals and Chemical Products CAN</th>
      <td>39.860081</td>
      <td>17.932442</td>
      <td>3.070289</td>
      <td>0.762316</td>
      <td>13.337536</td>
      <td>16.665463</td>
      <td>101.024190</td>
      <td>59.126990</td>
      <td>8.800949</td>
      <td>14.529243</td>
      <td>6.705011</td>
      <td>30.440385</td>
      <td>30.951703</td>
      <td>13.831611</td>
    </tr>
    <tr>
      <th>Rubber and Plastics CAN</th>
      <td>59.077958</td>
      <td>4.504902</td>
      <td>2.039675</td>
      <td>0.238671</td>
      <td>12.815317</td>
      <td>1.321228</td>
      <td>4.904089</td>
      <td>16.740772</td>
      <td>2.107050</td>
      <td>9.938051</td>
      <td>6.471468</td>
      <td>77.252548</td>
      <td>148.636083</td>
      <td>25.800531</td>
    </tr>
    <tr>
      <th>Other Non-Metallic Mineral CAN</th>
      <td>1.562187</td>
      <td>0.015998</td>
      <td>0.004976</td>
      <td>0.009423</td>
      <td>0.031294</td>
      <td>0.018047</td>
      <td>0.112054</td>
      <td>0.065559</td>
      <td>1.296025</td>
      <td>0.303058</td>
      <td>0.126303</td>
      <td>1.285158</td>
      <td>0.878171</td>
      <td>0.293304</td>
    </tr>
    <tr>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <td>12.185017</td>
      <td>2.439008</td>
      <td>0.448855</td>
      <td>0.640639</td>
      <td>10.108606</td>
      <td>3.707424</td>
      <td>4.912189</td>
      <td>19.486420</td>
      <td>5.786990</td>
      <td>725.879723</td>
      <td>86.810217</td>
      <td>239.503043</td>
      <td>287.990765</td>
      <td>44.535908</td>
    </tr>
    <tr>
      <th>Machinery, Nec CAN</th>
      <td>1.425633</td>
      <td>0.680417</td>
      <td>0.145065</td>
      <td>0.154547</td>
      <td>0.528588</td>
      <td>1.581647</td>
      <td>0.350177</td>
      <td>2.275353</td>
      <td>0.536463</td>
      <td>17.897653</td>
      <td>24.549061</td>
      <td>164.775215</td>
      <td>84.728174</td>
      <td>6.640536</td>
    </tr>
    <tr>
      <th>Electrical and Optical Equipment CAN</th>
      <td>1.578899</td>
      <td>0.521783</td>
      <td>0.142667</td>
      <td>0.151761</td>
      <td>0.389504</td>
      <td>1.527922</td>
      <td>0.320453</td>
      <td>1.419007</td>
      <td>0.379613</td>
      <td>8.838024</td>
      <td>18.647177</td>
      <td>129.305998</td>
      <td>30.959858</td>
      <td>6.717324</td>
    </tr>
    <tr>
      <th>Transport Equipment CAN</th>
      <td>14.939379</td>
      <td>3.664206</td>
      <td>0.515112</td>
      <td>0.315019</td>
      <td>2.872941</td>
      <td>0.311522</td>
      <td>2.630333</td>
      <td>3.267819</td>
      <td>3.849141</td>
      <td>18.658223</td>
      <td>5.601873</td>
      <td>17.046854</td>
      <td>610.509906</td>
      <td>1.659178</td>
    </tr>
    <tr>
      <th>Manufacturing, Nec; Recycling CAN</th>
      <td>1.118069</td>
      <td>4.454864</td>
      <td>0.147913</td>
      <td>0.207167</td>
      <td>0.600756</td>
      <td>0.031870</td>
      <td>0.217516</td>
      <td>0.369848</td>
      <td>1.449483</td>
      <td>4.776697</td>
      <td>0.710670</td>
      <td>19.301238</td>
      <td>6.233422</td>
      <td>3.894245</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Analyzing the inputs from Canada into Mexico again we can note two different things. First of all, the trade in absolute numbers is not too big, compared to the trade with the US (for both directions of the inputs and for both countries). Secondly, the biggest exportsectors for Canada into Mexico are 'Chemicals and Chemical Products' and 'Rubber and Plastics'. These sectors stay important and know an increase during 1995-2011. Other sectors that have known a small increase are'Textiles and Textile Products' and 'Transport Equipment '. In the next section, we look at the evolution of the intermediate inputs from US into Canada.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[19]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTCU1995</span> <span class="o">=</span> <span class="n">WIOT1995</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;CAN-US&#39;</span><span class="p">)</span>
<span class="n">IOTCU1995</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[19]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco CAN</th>
      <th>Textiles and Textile Products CAN</th>
      <th>Leather, Leather and Footwear CAN</th>
      <th>Wood and Products of Wood and Cork CAN</th>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <th>Chemicals and Chemical Products CAN</th>
      <th>Rubber and Plastics CAN</th>
      <th>Other Non-Metallic Mineral CAN</th>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <th>Machinery, Nec CAN</th>
      <th>Electrical and Optical Equipment CAN</th>
      <th>Transport Equipment CAN</th>
      <th>Manufacturing, Nec; Recycling CAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco USA</td>
      <td>359.259584</td>
      <td>0.658300</td>
      <td>2.130892</td>
      <td>0.344133</td>
      <td>3.444493</td>
      <td>0.570951</td>
      <td>11.698831</td>
      <td>5.070415</td>
      <td>0.241014</td>
      <td>0.880609</td>
      <td>0.569639</td>
      <td>0.229052</td>
      <td>0.778009</td>
      <td>0.468348</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products USA</td>
      <td>6.604184</td>
      <td>696.302613</td>
      <td>27.443271</td>
      <td>2.611861</td>
      <td>27.750202</td>
      <td>1.481077</td>
      <td>40.763983</td>
      <td>41.773433</td>
      <td>1.402517</td>
      <td>4.592523</td>
      <td>5.536635</td>
      <td>2.375653</td>
      <td>86.148871</td>
      <td>89.115630</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear USA</td>
      <td>0.007427</td>
      <td>3.024811</td>
      <td>2.509277</td>
      <td>0.002762</td>
      <td>0.034847</td>
      <td>0.000000</td>
      <td>0.028041</td>
      <td>0.058689</td>
      <td>0.001222</td>
      <td>0.002182</td>
      <td>0.006300</td>
      <td>0.020857</td>
      <td>1.163098</td>
      <td>1.331002</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork USA</td>
      <td>0.940232</td>
      <td>0.155165</td>
      <td>0.016349</td>
      <td>160.743345</td>
      <td>196.943400</td>
      <td>1.332027</td>
      <td>1.394061</td>
      <td>4.340311</td>
      <td>2.377449</td>
      <td>9.892598</td>
      <td>2.148390</td>
      <td>2.798260</td>
      <td>7.992041</td>
      <td>55.085406</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing USA</td>
      <td>348.487394</td>
      <td>25.543224</td>
      <td>3.120160</td>
      <td>27.342450</td>
      <td>1641.327351</td>
      <td>22.085045</td>
      <td>82.602311</td>
      <td>47.142005</td>
      <td>43.617292</td>
      <td>47.135702</td>
      <td>48.006186</td>
      <td>79.564701</td>
      <td>52.807715</td>
      <td>58.801915</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel USA</td>
      <td>8.643146</td>
      <td>3.381933</td>
      <td>0.630077</td>
      <td>6.206255</td>
      <td>29.057706</td>
      <td>94.470578</td>
      <td>126.443620</td>
      <td>35.734462</td>
      <td>8.047561</td>
      <td>34.275012</td>
      <td>9.773156</td>
      <td>3.294625</td>
      <td>10.085359</td>
      <td>4.236616</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products USA</td>
      <td>117.310619</td>
      <td>67.701964</td>
      <td>13.738837</td>
      <td>64.997869</td>
      <td>438.216894</td>
      <td>110.269808</td>
      <td>1752.075799</td>
      <td>901.392857</td>
      <td>45.854812</td>
      <td>169.316110</td>
      <td>109.336287</td>
      <td>40.637912</td>
      <td>146.990149</td>
      <td>49.756753</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics USA</td>
      <td>181.964906</td>
      <td>13.004581</td>
      <td>11.444181</td>
      <td>27.810962</td>
      <td>73.001234</td>
      <td>11.040305</td>
      <td>108.614558</td>
      <td>211.472921</td>
      <td>17.301179</td>
      <td>77.505681</td>
      <td>67.836891</td>
      <td>61.969892</td>
      <td>395.434509</td>
      <td>82.048745</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral USA</td>
      <td>35.275408</td>
      <td>2.118472</td>
      <td>0.037772</td>
      <td>12.572300</td>
      <td>7.107684</td>
      <td>14.816680</td>
      <td>22.458540</td>
      <td>17.241585</td>
      <td>196.878260</td>
      <td>83.645711</td>
      <td>70.376096</td>
      <td>9.356120</td>
      <td>119.103541</td>
      <td>10.601554</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal USA</td>
      <td>178.922185</td>
      <td>2.207108</td>
      <td>0.153375</td>
      <td>31.667577</td>
      <td>15.607083</td>
      <td>2.550328</td>
      <td>36.726538</td>
      <td>48.172323</td>
      <td>22.657385</td>
      <td>2550.195634</td>
      <td>465.490604</td>
      <td>498.549791</td>
      <td>966.181750</td>
      <td>136.932525</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec USA</td>
      <td>3.797103</td>
      <td>1.194089</td>
      <td>0.051360</td>
      <td>5.678451</td>
      <td>5.120984</td>
      <td>0.261237</td>
      <td>4.040523</td>
      <td>12.009641</td>
      <td>1.041413</td>
      <td>121.583673</td>
      <td>371.315623</td>
      <td>776.216746</td>
      <td>721.186304</td>
      <td>15.581195</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment USA</td>
      <td>5.390984</td>
      <td>4.936121</td>
      <td>0.256723</td>
      <td>2.408608</td>
      <td>119.038791</td>
      <td>0.620181</td>
      <td>20.413934</td>
      <td>7.093413</td>
      <td>3.332175</td>
      <td>45.207893</td>
      <td>397.833487</td>
      <td>2567.405185</td>
      <td>449.560726</td>
      <td>58.015539</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment USA</td>
      <td>1.810431</td>
      <td>4.116020</td>
      <td>0.098111</td>
      <td>1.767819</td>
      <td>1.477899</td>
      <td>0.074799</td>
      <td>1.480423</td>
      <td>87.337606</td>
      <td>0.319724</td>
      <td>77.060202</td>
      <td>17.033892</td>
      <td>144.397743</td>
      <td>14140.129439</td>
      <td>3.391596</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling USA</td>
      <td>5.328264</td>
      <td>3.156887</td>
      <td>0.302943</td>
      <td>1.791256</td>
      <td>25.569551</td>
      <td>0.296075</td>
      <td>7.854400</td>
      <td>2.384887</td>
      <td>1.005140</td>
      <td>6.474322</td>
      <td>4.731155</td>
      <td>36.252313</td>
      <td>70.540993</td>
      <td>66.063495</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[20]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTCU2011</span> <span class="o">=</span> <span class="n">WIOT2011</span><span class="o">.</span><span class="n">parse</span><span class="p">(</span><span class="s1">&#39;CAN-US&#39;</span><span class="p">)</span>
<span class="n">IOTCU2011</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[20]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sectors</th>
      <th>Food, Beverages and Tobacco CAN</th>
      <th>Textiles and Textile Products CAN</th>
      <th>Leather, Leather and Footwear CAN</th>
      <th>Wood and Products of Wood and Cork CAN</th>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <th>Chemicals and Chemical Products CAN</th>
      <th>Rubber and Plastics CAN</th>
      <th>Other Non-Metallic Mineral CAN</th>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <th>Machinery, Nec CAN</th>
      <th>Electrical and Optical Equipment CAN</th>
      <th>Transport Equipment CAN</th>
      <th>Manufacturing, Nec; Recycling CAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco USA</td>
      <td>964.809307</td>
      <td>3.404455</td>
      <td>0.085171</td>
      <td>2.975281</td>
      <td>10.581524</td>
      <td>9.961704</td>
      <td>92.162382</td>
      <td>44.029825</td>
      <td>0.950572</td>
      <td>5.297393</td>
      <td>4.841936</td>
      <td>0.986008</td>
      <td>4.406105</td>
      <td>3.679043</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products USA</td>
      <td>7.324273</td>
      <td>448.931481</td>
      <td>7.020033</td>
      <td>1.095538</td>
      <td>16.807989</td>
      <td>3.392901</td>
      <td>36.653917</td>
      <td>81.192348</td>
      <td>0.409624</td>
      <td>4.296964</td>
      <td>18.016581</td>
      <td>0.686777</td>
      <td>40.870466</td>
      <td>150.029902</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear USA</td>
      <td>0.008745</td>
      <td>1.615413</td>
      <td>0.557793</td>
      <td>0.000000</td>
      <td>0.024050</td>
      <td>0.000000</td>
      <td>0.011795</td>
      <td>0.107105</td>
      <td>0.000000</td>
      <td>0.002738</td>
      <td>0.026526</td>
      <td>0.000000</td>
      <td>0.034764</td>
      <td>1.027572</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork USA</td>
      <td>3.654109</td>
      <td>0.092472</td>
      <td>0.032919</td>
      <td>277.590890</td>
      <td>153.501274</td>
      <td>0.647456</td>
      <td>2.426749</td>
      <td>12.767954</td>
      <td>3.691948</td>
      <td>14.070126</td>
      <td>3.705724</td>
      <td>2.532408</td>
      <td>9.970158</td>
      <td>137.700625</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing USA</td>
      <td>668.595586</td>
      <td>42.989086</td>
      <td>1.974092</td>
      <td>36.201314</td>
      <td>2252.788133</td>
      <td>43.624799</td>
      <td>154.019733</td>
      <td>109.564660</td>
      <td>78.474059</td>
      <td>49.705613</td>
      <td>119.316759</td>
      <td>39.642591</td>
      <td>74.147297</td>
      <td>96.210188</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel USA</td>
      <td>43.913467</td>
      <td>10.959921</td>
      <td>0.882464</td>
      <td>42.981275</td>
      <td>111.722039</td>
      <td>870.453272</td>
      <td>1560.761293</td>
      <td>156.273518</td>
      <td>66.875886</td>
      <td>244.977435</td>
      <td>41.992978</td>
      <td>28.369540</td>
      <td>43.789841</td>
      <td>38.800444</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products USA</td>
      <td>159.426733</td>
      <td>100.503521</td>
      <td>4.703343</td>
      <td>161.395896</td>
      <td>387.655381</td>
      <td>546.908376</td>
      <td>4754.723699</td>
      <td>2381.550290</td>
      <td>52.413315</td>
      <td>292.621101</td>
      <td>264.043051</td>
      <td>59.926071</td>
      <td>252.960687</td>
      <td>196.683095</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics USA</td>
      <td>417.324798</td>
      <td>9.977991</td>
      <td>15.736666</td>
      <td>52.335025</td>
      <td>104.172906</td>
      <td>45.519091</td>
      <td>177.392462</td>
      <td>709.443359</td>
      <td>33.057356</td>
      <td>97.785503</td>
      <td>31.375959</td>
      <td>84.683868</td>
      <td>671.556082</td>
      <td>248.710290</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral USA</td>
      <td>42.312049</td>
      <td>0.629616</td>
      <td>0.038612</td>
      <td>13.567844</td>
      <td>5.860231</td>
      <td>24.489304</td>
      <td>15.587881</td>
      <td>27.947888</td>
      <td>481.190354</td>
      <td>108.661699</td>
      <td>1.774817</td>
      <td>7.442324</td>
      <td>245.356681</td>
      <td>14.904469</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal USA</td>
      <td>171.044602</td>
      <td>4.383056</td>
      <td>0.227879</td>
      <td>32.773012</td>
      <td>13.568985</td>
      <td>6.978305</td>
      <td>97.731843</td>
      <td>121.430899</td>
      <td>44.400867</td>
      <td>6633.592794</td>
      <td>1408.042565</td>
      <td>894.252240</td>
      <td>2269.752597</td>
      <td>338.960067</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec USA</td>
      <td>6.491053</td>
      <td>0.262975</td>
      <td>0.086993</td>
      <td>4.300182</td>
      <td>3.051054</td>
      <td>1.505004</td>
      <td>11.821570</td>
      <td>17.641922</td>
      <td>1.483011</td>
      <td>118.881485</td>
      <td>933.856961</td>
      <td>1304.083308</td>
      <td>1400.189896</td>
      <td>24.896584</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment USA</td>
      <td>7.868147</td>
      <td>6.377187</td>
      <td>0.186889</td>
      <td>13.764574</td>
      <td>89.428185</td>
      <td>5.069668</td>
      <td>41.296248</td>
      <td>34.551508</td>
      <td>3.853390</td>
      <td>76.047619</td>
      <td>1169.689059</td>
      <td>1308.162524</td>
      <td>872.232991</td>
      <td>181.443922</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment USA</td>
      <td>3.492021</td>
      <td>1.530435</td>
      <td>0.079211</td>
      <td>0.751034</td>
      <td>1.465874</td>
      <td>0.900747</td>
      <td>7.059653</td>
      <td>109.008214</td>
      <td>0.330016</td>
      <td>23.033906</td>
      <td>29.266732</td>
      <td>108.967124</td>
      <td>19458.023289</td>
      <td>4.898004</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling USA</td>
      <td>3.828606</td>
      <td>2.543129</td>
      <td>0.089553</td>
      <td>5.346827</td>
      <td>24.357503</td>
      <td>2.805110</td>
      <td>23.140795</td>
      <td>14.277813</td>
      <td>1.965671</td>
      <td>14.316141</td>
      <td>27.265365</td>
      <td>25.451050</td>
      <td>77.318415</td>
      <td>122.352317</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[21]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">IOTCU2011</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">subtract</span><span class="p">(</span><span class="n">IOTCU1995</span><span class="o">.</span><span class="n">set_index</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">),</span> <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[21]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Food, Beverages and Tobacco CAN</th>
      <th>Textiles and Textile Products CAN</th>
      <th>Leather, Leather and Footwear CAN</th>
      <th>Wood and Products of Wood and Cork CAN</th>
      <th>Pulp, Paper, Paper , Printing and Publishing CAN</th>
      <th>Coke, Refined Petroleum and Nuclear Fuel CAN</th>
      <th>Chemicals and Chemical Products CAN</th>
      <th>Rubber and Plastics CAN</th>
      <th>Other Non-Metallic Mineral CAN</th>
      <th>Basic Metals and Fabricated Metal CAN</th>
      <th>Machinery, Nec CAN</th>
      <th>Electrical and Optical Equipment CAN</th>
      <th>Transport Equipment CAN</th>
      <th>Manufacturing, Nec; Recycling CAN</th>
    </tr>
    <tr>
      <th>Sectors</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Food, Beverages and Tobacco USA</th>
      <td>605.549723</td>
      <td>2.746156</td>
      <td>-2.045721</td>
      <td>2.631148</td>
      <td>7.137031</td>
      <td>9.390754</td>
      <td>80.463550</td>
      <td>38.959410</td>
      <td>0.709558</td>
      <td>4.416783</td>
      <td>4.272297</td>
      <td>0.756956</td>
      <td>3.628096</td>
      <td>3.210695</td>
    </tr>
    <tr>
      <th>Textiles and Textile Products USA</th>
      <td>0.720090</td>
      <td>-247.371132</td>
      <td>-20.423239</td>
      <td>-1.516323</td>
      <td>-10.942212</td>
      <td>1.911825</td>
      <td>-4.110066</td>
      <td>39.418915</td>
      <td>-0.992893</td>
      <td>-0.295559</td>
      <td>12.479946</td>
      <td>-1.688875</td>
      <td>-45.278405</td>
      <td>60.914273</td>
    </tr>
    <tr>
      <th>Leather, Leather and Footwear USA</th>
      <td>0.001317</td>
      <td>-1.409398</td>
      <td>-1.951484</td>
      <td>-0.002762</td>
      <td>-0.010798</td>
      <td>0.000000</td>
      <td>-0.016246</td>
      <td>0.048416</td>
      <td>-0.001222</td>
      <td>0.000557</td>
      <td>0.020225</td>
      <td>-0.020857</td>
      <td>-1.128334</td>
      <td>-0.303430</td>
    </tr>
    <tr>
      <th>Wood and Products of Wood and Cork USA</th>
      <td>2.713877</td>
      <td>-0.062693</td>
      <td>0.016570</td>
      <td>116.847545</td>
      <td>-43.442127</td>
      <td>-0.684572</td>
      <td>1.032687</td>
      <td>8.427644</td>
      <td>1.314499</td>
      <td>4.177527</td>
      <td>1.557334</td>
      <td>-0.265852</td>
      <td>1.978117</td>
      <td>82.615219</td>
    </tr>
    <tr>
      <th>Pulp, Paper, Paper , Printing and Publishing USA</th>
      <td>320.108192</td>
      <td>17.445862</td>
      <td>-1.146068</td>
      <td>8.858864</td>
      <td>611.460782</td>
      <td>21.539754</td>
      <td>71.417422</td>
      <td>62.422655</td>
      <td>34.856768</td>
      <td>2.569911</td>
      <td>71.310574</td>
      <td>-39.922110</td>
      <td>21.339583</td>
      <td>37.408273</td>
    </tr>
    <tr>
      <th>Coke, Refined Petroleum and Nuclear Fuel USA</th>
      <td>35.270320</td>
      <td>7.577988</td>
      <td>0.252386</td>
      <td>36.775020</td>
      <td>82.664333</td>
      <td>775.982693</td>
      <td>1434.317673</td>
      <td>120.539056</td>
      <td>58.828325</td>
      <td>210.702423</td>
      <td>32.219823</td>
      <td>25.074915</td>
      <td>33.704483</td>
      <td>34.563828</td>
    </tr>
    <tr>
      <th>Chemicals and Chemical Products USA</th>
      <td>42.116114</td>
      <td>32.801557</td>
      <td>-9.035494</td>
      <td>96.398027</td>
      <td>-50.561513</td>
      <td>436.638568</td>
      <td>3002.647899</td>
      <td>1480.157433</td>
      <td>6.558503</td>
      <td>123.304991</td>
      <td>154.706764</td>
      <td>19.288159</td>
      <td>105.970539</td>
      <td>146.926343</td>
    </tr>
    <tr>
      <th>Rubber and Plastics USA</th>
      <td>235.359891</td>
      <td>-3.026590</td>
      <td>4.292485</td>
      <td>24.524062</td>
      <td>31.171672</td>
      <td>34.478786</td>
      <td>68.777904</td>
      <td>497.970438</td>
      <td>15.756178</td>
      <td>20.279822</td>
      <td>-36.460931</td>
      <td>22.713977</td>
      <td>276.121572</td>
      <td>166.661545</td>
    </tr>
    <tr>
      <th>Other Non-Metallic Mineral USA</th>
      <td>7.036642</td>
      <td>-1.488856</td>
      <td>0.000840</td>
      <td>0.995544</td>
      <td>-1.247453</td>
      <td>9.672624</td>
      <td>-6.870659</td>
      <td>10.706303</td>
      <td>284.312094</td>
      <td>25.015987</td>
      <td>-68.601279</td>
      <td>-1.913796</td>
      <td>126.253139</td>
      <td>4.302916</td>
    </tr>
    <tr>
      <th>Basic Metals and Fabricated Metal USA</th>
      <td>-7.877583</td>
      <td>2.175949</td>
      <td>0.074504</td>
      <td>1.105435</td>
      <td>-2.038098</td>
      <td>4.427977</td>
      <td>61.005306</td>
      <td>73.258576</td>
      <td>21.743482</td>
      <td>4083.397161</td>
      <td>942.551961</td>
      <td>395.702448</td>
      <td>1303.570847</td>
      <td>202.027541</td>
    </tr>
    <tr>
      <th>Machinery, Nec USA</th>
      <td>2.693950</td>
      <td>-0.931114</td>
      <td>0.035633</td>
      <td>-1.378268</td>
      <td>-2.069931</td>
      <td>1.243767</td>
      <td>7.781047</td>
      <td>5.632281</td>
      <td>0.441598</td>
      <td>-2.702188</td>
      <td>562.541338</td>
      <td>527.866562</td>
      <td>679.003592</td>
      <td>9.315389</td>
    </tr>
    <tr>
      <th>Electrical and Optical Equipment USA</th>
      <td>2.477162</td>
      <td>1.441066</td>
      <td>-0.069834</td>
      <td>11.355966</td>
      <td>-29.610606</td>
      <td>4.449487</td>
      <td>20.882314</td>
      <td>27.458095</td>
      <td>0.521216</td>
      <td>30.839727</td>
      <td>771.855573</td>
      <td>-1259.242662</td>
      <td>422.672264</td>
      <td>123.428382</td>
    </tr>
    <tr>
      <th>Transport Equipment USA</th>
      <td>1.681591</td>
      <td>-2.585585</td>
      <td>-0.018901</td>
      <td>-1.016785</td>
      <td>-0.012024</td>
      <td>0.825948</td>
      <td>5.579230</td>
      <td>21.670608</td>
      <td>0.010292</td>
      <td>-54.026296</td>
      <td>12.232840</td>
      <td>-35.430618</td>
      <td>5317.893850</td>
      <td>1.506409</td>
    </tr>
    <tr>
      <th>Manufacturing, Nec; Recycling USA</th>
      <td>-1.499658</td>
      <td>-0.613758</td>
      <td>-0.213389</td>
      <td>3.555571</td>
      <td>-1.212048</td>
      <td>2.509035</td>
      <td>15.286395</td>
      <td>11.892927</td>
      <td>0.960532</td>
      <td>7.841819</td>
      <td>22.534210</td>
      <td>-10.801264</td>
      <td>6.777422</td>
      <td>56.288822</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>When looking at the inputs from US into Canada in 1995, we see that the biggest sectors for the American re-exports into Canada were 'Food, Beverages and Tobacco', 'Chemicals and Chemical Products', 'Rubber and Plastics' and 'Basic and Fabricated Metal'. If we look at the evolution up to 2011, we can see the biggest increases were for the sectors 'Food, Beverages and Tobacco', 'Pulp, Paper, Printing and Publishing', 'Coke and Refined Petroleum', 'Chemicals and Chemical Products' and 'Rubber and Plastics'. We will analyze in the following part how these absolute increases relate to the evolution of the RCAs of the three countries.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='RCA'></a></p>
<h2 id="4.-Relation-to-Revealed-Comparative-Advantage">4. Relation to Revealed Comparative Advantage<a class="anchor-link" href="#4.-Relation-to-Revealed-Comparative-Advantage">&#182;</a></h2><p>A highly used index to measure the comparative advantage is the Revealed Comparative Advantage-index (RCA). This index shows the comparative advantage as observed from the trade flows, and can be easily calculated from the input-output tables. Thus, an important assumption in our model is that the present international trade flows represent the actual comparative advantage of the economy. The fraction in the numerator shows the share of exports in sector i from country j over the world exports of this sector. That share is then normalised by the share of country j in all the sectors (in the denumerator). We assume that country j has a comparative advantage in sector i if the RCA &gt; 1. The calculated RCA-values per sector for Canada, Mexico and US are calculated below.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
$$RCA_{ij} = \frac{x_{ij} / \sum _{j}x_{ij}  }{ \sum _{i}x_{ij} / \sum_{i} \sum_{j}x_{ij}}$$$$x_{ij}= exports\space from\space sector\space i\space by\space country\space j  \\ $$$$\sum _{i}= summation\space over\space all\space sectors\space i\space in\space country$$$$\sum_{j}= summation\space over\space all\space countries\space j\space$$
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>First, we look how the RCA changed for Canada in 1995-2011. We can see the calculated RCA index in the table and in the histogram below. The sectors where Canada gained the comparative advantage are: 'Food, Beverages and Tobacco', 'Wood and Products of Wood and Cork', 'Coke, Refined Petroleum and Nuclear Fuel', 'Chemicals and Chemical Products', 'Rubber and Plastics', 'Other Non-Metallic Mineral', 'Machinery, Nec' and 'Manufacturing, Nec; Recycling'. The biggest increases are for 'Coke, Refined Petroleum and Nuclear Fuel', 'Chemicals and Chemical Products', 'Rubber and Plastics' and 'Machinery, Nec'. The biggest loss in the RCA is for the sector 'Transport Equipment'. We will see that Mexico is the one that will create a big increase in RCA in that sector and take the Canadian specialisation in those inputs away.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span><span class="p">;</span> <span class="n">plt</span><span class="o">.</span><span class="n">rcdefaults</span><span class="p">()</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>


<span class="n">rcacan</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_excel</span><span class="p">(</span><span class="sa">r</span><span class="s1">&#39;C:\Users\Jesse\Downloads\PythonFinal\RCA.xlsx&#39;</span><span class="p">,</span> <span class="s2">&quot;RCA_CAN&quot;</span><span class="p">)</span>
<span class="n">FORMAT</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Sector&#39;</span><span class="p">,</span> <span class="s1">&#39;1995CAN&#39;</span><span class="p">,</span> <span class="s1">&#39;2011CAN&#39;</span><span class="p">]</span>
<span class="n">rcacan_selected</span> <span class="o">=</span> <span class="n">rcacan</span><span class="p">[</span><span class="n">FORMAT</span><span class="p">]</span>
<span class="n">rcacan</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[22]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Sector</th>
      <th>1995CAN</th>
      <th>2011CAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Food, Beverages and Tobacco</td>
      <td>0.929072</td>
      <td>1.253567</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Textiles and Textile Products</td>
      <td>0.371743</td>
      <td>0.255995</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Leather, Leather and Footwear</td>
      <td>0.604167</td>
      <td>0.391083</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Wood and Products of Wood and Cork</td>
      <td>6.210747</td>
      <td>6.484349</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Pulp, Paper, Paper , Printing and Publishing</td>
      <td>4.338523</td>
      <td>4.235671</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coke, Refined Petroleum and Nuclear Fuel</td>
      <td>1.123971</td>
      <td>3.053655</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Chemicals and Chemical Products</td>
      <td>1.624615</td>
      <td>2.183072</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Rubber and Plastics</td>
      <td>2.085719</td>
      <td>2.798665</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Other Non-Metallic Mineral</td>
      <td>0.176682</td>
      <td>0.493384</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Basic Metals and Fabricated Metal</td>
      <td>2.359734</td>
      <td>2.346964</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Machinery, Nec</td>
      <td>1.332708</td>
      <td>1.802747</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Electrical and Optical Equipment</td>
      <td>1.909170</td>
      <td>1.633738</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Transport Equipment</td>
      <td>6.753769</td>
      <td>4.626348</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Manufacturing, Nec; Recycling</td>
      <td>2.428586</td>
      <td>3.671017</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[23]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Histogram of the Revealed Comparative Advantage of Canada</span>

<span class="n">rcacan</span><span class="p">[</span><span class="s2">&quot;1995CAN&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span> <span class="o">=</span> <span class="s2">&quot;bar&quot;</span><span class="p">,</span> <span class="n">width</span> <span class="o">=</span> <span class="mf">0.6</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;#FF3333&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.5</span><span class="p">,</span> <span class="n">align</span><span class="o">=</span><span class="s1">&#39;center&#39;</span><span class="p">)</span>
<span class="n">rcacan</span><span class="p">[</span><span class="s2">&quot;2011CAN&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span> <span class="o">=</span> <span class="s2">&quot;bar&quot;</span><span class="p">,</span> <span class="n">width</span> <span class="o">=</span> <span class="mf">0.6</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;#00CC00&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.4</span><span class="p">,</span> <span class="n">align</span><span class="o">=</span><span class="s1">&#39;edge&#39;</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;RCA Canada &#39;95-&#39;11&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;RCA&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
vHixpP8dOTk/18aNG0t9EbOi1idJkyZNKjSuW7du+vjjj7V//37n9B07dhQ6h6SodWZkZCglJaVU
GYty9uxZjRkzRnXq1FH//v2d04v6mOfgwYOaMWOGmjRpojp16kiSGjZsqC5dujhv7du3L7NsQEXB
kRbAy0aNGqU+ffooNTVVDzzwgHPa999/r7/85S9atWqV7rrrLtWuXVtHjhzRxx9/rK+++krr16/X
xo0btXv3bj3yyCNFrrtu3bpq3ry5Zs+erWeeeabYDHfffbe2bdumV155Rd9884369+/vvCLu0qVL
tXLlSs2ZM0eSdOutt2rBggW6/fbb1aNHD+3du1dTp05VQkKCTp8+7fHjj4iIUIcOHfT666/L4XCo
bt26Wr58ufbu3VtobHJyspYuXaobb7xRDz30kHJzc/W3v/1NV199tb777jvnuK5duyokJEQ9e/bU
8OHDdfr0aU2fPl3R0dEXvJrshfTt21cxMTFKSEhQZmamZsyYoT179uizzz5zOYn56aefdn48FRMT
o3379mnatGk6c+aMJk+eXKptS78dPdq6dauk335S4LvvvtPLL78sSerVq5eaNGniHFsw/fvvv5ck
zZw5U2vXrpUkPf/886XOAPgdn353CbhEFXdFXGOMycvLM5dddpm57LLLTG5ursu8+fPnm65du5oa
NWqYoKAgU7t2bXPnnXeaf/7zn8YYYx599FEjyfz444/FbjspKclIcrlqa3FWrlxpbrvtNhMdHW2C
goJMZGSk6d69u1mwYIFzTH5+vnn11VdNXFycsdvtplmzZmbx4sVm0KBBLleRvdCVYSWZsWPHOu//
/PPP5vbbbzfVqlUzVatWNX369DGHDh0qNM4YY7744gvTokULExISYho2bGimTp1a5BVxFy1aZJo0
aWJCQ0NNfHy8GT9+vJkxY4aRZPbu3Vvi3+L3xo8fbxo3bmxCQ0NN9erVTa9evcw333xTaNycOXNM
hw4dTFRUlPNvePvtt5vNmzd7vM3zDRo0yEgq8paSkuIytrhxvMXjUmMzpohj0QAAAH6Gc1oAAIAl
UFoAAIAlUFoAAIAlUFoAAIAlUFoAAIAlWPo6Lfn5+Tp06JCqVKnicqVOAADgv4wxOnXqlGJiYhQQ
4P7xE0uXlkOHDjl/3wMAAFjLgQMHXH71viSWLi0FV6U8cOCA85drf8/hcGj58uXq2rWrgoODvRmP
LBbM4m95yEIWK+chC1mKk5mZqdjYWJerS7vDp6UlPj5eP/30U6HpDz30kN56660Sly/4SCgiIuKC
pSU8PFwRERF+sXOQxb+z+FsespDFynnIQpaSeHpqh09Ly6ZNm5SXl+e8v337diUmJqpPnz4+TAUA
APyRT0tLwU+2F3jttdd02WWXqWPHjkWOz87OVnZ2tvN+ZmampN+aosPhKHKZgunFzfcmshTNn7JI
/pWHLEUjS/H8KQ9ZikaW0m/Pb357KCcnRzExMRo5cqSee+65IsckJSUpOTm50PQ5c+YoPDy8vCMC
AIAykJWVpQEDBigjI6PY0zuK4jel5YMPPtCAAQO0f/9+xcTEFDmmqCMtsbGxOnbs2AXPaUlLS1Ni
YqJffHZIFv/O4m95yEIWK+chC1mKk5mZqcjISI9Li998e+idd95R9+7diy0skmS322W32wtNDw4O
LvGP7c4YbyFL0fwpi+RfechSNLIUz5/ykKVoFTlLabflF6Xlp59+0ooVK7RgwQJfRwEAAH7KLy7j
n5KSoujoaPXo0cPXUQAAgJ/yeWnJz89XSkqKBg0apKAgvzjwAwAA/JDPS8uKFSu0f/9+DR061NdR
AACAH/P5oY2uXbvKT77ABAAA/JjPj7QAAAC4g9ICAAAsgdICAAAsgdICAAAsgdICAAAsweffHgIA
4JIxbVrJY2w2qVYtKSVFcufbs8OHX3yuSwRHWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCVQ
WgAAgCVQWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCXwK8/wG6nHUmWC
3PjFUw8MixpWpusDAPgOR1oAAIAlUFoAAIAlUFoAAIAlUFoAAIAlUFoAAIAlUFoAAIAlUFoAAIAl
UFoAAIAlUFoAAIAlUFoAAIAlUFoAAIAlUFoAAIAlUFoAAIAl8CvPKF/TppU8xmaTatWS1q+TlFvy
+A4dLjoWAMB6ONICAAAsgdICAAAsgdICAAAsgdICAAAsgdICAAAsgdICAAAsgdICAAAsweel5eDB
g7r33ntVs2ZNhYWF6dprr9XXX3/t61gAAMDP+PTicidPnlT79u3VuXNnLVmyRFFRUdq1a5eqV6/u
y1gAAMAP+bS0jB8/XrGxsUpJSXFOa9CgQbHjs7OzlZ2d7byfmZkpSXI4HHI4HEUuUzC9uPneVCGz
2GwlZ/nvGJu7u2Nuyet0rrsUj69CPk9uIEvR/CmL5F95KmQWD97zHG6M/W1g+WX21XNU2u3ZjDGm
jLO4LSEhQd26ddPPP/+sL774QnXr1tVDDz2k+++/v8jxSUlJSk5OLjR9zpw5Cg8PL++4AACgDGRl
ZWnAgAHKyMhQRESE28v5tLSEhoZKkkaOHKk+ffpo06ZNGjFihKZOnapBgwYVGl/UkZbY2FgdO3as
2AftcDiUlpamxMREBQcHl88DcVOFzHLeUbRis9hsSouOVnrupzLu/PZQu/Zub35w5GC3xzrzVMTn
iSyXRBZ/y1Mhs3jwnpd49KiC3flf8JAhZRCsmCw+eo4yMzMVGRnpcWnx6cdD+fn5atmypV599VVJ
UrNmzbR9+/ZiS4vdbpfdbi80PTg4uMQ/tjtjvKVCZfGgExvluldagtxf58U8tgr1PHmALEXzpyyS
f+WpUFk8eM8LNsa90uKFv523n6PSbsun3x6qU6eOEhISXKZdddVV2r9/v48SAQAAf+XT0tK+fXvt
3LnTZdp//vMfxcXF+SgRAADwVz4tLU888YQ2bNigV199Vbt379acOXP09ttv6+GHH/ZlLAAA4Id8
WlpatWqlhQsXau7cubrmmmv00ksvadKkSbrnnnt8GQsAAPghn56IK0m33nqrbr31Vl/HAAAAfs7n
l/EHAABwB6UFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUF
AABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABY
AqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUF
AABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABYAqUFAABY
AqUFAABYAqUFAABYAqUFAABYgk9LS1JSkmw2m8utcePGvowEAAD8VJCvA1x99dVasWKF835QkM8j
AQAAP+TzhhAUFKTatWu7NTY7O1vZ2dnO+5mZmZIkh8Mhh8NR5DIF04ub700VMovNVnKW/46xubs7
5pa8Tue6S/H4KuTz5AayFM2fskj+ladCZvHgPc/hxtjfBpZfZl89R6Xdns0YY8o4i9uSkpL0xhtv
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
T2mzuKngeUpvkS4TWHYvVb/O4sN95mL+Lv7wWpL8c//lPe93Wby1//pTlt/JzMxUZGSkx6XFLz4e
euSRR7R48WKtWbOm2MIiSXa7XXa7vdD04ODgEndCd8Z4S4XK4kEnNsp170Xjwe/euDw2D/u5W3lK
m8VDJtCU6e/9+HUWH+4zF/N38afXkuRf+y/vecUMLe/915+yeDi/2M2XaqkyYozRo48+qoULF2r1
6tVq0KCBL+MAAAA/5tPS8vDDD2vOnDn65JNPVKVKFR05ckSSVLVqVYWFhfkyGgDACty5GKH0vwsS
pqSUfARi+PCLz4Vy4dPrtEyZMkUZGRnq1KmT6tSp47zNmzfPl7EAAIAf8vnHQwAAAO7gBxMBAIAl
UFoAAIAlUFoAAIAl+MV1WgAAl67UY6llem2fYVHDymxdsBaOtAAAAEugtAAAAEugtAAAAEugtAAA
AEugtAAAAEugtAAAAEugtAAAAEugtAAAAEvg4nJARTdtmnvjbDapVi1p/TpJuSWP79DhomIB5SG1
5nqZkvbfdJvb6+NCd97FkRYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJ
lBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJlBYAAGAJQb4OAACwmGnT
3Btns0m1aknr10nKvfDYDh0uOhYufRxpAQAAlkBpAQAAlkBpAQAAllBhzmlJPZYqE2TKbH3DooaV
2boAAEDJONICAAAsgdICAAAsgdICAAAsgdICAAAsgdICAAAsocJ8ewjwK1xRFAA8xpEWAABgCZQW
AABgCT4tLWvWrFHPnj0VExMjm82mjz/+2JdxAACAH/NpaTlz5oyuu+46vfXWW76MAQAALMCnJ+J2
795d3bt392UEAABgEZb69lB2drays7Od9zMzMyVJDodDDoejyGUKptvybGWapbjtubNMaZYta17L
Yiv57+747xibu7tjrvvPpcvjcyOLx3nIctF5Cu2DPtxn/Pp1fanvM5dCFjfz8Foq/evFZowpu18R
vAg2m00LFy5U7969ix2TlJSk5OTkQtPnzJmj8PDw8owHAADKSFZWlgYMGKCMjAxFRES4vZylSktR
R1piY2N17NixYh+0w+FQWlqa0lukywSW3UMdHDnY42UKsiQmJio4OLjMspSG17KkpJScxWZTWnS0
0nM/lSnpWiSS1K6925t3eZ7cyOJxHrJcdJ5CryUf7jN+/bq+1PeZSyGLm3l4Lf32/+/IyEiPS4ul
Ph6y2+2y2+2FpgcHB5f4ZmECjUxQ2ZWWi3lzcievt5R7Fg86sVGuey8aD55Hl8fmYT93Kw9ZLjpP
of3Ph/uMX7+uL/V95lLI4mGeivxaKu1rheu0AAAAS/DpkZbTp09r9+7dzvt79+7Vt99+qxo1aqh+
/frur2jGDCksrOh5nlwGXeJS6AAA+Cmflpavv/5anTt3dt4fOXKkJGnQoEFKTU31USoAAOCPfFpa
OnXqJD85DxgAAPg5zmkBAACWQGkBAACWQGkBAACWQGkBAACWQGkBAACWQGkBAACWQGkBAACWQGkB
AACWQGkBAACWQGkBAACWQGkBAACWQGkBAACWQGkBAACW4NNfeUY5mTat5DE2m1SrlpSSIrnzS9vD
h198LgAALgJHWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCVQWgAAgCXw7SEAKAOpx1Jlgtz4Jp6bhkUN
K7N1AZcKjrQAAABLoLQAAABLoLQAAABLoLQAAABLoLQAAABL4NtDFVxqzfUyyi15YLrNrfXxjQcA
QHmhtJQVfqQQAIByxcdDAADAEigtAADAEigtAADAEigtAADAEigtAADAEvj2kA/wNWMAADzHkRYA
AGAJlBYAAGAJlBYAAGAJnNMCAMXx5ErX69dJ7pyr1qHDRccCKiqOtAAAAEugtAAAAEugtAAAAEug
tAAAAEvweWl56623FB8fr9DQULVp00ZfffWVryMBAAA/5NPSMm/ePI0cOVJjx47Vli1bdN1116lb
t246evSoL2MBAAA/5NPSMmHCBN1///0aMmSIEhISNHXqVIWHh2vGjBm+jAUAAPyQz67TkpOTo82b
N2v06NHOaQEBAerSpYu+/PLLIpfJzs5Wdna2835GRoYk6UR2thy2on+nx2GzKSsrS+dy82WUX3Kw
k+fcyn884LjrhHMlL0cW72YplMeNLB7nIctF5/GnfcbqWTzO40/7zKWQxc08/rTPeC3L75w6dUqS
ZIxxa31OxkcOHjxoJJn169e7TB81apRp3bp1kcuMHTvWSOLGjRs3bty4XQK3AwcOeNQdLHVF3NGj
R2vkyJHO+/n5+Tpx4oRq1qwpWzFHWjIzMxUbG6sDBw4oIiLCW1HJYtEs/paHLGSxch6ykKU4xhid
OnVKMTExHi3ns9ISGRmpwMBA/fLLLy7Tf/nlF9WuXbvIZex2u+x2u8u0atWqubW9iIgIn+8cBchS
NH/KIvlXHrIUjSzF86c8ZClaRc9StWpVj5fx2Ym4ISEhatGihVauXOmclp+fr5UrV6pt27a+igUA
APyUTz8eGjlypAYNGqSWLVuqdevWmjRpks6cOaMhQ4b4MhYAAPBDgUlJSUm+2vg111yjatWq6ZVX
XtGbb74pSZo9e7auvPLKMt1OYGCgOnXqpKAg35/CQxb/zyL5Vx6ykMVT/pSHLGQpSzZjPP2+EQAA
gPf5/DL+AAAA7qC0AAAAS6C0AAAAS6C0AAAAS6C0AAAAS6C0AL/DF+oAwD/5/5eyPXTs2DHNmDFD
X375pY4cOSJJql27ttq1a6fBgwcrKirKxwnh7+x2u7Zu3aqrrrrK11GACzp8+LCmTJmitWvX6vDh
wwoICFDDhg3Vu3dvDR48WIGBgb6OCJSpS+o6LZs2bVK3bt0UHh6uLl26qFatWpJ++z2jlStXKisr
S8uWLVPLli19nPQ3Bw4c0NixYzVjxoxy39bZs2e1efNm1ahRQwkJCS7zzp07pw8++EADBw4s9xwF
duzYoQ0bNqht27Zq3Lix/v3vf2vy5MnKzs7Wvffeq5tuuqncM5z/45vnmzx5su69917VrFlTkjRh
woRyz1KUM2fO6IMPPtDu3btVp04d9e/f35mpvG3ZskXVq1dXgwYNJEkzZ87U1KlTtX//fsXFxemR
Rx5Rv379vJLl0UcfVd++fXXjjTd6ZXsl+fvf/66vvvpKt9xyi/r166eZM2dq3Lhxys/P1x133KEX
X3zRKxfp+vrrr9WlSxc1atRIYWFh+vLLLzVgwADl5ORo2bJlSkhI0NKlS1WlSpVyz1IgJydHH3/8
cZH/aLztttsUEhLitSwX8ssvv2jatGl64YUXvLrdn3/+WdWqVVPlypVdpjscDn355Zfq0KGDV3Ic
P35c3333na677jrVqFFDx44d0zvvvKPs7Gz16dPHv//B5tFvQvu5Nm3amGHDhpn8/PxC8/Lz882w
YcPM9ddf74NkRfv2229NQEBAuW9n586dJi4uzthsNhMQEGA6dOhgDh065Jx/5MgRr+QosGTJEhMS
EmJq1KhhQkNDzZIlS0xUVJTp0qWLuemmm0xgYKBZuXJlueew2WymadOmplOnTi43m81mWrVqZTp1
6mQ6d+5c7jkKXHXVVeb48ePGGGP2799v4uPjTdWqVU2rVq1M9erVTXR0tNmzZ49XsjRp0sSkpaUZ
Y4yZPn26CQsLM4899piZMmWKefzxx03lypXNO++845UsBfvt5Zdfbl577TVz+PBhr2y3KC+99JKp
UqWKufPOO03t2rXNa6+9ZmrWrGlefvll8+qrr5qoqCjzwgsveCVL+/btTVJSkvP+zJkzTZs2bYwx
xpw4ccI0bdrUPPbYY17JYowxu3btMg0bNjShoaGmY8eOpm/fvqZv376mY8eOJjQ01DRq1Mjs2rXL
a3kuxFvvvQUOHTpkWrVqZQICAkxgYKD54x//aE6dOuWc78334I0bN5qqVasam81mqlevbr7++mvT
oEEDc/nll5vLLrvMhIWFmc2bN3slS2lcUqUlNDTU7Nixo9j5O3bsMKGhoV7L88knn1zwNnHiRK/s
qL179zY9evQw6enpZteuXaZHjx6mQYMG5qeffjLGeL+0tG3b1vz5z382xhgzd+5cU716dfPcc885
5z/77LMmMTGx3HOMGzfONGjQoFBBCgoKMt9//325b//3bDab+eWXX4wxxtxzzz2mXbt25tdffzXG
GHPq1CnTpUsX079/f69kCQsLM/v27TPGGNOsWTPz9ttvu8yfPXu2SUhI8EoWm81mVqxYYUaMGGEi
IyNNcHCw6dWrl/n0009NXl6eVzIUuOyyy8xHH31kjPntf3yBgYFm1qxZzvkLFiwwjRo18kqWsLAw
8+OPPzrv5+XlmeDgYHPkyBFjjDHLly83MTExXslijDFdunQxt912m8nIyCg0LyMjw9x2222ma9eu
XsmydevWC97mzZvn1fe8gQMHmjZt2phNmzaZtLQ006JFC9OyZUtz4sQJY8xv78E2m80rWbp06WLu
u+8+k5mZad544w1Tr149c9999znnDxkyxPTu3dsrWUrjkiot8fHx5t133y12/rvvvmvi4uK8lqfg
X4g2m63YmzdeONHR0ea7775z3s/PzzcPPPCAqV+/vvnxxx+9XloiIiKc/+LKy8szQUFBZsuWLc75
27ZtM7Vq1fJKlq+++spcccUV5sknnzQ5OTnGGP8oLQ0bNjTLly93mb9u3ToTGxvrlSw1a9Y0X3/9
tTHmt/3n22+/dZm/e/duExYW5pUs5/9dcnJyzLx580y3bt1MYGCgiYmJMc8995zX/gUfFhbmLPvG
GBMcHGy2b9/uvL9v3z4THh7ulSxxcXFm7dq1zvuHDh0yNpvNZGVlGWOM2bt3r1f/kRYWFma2bdtW
7PzvvvvOq/tMce+9BdO9+Z4XExNjNm7c6Lx/7tw507NnT9O0aVNz/Phxr74HV69e3fzwww/GmN9e
TwEBAS7ZNm/ebOrWreuVLKVxSX176KmnntKwYcM0YsQILVq0SBs3btTGjRu1aNEijRgxQg888ICe
fvppr+WpU6eOFixYoPz8/CJvW7Zs8UqOs2fPunzGbrPZNGXKFPXs2VMdO3bUf/7zH6/kOJ/NZpMk
BQQEKDQ0VFWrVnXOq1KlijIyMrySo1WrVtq8ebPS09PVsmVLbd++3ZnNFwq2fe7cOdWpU8dlXt26
dZWenu6VHN27d9eUKVMkSR07dtT8+fNd5n/wwQdq1KiRV7KcLzg4WH379tXSpUu1Z88e3X///eXy
I6vFqV27tn744QdJ0q5du5SXl+e8L0nff/+9oqOjvZKld+/eeuCBB7R06VKtWrVK99xzjzp27Kiw
sDBJ0s6dO1W3bl2vZJGkatWqad++fcXO37dvn6pVq+aVLDVq1ND06dO1d+/eQrc9e/Zo8eLFXslR
ICMjQ9WrV3fet9vtWrBggeLj49W5c2cdPXrUa1lycnKc+0hwcLDCw8MVGRnpnB8ZGanjx497LY/H
fN2aytr7779v2rRpY4KCgpzNOigoyLRp08bMmzfPq1l69uxpxowZU+z8b7/91iuHBFu1amXee++9
Iuc9/PDDplq1al79V0eTJk3MkiVLnPe3bdtmHA6H8/6aNWtMgwYNvJanwNy5c02tWrVMQECAz460
XHvttaZZs2amcuXKZv78+S7zv/jiC6/9C+jgwYMmPj7edOjQwYwcOdKEhYWZG264wdx///2mQ4cO
JiQkxHz22WdeyXL+kZai5OfnFzoqVV6ef/55ExUVZe677z7ToEED8+yzz5r69eub//u//zPTpk0z
sbGx5oknnvBKllOnTpm+ffs63+vatWvncs7TsmXLzAcffOCVLMYYM2bMGFO9enUzYcIEs3XrVnPk
yBFz5MgRs3XrVjNhwgRTo0YNM3bsWK9k6dq1q3nppZeKne+t994C1157baHXszHGOBwO07t3b1O/
fn2vvQc3btzY5SPxxYsXO4/OGWPMhg0bTL169bySpTQuudJSICcnxxw6dMgcOnTIedjf29asWePy
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
4Pde36jzAAAAAElFTkSuQmCC
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The RCA of the US has increased in almost the same sectors as Canada. 'Food, Beverages and Tobacco', 'Wood and Products of Wood and Cork', 'Coke, Refined Petroleum and Nuclear Fuel', 'Chemicals and Chemical Products', 'Rubber and Plastics', 'Other Non-Metallic Mineral', 'Machinery, Nec' and 'Manufacturing, Nec; Recycling'. The biggest increases are for 'Coke, Refined Petroleum and Nuclear Fuel', 'Chemicals and Chemical Products', 'Rubber and Plastics' and 'Machinery, Nec'. The biggest loss in the RCA is also here for the sector 'Transport Equipment'. Again, we will see that Mexico is the one that will create a big increase in RCA in that sector and take the American specialisation in those inputs away. Afther having looked at RCAs of Canada and the US, we observe that both countries specialise in same sectors and trade wich each other in similar products. Both countries also lose their comparative advantage in 'Basic Metals and Fabricated Metal', 'Machinery, Nec', 'Electrical and Optical Equipment' and 'Transport Equipment'. Canada looses RCA especially in 'Transport Equipment' while the US in 'Electrical and Optical Equipment'.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[24]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Histogram of Revealed Comparative Advantage of the USA</span>

<span class="n">rcaus</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_excel</span><span class="p">(</span><span class="sa">r</span><span class="s1">&#39;C:\Users\Jesse\Downloads\PythonFinal\RCA.xlsx&#39;</span><span class="p">,</span> <span class="s2">&quot;RCA_US&quot;</span><span class="p">)</span>
<span class="n">FORMAT</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Sector&#39;</span><span class="p">,</span><span class="s1">&#39;1995USA&#39;</span><span class="p">,</span><span class="s1">&#39;2011USA&#39;</span><span class="p">]</span>
<span class="n">rcaus_selected</span> <span class="o">=</span> <span class="n">rcaus</span><span class="p">[</span><span class="n">FORMAT</span><span class="p">]</span>
<span class="n">rcaus</span>

<span class="n">rcaus</span><span class="p">[</span><span class="s2">&quot;1995USA&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span> <span class="o">=</span> <span class="s2">&quot;bar&quot;</span><span class="p">,</span> <span class="n">width</span> <span class="o">=</span> <span class="mf">0.6</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;#FF3333&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.5</span><span class="p">,</span> <span class="n">align</span><span class="o">=</span><span class="s1">&#39;center&#39;</span><span class="p">)</span>
<span class="n">rcaus</span><span class="p">[</span><span class="s2">&quot;2011USA&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span> <span class="o">=</span> <span class="s2">&quot;bar&quot;</span><span class="p">,</span> <span class="n">width</span> <span class="o">=</span> <span class="mf">0.6</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;#00CC00&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.4</span><span class="p">,</span> <span class="n">align</span><span class="o">=</span><span class="s1">&#39;edge&#39;</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;RCA United States &#39;95-&#39;11&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;RCA&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAi0AAAHKCAYAAADPQHvVAAAABHNCSVQICAgIfAhkiAAAAAlwSFlz
AAAPYQAAD2EBqD+naQAAIABJREFUeJzt3Xd4VHWixvF30hMgoRMikARQARHpSJFeFpHiUkRUiguI
qwJyRcVGsIDsKuBakGWVKAJSBES5dEEWEKUI0kRQUJQWYEmAQBKS3/2DzVyGJGQSkpn5wffzPPPo
nPqeYSbzzplzzjiMMUYAAAA+zs/bAQAAANxBaQEAAFagtAAAACtQWgAAgBUoLQAAwAqUFgAAYAVK
CwAAsAKlBQAAWIHSAgAArEBpAW4wMTEx6t+/v0fW1b9/f8XExHhkXQCuf5QW3JDi4+PlcDict4CA
AN10003q37+//vjjjxznW7BggTp27KjSpUsrKChIUVFR6tWrl7766qtsp//f//1fORwORUVFKSMj
w+18LVu2VM2aNbMdd+LECTkcDsXFxbm9vKvZvXu34uLidPDgwQJZXn5kZGTo448/VqNGjVSyZEkV
K1ZMt9xyi/r27auNGzcWaNaZM2dq0qRJBZA672JiYrL8u+3fv189evRQiRIlFBYWpmbNmmn16tVZ
5o2Li3N5zmbeQkJC3Fr3wYMH5XA4tGbNGuewI0eO6Nlnn1WrVq1UrFixLOMvt3z5cv3lL39RzZo1
5e/vTxmFVwR4OwDgTS+//LJiY2N14cIFbdy4UfHx8Vq3bp127tzp8mZgjNHDDz+s+Ph41alTRyNG
jFBkZKSOHDmiBQsWqE2bNlq/fr2aNGnisvwZM2YoJiZGBw8e1FdffaW2bdt6ehOz2Lt3r/z8/v/z
yu7duzVmzBi1bNnSa29EQ4cO1bvvvquuXbvqgQceUEBAgPbu3aslS5aocuXKuvPOOwss68yZM7Vz
504NHz68ALcgfw4dOqTGjRvL399fI0eOVJEiRTRt2jS1b99eq1atUvPmzbPMM3nyZBUtWtR539/f
P9/r37t3r8aPH6+bb75Zt99+u7755pscp505c6Zmz56tunXrKioqKt/rBK4FpQU3tI4dO6p+/fqS
pIEDB6p06dIaP368Fi1apF69ejmne/PNNxUfH6/hw4drwoQJcjgcznHPP/+8pk+froAA15fTuXPn
9Pnnn2vcuHGaNm2aZsyY4ROlJTg42NsRXBw7dkzvvfeeBg0apH/+858u4yZNmqSEhAQvJSt8r7/+
uk6fPq2dO3fq1ltvlSQNGjRI1apV05NPPqktW7ZkmadHjx4qXbp0gay/Xr16OnnypEqWLKl58+ap
Z8+eOU47duxYTZ06VYGBgbrnnnu0c+fOAskA5AVfDwGXueuuuyRJP//8s3PY+fPnNW7cOFWrVk1v
vPGGS2HJ9NBDD6lhw4YuwxYsWKDz58+rZ8+e6t27t+bPn68LFy4USu7Mrw7279+v/v37q3jx4oqI
iNCAAQOUnJzsMu3lx7TEx8c736hatWrl/Mrh8q8IlixZorvuuktFihRRsWLF1KlTJ+3atStLhoUL
F6pmzZoKCQlRzZo1tWDBAreyHzhwQMYYNW3aNMs4h8OhsmXLupX1888/V6dOnRQVFaXg4GBVqVJF
r7zyitLT053La9mypRYvXqxff/3VOf/le2xSUlI0evRoVa1aVcHBwapYsaKefvpppaSkuORasWKF
mjVrpuLFi6to0aK69dZb9dxzz7m1vZf797//rTp16jgLiySFhYWpS5cu2rp1q/bt25dlHmOMkpKS
ZIzJ8/quVKxYMZUsWdKtaaOiohQYGHjN6wSuBXtagMtkHitRokQJ57B169bp1KlTGj58eJ52xc+Y
MUOtWrVSZGSkevfurWeffVZffPHFVT/NXqtevXopNjZW48aN09atW/Wvf/1LZcuW1fjx47Odvnnz
5ho6dKj+8Y9/6LnnnlP16tUlyfnf6dOnq1+/furQoYPGjx+v5ORkTZ48Wc2aNdP333/vfMNfvny5
unfvrho1amjcuHE6efKkBgwYoAoVKuSaOTo6WpI0d+5c9ezZU2FhYfnKGh8fr6JFi2rEiBEqWrSo
vvrqK7300ktKSkrS3//+d0mX9oolJibq999/18SJEyXJ+VVLRkaGunTponXr1mnw4MGqXr26duzY
oYkTJ+qnn37SwoULJUm7du3SPffco1q1aunll19WcHCw9u/fr/Xr1+e6rVdKSUlxea5lynwMtmzZ
optvvtllXOXKlXX27FkVKVJE3bp105tvvqly5crled2AlQxwA5o2bZqRZFauXGkSEhLMoUOHzLx5
80yZMmVMcHCwOXTokHPat956y0gyCxYscHv5x44dMwEBAWbq1KnOYU2aNDFdu3Z1a/4WLVqY2267
LdtxCQkJRpIZPXq0c9jo0aONJPPwww+7THvvvfeaUqVKuQyLjo42/fr1c96fO3eukWRWr17tMt2Z
M2dM8eLFzaBBg1yGHz161ERERLgMr127tilfvrw5ffq0c9jy5cuNJBMdHZ3r9vbt29dIMiVKlDD3
3nuveeONN8yePXuyTJdTVmOMSU5OzjLskUceMWFhYebChQvOYZ06dco20/Tp042fn5/597//7TL8
/fffN5LM+vXrjTHGTJw40UgyCQkJuW5Xbjp37myKFy9ukpKSXIY3btzYSDJvvPGGc9ikSZPM448/
bmbMmGHmzZtnhg0bZgICAszNN99sEhMTrznL1R7bK+X0GAKFja+HcENr27atypQpo4oVK6pHjx4q
UqSIFi1a5LKHICkpSdKlXenu+vTTT+Xn56fu3bs7h91///1asmSJ/vOf/xTcBlxhyJAhLvfvuusu
nTx50rkNebFixQqdPn1a999/v06cOOG8+fv7q1GjRs4zXI4cOaJt27apX79+ioiIcM7frl071ahR
w611TZs2Te+8845iY2O1YMECPfXUU6pevbratGlz1bO5LhcaGur8/zNnzujEiRO66667lJycrB9/
/DHX+efOnavq1aurWrVqLtvbunVrSXJub/HixSVd+joqL2eEZefRRx/V6dOndd999+n777/XTz/9
pOHDh2vz5s2SLn01mWnYsGF6++231adPH3Xv3l2TJk3SRx99pH379um99967phyALSgtuKG9++67
WrFihebNm6e7775bJ06cyHKganh4uKRLb4Tu+uSTT9SwYUOdPHlS+/fv1/79+1WnTh2lpqZq7ty5
BZI9u2NrKlWq5HI/86uH/BSlzOMpWrdurTJlyrjcli9fruPHj0uSfv31V0nK8jWGJJdjNa7Gz89P
jz32mLZs2aITJ07o888/V8eOHfXVV1+pd+/ebi1j165duvfeexUREaHw8HCVKVNGDz74oCQpMTHR
re3dtWtXlm295ZZbJMm5vffdd5+aNm2qgQMHqly5curdu7fmzJmTrwLTsWNHvf3221q7dq3q1q2r
W2+9VYsXL9Zrr70mSS5nCWWnT58+ioyM1MqVK53DEhISdPToUeft7Nmzec4F+CqOacENrWHDhs6z
h7p166ZmzZqpT58+2rt3r/MNo1q1apKkHTt2qFu3brkuc9++fdq0aZOk7N/IZ8yYocGDB191GSEh
IS6fsi+XeWBtdtfnyOmYG5OPgzYz34SnT5+uyMjILOOvPFuqoJQqVUpdunRRly5d1LJlS3399df6
9ddfnce+ZOf06dNq0aKFwsPD9fLLL6tKlSoKCQnR1q1b9cwzz7hVKDIyMnT77bdrwoQJ2Y6vWLGi
pEt7dNauXavVq1dr8eLFWrp0qWbPnq3WrVtr+fLleT4F+fHHH9eAAQP0ww8/KCgoSLVr19YHH3wg
Sc7CdDUVK1bUqVOnnPcbNGjgLJKSNHr06AK7pg/gbZQW4L/8/f01btw4tWrVSu+8846effZZSVKz
Zs1UokQJzZo1S88991yub0ozZsxQYGCgpk+fnmXadevW6R//+Id+++23LHtFLhcdHa2vvvpK58+f
d/naQ7p0bY3MaQpCdntsJKlKlSqSpLJly171VO3MHNmd6ZKZNb/q16+vr7/+WkeOHFF0dHSOWdes
WaOTJ09q/vz5Ltc2OXDgQJZpr7a927dvV5s2bXKcJpOfn5/atGmjNm3aaMKECRo7dqyef/55rV69
Ol+ntRcpUkSNGzd23l+5cqVCQ0OzPaPqcsYYHTx4UHXq1HEOmzFjhkvhrVy5cp7zAL6Kr4eAy7Rs
2VINGzbUpEmTnKcnh4WF6ZlnntGePXv0zDPPZLvX4pNPPtF3330n6dKbxl133aX77rtPPXr0cLmN
HDlSkjRr1qyr5rj77ruVlpamKVOmuAzPyMjQ5MmTFRQUpDZt2hTEJqtIkSKSLu2tuFyHDh0UHh6u
sWPHKi0tLct8mddPKV++vGrXrq2PPvrI5WuYFStWaPfu3bmu/+jRo9lOl5qaqlWrVsnPz09Vq1a9
atbMcnj5v01qamq2x3oUKVIk26+LevXqpT/++ENTp07NMu78+fM6d+6cJLns1chUu3ZtScpyanR+
bNiwQfPnz9df/vIXl2OEsrtezeTJk5WQkKA//elPzmFNmzZV27ZtnTdKC64n7GkBrjBy5Ej17NlT
8fHxzgNbR44cqV27dunNN9/U6tWr1aNHD0VGRuro0aNauHChvvvuO23YsEHffvut9u/fr8cffzzb
Zd90002qW7euZsyYoWeeeSbHDJ07d1b79u315JNP6rvvvlOTJk2UnJysRYsWaf369Xr11VdVpkyZ
Atne2rVry9/fX+PHj1diYqKCg4PVunVrlS1bVpMnT9ZDDz2kunXrqnfv3ipTpox+++03LV68WE2b
NtU777wjSRo3bpw6deqkZs2a6eGHH9apU6f09ttv67bbbsv1mIrff/9dDRs2VOvWrdWmTRtFRkbq
+PHjmjVrlrZv367hw4c7L6aWU9YmTZqoRIkS6tevn4YOHSqHw6Hp06dnWzDr1aun2bNna8SIEWrQ
oIGKFi2qzp0766GHHtKcOXM0ZMgQrV69Wk2bNlV6erp+/PFHzZkzR8uWLVP9+vX18ssva+3aterU
qZOio6N1/Phxvffee6pQoYKaNWuWp8f+119/Va9evdSlSxdFRkZq165dev/991WrVi2NHTvWZdro
6Gjdd999uv322xUSEqJ169bp008/Ve3atfXII4/kab2Xe/XVVyXJee2d6dOna926dZKkF154wTnd
Dz/8oEWLFkm69NMDiYmJznnvuOMOde7cOd8ZALd59dwlwEsyT3netGlTlnHp6emmSpUqpkqVKubi
xYsu4+bNm2fat29vSpYsaQICAkxkZKTp3r27+eqrr4wxxjzxxBNGkvn5559zXHdcXJyRZLZv337V
jBcuXDBxcXGmWrVqJjg42BQpUsTceeed5pNPPskybeYpz1eehpu5nQcOHHAOu/KUZ2OMmTp1qqlc
ubLx9/fPctrr6tWrTYcOHUxERIQJCQkxVapUMf379zebN292WcZnn31mqlevboKDg02NGjXM/Pnz
Tb9+/XI9NTYpKcm89dZbpkOHDqZChQomMDDQFCtWzDRu3NhMnTrVZGRkuJV1/fr15s477zShoaEm
KirKPP3002bZsmVZtufs2bOmT58+pnjx4llOyU5NTTXjx483t912mwkODjYlSpQw9erVM2PGjHGe
Vrxq1SrTtWtXExUVZYKCgkxUVJS5//77zU8//XTV7czOqVOnTNeuXU1kZKQJCgoysbGx5plnnsly
CrQxxgwcONDUqFHDFCtWzAQGBpqqVavmOG1eSMrxdrnM51J2tyufT0BhcRhTAJdVBAAAKGQc0wIA
AKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwApWX6clIyNDhw8fVrFixXK9giUAAPANxhidOXNGUVFR
8vNzf/+J1aXl8OHDzt8DAQAAdjl06JAqVKjg9vRWl5ZixYpJurTRmb/Ee6W0tDQtX75c7du3V2Bg
oCfjkcXCLL6WhyxksTkPWciSk6SkJFWsWNH5Pu4uq0tL5ldC4eHhVy0tYWFhCg8P94knB1l8O4uv
5SELWWzOQxay5Cavh3ZwIC4AALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwAqU
FgAAYAVKCwAAsAKlBQAAWIHSAgAArEBpAQAAVqC0AAAAK1BaAACAFSgtAADACgHeDgAAQL5NmeLe
dA6HVK6cNG2aZMzVp33kkWvPhULBnhYAAGAFSgsAALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQ
WgAAgBUoLQAAwAqUFgAAYAVKCwAAsAKlBQAAWIHSAgAArEBpAQAAVqC0AAAAK1BaAACAFSgtAADA
CpQWAABgBUoLAACwAqUFAABYgdICAACsQGkBAABWoLQAAAArUFoAAIAVKC0AAMAKlBYAAGAFSgsA
ALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwAqUFgAAYAVKCwAAsAKlBQAAWIHS
AgAArEBpAQAAVvCZ0vL666/L4XBo+PDh3o4CAAB8kE+Ulk2bNmnKlCmqVauWt6MAAAAfFeDtAGfP
ntUDDzygqVOn6tVXX73qtCkpKUpJSXHeT0pKkiSlpaUpLS0t23kyh+c03pPIkj1fyiL5Vh6yZI8s
OfOlPB7J4nC4l+W/06W5M30hP3Y33L/RVdabVw5jjCngLHnSr18/lSxZUhMnTlTLli1Vu3ZtTZo0
Kdtp4+LiNGbMmCzDZ86cqbCwsMKOCgAACkBycrL69OmjxMREhYeHuz2fV/e0fPrpp9q6das2bdrk
1vSjRo3SiBEjnPeTkpJUsWJFtW/fPseNTktL04oVK9SuXTsFBgYWSO78IovvZ/G1PGQhi815PJJl
2jT3sjgcWlG2rNodP67A3D6rDxhQAMGukuVG+zfKRuY3JXnltdJy6NAhDRs2TCtWrFBISIhb8wQH
Bys4ODjL8MDAwFwfbHem8RSyZM+Xski+lYcs2SNLznwpT6FmyeOXBYHG5F5aPPS43TD/RjmsLz+8
Vlq2bNmi48ePq27dus5h6enpWrt2rd555x2lpKTI39/fW/EAAICP8VppadOmjXbs2OEybMCAAapW
rZqeeeYZCgsAAHDhtdJSrFgx1axZ02VYkSJFVKpUqSzDAQAAfOI6LQAAALnx+nVaLrdmzRpvRwAA
AD6KPS0AAMAKlBYAAGAFSgsAALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwAqU
FgAAYAVKCwAAsAKlBQAAWIHSAgAArEBpAQAAVqC0AAAAK1BaAACAFSgtAADACpQWAABgBUoLAACw
AqUFAABYgdICAACsQGkBAABWoLQAAAArUFoAAIAVKC0AAMAKAd4OAAAAvCv+RLxMgCmw5Q0uM7jA
lnU59rQAAAArUFoAAIAVKC0AAMAKlBYAAGAFSgsAALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtw
RVwAALzAlqvQ+hL2tAAAACtQWgAAgBUoLQAAwAqUFgAAYAVKCwAAsAKlBQAAWIHSAgAArEBpAQAA
VqC0AAAAK1BaAACAFbiMPwDghhFfaoOMLl59ogSH28vLcun8KVNyn8nhkMqVkzasl3LLIknNm7ud
53rHnhYAAGAFSgsAALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwAqUFgAAYAVK
CwAAsAKlBQAAWIHSAgAArEBpAQAAVqC0AAAAK1BaAACAFSgtAADACgHeDgAAsMyUKe5N53BI5cpJ
06ZJxlx92kceufZcuO6xpwUAAFiB0gIAAKzg1dIyefJk1apVS+Hh4QoPD1fjxo21ZMkSb0YCAAA+
yqulpUKFCnr99de1ZcsWbd68Wa1bt1bXrl21a9cub8YCAAA+yKsH4nbu3Nnl/muvvabJkydr48aN
uu2227yUCgBQkOJLbZDRxatPlOBwe3mDywy+xkSwlc+cPZSenq65c+fq3Llzaty4cbbTpKSkKCUl
xXk/KSlJkpSWlqa0tLRs58kcntN4TyJL9nwpi+RbeciSPbLkzCN5HO4VjLT/Tudw563movulxWXb
fCmLm3nylCUPefLzb545jyPd/W0uiCz5fX46jMntPLTCtWPHDjVu3FgXLlxQ0aJFNXPmTN19993Z
ThsXF6cxY8ZkGT5z5kyFhYUVdlQAAFAAkpOT1adPHyUmJio8PNzt+bxeWlJTU/Xbb78pMTFR8+bN
07/+9S99/fXXqlGjRpZps9vTUrFiRZ04cSLHjU5LS9OKFSvUrl07BQYGFtp2uIMsvp/F1/KQhSw+
mWfaNPeyOBxaUbasEi5+kfvXQ02aur36/qX7+2YWN/PkKUse8mTJ4obM50tCvQQZ/4KrA7llSUpK
UunSpfNcWrz+9VBQUJCqVq0qSapXr542bdqkt956S1OyuXhRcHCwgoODswwPDAzM9cXpzjSeQpbs
+VIWybfykCV7ZMlZoebJ42ddo4u5vzkHuL9Ml+3ypSx5zONWljzkuZZ/b+NvZPKw3deaJb9Zfe46
LRkZGS57UwAAACQv72kZNWqUOnbsqEqVKunMmTOaOXOm1qxZo2XLlnkzFgAA8EFeLS3Hjx9X3759
deTIEUVERKhWrVpatmyZ2rVr581YAADAB3m1tHzwwQfeXD0AALCIzx3TAgAAkB1KCwAAsAKlBQAA
WIHSAgAArEBpAQAAVqC0AAAAK3j9Mv4A7BJ/Ir5AL/c9uMzgAlsWgOsbe1oAAIAVKC0AAMAKlBYA
AGAFSgsAALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwAqUFgAAYAVKCwAAsAKl
BQAAWIHSAgAArEBpAQAAVqC0AAAAK1BaAACAFSgtAADACpQWAABgBUoLAACwAqUFAABYgdICAACs
QGkBAABWoLQAAAArFGhp2bNnj5566qmCXCQAAICkAigt586d0wcffKAmTZrotttu09KlSwsiFwAA
gIt8l5b169fr4YcfVrly5TR48GA1adJEu3fv1s6dOwsyHwAAgKQ8lpbjx4/rb3/7m6pVq6YePXqo
ePHiWrNmjfz8/PTwww+rWrVqhZUTAADc4ALyMnF0dLR69Oiht956S+3atZOfH8fxAgAAz8hT64iO
jta6deu0du1a/fTTT4WVCQAAIIs8lZYff/xRn3zyiY4cOaIGDRqoXr16mjhxoiTJ4XAUSkAAAAAp
HwfiNm3aVB9++KGOHDmiIUOGaO7cuUpPT9df//pXTZ06VQkJCYWREwAA3ODyfVBK0aJFNWjQIG3Y
sEG7du1SvXr19MILLygqKqog8wEAAEgqoIvLVa9eXW+88Yb++OMPzZ49uyAWCQAA4CJPpeXw4cN6
6qmnlJSUlGVcYmKiRo0apUaNGhVYOAAAgEx5Ki0TJkxQUlKSwsPDs4yLiIjQmTNnNG7cuAILBwAA
kClPpWXp0qXq27dvjuP79u2r1atXX3MoAACAK+WptBw4cECVKlXKcXyFChV08ODBa80EAACQRZ5K
S2ho6FVLycGDBxUaGnqtmQAAALLIU2lp1KiRpk+fnuP4jz/+WA0bNrzmUAAAAFfK028PPfXUU2rX
rp0iIiI0cuRIlStXTpJ07Ngx/e1vf1N8fLyWL19eKEEBAMCNLU+lpVWrVnr33Xc1bNgwTZw4UeHh
4XI4HEpMTFRgYKDefvtttW7durCyAgCAG1ieSoskPfLII+rUqZPmzp2r/fv3yxijW265RT169FCF
ChV0/vx5jmsBAAAFLs+lRbp0ltCTTz7pMiwlJUUTJkzQ3/72Nx09erRAwgHwgClT3JvO4ZDKlZM2
rJd0Mffpmze/plgAcKU8HYibkpKiUaNGqX79+mrSpIkWLlwoSZo2bZpiY2M1ceLELGUGAACgIORp
T8tLL72kKVOmqF27dlq/fr169uypAQMGaOPGjZowYYJ69uwpf3//wsoKAABuYHkqLXPnztXHH3+s
Ll26aOfOnapVq5YuXryo7du3y+FwFFZGAACAvH099Pvvv6tevXqSpJo1ayo4OFhPPvkkhQUAABS6
PJWW9PR0BQUFOe8HBASoaNGiBR4KAADgSnn6esgYo/79+ys4OFiSdOHCBQ0ZMkRFihRxmW7+/PkF
lxAAAEB5LC39+vVzuf/ggw8WaBgAAICc5Km0TJs2rbByAAAAXFWejmkBAADwFkoLAACwAqUFAABY
gdICAACsQGkBAABWoLQAAAArUFoAAIAVKC0AAMAKXi0t48aNU4MGDVSsWDGVLVtW3bp10969e70Z
CQAA+Civlpavv/5ajz32mDZu3KgVK1YoLS1N7du317lz57wZCwAA+KA8Xca/oC1dutTlfnx8vMqW
LastW7aoefPmXkoFAAB8kVdLy5USExMlSSVLlsx2fEpKilJSUpz3k5KSJElpaWlKS0vLdp7M4TmN
9ySyZM+Xski+lccjWRwO97L8dzqHu382Lrq53Hxs2w33b5QH1j5n3Hy+SFdsmy9lcTOPL76WHOnu
b3NBZMnv89NhjDH5mrOAZWRkqEuXLjp9+rTWrVuX7TRxcXEaM2ZMluEzZ85UWFhYYUcEAAAFIDk5
WX369FFiYqLCw8Pdns9nSsujjz6qJUuWaN26dapQoUK202S3p6VixYo6ceJEjhudlpamFStWqF27
dgoMDCyU7O4ii+9n8bU8Hsni5q+3pzkcWlG2rBIufiGji7nP0KSpW8vtX7q/W9O5ZLnR/o18LU9h
PGfcfL5IVzxnfCmLm3l88bWUUC9Bxr/g6kBuWZKSklS6dOk8lxaf+Hro8ccf15dffqm1a9fmWFgk
KTg4WMHBwVmGBwYG5vridGcaTyFL9nwpi+RbeQo1Sx4/txhddO8PbYB7y72W7bph/o3ywbrnjJvP
F+mK54wvZcljHl96LRl/I5OH7b7WLPnN6tXSYozRE088oQULFmjNmjWKjY31ZhwAAODDvFpaHnvs
Mc2cOVOff/65ihUrpqNHj0qSIiIiFBoa6s1oAADAx3j1Oi2TJ09WYmKiWrZsqfLlyztvs2fP9mYs
AADgg7x3GHEGAAAZ9klEQVT+9RAAAIA7fOJAXAAAUMCmTMl9GodDKldO2rBecuegYC9f+JUfTAQA
AFagtAAAACvw9RBggfgT8QV6DYXBZQYX2LIAwFPY0wIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAA
wAqUFgAAYAVKCwAAsAKlBQAAWIHSAgAArEBpAQAAVuAy/rhxuPOLp9L//+rptGmSyeXS+Y88cu25
AABuYU8LAACwAqUFAABYga+HgBzEl9ogo4tXnyjB4fby+GVlALg27GkBAABWoLQAAAArUFoAAIAV
KC0AAMAKlBYAAGAFSgsAALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwAqUFgAA
YAVKCwAAsAKlBQAAWIHSAgAArEBpAQAAVqC0AAAAK1BaAACAFSgtAADACpQWAABgBUoLAACwAqUF
AABYgdICAACsQGkBAABWoLQAAAArUFoAAIAVKC0AAMAKlBYAAGAFSgsAALACpQUAAFiB0gIAAKxA
aQEAAFagtAAAACtQWgAAgBUCvB0AAPIr/kS8TIApsOUNLjO4wJYFoOCxpwUAAFiB0gIAAKxAaQEA
AFagtAAAACtQWgAAgBUoLQAAwAqUFgAAYAWu0wLAt0yZkvs0DodUrpy0Yb2ki7lP37z5NccC4H3s
aQEAAFagtAAAACtQWgAAgBUoLQAAwAqUFgAAYAWvlpa1a9eqc+fOioqKksPh0MKFC70ZBwAA+DCv
lpZz587pjjvu0LvvvuvNGAAAwAJevU5Lx44d1bFjR7enT0lJUUpKivN+UlKSJCktLU1paWnZzpM5
PKfxBWbatFwnSXM4pLJllRYfLxmT+zIHDLj2XDll8dTj4gaPZXE43Jos7b/TOdx5eVx0b5lS/rYv
cx5HuvvryXOWwnhcJLcfmyyPixt5PJYlD/P4wmtJ8lAeX3ot+VIWN/PwWsr/89NhjDvvnoXP4XBo
wYIF6tatW47TxMXFacyYMVmGz5w5U2FhYYUZDwAAFJDk5GT16dNHiYmJCg8Pd3s+q0pLdntaKlas
qBMnTuS40WlpaVqxYoXatWunwMDAAs/t5OaelhVly6rd8eMK9IE9LR55XHwpixv/RtL//zslXPxC
JrerrTZp6vbq+5fu7/a0ziz/fWwS6iXI+BfcS9UlS2E8LpLbj02WxyUPr6VCz+IGX3oteSyPL72W
fCmLm3l4LV16/y5dunSeS4tVl/EPDg5WcHBwluGBgYG5vjjdmeaa5KH7BRrjXmnxwB/AQn9c8sCX
/o0kyehi7i/igDz8u1/Dthl/I5OHdeUpS2E8LpLbj02WxyUPeQo9Sx740mtJKuQ8vvRa8qUsecxz
I7+W8vvc5JRnAABgBUoLAACwgle/Hjp79qz279/vvH/gwAFt27ZNJUuWVKVKlbyYDAAA+BqvlpbN
mzerVatWzvsjRoyQJPXr10/x8fFeSgUAAHyRV0tLy5Yt5SMnLwHAdSX+RHyBHrw9uMzgAlsWkF9W
nT10LXgBAwBgNw7EBQAAVqC0AAAAK9wwXw8BgNWmTHFvOodDKldO2rBeyu1iYc2bX3MswJMoLYA3
8AYEAHlGaUHhcufNOfONedo09y47/cgj154LAGCd66O0fPihFBqa/bi8fFKV+LQKAICP4kBcAABg
BUoLAACwAqUFAABYgdICAACsQGkBAABWoLQAAAArUFoAAIAVKC0AAMAKlBYAAGAFSgsAALACpQUA
AFiB0gIAAKxAaQEAAFa4Pn7l2TLxpTbIuPOL0wkOt5Y3uMzga0wEAIDvY08LAACwAqUFAABYgdIC
AACsQGkBAABWoLQAAAArUFoAAIAVKC0AAMAKlBYAAGAFSgsAALACpQUAAFiBy/jDZxT0zxtI/MQB
PCf+RLxMgCmw5fHcBbJiTwsAALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtw9tD1aMqU3KdxOKRy
5aRp0yTjxhkPjzxy7bkAALgG7GkBAABWoLQAAAArUFoAAIAVKC0AAMAKlBYAAGAFSgsAALACpQUA
AFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwAqUFgAAYAVKCwAAsAKlBQAAWIHSAgAArEBp
AQAAVqC0AAAAK1BaAACAFSgtAADACgHeDgAAPmvKlNyncTikcuWkDeslXcx9+ubNrzkWcKNiTwsA
ALACpQUAAFiB0gIAAKxAaQEAAFagtAAAACtQWgAAgBUoLQAAwApeLy3vvvuuYmJiFBISokaNGum7
777zdiQAAOCDvFpaZs+erREjRmj06NHaunWr7rjjDnXo0EHHjx/3ZiwAAOCDvFpaJkyYoEGDBmnA
gAGqUaOG3n//fYWFhenDDz/0ZiwAAOCDvHYZ/9TUVG3ZskWjRo1yDvPz81Pbtm31zTffZDtPSkqK
UlJSnPcTExMlSadSUpTmcGQ7T5rDoeTkZF24mCGjjNyD/eeCW/lP+p10HXAh9/l8Mcv7oetk3Ln0
+E8puU8j6YFSD+Q7S0E/LtIVj40bWfKchyzXnOd6eS35QpY85/Gl58z1kMXNPL70nPFYliucOXNG
kmSMcWt5TsZL/vjjDyPJbNiwwWX4yJEjTcOGDbOdZ/To0UYSN27cuHHjxu06uB06dChP3cGqH0wc
NWqURowY4byfkZGhU6dOqVSpUnLksKclKSlJFStW1KFDhxQeHu6pqGSxNIuv5SELWWzOQxay5MQY
ozNnzigqKipP83mttJQuXVr+/v46duyYy/Bjx44pMjIy23mCg4MVHBzsMqx48eJurS88PNzrT45M
ZMmeL2WRfCsPWbJHlpz5Uh6yZO9GzxIREZHnebx2IG5QUJDq1aunVatWOYdlZGRo1apVaty4sbdi
AQAAH+XVr4dGjBihfv36qX79+mrYsKEmTZqkc+fOacCAAd6MBQAAfJB/XFxcnLdWXrNmTRUvXlyv
vfaa3njjDUnSjBkzdOuttxboevz9/dWyZUsFBHj/EB6y+H4WybfykIUseeVLechCloLkMCav5xsB
AAB4ntcv4w8AAOAOSgsAALACpQUAAFiB0gIAAKxAaQEAAFagtABX4IQ6APBNvn9Sdh6dOHFCH374
ob755hsdPXpUkhQZGakmTZqof//+KlOmjJcTwtcFBwdr+/btql69urejAFd15MgRTZ48WevWrdOR
I0fk5+enypUrq1u3burfv7/8/f29HREoUNfVdVo2bdqkDh06KCwsTG3btlW5cuUkXfo9o1WrVik5
OVnLli1T/fr1vZz0kkOHDmn06NH68MMPC31d58+f15YtW1SyZEnVqFHDZdyFCxc0Z84c9e3bt9Bz
ZNqzZ482btyoxo0bq1q1avrxxx/11ltvKSUlRQ8++KBat25d6Bku//HNy7311lt68MEHVapUKUnS
hAkTCj1Lds6dO6c5c+Zo//79Kl++vO6//35npsK2detWlShRQrGxsZKk6dOn6/3339dvv/2m6Oho
Pf744+rdu7dHsjzxxBPq1auX7rrrLo+sLzfvvPOOvvvuO919993q3bu3pk+frnHjxikjI0N//vOf
9fLLL3vkIl2bN29W27ZtVbVqVYWGhuqbb75Rnz59lJqaqmXLlqlGjRpaunSpihUrVuhZMqWmpmrh
woXZfmjs2rWrgoKCPJblao4dO6YpU6bopZde8uh6f//9dxUvXlxFixZ1GZ6WlqZvvvlGzZs390iO
kydP6ocfftAdd9yhkiVL6sSJE/rggw+UkpKinj17+vYHtjz9JrSPa9SokRk8eLDJyMjIMi4jI8MM
HjzY3HnnnV5Ilr1t27YZPz+/Ql/P3r17TXR0tHE4HMbPz880b97cHD582Dn+6NGjHsmRacmSJSYo
KMiULFnShISEmCVLlpgyZcqYtm3bmtatWxt/f3+zatWqQs/hcDhM7dq1TcuWLV1uDofDNGjQwLRs
2dK0atWq0HNkql69ujl58qQxxpjffvvNxMTEmIiICNOgQQNTokQJU7ZsWfPLL794JEutWrXMihUr
jDHGTJ061YSGhpqhQ4eayZMnm+HDh5uiRYuaDz74wCNZMp+3N998s3n99dfNkSNHPLLe7Lzyyium
WLFipnv37iYyMtK8/vrrplSpUubVV181Y8eONWXKlDEvvfSSR7I0bdrUxMXFOe9Pnz7dNGrUyBhj
zKlTp0zt2rXN0KFDPZLFGGP27dtnKleubEJCQkyLFi1Mr169TK9evUyLFi1MSEiIqVq1qtm3b5/H
8lyNp/72Zjp8+LBp0KCB8fPzM/7+/uahhx4yZ86ccY735N/gb7/91kRERBiHw2FKlChhNm/ebGJj
Y83NN99sqlSpYkJDQ82WLVs8kiU/rqvSEhISYvbs2ZPj+D179piQkBCP5fn888+veps4caJHnqjd
unUznTp1MgkJCWbfvn2mU6dOJjY21vz666/GGM+XlsaNG5vnn3/eGGPMrFmzTIkSJcxzzz3nHP/s
s8+adu3aFXqOcePGmdjY2CwFKSAgwOzatavQ138lh8Nhjh07Zowx5oEHHjBNmjQxp0+fNsYYc+bM
GdO2bVtz//33eyRLaGioOXjwoDHGmDp16ph//vOfLuNnzJhhatSo4ZEsDofDrFy50gwbNsyULl3a
BAYGmi5dupgvvvjCpKeneyRDpipVqpjPPvvMGHPpjc/f39988sknzvHz5883VatW9UiW0NBQ8/PP
Pzvvp6enm8DAQHP06FFjjDHLly83UVFRHslijDFt27Y1Xbt2NYmJiVnGJSYmmq5du5r27dt7JMv2
7duveps9e7ZH/+b17dvXNGrUyGzatMmsWLHC1KtXz9SvX9+cOnXKGHPpb7DD4fBIlrZt25qBAwea
pKQk8/e//91UqFDBDBw40Dl+wIABplu3bh7Jkh/XVWmJiYkxH330UY7jP/roIxMdHe2xPJmfEB0O
R443T7xwypYta3744Qfn/YyMDDNkyBBTqVIl8/PPP3u8tISHhzs/caWnp5uAgACzdetW5/gdO3aY
cuXKeSTLd999Z2655RbzP//zPyY1NdUY4xulpXLlymb58uUu49evX28qVqzokSylSpUymzdvNsZc
ev5s27bNZfz+/ftNaGioR7Jc/rikpqaa2bNnmw4dOhh/f38TFRVlnnvuOY99gg8NDXWWfWOMCQwM
NDt37nTeP3jwoAkLC/NIlujoaLNu3Trn/cOHDxuHw2GSk5ONMcYcOHDAox/SQkNDzY4dO3Ic/8MP
P3j0OZPT397M4Z78mxcVFWW+/fZb5/0LFy6Yzp07m9q1a5uTJ0969G9wiRIlzO7du40xl15Pfn5+
Ltm2bNlibrrpJo9kyY/r6uyhp556SoMHD9awYcO0aNEiffvtt/r222+1aNEiDRs2TEOGDNHTTz/t
sTzly5fX/PnzlZGRke1t69atHslx/vx5l+/YHQ6HJk+erM6dO6tFixb66aefPJLjcg6HQ5Lk5+en
kJAQRUREOMcVK1ZMiYmJHsnRoEEDbdmyRQkJCapfv7527tzpzOYNmeu+cOGCypcv7zLupptuUkJC
gkdydOzYUZMnT5YktWjRQvPmzXMZP2fOHFWtWtUjWS4XGBioXr16aenSpfrll180aNCgQvmR1ZxE
RkZq9+7dkqR9+/YpPT3deV+Sdu3apbJly3okS7du3TRkyBAtXbpUq1ev1gMPPKAWLVooNDRUkrR3
717ddNNNHskiScWLF9fBgwdzHH/w4EEVL17cI1lKliypqVOn6sCBA1luv/zyi7788kuP5MiUmJio
EiVKOO8HBwdr/vz5iomJUatWrXT8+HGPZUlNTXU+RwIDAxUWFqbSpUs7x5cuXVonT570WJ4883Zr
KmiffvqpadSokQkICHA264CAANOoUSMze/Zsj2bp3LmzefHFF3Mcv23bNo/sEmzQoIH5+OOPsx33
2GOPmeLFi3v0U0etWrXMkiVLnPd37Nhh0tLSnPfXrl1rYmNjPZYn06xZs0y5cuWMn5+f1/a03H77
7aZOnTqmaNGiZt68eS7jv/76a499Avrjjz9MTEyMad68uRkxYoQJDQ01zZo1M4MGDTLNmzc3QUFB
ZvHixR7JcvmeluxkZGRk2StVWF544QVTpkwZM3DgQBMbG2ueffZZU6lSJfPee++ZKVOmmIoVK5on
n3zSI1nOnDljevXq5fxb16RJE5djnpYtW2bmzJnjkSzGGPPiiy+aEiVKmAkTJpjt27ebo0ePmqNH
j5rt27ebCRMmmJIlS5rRo0d7JEv79u3NK6+8kuN4T/3tzXT77bdneT0bY0xaWprp1q2bqVSpksf+
BlerVs3lK/Evv/zSuXfOGGM2btxoKlSo4JEs+XHdlZZMqamp5vDhw+bw4cPO3f6etnbtWpc35yud
PXvWrFmzptBzjB071nTs2DHH8Y8++qhHX8CTJ082X375ZY7jR40aZf7yl794LM/lDh06ZBYuXGjO
nj3r8XXHxcW53JYuXeoy/qmnnjK9e/f2WJ7//Oc/5plnnjE1atQwISEhJigoyERHR5s+ffqYTZs2
eSxHTEyMOXHihMfWdzXp6enmtddeM/fcc48ZO3asycjIMLNmzTIVK1Y0pUqVMv379/f4c+f8+fMu
B3V60+uvv27Kly/v/Pol86uY8uXLm/Hjx3ssx/z588306dNzHH/q1CkTHx/vsTxPP/10jsfzpKWl
mS5dunjsb3BcXJyZNWtWjuOfe+458+c//9kjWfLjujrlGQDgfQcOHHA55Tnz1Pkb1cWLF5WcnKzw
8PAcx//xxx+Kjo72cLKskpOT5e/vr+DgYG9HydZ1dUwLAMD7YmNj1bhxYzVu3NhZWA4dOqSHH37Y
y8ku8XSWgICAHAuLdOkigWPGjPFYnqs5efKkHn30UW/HyBF7WgAAhW779u2qW7eu0tPTvR3Fp7JI
vpXHl7Jk57q7jD8AwPMWLVp01fG//PKLh5L4VhbJt/L4Upb8YE8LAOCa+fn5yeFwXPUHRx0Oh0c+
wftSFl/L40tZ8oNjWgAA18xXrkvla1l8LY8vZckPSgsA4JrVq1dPW7ZsyXF8bp/ur9csvpbHl7Lk
B8e0AACu2ciRI3Xu3Lkcx1etWlWrV6++4bL4Wh5fypIfHNMCAACswNdDAADACpQWAABgBUoLAACw
AqUFAABYgdICAACsQGkBkG8JCQl69NFHValSJQUHBysyMlIdOnTQ+vXrC2T5MTExmjRpUoEsC4D9
uE4LgHzr3r27UlNT9dFHH6ly5co6duyYVq1apZMnT3o7movU1FQFBQV5OwaAa8SeFgD5cvr0af37
3//W+PHj1apVK0VHR6thw4YaNWqUunTp4pxm4MCBKlOmjMLDw9W6dWtt377dZTlffPGFGjRooJCQ
EJUuXVr33nuvJKlly5b69ddf9eSTT8rhcMjhcDjn+eyzz3TbbbcpODhYMTExevPNN12WGRMTo1de
eUV9+/ZVeHi4Bg8erNTUVD3++OMqX768QkJCFB0drXHjxhXyowSgIFFaAORL0aJFVbRoUS1cuFAp
KSnZTtOzZ08dP35cS5Ys0ZYtW1S3bl21adNGp06dkiQtXrxY9957r+6++259//33Wr16te68805J
0vz581WhQgW9/PLLOnLkiI4cOSJJ2rJli3r16qXevXtrx44diouL04svvqj4+HiXdb/xxhu64447
9P333+vFF1/UP/7xDy1atEhz5szR3r17NWPGDMXExBTa4wOg4HFFXAD59tlnn2nQoEE6f/686tat
qxYtWqh3796qVauW1q1bp06dOun48eMKDg52zlO1alU9/fTTGjx4sJo0aaLKlSvrk08+yXb5MTEx
Gj58uIYPH+4c9sADDyghIUHLly93Dnv66ae1ePFi7dq1yzlfnTp1tGDBAuc0Q4cO1a5du7Ry5UqX
vTYA7MGeFgD51r17dx0+fFiLFi3Sn/70J61Zs0Z169ZVfHy8tm/frrNnz6pUqVLOvTJFixbVgQMH
9PPPP0uStm3bpjZt2uRpnXv27FHTpk1dhjVt2lT79u1Tenq6c1j9+vVdpunfv7+2bdumW2+9VUOH
DnUpPQDswIG4AK5JSEiI2rVrp3bt2unFF1/UwIEDNXr0aP31r39V+fLltWbNmizzFC9eXJIUGhpa
aLmKFCnicr9u3bo6cOCAlixZopUrV6pXr15q27at5s2bV2gZABQs9rQAKFA1atTQuXPnVLduXR09
elQBAQGqWrWqy6106dKSpFq1amnVqlU5LisoKMhl74kkVa9ePcsp1evXr9ctt9wif3//q2YLDw/X
fffdp6lTp2r27Nn67LPPnMfXAPB9/nFxcXHeDgHAPidPntQ999zjLArJyclauXKlXnjhBXXu3FnD
hw/XypUr9fHHH6ty5cry9/fX7t279f777ysiIkJRUVGKiYnRyJEjlZGRocjISB09elTx8fFq1qyZ
pEtnFh0+fFjNmzdXamqqwsLCFBsbq1GjRsnPz0/ly5fXl19+qdGjR+u1115T7dq1JUmTJk3SnXfe
6TyoV5ImTJiggwcPKjAwUKdOndLUqVN15MgRPf/88xzjAtjCAEA+XLhwwTz77LOmbt26JiIiwoSF
hZlbb73VvPDCCyY5OdkYY0xSUpJ54oknTFRUlAkMDDQVK1Y0DzzwgPntt9+cy/nss89M7dq1TVBQ
kCldurT585//7Bz3zTffmFq1apng4GBz+Z+refPmmRo1apjAwEBTqVIl8/e//90lW3R0tJk4caLL
sH/+85+mdu3apkiRIiY8PNy0adPGbN26tTAeGgCFhLOHAACAFTimBQAAWIHSAgAArEBpAQAAVqC0
AAAAK1BaAACAFSgtAADACpQWAABgBUoLAACwAqUFAABYgdICAACsQGkBAABW+D+49GCRSX7gkQAA
AABJRU5ErkJggg==
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The RCA of Mexico has increased in almost all sectors. 'Rubber and Plastics, 'Basic Metals and Fabricated Metal', 'Machinery, Nec', 'Electrical and Optical Equipment', 'Transport Equipment' and 'Manufacturing, Nec; Recycling'. The increases in the last three sectors are also the biggest ones, and go ten koste of the decrease of RCAs in Canada and US.</p>
<p>The sectors that lose their RCA relatively to 1995 are 'Textiles and Textile Products', 'Leather, Leather and Footwear' and especially 'Wood and Products of Wood and Cork'. The latter is now traded relatively more traded by Canada with the US, and that is possibly the reason for such a big loss in that sector.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[25]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Histogram of Revealed Comparative Advantage of the Mexico</span>

<span class="n">rcaus</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_excel</span><span class="p">(</span><span class="sa">r</span><span class="s1">&#39;C:\Users\Jesse\Downloads\PythonFinal\RCA.xlsx&#39;</span><span class="p">,</span> <span class="s2">&quot;RCA_MEX&quot;</span><span class="p">)</span>
<span class="n">FORMAT</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Sector&#39;</span><span class="p">,</span><span class="s1">&#39;1995MEX&#39;</span><span class="p">,</span><span class="s1">&#39;2011MEX&#39;</span><span class="p">]</span>
<span class="n">rcaus_selected</span> <span class="o">=</span> <span class="n">rcaus</span><span class="p">[</span><span class="n">FORMAT</span><span class="p">]</span>
<span class="n">rcaus</span>

<span class="n">rcaus</span><span class="p">[</span><span class="s2">&quot;1995MEX&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span> <span class="o">=</span> <span class="s2">&quot;bar&quot;</span><span class="p">,</span> <span class="n">width</span> <span class="o">=</span> <span class="mf">0.6</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;#FF3333&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.5</span><span class="p">,</span> <span class="n">align</span><span class="o">=</span><span class="s1">&#39;center&#39;</span><span class="p">)</span>
<span class="n">rcaus</span><span class="p">[</span><span class="s2">&quot;2011MEX&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span> <span class="o">=</span> <span class="s2">&quot;bar&quot;</span><span class="p">,</span> <span class="n">width</span> <span class="o">=</span> <span class="mf">0.6</span><span class="p">,</span> <span class="n">color</span> <span class="o">=</span> <span class="s1">&#39;#00CC00&#39;</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.4</span><span class="p">,</span> <span class="n">align</span><span class="o">=</span><span class="s1">&#39;edge&#39;</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;RCA Mexico &#39;95-&#39;11&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Sectors&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;RCA&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAi0AAAHKCAYAAADPQHvVAAAABHNCSVQICAgIfAhkiAAAAAlwSFlz
AAAPYQAAD2EBqD+naQAAIABJREFUeJzt3X98zXXj//Hn2a+zDWNsGGYjRZTk5+VHQ4xUSoqvVhfr
B1fphx9XKq5kKtGPSz+uuuRy1VZCJLpUFzVKLqSkCEkUUYyN2jC2Y3t9/6idj9M2zpntnPdbj/vt
dm435/1+vd/v5zk7tufev+YwxhgBAABYXFCgAwAAAHiD0gIAAGyB0gIAAGyB0gIAAGyB0gIAAGyB
0gIAAGyB0gIAAGyB0gIAAGyB0gIAAGyB0gLAEnbv3i2Hw6GMjIxARwFgUZQWoIplZGTI4XC4HyEh
IWrYsKFSU1P1008/lbvc4sWL1a9fP8XExCgsLEwNGjTQ4MGD9eGHH5Y5/r///a8cDocaNGig4uJi
r/OlpqbK4XAoKipKx48fLzV/x44d7uxPP/201+u1i7KK0oYNG3TFFVcoKipKNWrUUJ8+fbRx48ZS
y5a8d79/tGjRwqttr1y5Ug6HQ7t373ZP2759u8aMGaMuXbooPDy81PxTzZ8/XzfffLPOP/98ORwO
9ejRw8tXDdhTSKADAH8UjzzyiJo0aaITJ05o3bp1ysjI0OrVq7VlyxaFh4e7xxljdOuttyojI0OX
Xnqpxo4dq/r162v//v1avHixevXqpTVr1qhLly4e658zZ44SExO1e/duffjhh+rdu7fX2UJCQpSf
n6933nlHgwcPLrXe8PBwnThx4uzegDNISEjQ8ePHFRoaWqXbOZMvvvhC3bp1U3x8vCZNmqTi4mL9
85//VPfu3fXZZ5+pefPmHuOdTqf+/e9/e0yrWbNmhbf/ySef6Pnnn1fLli114YUXllmWSsyYMUMb
NmxQhw4ddOjQoQpvE7ANA6BKpaenG0lm/fr1HtMfeOABI8nMnz/fY/pTTz1lJJnRo0eb4uLiUut7
7bXXzKeffuox7ejRo6ZatWrm+eefN5deeqlJTU31Ot+wYcNMtWrVTJ8+fcyAAQNKzT///PPN9ddf
bySZp556yuv12oUkk56e7n5+5ZVXmujoaJOTk+Oetm/fPlO9enUzcOBAj2VL3ruK+uijj4wks2vX
Lve0Q4cOmby8PGPM/30WTp1/qj179piioiJjjDGtWrUy3bt3r3AWwA44PAQEyGWXXSZJ+u6779zT
jh8/rqlTp6pFixZ6+umn5XA4Si335z//WR07dvSYtnjxYh0/flyDBg3SkCFDtGjRIp/3jKSkpGjp
0qX65Zdf3NPWr1+vHTt2KCUlpcxlfvnlF40ePVrx8fFyOp1q1qyZnnjiCY/DU5MmTVJQUJBWrFjh
seyIESMUFhamTZs2SSr/nJZvvvlGgwcPVmxsrCIiItS8eXP97W9/8xjz5Zdfql+/foqKilL16tXV
q1cvrVu3zqfXX+J///ufevfurTp16rinxcXFqXv37nr33Xd19OjRUssUFRUpLy+vQtv7vdq1a6tG
jRpejY2Pj1dQEN/G8cfBpx0IkJLzFKKjo93TVq9ercOHDyslJUXBwcFer2vOnDnq2bOn6tevryFD
hujIkSN65513fMozcOBAORwOLVq0yD1t7ty5atGihdq2bVtqfH5+vrp3767XX39dQ4cO1fPPP6+u
Xbtq/PjxGjt2rHvcQw89pDZt2ui2227TkSNHJEnvv/++Zs2apYcffliXXHJJuZm++uorderUSR9+
+KGGDx+u5557TgMGDPB4bVu3btVll12mTZs26f7779fEiRO1a9cu9ejRQ59++qlP74EkFRQUKCIi
otT0yMhIFRYWasuWLaXeh6ioKNWsWVO1a9fWXXfdVWaxAVAJAr2rBzjXlRweWr58ucnOzjZ79+41
CxcuNLGxscbpdJq9e/e6xz733HNGklm8eLHX6z9w4IAJCQkxs2bNck/r0qWLufbaa71a/tRDHDfc
cIPp1auXMcaYoqIiU79+fTN58mSza9euUoeHHn30UVOtWjXz7bffeqzvwQcfNMHBwWbPnj3uaZs3
bzZhYWHm9ttvNz///LNp2LChad++vXG5XO4xJds49VBNUlKSqVGjhvnhhx88tnHqYbMBAwaYsLAw
891337mn7du3z9SoUcMkJSV59R6c6uKLLzYXXHCBOXnypHtaQUGBady4sZFkFi5c6PFaH3jgATN/
/nwzb948M2zYMCPJdO3a1eO1VdSZDg+disND+CNgTwvgJ71791ZsbKzi4+N1ww03qFq1alqyZIka
NWrkHlNyiMHbwwOS9MYbbygoKEjXX3+9e9qNN96opUuX6ueff/YpY0pKilauXKmsrCx9+OGHysrK
KvfQ0JtvvqnLLrtM0dHRysnJcT969+6toqIirVq1yj32oosu0uTJk/Xvf/9bffv2VU5Ojl599VWF
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
KC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWQgIdAAAAf8nIyZAJMZW2vhGxIypt
XTgz9rQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABb
oLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQAAABboLQA
AABboLQAAABboLQAAABboLQAAABbCGhpSUxMlMPhKPW46667AhkLAABYUEggN75+/XoVFRW5n2/Z
skXJyckaNGhQAFMBAAArCmhpiY2N9Xg+bdo0nXfeeerevXuZ4wsKClRQUOB+npeXJ0lyuVxyuVxl
LlMyvbz5/kSWslkpi2StPGQpG1nKZ6U8VsziKHJUyXorsoyV3hd/Z6no9hzGGFPJWSqksLBQDRo0
0NixYzVhwoQyx6SlpWny5Mmlps+dO1eRkZFVHREAAFSC/Px8paSkKDc3V1FRUV4vZ5nSsmDBAqWk
pGjPnj1q0KBBmWPK2tMSHx+vnJyccl+0y+VSZmamkpOTFRoaWiXZvUUW62exWh6ykMXOeayYJbtd
tkxw5f3YS41JrXAWK70v/s6Sl5enmJgYn0tLQA8Pnerll19Wv379yi0skuR0OuV0OktNDw0NPeOb
7c0YfyFL2ayURbJWHrKUjSzls1IeK2UxwUYmpPJKy9m8Liu9L/7OUtFtWaK0/PDDD1q+fLkWLVoU
6CgAAMCiLHGflvT0dNWtW1dXXXVVoKMAAACLCnhpKS4uVnp6uoYNG6aQEEvs+AEAABYU8NKyfPly
7dmzR7feemugowAAAAsL+K6NPn36yCIXMAEAAAsL+J4WAAAAb1BaAACALVBaAACALVBaAACALVBa
AACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACA
LVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBaAACALVBa
AACALVBaAACALYQEOgAAAH9EGTkZMiGm0tY3InZEpa3LqtjTAgAAbIHSAgAAbIHSAgAAbIHSAgAA
bIHSAgAAbIHSAgAAbIHSAgAAbIHSAgAAbIHSAgAAbCHgpeWnn37SzTffrDp16igiIkIXX3yxPv/8
80DHAgAAFhPQ2/j//PPP6tq1q3r27KmlS5cqNjZWO3bsUHR0dCBjAQAACwpoaXniiScUHx+v9PR0
97QmTZoEMBEAALCqgJaWJUuWqG/fvho0aJA+/vhjNWzYUCNHjtTw4cPLHF9QUKCCggL387y8PEmS
y+WSy+Uqc5mS6eXN9yeylM1KWSRr5SFL2chSPivlsWIWR5GjStZr9yz+/hpVdHsOY0zl/YlJH4WH
h0uSxo4dq0GDBmn9+vUaNWqUXnrpJQ0bNqzU+LS0NE2ePLnU9Llz5yoyMrLK8wIAgLOXn5+vlJQU
5ebmKioqyuvlAlpawsLC1L59e61du9Y97d5779X69ev1ySeflBpf1p6W+Ph45eTklPuiXS6XMjMz
lZycrNDQ0Mp/ET4gi/WzWC0PWchi5zxWzJLdLlsmuPJ+7KXGpJ4TWfz9NcrLy1NMTIzPpSWgh4fi
4uLUsmVLj2kXXnih3nrrrTLHO51OOZ3OUtNDQ0PP+GZ7M8ZfyFI2K2WRrJWHLGUjS/mslMdKWUyw
kQmpvKJwNq/LSln8/TWq6LYCeslz165dtX37do9p3377rRISEgKUCAAAWFVAS8uYMWO0bt06Pf74
49q5c6fmzp2rf/3rX7rrrrsCGQsAAFhQQEtLhw4dtHjxYs2bN08XXXSRHn30UT377LO66aabAhkL
AABYUEDPaZGkq6++WldffXWgYwAAAIsL+G38AQAAvEFpAQAAtkBpAQAAtkBpAQAAtkBpAQAAthDw
q4cAAKiwmTO9G+dwSPXqSWvXSDp5+rFJSWcdC1WDPS0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0A
AMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAW
KC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0A
AMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWKC0AAMAWAlpa0tLS5HA4PB4tWrQIZCQA
AGBRIYEO0KpVKy1fvtz9PCQk4JEAAIAFBbwhhISEqH79+l6NLSgoUEFBgft5Xl6eJMnlcsnlcpW5
TMn08ub7E1nKZqUskrXykKVsZCmflfL4JYvD4V2W38Y5vPmxd9K7dUoVe20lyziKvN9OVWfx9+el
ottzGGNMJWfxWlpamp566inVrFlT4eHh6ty5s6ZOnarGjRuXO37y5Mmlps+dO1eRkZFVHRcAAFSC
/Px8paSkKDc3V1FRUV4vF9DSsnTpUh09elTNmzfX/v37NXnyZP3000/asmWLatSoUWp8WXta4uPj
lZOTU+6LdrlcyszMVHJyskJDQ6vstXiDLNbPYrU8ZCGLnfP4JUt6undZHA5l1q2r7JPvyOjk6Qd3
6er15lNjUr0e687y2/uS3S5bJrjyfgSfTRZ/f17y8vIUExPjc2kJ6OGhfv36uf/dunVrderUSQkJ
CVqwYIFuu+22UuOdTqecTmep6aGhoWd8s70Z4y9kKZuVskjWykOWspGlfFbKU6VZfPy92+jkmUtL
iPfrPJvXZYKNjA/bqsos/v68VHRblrrkuVatWrrgggu0c+fOQEcBAAAWY6nScvToUe3cuVNxcXGB
jgIAACwmoKXlvvvu08cff6zdu3dr7dq1uu666xQSEqIbb7wxkLEAAIAFBfSclh9//FE33nijDh06
pNjYWHXr1k3r1q1TbGxsIGMBAAALCmhpeeONNwK5eQAAYCOWOqcFAACgPJQWAABgC5QWAABgC5QW
AABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABg
C5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QW
AABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5QWAABgC5VaWrZt26b77ruv
MlcJAAAgqRJKy7Fjx/Tyyy+rS5cuatWqlZYtW1YZuQAAADxUuLSsWbNGt956q+rVq6cRI0aoS5cu
+vrrr7Vly5bKzAcAACDJx9Jy8OBBPfnkk2rRooVuuOEG1apVSytXrlRQUJBuvfVWtWjRoqpyAgCA
P7gQXwYnJCTohhtu0HPPPafk5GQFBXEeLwAA8A+fWkdCQoJWr16tVatW6dtvv63UINOmTZPD4dDo
0aMrdb0AAODc4FNp+eabb/T6669r//796tChg9q1a6dnnnlGkuRwOCocYv369Zo5c6Zat25d4XUA
AIBzm8/Hd7p27apXXnlF+/fv1x133KE333xTRUVFGjlypGbNmqXs7Gyf1nf06FHddNNNmjVrlqKj
o32NAwAA/iB8OqflVNWrV9fw4cM1fPhwbdu2TS+//LIeeughjRw5Ui6Xy+v13HXXXbrqqqvUu3dv
PfbYY6cdW1BQoIKCAvfzvLw8SZLL5Sp3myXTfclUVchSNitlkayVhyxlI0v5rJTHL1m83Mvv+m2c
w5sfeye9P3JQkddWsoyjqOJHKCo7i78/LxXdnsMYYyorxMmTJ7VkyRINHDjQq/FvvPGGpkyZovXr
1ys8PFw9evRQmzZt9Oyzz5Y5Pi0tTZMnTy41fe7cuYqMjDyr7AAAwD/y8/OVkpKi3NxcRUVFeb2c
T3ta9u3bp+nTp+vhhx8utZHc3Fw99thjXp9Iu3fvXo0aNUqZmZkKDw/3apnx48dr7Nix7ud5eXmK
j49Xnz59yn3RLpdLmZmZSk5OVmhoqFfbqSpksX4Wq+UhC1nsnMcvWdLTvcvicCizbl1ln3xHRidP
P7hLV683nxqT6vVYd5bf3pfsdtkywZW23+Cssvj781JypMRXPpWW6dOnKy8vr8yCULNmTR05ckRT
p07VCy+8cMZ1bdiwQQcPHlTbtm3d04qKirRq1Sq98MILKigoUHBwsMcyTqdTTqez1LpCQ0PP+GZ7
M8ZfyFI2K2WRrJWHLGUjS/mslKdKs/h4sMDo5JlLS4j36zyb12WCjYwP26rKLP7+vFR0Wz6VlmXL
lumll14qd/7QoUM1fPhwr9bVq1cvbd682WPaLbfcohYtWuiBBx4oVVgAAMAfm0+lZdeuXWrcuHG5
8xs1aqTdu3d7ta4aNWrooosu8phWrVo11alTp9R0AAAAny55joiIOG0p2b17tyIiIs42EwAAQCk+
7Wnp1KmTZs+eraSkpDLnv/baa+rYsWOFw6xcubLCywIAgHObT6XlvvvuU3JysmrWrKlx48apXr16
kqQDBw7oySefVEZGhj744IMqCQoAAP7YfCotPXv21IsvvqhRo0bpmWeeUVRUlBwOh3JzcxUaGqp/
/OMfuvzyy6sqKwAAqAIZORmVeiXTiNgRlbauU/l8R9y//OUvuuqqq/Tmm29q586dMsboggsu0A03
3KBGjRrp+PHjnNcCAAAqXYVu49+oUSONGTPGY1pBQYGmT5+uJ598UllZWZUSDgAAoIRPVw8VFBRo
/Pjxat++vbp06aK3335bkpSenq4mTZromWeeKVVmAAAAKoNPe1oefvhhzZw5U8nJyVqzZo0GDRqk
W265RevWrdP06dM1aNAgbgoHAACqhE+l5c0339Rrr72ma665Rlu2bFHr1q118uRJbdq0SQ4v/9Im
AABARfh0eOjHH39Uu3btJEkXXXSRnE6nxowZQ2EBAABVzqfSUlRUpLCwMPfzkJAQVa9evdJDAQAA
/J5Ph4eMMUpNTXX/peUTJ07ojjvuULVq1TzGLVq0qPISAgAAyMfSMmzYMI/nN998c6WGAQAAKI9P
pSU9Pb2qcgAAAJyWT+e0AAAABAqlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKl
BQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA
2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AKlBQAA2EJAS8uMGTPUunVrRUVF
KSoqSp07d9bSpUsDGQkAAFhUQEtLo0aNNG3aNG3YsEGff/65Lr/8cl177bXaunVrIGMBAAALCgnk
xvv37+/xfMqUKZoxY4bWrVunVq1alRpfUFCggoIC9/O8vDxJksvlksvlKnMbJdPLm+9PZCmblbJI
1spDlrKRpXxWyuOXLA6Hd1l+G+fw5sfeSe/WKVXstZUs4yjyfjvnWpaKfiYcxhhToSUrWVFRkd58
800NGzZMX375pVq2bFlqTFpamiZPnlxq+ty5cxUZGemPmAAA4Czl5+crJSVFubm5ioqK8nq5gJeW
zZs3q3Pnzjpx4oSqV6+uuXPn6sorryxzbFl7WuLj45WTk1Pui3a5XMrMzFRycrJCQ0Or5DV4iyzW
z2K1PGQhi53z+CVLerp3WRwOZdatq+yT78jo5OkHd+nq9eZTY1K9HuvO8tv7kt0uWya48n4E2ylL
Xl6eYmJifC4tAT08JEnNmzfXxo0blZubq4ULF2rYsGH6+OOPy9zT4nQ65XQ6S00PDQ09438Ib8b4
C1nKZqUskrXykKVsZCmflfJUaRYff+82Onnm0hLi/TrP5nWZYCPjw7bOpSwVzRrw0hIWFqZmzZpJ
ktq1a6f169frueee08yZMwOcDAAAWInl7tNSXFzscQgIAABACvCelvHjx6tfv35q3Lixjhw5orlz
52rlypV6//33AxkLAABYUEBLy8GDBzV06FDt379fNWvWVOvWrfX+++8rOTk5kLEAAIAFBbS0vPzy
y4HcPAAAsBHLndMCAABQFkoLAACwBUoLAACwBUoLAACwBUoLAACwBUoLAACwBUoLAACwBUoLAACw
BUoLAAA8h8fHAAAbxUlEQVSwBUoLAACwBUoLAACwBUoLAACwBUoLAACwBUoLAACwBUoLAACwBUoL
AACwBUoLAACwBUoLAACwBUoLAACwhZBABzhnzJx55jEOh1SvnpSeLhlz5vF/+cvZ5wIA4BzBnhYA
AGALlBYAAGALlBYAAGALnNNyLuL8GgDAOYg9LQAAwBYoLQAAwBYoLQAAwBYoLQAAwBYoLQAAwBYo
LQAAwBYoLQAAwBYoLQAAwBa4uRwAnIMycjJkQry4caSXRsSOqLR1ARXFnhYAAGALlBYAAGALAS0t
U6dOVYcOHVSjRg3VrVtXAwYM0Pbt2wMZCQAAWFRAS8vHH3+su+66S+vWrVNmZqZcLpf69OmjY8eO
BTIWAACwoICeiLts2TKP5xkZGapbt642bNigpKSkAKUCAABWZKmrh3JzcyVJtWvXLnN+QUGBCgoK
3M/z8vIkSS6XSy6Xq8xlSqaXN7/SOBxnHOL6bYzLi7G/DqxgZitl8WrVfvoaeclKechSNrKUrySH
o8jL/9s+rrciy1Tpe+Pl97CS73UOb37snfT+vTub98VKXyN/Z6noZ8JhjKm8a+LOQnFxsa655hr9
8ssvWr16dZlj0tLSNHny5FLT586dq8jIyKqOCAAAKkF+fr5SUlKUm5urqKgor5ezTGm58847tXTp
Uq1evVqNGjUqc0xZe1ri4+OVk5NT7ot2uVzKzMxUcnKyQkNDqyS7JCk9/YxDXA6HMuvWVfLBgwr1
5m2/5Rb7Z/GC375GNsxDFrJUNE92u2yZ4Mr79p4ak1rhLFX63njx/U76v+952SffkdHJ0w/u0tXr
zZ/N+2Klr5G/s+Tl5SkmJsbn0mKJw0N333233n33Xa1atarcwiJJTqdTTqez1PTQ0NAz/ofwZsxZ
8aH7hRrjXVGoaF4rZfFBlX+NfGSlPGQpG1nKZ4JNpd5c7mxeW5W+Nz7+3m108sylxYf37Wxel5W+
Rv7OUtGsAS0txhjdc889Wrx4sVauXKkmTZoEMg4AALCwgJaWu+66S3PnztV//vMf1ahRQ1lZWZKk
mjVrKiIiIpDR/jAy6qw9828dkpTt3Ula3OobAFBVAnqflhkzZig3N1c9evRQXFyc+zF//vxAxgIA
ABYU8MNDAAAA3uBvDwEAAFugtAAAAFuwxCXPAFARGTkZlXqZJieSA9bGnhYAAGALlBYAAGALlBYA
AGALnNMSANzQDQAA37GnBQAA2AKlBQAA2AKlBQAA2AKlBQAA2AIn4gKAHcyc6d04h0OqV09au0Y6
0wn/SUlnHQvwJ/a0AAAAW6C0AAAAW6C0AAAAW+CcFgBAleIPW6KysKcFAADYAntaAFiLN1fJ+HKF
jMRVMsA5gj0tAADAFigtAADAFigtAADAFigtAADAFigtAADAFigtAADAFigtAADAFrhPC/BH5+tf
D05Pl4wXdzf9y1/OLhcA/A57WgAAgC1QWgAAgC1QWgAAgC1wTgsAn2TUWSvjzd/7yXZ4tT7+Yi8A
b7GnBQAA2AKlBQAA2AKlBQAA2ALntAAAUFm8ue9RyT2P1q6RvDk/LCnprGOdK9jTAgAAbIHSAgAA
bCGgpWXVqlXq37+/GjRoIIfDobfffjuQcQAAgIUFtLQcO3ZMl1xyiV588cVAxgAAADYQ0BNx+/Xr
p379+nk9vqCgQAUFBe7neXl5kiSXyyWXy1XmMiXTy5tfaRxnvpGW67cxDm/f9pPe3Zyr1GuzUhYf
lqnyr5GXrJTHL1m8+LxIf9DPb3q6d1nq1pUrI8O7PyR5yy1eZSmlKr5OXr4v0tn933YUeb8dn7NY
7X2x0ufXh2Wq9GtUgfnlcRjjzf+yqudwOLR48WINGDCg3DFpaWmaPHlyqelz585VZGRkVcYDAACV
JD8/XykpKcrNzVVUVJTXy9mqtJS1pyU+Pl45OTnlvmiXy6XMzEwlJycrNDS00nO7efkbWWbduso+
+Y53t0Hv0tWrTafGpFo3ixf89jWyYR6/ZPHi8yL9QT+/PmRJPnhQoVW5p6Uqvk5evi/S2f3fzm6X
LRNceT9qPLJY7X2x0ufXC375GpUhLy9PMTExPpcWW92nxel0yul0lpoeGhp6xm/o3ow5Kz50P6OT
3n1QQ7xbZ6nXZaUsPqjyr5GPrJSnSrP4+HvLH+rz60OWUGO8Ky0V/TpWxdfJy/dFOrv/2ybYyPiw
LZ+yWO19sdLn1wdV+jWqwPzycMkzAACwBUoLAACwhYAeHjp69Kh27tzpfr5r1y5t3LhRtWvXVuPG
jSt1Wxk5GZW662tE7IhKWxcAADizgJaWzz//XD179nQ/Hzt2rCRp2LBhysjICFAqAABgRQEtLT16
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
Yw4fPmzatGlj7r33Xr9kMcaYHTt2mKZNm5rw8HDTvXt3M3jwYDN48GDTvXt3Ex4ebpo1a2Z27Njh
tzyn46/vvSX27dtnOnToYIKCgkxwcLD585//bI4cOeKe78/vwZ9++qmpWbOmcTgcJjo62nz++eem
SZMm5vzzzzfnnXeeiYiIMBs2bPBLloo4p0pLeHi42bZtW7nzt23bZsLDw/2W5z//+c9pH88884xf
PqgDBgwwV111lcnOzjY7duwwV111lWnSpIn54YcfjDH+Ly2dO3c2f/vb34wxxsybN89ER0ebCRMm
uOc/+OCDJjk5ucpzTJ061TRp0qRUQQoJCTFbt26t8u3/nsPhMAcOHDDGGHPTTTeZLl26mF9++cUY
Y8yRI0dM7969zY033uiXLBEREWb37t3GGGMuvfRS869//ctj/pw5c0zLli39ksXhcJjly5ebUaNG
mZiYGBMaGmquueYa884775iioiK/ZChx3nnnmbfeessY8+sPvuDgYPP666+75y9atMg0a9bML1ki
IiLMd999535eVFRkQkNDTVZWljHGmA8++MA0aNDAL1mMMaZ3797m2muvNbm5uaXm5ebmmmuvvdb0
6dPHL1k2bdp02sf8+fP9+j1v6NChplOnTmb9+vUmMzPTtGvXzrRv394cPnzYGPPr92CHw+GXLL17
9za33367ycvLM0899ZRp1KiRuf32293zb7nlFjNgwAC/ZKmIc6q0JCYmmldffbXc+a+++qpJSEjw
W56S3xAdDke5D3/8x6lbt6756quv3M+Li4vNHXfcYRo3bmy+++47v5eWqKgo929cRUVFJiQkxHzx
xRfu+Zs3bzb16tXzS5bPPvvMXHDBBeavf/2rKSwsNMZYo7Q0bdrUfPDBBx7z16xZY+Lj4/2SpU6d
Oubzzz83xvz6+dm4caPH/J07d5qIiAi/ZDn1fSksLDTz5883ffv2NcHBwaZBgwZmwoQJfvsNPiIi
wl32jTEmNDTUbNmyxf189+7dJjIy0i9ZEhISzOrVq93P9+3bZxwOh8nPzzfGGLNr1y6//pIWERFh
Nm/eXO78r776yq+fmfK+95ZM9+f3vAYNGphPP/3U/fzEiROmf//+pk2bNubQoUN+/R4cHR1tvv76
a2PMr/+fgoKCPLJt2LDBNGzY0C9ZKuKcunrovvvu04gRIzRq1CgtWbJEn376qT799FMtWbJEo0aN
0h133KH777/fb3ni4uK0aNEiFRcXl/n44osv/JLj+PHjHsfYHQ6HZsyYof79+6t79+769ttv/ZLj
VA6HQ5IUFBSk8PBw1axZ0z2vRo0ays3N9UuODh06aMOGDcrOzlb79u21ZcsWd7ZAKNn2iRMnFBcX
5zGvYcOGys7O9kuOfv36acaMGZKk7t27a+HChR7zFyxYoGbNmvkly6lCQ0M1ePBgLVu2TN9//72G
Dx9eJX9ktTz169fX119/LUnasWOHioqK3M8laevWrapbt65fsgwYMEB33HGHli1bpo8++kg33XST
unfvroiICEnS9u3b1bBhQ79kkaRatWpp9+7d5c7fvXu3atWq5ZcstWvX1qxZs7Rr165Sj++//17v
vvuuX3KUyM3NVXR0tPu50+nUokWLlJiYqJ49e+rgwYN+y1JYWOj+jISGhioyMlIxMTHu+TExMTp0
6JDf8vgs0K2psr3xxhumU6dOJiQkxN2sQ0JCTKdOncz8+fP9mqV///5m4sSJ5c7fuHGjX3YJdujQ
wbz22mtlzrvrrrtMrVq1/PpbR+vWrc3SpUvdzzdv3mxcLpf7+apVq0yTJk38lqfEvHnzTL169UxQ
UFDA9rRcfPHF5tJLLzXVq1c3Cxcu9Jj/8ccf++03oJ9++skkJiaapKQkM3bsWBMREWG6detmhg8f
bpKSkkxYWJh57733/JLl1D0tZSkuLi61V6qqPPTQQyY2NtbcfvvtpkmTJubBBx80jRs3Nv/85z/N
zJkzTXx8vBkzZoxfshw5csQMHjzY/b2uS5cuHuc8vf/++2bBggV+yWKMMRMnTjTR0dFm+vTpZtOm
TSYrK8tkZWWZTZs2menTp5vatWubSZMm+SVLnz59zKOPPlrufH997y1x8cUXl/r/bIwxLpfLDBgw
wDRu3Nhv34NbtGjhcUj83Xffde+dM8aYdevWmUaNGvklS0Wcc6WlRGFhodm3b5/Zt2+fe7e/v61a
tcrjh/PvHT161KxcubLKczz++OOmX79+5c6/8847/fofeMaMGebdd98td/748ePNbbfd5rc8p9q7
d695++23zdGjR/2+7bS0NI/HsmXLPObfd999ZsiQIX7L8/PPP5sHHnjAtGzZ0oSHh5uwsDCTkJBg
UlJSzPr16/2WIzEx0eTk5Phte6dTVFRkpkyZYq6++mrz+OOPm+LiYjNv3jwTHx9v6tSpY1JTU/3+
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
m0jwd4sAAAAASUVORK5CYII=
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Based on the RCA analysis, we can draw the same conclusions as based on the analysis of the input-outputtables. Namely, that there is indeed a very strong regional North-American value chain, centralised around the US. The trade among the three countries was already large before NAFTA, so it did not play an enourmous role. However, after the NAFTA agreement, the three countries became more specialised in their comparative advantages. These are in the same sectors for the US and Canada and are situated in different sectors for Mexico. Important to keep in mind, the US keeps trading more with Canada and Mexico, than the latter two countries with each other.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id='Conclusion'></a></p>
<h2 id="5-Conclusion">5 Conclusion<a class="anchor-link" href="#5-Conclusion">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>"Nafta talks are at a 'much better' point, says Mexico" - that is a BBC News headline on January 29, 2018. The latest talks between three countries aim to renegotiate the Nafta agreement, due to the threats of President Donald Trump to withdraw from the agreement. See as an example for that a very short fragment from the Fox News on January 15, 2018. Because of these renewed talks we aimed to take a closer look at this agreement from an economical point of view.</p>
<p>ADD SOCIO ECONOMIC ACCOUNTS
AND THAT YOU COULD HAVE DONE A COMPARISON WITH BRAZIL</p>
<p>Also add that with nowadays the talks being renegotiated, check out the rest of it….</p>
<p>Important to notice, we also take Brazil and China into our account, because these countries have comparable wages and educational degrees to Mexico. Both of these countries are not part of the NAFTA agreement and additionally have less optimal geographic position.</p>
<p>Brazil, the country that we will use to make a comparison analysis, is not a NAFTA partner. Further, after a historically tense relationship, it only started trading with US after 2009, when a bilateral trade agreement between the two countries came into place.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[26]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">IPython.display</span> <span class="k">import</span> <span class="n">YouTubeVideo</span>

<span class="n">YouTubeVideo</span><span class="p">(</span><span class="s1">&#39;RJrxjXq1cDI&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[26]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">

        <iframe
            width="400"
            height="300"
            src="https://www.youtube.com/embed/RJrxjXq1cDI"
            frameborder="0"
            allowfullscreen
        ></iframe>
        
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a href='#Boven'>Click here to go back to the top</a></p>

</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>
