# Changelog

## 1.4 (11)

- This is a re-issue of the last release.

## 1.4 (10)

### Features

- Added "Return to title" button on game end and pause screen.
- Added close button to options screen.
- Improved game state management behind the scenes by adding finite state machines to scripts.

### Bug Fixes

- Fixes rendering issues with options on iPad.

## 1.4 (9)

### Features

- Added new options scene with persistent data.
- Updated CandyCoded and Unity iOS Bridge packages.

## 1.4 (8)

### Features

- Updated AR Foundation Components package.
- Updated Unity AR Foundation and ARKit packages.

## 1.4 (7)

### Features

- Updated to Unity 2019.1

### Bug Fixes

- Updated AR Foundation Components to fix a bug introduced in a previous version.

## 1.4 (6)

### Features

- Improved anonymous analytics for debugging hand rankings. [Example of collected data.](https://gist.github.com/neogeek/a4dc6feb794802d41166317c7eae27ae)

## 1.4 (5)

### Features

- Added anonymous analytics for debugging hand rankings.
- Updated packages.

## 1.4 (4)

### Features

- Added new card design to improve visibility while playing in AR.
- Improved flicking of cards.

### Bug Fixes

- Fixed issues with UI scaling on mobile devices smaller than the iPhone X.
- Fixed an issue where the table would appear to be glitching when placing in AR.
- Fixed an issue where the cards would be flicked really far away if let go at the top of the screen.
- Fixed an issue where letting go of a card under another card would cause the card to get stuck.
- Fixed issue where the game would not end if the deck was empty.

### Known Bugs

- Cards appear cut off on some mobile devices while playing in AR.
- Pause button is hard to hit.
- Some games complete with "No Winner" or "Playing/Computer wins with Nothing".
- AR works on some Android devices. Confirmed working on Nokia 7.1, broken on Google Pixel 2.
- Sometimes a card will be missing from the river.
- Sometimes a card will not be collected from the table when another game starts.
- Sometimes the timer will go missing. Full restart required to fix.

## 1.4 (2)

### Bug Fixes

- Fixed issue where computer player would discard cards that should be played and play cards that should be discarded.
- Fixed issue where computer player wouldn't take time between moves to think.
- Fixed issue where cards were placed incorrectly on the table making them appear inside each other and the table.
- Fixed issue where cards would sometimes be discarded if they landed face up.
- Fixed issue with cards colliding with each other.
- Fixed issue where card shadows were missing.
- Fixed issue where the player could continue playing cards after a hand was completed.
- Fixed issue where cards were being placed on the table face up.
- Fixed issue where the last card played would sometimes be removed from the table when the game was completed.

### Features

- Added pause functionality.
- Changed animation of the timer to animate each second rather than the duration of the timer.
- Moved timer to the center of the screen for better visibility.
- Hide all UI when the game is completed or when the game is paused.

### Maintenance

- Updated Unity packages.

### Known Bugs

- Cards in hand appear under notch of iPhone X/XS.
- Scale of UI elements is only correct on iPhone X/XS.
- AR doesn't work in Android version.
