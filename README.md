# Notion-Countdown-Timer

This project offers a countdown timer that utilizes the Youtube API Sound Player, making it embeddable into Notion pages via [Apption.co](https://apption.co/embeds/965d7809). Users can easily set timers ranging from 5 minutes to 60 minutes and more to enjoy the convenience of a sound alarm upon completion. 

![Timer Gif](https://github.com/ianTevesAcc/Notion-Countdown-Timer/blob/8211cd1fa9713cbc0bb946d0f3b3babbbd828545/chrome-capture-2024-2-28%20(1).gif)

**GitHub Pages Demo Timer:** [https://iantevesacc.github.io/Notion-Countdown-Timer/](https://iantevesacc.github.io/Notion-Countdown-Timer/)

## Usage

1. Access the timer through this [link](https://apption.co/embeds/965d7809).
2. Copy link and paste as embed into your notion pages.
3. Click on the timer buttons to add time to the countdown:
   - "+5 min": Adds 5 minutes to the current countdown.
   - "+15 min": Adds 15 minutes to the current countdown.
   - "+30 min": Adds 30 minutes to the current countdown.
   - "+60 min": Adds 60 minutes to the current countdown.
4. Press the "Play" button to start the countdown.
5. Use the "Pause" button to pause the countdown.
6. Press the "End" button to reset the timer.

## Features

- **Embedded Countdown Timer:** Easily embeddable into Notion pages via Apption.co.
- **Dynamic Incremental Timer:** Swiftly add time to your timer by pressing any of the "minute add" buttons to increase the duration.
- **Timer Controls:** Start, pause, and end the timer with intuitive controls.
- **Sound Alarm:** Plays a sound notification upon timer completion.

## Future Features

- **Light Mode:** Implement a light mode option for users who prefer a brighter interface.
- **Custom Sounds:** Allow users to choose custom alarm sounds from a selection of options or provide their own sound URL.
- **Custom Backgrounds:** Enable users to personalize the timer's appearance by selecting different background themes or uploading custom backgrounds.
- **Saved Progress:** Implement browser storage to save the timer's progress, allowing it to resume from the last known time even after the page is exited or refreshed.
   - **Time Elapsed Remembered:** Enable the program to retain the timer's progress, including the elapsed time since it was last active.
   - **Page Specific Timer:** Utilize the webpage address to restrict the timer's functionality, ensuring it operates exclusively on the specified page.
   - **Timer State Memory:** Retain the state of the timer before it was last accessed - to continue same functionality when used again.
- **Add GitHub Pages:** Enable open-source contributors to make their own changes to the codebase by hosting the project on GitHub Pages.
- **Implement Testing:** Ensure functionality remains intact by incorporating tests to prevent potential issues or bugs before changes are merged into the repository.
- **Add Browser Notifications:** Allow a chrome / edge browser to send notifications to user when timer equals 0.

## Bugs to Fix

- **YouTube API Delay:** Address delay in YouTube API's response for timer sound.
- **Play Button Bug:** Play button is accessible even when timer equals 0.
- **Timer Display Empty:** Timer is empty instead of displaying 00:00:00 when first accessed.

## Donation

To upkeep this project and keep ADs away from your embed timer - please consider making a $1 donation once or monthly or whenever you can to support keeping this and future projects being free and available to you and everyone. Im a broke unemployed programmer so the help would be greatly appreciated 🙏
[Make a 1 dollar Donation](https://ko-fi.com/ianteves)

## Support and Contributions

- For issues or feature requests, please visit the [GitHub page](https://github.com/ianTevesAcc/Notion-Countdown-Timer/issues).
- Updates and maintenance will be done and pushed through by Apption.co.

---

## License

This project is licensed under the MIT License, encouraging collaboration, innovation, and legal clarity. The [MIT License](https://opensource.org/licenses/MIT) allows users to freely use, modify, and distribute the software while providing clear legal terms and protecting the project's contributors.
