# Alert Box

A Material-You themed inbox app which logs all notifications and filters out spam, allowing you to revisit your past notifications.

## Why

We get bombarded with notifications on a daily basis, some more important than others. 
Sometimes there will be social media recommendations which we dismiss due to lack of time
but nevertheless want to watch later. Other times you may end up clearing all your
notifications when you didn't actually intend to.
Once they are cleared, you don't have access to them again. On some devices, notification
history is a built-in feature but that doesn't track for more than 24 hours. 
Moreover, it doesn't have any search functionality or spam filter built in. This is the
problem Alert Box is trying to solve.

## How

- A Material You app which blends in and feels like system UI
- Exact time of notifications must be shown as well as any media attached to them
- App must have a filter to detect spam and show it in a separate spam section
- Searches must be done based on app name or notification content

## Challenges faced

- Slowdowns caused by rendering many notifications at once will be tricky to avoid
- Searching through notifications can become very intensive with large volumes
- Making the app feel like Android by adhering to the Material 3 guidelines will be challenging

## Good to have features

- A way to export and/or import notification history into a format (such as JSON)
- Fuzzy search can be implemented and on top of that an extensible search system
with filters to show only notifications from a specific app, during a specific time period, 
having an image, etc.
(basically Discord search features)

contributed by [Abhinav Anil](https://github.com/Sasikuttan2163)
