<div align="center">

[![Reddit-Client](./public/images/preview.jpg)](https://github.com/dshane1903/instagram-build)

### Instagram Build

</div>

## Introduction


The application was built with the purpose of using some technologies I have not used before, including fireabase/firestore, firebase/auth and @tailwindcss.

Demo live at: [instapix.dshane.dev](https://instapix.dshane.dev)

Read more about it [on this blog](https://www.dshane.dev/writing/instapix).

## Features

- Signin/signup
- Forgot password
- Reset password
- Email verification
- Profile page
  - public for everyone with restrictions
  - no restrictions for logged in users
- Post page
  - public for everyone with restrictions
  - no restrictions for logged in users
- Inbox
  - Direct message
  - Multi-user Chat Rooms
  - Chat details
- Live notifications
- Settings
  - Edit profile
  - Change password
  - Notification settings
  - Privacy and security
- Timeline
- Suggestions
- Search
- Explore posts
- Add/delete posts
- Comment/like/save posts

## Codebase

### Technologies

The entire codebase consists in **Javascript**

Here is a list of technologies used:

- **React**: Front-end framework
- **Tailwind**: CSS framework
- **Firebase**: Cloud database/auth provider
- **Cloudinary**: Cloud image management

### Folder structure

```sh
instagram/
├── components     # Reusabble parts
├── constants      # Constant app data
├── context        # Global state layer
├── helpers        # Utility functions
├── hooks          # React custom functions
├── lib            # External helpers
├── services       # External services / network calls
├── styles         # General app styles
└── pages          # Application views
```

## Acknowledgments

This project is mimicking the famous [Instagram by Facebook](https://www.instagram.com/) web application with no intent of realeasing or advertising the use of the content in this repo. Being just a demo app!!!

