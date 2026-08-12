# Privacy Policy — GridTsugi: Maze of Woven Bridges

**Effective date:** 12 August 2026
**Last updated:** 12 August 2026

ZenElephant Pvt. Ltd., trading as ZenElephantXR Studios (“ZenElephantXR”, “we”, “us”, “our”), is the developer and publisher of the mixed-reality game **GridTsugi: Maze of Woven Bridges** (“GridTsugi”, “the Game”).

This Privacy Policy explains what information the Game processes, why we process it, where it is stored, how long it is kept, and how you can have it deleted. It applies to the Game as distributed on the Meta Horizon Store for Meta Quest devices.

Platform-level services provided by Meta Platforms — your Meta account, Meta Horizon OS features, and device-level cloud backup — are governed by Meta’s own terms and privacy policy, not by this one.

---

## Summary

GridTsugi processes two clearly separate categories of information:

1. **On-device game data.** Your progress, completion times, and mixed-reality room setup. This is stored only on your Quest headset and is never transmitted to us.
2. **Meta account data for the online leaderboards.** Your Meta user ID, your Meta username, your Meta age category, and information about which of your Meta friends also play the Game, retrieved through the Meta Platform SDK and used to operate the Game’s global and friends leaderboards.

Single-player gameplay works fully offline. The online leaderboard is the only part of the Game that requires a network connection and a signed-in Meta account.

We do not run our own game servers. We do not use advertising SDKs or third-party analytics. We do not sell, rent, or share your personal data with anyone. We do not access your profile picture, your email address, or your real name.

---

## 1. Platform features and data we access

The Game accesses the following Meta Platform SDK features. Each is used only for the purpose listed.

| Data we receive | Meta platform feature | Why we use it |
|---|---|---|
| Meta user ID | **User ID** | To identify your leaderboard entry across sessions, so that a new personal best updates your existing entry instead of creating a duplicate, and so the Game can highlight your own rank to you. |
| Meta username (display name) | **User Profile** | Displayed next to your score on the in-game leaderboard, so players see recognisable names rather than anonymous identifiers. |
| Meta age category (child / teen / adult) | **User Age Group** | To determine whether the online leaderboards are made available to you. See section 4. |
| Meta friends who also play GridTsugi | **Friends** | To build the friends leaderboard view, which shows your completion times alongside those of your Meta friends so you can compete within your friend group. We use this for no other purpose. See section 3. |
| Level completion times and level identifiers | — | Submitted as your leaderboard score and used to calculate rankings. |

### What we do not access

For clarity, the Game does **not** request, receive, or process any of the following:

- Your friends list for any purpose other than the friends leaderboard view described in section 3 — never for invitations, messaging, advertising, or anything else.
- Your Meta profile picture or avatar image.
- Your email address, real name, phone number, or postal address.
- Your precise or approximate location.
- Passthrough camera frames, room scans, depth data, or mesh data.
- Voice, hand-tracking, eye-tracking, or face-tracking data.
- Purchase, subscription, or payment information.

---

## 2. On-device game data

The following is written to the Game’s private application storage on your headset:

- **Gameplay and progress data** — scores, level completion times, levels attempted and completed, best times, and similar performance statistics.
- **Spatial anchor identifier** — a local identifier for the mixed-reality anchor that records where you placed the grid in your room, so you do not have to repeat setup each session. We do not store passthrough video, raw room scans, or mesh data. All room mapping and sensor processing is performed by Meta Horizon OS.

This data is not transmitted to us and is not accessible to us. If you have enabled Meta’s device-level cloud backup, your headset may include this data in that backup. That backup is a platform feature controlled by Meta and by your device settings; we neither control nor receive it.

---

## 3. The online leaderboard

**How it works.** When you complete a level while your headset is online and signed in to a Meta account, the Game submits your completion time, together with your Meta user ID and Meta username, to Meta’s Leaderboards service through the Meta Platform SDK. The Game then retrieves the ranking list in order to display it to you.

**The leaderboard has two views.** The **global view** ranks you among all GridTsugi players worldwide. The **friends view** shows only you and your Meta friends who also play GridTsugi, so you can compare completion times within your friend group. To display the friends view, the Game uses the Meta Platform SDK to determine which leaderboard entries belong to your Meta friends. We do not store your friends list, and we use it for no purpose other than building this view — never for invitations, messaging, advertising, or anything else.

**What other players can see.** Any GridTsugi player can see your Meta username, your completion time, and your rank on the global leaderboard. Players who are your Meta friends also see your entry in their friends view. No player can see your user ID, your age category, your friends list, or any other information about you.

**Where it is stored.** Leaderboard data is transmitted to and stored on Meta’s Platform servers. **We do not operate our own leaderboard servers, and we do not copy, mirror, export, or retain leaderboard data on any system under our control.** All leaderboard storage and processing takes place on Meta’s infrastructure and is subject to Meta’s Privacy Policy.

**If you play offline**, or if you do not complete a level, nothing is submitted.

---

## 4. Children and age gating

GridTsugi is listed on the Meta Horizon Store for mixed ages. To keep the online leaderboard away from younger players, the Game uses Meta’s Get Age Category API.

- Once per session, when your headset is online, the Game asks Meta for your age category. Meta returns only a broad category — child, teen, or adult — and never a date of birth or exact age.
- **If you are identified as a child under 13, the online leaderboards are disabled entirely** — both the global and friends views. No user ID, username, friends information, or score is submitted to or retrieved from the leaderboard service, and no leaderboard interface is shown. The rest of the Game remains fully playable.
- **If no age information is available** — for example because your headset is offline or the request fails — we will not prevent you from playing. The Game falls back to the age category most recently confirmed on that device, if any; where no category has ever been confirmed, the leaderboard remains disabled until one can be.
- The age category is used to make this decision only. It is never submitted to the leaderboard, never shown to other players, and never transmitted to us. Where it is cached, it is cached only in the Game’s private storage on your own device.

We do not knowingly collect personal information from children under 13. If you believe a child has provided personal information to us — for example by emailing us — please contact us at the address in section 13 and we will delete it. We handle children’s data in accordance with the Children’s Online Privacy Protection Act (COPPA), the UK Age Appropriate Design Code, and other applicable child-protection laws.

---

## 5. If you contact us

If you choose to contact us by email or through our website, you may provide your name, email address, or other details in your message. This happens outside the Game, is never required in order to play, and is used only to respond to your enquiry or support request.

---

## 6. Legal bases for processing (EEA, UK, and similar jurisdictions)

| Processing | Legal basis |
|---|---|
| On-device gameplay, progress, and spatial anchor data | Performance of a contract — delivering the game you chose to play |
| Submitting and displaying leaderboard entries | Performance of a contract — the online leaderboard is an advertised feature of the Game |
| Displaying the friends leaderboard view | Performance of a contract and legitimate interests — comparing completion times with friends is an advertised social feature of the Game |
| Associating scores with a user ID to prevent duplicate or fraudulent entries | Legitimate interests — maintaining a fair and accurate leaderboard |
| Retrieving age category to gate the leaderboard | Legal obligation and legitimate interests — protecting children and complying with platform and child-privacy requirements |
| Responding to support enquiries | Legitimate interests — assisting users who contact us |

We do not use any of this data for advertising, profiling, or automated decision-making that produces legal or similarly significant effects.

---

## 7. Data retention

- **On-device game data** — retained on your headset for as long as the Game is installed, or until you clear the Game’s data through your device’s application settings. Uninstalling the Game removes data held in its private storage, subject to your device’s behaviour and any platform backups you have enabled.
- **Leaderboard entries** — retained on Meta’s Platform servers for as long as the leaderboard for that level remains active, until you request deletion under section 8, or until your Meta account is deleted. Meta may apply its own retention policies to this data.
- **Age category** — not retained by us. Any local cache is limited to your own device and is cleared when the Game’s data is cleared.
- **Friends information** — not retained by us. Which entries appear in your friends view is determined afresh from Meta’s Platform each time the leaderboard is shown.
- **Support correspondence** — retained for up to 24 months after your enquiry is resolved, then deleted.

---

## 8. Your rights and choices

Depending on where you live, you may have the right to access, correct, delete, restrict, or object to our processing of your personal data, to withdraw consent where processing relies on consent, and to lodge a complaint with your local data protection authority. To exercise any of these rights, contact us at the address in section 13.

### Correcting or deleting your leaderboard data

To have a leaderboard entry corrected or removed, email **gridtsugi@gmail.com** with the subject line “Leaderboard data request” and tell us the Meta username shown on the leaderboard and what you would like corrected or deleted.

- **We never charge a fee for a correction or deletion request.**
- We will acknowledge your request within 7 days and complete it within 30 days.
- Because leaderboard data is held on Meta’s infrastructure rather than ours, we action deletion by submitting the removal through Meta’s Platform services. If Meta is unable to remove a particular entry, we will tell you which entry and why, and we will remove your username from any ranking display within the Game so that the entry is no longer attributable to you.

### Deleting your on-device data

Clear the Game’s data from your Meta Quest application settings, or uninstall the Game. This removes local progress, statistics, and the spatial anchor identifier.

### Other controls

- Play with your headset offline to keep any score from being submitted.
- Change the username other players see through your Meta account settings.
- Manage device-level cloud backup through your Meta Quest device settings.

---

## 9. Security

On-device data is held in the Game’s private application storage and protected by Meta Horizon OS application sandboxing. All communication with Meta’s Platform services is carried over encrypted connections established by the Meta Platform SDK. Because we operate no servers of our own and hold no copy of your leaderboard or gameplay data, there is no ZenElephantXR-controlled database that could be exposed.

If we become aware of a security incident affecting user data associated with the Game, we will report it to Meta through the Meta Horizon incident reporting process and notify affected users and regulators where required by law.

---

## 10. International transfers

Leaderboard data is stored on Meta’s Platform servers, which operate globally, and may therefore be transferred outside your country of residence. These transfers are made by Meta under its own safeguards, as described in Meta’s Privacy Policy. We do not carry out any separate international transfer of your data, because we do not receive or store it.

---

## 11. Third parties

- The Game integrates **no** third-party advertising, analytics, attribution, crash-reporting, or social SDKs.
- The only external service the Game communicates with is the **Meta Platform SDK**, provided by Meta Platforms as the operator of the Meta Horizon Store and Meta Quest devices.
- We do not sell, rent, licence, or otherwise disclose personal data to any third party, and we do not “share” personal data for cross-context behavioural advertising as that term is defined under applicable privacy laws.
- We do not combine Meta platform data with data from any other source, and we never transfer or disclose Meta user IDs or access tokens to anyone.

---

## 12. Changes to this policy

We may update this policy to reflect changes to the Game or to legal requirements. Material changes will be communicated in-game or on our website, and the effective date at the top of this page will be updated. Previous versions remain available in the revision history of this document.

---

## 13. Contact us

**Developer and publisher:** ZenElephant Pvt. Ltd. (ZenElephantXR Studios)
**Registered in:** India
**Email:** gridtsugi@gmail.com
**Website:** https://www.zenelephantxr.com

For any privacy question, data access request, or deletion request relating to GridTsugi: Maze of Woven Bridges, email us at the address above and we will respond within 30 days.
