# Amazigh Script Converter (Advanced Version)

This web-based tool provides a comprehensive set of options for converting between various Amazigh (Berber) scripts, including Tifinagh, Latin (in multiple representations), and a simplified IPA transcription. It's designed for users who need precise control over the conversion process and supports file import/export.

## Live Demo

Access the advanced converter here: [https://abdelhaqueidali.github.io/Amazigh-Scripts-Converter/Advance.html](https://abdelhaqueidali.github.io/Amazigh-Scripts-Converter/Advance.html)

## Basic Version

For a simplified version with only Tifinagh to Latin and Latin to Tifinagh conversion, see the basic version: [https://abdelhaqueidali.github.io/Amazigh-Scripts-Converter/iindex.html](https://abdelhaqueidali.github.io/Amazigh-Scripts-Converter/iindex.html)

## Features

*   **Multiple Conversion Options:**
    *   Tifinagh to Latin
    *   Latin to Tifinagh
    *   Tifinagh to OPV (IRCAM)
    *   OPV (IRCAM) to Tifinagh
    *   Tifinagh to OPV (Tawalt)
    *   OPV (Tawalt) to Tifinagh
    *   Tifinagh to IPA (Simple)
    *   Tifinagh to Latin (Imouhagh) - A Latin-based representation used for Tuareg languages.
    *   Latin (Imouhagh) to Tifinagh
 
## Scripts set explained

*  Tifinagh : It refers the 33 main letters of the alphabet
*  Latin : It refers to the Amazigh latin letters
*  OPV : It refers to the old Latin mappings of the fonts of Ircam and Tawalt, they are two different ones, If you copy a Tifinagh text from a book, you get Latin script that is not the main Amazigh latin, but rather eather Ircam opv or Tawalt opv fonts. The naming of OPV refers to the letters OPV that are mapped to a completely different letters in Tifinagh, the rest makes sens.
*  Latin (Imouhagh) : It refers to the Latin used by the Tuareg which have the letter ⴻ mapped to an upside down e, while normal e is mapped to a special vowel.
For the mapping of each script with the other, check the html code, the script part. It has the mapping and there is where to preform any updates.
*   **Advanced Text Manipulation:**
    *   **Remove 'e' and its variants:**  Optionally removes the Latin letter 'e' during Latin-to-Tifinagh and Imouhagh-to-Tifinagh conversions, except when it appears between two identical letters.  This reflects common practice in Tifinagh orthography.
    * **Smart Capitalization:** Capitalizes the first letter of sentences (after periods, question marks, and exclamation points) and at the start of the text, *even after conversion*.  It also correctly capitalizes the first letter after a newline.  This is particularly useful for Latin output.

*   **User-Friendly Interface:**
    *   Clearly labeled input and output text areas.
    *   Dropdown menu for selecting the conversion type.
    *   Checkbox options for fine-tuning the conversion.
    *   Buttons for common actions:
        *   Copy Input Text
        *   Paste into Input Text
        *   Clear Input Text
        *   Copy Output Text
        *   Clear Output Text
        *   Export Output Text as a `.txt` file
    * Tooltips on buttons
    * Dark theme

*   **File Import/Export:**
    *   **Import:**  Import text from a `.txt` file directly into the input area.  The imported text is automatically converted.
    *   **Export:** Export the converted text to a `.txt` file.

## Usage

1.  **Enter Text:** Type or paste text into the "Input Text" area.
2.  **Choose Conversion Type:** Select the desired conversion (e.g., "Tifinagh (Ircam) to Latin") from the "Conversion" dropdown.
3.  **Customize Options:** Check the "Remove 'e'" boxes as needed.
4.  **View Output:** The converted text appears in the "Output Text" area.
5.  **Import/Export:**
    *   **Import:** Click "Choose File" to select a `.txt` file, then click "Import".
    *   **Export:** Click "Export" to download the output as a `.txt` file.
6. **Copy/Paste/Clear:** Use the provided buttons.

## Contributing

Contributions are welcome! This could include:

*   Adding support for more Amazigh scripts/dialects variants mappings.
*   Improving conversion map accuracy.
*   Adding features.
*   Enhancing the UI.
*   Fixing bugs.
*   Writing tests.

Please submit pull requests or open issues on the repository.
