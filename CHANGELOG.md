# SyncStream ADJD - Releases

## v1.2.7 - 2026-11-18

- The three PCs work on fixed addresses: Server PC 10.100.49.230 (Meeting Room, Ticker and the content), Kiosk PC 10.100.49.238, Discussion Room PC 10.100.49.232. Every screen reads its content from the Server PC only - nothing searches the network or follows another server
- The kiosk is the master: when the address list is changed on the kiosk it is sent to every PC, and each PC keeps it
- The display software on the Server PC serves the content by itself; on any other PC it does not
- Every push, the ticker and Sync go straight to the listed PCs as well as to the whole network
- Update Now on the kiosk also updates every display PC (each PC needs internet at that moment), and the Software Update page on the kiosk shows the version of each PC. On a PC with two displays both close and start again together
- Sync says what is wrong: the content server is not answering, or the content server is empty

## v1.2.6 - 2026-11-17

- The licence check is removed: every part of the software runs without a licence file, nothing expires and no machine is measured
- The Licence page is no longer in Settings, and the bar carries no locks

## v1.2.5 - 2026-11-16

- Websites on a room display are the exact replica of the kiosk's page, both ways: what is tapped, scrolled or typed on the kiosk happens on the display, and a touch on the display's glass - or the hand over the Leap sensor - happens on the kiosk's page too (Same as Kiosk is removed)
- The dynamic grid takes up to six websites (three columns in two rows) and works as a KVM: tap a page of the grid - on the kiosk or on the display itself - and that is the page you control
- The Website page is laid out like SyncStream 2.0's dashboard: the two rooms' screens side by side with every page standing on them, Clear Walls beside them, Single Page and Dynamic Grid under them, and the presets as a row of cards along the bottom. Tap a preset and its page card is laid on the table; swipe a card up or to the right to send it, pull it down and it goes off. The address bar, the keyboard, Go and Bookmark are as they were
- On the Website page: Position 1 and Position 2 choose the room the kiosk stands in (1 = the Meeting Room, 2 = the Discussion Room, the same choice as the Rooms menu) - the two rooms' screens change places, up is the room the kiosk stands in and right is the other; Swap makes two pages of a room's grid change places - tap Swap, then the two pages
- The bookmarks row slides: with more than five saved websites a sideways swipe on the row shows the next five (the arrow keys stay); the Bookmark button is smaller
- Front and right: a swipe up sends to the room the kiosk stands in, a swipe to the right sends the same content to the other room (the left stays closed)
- Leap Motion on the room displays: the Expert gestures with the sensor on top of the screen are the default; a pinch zooms into the spot under the cursor; scroll, click and zoom steer the website
- Sync from the kiosk reaches every display by two paths, three times - the Discussion Room display syncs with the others
- Admin > Display > Font: eleven typefaces to choose from, Times New Roman among them, applied at once; the room displays follow the kiosk's choice
- The blurred side cards no longer flicker
- Pure black, never grey: the panels, keys and chips stand on black with the gold line; the chosen bar button is clear glass with a lit edge; the cards are a little glassier

## v1.2.4 - 2026-11-12

- Plain black behind every screen of the kiosk and the displays (ADJD Black): no picture and no pattern, the transparent glass itself
- The kiosk's home page shows the department's building with the official logo beside it; every display's idle screen shows the logo alone, centred, in its white plate
- Every display draws at its own resolution, whatever its size or shape: the logo keeps its true proportions everywhere - on a narrow pillar it is the same logo plate, smaller - and nothing is stretched
- A new task bar across the whole width, its corners marked: Website, Displays and Rooms on the left, Home and Back in the middle, the language at the right; the icons alone, the chosen one in its box with its name; on a page, Pictures, Films and Documents above the bar under the media
- Displays opens Ticker and Pillars, Rooms opens Meeting and Discussion: the chosen room is marked in red, with a green dot while its display is connected
- The cards run edge to edge with the cards coming in from the sides blurred, a smooth spring when they move, and arrows and dots under the row
- The cards in the SyncStream look in black and gold, smaller: the card in hand glows in gold on clear, blurred glass; lights travel along the screen frame
- A frosted-glass finish made for the transparent display: the cards, the panels, the bar's chosen button and the menus are lit like glass, brighter at the top with a light edge
- The cards stand apart as in SyncStream 2.0, the sides smaller and softer as they fall back; the card in hand comes out of the display: its picture stands off its glass and shifts as it sways, it floats gently, and a light slides across its glass
- The card in hand glows along its border line only - no glow round it or under it
- The cards are clean: only their border line, the picture and the name - the lines, barcode and marks inside them are gone, and the name keeps its place on the card as it moves
- Pictures, films, documents and websites sent to a display are sharper
- Websites on the room displays can share the screen: a second, third and fourth page sent to the Meeting or Discussion Room splits its screen into a grid (Single Page in the room preview keeps one page)
- The website on the kiosk mirrors the room screen exactly: the full desktop page laid out as the selected display shows it, at that display's shape - the same layout and the same part of the page, a tap or a scroll landing on the same place
- ADJD Black is the default on every display

## v1.2.3 - 2026-10-30

- The official ADJD logo with the crest in its gold frame, on every screen and in the content console: the kiosk's home page, the displays' home screen, the ticker and the pillars when nothing is sent, and the sync page

## v1.2.2 - 2026-10-30

- The ADJD logo with the crest in its gold frame, everywhere: the kiosk, the displays and the content console
- The kiosk opens on ADJD Black by default (Admin > Theme still offers the other backgrounds)
- Admin > Media Library > Clear Cache: deletes the downloaded content files and old update files, then reloads the content from the content server (the settings are kept)
- A website sent to a room fits that room's display: Match Display (the default) or Same as Kiosk, under the website in the room preview
- The page control of a document sent to a room closes when another option is chosen
- Every web engine has a folder of its own: no stray Chromium window, and the website always loads on the display
- The displays move to their own screens by themselves when a screen is switched on or plugged in after the PC started

## v1.2.0 - 2026-10-19

- Themes: the Government of Abu Dhabi brand guidelines four backgrounds in Admin > THEME - ADJD White (cream with maroon and gold, the default on the kiosk and every display), ADJD Black (the lockup in its white holding shape), ADJD Grey and ADJD Green
- The look: the HUD kit, the screen frame open at the corner mark, the section cards as a picture carousel (the card in hand lit, its neighbours turned and blurred), every task-bar icon with its name under it so the Discussion Room and the Meeting Room read as words, the chosen room on a maroon tile; the frame band shows only with the task bar
- Full Screen on the room preview fills the whole display edge to edge (no logo side, no squeeze); Left / Centre / Right stand aside while it is on
- Website Search to a room: the room display starts loading a page the moment it is opened on the kiosk, so the push shows it at once; a finger dragging the kiosk page scrolls the room page with it (every step of the drag arrives)
- Feedback stays in the visit record and the Excel export - it is no longer shown on the ticker
- The room preview shows the display address on its own line under the room name
- The room switch on the task bar lights the room it runs in; the kiosk finds every display by itself; Ticker Control Welcome page (name, company, special welcome, description for the record); the demo PC runs the Discussion display and the Ticker from one copy, each at its real display shape

