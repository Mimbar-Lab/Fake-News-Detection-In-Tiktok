# Problem Statement

## Who is affected?
- People that watch news type of videos on TikTok and may share them.
- Fact-checkers and moderators who must check videos by hand.
- The public who are exposed to fake health and political news.

## What exactly is going wrong?
A brief video clip, containing speech, pictures, captions, and music, runs for 30 to 60 seconds. There is no indication as to the source of the clip, and the viewers have nothing to go by when assessing the validity of the information presented. The fact-checkers only have enough time to review a little part of the videos, and fake clips often go viral before they are taken down.

## Why does it matter?
False health and political videos can change what the people believe and do, for example about vaccines or elections. Late corrections rarely reach everyone who saw the original clip.

## Evidence
In 2022, in September, NewsGuard reviewed 540 TikTok search results related to news topics (health, elections, the war in Ukraine) and found that 105 of them, or 19.4%, contained false or misleading claims (ABC7 New York, 2022). Researchers note that fake news on short video platforms is challenging to identify because a video contains multiple types of information (Qi et al., 2023).

## Problem statement (3 to 5 sentences)
People who consume news from TikTok find it difficult to identify the accuracy of the news because a 30-second clip usually combines multiple visual and verbal information, making it unclear where the information came from. Because fact-checkers check videos manually, this process is too slow to keep up with the rapid spread of TikTok content, which results in many fake news spreading before being identified and neutralized. During a 2022 audit, NewsGuard found that 105 of 540 TikTok search results (19.4%) contained deceptive statements about crucial subjects like vaccinations and elections. This demonstrates how easily false information may be disseminated in the form of TikTok videos containing misleading and deceptive information about medical and electoral issues.

## Users and stakeholders
| Group | Role |
|-------|------|
| TikTok viewers | Main users. Want a quick check before they trust or share a video. |
| Fact-checkers and moderators | Main users. Want to find the videos most worth checking first. |
| Video creators | Affected stakeholders. May be wrongly flagged if the model is wrong. |

## Scope
In scope
- MP4 video uploaded by the user (max 3 minutes).
- Spoken English (Malay as an alternative) in the video.
- Fake / Real prediction with confidence percentage.
- Display the transcript for the user to be able to see what the model is predicting.

Out of scope
- Download TikTok content on a large scale.
- Live streams, photo posting (video without sound/text).
- Detecting edited / deepfake videos (focus is on claims, not on pixel analysis).
- A final judgment on legality/editing claims (only warnings, not actual proof).
- A mobile application or TikTok plugin.

## References
- ABC7 New York. (2022, September 20). *Nearly 20% of TikTok search results yield videos with misinformation, report says.* https://abc7ny.com/post/tiktok-misinformation-search-result-newsguard/12241564/
- Qi, P., Bu, Y., Cao, J., Ji, W., Shui, R., Xiao, J., Wang, D., & Chua, T.-S. (2023). FakeSV: A multimodal benchmark with rich social context for fake news detection on short video platforms. *Proceedings of the AAAI Conference on Artificial Intelligence, 37*(12), 14444-14452. https://doi.org/10.1609/aaai.v37i12.26689