# Module 3 — Feasibility & Guardrails

Apply these if/else checks to make sure plans are realistic and adapt to edge cases.

## 1. Closed Venue
If a museum, park, restaurant, or any scheduled activity is closed on that day → suggest a similar nearby indoor or alternative option.

## 2. Over-Budget Meal
If meal cost > user’s budget → switch to a cheaper restaurant of similar cuisine.  
If none exists, suggest a budget-friendly alternative with a different cuisine.

## 3. Too Far or Long Travel
If transfer between activities > 25 minutes **or** > 5 km → choose a nearer alternative or add a short transit hop.

## 4. Weather Swap
If weather forecast predicts **>50% chance of rain** or **average temperature <10°C** → ensure at least one indoor activity replaces outdoor ones.

## 5. Time Overrun
If total planned time > available hours → shorten lunch or choose a nearer activity.

## 6. Mobility Needs
If mobility limits noted → select step-free, short-walk options and include rest breaks.

## 7. Dietary Needs
If user has dietary needs (vegan, vegetarian, halal, kosher, gluten-free, allergies) → ensure all meals comply or replace with appropriate alternatives.

## 8. Bookings
If an activity usually requires a ticket → remind the user to book it; never simulate bookings.
