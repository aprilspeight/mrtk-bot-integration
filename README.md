# <p align="center">Made with MRTK: Bot Integration</p>
<p align="center">
  <a href="https://github.com/aprilspeight/mrtk-spatial-awareness/blob/master/README.md#requirements">Requirements</a> |
  <a href="https://github.com/aprilspeight/mrtk-spatial-awareness/blob/master/README.md#videos">Videos</a> |
  <a href="https://github.com/aprilspeight/mrtk-spatial-awareness/blob/master/README.md#view-the-sample">View the Sample</a> | 
  <a href="https://github.com/aprilspeight/mrtk-spatial-awareness/blob/master/README.md#resources">Resources</a> | 
  <a href="https://github.com/aprilspeight/mrtk-spatial-awareness/blob/master/README.md#contact">Contact</a>
</p>

MRTK-Unity is a Microsoft-driven project that provides a set of components and features, used to accelerate cross-platform MR app development in Unity.

The videos and sample in this repository provides an introductory to creating a bot with the QnA Maker and integrating into a Mixed Reality project.

**Note**: This project uses billable Azure services. Be sure to delete your Azure resources if you do not intend to use this app for production.

## Requirements

- Windows 10
- Unity Version 2019.4.11f1
- [MRTK Foundation Package 2.5.3] (https://github.com/microsoft/MixedRealityToolkit-Unity/releases/tag/v2.5.3)
- [Tools Installed for Windows Mixed Reality development](https://docs.microsoft.com/windows/mixed-reality/develop/install-the-tools?tabs=unity&WT.mc_id=spatial-0000-apspeigh)

## Videos

Videos are published on YouTube in the playlist: [Made with MRTK: Bot Integration](https://www.youtube.com/c/vogueandcode)

|  Title |  Description |  Link |
|---|---|---|
| **Bot Integration: Setup Project**  | Learn how to setup your Unity environment in preparation to integrate a bot into the experience.  | [https://youtu.be/li5GDKHWzAk](https://youtu.be/li5GDKHWzAk)  |
| **Bot Integration: Create Azure Resources** |  Learn how to create the Azure resources and the bot. | [https://youtu.be/HPUMXxeDq4M](https://youtu.be/HPUMXxeDq4M) |
| **Bot Integration: Create UI and Bot Integration**  | Learn how to create the UI and add the scripts for bot integration.  | [https://youtu.be/pQO5P72n8Vc](https://youtu.be/pQO5P72n8Vc)    |
| **Bot Integration: Demo** | View a demo of the project with a HoloLens 2.  | [https://youtu.be/zo-VHyKwraM](https://youtu.be/zo-VHyKwraM)  |


## View the Sample

1. Install the [required tools](https://aka.ms/install-the-tools) for Windows Mixed Reality development.
2. Unzip the package.
3. Create a new Unity project.
4. [Configure Unity for Windows Mixed Reality development](https://aka.ms/learn-mrtk-unity).
5. Configure the Publishing capabilities: Internet Client, Internet Client Service, Private Network Client Server, Microphone.
6. Import the Cognitive Services Speech SDK.
7. Import TMP essential resources
8. Import the Mixed Reality Toolkit Foundation package. After import, in the MRTK Project Configurator window, select **MS HRTF Spatializer** for the **Spatializer Plugin**. 
Next, apply the default settings in the **MRTK Project Configurator**. Finally, add MRTK to scene and configure.
9. Open the sample_bot_integration scene (Project panel > Assets > Scenes > sample_bot_integration).
10. In the Microphone object, enter your Subscription Key, Region, and Bot ID in the Bot(Script) component.
11. Ensure that all objects are assigned to Listen Once Button (Microphone), Recognized Text (Recognixed Text), Error Text (Error), and State Indicator (Connection Status).
12. Click the **play button** to enter play mode.

Note: To simulate hand input, press the spacebar (right hand) and/or the left shift key (left hand).

## Resources

Mixed Reality Toolkit Repo: [aka.ms/mrtk](https://aka.ms/mrtk)

Tools to Install for Windows Mixed Reality Development: [aka.ms/install-the-tools](https://aka.ms/install-the-tools/?WT.mc_id=spatial-10982-apspeigh)

Set up a mixed reality project in Unity with the Mixed Reality Toolkit: [aka.ms/learn-mrtk-unity](https://aka.ms/learn-mrtk-unity/?WT.mc_id=spatial-10982-apspeigh)

Cognitive Services Speech SDK: [Microsoft.CognitiveServices.Speech](https://www.nuget.org/packages/Microsoft.CognitiveServices.Speech)

Create an Azure Account: [aka.ms/mrtk-azure](aka.ms/mrtk-azure)

QnA Maker Quickstart: [aka.ms/qna-maker](https://docs.microsoft.com/azure/cognitive-services/qnamaker/quickstarts/create-publish-knowledge-base?tabs=v1%2F%3FWT.mc_id%3Dspatial-10640-apspeigh&WT.mc_id=spatial-0000-apspeigh)

Connect to Direct Line of Speech: [aka.ms/direct-line-of-speech](https://docs.microsoft.com/azure/bot-service/bot-service-channel-connect-directlinespeech/?WT.mc_id=spatial-10640-apspeigh)

## Contact

Have a question or issue accessing a video or trying the sample? Submit an issue to the repo!
