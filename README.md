# soundcloud-mp3-downloader-api
This SoundCloud downloader API is provides direct mp3 download of any soundcloud track from your website.
<br>

<p><b>ACKNOWLEDGEMENT:</b> <br>
This API is a powered by
<a href="https://soundclouddownloader.info/" title="Soundcloud downloader">SoundCloud Downloader</a>. <br>

<b>ABOUT API:</b> <br>
This API is free to use for everyone. You 
can also customize it's designed as per your websites theme / requirement. Its a 
free service and always will be. Documentation: You can access this API via 
Iframe or HTML link as well. We have documented it to give you a working demo of 
this API.<br>

<b>EXAMPLES: IFRAME API [Track ID]: </b><br>
<pre><code><iframe src="https://soundclouddownloader.info/iframe-api/?t=SOUNDCLOUD_TRACK_ID" width="480" height="160" scrolling="no" style="border:none;"></iframe></code></pre><br>

<b>IFRAME API [Track URL]: </b><br>

<pre><code><iframe src="https://soundclouddownloader.info/iframe-api/?t=SOUNDCLOUD_TRACK_URL" width="480" height="160" scrolling="no" style="border:none;"></iframe></code></pre>

<b>BUTTON API: </b><br>
<pre><code>&lt;a href="https://soundclouddownloader.info/button-api/?t=SOUNDCLOUD_TRACK_ID/TRACK_URL"&gt;Download Link&lt;/a&gt;</code></pre>
<br>
<b>CSS STYLESHEETS FOR BUTTON API: </b><br>
You can also use these predefined css styles with the html button link to customize it.<br/>

To Create Green Color Button: <br/>
<pre>
<code>
<style>.button {
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}</style>
</code>
</pre>
<br>
<pre><code>&lt;a href="https://soundclouddownloader.info/button-api/?t=SOUNDCLOUD_TRACK_ID/TRACK_URL" class="button"&gt;Download&lt;/a&gt;</code></pre>
<br>



<b>Button Colors:</b><br/>
Use the background-color property to change the background color of a button: <br/>
<pre>
<code>
<style>
.button2 {background-color: #008CBA;} /* Blue */
.button3 {background-color: #f44336;} /* Red */ 
.button4 {background-color: #e7e7e7; color: black;} /* Gray */ 
.button5 {background-color: #555555;} /* Black */
</style>
</code>
</pre>
<br/>


<b>Button Sizes:</b><br/>
Use the font-size property to change the font size of a button:
<br/>
<pre>
<code>
<style>
.button1 {background-color: #4CAF50;} /* Green */
.button2 {background-color: #008CBA;} /* Blue */
.button3 {background-color: #f44336;} /* Red */ 
.button4 {background-color: #e7e7e7; color: black;} /* Gray */ 
.button5 {background-color: #555555;} /* Black */
</style>
</code>
</pre>
<br>
        
    
Use the padding property to change the padding of a button:
<br/>
<pre>
<code>
<style>
.button1 {padding: 10px 24px;}
.button2 {padding: 12px 28px;}
.button3 {padding: 14px 40px;}
.button4 {padding: 32px 16px;}
.button5 {padding: 16px;}
</style>
</code>
</pre>
<br/>

<b>Rounded Buttons:</b><br/>
Use the border-radius property to add rounded corners to a button:
<br/>
<pre>
<code>
<style>
.button1 {border-radius: 2px;}
.button2 {border-radius: 4px;}
.button3 {border-radius: 8px;}
.button4 {border-radius: 12px;}
.button5 {border-radius: 50%;}
</style>
</code>
</pre>
<br>

<b>Colored Button Borders:</b><br/>
Use the border property to add a colored border to a button:
<br/>
<pre>
<code>
<style>
.button {
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

.button1 {
    background-color: white; 
    color: black; 
    border: 2px solid #4CAF50;
}

.button2 {
    background-color: white; 
    color: black; 
    border: 2px solid #008CBA;
}

.button3 {
    background-color: white; 
    color: black; 
    border: 2px solid #f44336;
}

.button4 {
    background-color: white;
    color: black;
    border: 2px solid #e7e7e7;
}

.button5 {
    background-color: white;
    color: black;
    border: 2px solid #555555;
}
</style>
</code>
</pre>
<br>

<b>Hoverable Buttons:</b><br/>
Use the :hover selector to change the style of a button when you move the mouse over it.<br>
<strong>Tip:</strong> Use the transition-duration property to determine the speed of the "hover" effect:
<br/>
<pre>
<code>
<style>
.button {
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 16px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    cursor: pointer;
}

.button1 {
    background-color: white; 
    color: black; 
    border: 2px solid #4CAF50;
}

.button1:hover {
    background-color: #4CAF50;
    color: white;
}

.button2 {
    background-color: white; 
    color: black; 
    border: 2px solid #008CBA;
}

.button2:hover {
    background-color: #008CBA;
    color: white;
}

.button3 {
    background-color: white; 
    color: black; 
    border: 2px solid #f44336;
}

.button3:hover {
    background-color: #f44336;
    color: white;
}

.button4 {
    background-color: white;
    color: black;
    border: 2px solid #e7e7e7;
}

.button4:hover {background-color: #e7e7e7;}

.button5 {
    background-color: white;
    color: black;
    border: 2px solid #555555;
}

.button5:hover {
    background-color: #555555;
    color: white;
}
</style>
</code>
</pre>
<br>
    
    
<b>SUPPORT:</b><br>

Right now we have limited support via E-mail's. <br>
Via E-mail us : info@soundclouddownloader.info <br>

<b>DISCLAIMNER:</b><br>

We do not host (or serve/stream) any 
copyrighted/pirated content (SoundCloud Tracks) on (or from) our server. Users 
download soundcloud tracks directly from their CDN server.</p>
