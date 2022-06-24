
## Deployment instructions:
https://github.com/ucsb-cs148-f21/project-t04-youtubevoice/blob/44bef498d9965f31c4a278bd4e0ecefa468872ff/docs/DEPLOY.md

## Team

Aditya:
Contributed by coming up with ideas for features. Worked on the speech synthesis API part. Tried to remove the speaker’s original voice so that only your extension was speaking but this was later discarded. Incharge of researching APIs and tech stack and helping others with their code. Fixed bugs in other team member’s code. Helped Haolan on the issues he was working on.

Hunter:
In the first few weeks worked with Bisman to establish communication channels between the front and back end of YouTube. During the later half of the quarter focused on making the UI design for the extension. Made the menu so the users can customize different settings of the voice such as rate, pitch, play/pause button and other features of the settings menu. Worked with Kaleb to integrate the design with the rest of the code such that clicking the buttons resulted in the desired changes.

Bisman:
Started working in binary search to fetch the subtitles at different timestamps. Kaleb finished the issue. Hunter and I worked together in the beginning to establish the communications channel between the front script and the background script of YouTube. I also worked with him in the beginning stages of creating the buttons that our extension uses and helped him along the way. I implemented the security feature that sanitizes the html script so no one can inject malicious code.

Kaleb:
Implemented the binary search that fetched subtitles based on the timestamp of the video. Finished the implementation of communication channels between youtubescript.js and background.js. Worked on other issues like speech synthesis, dynamic accent selection, speed and pitch control, UI for speed and pitch control and play/pause button.

Haolan:
Worked on getting timestamps from the video and fetching subtitles. Worked to implement features like speech synthesis, fixing, dependencies, app deployment with yarn, fixing API issues, making extension work without refreshing, and making the extension on the YouTube tabe while other tabs are open. Worked with Kaleb and Aditya on some of these issues.



## Tech Stack

We are using Javascript with Google Chrome web APIs, HTML, and CSS.

## Functionality

* Giving Prof Höllerer a russian female accent

## Known problems

* Javascript is a hot pile of garbage
* Chrome asychrounous APIs are a hot pile of garbage too
* Message passing between content script and background is messy
* Background code not structured

## Contributing

Contributions are welcomed!

1. Fork it!
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request :D
