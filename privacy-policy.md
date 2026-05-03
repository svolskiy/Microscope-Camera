# Privacy Policy for Microscope Camera

Last updated: May 3, 2026

# Summary

Microscope Camera is designed to keep your data on your device. We do not operate any servers that receive data from the App. We do not collect personal information, do not run analytics, and do not track usage. All images, videos, recordings, projects, and settings stay on your Mac under your control.

The only situation in which data leaves your device is when you choose to use the optional AI feature, in which case prompts and images are sent directly from your Mac to Anthropic or OpenAI using your own API key. We are not involved in that exchange.

# What we collect

Nothing.

We do not collect, store, or transmit:
- Personal identifiers (name, email, phone, account ID, device ID)
- Images, video, audio, or any content captured by the App
- Project files, layer annotations, or AI chat history
- Usage analytics, telemetry, or behavioral data
- Crash reports
- Location data
- Cookies, advertising identifiers, or fingerprints

We do not have user accounts and the App does not require registration.

# How the App uses your device

To work as a microscopy tool, the App requests access to certain device capabilities through standard macOS permission prompts. All of the following is processed locally on your Mac and never reaches us.

Camera. Used to display live preview, capture frames, and record video from cameras connected to your Mac (built-in, USB, NDI sources, or iPhone via the companion app Microscope Camera Remote). Captured content is saved only to project folders that you choose.

Microphone. Used only if you enable voice control. Audio is processed locally for the sole purpose of recognizing voice commands.
Speech recognition. Used only if you enable voice control. The App relies on Apple's Speech framework to convert voice commands into text. Depending on your macOS version and settings, this may happen entirely on-device or via Apple's speech recognition services. Apple's handling is governed by Apple's Privacy Policy. We do not receive audio or transcripts.

Files and folders. Project data — frames, recordings, exported images, layer annotations, AI chat history, and project settings — is stored in folders that you select on your Mac. You retain full control of these files. We have no access to them.

Photos library. If you choose to export images to the macOS Photos library, the App requests permission to add photos. The App does not read or modify other photos in your library.

Local network. If you use NDI camera sources, the App communicates with NDI devices on your local network. No data is sent to us.

# AI feature (Claude and ChatGPT)

The App includes an optional integration with Anthropic's Claude and OpenAI's ChatGPT. This feature is disabled by default and works only after you enter your own API key for the chosen provider.

Where the API key is stored. Your API key is stored locally on your Mac in the macOS Keychain. We do not have access to it.

What is sent and to whom. When you submit a prompt through the AI feature, the App sends the request directly from your Mac to the servers of Anthropic or OpenAI over a secure HTTPS connection. The request contains:
- Your text prompt
- The current camera frame or selected image
- Information about layers you have referenced in the prompt using the {layer_id} syntax

The request does not pass through any server operated by us. We do not see, log, or store any part of it.

Third-party data handling. Once the data reaches Anthropic or OpenAI, its handling is governed entirely by their privacy policies and terms of service. We encourage you to review them before using the AI feature:
- Anthropic Privacy Policy: https://www.anthropic.com/legal/privacy
- OpenAI Privacy Policy: https://openai.com/policies/privacy-policy

You are responsible for the API key you provide and for any costs charged by the AI provider for API usage.

Disabling the AI feature. Remove your API key from the App's settings at any time. Once removed, no further requests can be made.

# Permissions you can manage

You may grant or deny each permission independently when first prompted, and revoke any of them at any time in System Settings → Privacy & Security:
- Camera (for live preview, capture, recording)
- Microphone (only if voice commands are used)
- Speech Recognition (only if voice commands are used)
- Photos (only if you export to the Photos library)
- Files and Folders (to read and write project files)
- Local Network (for NDI camera sources)
- Network access (for the AI feature, if used)

# Children's privacy

The App is a professional and educational tool that may be used by people of all ages, including in classroom and laboratory settings. Because we do not collect any personal information from anyone, the App does not knowingly collect data from children under 13 (or the equivalent minimum age in your jurisdiction).
International users (GDPR, CCPA, UK DPA, and others)
Because we do not collect, process, or store any personal data about users of the App, this Privacy Policy is consistent with the General Data Protection Regulation (GDPR) of the European Union, the California Consumer Privacy Act (CCPA), the UK Data Protection Act, and similar privacy laws worldwide. There is no personal data for us to share, sell, transfer across borders, or retain about you.

If you choose to use the AI feature, data is sent directly to servers operated by Anthropic or OpenAI, which may be located outside your country. Their respective privacy policies describe their own international transfer practices.

# Your rights
Because we hold no personal data about you, there is nothing on our side for you to access, correct, delete, port, or restrict.

You retain full control of all content created with the App, which is stored locally on your device. You may delete this content at any time by removing the corresponding files or folders.

If you wish to exercise rights regarding data sent to Anthropic or OpenAI through the AI feature, please contact those providers directly using the addresses provided in their privacy policies.

# Changes to this Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in the App's functionality or in applicable law. When we do, we will update the "Last updated" date at the top of this policy and post the new version at the same URL where you found it. Material changes will be communicated through an in-app notice or release notes.

# Contact

If you have any questions or concerns about this Privacy Policy or the App's privacy practices, please contact:

Email: sergey.volskiy@gmail.com
Developer: Serhii Volskyi
Address: Ukraine, Kyiv
