# Day 15

Two previous 2 bugs got triaged today, and I also reported 2 fresh ones. On my Discord server, I shared in `#collab` that I’m open to teaming up with hackers who have access to anything valuable — something that benefits both sides. Got a few DMs, and one stood out: a top bug hunter who's currently ranked #1 on his program and has made serious money there. 

We're planning to collaborate for 1 week. I don’t have access to his program yet, but we discussed one of his recent submissions. The customer said they might invite me on Monday. Until then, we’re staying in touch. I'm excited for this collab — not just for the bugs, but to understand his mindset, how he thinks, and the questions he asks. My goal is simple: spend 20 focused hours on his app in 7 days and see what we can pull off before he moves on to the next program.

One of my friends also found a solid lead on a Bugcrowd private program and sent it to me. I dug into it, investigated the flow, and managed to find a legit bug — always thankful for friends who share leads.

In the morning, I was on a Google Meet with a senior security engineer I’ve known for 4 years. He works at [REDACTED] and earns $120k/year. He was working on a pentest but only found a few low-priority (P4/P5) bugs. I jumped in just to see what a real pentest project looks like. Opened Burp, shared my screen — and within 45 minutes, I found 4 IDORs and a few more bugs. Total 7 bugs in less than an hour.

It was a GraphQL-based app. The `tripID` was being generated using date and time — super predictable. You pass that ID in the query and it returns Stripe secret tokens. Used ChatGPT to play with that token, and it ended up leaking full user billing details. He was stunned seeing how fast I hunted. I told him — we are machines, SIRRRR. We *smell* bugs 😤

---

### 🧠 Motivation  
https://x.com/TeslaTheGod/status/1915402785006162351

### 📚 Learning  
https://x.com/XHackerx007/status/1915587780010234032

### 🏋️‍♂️ GYM  
Chest day. Felt strong. Felt proud.

### 💊 Supplements  
Posted on X I take Ashwagandha + Magnesium. Helps me sleep better and stay calm throughout the day. Before taking any supplements consult with your Doctor.

See you Tommorow :)
