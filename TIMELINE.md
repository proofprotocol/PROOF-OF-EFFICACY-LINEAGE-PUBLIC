# Timeline

Compiled 2026-10-20 from the private lineage record. Vendors are lettered in order of first appearance, except Spyderbat, which is named with its consent; private repository names that contain another vendor's name are withheld. A commit hash fixes both the content and the date of that commit.

## 1. The practice, 2007 to 2024

### 2007 to 2008: conception and publication

| Date | Event | Evidence |
|---|---|---|
| 2007-06-07 | Spirent Avalanche test plan, employer performance test lab | Held privately |
| 2007-09 | WAF Test Methodology, WebAppSec.org, co-authored with Ivan Ristic (Breach Security), Amit Klein (AKsecurity), Bob Walder (NSS Group), Lior Cohen (Juniper Networks), and Spirent | Public |
| 2008-12 | *Technical Marketing*, Stratequest, ISBN 978-0982257005. Documents System Under Test (SUT) and Device Under Test (DUT) competitive testing | Public |

### 2020 to 2021: test infrastructure

| Date | Repository | Visibility | First commit |
|---|---|---|---|
| 2020-11-23 | surfd4wg/armor (and armor_aws_terraform_ansible_ubuntu, armor_AWS_tf_ans_ubu) | public | cfa7f21dc7e4b43bd4861e5ea64227a6e22ec6ab |
| 2021-02 to 2021-08 | surfd4wg/armor_AWS_tf_* (Windows, Ubuntu, Debian, CentOS, RHEL, SUSE, Fedora, Amazon Linux 2) and related scripts | public and private | see the GitHub API for each repository |
| 2021-11 | Delaware C-corporation formed by Craig Thomas Ellrod to build automated proof of efficacy | Public record |

### 2022: control present versus control absent

From March 2022 the HACKERverse YouTube channel (@theHACKERverse) streamed live sessions, including a live demo of Vendor B's endpoint product on 2022-04-29 (private stream; date held by YouTube and shown to verifiers on request).

| Date | Repository or item | Visibility | First commit or proof |
|---|---|---|---|
| 2022-01-03 | r3dlocust/r3d_aws, test range | private | 597d517a8160541aaa569840f2aedd89b97f55c2 |
| **2022-01-18** | **surfd4wg/kali: `install_userdata_kali.sh` (with the endpoint agent) and `install_userdata_noARMOR_kali.sh` (without it), added together. Same attack, control present and control absent** | **public** | **ec0178d5c24e73121986fb5de223f3dfca8c3244**, 2022-01-18T07:33:00-07:00 |
| 2022-01-18 | surfd4wg/armor_DOCKER | public | 07a9a98d4791f2f51350807ce701a145bd0d192f |
| 2022-02-28 | Range video: device under test under adversarial attack, by file creation metadata; public on YouTube since 2026-07-26 | public | https://youtu.be/sQ6w1N49Qxc |
| 2022-02-28 | r3dlocust/guacamole-bash, range access | private | acda2e9a2b11e8748b8e29166cf41f8e23b898cb |
| 2022-04-14 | Public repository, name withheld: Vendor A (API security) test environment | public | ef208fd2434b3680ff570aaf99a2e7367611b8df |
| 2022-05-26 | r3dlocust/(withheld), Vendor A files | private | b7941eb82ed06256c27b90c2eca36deef9e669e1 |
| 2022-05-30 | r3dlocust/(withheld), Vendor A in the test range | private | e20e228afb21a178d1c49fb75d7adc13bd90ba7f |
| 2022-06-12 | r3dlocust/(withheld), Vendor B (endpoint) test environment | private | d042efe62561b38cbb07490dc0c3832bda92a199 |
| 2022-07-07 | surfd4wg/trashpanda_tf_NGINX_reverseproxy_VPC_mirroring: traffic observed separately from the product under test | public | see the GitHub API |
| 2022-07-08 | r3dlocust/(withheld), attack jump server | private | 5c09755033267dfe1b5fed1f9218e74969590852 |
| 2022-10-29 | kikrr/aws-ami-kali, attack image | private | cfe8587da0a7bb8301fa842d2bc6939e1d8849f9 |
| 2022-10-31 | kikrr/(withheld), Vendor B environment rebuilt | private | edc6f638e23229f73eb8ceae7f61d1eb48f0ee47 |

### 2023: live, unscripted vendor evaluation (Spyderbat)

The 2023 engagement with Spyderbat is where the problem the category answers was stated plainly. A vendor product leader, recording a testimonial, said that scripted vendor demos "suffer from 'knowing the answer'" because "the demo'er already knows the script", and that the answer was to let real red teamers attack the product live with their own tools: "Put your product in a live attack environment, and show how it works." A test whose outcome the presenter already knows proves nothing. Every later specification is built to remove that knowledge: blind witnesses, committed canaries, outcomes judged outside the vendor's console.

| Date | Item | Evidence | Third-party date |
|---|---|---|---|
| 2023-05-02 | kikrr/aws-ami-w16-unprotected, control-absent baseline | private, first commit fa61cf835dbb84a6312fab318b3a08cfbb220f32 | GitHub |
| 2023-05-03 | "LIVE NOW from inside the HACKERverse", public on YouTube | https://www.youtube.com/watch?v=tW69T1gWNt8 | YouTube; Internet Archive 2026-10-20 |
| 2023-05-04 | kikrr/aws-ami-win19-unprotected, control-absent baseline | private, first commit 879b20bc7f260f2e8e82bc4376e78a4f02bcc34c | GitHub |
| 2023-05-19 | Mutual non-disclosure agreement with Spyderbat | EV-C-0277 | |
| 2023-05-29 | Sign-up video, World Hacker Games featuring Spyderbat | private YouTube video | YouTube Studio, shown on request |
| 2023-05-31 | Engagement script, revised 2023-05-31: hackers paired with Spyderbat to test each of the vendor's stated product claims live, at the World Hacker Games. Lists seven YouTube videos made for the engagement | EV-C-0048 | Dropbox server copy 2023-10-09T18:17:58Z, byte-identical |
| 2023-06-01 | The seven engagement videos listed in the script uploaded to YouTube (unlisted), including "SPEED DEMO - Spyderbat - LIVE NOW from inside the HACKERverse" | https://www.youtube.com/shorts/BjLry3xViTA | YouTube; capture LINEAGE02 (RFC 3161), see EVIDENCE.md |
| **2023-06-30** | **"SPYDERbat vs. Cluster of PODs": World Hacker Games watch party, a live attack on Spyderbat's product by red teamers using their own tools (first PWN at 27:30, second at 1:03:23)** | **https://www.youtube.com/watch?v=PRxzCvHnL7U** | **YouTube premiere; Internet Archive 2026-10-20** |
| 2023-07 to 2023-09 | Live attack footage from the engagement (container escape, honeypot attack, walkthroughs) | group `attack-footage` in the manifest | |
| 2023-08-17 | Pre-release advert for the second round, Spyderbat vs Silent Bob | https://www.youtube.com/shorts/Bezj_cbPzms | YouTube; Internet Archive 2026-10-20 |
| 2023-08-20 | theHACKERverse/SpyderbatArena1, Spyderbat arena repository | private, first commit 90ac02c6c1a333da40170c4dc8703c1ccc267e13 | GitHub |
| **2023-08-24** | **World Hacker Games watch party live 2: Spyderbat vs Silent Bob** | **https://www.youtube.com/watch?v=s9I-11Ms1qA** | **YouTube; Internet Archive 2026-10-20** |
| 2023-09-22 | Testimonial notes, Spyderbat product leader (quoted above) | EV-C-0331 | Dropbox server copy 2023-10-09T18:25:47Z, byte-identical |
| 2023-09-25 | Seven testimonial clips | EV-C-0313 to EV-C-0325 | Dropbox server copies 2023-10-09, byte-identical |
| 2023-12-29 to 2024-01-03 | Testimonial edit sessions; editor auto-save files carry their timestamps in their names | group `edit-project` | |
| 2024-01-02 | Final testimonial render | EV-C-0033 | private YouTube upload 2024-01-03, shown on request |

### 2024: demos, automation

| Date | Repository | Visibility | First commit |
|---|---|---|---|
| 2024-01-17 | HACKERverse-demo/(withheld), Vendor D demo | private | 72e2c2b034e539a62253d1cc4c93af363263f621 |
| 2024-01-24 | HACKERverse-demo/(withheld), Vendor E demo | private | 0a2fd38e23d5082ded3985bed209b348761dc138 |
| 2024-03-25 | HACKERverse-demo/(withheld), Vendor F demo | private | 46b6ae9de76a1e608212ac62102bd29c21173833 |
| 2024-04-16 | HACKERverse-bot/POCBOT, automated proof of concept | private | eda2922b4a8820ed2199184ccce862127fd5fd9f |
| 2024-07-20 | HACKERverse-bot/HV_ATTACK_BOT, automated attack | private | e0ebf0980853de42a84f41d84a49f5059d893dce |
| 2024-07-22 | Public repository, name withheld: Vendor G specification series | public | d86080d4ea44b2a7d85e27caed2554ca62933e5f |

## 2. The names, 2025

| Date | Event | Third-party evidence |
|---|---|---|
| 2025-09-18 | Continuous Autonomous Evaluation (CAE) published as a category | Internet Archive, 2025-10-06: https://web.archive.org/web/20251006175845/https://blog.hackerverse.ai/2025/09/18/continuous-autonomous-evaluation-cae-the-next-category-in-cybersecurity/ |
| 2025-09-25 | The Proof Economy published as a category | Internet Archive, 2025-10-06: https://web.archive.org/web/20251006161031/https://blog.hackerverse.ai/2025/09/25/the-proof-economy-proof-is-the-new-currency-hackerverse-at-techcrunch-disrupt/ |
| 2025-10-09 | The CAE Manifesto | Internet Archive, 2025-11-09: https://web.archive.org/web/20251109060700/https://blog.hackerverse.ai/2025/10/09/the-cae-manifesto-welcome-to-the-proof-economy/ |
| 2025-10-23 | The Proof Economy Manifesto | Internet Archive, 2025-11-09: https://web.archive.org/web/20251109065612/https://blog.hackerverse.ai/2025/10/23/the-proof-economy-manifesto/ |
| 2025-09 to 2025-11 | Vendor G engagement series, 14 repositories | private, first commit 49bb42d5f4dd30845470a4056a3faf9416732c01 |
| 2025-12-29 | Vendor H proof-of-concept series begins, through 2026-02-10 | private, first commit d229084ea14bd8c8ac42ee44c5f6fb073deb3a0a |

## 3. Publication, 2026

| Date | Event | Evidence |
|---|---|---|
| 2026-02-28 | Earliest provisional patent application filed | Stated in PP-SPEC-014 |
| 2026-07-04 | DKP-SPEC-001 v1.1 published | https://github.com/proofprotocol/Defensible-Knowledge-Proof |
| 2026-07 | Proof Economy Prior Art Declaration | DOI 10.5281/zenodo.21379780 |
| 2026-10-13 | PP-SPEC-077 v0.7.4, 078 v0.2.3, 079 v0.1.3, 080 v0.1.1 | DOIs 10.5281/zenodo.23347914, 23347986, 23347697, 23348072 |
| 2026-10-20 | This public edition, fixing the hashes of the 2023 evidence | This repository's creation date on GitHub |
