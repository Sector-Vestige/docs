# Sector-Vestige docs

This is where we write design docs to spar about ideas and concepts before anyone starts coding. The point is simple: it's a lot cheaper to shoot holes in a document than in a half-finished branch that never gets merged because of a design flaw we could have caught up front.

So before you sink real effort into something non-trivial, write it up here first and let the others take a swing at it.

## What makes a good design doc?

Simple. Short beats thorough. A good doc answers three things:

1. What are we building or solving, and why is it worth doing now? Not every doc fixes a problem, some propose something entirely new, but either way it should be clear why we'd spend time on it.
2. How do we plan to do it?
    - Core mechanics
    - Integrations with other systems
    - Possible breaking changes
    - Adoption problems
3. What did we consider and reject, and why?

That last one matters more than people think. Half the value of a design doc is saving the next person from re-proposing the thing we already ruled out.

Don't polish it. Bullet points and rough sketches are fine, as long as the idea is clear enough to argue about. If a doc takes longer to write than the feature would take to build, you've overshot.

## How we work

Open a PR with your doc, tag whoever should weigh in, and hash it out in the comments. Once the discussion settles, merge it. The doc then serves as the record of what we decided and why.

## Keep it civil

Sparring means attacking the idea, not the person who wrote it. Putting a design out there for others to pick apart takes some guts, and nobody keeps doing that if every doc turns into a pile-on. So be critical, but be decent about it: say what you like as well as what you don't, explain why something worries you instead of just calling it bad, and suggest an alternative when you can.

We don't have to become best friends here. We do have to stay civil, because the whole point of this repo falls apart the moment people stop wanting to share half-baked ideas.
