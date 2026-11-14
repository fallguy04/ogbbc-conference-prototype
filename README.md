# Annual Conference prototype

A working demo of the Annual Conference tools for ogbbc.org, built as a WordPress plugin. It is for the webmasters and the Committee of Arrangements to look at and talk over.

- **Everyone in it is made up.** Every person, household, phone number and count is a sample. It is not the real site, and nothing in it is real data.
- **The details are the committees' to decide.** What you see is one way it could work, to be shaped by your input.

## Open it

**The demo has moved:** https://conference-rqens.ondigitalocean.app/annual-conference/

The Playground link below now shows a page with an Open the demo button that goes there. The new site has everything this prototype had, and more.

https://playground.wordpress.net/?mode=seamless&blueprint-url=https://raw.githubusercontent.com/fallguy04/ogbbc-conference-prototype/main/blueprint.json

The old WordPress version, frozen on Nov 10, 2026, is kept for reference:
https://playground.wordpress.net/?mode=seamless&blueprint-url=https://raw.githubusercontent.com/fallguy04/ogbbc-conference-prototype/main/blueprint-prototype.json

It runs the whole site inside your own web browser, through WordPress Playground (a tool from WordPress.org). The first visit can take a minute to load.

## Looking around

Click around as you would on the real site. A small dark pill in the bottom right corner says where you are (`Conference page · Mar 2`). Point at it, or tap it, to choose:

- **Go to:** the Conference page, Register, Volunteer, Tournaments, the guide, or the committees' side.
- **Day** (on the Conference page and the guide): when it's announced, when registration opens, when the schedule is out, the week before, during Conference, and after. Registering and volunteering are always open.
- **Signed in as** (on the committees' side): the Committee of Arrangements, Lodging, or a webmaster.
- **Leave feedback** (beside the pill at the bottom) takes a picture of the screen you're on, a pop-up included; add your idea and your name, and tap the thing you mean if you like. The number beside it opens the board: the feed of ideas, newest first, with every screen of the demo beside it to pick from, and Upvote and Reply on each idea.

To try a form without typing your own details, press **Autofill** (a small dark pill beside Continue on Register, and at the top of a first-time volunteer's sign-up). It fills the step with a made-up household; Continue goes on. Type your own instead whenever you like.

No email is ever sent from the prototype: where the site would email a sign-in code, the prototype shows it on screen (Autofill fills that in too). Phone numbers, texts and map links say what they would do on a phone instead of opening.

## What's in this folder

- `blueprint.json`: the page that sends the old link to the new demo.
- `blueprint-prototype.json`: the old prototype (the plugin, a stand-in for the site's theme, and the sample data).
- `ogc-conference.zip`: the plugin.
- `ogbbc-standin.zip`: a stand-in for the ogbbc.org theme's header and footer.
