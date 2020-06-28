# Tarkov Price Checker Design Thoughts

This page outlines the design considerations for Tarkov Price Checker, including standard use case.
MVP (Minimum viable product), and future features.

## Standard Use Case
These are the steps of the simplified outline of how the program will work
1. User is playing Tarkov
2. User enters a hotkey on their keyboard
3. User is informed of how much the item is worth

## MVP
The bare minimum functionality are as follows:
- Pre-defined hotkey
- Program checks an offline DB
- DB contains trader or fleamarket prices

## Possible Technologies
- AHK. Can be used to scan the screen for either text or an image
- SQLLite for DB. Python has sqllite library