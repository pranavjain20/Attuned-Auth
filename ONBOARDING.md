# Onboarding to Attuned

Attuned creates personalized Spotify playlists based on your WHOOP recovery data — every playlist is built from your own music library, matched to what your body needs today.

Getting onboarded takes **3 minutes**. Two quick steps, both one-time only.

---

## Step 1: Create a Spotify Developer App (2 minutes)

This lets Attuned read your music library and create playlists for you. You're just registering a small app under your Spotify account — it's free and takes 2 minutes.

**You need Spotify Premium for this to work.**

1. Go to **[developer.spotify.com/dashboard](https://developer.spotify.com/dashboard)**
2. Log in with your Spotify account
3. Click **"Create App"**
4. Fill in:
   - **App name:** `Attuned` (or anything you want)
   - **App description:** `Personalized playlists` (or anything)
   - **Redirect URI:** Paste this exactly: `https://pranavjain20.github.io/Attuned-Auth/`
   - Check the box to accept the terms
5. Click **"Save"**
6. You'll see your app's dashboard. Click **"Settings"**
7. You'll see two things:
   - **Client ID** — a long string of letters and numbers
   - **Client Secret** — click "View client secret" to reveal it
8. **Copy both and send them to Pranav** (text, Slack, whatever)

That's it for this step. You won't need to touch this again.

---

## Step 2: Authorize Your Accounts (1 minute)

Pranav will send you **two links** — one for Spotify, one for WHOOP.

For each link:
1. Open the link
2. Log in with your account (Spotify or WHOOP)
3. Click **"Agree"** or **"Authorize"**
4. You'll land on a page that says **"Send this code to Pranav"** with a big green Copy button
5. Tap **Copy**, then paste it and send it to Pranav

Do this for both links. Takes about 30 seconds each.

---

## That's it!

After these two steps, Pranav handles everything else. A playlist will show up in your Spotify — personalized to your WHOOP recovery data, built from your own music library.

You'll get a new playlist whenever one is generated. You don't need to do anything else.

---

## FAQ

**Do I need to pay for anything?**
No. You need Spotify Premium (which you probably already have), but there's no additional cost.

**Is this safe?**
Yes. You're logging in directly on Spotify's and WHOOP's official websites — Pranav never sees your password. The Client ID and Client Secret are just app identifiers, not your personal credentials.

**What data does this use?**
Your Spotify library (liked songs, top tracks, listening history) and your WHOOP recovery data (HRV, sleep, recovery score). Nothing is shared publicly.

**Can I revoke access later?**
Yes. Go to your [Spotify account settings](https://www.spotify.com/account/apps/) and remove the app. For WHOOP, go to your WHOOP app settings.
