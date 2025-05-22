<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UserScript: Gemini: Enter for Newline, Shift+Enter to Send - Description</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.7;
            margin: 25px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 0.3em;
        }
        h1 {
            font-size: 2em;
            text-align: center;
            margin-bottom: 1em;
        }
        h2 {
            font-size: 1.5em;
            margin-top: 1.5em;
        }
        h3 { /* This style was present but not used in the user's latest HTML, kept for consistency if needed */
            font-size: 1.2em;
            border-bottom: 1px dashed #bdc3c7;
        }
        code { /* This style was present but not used in the user's latest HTML's main text, kept for consistency if needed */
            background-color: #ecf0f1;
            padding: 2px 5px;
            border-radius: 4px;
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
            font-size: 0.95em;
        }
        pre { /* This style was present but not used as the code block was removed, kept for consistency if needed */
            padding: 15px;
            overflow-x: auto;
            white-space: pre-wrap;
            word-wrap: break-word;
            background-color: #ecf0f1; /* Added background color for pre if it were used */
            border-radius: 4px; /* Added border-radius for pre if it were used */
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace; /* Added font-family for pre if it were used */
            font-size: 0.95em; /* Added font-size for pre if it were used */
        }
        ul, ol {
            padding-left: 30px;
        }
        li {
            margin-bottom: 0.5em;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .note { /* This style was present but not used in the user's latest HTML, kept for consistency if needed */
            background-color: #fff9e6;
            border-left: 5px solid #f1c40f;
            padding: 15px;
            margin: 20px 0;
            border-radius: 4px;
        }
        .keycap {
            display: inline-block;
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            border-radius: 3px;
            padding: 2px 6px;
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
            box-shadow: 1px 1px 1px #aaa;
            margin: 0 2px;
        }
    </style>
</head>
<body>

    <h1>UserScript: "Gemini: Enter for Newline, Shift+Enter to Send"</h1>

    <p style="text-align: center;"><strong>Make your typing experience in Gemini more comfortable.</strong></p>

    <p>This UserScript modifies the keyboard behavior in the Google Gemini web UI on PC to be more intuitive and align with common chat applications.</p>
    <p>By default, pressing the <span class="keycap">Enter</span> key sends the message immediately. This script changes the operations as follows:</p>
    <ul>
        <li><span class="keycap">Enter</span> key alone: Inserts a <strong>new line</strong>.</li>
        <li><span class="keycap">Shift</span> + <span class="keycap">Enter</span> keys: <strong>Sends</strong> the message.</li>
    </ul>
    <p>This allows for easier creation of multi-line prompts and enhances the Gemini user experience.</p>

    <h2>✨ Key Features</h2>
    <ul>
        <li>Press <span class="keycap">Enter</span> for a new line in Gemini's chat input field.</li>
        <li>Press <span class="keycap">Shift</span> + <span class="keycap">Enter</span> to send the message.</li>
        <li>Designed for the PC version of the Gemini website (<code>https://gemini.google.com/app*</code>).</li>
    </ul>

    <h2>🚀 How to Install</h2>
    <p>To use this UserScript, you first need to install a UserScript manager (e.g., Tampermonkey) in your browser.</p>
    <ol>
        <li>
            <strong>Install a UserScript Manager:</strong>
            <br>Install a manager compatible with your browser (e.g., <a href="https://www.tampermonkey.net/" target="_blank" rel="noopener noreferrer">Tampermonkey</a>, <a href="https://violentmonkey.github.io/" target="_blank" rel="noopener noreferrer">Violentmonkey</a>).
        </li>
        <li>
            <strong>Install this UserScript:</strong>
            <br>Install by clicking a button like "Install" (typically found on the UserScript hosting page).
        </li>
    </ol>
    <p>After installation, reload the Gemini page, and the script will become active.</p>

    <h2>🛠️ How to Use</h2>
    <p>In Gemini's chat input field, press the <span class="keycap">Enter</span> key if you want to insert a new line, or press <span class="keycap">Shift</span> + <span class="keycap">Enter</span> if you want to send the message.</p>

    <h2>📝 Notes</h2>
    <ul>
        <li>Changes to Gemini's website structure may cause this script to stop working.</li>
        <li>Conflicts with other extensions are rare but possible.</li>
        <li>This script is primarily intended for use on PC desktop browsers.</li>
    </ul>

    <h2>📜 License</h2>
    <p>This UserScript is released under the <a href="https://opensource.org/licenses/MIT" target="_blank" rel="noopener noreferrer">MIT License</a>.</p>

    <h2>👨‍💻 Author</h2>
    <p>Hayaokuri</p>

    <h2>📄 Version Information</h2>
    <p>Version: 1.0</p>

    <hr style="margin: 2em 0;">

</body>
</html>
