# Meal Planning and Recipes

A personal meal planning system for organizing weekly dinner plans, recipes, and shopping lists.

## Overview

This repository contains a simple but effective meal planning workflow that helps track weekly dinner plans, maintain a recipe collection, and generate shopping lists. The system is designed to work with AI assistants (like Claude) to help plan meals while avoiding repetition and considering weekly schedule constraints.

## File Structure

### Core Planning Files

- **`mealplan.md`** - The main meal planning log. Contains a chronological record of weekly dinner plans going back in time. Each week is listed with Sunday through Friday meals. This file helps track what you've eaten recently to avoid falling into a rut.

- **`print.md`** - The current week's meal plan in a printable format. Contains:
  - The week's meals organized by day (Sun-Fri)
  - Recipe notes for the week's meals
  - Shopping list organized by category (Produce, Meat, Thaw, Dairy/Frozen, Pantry)
  - This file is updated each week and can be printed or viewed on a device while shopping

- **`recipes.md`** - A collection of recipes and cooking notes. Recipes are organized by category (Rice Bowls, Starches/Carbs, etc.) and often contain simplified notes rather than full recipes, focusing on key techniques and ingredients.

- **`freezer.md`** - An inventory of items currently in the freezer. Helps track what's available for meal planning and what needs to be used up.

### Configuration Files

- **`CLAUDE.md`** - Instructions for AI assistants on how to help with meal planning. Contains:
  - Meal prep strategy preferences
  - Weekly schedule considerations (e.g., Monday/Tuesday evening activities, Thursday early departure)
  - Formatting guidelines for meal descriptions and shopping lists
  - Rules about meal planning (e.g., avoid quinoa, include protein and vegetables)

- **`test-recipes.md`** - A testing/development file for recipe-related functionality.

### Excluded Files

- **`Calorie Plan/`** - This folder contains personal calorie tracking files and is excluded from the repository via `.gitignore` for privacy.

## How to Use

1. **Weekly Planning**: Review `mealplan.md` to see recent meals and avoid repetition
2. **Plan Meals**: Work with an AI assistant (using `CLAUDE.md` as context) to plan the week's dinners
3. **Update Files**: 
   - Add the new week to `mealplan.md`
   - Update `print.md` with the current week's plan and shopping list
   - Add any new recipes to `recipes.md`
4. **Shop**: Use `print.md` as your shopping reference

## Meal Planning Philosophy

- Focus on dinner planning only
- Plan meals that create leftovers early in the week (rice, baked potatoes, roast veggies) that can be reused
- Consider weekly schedule constraints (evening activities, early departures)
- Include a protein and vegetable with each meal
- Use concise, comma-separated meal descriptions

## License

This is a personal project. Feel free to use it as inspiration for your own meal planning system.

