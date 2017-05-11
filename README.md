# IntuitProject
<p>Project created on 5/10/2017</p>
<p>Author: Shane Yang</p>
Project for Intuit interview
<h2>Question:  Is your solution optimal? If so, why?</h2>
<ul>
<li>The soultion that I have written out changes the map&lt;string, string> to map&lt;Integer, string> allowing users to easily change channels, whether it
is through a selection or increments.</li> 
<li>The code assumes that the user can choose to start at channel 0 or select their own channel to start on.
The ability to start on a channel can be useful for when the user starts a new session, eg. turning off the tv and turning it back on to
the same channel.</li>
<li>For the goToChannel() method the program can check if a entered channel is valid or not, this will prevent users from trying
to access a channel number outside of the collection of channels.</li>
<li>The channelUp() and channelDown() methods also have a similar check in place. The up and down methods will check if the current channel reaches the upper or lower
limit of the channel list and start the channel on the top or bottom of the list.</li>
</ul>
