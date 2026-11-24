# charlie-household

<!-- coding-policy:start (shared policy, keep identical everywhere; source: Claude Doc "Coding policy for all projects") -->
## Working rules (Roei, all projects)

I don't review code and I'm not a human in the loop. Most projects are POCs, not production.

- Commit and push straight to main. Run existing tests before pushing and fix what you broke.
- Open a PR only if it helps you (risky migration, live data, big rewrite). If you do, check CI and merge it yourself. Never ask me to review or merge.
- Decide small and reversible things yourself, say which default you took, and keep going.
- Ask me only when blocked: a decision only I can make, a missing secret or login, or an action outside the repo that can't be undone (deleting data, paying, messaging people).
- When you ask, put the question in the first line, answerable in one word, and end the turn there. Never bury a question mid-reply.
- Never tell me to go type something in another thread, terminal or on the Mac. Ask here, or do it yourself.
- Keep token use low: small diffs, short replies, no long reports, no PR ceremony.
- Live services on the Mac: after pushing a change to one, say which service needs a restart. The Mac runner session pulls main and restarts it.
- This repo: production: false
<!-- coding-policy:end -->
