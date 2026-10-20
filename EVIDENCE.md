# Key evidence: Vendor C, 2023

Every file in the 2023 Vendor C engagement folder is listed in [evidence/vendor-c-2023/manifest.tsv](evidence/vendor-c-2023/manifest.tsv) (393 files). The items below carry the argument.

"Dropbox server copy" is the time Dropbox recorded on its own servers for a copy of the same file in a folder snapshot dated 2023-10-10. For each of these items the local file and the 2023 server copy have the same Dropbox content hash, so they are byte-identical. Dropbox, not the author, keeps that date.

| ID | Item | SHA-256 | File time (UTC) | Dropbox server copy (UTC) |
|---|---|---|---|---|
| EV-C-0048 | Engagement script, revised 2023-05-31 | `21a12c3e80eb74392a7a5c8135c2957f0a6bd65477b04a0f0ef573e7de458dad` | 2023-06-02T16:15:01Z | 2023-10-09T18:17:58Z |
| EV-C-0049 | Engagement script, re-record note | `9e7be7f65b6e8e483d17bd101e99f1c87cccecb9f175d99661c48ada3b042466` | 2023-07-13T01:58:23Z | 2023-10-09T18:17:59Z |
| EV-C-0331 | Testimonial notes, Vendor C product leader | `9a9b3ca4847ffb653959afd54a33b5486db2ac51525ef18608e85034a107485f` | 2023-09-22T22:11:24Z | 2023-10-09T18:25:47Z |
| EV-C-0313 | Testimonial clip 1 | `37a59171b0145ee06f03c40b3861f822bc487723fc2902e64b4b35aec1264ec1` | 2023-09-25T20:43:45Z | 2023-10-09T18:25:04Z |
| EV-C-0315 | Testimonial clip 2 | `b9306aa01bc9c12f1eb5b5a051a403c128229892a87f7f76a08039bd2beb532f` | 2023-09-25T20:44:27Z | 2023-10-09T18:24:53Z |
| EV-C-0317 | Testimonial clip 3 | `6188e26a901560eee05735d6a5c1cdbe30ed4646a1bc429584c9fffd1750bd93` | 2023-09-25T20:44:41Z | 2023-10-09T18:24:57Z |
| EV-C-0319 | Testimonial clip 4 | `7b948d34ca2b768460a7e474f304d6c681a401c5da6c7e661c678016d32d54fa` | 2023-09-25T20:45:15Z | 2023-10-09T18:25:16Z |
| EV-C-0321 | Testimonial clip 5 | `1066b6e1389dac92822fcf82ab6efcc487b19c164c2629962655d0917fb4818c` | 2023-09-25T20:45:27Z | 2023-10-09T18:25:20Z |
| EV-C-0323 | Testimonial clip 6 | `6d778f37b9874c419af846970c4953511ada271b6d21f77f1fc7c6d735303883` | 2023-09-25T20:45:58Z | 2023-10-09T18:25:37Z |
| EV-C-0325 | Testimonial clip 7 | `7c3a0b8497035105f87ff31836aa987555dad99ff72bb1e73f072c3d5453bf63` | 2023-09-25T20:46:25Z | 2023-10-09T18:25:27Z |
| EV-C-0327 | Testimonial storyboard ("Knowing the answer", "Does the solution work now?") | `f058c43adee3991b0689142a80bf608e47468edd03ca189e95cf0778e566248d` | 2023-10-03T00:56:15Z | |
| EV-C-0033 | Final testimonial render | `e2540fa37e0221db205dab662472cd3633a649b669eb7b4f9250d5d0dcb62fc0` | 2024-01-02T22:44:17Z | |
| EV-C-0277 | Mutual NDA with Vendor C | `86fcdb13a51ef6ccf2dc0c351ee1625ca009a815537b5499d98c8242dfbb480b` | 2023-05-19T15:07:54Z | |

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
