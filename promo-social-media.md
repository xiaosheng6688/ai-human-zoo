# Reddit — r/InternetIsBeautiful
## Post Title
AI Global Human Zoo — answer 8 questions and get your AI-generated creature form. No signup, works in 5 languages, 100% free.

## Post Body
Just built this over the weekend — a personality quiz that spits out your "biological form" in the digital age.

**How it works:**
1. Enter your name
2. Answer 8 weird questions
3. AI generates your creature image in 6 art styles (cyberpunk, anime, realistic, pixel, 3D, watercolor)
4. Share your result with friends

**Languages:** English, 中文, 日本語, 한국어, Español

**Creatures include:** Midnight Caffeine Beast, Social Chameleon, Keyboard Warrior Raptor, Buddha Jellyfish, Involution Cockroach, and more...

There's a feeding minigame too. Feed your creature 100 points to win.

Free to play. HD image unlocks cost $2.99 but you can also watch an ad.

🔗 https://xiaosheng6688.github.io/ai-human-zoo/

Would love feedback! What creature did you get?

---
# Reddit — r/WebDev (cross-post)
## Title
I built a single-file HTML personality quiz that generates AI creature images — looking for feedback on monetization

## Body
Single index.html file, no frameworks, no build tools. Just vanilla JS + Pollinations AI API for image generation.

Tech stack:
- Pure HTML/CSS/JS (one file)
- Pollinations.ai for creature images
- localStorage for state management
- GitHub Pages for hosting
- 5-language i18n system (en/zh/ja/ko/es)
- 30-question pool per language, 8 randomly selected each playthrough

Monetization: $2.99 PayPal unlock for HD images, ad-supported free tier.

What would you change? https://xiaosheng6688.github.io/ai-human-zoo/

---
# Product Hunt — Launch Copy
## Tagline
Discover your biological form in the digital age. AI-generated creature images, 5 languages, zero signup.

## Description
AI Global Human Zoo is a viral personality quiz that reveals what creature you've become in the digital era.

🧬 8 quirky personality questions  
🎨 6 art styles (Cyberpunk, Anime, Realistic, Pixel, 3D, Watercolor)  
🌍 5 languages (EN, 中文, 日本語, 한국어, Español)  
🦎 8 possible creature forms  
🖼️ AI-generated images via Pollinations  
🎮 Feeding minigame  
📊 Global leaderboard  
🔓 HD unlock $2.99 or free with ads  

No account needed. Just enter your name and go.

Built as a single HTML file. Vanilla JS, zero frameworks.

## Topics
Personality Tests, AI Art, Quizzes, Fun, Games

---
# dev.to — Article
## Title
I Built a Single-File AI Personality Quiz That Works in 5 Languages — Here's How

## Tags
#javascript #webdev #ai #tutorial #showdev

## Body
Last weekend I built AI Global Human Zoo — a personality quiz where AI generates your "creature form" based on your answers. It all lives in a single `index.html` file.

### The Tech
- **One file.** No React, no Vue, no build step. 100KB of vanilla HTML/CSS/JS.
- **5-language i18n.** Built a translation map object. Language detection from `navigator.language`. Full creature data, UI text, and question banks in each language.
- **Question deduplication.** localStorage tracks which questions you've seen. Pool of 30 per language, 8 sampled each playthrough — you won't see the same questions twice until you've exhausted the pool.
- **AI image generation.** Pollinations.ai API. Send a prompt, get back a unique creature image.
- **Monetization.** HD images locked behind $2.99 PayPal. Ad-supported free tier.

### Why a Single File?
Because deployment is just dragging it to GitHub Pages. No CI/CD pipeline, no environment variables, no `npm install`. It works.

### What I Learned
- English contractions in JS strings will ruin your day. 'I'm', 'haven't', 'don't' — escape them.
- `<button>` can't contain `<div>`. HTML spec, not optional.
- GitHub API (`gh api`) is more resilient than `git push` on restricted networks.
- Personality quizzes are inherently viral. People love sharing their results.

Try it and tell me what creature you got: https://xiaosheng6688.github.io/ai-human-zoo/

---
# Twitter/X — Thread
## Tweet 1
🧬 I built a personality quiz that uses AI to reveal your "biological form" in the digital age.

8 questions → AI generates your creature image.

Works in 5 languages. No signup. Totally free.

Try it: https://xiaosheng6688.github.io/ai-human-zoo/

(What creature did you get? 👇)

## Tweet 2
The 8 possible results:

🐺 Midnight Caffeine Beast
🦎 Social Chameleon
🐍 Procrastination Python
🦖 Keyboard Warrior Raptor
🪼 Buddha Jellyfish
🪳 Involution Cockroach
🧟 Notification Zombie
🪱 Meeting Parasite

Which one are you?

## Tweet 3
Built as a single index.html file.

No React. No build tools. Just vanilla JS + Pollinations AI.

Drag → GitHub Pages → Live.

Sometimes simple is better.

## Tweet 4
Tech breakdown:
• 5-language i18n (EN/ZH/JA/KO/ES)
• 30-question pool per language
• localStorage deduplication
• 6 art styles (cyberpunk/anime/realistic/pixel/3D/watercolor)
• PayPal monetization
• Feeding minigame

Source: https://github.com/xiaosheng6688/ai-human-zoo
