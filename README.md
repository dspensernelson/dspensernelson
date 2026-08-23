## D. Spenser Nelson

Chicago. AI and automation consultant, currently Senior Consultant at rGen Consulting. MPP candidate at DePaul with a certificate in Energy Policy and Management, expected 2027, which is where the energy work below comes from.

I direct the build, set the standard it has to clear, then figure out how to prove it cleared it. Most of the work is in that last part. Getting a model to produce something that runs is easy now. Knowing whether it is right, and still knowing after you have stopped watching, is not.

### [Roy R. Fisher](https://github.com/dspensernelson/roy-r-fisher-app)

A commercial appraisal firm runs on this. Windows, offline, one machine, one user, and the output is a signed report that goes to a client.

[`HOW-WE-WORK.md`](https://github.com/dspensernelson/roy-r-fisher-app/blob/main/HOW-WE-WORK.md) is the standard the build had to clear. Never state a fact the app cannot observe, because a blank costs the appraiser ten seconds and a confident wrong answer reaches a client. Never generalize from one example. Point at where a value lives rather than copying it, because a copy drifts and then quietly lies. Every rule has the failure that produced it written next to it.

### [Baseload capacity gap](https://github.com/dspensernelson/Baseload-capacity-gap)

Live at [baseload-capacity-gap.vercel.app](https://baseload-capacity-gap.vercel.app).

Every number traces to an NRC or EIA primary source, and it refreshes on 11 GitHub Actions crons. Once a week it re-derives its own figures from those sources and checks that they still match. A pipeline that runs is not a pipeline that is correct, and the weekly re-derivation is what turns that difference into something I can see.

### [SignalFlow Lab](https://github.com/dspensernelson/SignalFlow-Lab)

Live at [signal-flow-lab.vercel.app](https://signal-flow-lab.vercel.app).

A React app for practicing workplace automation, built on a fictional energy-market workflow. It started as a question about how far a model could be pushed to build and to think. The specs, decision logs, and red-team cases in it are the standard the build had to clear, written before the build.

---

What I add is upstream of the code: deciding what done means, what correct means, and what counts as evidence.
