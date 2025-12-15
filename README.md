New Year's Eve Party 2025 Invite 🥂✨

This repository hosts the interactive, responsive web invitation for Andrew & Cash's NYE Party. The theme is "All That Glitters Is Gold", featuring a midnight blue and gold luxury aesthetic with high-end animations.

🌟 Features

Immersive Intro: "Champagne Fizz" overlay with rising bubbles and entrance animation.

Responsive Design: Optimized for all devices with a fixed starry background (no seams).

Dynamic Animations:

3D Card Tilt: Physics-based smooth tilting effect on mouse movement.

Confetti Burst: Triggers when guests click the RSVP button.

Gold Shimmer: animated text gradients and floating background particles.

Smart Interactions:

Group RSVP: One-tap button composes a group SMS to both hosts.

Live Countdown: Ticks down to Midnight, Jan 1, 2026.

Calendar Integration: Direct links for Google Calendar and Apple Calendar (.ics).

Navigation: Clickable address opens Google Maps; dedicated "Copy" button for clipboard.

Share: Native share sheet integration for easily sending the invite to others.

Spotify: Direct link to the collaborative party playlist.

Social Preview: Optimized Open Graph tags ensuring the link looks beautiful when texted or shared on social media.

📁 File Structure

index.html - The main application code containing HTML, CSS, and JavaScript.

og-preview.html - A utility file used to generate the social media preview image text/layout.

hosts.jpg - (Required) The photo of Andrew & Cash displayed in the "Hosts" section.

preview.jpg - (Required) The image shown when the link is shared via text or social media.

🛠️ Customization & Updates

1. Host Photo

Ensure you have a photo of the hosts named hosts.jpg uploaded to the root of this repository.

2. Generating the Link Preview

To ensure the link looks great when texted (iMessage/WhatsApp):

Open og-preview.html in your web browser on a desktop.

Take a screenshot of the page (it is sized to 1200x630px).

Save the screenshot as preview.jpg.

Upload it to this repository.

3. Modifying Text/Details

Edit index.html directly. Search for specific text (e.g., "13130 Pond Springs") to update the address, time, or message.

4. Modifying the RSVP Number

To update who receives the RSVP texts, search for sms: in index.html:

<a href="sms:9258901507,5126569229?body=Can't wait for NYE!" ... >


Replace the numbers with your preferred contacts, separated by a comma (no spaces).

🚀 Deployment

This project is designed to be hosted on GitHub Pages.

Go to your repository Settings.

Click Pages in the left sidebar.

Under Source, select Deploy from a branch.

Select main as the branch and / (root) as the folder.

Click Save.

Your invite will be live at: https://[your-username].github.io/[repo-name]/
