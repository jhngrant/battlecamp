# Wardley Maps BattleCamp

A Wardley Map BattleCamp is an advanced Wardley Map workshop dedicated to teaching and training people (and robots!) to do Gameplay. Its purpose is to show that there are other important phases of the Wardley Map Strategy Cycle, such as "Climatic Patterns", "Doctrine" and "Gameplay".

The **focus** of this workshop is **on playing the "game"**. Its goal is to help attendees to utilize all of the phases of Wardley Map Strategy Cycle and understand that you will be doing all of the phases in a real-life scenario.

**You should do all of the phases**.

Not:

- "I'm just going to do a gameplay move"
- "I'm just going to do a map"
- "I'm just going to predict based on a map and some climatic patterns"
- "I'm just going to optimize a bit my company using the Doctrines"

The purpose is to do all of the phases and to practice them.

*Note:* This workshop is a "simulation" of a real-life scenario. Consider it as such, a simulation.

## Requirements to Attend

In order to attend a workshop, you should at least have read the book / created several Wardley Maps yourself, read and learned some of the Climatic Patterns, Doctrine and Gameplay. This is an advanced workshop which expects attendees to have at least some real-life experience with Wardley Maps.

## Requirements to Organize

In order to organize a workshop yourself, you must have at least played two BattleCamps in the past.
It's not mandatory, though the rules and the game are complex and require experience with Wardley Maps.

Public and community events must be free, in case you're doing something privately, you are free to charge for your time.

## Workshop Structure

### The Goal

To Win. To be the dominant company in the given market.

### Your role and the attendee structure

You are a company board member.

Attendees are divided into two teams with random team members.
*(In real life, you will rarely have the choice over who you work with, so it's better to learn to cooperate and create a team atmosphere focusing on a common goal)*

**There needs to be a team of at least two judges which keep track of the workshop statistics and gameplay.**

Each company team belongs to a single company, which is doing business in a single market. Each company has a different scenario.

**Two or three teams of random team members. Minimum 3 members per team. Equal members per team.**

### Game structure

Turn based. Simultaneous turns. Max 40 rounds.
The teams need to be in different rooms.

### Structure

Each company has three main resources.

1. Time (represented in points, each team has 10 time points per round.)
2. Capital (represented in cash, e.g. dollars)
3. Market share (represented in percentages)

All companies operate in a single market developing a single product. 

#### Market and Income

The market size is 100,000 total units sold per quarter (round).

`Market share` * `the total market size` * `your product price` = `your revenue you have made`.

*Example:*
Your market share = 8% ~ `0.08`
Your product price = `$100`

`0.08` * `100,000` * `$100` = `$800,000` revenue / round.

But **this isn't your income.** :) You must subtract the product cost (which is calculated by using the capital flows of your Wardley Map, if you don't have a map, well, you won't know which components cost the most).
If your product cost is `$80` per product sold, your income would be `$160,000`.

The judges **must** calculate the income each round for each company. The judges **must not** share data between teams.
_(A good team will understand that they should calculate the other team's income too)_

### Product Cost

Product cost is calculated using the Capital Flows of your Wardley Map.

![Capital Flow Example](https://github.com/simalexan/battlecamp/images/capital-flow.png "Example Capital Flow")

### Product Price Elasticity

The price is elastic in an easy setting.

## BattleCamp Cards

Cards from the first, initial BattleCamp are going to be open source and in the folder `cards`. We will be slowly adding them.

The card data is contained in the `src/cards.json`. You can change the data there and then use `generate-cards.js` to generate a new set of cards with the updated information and in different colors, text, effects and so on.

## Rights

Wardley Maps belong to Simon Wardley.

Battle Camp is following the licenses defined by the Wardley Maps, and is under the CC by SA 4.0 license.
