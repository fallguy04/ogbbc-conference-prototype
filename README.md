# Annual Conference prototype

A working demo of the Annual Conference tools for ogbbc.org, built as a WordPress plugin. It is for the webmasters and the Committee of Arrangements to look at and talk over.

- **Everyone in it is made up.** Every person, household, phone number and count is a sample. It is not the real site, and nothing in it is real data.
- **The details are the committees' to decide.** What you see is one way it could work, to be shaped by your input.

## Open it

https://playground.wordpress.net/?mode=seamless&blueprint-url=https://raw.githubusercontent.com/fallguy04/ogbbc-conference-prototype/main/blueprint.json

The link runs the whole site inside your own web browser, through WordPress Playground (a tool from WordPress.org). Nothing is installed on your computer, what you do stays in your browser, and it starts fresh each time you open the link. The first visit can take a minute to load.

## The tour

A small card at the foot of the screen walks through ten scenes, one at a time: the Conference page when registration opens and a week before, a family registering, volunteering, the guide during Conference, the printed schedule, the Committee of Arrangements' home, the households that have registered, Lodging's rooms, and the webmasters' view. Each scene signs in the right made-up person and shows the date that fills the screen. Next and Back move between them; **Scenes** lists them all and lets you see a page as someone else. The card can be closed and opened again.

No email is ever sent from the prototype: where the site would email a sign-in code, the prototype shows it on screen. Phone numbers, texts and map links say what they would do on a phone instead of opening.

## What's in this folder

- `blueprint.json`: what WordPress Playground sets up (the plugin, a stand-in for the site's theme, and the sample data).
- `ogc-conference.zip`: the plugin.
- `ogbbc-standin.zip`: a stand-in for the ogbbc.org theme's header and footer.
