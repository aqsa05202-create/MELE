# Mela

Static web app: open `index.html`, or upload these files to your GitHub Pages repo (replace the old ones).

## Included
Accounts and profiles (photo, bio, followers) · photo/video/reel/story upload with image compression and progress bar · filters · likes, comments, saves · follow system with private accounts and follow requests · Everyone/Following feed · vertical reels with autoplay, tap to mute, double-tap to like · 24-hour stories · direct messages with read receipts and post sharing · alerts · search and trending hashtags · events with RSVP · English/Urdu with right-to-left layout · low-data mode · report (3 reports hide a post), block, mute · who-can-message setting · data export and account delete · About, Privacy, Terms pages.

## Important limits
- Data lives only in each visitor's browser (localStorage + IndexedDB). Users cannot see each other's posts until you connect a backend such as Firebase or Supabase. Replace the `D`/`save()` calls in `app.js` with API calls.
- "Continue with Google" needs a backend; it is not included.
- Passwords are hashed in the browser for the demo only. Real login must be handled by a server.
- Privacy and Terms are placeholders. Have them reviewed before launch.
- Not included yet: video trimming, sound library, moderation review screen.
