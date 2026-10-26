# Gas

A simple gas mileage tracker: log fill-ups, see MPG, price per gallon, and miles per month.

- **More than one vehicle:** keep separate logs for each car, truck or bike, each with its own little tile icon (pickup, sedan, SUV or motorcycle, in six colors). Tap **Vehicles** at the top to switch or add one.
- **Charts you can scroll:** pick 3 months, 6 months, a year or all time, then tap the arrows (or swipe the charts) to move back and forth.
- **All-time records:** best and worst tank, highest and lowest price per gallon.
- **Edit any entry** if you fat-fingered a number.
- **Catches gaps:** if a tank's MPG is way off from that vehicle's usual (once it has 5+ tanks), the app figures a fill-up probably didn't get logged, leaves that tank out of your MPG, and asks you about it. You can also tick **Missed logging a fill-up before this one** when you add an entry.

**Use it:** https://mgilvryallen.github.io/gas/

## Put it on your phone

- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open it in Chrome, tap the menu, then **Install app** (or **Add to Home screen**).

It then opens like a regular app and works offline.

## Where your data lives

On your device, in that browser's storage. There's no server and no account, and nobody else (including me) can see your entries.

**Sync (optional):** to use the same log on your phone and computer, turn on **Sync**. You make a GitHub token that can only touch gists, and the app keeps your log in a private gist on your own GitHub account. Each device keeps its own full copy and merges with the gist when you open it or make a change: the newest edit wins, and deletions carry over. The token is stored on your device only. To stop, tap **Turn off sync on this device**, and delete the token on GitHub if you like.

That also means nobody can recover them for you. Tap **Save Backup** now and then and keep the file somewhere safe (iCloud Drive, Google Drive, email it to yourself). On a new phone, install the app and tap **Restore From Backup**.

Restoring merges with what's already there and skips duplicates. It also reads the old Gas Tracker export files.

## Make your own copy

Want to change it? Click **Use this template** on GitHub to get your own copy, then go to **Settings → Pages**, set the source to the `main` branch, and GitHub hosts it for free at `your-username.github.io/gas/`. Everything is in `index.html`: no build step, no dependencies to install.

Made by [M'Gilvry Allen](https://mgilvryallen.com). Charts by [Chart.js](https://www.chartjs.org) (MIT).
