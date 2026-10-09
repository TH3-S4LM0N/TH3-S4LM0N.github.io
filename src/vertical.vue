<script setup lang="ts">
import untitled_short_story from './writings/untitled_short_story.vue'
import pvguqb from './writings/pvguqb.vue'
import everything_game from './writings/everything_game.vue'
import review_outer_wilds from './writings/review_outer_wilds.vue'
</script>

<template>
  <div style="background: black; padding: 1rem">
    <h1>Blake 'Salmon' Blankenship</h1>
    blakeblank007@gmail.com | <a href="https://www.instagram.com/th3s4lm0n/">@th3s4lm0n</a>
    <el-divider />
    <div>
      <p>
        I'm a Christian game designer and writer from Dallas. I've been programming since I was 14,
        with an introduction from modding games, leading into a passion for RPG design, game
        writing, and development in general. I've released one larger project, a tabletop RPG by the
        name of <i>Myst</i>, worked on multiple smaller ones, and am currently starting a new game
        called Choros. In the meantime, I'm studying Animation and Games at the University of Texas
        at Dallas.
      </p>
      <p style="margin-top: 1em">For my UTD game lab application:</p>
      <p>
        While references were not mentioned, I have a letter of recommendation from Dr Adam Brackin
        (abrackin@ccawarriors.com), who taught a few narrative and design classes in the Bass school
        here at UTD way back when, and taught various english and creative writing classes for me in
        high school.
      </p>
      <p>
        It doesn't exactly fit in a portfolio well but I can also produce my non-gamedev related
        resume of previous jobs if you'd like to consider it.
      </p>
    </div>
    <el-divider />
    <h2>My Projects</h2>
    <h3 style="font-family: 'Petit Formal Script'">
      <i>Myst: A Fantasy Role-Playing Game about Perfection</i>
    </h3>

    <a
      href="https://www.drivethrurpg.com/en/product/568196/myst-a-fantasy-role-playing-game-about-perfection"
      style="font-size: 0.75rem"
      >Download on DriveThruRPG</a
    >
    <br />
    <p>
      <i>Myst</i> is a short TTRPG and my first delve into writing a serious and large scale
      non-linear story. While it's a project I'm proud of, I'd say a lot more learning for Blake
      Blankenship came out of it than good game for everybody else. It taught me the importance of
      planning ahead, especially in non-linear writing, and it also taught me that scope creep is
      very real.
    </p>
    <p>
      <i>Myst</i> is a game about the PC grappling with vampyrism and their sinful nature, and the
      many gods and vices that rule our worlds. It follows the player incarnating into their new
      life to discover a dark disease within their deepest essence. They are inherently ruined.
      Vampyrism makes them the scum of the earth to man and Numein, the lesser gods worshipped as
      true divinity across Ikkown.
    </p>
    <p style="margin-bottom: 1em">
      Thematically, <i>Myst</i> focuses on what gives what we call good, evil, and apathy meaning,
      and explores why purpose often falls short in the wake of eternity. Valsai Kwaarum. Valsai
      Yonum. Valsai Mathia.
    </p>
    <center>
      <div style="margin-bottom: 1rem">
        <img src="./images/ikkown-map.jpg" width="50%" />
        <br />
        <center>A world map</center>
      </div>

      <div>
        <img src="./images/a-history.jpg" width="50%" />
        <br />
        <center>A page from the world history</center>
      </div>
    </center>
    <p class="marginp">
      While <i>Myst</i> is a project I am proud of, it's themes do not wholly reflect who I am or
      what I believe anymore. In all honesty, if you'd like to know about it to learn about me,
      don't read it, just ask me about it.
    </p>
    <el-divider />
    <h3 style="font-family: 'Quantico'"><i>Choros</i></h3>
    <p>
      Choros is a current work in progress, having started in early September of 2026, and is my
      first attempt at a full scale (~10 hr) video game.
    </p>
    <p>
      It is a sci-fi cRPG about the universe ending and you being left behind, the worth and purpose
      of a life in the face of the destruction of the race, and why nothing has actually changed in
      this scenario. It's currently being made in Godot 4 with GDScript, and I plan to make most of
      the assets (which it is admittedly not super heavy on) myself or with assistance from an
      artist.
    </p>
    <div>
      <center>
        <img src="./images/chorosmenu.gif" width="100%" />
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
      At the time, swapping models wasn't possible with the tools available, and I worked with a few
      other people to make the first public mod that was able to do model swapping. I additionally
      wrote a fair amount of documentation for the Northstar client for Titanfall in it's infancy
      (although little of that is still around today).
    </p>
    <el-divider />
    <h3 style="font-family: 'IBM Plex Sans Thai Looped'">
      &lt;This Website /&gt; (and general programming skills)
    </h3>
    <p>
      While it's not exactly the most beautiful thing I've ever seen, I made it by hand with Vue and
      Element+ and I'm rather proud of it. In addition to a basic knowledge of HTML and TypeScript,
      I'm proficient with Rust and Godot, and fairly decent with C++ and Python. I also have plenty
      of experience with Linux for what it's worth.
    </p>

    <el-divider />
    <div style="text-align: center">
      <h1 style="text-align: center">My Writings</h1>
      Website is actively being revamped, more added as I format old things
    </div>
    <el-divider />
    <div>
      <review_outer_wilds class="writing-margin" />
      <el-divider />
      <everything_game class="writing-margin" />
      <el-divider />
      <pvguqb class="writing-margin" />
      <el-divider />
      <untitled_short_story class="writing-margin" />
      <el-divider />
      <p style="margin-bottom: 1em"><center>Thanks for looking at my stuff!</center></p>
    </div>
  </div>
</template>

<style>
@import './general.css';

.writing-margin {
  margin-left: 15%;
  margin-right: 15%;
}

@media (max-width: 400px) {
  .writing-margin {
    margin-left: 0;
    margin-right: 0;
  }
}
</style>
