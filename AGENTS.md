# Agent instructions: Meal planning

## Meal Prep Strategy

We like preparing meals that create leftovers early in the week, like rice, baked potatoes, roast veggies, etc, that can become staples and used in other meals during the week.

## Focus

Focus on dinner planning only

## Weekly Schedule Considerations

- **Monday and Wednesday**: Lacrosse nights — plan lighter, quicker dinners
- **Thursday**: We leave the house early at 3:30 pm and aren't home until after 6:30 pm
  - Good day for either very fast meals (like simple pasta aglio olio)
  - OR instant pot / pressure cooker meals that can be made ahead of time

## Meal Planning Process

### Default workflow: brainstorm in chat, write to the plan only when asked

- **Do not edit `mealplan.md` unless the user explicitly asks** (e.g. "add that to the plan", "update the meal plan", "record Monday as …").
- Default to **brainstorming and proposing ideas in the conversation** — varied options, tradeoffs, and fit with the weekly schedule — then let the user choose what to commit.
- When the user shares what they actually ate or decided, **confirm before writing** unless they clearly asked you to log it.
- Creating or extending a week header (e.g. a new "### Week of …" block) is still an edit — only do it when asked, except for logging meals the user explicitly told you to record.

### Using the meal plan file

- Use `mealplan.md` as the running record of **committed** meals and dates, so we don't fall into a rut or repeat the same things.
- **Note**: `mealplan.md` is organized in reverse chronological order, with the newest/most recent weeks at the top.
- When brainstorming, read recent weeks in the meal plan to avoid repeating suggestions already offered or recently eaten. Provide fresh, varied ideas in chat.
- If a recipe is committed to the plan but isn't in the recipes list, ask whether to add it to the recipes list.
- Use concise, comma-separated format for meal descriptions (e.g. "pasta aglio olio, chicken, salad stuff" rather than "pasta aglio olio with precooked chicken and salad stuff").
- We typically try to include a protein and a vegetable with each meal.
- **Avoid quinoa** - we don't like it.

## Print File Format

The print.md file should follow this specific format:

```
### Week of [Date]

Sun:
[meal description]

Mon:
[meal description]

Tue:
[meal description]

Wed:
[meal description]

Thu:
[meal description]

Fri:
[meal description]

-----

## Shopping List

| **Produce** | **Meat** | **Thaw** | **Dairy/Frozen** | **Pantry** |
|-------------|----------|----------|------------------|------------|
| [item] | [item] | [item] | [item] | [item] |
| [item] | [item] | [item] | [item] | [item] |
```

The shopping list should be organized into a markdown table with these columns (only include columns that have items):

1. **Produce** - fresh vegetables, fruits, herbs
2. **Meat** - fresh meat, seafood, poultry
3. **Thaw** - frozen items to defrost
4. **Dairy/Frozen** - dairy products and frozen items
5. **Pantry** - dry goods, condiments, spices, etc.

**Note**: The shopping list is built together line by line during the planning conversation, not automatically generated.