---
icon: lucide/recycle
---

# Disenchant Command

The `/disenchant` command allows you to convert unwanted or duplicate cards into resources, which you can then use to craft specific cards you need.

## How to Use

Simply type `/disenchant` in any channel where the bot is present. The bot will show you a list of all cards available. When you select a card, it will display the number of copies you have (if any) and allow you to choose how many to disenchant.

## What is Disenchanting?

Disenchanting is the process of **breaking down cards** into crafting resources. Think of it as recycling cards you don't need into materials for cards you do need!

### Why Disenchant?

- **Get Crafting Resources** - Convert cards into materials for crafting
- **Manage Duplicates** - Clear out extra copies of cards
- **Progress Your Collection** - Turn what you have into what you need
- **Complete Daily Quests** - Some quests require disenchanting

## Resource Yields

Different rarity cards give different amounts and types of resources. Resource yields are **random** and vary based on the card's rarity:

| Card Rarity | Typical Resources | Notes |
|-------------|-------------------|-------|
| **Common** | Random amount of Common Resources | Resources are randomly generated |
| **Uncommon** | Random amount of Uncommon Resources | May also include some Common Resources |
| **Rare** | Random amount of Rare Resources | May include lower rarity resources |
| **Legendary** | Random amount of Legendary Resources | May include lower rarity resources |
| **Mythic** | Random amount of Mythic Resources | May include lower rarity resources |

!!! note "Variant Bonuses"
    - **Shiny (<img src="https://wizarding.cards/assets/emojis/shiny.png" alt="Shiny" class="hp-emoji">) cards:** Give **3× resources** (multiplied by shiny chance)
    - **Gold (<img src="https://wizarding.cards/assets/emojis/golden.png" alt="Golden" class="hp-emoji">) cards:** Give **5× resources** (multiplied by gold chance)

!!! warning "Disenchant Failure Chances"
    - **Cursed cards:** Have a **50% chance of failure** - the card disintegrates and you get no resources
    - **Gold cards:** Have a **25% chance of failure** - the card disintegrates and you get no resources

## Disenchanting Process

### Step 1: Review Your Collection

Before disenchanting, check what you have:

```
/profile → Collection
```

Look for cards where you have multiple copies. These are prime candidates for disenchanting!

### Step 2: Identify Safe Disenchants

**Safe to Disenchant:**
- Any card where you have 2+ copies (keep 1 of each)
- Common and Uncommon cards with many duplicates
- Cards you're not attached to

**Keep at Least One:**
- Always keep at least 1 copy of each card
- Collection completion requires having one of each
- Some achievements require owning specific cards

### Step 3: Disenchant Cards

1. Use `/disenchant`
2. Browse your cards
3. Select a card to disenchant
4. Confirm the disenchant
5. Receive resources!

### Disenchant Response

![Disenchant Result](https://wizarding.cards/assets/screenshots/Disenchant-Result.jpg)

## Strategic Disenchanting

### What to Disenchant First

Priority order for disenchanting:

1. **Common Duplicates (3+ copies)** - You'll claim more naturally
2. **Uncommon Duplicates (3+ copies)** - Also claim frequently
3. **Rare Duplicates (2+ copies)** - Keep 1, disenchant extras
4. **Legendary Duplicates** - Only if you have 2+
5. **Mythic Duplicates** - Very rare, consider carefully

### What to Keep

!!! warning "Don't Disenchant These!"
    - Your only copy of any card
    - Cards needed for achievements
    - Cards you personally like

!!! note "Shiny and Gold Variants"
    Shiny and Gold variants give excellent rewards (3× and 5× respectively), but consider:
    - **Shiny variants:** Give 3× resources - great for disenchanting if you have duplicates
    - **Gold variants:** Give 5× resources but have a 25% failure chance - weigh the risk vs reward
    - If you're a collector, you may want to keep variants even if they're duplicates

## Resource Planning

### Calculate Your Needs

Before mass disenchanting, plan what you want to craft:

**Example Plan:**
```
Goal: Craft Albus Dumbledore (Legendary)
Needs: 15 Legendary Resources

Current: 4 Legendary Resources
Needed: 11 more

Strategy: Disenchant 2-3 duplicate legendary cards
(Resource yields are random, so you may need multiple cards)
```

### Resource Conversion Ratios

Since resource yields are random, exact conversion ratios vary. However, you can generally expect:

- Higher rarity cards give more and better resources
- Shiny variants give 3× resources, making them valuable to disenchant
- Gold variants give 5× resources, but have a 25% failure risk
- Resources may include lower rarity resources in addition to the card's rarity

## Daily Quest Integration

Disenchanting counts toward daily quests:

- "Disenchant X Common Cards"
- "Disenchant X Uncommon Cards"
- "Disenchant X Rare Cards"
- "Disenchant X Legendary Cards"

**Quest Strategy:**
- Wait to see your daily quests before mass disenchanting
- Disenchant the rarity specified in the quest
- Save your disenchants for quest days when possible

## Rewards

Disenchanting awards both Galleons and XP based on the card's rarity and variant:

### Galleon Rewards

| Card Rarity | Base Galleons | With Shiny | With Gold |
|-------------|---------------|------------|-----------|
| **Common** | 3 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 9 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 15 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> |
| **Uncommon** | 6 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 18 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 30 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> |
| **Rare** | 9 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 27 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 45 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> |
| **Legendary** | 12 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 36 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 60 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> |
| **Mythic** | 15 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 45 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | 75 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> |

### XP Rewards

| Card Rarity | Base XP | With Shiny | With Gold |
|-------------|---------|------------|-----------|
| **Common** | 75 XP | 225 XP | 375 XP |
| **Uncommon** | 150 XP | 450 XP | 750 XP |
| **Rare** | 225 XP | 675 XP | 1,125 XP |
| **Legendary** | 300 XP | 900 XP | 1,500 XP |
| **Mythic** | 375 XP | 1,125 XP | 1,875 XP |

!!! note "Reward Calculation"
    Rewards are calculated as: **Base (3 Galleons, 75 XP) × Rarity Multiplier × Variant Multiplier (Shiny=3×, Gold=5×) × Global Multiplier (if active) × Successful Disenchants**

!!! note "Failed Disenchants"
    If a disenchant fails (cursed or gold cards), you receive **no rewards** for that card - it simply disintegrates.

## Advanced Strategies

### Mass Disenchanting

For players with many duplicates:

1. **Sort by Quantity** - Find cards with most copies
2. **Keep 2-3 of Each** - Leave some buffer copies
3. **Disenchant in Bulk** - Process many at once
4. **Track Resources** - Monitor your resource gains

### Resource Hoarding vs Spending

**Hoarding Approach:**
- Save up large amounts of resources
- Craft expensive cards (Legendaries/Mythics)
- Takes patience but feels rewarding

**Spending Approach:**
- Craft cards as soon as you can
- Fill collection gaps immediately
- Feels like faster progress

Both are valid! Choose based on your personality and goals.

### Event Considerations

During special events:
- Resource gains may be boosted
- Event-specific resources might exist
- Consider timing your disenchants for maximum benefit

## Common Mistakes to Avoid

- ❌ **Disenchanting Your Only Copy** - Always keep at least one!
- ❌ **Disenchanting Shiny/Gold Variants Without Understanding** - They give great rewards but gold has failure risk
- ❌ **Mass Disenchanting Without Planning** - Know what you'll craft first
- ❌ **Ignoring Quest Requirements** - Check daily quests before disenchanting
- ❌ **Hoarding Too Many Duplicates** - Use those resources!
- ❌ **Not Considering Failure Chances** - Cursed (50%) and Gold (25%) cards can fail

## Viewing Disenchant Values

To see what resources a card will give:

1. The disenchant interface shows resource gains
2. Higher rarity = more resources
3. Shiny/Gold variants show bonus multiplier
4. Confirm before finalizing to avoid mistakes

## Bulk Disenchanting Tips

!!! tip "Efficient Disenchanting"
    **Best Practices:**

    1. **Do Monthly Cleanups** - Disenchant duplicates regularly
    2. **Keep a Buffer** - Maintain 2-3 copies of commons/uncommons
    3. **Focus on Commons First** - They accumulate fastest
    4. **Save Rares** - Only disenchant when you have 3+ copies
    5. **Consider Variants Carefully** - Shiny/Gold give great rewards but may be collectibles you want to keep

## Undo Disenchanting

!!! danger "No Undo!"
    Disenchanting is **permanent**. Once you disenchant a card, you cannot get it back without claiming or crafting it again.

    Always double-check before confirming!

## Troubleshooting

### "You don't have any copies of this card"
- **Cause:** Card not in your collection or you've disenchanted all copies
- **Solution:** You need to claim or craft the card first

### "Disenchant command not responding"
- **Cause:** Temporary bot issue
- **Solution:** Wait and try again, or contact support

## Related Commands

- [`/craft`](craft.md) - Use resources to create cards
- [`/profile`](profile.md) - View your collection and resources
- [`/daily`](daily.md) - Check for disenchanting quests

## Frequently Asked Questions

**Q: Can I get a card back after disenchanting?**

A: No, disenchanting is permanent. You'd need to claim or craft it again.

**Q: Should I disenchant all my duplicate commons?**

A: Keep 2-3 copies as a buffer, disenchant the rest for resources.

**Q: Do Shiny cards give more resources?**

A: Yes! Shiny cards give **3× resources**, Gold cards give **5× resources** (but gold has a 25% failure chance).

**Q: Is there a cooldown on disenchanting?**

A: No, you can disenchant as many cards as you want instantly.

**Q: What if I accidentally disenchant a card I wanted?**

A: Unfortunately, you'll need to claim or craft it again. Always double-check!

**Q: Can I disenchant Cursed cards?**

A: Yes, but Cursed cards have a **50% failure chance** - they may disintegrate without giving resources. Consider keeping them.

**Q: Do disenchants count for statistics?**

A: Yes! Your total disenchants are tracked in your profile and leaderboards. The total count includes all disenchant attempts, including failed ones (cursed/gold cards that disintegrate).

---

<div class="hp-card" markdown="1">
**Golden Rule:** When in doubt, keep it! It's better to have extras than to regret disenchanting a card you wanted. Always keep at least one copy of every card!
</div>

