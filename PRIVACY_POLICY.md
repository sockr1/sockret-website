# Sockret — Privacy Policy

**Last updated:** 8 June 2026
**Applies to:** the Sockret Android app, all versions.
**Contact:** John Hallberg — sockret.app@gmail.com

> **Note for hosting:** Google Play requires the privacy policy to live at a
> public, non-geofenced, stable URL that is **not** a PDF. Render this file as a
> web page (GitHub Pages is an accepted precedent for apps like this) and use
> that URL in both Play Console and the in-app About/Legal screen. The URL must
> match the Data Safety form 1:1.
>
> **Entity placeholder:** drafted with John Hallberg as the individual developer
> and data controller. If you publish under a company, replace the name and add
> the registered address.

---

## Summary (plain language)

Sockret does not have any servers. It does not collect, transmit, sell, or share
your personal or health data with us or with any third party for our purposes.
Everything Sockret stores — your glucose readings, login credentials, logs,
journal entries, photos, and settings — stays on your device. The only data that
leaves your device is the request Sockret makes, on your behalf, to the glucose
data source **you** choose and configure (LibreLinkUp, Dexcom Share, or your own
Nightscout server), and any SMS alert you set up to send to a follower from your
own phone.

There is no analytics, no advertising, no crash-reporting-to-a-server, and no
third-party tracking SDK in Sockret.

---

## 1. Who we are

Sockret is a personal, secondary-display companion app for following glucose
data from a separate continuous glucose monitor (CGM) system. It is developed and
maintained by John Hallberg. Sockret **is not a medical device** and does not
diagnose, treat, or prevent any condition.

## 2. What data Sockret handles, and where it stays

All of the following is stored **locally on your device** and is never sent to a
Sockret-controlled server (there is none):

- **CGM account credentials** (LibreLinkUp, Dexcom Share, or Nightscout
  URL/token). Stored encrypted using the Android Keystore (AES-256/GCM).
- **Glucose readings and trends** fetched from your chosen source.
- **Health and lifestyle entries you create**: meals, treatments, corrections,
  exercise, fingerstick (blood) readings, journal entries and mood faces, cycle
  and pregnancy data.
- **Photos** you attach to meal entries (via the camera or your gallery).
- **Follower contact details** (phone numbers) you enter to receive SMS alerts.
- **App settings, alarm thresholds, and diagnostic event logs** used for
  in-app troubleshooting.

## 3. Data that leaves your device (and only because you direct it to)

Sockret only sends data off your device in two situations, both initiated and
controlled by you:

1. **To your chosen glucose source.** To show your readings, Sockret connects
   directly from your device to the service you configured — Abbott LibreLinkUp,
   Dexcom Share, or the Nightscout server you operate. Your credentials and
   requests go only to that service. That service has its own privacy policy and
   terms, which govern how it handles your data. Sockret is not affiliated with
   Abbott, Dexcom, or Nightscout.
2. **SMS alerts to followers.** If you enable follower alerts, Sockret sends a
   text message from your device, using your mobile carrier, to the phone number
   you entered. The message goes through your carrier like any text you send;
   Sockret has no server in the path.

We — the developer — receive none of this data.

## 4. Health Connect (optional)

If you choose to enable it, Sockret can read and write blood glucose values to
Android **Health Connect** on your device so other apps you authorize can use
them. This is an on-device exchange you control; the data is not sent to us. You
can revoke this access at any time in Health Connect settings. Sockret's use of
Health Connect data is limited to displaying and logging glucose and is never
used for advertising or shared with third parties.

## 5. Permissions and why they are used

- **Internet:** connect to your chosen CGM source.
- **SMS (send/receive):** send glucose alerts to followers and confirm delivery.
  Used only for the alerting feature you configure.
- **Camera:** attach a photo to a meal entry.
- **Location (approximate/precise):** required by Android for certain
  connectivity operations; Sockret does not store, log, or transmit your location
  to us or anyone else.
- **Notifications, full-screen intent, foreground service, wake lock, ignore
  battery optimizations:** keep the background refresh and alarms working
  reliably.
- **Health Connect (read/write blood glucose):** optional on-device sync
  described above.
- **Receive boot completed:** restart the background refresh after a reboot.

## 6. Analytics, advertising, and tracking

None. Sockret contains no analytics SDK, no advertising SDK, no attribution or
marketing SDK, and no third-party crash-reporting service. We do not build
profiles, we do not track you across apps or websites, and we have no data to
sell because none reaches us.

## 7. Children

Sockret is a general-audience health-companion tool and is not directed at
children. It does not knowingly collect data from anyone, including children.

## 8. Data retention and deletion

Because your data lives on your device, you are in control of it:

- Delete individual entries within the app.
- Clear a profile's data, or remove an account, from within the app.
- Uninstalling Sockret removes its on-device data and stored credentials.
- Any encrypted backup file you export is yours; delete it wherever you saved it.

We hold no copy of your data and therefore have nothing to delete on your behalf.
If you have a question about deletion, contact sockret.app@gmail.com.

## 9. Security

Credentials are encrypted at rest using the Android Keystore (AES-256/GCM).
Network connections to your chosen CGM source use HTTPS. Because there is no
central server, there is no central database to breach.

## 10. Changes to this policy

If this policy changes, we will update the date above and the published page. The
Data Safety section in Google Play will be kept consistent with this policy.

## 11. Contact

Questions about privacy: **John Hallberg — sockret.app@gmail.com**

---

# Sockret — Integritetspolicy (Svenska)

**Senast uppdaterad:** 8 juni 2026
**Gäller:** Sockret-appen för Android, alla versioner.
**Kontakt:** John Hallberg — sockret.app@gmail.com

## Sammanfattning

Sockret har inga servrar. Vi samlar inte in, överför, säljer eller delar dina
person- eller hälsouppgifter med oss eller någon tredje part. Allt som Sockret
lagrar — glukosvärden, inloggningsuppgifter, loggar, dagboksinlägg, foton och
inställningar — stannar på din enhet. Det enda som lämnar enheten är den begäran
Sockret gör, å dina vägnar, till den glukoskälla **du** väljer (LibreLinkUp,
Dexcom Share eller din egen Nightscout-server), samt eventuella SMS-aviseringar
du själv ställer in till en följare från din egen telefon.

Sockret innehåller ingen analys, ingen reklam, ingen kraschrapportering till
server och inga spårnings-SDK:er från tredje part.

## 1. Vilka vi är

Sockret är en personlig kompletterande visningsapp för glukosdata från ett
separat CGM-system, utvecklad av John Hallberg. Sockret **är inte en
medicinteknisk produkt** och diagnostiserar, behandlar eller förebygger inget
tillstånd.

## 2. Vilka uppgifter Sockret hanterar (lokalt på din enhet)

Allt nedan lagras **lokalt på din enhet** och skickas aldrig till någon
Sockret-server (det finns ingen): CGM-inloggningsuppgifter (krypterade med
Android Keystore, AES-256/GCM), glukosvärden och trender, hälso- och
livsstilsinlägg du skapar (måltider, behandlingar, korrigeringar, träning,
blodvärden, dagbok och humörsymboler, cykel- och graviditetsdata), foton du
lägger till, följares telefonnummer, samt appinställningar, larmgränser och
diagnostiska händelseloggar.

## 3. Uppgifter som lämnar enheten (endast när du styr det)

Sockret skickar endast uppgifter från enheten i två fall, båda initierade av dig:
(1) **Till din valda glukoskälla** — Sockret ansluter direkt från din enhet till
tjänsten du konfigurerat (Abbott LibreLinkUp, Dexcom Share eller din egen
Nightscout-server). Dessa tjänster har egna integritetspolicyer. (2)
**SMS-aviseringar till följare** — Sockret skickar ett textmeddelande från din
enhet via din operatör till numret du angett. Utvecklaren tar inte emot något av
detta.

## 4. Health Connect (valfritt)

Om du aktiverar det kan Sockret läsa och skriva blodglukos till Android Health
Connect på din enhet. Detta är ett utbyte på enheten som du styr; uppgifterna
skickas inte till oss och används aldrig för reklam.

## 5. Behörigheter

Internet (anslut till din CGM-källa); SMS (skicka aviseringar till följare);
Kamera (bild på måltid); Plats (krävs av Android för viss anslutning — lagras
eller överförs aldrig till oss); aviseringar, helskärmsavisering,
förgrundstjänst, wake lock, batterioptimering (tillförlitlig bakgrundsuppdatering
och larm); Health Connect (valfri synk på enheten); starta efter omstart.

## 6. Analys, reklam och spårning

Inga. Sockret innehåller inga analys-, reklam-, attributions- eller
kraschrapporterings-SDK:er och spårar dig inte.

## 7. Barn

Sockret riktar sig inte till barn och samlar inte medvetet in uppgifter från
någon.

## 8. Lagring och radering

Dina uppgifter finns på din enhet. Du kan radera enskilda inlägg, rensa en
profil eller ta bort ett konto i appen, och avinstallation tar bort appens
data. Vi har ingen kopia. Frågor: sockret.app@gmail.com.

## 9. Säkerhet

Inloggningsuppgifter krypteras med Android Keystore (AES-256/GCM). Anslutningar
sker via HTTPS. Eftersom ingen central server finns, finns ingen central databas
att angripa.

## 10. Ändringar

Vid ändringar uppdateras datumet ovan och den publicerade sidan, och Data
Safety-sektionen i Google Play hålls i linje med denna policy.

## 11. Kontakt

**John Hallberg — sockret.app@gmail.com**
