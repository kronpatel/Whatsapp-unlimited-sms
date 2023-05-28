# pyautogui Automated Messaging

This is a simple Python script that uses the `pyautogui` library to automate sending repetitive messages. The script prompts the user to enter a limit and a message, and then sends the specified message multiple times based on the given limit.

## Prerequisites

Before running the script, ensure that you have the following:

- Python: Make sure you have Python installed on your system. You can download Python from the official website: https://www.python.org/downloads/

- `pyautogui` library: Install the `pyautogui` library by executing the following command in your command prompt or terminal:
  ```
  pip install pyautogui
  ```

## Usage

1. Clone the repository or download the script file to your local machine.

2. Open a command prompt or terminal and navigate to the directory where the script is located.

3. Run the script by executing the following command:
   ```
   python script_name.py
   ```

4. The script will prompt you to enter the limit and message. Enter the desired values as per your requirements.

5. After a 3-second delay, the script will start sending the specified message. It will simulate pressing the Enter key after typing each message.

6. The script will continue sending the message until it reaches the specified limit.

7. To stop the script execution, move the mouse cursor to the top-left corner of the screen. This will trigger the `pyautogui.FailSafeException` and terminate the script.

## Important Note

Please use this script responsibly and consider the following:

- Do not use it for spamming or sending unsolicited messages.
- Make sure you have the necessary permissions to send messages on the target platform.
- Be cautious when using automation tools, as they can have unintended consequences.

## Disclaimer

The author of this script is not responsible for any misuse or damage caused by the script. Use it at your own risk.

## Contributing

If you have any suggestions, improvements, or issues, please feel free to open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to modify and distribute it as per the license terms.
