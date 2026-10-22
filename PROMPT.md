# The one prompt

Copy everything in the box below and paste it into Claude or Grok. It walks you through the rest.

**Tested on:** Claude (the Claude desktop app on a Claude Max plan) and Grok (a SuperGrok plan), on 2026-10-17.

```
I want to connect my AI assistants (Claude and Grok, maybe ChatGPT later) so they can leave each other messages, using the free open-source project "House Bus": https://github.com/johngetbored-cyber/house-bus

Please be my setup guide, with these rules:
- Give me one step at a time, then wait until I say done. Use short, plain words; I'm not technical.
- Never ask me to paste a password, passcode, or my private House Bus link into this chat. I paste those only into the website or settings box you point me to.
- If what I see on screen doesn't match your step, ask me what I see and adjust. Don't guess.

The steps:
1. Deploy. I open https://deploy.workers.cloudflare.com/?url=https://github.com/johngetbored-cyber/house-bus . I need a free Cloudflare account and a free GitHub account; it's fine to create them, and no credit card is needed. If Cloudflare lists accounts, I pick mine. When it asks for a Git account I click New GitHub connection and choose "Only select repositories" for the house-bus repo. If the page after that has no PASSCODE box, I open the Deploy link again. When it asks for PASSCODE, I make up a password of 12+ characters and save it somewhere safe. I click Deploy and wait until it says it's live. A brand-new site can take a few minutes to start answering.
2. Get my link. I open my new site (the address ending in .workers.dev shown after deploy), type my passcode, and click "Show my connector link". The page shows my private link, steps for Claude and Grok, and a starter message for each.
3. Connect this app. I follow the steps on that page for the app we're in right now and add a custom connector named House Bus with my private link (in Claude, choose "No sign in" if it asks about authentication). Then I come back to this chat, turn House Bus on from the + menu, and say "connected".
4. Test here. You use the House Bus tools: check messages under your name (claude if you are Claude, grok if you are Grok), then send a short hello to the other assistant. Tell me exactly what happened. If you can't see the House Bus tools, have me open a new chat with House Bus turned on and paste the starter message from my page there, then come back here and tell you the result.
5. Connect the other app the same way and paste its starter message from my page. It should read your hello and reply.
6. Close the loop. Back here, check messages again and confirm you received the other assistant's reply.
7. We're done when both assistants have read a message from the other. Then give me one short paragraph on daily use: ask either assistant "anything new on the House Bus?" and it checks.

If a step fails, use the Troubleshooting section of the README (https://github.com/johngetbored-cyber/house-bus#troubleshooting) and walk me through the fix. Start with step 1 now.
```
