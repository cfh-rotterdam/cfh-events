# CFH Events

Calendar of upcoming CFH events for the coaches: https://cfh-rotterdam.github.io/cfh-events/

- Events are stored in Firebase Realtime Database (`cfh-holiday-planning`, path `/events`), shared with the CFH Holiday Board.
- Anyone can view. Only the admin account can add, edit or delete events: use **Admin sign in** at the bottom of the page.
- `events.json` is the initial import from the CFH Communication Calendar and the read-only fallback when the database is empty.
