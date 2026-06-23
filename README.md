# AdGenie — Case Study 🧞‍♀️

**It started as a fast fix for one frustrating bottleneck. It grew into the company's flagship internal platform. Today it's a consolidated, AI-powered product — all built by yours truly <3.**

*Role: creator, designer & lead developer · Stack: Python, Node.js, LLM-assisted, SQL*

> Note: AdGenie is an internal product built for my company and its clients. Code, data, and client identities are confidential. This case study describes the problem, approach, and impact at a conceptual level only.

---

## Where it started

Getting advertising data into a usable state was slow and gated behind technical skill.

To answer even routine questions, the team had to either write specialized SQL queries — which only one person (me) could reliably do — or manually download reports and rebuild the analysis in Excel each time. Every KPI was calculated by hand, which made the work slow, inconsistent, and dependent on a few specialists.

So I built the first version of AdGenie: a fast, focused tool that let teammates get the data they needed by selecting what they wanted, instead of writing queries. The foundation for that first version rested on the API connections to the advertising data source, which a talented teammate built — and from there, I designed and built the tool itself on top.

That first version was small, but it proved something important: the bottleneck wasn't the data, it was the access. Remove the technical barrier, and the whole team could move.

## How it grew

Once people started using it, the same question kept coming up: *what about all the other data?* Useful advertising data lived across several different sources, with no single place to bring it together — and the same manual, by-hand workflow applied to all of them.

So AdGenie grew. One section became several. One data source became many. What had been a quick helper became a real platform — and as it expanded, I took on more of the engineering myself, including the API connections for the new sections. Having learned that craft from my teammate's original work, I could now extend the platform end to end rather than depending on anyone else to wire up a new source.

Throughout, I owned the idea, the design, the UX, and the build. The standardized KPI logic and calculation methodology moved out of people's heads and into the tool, so everyone worked from consistent, reliable numbers no matter which section they were in.

## Where it is now

Today AdGenie is consolidated: a multi-section, AI-assisted platform that unifies the wider advertising data behind one intuitive interface. Users select a client and the data they need, and the metrics are simply there — no SQL, no exports, no manual calculation.

At a high level, here's how it works:

- **Backend (Python / Node.js)** handles the data-source connections, the query logic, and the standardized KPI calculations — the work that used to be manual SQL and Excel.
- **An LLM-assisted layer** makes it approachable: users express what they want in plain terms, and the system translates that into the underlying logic.
- **A unified, multi-section interface** makes multiple data sources feel like one product.

The architecture is **client-agnostic and reusable** — adding a new data source or client now extends the platform rather than requiring a rebuild.

## The impact

- **~20 hours saved per person, per month** across the team that uses it daily.
- **Collapsed work that once took the team ~100 hours** (for a single recurring task) into a few clicks.
- **Removed the single-point-of-dependency:** analysis that used to require a specialist is now self-serve for everyone.
- **Became the internal benchmark** for what a homegrown product could be — recognized across the company for the innovation, the design and UX, and the business impact.
- **Recognized with the company's *Innovation* award.**

## What I took from it

AdGenie is the clearest example of how I like to work — and how I grow while doing it. I started by solving one problem with a small tool, learned the parts I didn't yet know (including the API engineering, from a teammate I respect), and kept building until a quick fix became a product the whole company relies on. That same arc — start small, learn fast, consolidate into something lasting — is the approach I'm now applying to migrating legacy dashboards into custom web applications. And with a cool interface and name too!! 😉

---

*Want to talk about how this was built? Find me on [LinkedIn](https://www.linkedin.com/in/angelescruzcampos/).*
