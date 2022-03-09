# Intel Holiday Calendar

👉 Synchronized web calendars with Intel Holidays for various regions.

1. Go to <https://outlook.office.com/calendar/view/week>.
2. Click on `Add Calendar`.
3. Select `Subscribe from web` tab.
4. Provide URL, provide details.

   ```url
   https://github.com/dseynhae/Intel-Holiday-Calendar/blob/main/Intel-Holidays-UNITED-STATES.ics
   ```

   ⚠️ A web calendar needs to be accessible from a public URL.

   * The source URL for the calendars won't work:

      ```url
      https://phonebook.fm.intel.com/ww/ics/Intel-Holidays-UNITED%20STATES.ics
      ```

      Therefore, the different region calendars are copied from this internal location, to the WAN-accessible URL in GitHub.

   * This will NOT work when using a 1Source Sandbox repository (the URL is still internal)!

5. Import, close `Add Calendar` popup.

---

This repository holds all the components to make this happen.
