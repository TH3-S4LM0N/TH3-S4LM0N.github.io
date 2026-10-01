<script setup lang="ts">
import untitled_short_story from './writings/untitled_short_story.vue'
</script>

<template>
  <div style="background: black; margin-left: 300px; margin-right: 300px">
    <el-main>
      <h1>Blake Blankenship</h1>
      blakeblank007@gmail.com | <a href="https://www.instagram.com/th3s4lm0n/">@th3s4lm0n</a>
      <el-divider />
      <div>
        <p>
          I'm a Christian game designer and writer from Dallas. I've been programming since I was
          14, with an introduction from modding games, leading into a passion for RPG design, game
          writing, and development in general. I've released one larger project, a tabletop RPG by
          the name of <i>Myst</i>, worked on multiple smaller ones, and am currently starting a new
          game called Choros. In the meantime, I'm studying Animation and Games at the University of
          Texas at Dallas.
        </p>
      </div>
      <el-divider />
      <h2>My Projects</h2>
      <h3 style="font-family: 'Petit Formal Script'">
        <i>Myst: A Fantasy Role-Playing Game about Perfection</i>
      </h3>

      <a
        href="https://www.drivethrurpg.com/en/product/568196/myst-a-fantasy-role-playing-game-about-perfection"
        style="font-size: 9pt"
        >Download on DriveThruRPG</a
      >
      <br /><br />
      <p>
        <i>Myst</i> is a short TTRPG and my first delve into writing a serious and large scale
        non-linear story. While it's a project I'm proud of, I'd say a lot more learning for Blake
        Blankenship came out of it than good game for everybody else. It taught me the importance of
        planning ahead, especially in non-linear writing, and it also taught me that scope creep is
        very real.
      </p>
      <p style="margin-bottom: 1em">
        <i>Myst</i> is a game about the PC grappling with vampyrism and their sinful nature, the
        many gods and vices that rule our worlds, and what gives good, evil, and apathy meaning.
      </p>
      <center>
        <el-space>
          <div>
            <img src="./images/ikkown-map.jpg" width="500px" />
            <br />
            <center>A world map</center>
          </div>

          <div>
            <img src="./images/a-history.jpg" width="500px" />
            <br />
            <center>A page from the world history</center>
          </div>
        </el-space>
      </center>
      <p class="marginp">
        While <i>Myst</i> is a project I am proud of, it's themes do not wholly reflect who I am or
        what I belive anymore. In all honesty, if you'd like to know about it to learn about me,
        don't read it, just ask me about it.
      </p>
      <el-divider />
      <h3 style="font-family: 'Quantico'"><i>Choros</i></h3>
      <p>
        Choros is a current work in progress, having started in early September of 2026, and is my
        first attempt at a full scale (~10 hr) video game.
      </p>
      <p>
        It is a sci-fi cRPG about the universe ending and you being left behind, and the worth and
        purpose of a life in the face of the destruction of the race.
      </p>
      <div>
        <center>
          <img src="./images/chorosmenu.gif" />
          <br />
          Main menu with placeholders
        </center>
      </div>
      <el-divider />
      <h3 style="font-family: 'Silkscreen'">Mods</h3>
      <p>
        My introduction to programming was through making mods for Titanfall 2. One of my favorites
        was the
        <a href="https://thunderstore.io/c/northstar/p/TH3_S4LM0N/kunai_melee/">kunai melee mod</a>.
        At the time, swapping models wasn't possible with the tools availible, and I worked with a
        few other people to make the first public mod that was able to do model swapping. I
        additionally wrote a fair amount of documentation for the Northstar client for Titanfall in
        it's infancy (although little of that is still around today).
      </p>
      <el-divider />
      <h3 style="font-family: 'IBM Plex Sans Thai Looped'">
        &lt;This Website /&gt; (and general programming skills)
      </h3>
      <p>
        While it's not exactly the most beautiful thing I've ever seen (and it falls to pieces in
        anything but 16:9 as I haven't implemented UI scaling yet), I made it by hand with Vue and
        Element+ and I'm rather proud of it. In addition to a basic knowledge of HTML and
        TypeScript, I'm proficient with Rust, and fairly decent with C++ and Python. I also have
        plenty of experience with Linux for what it's worth.
      </p>
    </el-main>

    <el-divider />
    <div>
      <center>
        <h1>My Writings</h1>
        More added as I write or decide old things are worth including
      </center>
    </div>
    <el-divider />
    <untitled_short_story />
  </div>
</template>

<style>
@import './general.css';

body {
  background-image: url('./images/original.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
</style>
