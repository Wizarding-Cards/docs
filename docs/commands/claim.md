---
icon: lucide/gift
---

# Claim Command

The `/claim` command is the core of Wizarding Cards - it's how you collect new cards and build your collection!

## How to Use

```
/claim
```

Simply type `/claim` in any channel where the bot is present. The bot will give you a random card from the entire collection.

## What Happens When You Claim

When you successfully claim a card, you'll receive:

1. **A Random Card** - One card selected from all available cards
2. **Galleons** - Currency (amount increases with streak)
3. **XP** - Experience points to level up
4. **Streak Progress** - Your streak increases by 1
5. **Event Currency** - During seasonal events (Sweets, Crackers, Coal)

### Example Claim Response

![Claim Result](https://wizarding.cards/assets/screenshots/Claim.jpg)

## Cooldown System

After claiming, you must wait before claiming again:

| Player Type | Cooldown |
|-------------|----------|
| **Regular Players** | 30 minutes |
| **Voters** | 20 minutes |
| **Auror (Premium)** | 10 minutes |

!!! warning "Cooldown Timer"
    Trying to claim before the cooldown expires will show you how much time is remaining.

## The Streak System

Your **streak** is the number of consecutive claims you've made without letting too much time pass between claims.

### How Streaks Work

- Each claim within the time window increases your streak by 1
- Streaks provide multiple benefits (see below)
- Missing the window resets your streak to 0

### Streak Time Windows

| Player Type | Maximum Time Between Claims |
|-------------|----------------------------|
| **Regular Players** | 12 hours |
| **Auror (Premium)** | 24 hours |

!!! danger "Don't Break Your Streak!"
    If you don't claim within 12 hours (24 for Aurors) of your last claim, your streak resets to 0!

### Streak Benefits

Higher streaks provide significant advantages:

#### 1. Increased Rare Card Odds
The higher your streak, the better your chances of getting rare cards:

| Streak Range | Bonus |
|--------------|-------|
| 1-10 | Base odds |
| 11-25 | +10% rare card chance |
| 26-50 | +20% rare card chance |
| 51-100 | +30% rare card chance |
| 100+ | +40% rare card chance |

#### 2. Galleon Multiplier
Your Galleon rewards are multiplied by your streak:

- **Streak 1-5:** 1.0x multiplier
- **Streak 6-15:** 1.5x multiplier
- **Streak 16-30:** 2.0x multiplier
- **Streak 31-50:** 2.5x multiplier
- **Streak 51+:** 3.0x multiplier

#### 3. Status Symbol
High streaks show dedication and appear on your profile and leaderboards!

[Learn more about the streak system →](../features/streaks.md)

## Card Rarity Odds

Your claim has different chances for each rarity:

| Rarity | Base Chance | With 100+ Streak |
|--------|-------------|------------------|
| **Common** | 50% | 40% |
| **Uncommon** | 30% | 25% |
| **Rare** | 15% | 20% |
| **Legendary** | 4% | 10% |
| **Mythic** | 0.9% | 4.5% |
| **Cursed** | 0.1% | 0.5% |

!!! note "Shiny & Gold Variants"
    When you claim a Legendary or Mythic card, there's an additional small chance it will be a <span class="hp-variant-shiny" markdown="1">Shiny</span> <img src="https://wizarding.cards/assets/emojis/shiny.png" alt="Shiny" class="hp-emoji"> or <span class="hp-variant-gold" markdown="1">Gold</span> <img src="https://wizarding.cards/assets/emojis/golden.png" alt="Golden" class="hp-emoji"> variant!

## First Claim

Your very first claim in Wizarding Cards is **free** and immediate:

- No cooldown on first claim
- Starts your streak at 1
- Awards your first card and Galleons
- Unlocks the rest of the bot's features

## Claim Modifiers

Certain items and events can modify your claim odds:

### Shop Items That Affect Claims

| Item | Effect |
|------|--------|
| **Felix Felicis Potion** | +50% rare card odds for 3 claims |
| **Time Turner** | Resets claim cooldown immediately |
| **Duplicate Prevention (Common)** | Prevents common duplicates for 5 claims |
| **Duplicate Prevention (Uncommon)** | Prevents uncommon duplicates for 5 claims |
| **Duplicate Prevention (Rare+)** | Prevents rare+ duplicates for 5 claims |

### Global Vault Key Events

When a Global Vault Key is active:
- All rewards are multiplied (typically 2x)
- Entire community benefits
- Announced in support server

[Learn more about shop items →](../features/shop-items.md)

## Tips for Optimal Claiming

!!! tip "Maximise Your Claims"
    **Best Practices:**

    1. **Set Reminders** - Don't let your streak die!
    2. **Claim Consistently** - Try to claim every 3 hours during active hours
    3. **Build High Streaks** - The benefits compound significantly
    4. **Use Potions Strategically** - Save Felix Felicis for when you have high streaks
    5. **Time Your Claims** - Claim right before bed to extend your streak window overnight

## Common Mistakes to Avoid

❌ **Forgetting About Cooldown** - Claiming is time-gated, plan accordingly
❌ **Breaking Streaks** - Set multiple reminders to prevent this
❌ **Not Using Items** - Felix Felicis and other items are meant to be used!
❌ **Claiming Without Strategy** - Consider using Duplicate Prevention when targeting specific cards

## Daily Quest Integration

The `/claim` command is central to many daily quests:

- "Claim X Common Cards"
- "Claim X Uncommon Cards"
- "Claim X Rare Cards"
- "Claim X Legendary Cards"
- "Claim X Mythic Cards"

Your claims automatically count toward these quests!

## Troubleshooting

### "You must wait X hours before claiming again"
- **Cause:** Cooldown hasn't expired yet
- **Solution:** Wait for cooldown to finish, or use a Time Turner item

### "Your streak has been reset"
- **Cause:** More than 12 hours (24 for Aurors) passed since last claim
- **Solution:** Start rebuilding your streak, set better reminders

### "Database error"
- **Cause:** Temporary server issue
- **Solution:** Wait a moment and try again, or contact support if it persists

## Related Commands

- [`/profile`](profile.md) - View your collection and stats
- [`/daily`](daily.md) - Check quest progress
- [`/shop`](shop.md) - Buy items to enhance claims
- [`/vote`](vote.md) - Earn extra rewards

## Frequently Asked Questions

**Q: Can I claim multiple cards at once?**
A: No, `/claim` gives one card at a time with a cooldown between claims.

**Q: Can I choose which card I get?**
A: No, claims are random. Use `/craft` to target specific cards.

**Q: Do duplicate cards have any value?**
A: Yes! You can disenchant them for resources to craft other cards.

**Q: What happens to my streak if I become Auror?**
A: Your current streak is preserved, and you immediately get the 24-hour window instead of 12.

**Q: Is there a limit to how high my streak can go?**
A: No limit! Some players have streaks in the hundreds or thousands.

---

<div class="hp-card" markdown="1">
**Remember:** Consistency is key! The `/claim` command is your daily bread and butter. Set reminders, maintain your streak, and watch your collection grow!
</div>

