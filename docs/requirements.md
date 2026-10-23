# Requirements

## Functional requirements (what the system must DO)
1. The system shall accept an uploaded video file in MP4 format of up to 3 minutes.
2. The system shall reject a file that is not a valid MP4 and show an error message that names the problem.
3. The system shall convert the speech in an accepted video into a text transcript.
4. The system shall extract one frame per second from an accepted video for analysis.
5. The system shall classify each accepted video as "Fake" or "Real".

## Non-functional requirements (how the system must PERFORM)
1. The system shall return a classification within 60 seconds for a 60-second video on a laptop with 8 GB of RAM.
2. The classifier shall reach a macro F1-score of at least 0.75 on a held-out test set that was not used for training.
3. The system shall delete every uploaded video within 24 hours of upload and shall not share uploaded videos with any third party.
