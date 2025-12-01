---
icon: lucide/calendar-check
---

# Daily Command

The `/daily` command shows your daily quests - special challenges that reset every day at midnight and reward you with bonus Galleons and XP!

## How to Use

Use `/daily` to display your four daily quests, their progress, and the rewards for completing all of them.

## Daily Quest System

Every day at **midnight GMT/BST**, you receive 4 new random quests to complete. The `/daily` command shows a countdown timer displaying when quests reset in your local timezone.

### Quest Display

![Daily Quests](https://wizarding.cards/assets/screenshots/Quests.jpg)

## Quest Types

There are four main types of daily quests:

### 1. <img src="https://wizarding.cards/assets/emojis/card.png" alt="Card" class="hp-emoji"> Card Collector

**Objective:** Claim a certain number of cards of a specific rarity

**Variants:**

- Claim 3/5/7/10 Common Cards
- Claim 2/3/4/5 Uncommon Cards
- Claim 1/2/3 Rare Cards
- Claim 1 Legendary Card
- Claim 1 Mythic Card

**Strategy:**

- Happens naturally through `/claim`
- Just play normally!
- Higher rarity quests may take multiple days

### 2. <img src="https://wizarding.cards/assets/emojis/craft.png" alt="Craft" class="hp-emoji"> Card Crafter

**Objective:** Craft a certain number of cards of a specific rarity

**Variants:**

- Craft 2/3/4 Common Cards
- Craft 1/2/3 Uncommon Cards
- Craft 1/2 Rare Cards

**Strategy:**

- Save your resources for craft quest days
- Focus on cheaper crafts when possible
- Check if you have enough resources before committing

[Learn about crafting →](craft.md)

### 3. <img src="https://wizarding.cards/assets/emojis/disenchant.png" alt="Disenchant" class="hp-emoji"> Resource Gatherer

**Objective:** Disenchant a certain number of cards of a specific rarity

**Variants:**

- Disenchant 2/4/6 Common Cards
- Disenchant 2/3/4 Uncommon Cards
- Disenchant 1/2 Rare Cards
- Disenchant 1 Legendary Card

**Strategy:**

- Wait until you see this quest before mass disenchanting
- Focus on the specific rarity requested
- Make sure you keep at least one copy of each card!

[Learn about disenchanting →](disenchant.md)

### 4. <img src="https://wizarding.cards/assets/emojis/vote.png" alt="Vote" class="hp-emoji"> Vote Collector

**Objective:** Vote on a certain number of bot listing sites

**Variants:**

- Vote on 1/2/3/4 Voting Sites

**Strategy:**

- Easiest quest to complete!
- Use `/vote` to get links
- Each site has a 12-hour cooldown
- Do this quest first each day

[Learn about voting →](vote.md)

## Quest Rewards

### Individual Quest Completion

Each quest you complete contributes toward your overall progress, but the real reward comes from completing all four!

### All Quests Bonus

When you complete all 4 daily quests, you receive:

- **<img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> Galleons:** Base reward (typically 500+)
- **<img src="https://wizarding.cards/assets/emojis/xp.png" alt="Xp" class="hp-emoji"> XP:** Base reward (typically 100+)
- **Multipliers:** Active vault keys multiply these rewards!

!!! tip "Vault Key Multiplier"
    During Global Vault Key events, quest rewards can be 2x, 3x, or even higher! Watch for announcements in the support server.

[Learn about vault keys →](../features/shop-items.md#vault-keys)

## Quest Reset Time

Quests reset at **midnight GMT/BST** (00:00).

**Important:** You must complete your quests before midnight GMT/BST or they'll be replaced with new ones!

!!! tip "Check Your Local Time"
    Use `/daily` to see a countdown timer that shows exactly when quests reset in your local timezone. This makes it easy to plan when to complete your quests!

### Reset Timer

The `/daily` command shows:
```
Quests reset in 8 hours (at 12:00 AM)
```

Use this to plan your day!

## Quest Selection

### How Quests Are Chosen

Each day's quests are randomly selected from available quest types:

- Up to **2 quests of each type** (Claim, Craft, Disenchant, Vote)
- Each quest has a **unique (type, rarity) combination**
- **Vote quests** have a 50% chance of appearing
- Total of **4 quests** per day

### Quest Difficulty

Quests are balanced to be completable in one day:

- **Easy:** <img src="https://wizarding.cards/assets/emojis/vote.png" alt="Vote" class="hp-emoji"> Vote quests, low-count claim quests

- **Medium:** Uncommon crafts, rare disenchants

- **Hard:** High-count legendary claims, multiple crafts

## Completion Strategies

### Morning Routine

1. **Check quests:** See what you need to do today

2. **<img src="https://wizarding.cards/assets/emojis/vote.png" alt="Vote" class="hp-emoji"> Vote immediately:** Easiest quest to complete

3. **Plan your day:** Know what you need to focus on

### During the Day

4. **<img src="https://wizarding.cards/assets/emojis/card.png" alt="Card" class="hp-emoji"> Claim regularly:** Works toward claim quests naturally

5. **Save crafts/disenchants:** Wait to see what's needed

6. **Avoid wasting resources:** Don't craft/disenchant randomly

### Evening Check

7. **Review progress:** See what's left

8. **Complete remaining quests:** Before midnight!

9. **Claim rewards:** All 4 quests completed!

## Quest Progress Tracking

### Visual Indicators

- **<img src="https://wizarding.cards/assets/emojis/owned.png" alt="Owned" class="hp-emoji"> Green Diamond:** Quest completed

- **<img src="https://wizarding.cards/assets/emojis/notowned.png" alt="Not Owned" class="hp-emoji"> Red Diamond:** Quest not completed

- **Progress Counter:** Shows <img src="https://wizarding.cards/assets/emojis/quest.png" alt="Quest" class="hp-emoji"> `current/target` (e.g., "2/5")

### Real-Time Updates

Quest progress updates instantly when you:

- <img src="https://wizarding.cards/assets/emojis/card.png" alt="Card" class="hp-emoji"> Claim a card

- <img src="https://wizarding.cards/assets/emojis/craft.png" alt="Craft" class="hp-emoji"> Craft a card

- <img src="https://wizarding.cards/assets/emojis/disenchant.png" alt="Disenchant" class="hp-emoji"> Disenchant a card

- <img src="https://wizarding.cards/assets/emojis/vote.png" alt="Vote" class="hp-emoji"> Vote on a site

Check `/daily` anytime to see your progress!

## Tips for Daily Quest Success

!!! tip "Maximise Quest Rewards"
    **Best Practices:**
    
    1. **Check Quests First Thing** - Plan your day around them
    2. **Vote Immediately** - Knock out the easiest quest
    3. **Don't Rush** - You have all day to complete them
    4. **Save Resources** - Don't craft/disenchant until you see the quest
    5. **Set a Reminder** - Complete quests before midnight!
    6. **Stack with Events** - During multiplier events, quest rewards are even better

## Common Mistakes to Avoid

❌ **Forgetting to Check Quests** - You might waste actions on wrong rarities

❌ **Leaving Quests Until Last Minute** - Technical issues could prevent completion

❌ **Disenchanting Before Checking** - Might need those cards for another quest

❌ **Ignoring Vote Quest** - Easiest free <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> Galleons and <img src="https://wizarding.cards/assets/emojis/xp.png" alt="Xp" class="hp-emoji"> XP!

❌ **Not Planning Ahead** - Know what you need before you start  

## Special Considerations

### Seasonal Quests

During events (Halloween, Christmas), special event quests may appear:

- Use event currency (<img src="https://wizarding.cards/assets/emojis/sweets.png" alt="Sweets" class="hp-emoji"> Sweets, <img src="https://wizarding.cards/assets/emojis/crackers.png" alt="Crackers" class="hp-emoji"> Crackers, <img src="https://wizarding.cards/assets/emojis/coal.png" alt="Coal" class="hp-emoji"> Coal)

- Different requirements

- Bonus rewards

- Theme-appropriate tasks

### Multiplier Events

When Global Vault Keys are active:

- All quest rewards (<img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> Galleons and <img src="https://wizarding.cards/assets/emojis/xp.png" alt="Xp" class="hp-emoji"> XP) are multiplied

- Worth prioritising quest completion

- Announced in support server


## Troubleshooting

### "Quest not counting"
- **Cause:** Wrong rarity or type
- **Solution:** Double-check quest requirements

### "Quest progress reset"
- **Cause:** Midnight passed
- **Solution:** New day = new quests. Complete them faster tomorrow!

### "Can't complete quest in time"
- **Cause:** Difficult quest or limited play time
- **Solution:** It's okay to miss a day - there's always tomorrow!

## Related Commands

- [`/claim`](claim.md) - Complete claim quests
- [`/craft`](craft.md) - Complete craft quests
- [`/disenchant`](disenchant.md) - Complete disenchant quests
- [`/vote`](vote.md) - Complete vote quests
- [`/profile`](profile.md) - Track overall progress

## Frequently Asked Questions

**Q: What if I can't complete a quest?**  
A: It's okay! Missing one day won't hurt your long-term progress. New quests tomorrow!

**Q: Can I skip a quest I don't want to do?**  
A: No, quests cannot be skipped or rerolled. However, if you can't complete a quest, new ones will be available tomorrow!

**Q: Do quests carry over to the next day?**  
A: No, incomplete quests are replaced at midnight with new ones.

**Q: What happens if I complete quests after midnight?**  
A: The old quests are gone. You'll have new quests to complete instead.

**Q: Can I see tomorrow's quests?**  
A: No, quests are generated at midnight. You'll see them when they're available.

**Q: Do all players get the same quests?**  
A: No, quests are unique to each player and randomly generated.

**Q: What's the hardest quest type?**  
A: "Craft 2 Rare Cards" or "Claim 1 Mythic Card" are typically the most challenging.

---

<div class="hp-card" markdown="1">
**Daily Discipline:** Completing all 4 daily quests every day is one of the fastest ways to earn Galleons and XP. Make it part of your routine!
</div>

