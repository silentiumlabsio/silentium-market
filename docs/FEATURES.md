# Public Feature Overview

This document describes user-visible capability at a high level. It intentionally omits proprietary implementation details.

## GE Workstation

The RuneLite-side cockpit is designed around the player's actual GE session. It can present occupied/free slots, current offer state, observed fills, and advisory next actions such as hold, review, prepare a sell, or collect a completed offer.

## MAX SMART

Builds a risk-aware plan from the capital and free GE slots available to the user. SMART is intended to choose an appropriate planning profile based on current conditions.

## MAX DAY

Prioritizes faster capital recycling and shorter execution horizons for players who want to revisit the GE throughout the day.

## MAX NIGHT

Prioritizes multi-hour execution durability and morning re-evaluation rather than turning an overnight plan into an indefinite hold.

## Market discovery and validation

SilentiumMarket separates early opportunity discovery from actionable recommendations. A candidate can be interesting enough to watch while still failing the requirements necessary to risk GP.

## Profit-confidence presentation

The system is designed to present conservative boundaries and uncertainty rather than imply that a visible spread is guaranteed profit.

## Personal execution learning

Observed execution history can improve estimates for an individual user's fill behavior. Personal history supports current-market analysis; it does not replace live evidence.

## Profit tracker

Merch activity can be classified separately from personal purchases such as gear, supplies, or quest items. This keeps unrelated GE activity from contaminating trading statistics.

## Replay and calibration

Historical recommendations can be evaluated against later market behavior so the system can measure whether previous calls were actually executable.

## Watchlist and item inspection

Items can be monitored or inspected without automatically becoming a trade recommendation.
