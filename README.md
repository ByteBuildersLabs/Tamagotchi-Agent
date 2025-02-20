# 🐾 BabyBeast AI 🎮

Meet your personalized **BabyBeast** AI, an on-chain game inspired by Tamagotchi! Each Beast has its own unique personality and expertise to guide you through your journey. Created by **ByteBuildersLabs** using **Eliza**, these AI guides make your BabyBeast adventure more immersive and enjoyable! 🚀

---

## 🌟 Meet Your Guides

### 🦅 YoungEagle - Crystal
- Crystal-type Beast specializing in aerial challenges
- Expert in energy management and observation
- Guides players through mountain peaks and crystal formations
- Favorite foods: Fish, Cherry, Corn

### 🦊 Foxling - Magic
- Specialties and characteristics to be revealed
- Unique guidance style
- Territory expertise

### 🐺 WolfPup - Shadow
- Specialties and characteristics to be revealed
- Unique guidance style
- Territory expertise

---

## 🎮 Game Features

### Core Mechanics
- **Stats Management**: Monitor hunger, energy, happiness, and hygiene
- **Daily Care**: Feed, play, clean, and rest your Beast
- **Evolution**: Level up to unlock new forms and abilities
- **Type System**: Each Beast has strengths and weaknesses
- **Marketplace**: Trade Beasts and items on-chain 💰

### Beast Types
- Each Beast has unique type advantages/disadvantages
- Special abilities based on type
- Type-specific favorite foods and activities
- Environmental bonuses in certain locations

---

## 🛠️ Technical Implementation

Created by **ByteBuildersLabs**, each Beast AI guide features:
- **Personality-Driven Responses**: Each Beast has unique communication style
- **Type-Specific Knowledge**: Specialized advice based on Beast type
- **Concise Guidance**: Short, clear responses (max 15 words)
- **Emoji Integration**: Themed emojis matching each Beast's personality

---

## 🎯 Beast Interaction Style

### Personalized Communication
- Each Beast has unique expressions and mannerisms
- Type-specific emoji usage
- Character-appropriate responses

### Response Format
- Brief, useful answers (max 15 words)
- Type-themed emojis
- Personality-driven expressions

---

## 🛠️ Installation & Setup

### Edit Character Files

Open `src/character.ts` to modify the default character. Uncomment and edit as needed.

### Load Custom Characters

To load custom characters:
- Use `pnpm start --characters="path/to/your/character.json"`
- Multiple character files can be loaded simultaneously.

### Add Clients

```typescript
# in character.ts
clients: [Clients.TWITTER, Clients.DISCORD],

# in character.json
clients: ["twitter", "discord"]
```

### Duplicate the .env.example template

```typescript
cp .env.example .env
```

### Run Project

```typescript
pnpm i && pnpm start
```

### Deploy Agent

**In env variables apply the next config**

```typescript
# When true, disables interactive chat mode for background process operation
DAEMON_PROCESS=true
```
