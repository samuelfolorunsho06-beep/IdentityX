IDENTITYX CONVERSION ENGINE V11

V10 visual language is preserved.

NEW CONVERSION LAYER
1. Each lead category now has deeper industry-specific persuasion below the hero.
2. Campaign attribution is supported through URL parameters.
3. WhatsApp messages automatically carry the experience/campaign/source/lead attribution.
4. Lightweight funnel events are recorded locally in the visitor browser:
   page_view, scroll_50, pricing_view, difference_click, whatsapp_click.

EXAMPLE CAMPAIGN LINKS
business.html?src=whatsapp&campaign=ilorin-business
gym.html?src=whatsapp&campaign=ilorin-gym
school.html?src=whatsapp&campaign=ilorin-school
professional.html?src=linkedin&campaign=career-outreach

OPTIONAL INDIVIDUAL PROSPECT TAG
business.html?src=whatsapp&campaign=ilorin-business&lead=prospect-001

When that prospect clicks WhatsApp, the prefilled message includes the experience,
campaign, source and lead tag, so you can identify what converted them.

NOTE
Local browser events are the instrumentation foundation. V12 can connect these events
to a persistent analytics endpoint/dashboard and add a fallback lead-capture mechanism.
