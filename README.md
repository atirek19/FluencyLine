# Fluency Line: install on Android without logging in to Claude

Everything in this folder is the app. It contains no personal data. Your progress, notes, stories,
profile and API key are stored only on the phone where you use it.

## 1. Put it online (free, about 10 minutes, on a computer)

1. Create a free GitHub account at github.com (any email address).
2. Click **New repository**. Name it `fluency-line`, set it to **Public**, click **Create repository**.
3. Click **uploading an existing file**, drag in every file from this folder, then **Commit changes**.
4. Open the repository's **Settings > Pages**. Under *Build and deployment*, choose
   **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After a minute or two, your app is live at `https://YOUR-USERNAME.github.io/fluency-line/`.

## 2. Install it on the phone

**Option A, simplest:** open the address in Chrome on the phone, tap the menu, then
**Add to Home screen > Install**. Chrome installs it as a proper Android app: its own icon in the
app drawer, full screen, works offline.

**Option B, a real .apk file:** go to pwabuilder.com on a computer, paste your app address,
choose **Package for stores > Android**, and download the package. It includes a signed APK
you can copy to the phone and install (allow installs from unknown sources when asked).

## 3. Optional: switch on Claude features with an API key

Without a key, the app still has all 110 lessons, 160+ flashcards, the interview bank, story bank,
phrase drills, a daily-changing mix and live tech headlines.

With a key you also get coaching on your spoken answers, roleplays (including an HR interviewer and a
hiring CFO), deeper lessons, and a fresh web-searched briefing every morning.

1. On a computer, sign in at console.anthropic.com (this is the developer console, separate
   from the Claude app) and create an API key under **API keys**.
2. Set a monthly spend limit under **Limits** so costs can never surprise you.
3. For the daily briefing, make sure web search is enabled in the Console's settings.
4. In the app, tap the streak counter at the top right, scroll to **Settings**, paste the key,
   then tap **Test it**.

Anyone who can unlock the phone could find a key stored in the app, so keep the spend limit low
and delete the key in the Console if the phone is lost.

## 4. Updating

When you get a new `index.html`, upload it to the same repository (replace the old file).
The installed app picks up the new version the next time it opens with internet.
Use **Export backup** in Settings now and then; progress lives only on the phone.
