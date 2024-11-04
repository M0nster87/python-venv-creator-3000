Create venv for work

## Virtual Environment for Python

1. Open a Terminal:
   - On Windows:
     - Press `Win + R`, type `cmd`, and press `Enter`
   - **On macOS:**
     - Press `Cmd + Space` to open Spotlight, type "Terminal," and press `Enter`
   - **On Linux:**
     - Press `Ctrl + Alt + T`

2. Activate the Virtual Environment
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. Save new Packages to `requirements.txt` file
   - On Windows, macOS, and Linux:
   ```bash
   pip freeze > requirements.txt
   ```
