# MCP-Server

This a MCP Server where you can generate voice messages and then send it through Whatsapp with the help of Claude and ElevenLabs.
# Prerequisites-
For Building Whatsapp MCP Server

1.Go

2.Python 3.6+

3.Anthropic Claude Desktop app 

4.Install UV (Python package manager) ![image](https://github.com/user-attachments/assets/c7c304ed-31a8-4652-86e9-2aba3c79fda8)


5.FFmpeg (optional) - Only needed for audio messages. If you want to send audio files as playable WhatsApp voice messages, they must be in .ogg Opus format. With FFmpeg installed, the MCP server will automatically convert non-Opus audio files. Without FFmpeg, you can still send raw audio files using the send_file tool.

File Provided above.

For Building ElevenLabs MCP Server
1.Get your API key from ElevenLabs.
2.Install UV ![image](https://github.com/user-attachments/assets/feef6fb5-f750-4cd4-a5b3-c67799ae74fc)


# Steps-
1.Clone this repository

![Screenshot 2025-04-14 182606](https://github.com/user-attachments/assets/19637795-9f68-4839-92de-2d736da6f3e2)

2.Go to Claude > Settings > Developer > Edit Config > claude_desktop_config.json to include the following:

![image](https://github.com/user-attachments/assets/aa36d719-352c-4cf7-9827-5e36eabc35bd)

Replace with your API key and file directories.

3.See the ReadMe file inside respective folders above to install the required Dependencies

4.Restart your Claude Desktop App and it would work


