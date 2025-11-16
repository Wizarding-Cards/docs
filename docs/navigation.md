---
icon: lucide/compass
---

# Navigation Guide

Understanding the Wizarding Cards interface is key to efficiently managing your collection and making the most of the bot's features. This guide explains all the icons, indicators, and navigation elements you'll encounter.

## Collection Icons

When viewing your collection through `/profile` → **Collection**, you'll see different colored icons next to each card:

### <span class="hp-icon-green" markdown="1"><img src="https://wizarding.cards/assets/emojis/owned.png" alt="Owned" class="hp-emoji"> Green Diamond</span>
**Meaning:** You **own** this card

- The card is in your collection
- You have at least one copy
- The number next to it shows how many copies you have
- Safe to disenchant extras if you have multiple copies

**Example Display:**

![Collection - Owned Card](https://wizarding.cards/assets/screenshots/Profile-Collection.jpg)

### <span class="hp-icon-red" markdown="1"><img src="https://wizarding.cards/assets/emojis/notowned.png" alt="Not Owned" class="hp-emoji"> Red Diamond</span>
**Meaning:** You **don't own** this card yet

- The card is not in your collection
- You need to claim or craft it
- Check if it's craftable (see orange icon below)
- These are your collection completion targets

**Example Display:**

![Collection - Not Owned Card](https://wizarding.cards/assets/screenshots/Profile-Collection.jpg)

### <span class="hp-icon-orange" markdown="1"><img src="https://wizarding.cards/assets/emojis/craftable.png" alt="Craftable" class="hp-emoji"> Orange Diamond</span>
**Meaning:** You **can craft** this card

- You have enough resources to craft this card
- Click to see exact resource requirements
- Crafting costs resources but guarantees you'll get the card
- More efficient than hoping for random claims for specific cards

**Example Display:**

![Collection - Craftable Card](https://wizarding.cards/assets/screenshots/Profile-Collection.jpg)

!!! tip "Collection Strategy"
    Focus on crafting orange icon cards to fill gaps in your collection. This is faster than waiting for random claims!

## Profile Interface Elements

### XP and Level Bar

The XP bar shows your progress to the next level:

![XP Bar](https://wizarding.cards/assets/screenshots/Profile.jpg)

- **Filled sections** = XP you've earned
- **Empty sections** = XP still needed
- **Level number** = Your current level

### Trophy Bar

Shows achievement completion progress:

![Trophy Bar](https://wizarding.cards/assets/screenshots/Profile.jpg)

- **First number** = Trophies earned
- **Second number** = Total available trophies
- More filled sections = More achievements completed

### Statistics Grid

Your profile displays various stats:

| Emoji | Stat | What It Means |
|-------|------|---------------|
| <img src="https://wizarding.cards/assets/emojis/level.png" alt="Level" class="hp-emoji"> | Level | Your overall progress rank |
| <img src="https://wizarding.cards/assets/emojis/galleons.png" alt="Galleons" class="hp-emoji"> | Galleons | Your currency balance |
| <img src="https://wizarding.cards/assets/emojis/streak.png" alt="Streak" class="hp-emoji"> | Max Streak | Your longest claiming streak ever |
| <img src="https://wizarding.cards/assets/emojis/card.png" alt="Card" class="hp-emoji"> | Claims | Total cards you've claimed |
| <img src="https://wizarding.cards/assets/emojis/craft.png" alt="Craft" class="hp-emoji"> | Crafts | Total cards you've crafted |
| <img src="https://wizarding.cards/assets/emojis/disenchant.png" alt="Disenchant" class="hp-emoji"> | Disenchants | Total cards you've disenchanted |

### Seasonal Currency (When Active)

During events, additional currencies appear:

| Event | Currency | Icon |
|-------|----------|------|
| Halloween <img src="https://wizarding.cards/assets/emojis/halloween.png" alt="Halloween" class="hp-emoji"> | Sweets | <img src="https://wizarding.cards/assets/emojis/sweets.png" alt="Sweets" class="hp-emoji"> |
| Christmas <img src="https://wizarding.cards/assets/emojis/christmas.png" alt="Christmas" class="hp-emoji"> | Wizard Crackers | <img src="https://wizarding.cards/assets/emojis/crackers.png" alt="Crackers" class="hp-emoji"> |
| Christmas <img src="https://wizarding.cards/assets/emojis/christmas.png" alt="Christmas" class="hp-emoji"> | Lumps of Coal | <img src="https://wizarding.cards/assets/emojis/coal.png" alt="Coal" class="hp-emoji"> |

## Shop Interface

### Shop Navigation

The shop uses pagination with buttons:

- **<img src="https://wizarding.cards/assets/emojis/leftarrow.png" alt="Left Arrow" class="hp-emoji"> Left Arrow** - Previous page
- **<img src="https://wizarding.cards/assets/emojis/rightarrow.png" alt="Right Arrow" class="hp-emoji"> Right Arrow** - Next page
- **<img src="https://wizarding.cards/assets/emojis/rightarrow.png" alt="Down Arrow" class="hp-emoji hp-emoji-rotate-down"> Item Dropdown** - Select item to purchase
- **❌ Close** - Exit the shop

### Item Display Format

Each shop item shows:

![Shop Item Display](https://wizarding.cards/assets/screenshots/Shop-Purchase.jpg)

- **Name** - Item name
- **Price** - Cost in Galleons (or event currency)
- **Quantity** - How many you currently own
- **Description** - What the item does

!!! note "Locked Items"
    Some items show a 🔒 padlock icon and "Level X Required" - you must reach that level to purchase them.

## Quest Interface

### Quest Status Indicators

In the `/daily` command, quests show their completion status:

![Quest Status](https://wizarding.cards/assets/screenshots/Quests.jpg)

- **<img src="https://wizarding.cards/assets/emojis/owned.png" alt="Owned" class="hp-emoji"> Green Diamond** = Quest completed
- **<img src="https://wizarding.cards/assets/emojis/notowned.png" alt="Not Owned" class="hp-emoji"> Red Diamond** = Quest not completed

### Quest Types

Different quest types have different emojis:

| Emoji | Quest Type | What To Do |
|-------|------------|------------|
| <img src="https://wizarding.cards/assets/emojis/card.png" alt="Card" class="hp-emoji"> | Card Collector | Claim specific rarity cards |
| <img src="https://wizarding.cards/assets/emojis/craft.png" alt="Craft" class="hp-emoji"> | Card Crafter | Craft specific rarity cards |
| <img src="https://wizarding.cards/assets/emojis/disenchant.png" alt="Disenchant" class="hp-emoji"> | Resource Gatherer | Disenchant specific rarity cards |
| <img src="https://wizarding.cards/assets/emojis/vote.png" alt="Vote" class="hp-emoji"> | Vote Collector | Vote on bot listing sites |

## Inventory Interface

Your inventory (accessed via `/profile` → **Inventory**) shows:

![Inventory](https://wizarding.cards/assets/screenshots/Profile-Inventory.jpg)

- Items you own appear at the top
- Items you don't own appear at the bottom
- Quantity shows how many of each item you have
- Use the dropdown to select and use items

## Leaderboard Navigation

The `/leaderboard` command shows rankings:

![Leaderboard](https://wizarding.cards/assets/screenshots/Leaderboard-Landing.jpg)

- **<img src="https://wizarding.cards/assets/emojis/gold.png" alt="Gold" class="hp-emoji"> Gold** = 1st place
- **<img src="https://wizarding.cards/assets/emojis/silver.png" alt="Silver" class="hp-emoji"> Silver** = 2nd place
- **<img src="https://wizarding.cards/assets/emojis/bronze.png" alt="Bronze" class="hp-emoji"> Bronze** = 3rd place

Available leaderboards:
- Claims (total cards claimed)
- Streak (highest current streak)
- Level (highest level reached)
- Collection (most unique cards owned)

## Button Interactions

### Common Buttons

Throughout the bot, you'll see these buttons:

| Button | Purpose |
|--------|---------|
| **Collection** | View your card collection |
| **Accolades** | See achievement progress |
| **Inventory** | Check owned items |
| **Settings** | Adjust preferences |
| **Close** | Exit the current menu |
| **Enter The Store** | Open the shop |
| **Back to Profile** | Return to profile view |

### Pagination Buttons

For multi-page content:

| Button | Function |
|--------|----------|
| <img src="https://wizarding.cards/assets/emojis/skip_back.png" alt="Skip_back" class="hp-emoji"> | Skip back 10 pages |
| <img src="https://wizarding.cards/assets/emojis/prev.png" alt="Prev" class="hp-emoji"> | Previous page |
| <img src="https://wizarding.cards/assets/emojis/search.png" alt="Search" class="hp-emoji"> | Search (in collection) |
| <img src="https://wizarding.cards/assets/emojis/next.png" alt="Next" class="hp-emoji"> | Next page |
| <img src="https://wizarding.cards/assets/emojis/skip_forward.png" alt="Skip_forward" class="hp-emoji"> | Skip forward 10 pages |

## Card Display Format

When you claim a card, it shows:

![Card Claim Result](https://wizarding.cards/assets/screenshots/Claim.jpg)

### Card Information Elements

- **Card Name** - Character/creature/spell name
- **Rarity Star Count** - More stars = higher rarity
- **Rarity Name** - Common, Uncommon, Rare, Legendary, Mythic, Cursed
- **Copy Count** - How many you have total
- **Rewards Section** - Galleons, XP, and streak info
- **Special Variants** - <img src="https://wizarding.cards/assets/emojis/shiny.png" alt="Shiny" class="hp-emoji"> for Shiny, <img src="https://wizarding.cards/assets/emojis/golden.png" alt="Golden" class="hp-emoji"> for Gold

## Rarity Colour Coding

While Discord doesn't show colours in the same way, rarities are indicated by:

| Rarity | Indicator | Stars |
|--------|-----------|-------|
| <span class="hp-rarity-common" markdown="1">**Common**</span> | No special marking | ★ |
| <span class="hp-rarity-uncommon" markdown="1">**Uncommon**</span> | No special marking | ★★ |
| <span class="hp-rarity-rare" markdown="1">**Rare**</span> | No special marking | ★★★ |
| <span class="hp-rarity-legendary" markdown="1">**Legendary**</span> | Can be <img src="https://wizarding.cards/assets/emojis/shiny.png" alt="Shiny" class="hp-emoji"><span class="hp-variant-shiny" markdown="1">Shiny</span> | ★★★★ |
| <span class="hp-rarity-mythic" markdown="1">**Mythic**</span> | Can be <img src="https://wizarding.cards/assets/emojis/shiny.png" alt="Shiny" class="hp-emoji"><span class="hp-variant-shiny" markdown="1">Shiny</span> or <img src="https://wizarding.cards/assets/emojis/golden.png" alt="Golden" class="hp-emoji"><span class="hp-variant-gold" markdown="1">Gold</span> | ★★★★★ |
| <span class="hp-rarity-cursed" markdown="1">**Cursed**</span> | Special indicator | ★★★★★★ |

## Search Functionality

In your collection, use the <img src="https://wizarding.cards/assets/emojis/search.png" alt="Search" class="hp-emoji"> search button to find specific cards:

1. Click the search button
2. Type part of the card name
3. Results show matching cards
4. Works with partial names (e.g., "Harry" finds "Harry Potter")

## Settings Interface

Access settings via `/profile` → **Settings**:

![Settings Interface](https://wizarding.cards/assets/screenshots/Profile-Settings.jpg)

- **<img src="https://wizarding.cards/assets/emojis/owned.png" alt="Owned" class="hp-emoji"> Green Diamond** = Setting enabled
- **<img src="https://wizarding.cards/assets/emojis/notowned.png" alt="Not Owned" class="hp-emoji"> Red Diamond** = Setting disabled
- Use dropdown to toggle settings

## Tips for Efficient Navigation

!!! tip "Keyboard Shortcuts"
    While Discord doesn't have traditional keyboard shortcuts for bot commands, you can:

    - Use `/` to bring up command menu
    - Type command names quickly to autocomplete
    - Use arrow keys to navigate suggestion lists

!!! tip "Mobile vs Desktop"
    The interface works the same on mobile and desktop, but:

    - **Desktop:** Easier to see multiple cards at once
    - **Mobile:** Buttons may be slightly smaller
    - **Both:** All features fully functional

## Common Navigation Patterns

### Viewing A Specific Card
1. Use `/view` to search for and view a specific card
2. Or use `/profile` → **Collection**
3. Navigate pages or use <img src="https://wizarding.cards/assets/emojis/magnifyingglass.png" alt="Search" class="hp-emoji"> search
4. Find your card

### Checking Quest Progress
1. Use `/daily`
2. Review quest list
3. See checkmarks for completed quests
4. Plan remaining actions

### Buying Shop Items
1. Use `/shop`
2. Click **Enter The Store**
3. Navigate pages with arrows
4. Select item from dropdown
5. Confirm purchase

### Using An Item
1. Use `/profile`
2. Click **Inventory**
3. Select item from dropdown
4. Confirm usage

---

<div class="hp-card" markdown="1">
**Master Tip:** Bookmark frequently used commands by typing them in a private Discord channel or note. This makes it faster to access them throughout the day!
</div>

