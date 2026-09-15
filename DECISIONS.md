# Decision log

Your methods section. About one page total.

Answer these as you go, not the night before it is due.
Specifics beat polish - a short honest answer is worth more than a long vague one.

Delete these instructions when you are done, or leave them. It does not matter.

---

## 1. What did you set out to build, and what changed?

What you wanted at the start, and what is actually live now.
Name one thing you dropped or added along the way, and why.

I set out to build a personal portfolio website that I could use outside of this class, not just a site made for an assignment. I wanted it to introduce who I am, show some of my projects, and give people a quick way to see my skills and contact information.

The live version became more focused on game development and graphics than my first idea. One change I made was replacing Circuit Detective with Away from Kitty because Away from Kitty represents more of my own creative work and shows my experience with game planning, UI, and visual art.

---

## 2. A fork in the road

Name one real choice where you could have gone two ways.
Plain HTML or a framework. One page or several. Your own CSS or someone's template.
What goes on the front page and what does not.

Say which you picked, what the alternative was, and what you gave up by not taking it.

"There was no alternative" is not an answer. Find the fork.

One choice I had to make was whether to build a single scrolling page or separate pages for About, Projects, Skills, and Contact.

I chose the single-page layout because I wanted visitors to be able to see everything quickly without opening several pages. The alternative would have made each section more independent and would have given me more room for detailed project pages, but it also would have made the site more complicated to navigate and maintain.


---

## 3. Where you overruled the agent

One time Claude suggested, wrote, or claimed something and you did not take it.

What did it do? How did you notice? What did you do instead?

If it genuinely never happened, say so plainly, and then say what you would have had to
check in order to notice. Being honest here costs you far less than a story you cannot
defend when you record your video.

Claude originally used Circuit Detective as one of the main projects and also included Phaser in the skills section. I decided not to keep that choice because I wanted the portfolio to represent the projects and tools that I most wanted people to associate with me.

I replaced Circuit Detective with Away from Kitty, a group RPG made in GameMaker where I worked on the game planning and created the UI and visual art. I also removed Phaser and added GameMaker to the skills section. This made the portfolio more accurate to the work I wanted to present.


---

## 4. How you know it works

What check did you run, and what did it tell you?

Then the real question: **what would have made this check fail?**
A check that could not have failed is not a check.

Link to your `verification/` folder.


I first tested the site locally at `http://localhost:8000` and checked that the navigation, sections, layout, and links displayed correctly. I also published the site through GitHub Pages and opened the live URL to confirm that the deployed version loaded outside of the local development environment.

These checks could have failed if the file paths were incorrect, if GitHub Pages was configured incorrectly, if files were not pushed to the repository, or if the live site loaded differently from the local version.

Verification:
[verification/](./verification/)

---

## 5. What is still wrong

One thing on your own site that is not right, not finished, or that you do not
fully understand.

What would you do next, and how would you find out?

The project descriptions are still fairly short, and the portfolio does not yet include screenshots, playable builds, or detailed pages for each project.

My next step would be to add images and links for projects such as Away from Kitty and expand the project section as I complete more work. I would test those additions locally first and then check the deployed GitHub Pages version to make sure the images and links work correctly.
