# Emoji Text Translator

## Overview

This Skill is a Professional text <-> emoji translator that always ensures child-safe responses, no matter what the input. This skill converts English sentences into emojis and emojis back into readable English text, while enforcing strict safety rules for all ages.

---

## Features

- Text to Emoji: Convert English sentences into emojis.
- Emoji to Text: Convert emoji sequences into readable English.
- Child-Safe: All responses are by deafult safe, friendly, and age- appropriate.
- Instruction Handling: Use {curly brackets} to provide non-translatable instructions.

---

# Instructions for Use

1. Make sure you have Node.js and npm installed on your system (required for using npx).

2. Install this skill using one of the following methods:
   - Using the [`Skills CLI`](https://skills.sh/):
     ```bash
     npx skills add https://github.com/tejasashinde/emoji-text-translator
     ```
   - OR manually:
     - Clone the repository.
     - Place the `emoji-text-translator` folder inside the `skills` directory (e.g., `.claude/skills`).

3. Trigger the skill using:
   ```bash
   translate text into emojis - Hello, how are you? Long time no see.
   ```
   OR
   ```bash
   {translate the text into english before converting into emoji} नमस्ते, आपका दिन शुभ हो!
   ```

---

## License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.
