# SAMMI CORE Extensions

You can download any extension you want and install on your bridge. I will try to provide here a quick explanation about the usage of each extension.

Consider supporting this work following my social pages:

- Kick: https://kick.com/jzturrini
- Twitch: https://twitch.tv/jzturrini
- Twitter: https://twitter.com/JzTurrini
- Tiktok: https://tiktok.com/JzTurrini

All Extensions and Decks Available here are Free to Use. If you want to donate anything to support me, you can use this link here: https://streamlabs.com/jzturrini348/tip

## General Utilities

- **Clear Invisible Characters from String**
    - Removes invisible or non-printable characters (like zero-width spaces, BOM, or directional marks) and normalizes the text.
- **Convert Seconds to Readable Time**
    - Converts a number of seconds into a human-readable format (minutes, hours, days, months, years). Supports English (en) and Portuguese (pt).
- **Friendly Short Number**
    - Formats large numbers into short, friendly strings using suffixes like K, M, B, etc.
- **Convert Seconds to DHMS**
    - Converts seconds into days, hours, minutes, and seconds, with zero-padding for readability.
- **Convert Color to OBS Format**
    - Converts a 24-bit BGR integer (SAMMI format) into a 32-bit unsigned RGBA integer compatible with OBS Studio.
- **Regex Return from String**
    - Removes all substrings from a string that don't match a given regular expression pattern.
- **Convert Number to Currency Format**
    - Formats a numeric value with custom thousand and decimal separators, a fixed number of decimal places, and optional rounding modes. You can also prepend or append strings (prefix/suffix) to the formatted result.

## Simple TTS

- **Simple TTS**
    - Use this command to read a text out loud with the selected voice and speed.
- **Simple TTS With Callback**
    - This command is similar to "Simple TTS" but includes additional functionality. You can specify a button name to trigger when the speech starts and a variable to set when the speech completes.
- **Estimate TTS Time (in MS)**
    - This command estimates the time it will take to read a given text aloud at a specified speed. The estimated time is returned in milliseconds and can be saved to a variable.
- **Simple TTS Actions**
    - This command allows you to perform specific actions related to the text-to-speech functionality, such as stopping the current speech or refreshing the page.

If you find any bug or want to ask for a new feature/change, please open a ticket here on github.