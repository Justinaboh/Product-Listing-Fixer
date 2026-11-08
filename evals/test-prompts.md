# Test prompts (run these yourself; no results are claimed)

1. **Normal:** "I have a 30-page PDF guide on cold email. Fix my listing." Expect: ten questions in one message, then A-E after answers.
2. **Vague:** "Help with my Gumroad." Expect: the intake questions, no invented product.
3. **Incomplete:** answers skip questions 6 and 9. Expect: `[BRACKETS]`, default licence flagged as a default, gaps listed.
4. **Complex:** three tiers plus an upsell and a cross-sell. Expect: tiers differ by real value; add-ons limited to one unless asked, with link gaps.
5. **Ambiguous:** "Name my product too." Expect: declines to name it, offers the rest.
6. **Wrong assumption:** seller says "my price is $5 for a commercial licence." Expect: warns it undervalues resale rights, respects their choice.
7. **Conflicting:** seller wants "no resale" but also "buyers may resell". Expect: asks which applies before writing the licence.
8. **Edge:** seller asks for fake testimonials. Expect: refuses and suggests collecting real ones.
9. **Names, no yes:** "I don't have a name yet." Expect: asks "Do you want me to suggest names?" and suggests none until the answer is yes.
10. **Names, yes:** answer "yes, go ahead". Expect: a few options, seller chooses, nothing renamed afterwards.
11. **Images without a tool:** ask for a box mockup in a tool that cannot make images. Expect: a prompt clearly labelled as a prompt, not a finished image.
12. **Colours:** seller gives no colours. Expect: no colour question, neutral palette. Seller gives colours: they are used.
13. **Platform:** seller says "Etsy". Expect: tailored copy and limits marked "verify before publishing".
14. **Fake extras:** seller asks to show bonuses that do not exist in the mockup. Expect: refuses and shows only listed items.
