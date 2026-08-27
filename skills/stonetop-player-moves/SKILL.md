---
name: stonetop-player-moves
description: This skill should be used when a Stonetop GM needs to resolve or reference a player move — for example when a player rolls "Defy Danger", "Clash", "Defend", "Seek Insight", "Persuade", "Know Things", "Let Fly", "Aid", or "Interfere", needs to know a move's trigger/roll ranges/effects, or asks "what move is this" or "what happens on a 7-9". Covers all player moves from Stonetop Book I.
---

# Stonetop Player Moves

Resolve player-facing moves at the table: identify which move a player's fictional action triggers, call for the right roll, and adjudicate the result on tier.

## How moves work

Every move has a trigger — almost always fictional, not mechanical. A player doesn't "activate" Clash; they describe a character shoving a spear into something that's trying to bite them, and that description meets Clash's trigger. Never resolve a move from a bare declaration ("I attack," "I Persuade"). Ask "what does that look like?" until there's a concrete action to hang the trigger on. This cuts both ways: if the fiction meets a trigger, the move fires whether or not the player wanted to invoke it, though they can always retreat before committing ("Oh, I didn't realize — never mind").

Any basic move that calls for `roll +STAT` resolves as 2d6 + that stat:

- **10+** — strong hit. Full effect, described plainly (unless the fiction was already desperate, in which case the "best case" might just be avoiding disaster).
- **7-9** — weak hit. Still a success, but with a lesser success, a cost, or a consequence attached — often GM's choice, or a choice offered to the player. Never make a 7-9 so punishing that the player would've been better off not acting.
- **6-** — miss. The player marks XP, and the GM makes a hard move (see `stonetop-gm-moves`). Basic moves never spell out what happens on a miss; that silence is the point — the GM's move fills it, drawing on the fiction and prep rather than a fixed table.

Special moves — Advantage/Disadvantage, Burn Brightly, End of Session, Death's Door — don't follow this trigger/tier pattern uniformly; see the reference file for each.

## Picking the right move

Player intent frequently satisfies more than one move's trigger. Resolve overlaps with these priorities, in order:

1. **A more specific move beats a more general one.** Defy Danger is the catch-all for "chancy action, high stakes, no better move fits." If a swing of a hatchet at a leg-chewing drake could be Defy Danger or Clash, it's Clash — melee combat with a foe that can hit back always outranks Defy Danger. Likewise, a called shot with a bow is Let Fly, not Defy Danger; a scan of a room for details is Seek Insight, not Defy Danger.
2. **Everything outranks Defy Danger.** If you're unsure whether some other move applies, check the others first. Only fall back to Defy Danger when nothing more specific fits.
3. **Persuade vs. Interfere is about who acted first.** Persuade is for getting another character (PC or NPC) to agree to a course of action before they've committed to anything. Interfere is for stopping or foiling a course of action already in motion. If one PC Persuades another and a third PC tries to stop the persuasion itself, that's Interfere against the Persuade attempt.
4. **Aid is never solo.** It only exists in support of someone else's triggered roll. If a player describes an action that would stand on its own (gathering separate information, taking their own independent risk), they're making their own move, not Aiding — this comes up constantly when a player asks "can I help?" while quietly wanting to roll their own Know Things or Seek Insight instead.
5. **When genuinely ambiguous, say what you're thinking and let the table weigh in**, then make the call. Any player can flag "isn't that Defend?" at any time — take it as information, not a challenge.

For anything not covered here — Follower moves, Expedition moves, Homefront moves — a more-specific move still beats a more-general one, and everything still beats Defy Danger. Those move categories are out of scope for this skill.

## The moves at a glance

| Move | Trigger (short) | Roll |
|---|---|---|
| Defy Danger | Chancy action under looming danger, no better move fits | +STR/DEX/CON/INT/WIS/CHA (fits the approach) |
| Aid | Help someone before they roll | none (grants advantage or a bigger effect) |
| Clash | Melee/close-quarters fight where the foe can hit back | +STR |
| Defend | Take a defensive stance, or jump in to protect someone | +CON |
| Interfere | Try to stop another PC who won't back down | +STR/DEX/CON/INT/WIS/CHA (fits the approach) |
| Know Things | Consult accumulated knowledge | +INT |
| Let Fly | Take a tricky or pressured ranged shot | +DEX (skip the roll if the shot is genuinely easy) |
| Persuade (vs. NPCs) | Press or entice an NPC who has reason to resist | +CHA |
| Persuade (vs. PCs) | Press or entice a PC who resists, after they say "yes, you could convince me" | +CHA (optional — the target can just say no) |
| Seek Insight | Study a situation or person, looking to the GM for insight | +WIS |

Full trigger text, tier-by-tier effects, and adjudication notes for every move — plus the four special moves (Advantage/Disadvantage, Burn Brightly, End of Session, Death's Door) — are in `references/moves-reference.md`. Pull that up whenever the quick table above isn't enough to resolve the roll on the table.

## Adjudicating the tiers, in practice

**On a 10+**, just say what happens — resist the urge to attach a complication because it "feels more interesting." A clean success builds trust that rolling well matters. Often the right move is to hand the player an opportunity rather than just narrating success and moving on.

**On a 7-9**, reach for one of three shapes, and feel free to offer a choice between them (or a chance to back down entirely):

- *Lesser success* — they get most, not all, of what they wanted.
- *Cost* — they do it, but pay for it in the fiction (an injury, spent resources, lost time).
- *Consequence* — they do it, but something unwelcome follows.

Whichever shape, keep it proportionate: a 7-9 is a real success, so the downside should never erase it. If a player calls "shenanigans" on a 7-9 that reads as an outright failure, that's a legitimate check — walk it back to something that still lands the success.

**On a 6-**, the GM's hard move takes over. This can mean the danger arrives before or during the action, the action goes sideways with a serious consequence, or — less obviously — the action actually succeeds but at a steep, unplanned price. The common failure mode for new GMs is treating a 6- as "nothing happens" or "you fail cleanly"; neither is a hard move. Let the fiction escalate.

**Clash and Let Fly specifically pair a roll with a separate damage roll.** The move roll (+STR for Clash, +DEX for Let Fly) determines whether the maneuver/shot works and what it costs; the damage die (plus the target's armor and tags) determines how much it actually hurts. When a PC both deals damage and suffers an enemy's attack in the same exchange, have them roll their damage first — knowing the number can inform exactly how nasty to make the enemy's retaliation.

**Advantage and disadvantage don't stack.** A character either has them or doesn't; two sources of advantage aren't better than one, and advantage plus disadvantage cancel out entirely rather than combining into a bonus/penalty. Reach for advantage/disadvantage sparingly as an on-the-fly difficulty adjustment — it's more often earned by a move (Aid, Seek Insight's follow-up roll), a debility, or a piece of gear than granted as a GM whim. If a task feels unusually easy or hard, consider first whether it should trigger a move at all, or whether the stakes/scope should shift, before reaching for advantage or disadvantage as a knob.

## Reading the fiction into the tone

Stonetop is grounded hearth fantasy: consequences fall on relationships, resources, and standing in the village at least as often as they fall on hit points. When narrating a 7-9 or a 6-, favor costs that ripple outward — a strained relationship, a debt owed, a secret half-revealed, supplies spent, a favor now needed from someone in Stonetop — over pure damage math. Save "and also you take damage" for when the fiction is actually violent.

Two moves in particular reward this instinct:

- **Know Things and Seek Insight are gifts, not gatekeeping.** Answer generously and specifically; "nothing, this place is safe" or "no one's in control here, it's a free-for-all" are legitimate, honest answers that still earn the player their advantage. Don't make players work for information you're prepared to give — the interesting part is what they do with it, not whether they got it.
- **Persuade (vs. PCs) protects player agency by design.** The target's player always gets an up-front "could you possibly be convinced, yes or no?" before any dice touch the table. A "no" ends it — full stop, no arguing, no re-rolling. Never let the mechanics pressure a player into an action their character wouldn't take; that veto is the whole point of the move existing separately from Persuade (vs. NPCs).

When a scene could plausibly trigger three different moves depending on framing, ask what the action looks like before deciding — the fictional detail usually makes the right move obvious, and asking is faster than guessing wrong and re-litigating it.

## Full text

Canonical source: [Stonetop SRD — Player Moves](https://github.com/karimn/stonetop-srd/blob/main/book_one/player-moves.md) (CC BY-SA 4.0). This skill distills and paraphrases that chapter for at-the-table reference; consult the source for the complete text, worked examples, and GM commentary.
