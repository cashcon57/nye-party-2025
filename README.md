New Year's Eve Party 2025 Invite 🥂✨

This repository hosts the responsive web invitation for Andrew & Cash's NYE Party. The theme is "All That Glitters Is Gold".

🌟 Features

Responsive Design: Looks great on mobile and desktop.

Dynamic Animations: CSS-based shimmer text, floating particles, and entrance animations.

Interactive Modals: Popups for "Directions" and "Dress Code" to keep the main view clean.

Smart Actions:

RSVP via Text: Opens the user's SMS app pre-filled with a message to both Andrew & Cash.

Spotify Integration: Link to add songs to the collaborative playlist.

Social Preview: Configured with Open Graph tags for beautiful link previews in iMessage/WhatsApp.

📁 File Structure

index.html - The main HTML/CSS code for the invite.

hosts.jpg - (Required) The photo of Andrew & Cash displayed in the "Hosts" section.

preview.jpg - (Required) The Open Graph preview image shown when the link is shared via text or social media.

🛠️ How to Update

1. Changing Text

To update the address, time, or descriptions, edit the index.html file directly. Look for the content inside the specific HTML tags (e.g., <span class="details-value">).

2. Updating Images

To change the host photo or link preview:

Rename your new image file to match the filename in the code exactly (e.g., 20251212_182720.jpg).

Upload it to this repository, replacing the existing file.

3. Modifying the RSVP Number

Search for sms: in index.html to find the anchor tag and update the phone number:

<a href="sms:YOUR_NUMBER_HERE?body=Can't wait for NYE!" ... >


🚀 Deployment

This project is designed to be hosted on GitHub Pages.

Go to Settings > Pages.

Under Source, select Deploy from a branch.

Select main as the branch and / (root) as the folder.

Click Save.

Your invite will be live at: https://[your-username].github.io/[repo-name]/
