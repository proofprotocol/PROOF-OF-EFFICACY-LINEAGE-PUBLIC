# Key evidence: Spyderbat, 2023

Every file in the 2023 Spyderbat engagement folder is listed in [evidence/vendor-c-2023/manifest.tsv](evidence/vendor-c-2023/manifest.tsv) (393 files). The items below carry the argument.

"Dropbox server copy" is the time Dropbox recorded on its own servers for a copy of the same file in a folder snapshot dated 2023-10-10. For each of these items the local file and the 2023 server copy have the same Dropbox content hash, so they are byte-identical. Dropbox, not the author, keeps that date.

| ID | Item | SHA-256 | File time (UTC) | Dropbox server copy (UTC) |
|---|---|---|---|---|
| EV-C-0048 | Engagement script, revised 2023-05-31 | `21a12c3e80eb74392a7a5c8135c2957f0a6bd65477b04a0f0ef573e7de458dad` | 2023-06-02T16:15:01Z | 2023-10-09T18:17:58Z |
| EV-C-0049 | Engagement script, re-record note | `9e7be7f65b6e8e483d17bd101e99f1c87cccecb9f175d99661c48ada3b042466` | 2023-07-13T01:58:23Z | 2023-10-09T18:17:59Z |
| EV-C-0331 | Testimonial notes, Spyderbat product leader | `9a9b3ca4847ffb653959afd54a33b5486db2ac51525ef18608e85034a107485f` | 2023-09-22T22:11:24Z | 2023-10-09T18:25:47Z |
| EV-C-0313 | Testimonial clip 1 | `37a59171b0145ee06f03c40b3861f822bc487723fc2902e64b4b35aec1264ec1` | 2023-09-25T20:43:45Z | 2023-10-09T18:25:04Z |
| EV-C-0315 | Testimonial clip 2 | `b9306aa01bc9c12f1eb5b5a051a403c128229892a87f7f76a08039bd2beb532f` | 2023-09-25T20:44:27Z | 2023-10-09T18:24:53Z |
| EV-C-0317 | Testimonial clip 3 | `6188e26a901560eee05735d6a5c1cdbe30ed4646a1bc429584c9fffd1750bd93` | 2023-09-25T20:44:41Z | 2023-10-09T18:24:57Z |
| EV-C-0319 | Testimonial clip 4 | `7b948d34ca2b768460a7e474f304d6c681a401c5da6c7e661c678016d32d54fa` | 2023-09-25T20:45:15Z | 2023-10-09T18:25:16Z |
| EV-C-0321 | Testimonial clip 5 | `1066b6e1389dac92822fcf82ab6efcc487b19c164c2629962655d0917fb4818c` | 2023-09-25T20:45:27Z | 2023-10-09T18:25:20Z |
| EV-C-0323 | Testimonial clip 6 | `6d778f37b9874c419af846970c4953511ada271b6d21f77f1fc7c6d735303883` | 2023-09-25T20:45:58Z | 2023-10-09T18:25:37Z |
| EV-C-0325 | Testimonial clip 7 | `7c3a0b8497035105f87ff31836aa987555dad99ff72bb1e73f072c3d5453bf63` | 2023-09-25T20:46:25Z | 2023-10-09T18:25:27Z |
| EV-C-0327 | Testimonial storyboard ("Knowing the answer", "Does the solution work now?") | `f058c43adee3991b0689142a80bf608e47468edd03ca189e95cf0778e566248d` | 2023-10-03T00:56:15Z | |
| EV-C-0033 | Final testimonial render | `e2540fa37e0221db205dab662472cd3633a649b669eb7b4f9250d5d0dcb62fc0` | 2024-01-02T22:44:17Z | |
| EV-C-0277 | Mutual NDA with Spyderbat | `86fcdb13a51ef6ccf2dc0c351ee1625ca009a815537b5499d98c8242dfbb480b` | 2023-05-19T15:07:54Z | |

## Groups in the manifest

| Group | Files | Earliest file time | Latest file time |
|---|---|---|---|
| `agreement` | 1 | 2023-05-19T15:07:54Z | 2023-05-19T15:07:54Z |
| `attack-footage` | 10 | 2023-07-21T21:34:56Z | 2023-09-28T19:44:17Z |
| `brand-asset` | 239 | 2018-04-23T19:22:18Z | 2024-11-16T18:45:18Z |
| `edit-project` | 74 | 2023-09-25T14:09:54Z | 2024-02-17T05:04:39Z |
| `engagement-script` | 2 | 2023-06-02T16:15:01Z | 2023-07-13T01:58:23Z |
| `event-still` | 11 | 2023-09-26T03:08:44Z | 2023-10-07T13:23:02Z |
| `footage-segment` | 8 | 2023-09-26T03:23:03Z | 2023-09-26T16:21:33Z |
| `promo-or-source-video` | 8 | 2023-09-22T21:52:39Z | 2025-01-01T23:59:40Z |
| `screenshot` | 16 | 2023-05-24T15:09:46Z | 2023-10-07T12:54:26Z |
| `source-archive` | 2 | 2023-05-17T20:31:46Z | 2023-09-28T16:05:35Z |
| `stock-media` | 9 | 2023-09-28T01:12:39Z | 2023-09-29T16:33:41Z |
| `template-media` | 2 | 2023-09-26T02:42:45Z | 2023-09-26T19:40:07Z |
| `testimonial-clip` | 7 | 2023-09-25T20:43:45Z | 2023-09-25T20:46:25Z |
| `testimonial-notes` | 2 | 2023-09-22T22:11:24Z | 2023-10-03T00:56:15Z |
| `testimonial-render` | 2 | 2024-01-02T22:44:17Z | 2024-01-03T14:28:22Z |

`stock-media`, `template-media` and most `brand-asset` files are licensed stock and design files used in the edit. They are hashed for completeness, not because they carry dates that matter.

## YouTube

YouTube records an upload date for every video. For a public video the date is shown to anyone; for a private or unlisted video it is shown on the watch page only to someone with the link, and in YouTube Studio to the channel owner. When a private or unlisted video is made public, YouTube replaces that date with the date of the change. Times below are as YouTube reports them (Pacific time).

### Public videos

| Video | YouTube date | Archived |
|---|---|---|
| [LIVE NOW from inside the HACKERverse](https://www.youtube.com/watch?v=tW69T1gWNt8) | 2023-05-03 10:18 | [2026-10-20](https://web.archive.org/web/20261020234027/https://www.youtube.com/watch?v=tW69T1gWNt8) |
| [SPYDERbat vs. Cluster of PODs](https://www.youtube.com/watch?v=PRxzCvHnL7U), World Hacker Games watch party | 2023-06-30 16:52 (premiere) | [2026-10-20](https://web.archive.org/web/20261020234044/https://www.youtube.com/watch?v=PRxzCvHnL7U) |
| [Pre-Release Video Advert for SILENTbob](https://www.youtube.com/shorts/Bezj_cbPzms) | 2023-08-17 08:55 | [2026-10-20](https://web.archive.org/web/20261020234100/https://www.youtube.com/shorts/Bezj_cbPzms) |
| [WORLD HACKER GAMES WATCH PARTY LIVE 2, SPYDERbat vs Silent Bob](https://www.youtube.com/watch?v=s9I-11Ms1qA) | 2023-08-24 15:57 | [2026-10-20](https://web.archive.org/web/20261020234124/https://www.youtube.com/watch?v=s9I-11Ms1qA) |

### The seven engagement videos of 2023-06-01

The engagement script (EV-C-0048) lists seven videos made for the Spyderbat engagement. All seven were uploaded on 2023-06-01 and kept unlisted. Capture LINEAGE02 recorded each watch page on 2026-10-20 at 23:12 UTC, with YouTube's 2023-06-01 dates. Six of them were then made public, which reset their YouTube dates to 2026-10-20 (capture LINEAGE04, 23:38 UTC, shows the reset); one of the six was returned to unlisted, and its date stayed reset. The speed demo was not changed and still shows 2023-06-01.

| Video ID | Title | YouTube date in LINEAGE02 | Now |
|---|---|---|---|
| [BjLry3xViTA](https://www.youtube.com/shorts/BjLry3xViTA) | SPEED DEMO - Spyderbat - LIVE NOW from inside the HACKERverse | 2023-06-01 19:48 | unlisted, 2023-06-01 ([archived](https://web.archive.org/web/20261020230245/https://www.youtube.com/shorts/BjLry3xViTA)) |
| yonvDJ35pqo | WHG Advertisement | 2023-06-01 14:04 | public, date reset |
| 3rcprLX1x_U | COUNTdown to DISruption | 2023-06-01 14:01 | public, date reset |
| BvMS3y-DZGE | SPYDERbat ADvertisement | 2023-06-01 14:11 | unlisted, date reset |
| VEYCSC2P8NI | WHG WELCOME | 2023-06-01 14:30 | public, date reset |
| wIYbHQN_rWw | KIKrr ADvertisement | 2023-06-01 16:45 | public, date reset |
| I-g7wdSd7oU | WORLD HACKER GAMES welcomes SPYDERbat to defend their microservices | 2023-06-01 19:32 | public, date reset |

The SPYDERbat ADvertisement's source video file carries an embedded creation time of 2023-06-01 21:12 UTC, one minute after its YouTube upload at 21:11 UTC (14:11 Pacific).

### Private items

Private videos and live streams on the channel carry YouTube Studio dates that only the channel owner can see. They are shown to verifiers on request. They include live streams from 2022-03-16 onward, a live demo of Vendor B's endpoint product streamed 2022-04-29, a sign-up video for the World Hacker Games featuring Spyderbat uploaded 2023-05-29, and the final testimonial uploaded 2024-01-03.

### Captures

Each capture fetched YouTube's own page for each video, recorded a SHA-256 of the page, bound the run to a NIST Randomness Beacon pulse, and had the manifest timestamped by an independent RFC 3161 authority (FreeTSA). The captured pages are held privately and shown to verifiers. In the capture records, "Vendor C" means Spyderbat (the records were made before Spyderbat agreed to be named, and changing them would break their timestamps).

| Capture | NIST pulse | Manifest SHA-256 | Published here |
|---|---|---|---|
| [20261020T231254Z-LINEAGE02](evidence/youtube-captures/20261020T231254Z-LINEAGE02/) | 1992321 | `d155cb39a25c84d1ac48531ff5f8f9d90ca44c6718e07814ae381973b4fb4575` | manifest, timestamp |
| [20261020T233817Z-LINEAGE04](evidence/youtube-captures/20261020T233817Z-LINEAGE04/) | 1992346 | `50a795dd878121a2cc95c8e517ee9aaa2f6d3321f2119a9771c18f33cf20f02f` | timestamp only; the manifest names another vendor and is shown to verifiers |

To verify LINEAGE02:

```
cd evidence/youtube-captures/20261020T231254Z-LINEAGE02
sha256sum MANIFEST.json
openssl ts -reply -in MANIFEST.json.tsr -text
```

The message imprint in the reply must equal the SHA-256 of `MANIFEST.json`. Each record's `html_sha256` can be checked against the page when it is shown.
