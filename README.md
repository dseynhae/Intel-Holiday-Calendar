# dseynhae.intel-web-calendar

👉 Synchronized web calendars with Intel Holidays for various regions.

   1. Go to <https://outlook.office.com/calendar/view/week>.
   2. Click on `Add Calendar`.
   3. Select `Subscribe from web`.
   4. Provide URL, provide details.

⚠️ A web calendar needs to be accessible from a public URL.

 This will NOT work when using a 1Source Sandbox repository (the URL is still internal):

 ```url
 https://github.com/intel-sandbox/dseynhae.intel-web-calendar/blob/main/Intel-Holidays-UNITED-STATES.ics
 ```

The internal URL <http://phonebook.intel.com/cgi-bin/phonecal?e=> doesn't work for that; Therefore, the different region calendars are copied from this internal location, to a this WAN-accessible URL.

This repository holds all the components to make this happen.
