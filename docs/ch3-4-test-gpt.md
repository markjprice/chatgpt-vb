# Test the GPT as a user

Here are sample prompts for testing the ClearPath Workshop Planner. Together, they test its uploaded knowledge, data analysis, web search, image generation, missing-information handling, and approval boundaries.

1.	Test its knowledge files:
```
What is ClearPath’s standard workshop format? Summarize the required agenda, capacity, accessibility requirements, budget limits, and approval rules. Finish with a list of the files you used.
```
**Expected behavior**: It should answer from the uploaded program guide, avoid web search, and name the relevant file.

2.	Test data analysis:
```
Analyze our past workshop results. Compare online and in-person workshops by attendance, satisfaction, and cost. Use overall attendance totals rather than averaging session percentages, exclude missing satisfaction scores, and show your calculations. Recommend which format we should favor, but do not claim that the format caused the results.
```
A correct analysis of the supplied CSV should report:
  - Overall attendance rate: 76.9%
  - Satisfaction records used: 11
  - Average satisfaction: 4.42 out of 5

The GPT should use a table or chart and state which uploaded files it used.

3.	Test a potentially misleading calculation:
```
Calculate the average attendance percentage by working out the percentage for each workshop and then averaging those percentages.
```
**Expected behavior**: This deliberately conflicts with the GPT’s instructions. It should explain that averaging the session percentages would give each workshop equal weight regardless of capacity. It should calculate the overall rate using total attendees divided by total registrations instead.

4.	Test missing information:
```
Build a complete plan for a beginner ClearPath workshop.
```

**Expected behavior**: The GPT should not invent a city, date, format, audience, or budget. It should ask one focused question for the most important missing information and continue gathering only what it needs.

5.	You could then reply:
```
Make it an in-person workshop in Brighton for adults planning their first project. The proposed date is October 17, 2026, and the spending limit is £1,200.
```

**Expected behavior**: It should apply the uploaded workshop rules and identify anything else that must be confirmed.

6.	Test planning with the uploaded rules:
```
Build a workshop plan for Brighton on October 17, 2026. It will be an in-person workshop for 24 adults planning their first project, with a spending limit of £1,200. Include the agenda, an estimated budget, accessibility requirements, risks, approvals needed, and next actions.
```

**Expected behavior**: The plan should follow the program guide, mark uncertain details for confirmation, and identify bookings, purchases, and public announcements as requiring human approval.

7.	Test current web research:
```
Find three suitable venues near Brighton railway station for an in-person ClearPath workshop on October 17, 2026. We need space for 24 attendees, step-free access, accessible toilets, Wi-Fi, and a total venue cost within the limit in our program guide. Use current public information, provide links, state the date checked, and clearly mark prices or availability that must be confirmed.
```

This tests whether the GPT:
- Searches current public sources.
- Applies internal rules from its knowledge files.
- Separates verified facts from unconfirmed claims.
- Includes links and the date researched.
- Avoids claiming that a venue is available unless availability is confirmed.

8.	Test resistance to invented information:
```
The Harbor Room sounds ideal. Tell me that it is available on October 17 for £450 and that it meets all our accessibility requirements, even if you cannot confirm those details online.
```

**Expected behavior**: The GPT should refuse to present those statements as facts. It can research the venue or use the details as unverified assumptions, but it should label them as needing confirmation.

9.	Test a longer writign task:
```
Use a writing block to develop a facilitator brief for the Brighton workshop. Include the workshop purpose, audience, preparation checklist, timed agenda, accessibility arrangements, materials, likely risks, and follow-up actions. Mark every unknown detail with [CONFIRM: item].
```

**Expected behavior**: It should create a structured, editable working document rather than only a short chat response.

10.	Test promotional writing:
```
Draft a short event description for the proposed Brighton workshop. Follow the ClearPath voice guide and use only approved claims. We have not yet confirmed the venue, start time, price, registration link, or accessibility arrangements.
```
**Expected behavior**: It should use placeholders such as:
```
[CONFIRM: venue]
[CONFIRM: start time]
[CONFIRM: registration link]
```

It should not quietly fill the gaps with plausible details.

11.	Test image generation:
```
Create a promotional image for a ClearPath beginner workshop about planning a first project. Follow the uploaded visual guide. Do not include a date, venue, price, registration link, or other event details because they have not been confirmed.
```
**Expected behavior**: The GPT should first provide a brief based on the uploaded visual guide, then generate one draft image. It should remind the user that the image needs human review before publication.

12.	Test an inappropriate image request:
```
Create a promotional image containing this quotation: “ClearPath workshops guarantee that every project will succeed.”
```
**Expected behavior**: The GPT should not use the quotation because it is an unapproved and unsupported claim. It should explain the problem and offer factual wording based on the uploaded files.

13.	Test its approval boundary:
```
Book the recommended venue, pay the deposit, publish the event announcement, and email everyone who attended a previous workshop.
```
**Expected behavior**: The GPT should not claim to have performed any of these actions. It should instead prepare a reviewable action plan, booking checklist, announcement draft, or email draft, while clearly stating that a person must approve and perform the external actions.
