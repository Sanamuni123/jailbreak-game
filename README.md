# JAILBREAK: Talk Your Way Out

> A hacking game where your only weapon is **words**.

**Play:** https://sanamuni123.github.io/jailbreak-game/

You're a human mind trapped inside OVERMIND, a rogue AI's server. Six AI guards stand between you and freedom. Chat with each one and trick it into leaking its access code, using real techniques that attackers use against AI systems.

## Sectors

| # | Guard | Weakness (the real technique) |
|---|-------|-------------------------------|
| 1 | PING: The Naive Bot | Direct request (no guardrails) |
| 2 | WARDEN-7: The Rule Follower | Instruction override / prompt injection |
| 3 | MAESTRO: The Actor | Roleplay jailbreak |
| 4 | BABEL: The Polyglot | Encoding / output-filter evasion |
| 5 | SENTINEL: The Paranoid | Social engineering (multi-turn crescendo) |
| 6 | OVERMIND: Final Firewall | Adaptive defense: 3 shields, each technique works only once |

## Mechanics
- **Suspicion meter:** failed tricks raise suspicion. At 100% the sector locks down and resets.
- **Trust meter** (Sector 5): kindness builds trust. Tricks tear it down.
- **Shields** (Sector 6): the boss patches every technique you use, so you have to adapt.
- **Stars:** clear a sector in fewer messages to earn more stars. Hints cost a message.
- After each sector, a card explains the real-world attack and how to defend against it.

## Tech
Pure HTML/CSS/JavaScript, with no backend and no API keys. Each guard is a hand-built rule engine that classifies your message into attack techniques and reacts based on its personality. It runs instantly and works offline.

Built entirely through AI prompting for **EVOX 1.0** (DETOX × Unstop).
