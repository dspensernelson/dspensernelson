# Spenser Nelson

Chicago-based AI and automation consultant, currently Senior Consultant at rGen Consulting. I am also an MPP candidate at DePaul with a certificate in Energy Policy and Management, expected 2027. The energy-policy work below grew out of that study.

I direct the build, set the standard it has to clear, then figure out how to prove it cleared it. Most of the work is in that last part. Getting a model to produce something that runs is easy now. Knowing whether it is right, and still knowing after you have stopped watching, is not.

### [Roy R. Fisher](https://github.com/dspensernelson/roy-r-fisher-app)

A Windows desktop app for producing commercial appraisal reports, built for one appraiser who has written them in Word for decades. It has a Python server and React interface and runs locally on a single machine.

The app creates a job from a form and lays down his own eight folders on disk, named the way he names them. It reads what has actually arrived in those folders and shows it against what the report still needs. It proposes the sections required for the kind of appraisal and currently builds the subject photo pages into a real Word file.

[`HOW-WE-WORK.md`](https://github.com/dspensernelson/roy-r-fisher-app/blob/main/HOW-WE-WORK.md) is the standard the build has to clear. Never state a fact the app cannot observe, because a blank costs the appraiser ten seconds and a confident wrong answer reaches a client. Never generalize from one example. Point at where a value lives rather than copying it, because a copy drifts and then quietly lies.

The rules keep the failures that produced them visible. A title page that looked wrong against one report matched seven of the other nine. A brand color sat wrong for months because it was written out instead of pointed at.

### [Baseload Capacity Gap](https://github.com/dspensernelson/Baseload-capacity-gap)

Live at [baseload-capacity-gap.vercel.app](https://baseload-capacity-gap.vercel.app/).

A public visualization of the American nuclear-capacity gap. Every public number has a recorded formula and source, with the core fleet data anchored in NRC and EIA records. Scheduled GitHub Actions workflows keep the underlying data current.

Once a week, the system independently recomputes its headline figures from atomic rows and compares them with the live view. A pipeline that runs is not necessarily a pipeline that is correct. The weekly reconciliation is what makes that difference visible.

### [SignalFlow Lab](https://github.com/dspensernelson/SignalFlow-Lab)

Live at [signal-flow-lab.vercel.app](https://signal-flow-lab.vercel.app/).

A React app for practicing workplace automation through fictional operating workflows. Learners inspect source material, transform messy inputs, make approval decisions, and assemble usable artifacts instead of clicking through explanations.

It started as a question about how far a model could be pushed to build and how much judgment could be made explicit before it began. The specs and red-team cases defined the bar before implementation. The decision log and acceptance punchlists record whether each slice cleared it.
