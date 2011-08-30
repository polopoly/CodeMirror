This is an old fork of CodeMirror that is used in Polopoly (Based on 0.9).
Sadly the newest does not work for us, so I'm adding patches on the latest known good version.

NB. minified files used:
cat js/util.js js/stringstream.js js/select.js js/undo.js js/editor.js js/tokenize.js js/parsecss.js | ./closure > basefiles_css.js
cat js/util.js js/stringstream.js js/select.js js/undo.js js/editor.js js/tokenize.js js/tokenizejavascript.js js/parsejavascript.js | ./closure > basefiles_js.js
cat js/util.js js/stringstream.js js/select.js js/undo.js js/editor.js js/tokenize.js js/parsecss.js js/tokenizejavascript.js js/parsejavascript.js js/parsexml.js js/parsehtmlmixed.js | ./closure > basefiles_html.js

