# A Better Web: Notes on Attention, Trust, and Honest Tools

*A conversation exploring platform manipulation, content quality, and the philosophy of a better media system.*

---

## The Problem with Platform Engagement

Modern platforms like YouTube and Reddit are structured like fishing nets — they capture large audiences by offering genuinely good content early, then gradually exploit that audience for profit. The degradation is slow and deliberate, like boiling a frog. Users join because the content is good, but standards erode incrementally until low-quality content feels normal.

Platforms systematically dismantle the signals users need to distinguish quality from slop:
- Removing public dislike counts
- Replacing chronological feeds with algorithmic ones
- Burying "not interested" controls deeper in menus
- Hiding critical comments

Each change seems minor in isolation. Cumulatively, users are disarmed.

---

## Platform UX Bloat Is Spam

Spam lies to steal your attention. So does clickbait. They are functionally identical — both unsolicited, both deceptive, both deliver something other than what was promised.

Much celebrated "engagement" UX is sophisticated spam in disguise:
- Infinite scroll
- Autoplay
- Notification badges
- Algorithmic feed injection

Popups were universally rejected and blocked. But when they put on glasses and a mustache — as autoplay video, notification prompts, and cookie banners designed to make "accept all" the easy button — we collectively forgot we'd already had this conversation.

Gratuitous sound effects (fart sounds, wheezing laugh tracks) in short-form video are audio popups — unsolicited sensory interruptions designed to hijack attention.

---

## A Better System: Core Philosophy

### Binary Signals Over Complex Metrics

Humans already have fast, accurate, intuitive quality detectors. A baby doesn't deliberate — it makes a face or it doesn't. That reaction is pure, uncontaminated signal.

The mistake platforms make is over-engineering feedback mechanisms, which degrades signal quality:
- Five-star ratings cause agonizing over 3 vs 4
- Visible upvote counts introduce social proof contamination before you vote

Better signals are simple:
- Finished it / didn't finish it
- Recommend / don't recommend
- Relevant / not relevant

Every additional step between gut reaction and captured signal is data loss.

### Cryptographically Secured Peer Reviews

Reviews should be cryptographically signed, tied to real identities in a personal trust graph. This solves fake engagement at a fundamental level — botted likes are easy, but forging signed reviews from trusted peers at scale is not.

If everyone you trust likes something, you'll probably like it. If everyone you trust avoids something, you know to skip it without wasting attention. The trust graph is yours — no algorithm decides whose opinion gets weighted.

### A Semantic Descriptor Lexicon

A shared vocabulary for content quality — precise enough to be actionable, neutral enough to mean different things to different people:

**Pacing & Structure**
- Buries the lead
- Excessive preamble
- Clickbait mismatch between title and content

**Production Choices**
- Gratuitous sound effects
- Artificial tension padding
- Excessive jump cuts

**Intellectual Honesty**
- Overstates conclusions
- Cherry picks data
- False balance

**Presentation Style**
- Performative outrage
- Condescending to audience

Critically, descriptors are neutral data — the trust graph determines how they're weighted per individual. What deters one person attracts another. The end user is the judge. People aren't stupid; they've been lied to in order to lower their standards.

The lexicon itself can be community-developed and peer-reviewed using the same trust mechanism, evolving organically rather than being handed down by a platform.

### This Is a Semantic Spam Filter

Early spam filters were syntactic — matching specific words. Bayesian filters understood context and patterns. A descriptor lexicon is training data for a semantic content filter that understands *why* something is low quality, not just surface features. Because it's built on a personal trust graph rather than a central authority, it can't be gamed the way spam filters eventually get gamed.

---

## The Technical Vision: An OS-Level Network Experience

The ideal system extends how computing hardware already works. Memory operates at different speeds and vicinities to processors:

- Registers/cache — tiny, fast, close to CPU
- RAM — larger, slightly further
- SSD/HDD — much larger, slower
- Network storage — vast, most distant

An OS abstracts all of this seamlessly. A network OS extends that hierarchy further outward — local device, edge servers, distributed storage — with the user not needing to care where in the hierarchy their data or compute lives at any moment.

This reframes the power dynamic entirely. You're not a user of YouTube's platform. You're an owner of data choosing to render it through a particular compute resource. Platforms become specialized compute resources you temporarily leverage, not walled gardens that capture and hold your data.

### The Open Web Already Exists

RSS feeds, independent blogs, Bandcamp, Substack, the Fediverse (ActivityPub, Nostr, PeerTube) — these are all "open sea" spaces where the creator-audience relationship is direct and honest. The platforms didn't replace them; they made their walled gardens convenient enough that people stopped swimming out.

The central design question: **how do you make the open sea accessible without turning it into another shallow harbor?**

---

## The Pen

A pen is a simple tool, but can be used to move mountains and raise civilizations. Nobody demands the pen second-guess what you're writing or inject suggested words.

The pen's power comes from simplicity and honesty. It captures exactly what you intend, nothing more, nothing less. No agenda between thought and page.

The proposed system is a pen for human taste and judgment about media. Simple, honest, faithful capture of what people already naturally think — then letting those signals accumulate and connect through a trust graph the way written ideas accumulated through libraries and universities.

**The platforms built slot machines when they should have built pens.**

The pen outlasted every empire that tried to control it.

---

## Strategic Considerations for Building This

The hardest problem isn't technical — it's surviving long enough to reach critical mass. Google and Microsoft buy out or force out competition. Moat strategies worth considering:

- **Open source the core protocol early** — buying you out doesn't kill the project
- **Build unsexy infrastructure first** — consumer-facing layers attract attacks; protocols fly under the radar longer (nobody bought SMTP or HTTP)
- **Developer adoption before user adoption** — technical social capital is sticky
- **Network effects that resist centralization** — like email or the web itself, not like Facebook
- **Legal structure that resists hostile acquisition**
- **Build community ownership** — people defended Linux, Wikipedia, and Firefox with genuine passion because they felt ownership

The social capital moat may matter as much as the technical one.

---

## Status

This system is on the roadmap. The idea is solid enough not to be rushed — it's grounded in human nature rather than current technology trends, which makes it durable. The thinking done today will still be valid when the time comes to build.

*"The mustache keeps changing. The intent doesn't."*
