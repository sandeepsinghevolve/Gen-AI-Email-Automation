# Gmail Mail Automation_main
This Python script streamlines the process of sending emails through Gmail, offering two convenient methods. It supports the inclusion of **Carbon Copy** (**CC**) and **Blind Carbon Copy** (**BCC**) recipients.

# Pre-requisites
- Python 3.9 or lower
- Gmail Account
- If you meet the above requirements, install the necessary dependencies using:

```bash
pip install -r requirements.txt
```
## Method - 1 Command Line Options

- `-e`: Sender's email address.
- `-p`: Password for the sender's email address. If not provided, the script will prompt for it securely.
- `-to`: Recipient's email address.
- `-cc`: CC email address.
- `-bcc`: BCC email address.
- `-S`: Email subject.
- `-T`: Email text or body.

### Example Usage
```bash
python main.py -e "sender@example.com" -p "password123" -to "recipient@example.com" -S "Subject" -T "Hello, this is the email body."
```
### Method 2: Interactive Prompt
If you prefer a more interactive approach, run the script without command line options. The program will prompt you to provide the necessary details.

Feel free to automate your Gmail emails effortlessly!

-----------------------------------------------------------------------------------------------


# Email-automation-with-gpt-ai-and-python
An example of using the OpenAI API in python to automate email responses

1. This script was created to automatically reply to emails in an email inbox using OpenAI API. <br />
   The script allows you to reply to only unread messages or to all messages in the inbox. <br />
   Sent messages are moved to the specified folder.

2. The program is ready to use. You only need: <br />
   a.) Install the OpenAI library:<br />
   ```sh
   pip install openai
   ```
   b.) Complete the API key and login details 

   

4. If you find a bug or have an idea to improve the program, please e-mail me.