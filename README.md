# 🏘 Local Ads & Notes Sharing Dashboard

[![StandWithUkraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)
[![Github Badge](https://img.shields.io/github/followers/digitalandyeu?label=@digitalandyeu&style=social)](https://www.github.com/digitalandyeu)
[![Github Badge](https://img.shields.io/github/followers/andriilive?label=@andriilive&style=social)](https://www.github.com/andriilive)

Open-source web app that lets people easily share small ads, notes, or announcements with neighbors. Whether you’re selling a couch, warning about street work, or inviting others to a block party — this app makes it super easy to connect with locals in your area.


```shell
valet secure
open "https://neighbor-sharing.test"
```

----

TODO: plan the architecture of the application

> 🚧️ **Work in progress** - this is a playground, not a production-ready application

---

## Features planning

**Nice-to-have** features are marked with an asterisk *

### User

The user system is the backbone of the application, allowing users to create accounts, manage their profiles, and interact with the platform

- [ ] Permissions control
- [ ] User registration
- [ ] User login
- [ ] Moderator user role*
- [ ] Voting for moderator feature*
- [ ] Ban users feature*
- [ ] Vote to ban users feature*

### Listing

Users can create listings to share information, sell items, or post announcements. Listings are displayed in a chat-like format, making it easy for users to read and respond to them.

**Example:**

```txt
@user1
01.01.2023 12:00
Selling a couch! Brand new, never used. Price: $100
```

- [ ] CRUD listing
- [ ] View own listings
- [ ] Images upload feature*
- [ ] Rich content editor*
- [ ] Date/time localization*
- [ ] Date/time pretty print*
- [ ] Image upload feature*

### Room

Rooms are a hierarchical way to categorize listings by location. Rooms are created automatically based on the user's location.

**Example:** `Czech Republic` > `Prague` > `Prague 2`

- [ ] State level
- [ ] City level
- [ ] State/city detection based on IP
- [ ] Browser geolocation API
- [ ] District level*

### Dashboard

The dashboard is the main page of the application, where users see the closest rooms and listings. The dashboard is designed to be user captive and SEO friendly.

---

## Notes

Inspiration for the project:

- https://api-platform.com
- https://github.com/Dahkenangnon/symfony-rest-api-starter