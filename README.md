# MIDI Drum Kit Project

## Overview
This project was developed as part of a JavaScript study provided by Alura and Oracle Next Education (ONE). The objective was to deepen JavaScript knowledge by exploring **functions, event handling, conditionals, and lists** to create a dynamic page featuring a **Musical Instrument Digital Interface (MIDI) Drum Kit**.

While the **HTML and CSS were provided**, customizations were made to enhance the appearance and make the interface more engaging.

## Features
- **Interactive Drum Kit:** Users can trigger drum sounds by clicking buttons or pressing keys.
- **Keyboard Support:** Sounds can be played using the **Space** and **Enter** keys.
- **Visual Feedback:** Pressed keys visually change when activated.
- **Error Handling:** Prevents invalid elements from triggering audio.

## Technologies Used
- **JavaScript**: Handles event listeners, key interactions, and sound playback.
- **HTML**: Provides the structure for the drum interface.
- **CSS**: Styles the layout and adds animations for user interaction.

## How It Works
### Event Handling
- Clicking a drum pad triggers the corresponding sound.
- Pressing **Space** or **Enter** activates the pad and plays the sound.
- Releasing the key resets the visual feedback.
- If an invalid element is selected, an error message is logged.

### JavaScript Logic
1. A function selects and plays the corresponding audio element.
2. A loop assigns event listeners to each drum pad.
3. A keydown event listens for **Space** and **Enter** to add a visual effect.
4. A keyup event removes the visual effect.

## Installation and Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/dharitcha/js-midi-drum-kit.git
   ```
2. Open `index.html` in a web browser.
3. Click or press keys to play drum sounds.

## Future Improvements
- Add more instruments and sounds.
- Implement a recording and playback feature.
- Improve animations for better user experience.
- Mobile-friendly touch support.

## Live Demo
You can access the live version here: [dharitcha.github.io/alura-midi](https://dharitcha.github.io/alura-midi/)

## License
This project is open-source and available under the MIT License.

