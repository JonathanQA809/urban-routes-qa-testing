# Bug Reports

---
## Bug #1: The "map zoom plus button" on the "Urban Routes App" is missing

**Description**

The “map zoom plus button” is not showing anywhere on the map.

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must be login “Urban Routes App”

User must have the “Sprint 1 Project: Test Cases” PDF open 

**Test Steps:**

Login to “tripleten learning platform”

Navigate to Project 1: Task - TripleTen

Scroll down the page and click on “Start button”

Scroll down the same page and click on “Test cases pdf” 

Open “Test cases pdf” in new window

Read “ID Case-2”

Open “Urban Routes App” On new window

Execute “ID Case-2” on Urban routes app

Look for the “Plus Button” and click to zoom the map 

**Expected result:**

The zoom level changes by one value. All objects are rendered according to the design. 

**Actual result:**

When looking for the “Plus zoom button” on the “Urban Routes App” it wasn't there.

I “refresh” the page to see if it was a caching problem, but the page went completely blank.

I restarted the server the app was able to load. but still no button was found.

**Environment**

OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)

---
## Bug #2: The "search field" in the "FROM" search section of "Urban Routes App" is not empty

**Description**

When I click on the "From" search field in the top-left corner of the app, it displays a pre-filled street address instead of being empty.

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must be login “Urban Routes App” 

**Test Steps:**

Read “ID Case-4”

Open “Urban Routes App” On new window

Click the "From" field on left corner of the app.
 

**Expected result:**

The "From" field is selected, the cursor is blinking inside the field, and the field is empty and ready for input.
 

**Actual result:**

when clicking on the “From” field it displays a street address instead of being empty. The street address shown is “East 2nd Street, 601”

**Environment**

OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)

---
## Bug #3: When typing "Subway" into the "To" search field in the Urban Routes App, the list of station suggestions does not appear.

**Description**

When Typing "Subway" into the "To" search field does not display the list of subway stations as expected.

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must have “Urban Routes App” open
 

**Test Steps:**

Read “ID Case-5”

Open “Urban Routes App” On new window

Click the "To" field on left corner of the app.

Type “Subway”
 

**Expected result:**

when the cursor appears and blinks in the "To" field. As the word "Subway" is typed, a list of subway stations needs to show below the field.
 

**Actual result:**

After typing "Subway" into the "To" field, no dropdown list or station suggestions appear.

**Environment**

OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)

---

## Bug #4: When clicking the "To" search field in the Urban Routes App and typing an address, nothing happens — the map does not respond or update. 

**Description**

When a user clicks on the "To" search field and types in a valid address, the app does not respond. The map does not zoom in or display a location pin, and no visual feedback is shown to confirm the input.

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must have “Urban Routes App” open

 

**Test Steps:**

Read “ID Case-6”

Open “Urban Routes App” On new window

Click the "To" field on left corner of the app.

Type “An address”

 

**Expected result:**

The "To" field is selected with a blinking cursor.

The field is initially empty and ready for input.

After entering the address, the map zooms in on the location pin.

The map view matches the design specifications.

 

**Actual result:**

When the user types an address into the "To" field, nothing happens. For example, entering "221B Baker Street" does not trigger any response from the app — the map does not update or show a pin. A second attempt with a different address, "3275 S. John Young Pkwy," also produced no result. 

**Environment**


OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)

---
## Bug #5: When a user types an address into the "From" search field in the Urban Routes App, the map does not respond.

**Description**

In the “Urban Routes App”, when a user clicks on the "From" search field and enters a valid address, the app does not respond. The map does not zoom in, no location pin appears, and the view remains unchanged.

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must have “Urban Routes App” open

 

**Test Steps:**

Read “ID Case-6”

Open “Urban Routes App” On new window

Click the "From" field on left corner of the app.

Type “An address”

 

**Expected result:**

The "From" field becomes active with a blinking cursor.

After entering a “valid address”, the map zooms in on the corresponding location pin.

The “map view” matches the expected layout and design.

 

**Actual result:**

When the user types a valid address into the "From" search field in the Urban Routes App, there is no response from the app. 

The map does not zoom in or display a location pin. For example, entering "3275 S. John Young Pkwy" and "7007 Sawmill Circle" produced no result.

The view didn't match the design in the description.

**Environment**


OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)

---
## Bug #6: In the "Urban Routes App", the Landscape Mode button is incorrectly labeled as "Terrain", and does not match the expected design.

**Description**

The “Map Mode” options in the “Urban Routes App” include a button labeled "Terrain". When we Look into the design and test case, this button should be labeled "Landscape." This mislabeling may cause confusion for users trying to select the correct map view, even though the functionality and visual rendering are correct.

 

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must have “Urban Routes App” open

Map interface is visible

 

**Test Steps:**

Open “Urban Routes App” On new window

Hover the cursor over the “Map Mode button”

Hover the cursor over the “Landscape Mode option”

Click on the “Landscape Mode button”

Hover the cursor over the “Satellite Mode option”

Click the “Satellite Mode button”

 

**Expected result:**

The map mode button is labeled "Landscape" as specified in the design. 

When selected, it renders the correct map view, and the label reflects the mode.

 

**Actual result:**

When the user hovers over the Map Mode options, the button intended to display "Landscape" instead shows "Terrain." 

All other functionality works as expected.

The map switches to the correct view, and the design behaves as intended, but the label is incorrect.

**Environment**


OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)

---
## Bug #7: The minus icon for zooming out is missing from the map interface in the Urban Routes App, making it not easy for user to manually decrease the zoom level.

**Description**

The user wasn’t able to find the minus icon button used for zooming out of the map. The instructions says for the user to click the minus icon five times to reduce the zoom level, but this control is not visible or accessible anywhere on the interface. All other steps in the test case, including accessing Street View and 360 scrolling, worked as expected. 

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must have “Urban Routes App” open

The map interface is visible

 

**Test Steps:**

Scroll the map by street area

Set the maximum zoom level

Click the minus icon 5 times

Drag the Street View icon and drop it on any street

Scroll over the picture in Street View

 

**Expected result:**

The minus icon should be clearly visible on the map interface 

Clicking it should reduce the zoom level incrementally

 

**Actual result:**

The minus icon is not present on the screen

The user cannot zoom out using the controls

Zooming out using mouse scroll works as expected, but the minus button is missing

**Environment**


OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)

---
## Bug #8: When the user clicks on the "Urban Routes logo" there's no response, it does not display any app information

**Description**

When the user clicks on the “logo” in the “Urban Routes App”, nothing happens, there's no information been display about the app.

 

**Preconditions:**

User must have “internet connection”

User must be login to “tripleten learning platform”

User must have “Urban Routes App” open

The home screen is visible.

 

**Test Steps:**

Open “Urban Routes App” On new window

Move curser to the upper left corner of the app

Click on the logo

 

**Expected result:**

Clicking the logo should open or display the app information section.

 

**Actual result:**

When the Use Clicks on the logo there’s no effect. The app does not display any app-related information or change views.

**Environment**


OS: Microsoft Windows version 24h2 (OS Build 26100.3915)

Browser: Microsoft Edge Version 136.0.3240.64 (Official build) (64-bit)
