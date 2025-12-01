---
icon: lucide/gift
---

# Claim Command

The `/claim` command is the core of Wizarding Cards - it's how you collect new cards and build your collection!

## How to Use

Simply type `/claim` in any channel where the bot is present. The bot will give you a random card from the entire collection.

## What Happens When You Claim

When you successfully claim a card, you'll receive:

1. **A Random Card** - One card selected from all available cards
2. **Galleons** - Currency (amount based on card rarity)
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

#### 1. Increased Higher Rarity Card Odds
The higher your streak, the better your chances of getting Legendary and Mythic cards (rarities that can be shiny):

- **Streak Bonus:** Reduces the odds denominator by `streak × 0.001` (capped at streak 5000)
- **Legendary:** Base odds of 1 in 20 (5%) improve with higher streaks
- **Mythic:** Base odds of 1 in 100 (1%) improve with higher streaks
- **Maximum Effect:** At streak 5000+, Legendary odds improve significantly, and Mythic odds improve substantially

**Example:**
- At streak 1000: Legendary odds improve from 1 in 20 to approximately 1 in 19
- At streak 5000: Maximum bonus applied (reduction of 5 to the odds denominator)

#### 2. Status Symbol
High streaks show dedication and appear on your profile and leaderboards!

[Learn more about the streak system →](../features/streaks.md)

## Card Rarity Odds

The system rolls for rarities from highest to lowest. Each rarity has a "1 in X" chance:

| Rarity | Base Odds | Approximate Chance |
|--------|-----------|-------------------|
| **Cursed** | 1 in 2,000 | ~0.05% |
| **Mythic** | 1 in 100 | ~1% |
| **Legendary** | 1 in 20 | ~5% |
| **Rare** | 1 in 5 | ~20% |
| **Uncommon** | 1 in 3 | ~33% |
| **Common** | Guaranteed if all else fails | ~50% |

!!! note "How It Works"
    The system checks rarities from highest to lowest. If you fail all higher rarity rolls, you're guaranteed a Common card. Streaks improve odds for Legendary and Mythic cards only.

!!! note "Shiny & Gold Variants"
    When you claim a Legendary or Mythic card, there's an additional small chance it will be a <img src="https://wizarding.cards/assets/emojis/shiny.png" alt="Shiny" class="hp-emoji"> <span class="hp-variant-shiny" markdown="1">Shiny</span> or <img src="https://wizarding.cards/assets/emojis/golden.png" alt="Golden" class="hp-emoji"> <span class="hp-variant-gold" markdown="1">Gold</span> variant!

## Galleon Rewards

Galleon rewards are based on the **rarity** of the card you claim, not your streak:

| Rarity | Galleons |
|--------|----------|
| **Common** | <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> 1 |
| **Uncommon** | <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> 2 |
| **Rare** | <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> 3 |
| **Legendary** | <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> 4 |
| **Mythic** | <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> 5 |
| **Cursed** | <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> 6 |

!!! note "Global Multipliers"
    During special events (like Global Vault Keys), all Galleon rewards are multiplied. This applies to the base reward amount.

## First Claim

Your very first claim in Wizarding Cards is **free** and immediate:

- No cooldown on first claim
- Starts your streak at 1
- Awards your first card and Galleons
- Unlocks the rest of the bot's features

## Claim Modifiers

Certain items and events can modify your claims:

### Shop Items That Affect Claims

| Item | Effect |
|------|--------|
| **Rapid Reclamation Remedy** | Instantly resets claim cooldown |
| **Rapid Bounty Draught** | Get 5 cards per claim (stacks with multiple uses) |

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
    3. **Build High Streaks** - Improves odds for Legendary and Mythic cards
    4. **Use Items Strategically** - Save Rapid Reclamation Remedy for emergency streak protection
    5. **Time Your Claims** - Claim right before bed to extend your streak window overnight

## Common Mistakes to Avoid

- ❌ **Forgetting About Cooldown** - Claiming is time-gated, plan accordingly
- ❌ **Breaking Streaks** - Set multiple reminders to prevent this
- ❌ **Not Using Items** - Rapid Reclamation Remedy and other items are meant to be used!
- ❌ **Expecting Streak to Affect Galleons** - Galleons are based on card rarity, not streak

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

A: Technically possible with the **Rapid Bounty Draught** shop item (gives 5 cards per claim), but otherwise no - `/claim` gives one card at a time with a cooldown between claims.

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

