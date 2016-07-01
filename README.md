<style>
p.quarter {
	float:left;
	width:25%;
	font-size:1.3em;
}
p.fifth {
	float:left;
	width:20%;
	font-size:0.9em;
}
a[id] {color:#333;}
</style>

<p align="center">
    <a href="https://github.com/inikulin/parse5">
        <img src="https://raw.githubusercontent.com/ChiefOfGxBxL/Glacier/master/header.jpg" alt="Glacier" />
    </a>
</p>

<p>
<center><b>Glacier</b><br/>
<i>Glacier is a WC3 suite that is built on top of SharpCraft. Essentially, it loads .dll's into the game. At a bigger picture, this means that map developers can leverage virtually any functionality that can be written in C#, the language SharpCraft and the .dll's are written in.</i></center>
</p>

----

<p class='quarter' align="center">
  <a href="#overview">Overview</a>
</p>

<p class='quarter' align="center">
  <a href="#get-started">Getting Started</a>
</p>

<p class='quarter' align="center">
  <a href="#developers">Developers</a>
</p>

<p class='quarter' align="center">
  <a href="#contributing">Contributing</a>
</p>

<br style='clear:both;'/>

<p class='fifth' align="center">
  <a href="#">Versions</a>
</p>

<p class='fifth' align="center">
  <a href="#">Authors</a>
</p>

<p class='fifth' align="center">
  <a href="#">Contact Us</a>
</p>

<p class='fifth' align="center">
  <a href="#">FAQ</a>
</p>

<p class='fifth' align="center">
  <a href="#">Feedback</a>
</p>

<br style='clear:both;'/>

----

<a id='overview'><h3>Overview</h3></a>
Glacier is a WC3 project built on top of SharpCraft. It does two things:  
	<ol>
		<li>Acts as a <b>game client</b>, managing maps and resources. Think of this as <i>Steam</i> but for Warcraft.
		<li>Injects .dll's and natives into Warcraft, greatly enhancing map capabilities.
	</ol>

Let's go over each point in a little more detail.

First, Glacier is a client. If you've ever used Steam to download games and connect with friends, you'll feel comfortable with Glacier. Glacier allows users to browse maps and download them. It acts as a central repository for maps. Further, the user can connect with friends through Glacier and easily play games with them by invite or arranged teaming. Maps are automatically kept up-to-date when the map developer pushes an update!

Second, we augment Warcraft's capabilities by importing .dll's and adding new natives. Check out the developer guide for assortment of modules that are available to use, but they include:
	<ul>
		<li>Local Storage - Read and write files locally on the user's file system. Useful for save codes!
		<li>Websocket - Use the websocket API to bypass Wc3 Battle.net to play multiplayer games. Now you can have games with more than 12 people in it!
		<li>Database - Store game data on Glacier servers. Great for RPGs!
		<li>Audio Manager - A specialized version of local storage, this allows you to have resources outside of the map, which can help reduce map file size
	</ul>

<a id='get-started'><h3>Getting Started</h3></a>
(We're currently working very hard to develop the client and will post it soon. The application is cross-platform.)

<a id='developers'><h3>Developers</h3></a>

<a id='contributing'><h3>Contributing</h3></a>

<h4>Authors and Contributors</h4>
Glacier is written by @chiefofgxbxl.  
Experimental map design and JASS ports written by @derdan.  
SharpCraft is written by MindWorX on The Hive.

<h4>Support or Contact</h4>
(We're working on public documentation and the wiki. If you need anything for now, PM @chiefofgxbxl)
