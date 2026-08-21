# Nightfall

A text-based social deduction **Mafia / Impostor** game designed for group chats **and** a fully playable browser version.

Friends get secretly assigned as either **Mafia** or **Town**, then eliminate each other through discussion, accusations, and voting — with built-in conversation topics to keep the game fun and lively.

---

## 🎮 Playable Web Version (HTML + CSS + JS)

A complete single-file interactive Game Master tool is included:

**[Open index.html](https://github.com/enerjadez/nightfall-mafia/blob/main/index.html)** (or enable GitHub Pages and open the live site)

### Features of the web app:
- Add / remove players
- Configure number of Mafia + Detective / Doctor
- Secret role reveal mode (one player at a time)
- Full Night phase (kill / investigate / protect)
- Day phase with random discussion prompts
- Voting system with tally
- Automatic win detection
- Beautiful dark atmospheric styling
- Game log and status tracking

**How to use:**
1. Download or open `index.html` in any modern browser
2. Or enable GitHub Pages (Settings → Pages → Deploy from main branch) for a live URL
3. Host runs the page, shares screen or relays info to friends

---

## How to Start a Game (Text / Chat version)

1. List your friends (example):
   `Players: Jade, Alex, Sam, Taylor, Jordan, Riley, Casey`
2. Choose how many Mafia you want, or let the host auto-balance:
   - 5–6 players → 1 Mafia
   - 7–9 players → 2 Mafia
   - 10–12 players → 3 Mafia
   - 13+ → 4 Mafia
3. (Optional) Choose special roles and theme.
4. Host assigns every role secretly and distributes them privately to each player.
5. Start **Night 1**.

You can add or remove players before the game starts by saying “Add ___” or “Remove ___”.

---

## Roles

**Always included:**
- **Mafia** — Know who the other Mafia are. Every night they choose one person to kill.
- **Villager** — No special power. Just try to find the Mafia through discussion and voting.

**Recommended specials (strongly suggested with 7+ players):**
- **Detective** — Once per night, investigate one living player and learn if they are Mafia or not.
- **Doctor** — Once per night, protect one player. That person cannot die that night.

Advanced options (add later if desired): Jester, Bodyguard, Mayor, Vigilante, etc.

---

## Game Flow (Rounds)

### Night Phase
- Everyone “goes to sleep”.
- Mafia privately choose who to kill.
- Detective investigates someone.
- Doctor protects someone.
- Host resolves the actions and announces the result in the morning (“X was found dead…” or “It was a peaceful night…”).

### Day Phase
1. Host gives 1–2 **discussion topics** to force conversation and keep energy high.
2. Free discussion + accusations.
3. Voting: Everyone votes who to eliminate. Majority (or plurality) wins.
4. The eliminated player gets **last words**, then their role is revealed.
5. Next night begins.

### Win Conditions
- **Town wins** if all Mafia are eliminated.
- **Mafia wins** if the number of living Mafia is equal to or greater than the remaining Town players.

---

## Discussion Topics System

Every Day phase the host provides fresh prompts so the chat stays lively. Examples:

- “Give your best alibi for last night — what were you doing?”
- “Who currently has the most suspicious energy and why?”
- “If you had to vote someone out right now based only on vibes, who would it be?”
- “Share one observation about another player that makes you slightly distrust them.”
- “What’s one true fact and one lie about yourself? Everyone else has to guess which is which.”
- Theme-specific prompts (Space Station, Medieval Village, etc.)

---

## How the Host Runs It

The host (or Grok / the HTML app) acts as full Game Master:
- Tracks living players and secret roles
- Collects night actions privately
- Posts discussion prompts
- Tallies votes
- Narrates dramatically
- Announces results

**For role secrecy:**
At the start the host gets a private role list and forwards individual role messages to each player (or players message the host privately).

---

## Theme Options

- Classic Village / Italian Mafia
- Space Station (Among Us vibe)
- Medieval Fantasy Town
- Corporate Office
- High School
- Custom (whatever the group wants)

---

## Quick Start Template

```
Start Nightfall with these players: [list names].
Use 2 Mafia + Detective + Doctor.
Theme: Classic Village
```

---

Designed with Grok for fun group chats.

Enjoy the game — and may the best deceivers win.
