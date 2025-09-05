# Chitti-voice-assistant
Of course. Here is a comprehensive README file for your Chitti voice assistant project, formatted using Markdown for easy integration into your GitHub repository.

### **Chitti-Voice-Assistant**

An AI-powered voice assistant named Chitti, built with Python. This project can listen for commands, play music, provide information from Wikipedia, tell jokes, and more.

-----

### **Features** 🎙️

  * **Voice Activation:** Wakes up when it hears the keyword "Chitti".
  * **Music Playback:** Plays songs on YouTube based on voice commands. (e.g., "Chitti, play Despacito").
  * **Time Inquiry:** Tells the current time. (e.g., "Chitti, what's the time?").
  * **Wikipedia Search:** Provides a brief summary from Wikipedia for any query. (e.g., "Chitti, who is Elon Musk?").
  * **Jokes:** Tells a random joke. (e.g., "Chitti, tell me a joke").
  * **Stop Command:** The assistant can be stopped with a voice command.

-----

### **Prerequisites** 💻

To run this project, you need to have **Python 3.9+** installed on your system. This project has been successfully tested on Python 3.9.6.

You will also need to install the following Python libraries:

  * `speechrecognition`
  * `pyttsx3`
  * `pywhatkit`
  * `wikipedia`
  * `pyjokes`
  * `pyaudio` (for microphone support)

You can install all the required libraries using `pip`.

```bash
pip install -r requirements.txt
```

#### **Special Installation for PyAudio**

Installing `PyAudio` can be tricky on Windows. If the `pip` command above fails, you may need to download a precompiled wheel (`.whl`) file for your specific Python version and install it manually.

  * Visit [PyAudio Unofficial Wheels](https://www.google.com/search?q=https://www.lfd.uci.edu/~gohlke/pythonlibs/%23pyaudio).
  * Download the `.whl` file that matches your Python version and system architecture (e.g., `PyAudio‑0.2.11‑cp39‑cp39‑win_amd64.whl` for Python 3.9, 64-bit).
  * Navigate to your `Downloads` folder in the terminal and run:
    ```bash
    pip install PyAudio‑0.2.11‑cp39‑cp39‑win_amd64.whl
    ```

-----

### **Usage** ▶️

1.  Clone this repository or download the source code.
    ```bash
    git clone https://github.com/Gagan7411/Chitti-voice-assistant.git
    ```
2.  Navigate to the project directory.
    ```bash
    cd Chitti-voice-assistant
    ```
3.  Run the main script.
    ```bash
    python chitti.py
    ```

The program will start listening for your commands. Speak clearly and use the activation word "Chitti" to interact with the assistant.

-----

### **Example Commands** 🗣️

  * "Chitti, play [song name]"
  * "Chitti, what is the time?"
  * "Chitti, who is [person's name]?"
  * "Chitti, tell me a joke."
  * "Chitti, stop."

-----

### **Troubleshooting** ⚙️

  * **Error: `ModuleNotFoundError: No module named 'pywintypes'`**: This error typically occurs if `pywin32` is not installed correctly.
      * Try running `pip install pywin32` again.
  * **Error: `Could not find PyAudio; check installation`**: This means `PyAudio` is not properly installed.
      * Follow the **"Special Installation for PyAudio"** steps above to install the correct `.whl` file.
