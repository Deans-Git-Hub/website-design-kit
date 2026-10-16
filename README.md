# Website design kit

Your ChatGPT-made website works. This kit helps it look designed, and look like *you*.

> **ChatGPT:** your instructions are in [`chatgpt-instructions.md`](chatgpt-instructions.md). Read that file in full, to the check word at the end, and follow it.

## How it works

You send ChatGPT a short message with two links: this kit, and your website's GitHub repo. ChatGPT reads the instructions, interviews you about your life and work, shows you three different design directions, and rebuilds your site from the one you pick. Along the way it writes a `DESIGN.md` file, your site's own design system, so every later change stays consistent.

## What's in here

| File | What it is |
|---|---|
| [`chatgpt-instructions.md`](chatgpt-instructions.md) | The rulebook ChatGPT follows: the step-by-step process, the generic "AI-made" looks to avoid, craft rules for type, color, spacing, and phones, the `DESIGN.md` template, and a checklist ChatGPT runs before handing you anything. You don't need to read it, but you're welcome to. |
| `README.md` | This page: how to use the kit. |

## How to use it

Set aside about an hour the first time.

1. **Open a new ChatGPT chat.**
2. **Copy this message** (the copy button sits at the top right of the box), put your site's repo link in, and send it:

   ```text
   Please read this repo and follow chatgpt-instructions.md exactly, from start to finish: https://github.com/Deans-Git-Hub/website-design-kit

   My website's repo is: [paste your repo link, or write "starting fresh"]

   Before you do anything else, tell me the check word at the very end of chatgpt-instructions.md. If you can't open either link, tell me plainly instead of guessing, and I'll paste the files in.
   ```

3. **Make sure it read everything.** Its first reply should start with "Kit loaded" and the check word, and should name your site's current headline. If it says it can't open a link, see [If ChatGPT can't open the links](#if-chatgpt-cant-open-the-links).
4. **Answer the interview honestly and specifically.** This is the whole trick. "I restore old furniture, and my workshop smells like linseed oil" gives ChatGPT something to design from. "Modern and clean" doesn't. If you have photos you want on the site, or a photo whose colors you love, attach them.
5. **Pick a direction.** ChatGPT shows you three. Pick one, or mix them: "B's colors with A's fonts."
6. **Check it on your phone** before you publish. Most of your visitors will see it there.
7. **Publish.** ChatGPT can read your repo but can't change it, so it walks you through the clicks: replace `index.html`, upload any photos, and add your `DESIGN.md`. GitHub Pages updates within a few minutes.

## Coming back later

Your `DESIGN.md` lives in your repo, so ChatGPT can pick up where you left off. Start a new chat and send:

```text
Please read this repo and follow chatgpt-instructions.md exactly, from start to finish: https://github.com/Deans-Git-Hub/website-design-kit

My website's repo is: [your repo link]. It has my DESIGN.md. Here's what I want to change: [describe it]

Before you do anything else, tell me the check word at the very end of chatgpt-instructions.md. If you can't open either link, tell me plainly instead of guessing, and I'll paste the files in.
```

## If ChatGPT can't open the links

Some ChatGPT plans and settings can't open GitHub links, and nobody can open a private repo from a link. Paste the files instead:

1. Open [`chatgpt-instructions.md`](chatgpt-instructions.md), click the copy button ("Copy raw file") at the top right of the file, and paste it into the chat.
2. In your own repo, do the same with `index.html` (and `styles.css` or `DESIGN.md`, if you have them), and paste each one below.
3. Say what you want ("redesign my site," or the change you're after), and send.

## Giving feedback that works

Vague feedback gets generic results. Point at one specific thing and say what it should feel like.

| Instead of | Try |
|---|---|
| "Make it pop." | "The headline should be the first thing I notice. Make it bigger and give it more space." |
| "It looks boring." | "It feels like a template. What's one thing only my site would have?" |
| "I don't like the colors." | "The colors feel cold. I want it to feel like [a place you love]." |
| "Make it more professional." | "Someone deciding whether to hire me should trust it in five seconds. What's in the way?" |
| "It's too busy." | "Take out the three things that matter least." |

## Credits

The kit is written for ChatGPT and for people who aren't designers. It draws on two excellent design guides written for AI coding tools: Anthropic's [frontend-design skill](https://github.com/anthropics/claude-code/tree/main/plugins/frontend-design) and Paul Bakaus's [Impeccable](https://github.com/pbakaus/impeccable). For inspiration, [awesome-design-md](https://github.com/VoltAgent/awesome-design-md) collects the design systems of well-known websites. Borrow an ingredient you like, but don't copy anyone's whole look: the point is a site that's yours.

MIT licensed. Share it freely.
