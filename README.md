# cat-walk

Cats walking across my GitHub contribution graph, 2025-08-31 → 2026-08-22.

The graph is a 7×52 bitmap: seven rows for the days of the week, one column per
week, five shades of green. This draws an 11×7 cat sprite into it three times —
one per beat of a walk cycle — and then sits the cat down at the end.

The sprite fills all seven rows, so there's no vertical room to bob the body.
The motion instead comes from the legs (four of them, on fixed alternating
columns, with different pairs lifted each frame — a diagonal trot) and from the
tail, which stands up on the outer two frames and swishes down on the middle one.

Every square is a backdated commit, `GIT_AUTHOR_DATE` and `GIT_COMMITTER_DATE`
set to the day it needs to land on. This is
[gitfiti](https://github.com/gelstudios/gitfiti)'s trick, hand-rolled.

It is art, not activity. Every one of these commits was pushed on the same
afternoon, and the repo is younger than the commits it contains.
