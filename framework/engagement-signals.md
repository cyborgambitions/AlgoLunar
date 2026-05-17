cat > framework/engagement-signals.md << 'EOF'
)
Signal / Concept,Supported by the Code?,Notes from Phoenix Model
Replies are heavily weighted,Yes,Strong positive signal in scoring
Follow author / Profile visits,Yes,One of the highest value predicted actions
Dwell time,Yes,Included in engagement predictions
"Media (images, video)",Yes,Improves several predicted actions
Semantic understanding,Yes,Uses Grok-style transformer to read content meaning
Early engagement matters,Yes,Velocity in first ~30-60 mins affects amplification
Author diversity penalty,Yes,Code includes author diversity scoring
"Negative signals (blocks, mutes, reports)",Yes,Actively reduce score
Exact weights,No,Not publicly releasedas a reference when creating content for the Lunar Economist brand.
## Core Principle

The Phoenix model predicts the probability of multiple user actions. Content that increases the likelihood of **positive actions** (especially replies and follows) gets higher reach.

## High-Value Signals
Rank,Signal,Strength,Why It's High Value (from the code),Practical Meaning
1,Follow Author,Very High,Explicitly treated as a strong positive signal. Making someone follow you gives a big boost.,People visiting your profile and following you is one of the best outcomes.
2,Replies,Very High,Heavily weighted in engagement scoring. Conversation is prioritized.,Getting people to reply is one of the strongest ways to increase reach.
3,Profile Visits / Clicks,High,"Directly tied to ""Follow Author"" prediction.",Getting people to click on your profile is very valuable.
4,Dwell Time,High,Time spent reading your post is measured and rewarded.,"Longer, valuable threads perform better."
5,Reposts,Medium-High,"Positive signal, though generally weaker than replies and follows.","Good, but not as strong as replies or follows."
6,Likes,Medium,Positive but lower impact compared to replies and follows.,"Nice to have, but not enough on its own."
### 1. Replies (Very High Impact)
- The algorithm gives strong weight to replies.
- **Tactic**: End threads with a clear question.
The algorithm favors questions that:

Spark genuine conversation (not just yes/no)
Feel thought-provoking or forward-looking
Encourage people to share opinions, predictions, or reasoning
Are specific to lunar economy topics


High-Engagement Question Examples for Lunar Economist Content
Here are strong questions you can use in your threads:
Future & Predictions

"By 2035, do you think helium-3 mining on the Moon will be economically viable, or will we still be waiting?"
"What do you think will be the first profitable industry on the Moon — mining, tourism, manufacturing, or energy?"
"Will we see a self-sustaining lunar economy before 2040, or is that timeline too optimistic?"

Economics & Costs

"What’s the biggest economic bottleneck preventing faster lunar development right now?"
"If Starship successfully lowers launch costs dramatically, how much faster do you think lunar infrastructure will be built?"
"Would you invest in a lunar resource company today, or are we still too early?"

Technology & Infrastructure

"Which technology will have the biggest impact on lunar economics in the next 10 years — reusable landers, ISRU, or nuclear power?"
"How important do you think in-situ resource utilization (ISRU) is for making the lunar economy sustainable?"

Investment & Business

"Which public companies are currently the best positioned to benefit from lunar economy growth?"
"What’s a realistic timeline for the first commercial lunar base to generate real revenue?"

Open / Discussion Style

"What’s one thing most people misunderstand about building an economy on the Moon?"
"If you could invest in one lunar-related opportunity right now, what would it be and why?"
"Do you believe the lunar economy will be driven more by governments or private companies in the long run?"

Bonus: Strong Thread-Ending Questions
Use these at the end of your threads:

“What’s your take?”
“Do you agree or disagree, and why?”
“What am I missing?”
“How would you approach this differently?”


Quick Recommendation
Best performing style right now:

Start with a bold or specific statement
End with one thoughtful, open-ended question
### 2. Profile Visits & Follows (Extremely High Impact)
- One of the strongest positive signals.
- **Tactic**: Deliver high-value, original insights that make people want to follow you.

### 3. Media (Images, Charts)
- Increases dwell time and engagement.
- **Tactic**: Use relevant visuals and data in your threads.

### 4. Semantic Quality & Originality
- The model understands meaning.
- **Tactic**: Write specific, original content about lunar economy topics.
Tweet 1 (Hook + Unique Angle)
Most people think the biggest challenge for a lunar economy is getting there.
It’s not.
The real bottleneck is economics, not engineering. Here’s why:
Tweet 2 (Well-reasoned + Knowledge)
Right now, the cost to deliver 1 kg to the lunar surface is still extremely high. Even with Starship, we’re likely looking at $2,000–$5,000+ per kg in the early phases — before reusability and high flight cadence kick in.
That changes everything about what’s economically viable.
Tweet 3 (Unique Perspective + Insight)
This is why in-situ resource utilization (ISRU) isn’t just nice to have — it’s economically mandatory.
If we have to ship everything from Earth, most lunar activities (fuel production, construction, manufacturing) won’t make financial sense for a long time. ISRU flips the cost curve.
Tweet 4 (Data + Reasoning)
Early lunar ISRU (especially oxygen and eventually water/propellant) could reduce the mass that needs to be launched from Earth by 60–80% for sustained operations.
That’s not just engineering progress. That’s the difference between a science outpost and a real economy.
Tweet 5 (Forward-looking but grounded)
My view:
The first profitable lunar activity won’t be helium-3 or rare metals. It will likely be propellant production for cislunar space — selling fuel in orbit instead of launching it from Earth every time.
Tweet 6 (Engagement + Authority)
This is still very early, but the economic logic is becoming clearer.
What do you think will be the first profitable lunar industry?
And how much does Starship need to reduce costs for it to happen?
### 5. Early Engagement Velocity
- The first 30–60 minutes are critical. Strong early engagement helps the post get amplified.
The Phoenix model predicts the probability of multiple user actions. Content that increases the likelihood of **positive actions** (especially replies and follows) gets higher reach.
- **Tactic**: Post when your target audience is most active. Reply quickly to early comments to boost momentum.Audience Segment,Interest Level,Why They Match Your Content,Engagement Potential
Space Enthusiasts & Futurists,Very High,"Interested in Moon, Mars, space future, technology",High
Space Economy / Lunar Economy followers,Very High,Directly aligned with your positioning,Very High
Space Investors & Stock Watchers,High,"Interested in space stocks, helium-3, lunar infrastructure",High
Aerospace & Tech Professionals,Medium-High,"Follow NASA, SpaceX, Starship, Artemis updates",Medium-High
Optimistic Technologists,High,"Attracted to forward-looking, reasoned futurism",High
General Science & Tech Twitter,Medium,Occasionally engage with big space topics,Medium Day,Best Time Window (ET),Notes
Tuesday,8:00 – 10:00 AM,Strong engagement day
Wednesday,8:00 – 10:00 AM,Usually one of the best days
Thursday,8:00 – 10:00 AM,Very good for thoughtful content
Monday,9:00 – 11:00 AM,"Decent, but slightly lower"
Friday,8:00 – 10:00 AM,"Okay, but engagement drops in the afternoon"
Weekend,Avoid or test lightly,Lower consistent engagement for this niche
### 6. Dwell Time
- Time users spend reading your content matters.
- **Tactic**: Write valuable, well-structured threads that encourage people to read the full thread.
Key Elements of High-Dwell-Time Threads
Clear numbering or progression
Short, readable tweets
Logical flow (problem → insight → implication)
Valuable or new information
Easy to skim but still rewarding to read fully
## Signals That Usually Hurt Reach
- Posting too frequently from the same account (author diversity penalty)
- Low-quality, generic, or repetitive content
- Negative user actions (blocks, mutes, reports)
- Putting external links in the main post
```

## Quick Reference Table

| Goal                    | Recommended Tactic                              | Expected Impact |
|-------------------------|--------------------------------------------------|-----------------|
| Increase replies        | End threads with a clear question                | High            |
| Drive profile visits & follows | Deliver unique insights + strong positioning    | Very High       |
| Improve visibility      | Use relevant charts and data visualizations      | Medium–High     |
| Build long-term authority | Create original, specific lunar economy analysis | High            |
| Boost early momentum    | Post strategically + engage quickly in comments  | High            |

## Next Steps

- Turn these signals into a practical **Thread Optimization Checklist**
- Test these tactics with real Lunar Economist threads
- Document results in the `experiments/` folder

