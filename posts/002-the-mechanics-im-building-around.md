# 002 — The Mechanics I'm Building Around

I said in the last post that this game is about someone climbing out of a depressive state while chasing a lost song. The harder design problem underneath that sentence is: how do you make a player *feel* that, instead of just reading about it? I didn't want dialogue trees or narration doing the emotional work — if the story only exists in text boxes, the player is watching the protagonist's state, not sharing it. So the mechanics themselves had to carry the weight. Here's where that's landed so far.

## Friction as emotional state

Early on, everything the protagonist does is a little too hard. Walking is slow. Opening curtains, making coffee — small actions that should be nothing — take a beat longer than they should, communicated entirely through the controls: input delay, sluggish animation, a hold-to-interact that used to be a tap. Nothing is explained. The player just feels like the world has more resistance in it than it should.

That resistance eases over time, but not on a timer or a cutscene trigger — it's tied to the player actually engaging with small tasks. Do the thing enough times, and the thing gets a little lighter. Progress is something you feel in your hands before you'd ever think to name it.

## Two layered spaces

The game moves between the physical world — an apartment, a city — and a second space: an in-game recreation of an old internet forum/browser interface, accessed by sitting down at a computer. The physical space is where the friction mechanic above lives. The digital space is where the actual investigation happens: reading archived threads, following dead links, piecing together who said what about this song and when.

I like this split because it lets the game be about reading without being about talking. Nobody the protagonist encounters online is a character you have a conversation with — they're a voice in a thread from years ago. The story arrives as found text, not dialogue.

## AI restoration as the central choice

This is the mechanic I've spent the most time thinking through. The protagonist has access to a modern AI tool that can reconstruct corrupted or missing pieces of the lost song. It's fast, and what it gives back is complete and plausible-sounding. It's also not necessarily *true* — it's filling gaps with something that sounds right, not something that is.

The alternative is slower: real archived fragments, secondhand accounts from people who were actually there, pieces that stay incomplete because that's what's actually left. The player is repeatedly put in the position of choosing between the two. Neither choice is flagged as "correct" in the moment — the AI version genuinely sounds better, most of the time.

This is doing double duty. Mechanically, it's the most interesting decision point in the game. Thematically, it's the whole point: the pull toward a complete, comforting, manufactured answer over an incomplete but real one is not just about a song.

## A hidden authenticity meter

How often the player leans on the AI shortcut versus does the real digging is tracked quietly, with no number shown anywhere in the UI. It determines which of several possible endings the player reaches. I don't want this to read as a score to optimize — there's no "good ending" flagged as the intended one going in. It's meant to reflect back a pattern the player didn't necessarily notice they were building.

## Still unresolved

The day-to-day loop structure — how many discrete "days," how content is paced across them — isn't locked yet, and neither is exactly what this song means to the protagonist personally. Those are next.
