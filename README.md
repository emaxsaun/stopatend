JW Player Stop At End
==========

This is a small JavaScript library for use with the JW Player. It makes the player stop right before the end of the video, to show the last frame of the video, instead of going into an idle state, and displaying the poster image. It creates a replay button on the player as if playback had actually completed.

### [Demo](http://www.pluginsbyethan.com/github/stopatend.html)

Implementation:
==========

The file stopatend.js simply needs to be loaded unerneath the closing script tag for your JW Player embed. It is that simple. Like so:

<pre>
&lt;script type=&quot;text/javascript&quot; src=&quot;stopatend.js&quot;&gt;&lt;/script&gt;
</pre>

Example:
==========
<pre>
&lt;script type=&quot;text/javascript&quot; src=&quot;jwplayer.js&quot;&gt;&lt;/script&gt;
&lt;div id=&quot;player&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
jwplayer('player').setup({
&nbsp;&nbsp;'width': '575',
&nbsp;&nbsp;'height': '400',
&nbsp;&nbsp;'file': 'video.mp4'
&nbsp;&nbsp;'image': &quot;video.jpg&quot;
});
&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;stopatend.js&quot;&gt;&lt;/script&gt;
</pre>

The source code is available for this script. There is just a .js file for JavaScript. Publishing the JavaScipt can be simply done with any text editor. Enjoy~! :)