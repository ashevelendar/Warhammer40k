# Database Structure

The Supabase database is the authoritative persistent state.

## Realm

### realms
The player's nation or other chosen political entity.

Tracks identity, culture, government, leader, population, treasury, food, reputation, territory, laws, traditions, faiths and current situation.

### realm_stats
Military, Diplomacy, Economy, Knowledge, Infrastructure and the realm-specific sixth attribute.

### realm_resources
Quantities and condition of strategic, economic and survival resources.

### realm_settlements
Settlements controlled by a realm.

### realm_territories
Territories, regions, strategic value and resources.

### realm_relations
Relationships between realms.

### trade_agreements
Active and historical trade agreements with realms or factions.

### realm_laws
Current and historical laws.

### realm_traditions
Cultural traditions.

### realm_faiths
Religions and belief systems present within the realm.

### realm_ambitions
Primary, secondary and long-term ambitions with progress tracking.

### realm_events
Events directly associated with a realm.

## World

### world_state
Global setting, date, tone, danger, collapse rate, simulation style, world summary, worldbuilding answers and independent developments.

### locations
General locations that can exist independently of any realm.

### events
General world events.

### rumours
Information that may be true, false, incomplete or misleading.

### factions
External powers that are not necessarily sovereign realms.

### faction_relationships
Relationships between external factions.

## People

### characters
Notable citizens, leaders and other important individuals.

### character_stats
Personal attributes.

### relationships
Relationships between characters.

### abilities
Skills, abilities and learned capabilities.

### inventory
Important possessions.

### character_knowledge
What an individual actually knows.

### character_events
An individual's memory of events.

## Compatibility

The original character-oriented tables remain available for notable citizens and continuity. Nation-level state is now represented primarily by the `realm_*` tables.

No starting nation, character, faction, location or event is seeded.
