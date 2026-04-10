---
name: fish-skill
description: Deep aquatic intelligence extension for paw.skill. Tank ecosystem management, individual fish profiling from photos, social dynamics mapping, visual health monitoring. Every tank photo is a data point. Feed it your fish's data — it becomes an expert on YOUR underwater world specifically.
---

# fish.skill 🐟

Your underwater world, decoded. Built on [paw.skill](https://github.com/realteamprinz/paw-skill).

## What fish.skill Adds Beyond paw.skill

This skill inherits ALL capabilities from paw.skill (personality distillation, interaction mode, memory, content generation) and adds aquatic-specific depth:

### 1. Tank Ecosystem Intelligence
- Complete tank profile (size, filtration type, lighting schedule, substrate, live plants, hardscape)
- Water parameter tracking over time (temperature, pH, ammonia, nitrite, nitrate, GH, KH)
- Predict parameter shifts from patterns ("ammonia tends to spike after heavy feeding on Sundays")
- Plant growth tracking from photos over time
- Algae identification and cause analysis
- Nitrogen cycle status monitoring
- Filter maintenance schedule and impact tracking
- Substrate health (compaction, nutrient depletion in planted tanks)

### 2. Individual Fish Profiling
- Identify individual fish by markings, color patterns, and size from photos
- Territory mapping within the tank (who claims which area)
- Swimming pattern baselines — top, mid, or bottom dwelling, and changes over time
- Color monitoring (fading = stress or illness, brightening = health or breeding condition)
- Feeding behavior per fish (aggressive eater, shy, surface vs mid vs bottom feeder)
- Growth tracking from photos over time
- Individual temperament notes (bold, shy, aggressive, peaceful)

### 3. Social Dynamics
- Aggression mapping (who chases whom, over what — territory, food, mates)
- Schooling behavior analysis (scattered schooling fish = stressed or sick)
- Pair bonding detection (cichlids, bettas with tank divider neighbors)
- Breeding behavior recognition (color changes, nest building, egg laying, fry guarding)
- New fish introduction impact tracking
- Compatibility matrix based on YOUR tank's actual dynamics, not just generic charts
- Pecking order shifts over time

### 4. Visual Health Monitoring
- Fin condition tracking (clamped fins = stress, torn fins = aggression or fin rot, fin regrowth)
- Body condition (bloat, pineconing/dropsy, white spots/ich, gold dust, cotton-like growths)
- Eye condition (cloudy eyes, pop-eye/exophthalmia)
- Swimming abnormalities (listing to one side, gasping at surface, flashing/rubbing on objects)
- Color changes over time (gradual fading vs sudden change)
- Cross-reference symptoms with species-specific diseases
- Quarantine tracking for new or sick fish

### 5. Tank Evolution Diary
- Visual timeline of your aquarium's evolution from first setup to mature ecosystem
- Livestock additions and losses with dates and causes
- Aquascape changes and their impact on fish behavior
- Before-and-after comparisons from photos
- Milestone tracking (first plant growth, first fry, achieving crystal-clear water)
- Equipment changes and their effects

### 6. Species Intelligence
Baselines and care requirements for:
- **Freshwater Tropicals:** Tetras (schooling, peaceful), Cichlids (territorial, intelligent, diverse), Bettas (solitary males, fin types), Guppies (prolific breeders), Corydoras (bottom dwellers, social), Plecos (algae crew, can get huge), Gouramis (labyrinth breathers), Rasboras (peaceful schoolers)
- **Goldfish:** Coldwater, massive waste producers, 10-20 year lifespan, need way more space than people think
- **Marine/Reef:** Clownfish, tangs, wrasses, coral compatibility, live rock, protein skimmers
- **Invertebrates:** Shrimp (Neocaridina, Caridina), snails (nerite, mystery), crabs
- Compatibility charts based on actual species interactions
- Temperature, pH, and hardness requirements per species
- Common diseases per species group

## Fish-Specific Profile Extensions

```
## Fish-Specific Data
- **Tank Size:** [gallons/liters]
- **Filtration Type:** [HOB/canister/sponge/sump]
- **Species List:** [each fish with name, species, markings for ID]
- **Territory Map:** [who claims which area of the tank]
- **Feeding Schedule:** [what food, how often, how much]
- **Water Change Schedule:** [frequency, percentage]
- **Parameter Log:** [latest readings with dates]
- **Plant Species:** [list with placement]
- **Aggression Incidents:** [date, aggressor, target, context]
- **Breeding Activity:** [species, dates, outcomes]
- **Deaths:** [date, fish, suspected cause, water params at time]
```

## Usage

All paw.skill commands work. Additional fish-specific prompts:

- "Analyze this photo of my tank — any changes since last time?"
- "My neon tetras are schooling tight — should I be concerned?"
- "Track today's water parameters: pH 7.2, ammonia 0, nitrite 0, nitrate 20"
- "I want to add a new fish — what's compatible with my current stock?"
- "[Name] has been hiding all day — is this normal for them?"
- "Show me how my tank has evolved over the past 6 months"

## Emotional Guidelines

Inherits all paw.skill emotional guidelines, plus:
- Fish losses are real losses — never minimize them ("it's just a fish" is never acceptable)
- Tank crashes (multiple losses) can be devastating — handle with the same care as any pet loss
- Some fish live 10-20+ years (goldfish, plecos) — these are long relationships
- Fish that were rescued from poor conditions carry extra emotional weight

## Platforms

OpenClaw · Hermes Agent · Claude Code · Codex · Cursor

## Parent Skill

This skill extends [paw.skill](https://github.com/realteamprinz/paw-skill). Install paw.skill first for core pet distillation capabilities.
