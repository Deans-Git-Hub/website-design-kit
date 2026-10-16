# The prompts

There are two. Use **Prompt 1** once, to redesign your site. Use **Prompt 2** in every chat after that.

## Prompt 1: Redesign my site

Before you paste it, attach these to a new ChatGPT chat:

1. `design-guide.md` from this repo (required).
2. Your current `index.html`, plus `styles.css` if your site has one. Starting from scratch? Skip this.
3. Optional: up to three photos you want on the site, or a photo whose colors you love.

Then copy everything in the box and send it.

```text
I'm redesigning my website with your help. I publish it with GitHub Pages, and I'm not a designer or a developer.

I've attached design-guide.md. Read all of it before you reply: it's the rulebook for this whole conversation. Sections 1 and 2 cover your role and how to work with me. Section 3 is where my site's personality should come from. Section 4 is the generic "AI-made" look to avoid. Section 5 holds the craft rules. Section 6 is the DESIGN.md template we'll fill in together, and section 7 is the checklist you run before you hand me any file. If I ask for something the guide warns against, do it, but tell me once that it's on the list.

If I attached my current site, treat it as the starting point: keep my content, replace the look. If I didn't, we're starting fresh.

Work through these steps with me. Finish each one, then wait for my reply before you start the next.

Step 1. Show me you read the guide: list the five rules that matter most for my site. If I attached my site, list what currently looks generic, using section 4.

Step 2. Interview me. Ask three or four questions at a time, in plain language, until you understand: who the site is for and what I want visitors to do; how I'd describe myself or my work to a friend; three words for how the site should feel, and one it must never feel like; the materials, places, tools, objects, and eras that show up in my work and life; colors, websites, magazines, album covers, or places I love, and what exactly I love about them; what I dislike; my real content (bio, photos, work, contact details); and any personal quirk that could become a signature. Follow up when my answers are vague. Stop when you have enough, usually after three rounds.

Step 3. Propose three design directions that are clearly different from each other. For each, give me: a name; one sentence on the idea and which of my answers it comes from; 4 to 6 named colors with hex codes; the fonts (from Google Fonts) and why they fit me; a quick text sketch of the top of the home page; the one signature element; and what it deliberately avoids. Then make one small file called directions.html that shows all three next to each other (colors, fonts, a sample headline, a button), so I can open it in my browser and compare. Give it to me as a download if you can, or show me a preview here. Ask me to pick one, or to mix parts of them.

Step 4. Write my DESIGN.md using the template in section 6, and show it to me. Ask me to confirm it or change it.

Step 5. Build the site from DESIGN.md and the guide. Give me complete files, ready to put in GitHub, as downloads if you can. After the files, list every placeholder I need to fill in, every image I need to upload (with the exact filename and folder), and three to six plain bullets on what changed.

Step 6. Critique your own work. Check what you built against the section 7 checklist and the section 4 list, tell me what you found, and give me a fixed version. Remove one decoration that isn't earning its place.

Step 7. Keep improving it with me. When I give feedback, change only what I asked for, keep everything consistent with DESIGN.md, and add a line to the DESIGN.md change log. When I'm happy, walk me through publishing: replacing index.html in GitHub, uploading images, and adding DESIGN.md to the repo.

The whole way through: plain English, complete files only, never invent facts about me, and ask before you rewrite how I describe myself.
```

## Prompt 2: Every chat after that

ChatGPT forgets your design between chats. `DESIGN.md` is how it remembers. Attach `design-guide.md`, your `DESIGN.md`, and your current `index.html` (plus `styles.css` if you have one), then send this, with your change filled in:

```text
I'm continuing work on my website. I've attached design-guide.md (the rulebook), DESIGN.md (my site's design system), and my current site files.

Read all of them before you reply. DESIGN.md is the source of truth for how my site looks and sounds, so follow it exactly. If a change I ask for would break it, tell me, and suggest how we'd update DESIGN.md instead.

Here's what I want to change: [describe it]

Give me complete files, list any images I need to upload, and run the section 7 checklist from the guide before you hand anything over. Add a line to the DESIGN.md change log, and give me the updated DESIGN.md too.
```
