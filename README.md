New Year's Eve Party 2025 Invite 🥂✨

This repository hosts the interactive, responsive web invitation for Andrew & Cash's NYE Party. The theme is "All That Glitters Is Gold", featuring a midnight blue and gold luxury aesthetic.

🌟 Features

Responsive Design: Optimized for both mobile devices and desktops.

Dynamic Animations:

"Champagne Fizz" intro overlay with rising bubbles.

3D Card Tilt effect on mouse movement (physics-based smoothing).

Gold shimmer text and floating background particles.

Confetti burst upon clicking RSVP.

Smart Interactions:

RSVP via Text: Composes a group SMS to both hosts automatically.

Live Countdown: Ticks down to Midnight, Jan 1, 2026.

Add to Calendar: Direct links for Google Calendar and Apple Calendar (.ics).

Maps & Copy: Clickable address opens Google Maps; copy button for clipboard access.

Share Button: Uses the native device share sheet to send the link.

Spotify Integration: Link to the collaborative playlist.

Local Notifications: "Time-bomb" notification logic that thanks guests for attending if they visit the site after Jan 1, 2026 (requires user permission).

Social Preview: Optimized Open Graph tags for beautiful link previews in iMessage/WhatsApp.

📁 File Structure

index.html - The main application code containing HTML, CSS, and JavaScript.

og-preview.html - A utility file used to generate the social media preview image.

20251212_182720.jpg - (Required) The photo of Andrew & Cash displayed in the "Hosts" section.

preview.jpg - (Required) The image shown when the link is shared via text or social media.

🛠️ Customization & Updates

1. Generating the Link Preview

To ensure the link looks great when texted:

Open og-preview.html in your web browser on a desktop.

Take a screenshot of the page (it is sized to 1200x630px).

Save the screenshot as preview.jpg.

Upload it to this repository.

2. Changing Text/Details

Edit index.html directly. Search for specific text (e.g., "13130 Pond Springs") to update the address, time, or message.

3. Modifying the RSVP Number

To update who receives the RSVP texts, search for sms: in index.html:

<a href="sms:9258901507,5126569229?body=Can't wait for NYE!" ... >


Replace the numbers with your preferred contacts, separated by a comma.

4. Updating the Host Photo

Rename your new photo to 20251212_182720.jpg (or update the filename in the HTML).

Upload it to the repository to overwrite the existing file.

🚀 Deployment

This project is designed to be hosted on GitHub Pages, and is currently formatted for a New Year's Eve party I'm hosting/hosted, but can be modified for your own purposes.

Go to your repository Settings.

Click Pages in the left sidebar.

Under Source, select Deploy from a branch.

Select main as the branch and / (root) as the folder.

Click Save.

Your invite will be live at: https://[your-username].github.io/[repo-name]/
