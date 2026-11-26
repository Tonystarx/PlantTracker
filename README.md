# Plant Tracker

A plant watering tracker built for iPhone, styled with Art Deco touches and an aqua-to-dark-green gradient palette.

## Features

- Unlimited plant cards. Add, edit, or delete a plant, with a name, an optional check interval (how often to check whether it needs water), optional room (shown on the plant page), and notes.
- Each card shows days since the last watering, over a faint Art Deco palm-leaf pattern. Cards sort so the plant due for a check soonest is on top; plants with no check interval follow, longest since watered first.
- Tap the checkmark after watering. Tap it again to undo today's log.
- Overdue cards turn burgundy, plants due today turn amber, and plants watered today get the gradient frame.
- Optional fertilizing schedule per plant, shown as a line on the card and logged from the plant's page or the calendar.
- Tap a plant for its own calendar. Tap any past day to add or remove a watering or feeding. Upcoming due dates are outlined.
- All tab: a sortable list of every plant with its room and adoption date. Tap a name, room, or date to edit it in place, tap the arrow to open the plant, or use Add plant at the bottom of the list.
- Optional adoption date for each plant, set when adding or editing it.
- Calendar tab with a combined month view (plants watered each day, feedings, and projected due dates) and a week grid.
- Days end at midnight Eastern.
- Works offline after the first visit, and installs to the Home Screen with its own icon.
- Data is saved on the device. Export/Import in Settings handles backups. Settings also has sample data and erase-all for testing.

When you change index.html, bump `CACHE` in sw.js so installed copies pick up the update.
