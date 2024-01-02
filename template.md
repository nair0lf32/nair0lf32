# Hi 👾, I'm Florian EDEMESSI

A Med student who codes (somehow). I am a "self-taught" developer and software engineer **wannabe** with a decent understanding of web/software development most important concepts, fiddling with many programming languages at once (mostly C, Python, and Javascript) always learning new things (Golang and Rust currently). I am mostly trying to have fun and in the meantime, contribute to the development of awesome solutions for some of the world's silliest problems. I am also a terrible CTF player, passionate about cybersecurity and worst coding practices imaginable. I also happen to enjoy video games and silly memes (^_^)

Welcome to my personal GitHub, where I put terrible spaghetti code and stuff. May you ever find something you like

## Metrics

**{{ Math.round(REGISTERED_YEARS) }}** years ago I joined GitHub on **{{ f.date(REGISTRATION_DATE, {date:true}) }}**, and so far, I contributed to **{{ REPOSITORIES_CONTRIBUTED_TO }}** repositories, with just **{{ REPOSITORIES }}** repositories created by me. I got **{{ STARGAZERS }}** nice stargazers, and starred **{{ STARRED }}** repositories myself, made **{{ COMMITS }}** commits, joined **{{ ORGANIZATIONS }}** organizations, made **{{ PULL_REQUESTS }}** pull requests, got involved into **{{ ISSUES }}** issues. I am following **{{ FOLLOWING }}** great inspiring people and got **{{ FOLLOWERS }}** great ones behind me too, to which I am very thankful 💛. I use a lot of coding languages and tools but my favorite ones are:

<% LANGUAGES.forEach(language => { %>
  <li><strong><%= language.name %></strong>: <%= language.size %> bytes</li>
<% }); %>


[![My Skills](https://skillicons.dev/icons?i=linux,bash,c,python,js,php,kotlin,flutter,golang,rust)](https://skillicons.dev)

## Cool music I vibe with

<%- await embed(`nairolf-music`, {music:true, music_token:"${{ secrets.SPOTIFY_SECRET }}", music_mode:"recent", music_played_at:true, music_provider:"spotify", music_user:"nairolf32"}) %>

## Weeb stuff

<%- await embed(`nairolf-anilist`, {anilist:true, anilist_user:"nairolf32", anilist_media:"anime,manga", anilist_sections:"favorites, characters"}) %>

## wanna get in touch?

Most (if not all) of my social links are available on my [about.me](https://about.me/florian_edemessi) page. I recommend using mostly mails, whatsApp or discord to reach me faster, as I check those more often, but feel free to use any available link you want.

*If you wanna see my favorite places for [learning or practice coding](https://github.com/nair0lf32/challenger) follow the given link.*

*Also feel free to check my pinned repositories for more details about my main projects*

## There you go

![Jokes Card](https://readme-jokes.vercel.app/api?hideBorder)
