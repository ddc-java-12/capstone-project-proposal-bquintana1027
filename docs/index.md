## Summary

Timely is a time tracking application that allow users to track their work and creative hours all in one place.


## Intended users

Creatives who work on multiple contracts.

As a digital freelancer with a crazy schedule I want to be able to track my time spent on specific projects. This will help me when billing hourly for services.

Creatives who are early in their careers.

As a creative who loves to be immersed I want the ability to see what I spend most of my time to help me create better time management.

## Client component

* **Functionality**

  User will be able to

Track time spent on projects.
- Utilize the application management for a team, project and specific client.
- Data collection (Hours spent per project, client and price points for billing)
- Reports (Total Hours, Total Projects, Projects per client, Hours per project)
- Calendar and Project History
- Timing feature that accurately tracks by start and stop feature.

* **Persistent data**

    Summarize, in general terms, what content will be stored on the client side. This should include any information that a user of your system should expect to be maintained locally (i.e. without connection to a server) across multiple sessions of use, on a single device. 
    
* **Device/external services**

    If the client component will need to access special services of the device (e.g. sensors, contacts, messaging), list them here. Also, if the client component will need to access already-existing external services (e.g. real-time weather data, Open Trivia Database), those should also be listed here; any such references to external services should include links to the main page or API description page for the service.
    
For listing multiple items, please use bullet lists (or ordered lists, if order is relevant), not just separate lines or paragraphs of text.
    
## Server component

* **Functionality**

- Persistent data
- User Profiles
- User History
- Calendar
- Timing

* **Persistent data**

    Summarize, in general terms, what content will be stored on the server side. This should include any information that a user of your system should expect to be accessible across multiple sessions of use, even if accessed from separate devices. In addition, if there will be data originating from some users that will then be accessible by other users, it should be part of the persistent data on the server. 
    
* **External services**

Tag entry system

which would allow us to create entries with multiple tags. We could then view each tag by project, client etc. This would also allow us to list time entries by tag within certain date ranges.
Google Calender API

https://developers.google.com/calendar
I believe I could use Google Calendar API as the primary calendar the app would use to track activity across pages.
Timing Logger

https://developer.android.com/reference/android/util/TimingLogger
Not sure if this is considered an external service if this API is created by Android Developers. But the ability to track time across multilpe events & dates is a core element to making this application work.

Stretch goals/possible enhancements

Ability to track hours for a project over a weekly or bi-weekly period and produce invoice based on the services and hours rendered.