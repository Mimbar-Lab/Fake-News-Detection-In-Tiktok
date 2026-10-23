# User Stories

## User Story 1 
As a TikTok viewer, I want to upload a news video and get a Fake or Real result with a confidence score, so that I can decide whether to trust or share it.

Acceptance criteria:
1. When I upload a valid MP4 of up to 3 minutes, the system shows either "Fake" or "Real".
2. The result shows a confidence score between 0% and 100%.
3. When the file is not a valid MP4, the system shows an error and shows no result.

## User Story 2
As a fact-checker, I want to read the transcript of the video next to the result, so that I can see what the prediction was based on and check the claim myself.

Acceptance criteria:
1. After a video is processed, the transcript is shown on the same page as the result.
2. When the video has no speech, the page says "No speech found" instead of showing an empty transcript.

## User Story 3
As a fact-checker, I want to mark a result as correct or incorrect, so that wrong predictions are recorded and can be used to improve the model.

Acceptance criteria:
1. Each result has a "Correct" and an "Incorrect" button.
2. After I press a button, the system records my choice with the video's result and shows a confirmation message.
3. I can change my choice later, and only the latest choice is kept.

