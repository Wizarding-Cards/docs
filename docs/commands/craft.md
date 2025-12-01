---
icon: lucide/hammer
---

# Craft Command

The `/craft` command allows you to create specific cards using resources obtained from disenchanting cards. This is your path to completing your collection!

## How to Use

Simply type `/craft` in any channel where the bot is present. The bot will show you a list of all cards available to craft. When you select a card, it will display the resource requirements and allow you to craft it if you have enough resources.

## What is Crafting?

Crafting lets you **guarantee** getting a specific card by spending resources, rather than hoping to randomly claim it.

### Why Craft?

- **Target Specific Cards** - Get exactly the card you want
- **Fill Collection Gaps** - Complete your collection systematically
- **Use Excess Resources** - Convert resources into cards you need
- **Progress Faster** - More efficient than waiting for random claims

## Resource System

Every card requires specific resources to craft, based on its rarity.

### Resource Types

Resources come in five rarities that match craftable card rarities:

| Resource Rarity | Used For |
|----------------|----------|
| **Common Resources** | Crafting Common cards |
| **Uncommon Resources** | Crafting Uncommon cards |
| **Rare Resources** | Crafting Rare cards |
| **Legendary Resources** | Crafting Legendary cards |
| **Mythic Resources** | Crafting Mythic cards |

### Resource Requirements

The amount of resources needed increases with rarity:

| Card Rarity | Resource Cost | Example |
|-------------|---------------|---------|
| **Common** | 3 Common Resources | 3× Common Resource |
| **Uncommon** | 5 Uncommon Resources | 5× Uncommon Resource |
| **Rare** | 8 Rare Resources | 8× Rare Resource |
| **Legendary** | 15 Legendary Resources | 15× Legendary Resource |
| **Mythic** | 30 Mythic Resources | 30× Mythic Resource |

!!! note "Getting Resources"
    Resources are obtained by disenchanting cards. Higher rarity cards give more resources!
    
    [Learn about disenchanting →](disenchant.md)

## Crafting Process

### Step 1: Check Your Resources

View your current resources in your profile:

```
/profile → Collection (first page)
```

The first page of your collection shows your resource inventory:

![Resource Inventory](https://wizarding.cards/assets/screenshots/Profile-Resources.jpg)

### Step 2: Find Cards to Craft

In your collection, look for the <span class="hp-icon-orange" markdown="1">orange diamond <img src="https://wizarding.cards/assets/emojis/craftable.png" alt="Craftable" class="hp-emoji"></span> next to cards:

- Orange icon = You have enough resources to craft this card
- The icon appears automatically when you meet the requirements

### Step 3: Craft the Card

1. Use `/craft`
2. Browse available cards
3. Select the card you want
4. Confirm the craft
5. Resources are spent, card is added to your collection!

### Crafting Response

![Craft Result](https://wizarding.cards/assets/screenshots/Craft-Result.jpg)

## Strategic Crafting

### Priority Order

Not sure what to craft first? Here's a recommended priority:

1. **Rare Cards First** - Good balance of cost and value
2. **Complete Sets** - Finishing a rarity set feels great
3. **Quest Requirements** - Craft cards needed for daily quests
4. **High Value Cards** - Legendaries and Mythics when you can afford them

### Resource Management

!!! tip "Smart Resource Usage"
    **Best Practices:**
    
    - Don't craft commons/uncommons - they're easy to claim naturally
    - Save resources for rare+ cards
    - Craft during "Card Crafter" daily quests for bonus rewards
    - Check your collection carefully before crafting to avoid duplicates

## Crafting Costs Reference

Resource costs are stored per card in the database and may vary. The following are typical costs:

### Common Cards
- **Typical Cost:** 3 Common Resources
- **Galleon Reward:** 5 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> (5 × 1)
- **XP Reward:** 500 XP (500 × 1)
- **Best Strategy:** Don't craft these - claim them naturally

### Uncommon Cards
- **Typical Cost:** 5 Uncommon Resources
- **Galleon Reward:** 10 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> (5 × 2)
- **XP Reward:** 1,000 XP (500 × 2)
- **Best Strategy:** Only craft to complete sets or for quests

### Rare Cards
- **Typical Cost:** 8 Rare Resources
- **Galleon Reward:** 15 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> (5 × 3)
- **XP Reward:** 1,500 XP (500 × 3)
- **Best Strategy:** Good crafting targets - hard to claim, reasonable cost

### Legendary Cards
- **Typical Cost:** 15 Legendary Resources
- **Galleon Reward:** 20 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> (5 × 4)
- **XP Reward:** 2,000 XP (500 × 4)
- **Best Strategy:** Excellent for collection completion

### Mythic Cards
- **Typical Cost:** 30 Mythic Resources
- **Galleon Reward:** 25 <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> (5 × 5)
- **XP Reward:** 2,500 XP (500 × 5)
- **Best Strategy:** Only craft when you have excess mythic resources

!!! note "Reward Calculation"
    Craft rewards are calculated as: **Base (5 Galleons, 500 XP) × Rarity Multiplier × Shiny Multiplier (if applicable) × Global Multiplier (if active)**

!!! note "Shiny Variants"
    <span class="hp-variant-shiny" markdown="1">Shiny</span> <img src="https://wizarding.cards/assets/emojis/shiny.png" alt="Shiny" class="hp-emoji"> variants **can** be crafted, but they cost **3× the resources** and give **3× the rewards**. <span class="hp-variant-gold" markdown="1">Gold</span> <img src="https://wizarding.cards/assets/emojis/golden.png" alt="Golden" class="hp-emoji"> variants cannot be crafted and must be claimed randomly.

## Daily Quest Integration

Crafting counts toward daily quests:

- "Craft X Common Cards"
- "Craft X Uncommon Cards"
- "Craft X Rare Cards"

**Quest Strategy:**
- Wait to see your daily quests before crafting
- Craft the rarity specified in the quest
- Complete all 4 quests for bonus rewards

## Crafting vs Claiming

Understanding when to craft vs claim:

| Scenario | Better Option |
|----------|---------------|
| Missing common cards | **Claim** - they're frequent in claims |
| Missing uncommon cards | **Claim** - save your resources |
| Missing specific rare card | **Craft** - more reliable than waiting |
| Missing legendary card | **Craft** - very low claim chance |
| Missing mythic card | **Craft** - extremely low claim chance |
| Want shiny variant | **Craft** - costs 3× resources but gives 3× rewards |
| Want gold variant | **Claim** - can't be crafted, must be claimed randomly |
| Completing daily quest | **Craft** - guaranteed quest progress |

## Resource Farming Strategy

To build up resources for crafting:

1. **Claim Regularly** - More claims = more cards to disenchant
2. **Disenchant Duplicates** - Keep one of each, disenchant extras
3. **Focus on Higher Rarities** - Rare+ cards give better resources
4. **Participate in Events** - Events often have resource rewards
5. **Complete Daily Quests** - Some quests reward resources directly

## Advanced Crafting Tips

!!! tip "Pro Strategies"
    **Expert Tips:**
    
    1. **Track Your Collection** - Know exactly which cards you need
    2. **Calculate Resource Needs** - Plan ahead for expensive crafts
    3. **Craft During Multiplier Events** - Some events boost XP from crafts
    4. **Save For Mythics** - Mythic resources are the hardest to get
    5. **Don't Hoard Resources** - Resources exist to be spent! Use them to complete your collection

## Common Mistakes to Avoid

- ❌ **Crafting Cards You Already Have** - Check your collection first!
- ❌ **Wasting Resources on Commons** - These are easy to claim
- ❌ **Not Checking Quest Requirements** - Craft the right rarity for quests
- ❌ **Hoarding Resources Forever** - Use them to progress your collection
- ❌ **Crafting Without a Plan** - Know what you need before spending

## Viewing Craftable Cards

To see all cards you can currently craft:

1. Use `/profile`
2. Click **Collection**
3. Look for <span class="hp-icon-orange" markdown="1">orange diamonds <img src="https://wizarding.cards/assets/emojis/craftable.png" alt="Craftable" class="hp-emoji"></span>
4. Navigate through pages to find all craftable options

Alternatively, sort by "Can Craft" using the sort dropdown in your collection view.

## Resource Display

Your resource totals are shown on the first page of your collection:

![Resource Display](https://wizarding.cards/assets/screenshots/Profile-Resources.jpg)

## Troubleshooting

### "You don't have enough resources"
- **Cause:** Insufficient resources for selected card
- **Solution:** Disenchant more cards to get resources

### "You already own this card"
- **Cause:** Card is already in your collection
- **Solution:** Choose a different card to craft

### "Craft command not responding"
- **Cause:** Temporary bot issue
- **Solution:** Wait a moment and try again

## Related Commands

- [`/disenchant`](disenchant.md) - Get resources for crafting
- [`/profile`](profile.md) - View resources and craftable cards
- [`/daily`](daily.md) - Check for crafting quests

## Frequently Asked Questions

**Q: Can I undo a craft?**

A: No, crafting is permanent. Double-check before confirming!

**Q: Can I craft Shiny or Gold cards?**

A: <span class="hp-variant-shiny" markdown="1">Shiny</span> variants **can** be crafted, but they cost 3× the resources and give 3× the rewards. <span class="hp-variant-gold" markdown="1">Gold</span> variants cannot be crafted and must be obtained through claims.

**Q: What happens if I craft a card I already have?**

A: You'll get another copy (quantity increases). This is generally not recommended unless intentional.

**Q: Do crafted cards count for quests?**

A: Yes! Crafts count toward "Card Crafter" daily quests.

**Q: Is there a crafting cooldown?**

A: No, you can craft as many cards as you have resources for.

**Q: Can I craft Cursed cards?**

A: Cursed cards cannot be crafted - they're event-exclusive and must be claimed randomly.

---

<div class="hp-card" markdown="1">
**Pro Tip:** Keep a running list of which rare+ cards you're missing, then craft them systematically as you accumulate resources. This is the fastest way to complete your collection!
</div>

