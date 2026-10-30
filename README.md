# Annual Conference prototype

A working demo of the Annual Conference tools for ogbbc.org, built as a WordPress plugin. It is for the webmasters and the Committee of Arrangements to look at and talk over.

- **Everyone in it is made up.** Every person, household, phone number and count is a sample. It is not the real site, and nothing in it is real data.
- **The details are the committees' to decide.** What you see is one way it could work, to be shaped by your input.

## Open it

https://playground.wordpress.net/?mode=seamless&blueprint-url=https://raw.githubusercontent.com/fallguy04/ogbbc-conference-prototype/main/blueprint.json

The link runs the whole site inside your own web browser, through WordPress Playground (a tool from WordPress.org). Nothing is installed on your computer, what you do stays in your browser, and it starts fresh each time you open the link. The first visit can take a minute to load.

## Looking around

Click around as you would on the real site. A small dark pill in the bottom right corner says which day you're looking at and who you are (`Mar 2 · Visitor`). Point at it, or tap it, to choose:

- **When:** a day in the coming Conference's year: when it's announced, when registration opens, when the schedule is out, the week before, during Conference, and after. The whole site stays on that day as you click around.
- **As:** a visitor, the Committee of Arrangements, Lodging, or a webmaster. Each opens the page that person would use.


No email is ever sent from the prototype: where the site would email a sign-in code, the prototype shows it on screen. Phone numbers, texts and map links say what they would do on a phone instead of opening.

## What's in this folder

- `blueprint.json`: what WordPress Playground sets up (the plugin, a stand-in for the site's theme, and the sample data).
- `ogc-conference.zip`: the plugin.
- `ogbbc-standin.zip`: a stand-in for the ogbbc.org theme's header and footer.
