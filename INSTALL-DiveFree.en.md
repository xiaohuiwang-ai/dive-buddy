# Dive Buddy · Free (DiveFree) — Install Guide

> Supported device: **Garmin Descent G2** (contact the seller for other models)
> Sideload install — copy one file to the watch. ~5 minutes, no technical skills needed.

## Step 1: Get the watch face file

After purchase you receive one file: `DiveFree.prg`. Save it to your computer.

## Step 2: Copy it to the watch

Connect the watch to your computer with the **original charging cable**.

**Mac** (install the free tool OpenMTP first — macOS cannot see the watch storage natively):
1. Download from https://openmtp.ganeshrvel.com and install (drag to Applications)
2. Open OpenMTP — the watch storage appears on the right (if not: use the original cable, replug)
3. Open `GARMIN` → `APPS`
4. Drag `DiveFree.prg` into `APPS`
5. Unplug

**Windows** (no extra software):
1. Open "This PC", double-click the Garmin device
2. Open `GARMIN` → `APPS`
3. Copy `DiveFree.prg` there, unplug

## Step 3: Activate the face on the watch

A few seconds after unplugging:
1. On the watch face screen, **long-press MENU** → "Watch Face"
2. Select the new **DiveFree**

> Not listed? Wait 10 seconds and re-open the list; if still missing, restart the watch.

## Step 4: Pair (30 seconds)

On first use the face shows **PAIR CODE + 6 digits** and a URL.

1. Open **watch.xiaohuiwangai.cn/dive** on your phone and follow the 1-2-3 stepper
2. At step 2, enter the 6-digit code from the watch — your private account is created automatically (the step-1 token is generated at the same time)
3. Step 3 — link your Garmin account (on the account page): choose **Garmin China** (garmin.cn) or International, enter your Garmin credentials
   - The password is used once to sign in to Garmin and is **never stored**; with 2FA enabled you will be asked for a code
4. Done — leave the watch alone: it activates itself within 10 minutes (the code disappears) and freedive data appears within ~20-30 minutes

## FAQ

| Symptom | Cause / fix |
|---|---|
| Pair code never disappears | The face checks every 10 minutes — wait for the next cycle |
| Pair code expired (1 h) | Re-open the face to get a fresh code |
| OpenMTP does not see the watch | Original cable; replug once |
| Data shows "--" | First pull can take up to 30 min; check the dive shows in Garmin Connect |
| When does data arrive | After a dive: within 10-20 min. Sleep: within 1-2 h of waking. In a hurry: "Sync now" on the web dashboard (~10 s) |

Questions: contact the seller, or open an issue: https://github.com/xiaohuiwang-ai/dive-buddy
