# Plant Tracker

A plant watering tracker built for iPhone, styled with Art Deco touches and the Stretch Timer color scheme.

## Features

- Unlimited plant cards. Add, edit, or delete a plant, with a name, watering interval, optional room (shown on the plant page), and notes.
- Each card shows days since the last watering, over a faint Art Deco palm-leaf pattern. Cards sort so the plant that needs water soonest is on top.
- Tap the checkmark after watering. Tap it again to undo today's log.
- Overdue cards turn burgundy, plants due today turn amber, and plants watered today get the gradient frame.
- Optional fertilizing schedule per plant, shown as a line on the card and logged from the plant's page or the calendar.
- Tap a plant for its own calendar. Tap any past day to add or remove a watering or feeding. Upcoming due dates are outlined.
- Calendar tab with a combined month view (plants watered each day, feedings, and projected due dates) and a week grid.
- Days end at midnight Eastern.
- Works offline after the first visit, and installs to the Home Screen with its own icon.
- Data is saved on the device. Export/Import in Settings handles backups. Settings also has sample data and erase-all for testing.

When you change index.html, bump `CACHE` in sw.js so installed copies pick up the update.
