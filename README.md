# Website design kit

Your ChatGPT-made website works. This kit helps it look designed, and look like *you*.

You give ChatGPT a design rulebook. It interviews you about your life and work, shows you three different directions, and rebuilds your site from the one you pick. Along the way it writes a `DESIGN.md` file, your site's own design system, so every later change stays consistent.

## What's in here

| File | What it is | Who reads it |
|---|---|---|
| [`design-guide.md`](design-guide.md) | The design rulebook | ChatGPT (you attach it) |
| [`PROMPT.md`](PROMPT.md) | Two prompts to copy and paste | You copy it, ChatGPT follows it |
| `README.md` | This page | You |

## How to use it

Set aside about an hour the first time.

1. **Download the guide.** Open [`design-guide.md`](design-guide.md) and click the download button ("Download raw file") at the top right of the file.
2. **Download your current site.** In your website's GitHub repo, download `index.html` the same way, plus `styles.css` if you have one. Starting from scratch? Skip this step.
3. **Start a new ChatGPT chat** and attach `design-guide.md`, your site files, and, if you like, a few photos you want on the site or a photo whose colors you love. If your ChatGPT has **Projects**, make one called "My website" and add the files there, so every chat about your site can see them.
4. **Copy Prompt 1** from [`PROMPT.md`](PROMPT.md) (the copy button sits at the top right of the box), paste it into the chat, and send.
5. **Answer the interview honestly and specifically.** This is the whole trick. "I restore old furniture, and my workshop smells like linseed oil" gives ChatGPT something to design from. "Modern and clean" doesn't.
6. **Pick a direction.** ChatGPT shows you three. Pick one, or mix them: "B's colors with A's fonts."
7. **Check it on your phone** before you publish. Most of your visitors will see it there.
8. **Publish.** In your GitHub repo, replace `index.html` with the new one, upload any photos into an `images` folder, and add your `DESIGN.md`. GitHub Pages updates within a few minutes.

## Coming back later

ChatGPT forgets your design between chats. `DESIGN.md` is how it remembers. Next time, attach `design-guide.md`, your `DESIGN.md`, and your current site files, then paste **Prompt 2** from [`PROMPT.md`](PROMPT.md).

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

The guide is written for ChatGPT and for people who aren't designers. It draws on two excellent design guides written for AI coding tools: Anthropic's [frontend-design skill](https://github.com/anthropics/claude-code/tree/main/plugins/frontend-design) and Paul Bakaus's [Impeccable](https://github.com/pbakaus/impeccable). For inspiration, [awesome-design-md](https://github.com/VoltAgent/awesome-design-md) collects the design systems of well-known websites. Borrow an ingredient you like, but don't copy anyone's whole look: the point is a site that's yours.

MIT licensed. Share it freely.
