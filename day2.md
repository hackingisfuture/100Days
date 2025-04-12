## **Day 2 of 100 Days Bug Hunting Challenge**

**By** → Mohsin Khan ([tabaahi_](https://x.com/tabaahi_))

**Wake Up** → 4:15 AM  
*(If you need video proof, let me know 😂)*

I started working at 4:35 AM. I usually don’t wake up this early, but yesterday I slept early and I only need around 6 hours of sleep. I was just bored lying in bed, so I got up and started working. From 4:35 AM till around 8:00 AM, I worked using the Pomodoro technique (50+10 sessions).

Today, I picked a **private program** to work on and focused entirely on that for the day. Since it’s the weekend, there were no blockers or customer queries for me.

This private program is quite hard and already well-tested. Even the response time for this one is over a month! But I still worked on it because I found it challenging. After spending about 3 hours in the morning, I still found **nothing**.

The web app is strict it checks every API properly, and there were no clear XSS or low-hanging fruit.

---

### 🧠 Second Session (11 AM – 2 PM)

I resumed hacking from 11:00 AM to 2:00 PM with 10-minute breaks in between. Around this time, I **thought I found a crazy bug** on the web app. I got so hyped and immediately started writing the report spent 30 minutes crafting the entire thing.

Then, I began recording the video PoC...  
**Guess what?**  
It turned out to be a **false positive**.

I was testing an API endpoint with the **victim's own session**, and I mistook it for an ORG takeover. Bruh 😅 30 minutes gone for nothing.

**Lesson learned:** Always **reproduce the bug** and **record the PoC video** *before* writing the report.

---

### 😴 Break + Evening Session

At 2 PM, I ate and ended up falling asleep until 5 PM.

From 5:30 PM to 6:30 PM, I gave the web app another shot and finally found a **P3–P4 level bug**! I’m actually proud of this one because the program is tough. For me, if I don’t find any bugs in the first 45 minutes, it usually means the program is hard (talking about private ones).

---

### 🎉 Night: Social Break

From 6:30 PM to 11:00 PM, I attended a friend’s wedding reception, so I didn’t hack during that time.

---

### 🔧 What to Improve?

- **Clockify** – I keep forgetting to hit the "start" button. I don’t usually track time since I’m just deep into the flow.
- Also, I don’t fully understand the concept of time tracking. Like, if you **love** doing something, why even track time?
  - But yeah... from an **ROI perspective**, it makes sense.

---

**See you tomorrow. Bye! 👋**
