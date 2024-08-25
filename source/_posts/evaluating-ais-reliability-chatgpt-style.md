---
title: Evaluating AI's Reliability - ChatGPT Style
date: 2024-08-24T14:12:48.578Z
updated: 2024-08-25T14:12:48.578Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Evaluating AI's Reliability - ChatGPT Style
excerpt: This Article Describes Evaluating AI's Reliability - ChatGPT Style
thumbnail: https://thmb.techidaily.com/be96a560d136aae29d0d1d935d5244e5292b9067e58872c0b73ef94229888129.jpg
---

## Is CodeGPT The Future of Coding? Evaluating Its Capability to Compose Code

### Quick Links

* [What Is CodeGPT?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#what-is-codegpt)
* [How Much Does CodeGPT Cost?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#how-much-does-codegpt-cost)
* [Can CodeGPT Really Write Code?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#can-codegpt-really-write-code)

### Key Takeaways

* CodeGPT is an AI-powered coding assistant that helps programmers write and fix code, with features like auto-completion and code explanation.
* CodeGPT is available for free, but subscription plans for some features range from $9.99 to $49.99 per month.
* While CodeGPT can write code, its output may not always be error-free or follow best practices, so you should aim to understand and modify the generated code as necessary.

 If you're looking for an AI-powered assistant to help you write code, chances are you've encountered CodeGPT. It's one of many AI-powered tools you can use to assist you when programming. But can CodeGPT actually write code?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## What Is CodeGPT?

 CodeGPT is a dedicated extension that uses different artificial intelligence (AI) models to help programmers write and fix code. It includes various features geared towards faster and easier programming, including auto-completion, code explanation, refactoring, documentation, unit testing, error-checking, and bug-fixing. It also has a ChatGPT-like interface you can access from your code editor.

 The extension is particularly powerful because it lets you connect to various mainstream[large language models (LLMs)](https://www.makeuseof.com/what-are-large-langauge-models-how-do-they-work/) from different providers like OpenAI and Google. On top of that, CodeGPT lets you create your own AI agents that you can use in your projects or share with others.

 While there are several[code editors for Linux](https://www.makeuseof.com/best-ide-code-editors-for-linux/) , macOS, and Windows, CodeGPT is only available in two. Today, you can either[install and use CodeGPT in VS Code](https://www.makeuseof.com/install-use-codegpt-in-vs-code/) or in Cursor, which is a fork of VS Code.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## How Much Does CodeGPT Cost?

 You can download and install CodeGPT for free, but using the extension comes at a cost. CodeGPT offers various subscription packages that you can pay for if you need unlimited access.

 CodeGPT Plus has three subscription plans. The Basic plan goes for $9.99/month, followed by Standard ($19.99/month) and Gold ($49.99/month). There's a free trial period available, which you can use to evaluate the extension. Each package gives you access to specific AI agents with unlimited interactions.

 Bear in mind that you'll need to pay for unlimited usage of third-party AI models like OpenAI's GPT-4 model, for example. Although you can[access Open AI's GPT-4 model for free](https://www.makeuseof.com/ways-access-gpt-4-free/) , you cannot do so from within VS Code or Cursor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## Can CodeGPT Really Write Code?

 To evaluate this, we'll use the extension to help us generate two different code samples in Python.

 First, we ask the model to generate a stack data structure in Python with all the relevant methods. We used this prompt:

> Create a stack in Python and include all the necessary methods

The model generated the following response:

        `class Stack:  
    def __init__(self):  
        self.stack = []  
​  
    def push(self, item):  
        self.stack.append(item)  
​  
    def pop(self):  
        if self.is_empty():  
            raise IndexError("Pop from empty stack")  
        return self.stack.pop()  
​  
    def peek(self):  
        if self.is_empty():  
            raise IndexError("Peek from empty stack")  
        return self.stack[-1]  
​  
    def is_empty(self):  
        return len(self.stack) == 0  
​  
    def size(self):  
        return len(self.stack)`

 This sample shows that CodeGPT is clever enough to create the stack using a**class** and include the necessary checks to handle specific errors that may arise. For instance, the code throws informative errors if you try to**peek** or**pop** an empty stack.

 In a second challenge, we asked CodeGPT to save a response formatted in JSON from the[JSONPlaceholder](https://jsonplaceholder.typicode.com/) API to a CSV file. For context, the response from the JSONPlaceholder API looks like this:

        `{  
 'userId': 1,  
 'id': 1,  
 'title': 'sunt aut facere repellat provident occaecati excepturi optio reprehenderit',  
 'body': 'quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto'  
}`

We asked CodeGPT the following:

> I've made a request to an external API at <https://jsonplaceholder.typicode.com/posts/1> and I'm getting a response back. I've formatted the response as json, how can I save it in a csv file?

The code that CodeGPT responded with was:

        `import csv  
import requests  
  
# Make a GET request to the API  

response = requests.get('<https://jsonplaceholder.typicode.com/posts/1>')  

# Convert the response to JSON format  

data = response.json()  
  
# Since we're receiving a dictionary, we need to turn it into a list of one dictionary  

data = [data]  
  
# Open (or create) a CSV file to write the data  

with open('output.csv', 'w', newline='') as output_file:  
   # Create a CSV writer object  
   writer = csv.DictWriter(output_file, fieldnames=data[0].keys())  
   # Write the CSV headers  
   writer.writeheader()  
   # Write the data to the CSV file  
   writer.writerows(data)  
`

 Generally, this response is good; it doesn't need any tweaking to work. CodeGPT also added comments explaining the purpose of the various lines of code, which is useful if you're doing something for the first time.

 The only issue here is the response doesn't specify an encoding type while calling**open()** . While a default will automatically be included, specifying an encoding type is recommended and considered best practice when[writing to files in Python](https://www.makeuseof.com/write-print-to-file-python/) . This might save you from incorrect interpretation, leading to jumbled text.

 So: CodeGPT can write code, but you should be careful because it won't always give you the best output. What you get might be error-prone and might not follow the best practices. Whenever you use CodeGPT or any other AI-powered tool to write code, strive to understand what the code does first. Don't just copy and paste.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-cutting-edge-techniques-mastering-youtube-subtitlecc-additions/"><u>[New] 2024 Approved  Cutting-Edge Techniques  Mastering YouTube Subtitle/CC Additions</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-try-the-tiktok-craze-today-with-our-picks/"><u>[New] 2024 Approved  Try the TikTok Craze Today with Our Picks</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-achieving-maximum-comfort-in-vr-landscape/"><u>[New] Achieving Maximum Comfort in VR Landscape</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-aligning-phonetablet-zoom-schedules-with-pc-plans/"><u>[New] In 2024, Aligning Phone/Tablet Zoom Schedules with PC Plans</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-keeping-your-browsing-free-of-pop-up-videos/"><u>[New] In 2024, Keeping Your Browsing Free of Pop-Up Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-premier-9-video-calls-prioritizing-security-in-smes/"><u>[New] In 2024, Premier 9 Video Calls  Prioritizing Security in SMEs</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-unveiling-strategies-to-stand-out-with-a-great-podcast-name/"><u>[New] In 2024, Unveiling Strategies to Stand Out with a Great Podcast Name</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instagrams-power-in-motion-crafting-a-comprehensive-video-plan-for-2024/"><u>[New] Instagram's Power in Motion  Crafting a Comprehensive Video Plan for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-15-gadget-unboxers-your-ultimate-2024-guide/"><u>[New] Top 15 Gadget Unboxers  Your Ultimate 2024 Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-a-vloggers-guide-to-camera-lenses-wondershare-filmora-for-2024/"><u>[Updated] A Vlogger's Guide To Camera Lenses | Wondershare Filmora for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-crafting-success-pushing-your-video-into-top-charts-for-2024/"><u>[Updated] Crafting Success  Pushing Your Video Into Top Charts for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-greatest-action-packed-gaming-escapades-top-10-for-2024/"><u>[Updated] Greatest Action-Packed Gaming Escapades (Top 10) for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-framebyframe-faceoff/"><u>[Updated] In 2024, FrameByFrame Faceoff</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-simplified-guide-to-movie-recording-on-diverse-systems-for-2024/"><u>[Updated] Simplified Guide to Movie Recording on Diverse Systems for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-unlocking-the-potential-of-pc-based-tiktok-live-shows-for-2024/"><u>[Updated] Unlocking the Potential of PC-Based TikTok Live Shows for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-the-transformative-power-of-augmented-vision/"><u>2024 Approved  The Transformative Power of Augmented Vision</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-apple-iphone-12-mini-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from Apple iPhone 12 mini</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ace-your-conversations-is-google-bard-or-bing-chat-the-top-contender/"><u>Ace Your Conversations: Is Google Bard or Bing Chat the Top Contender?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/achieving-success-a-guide-to-setting-health-objectives-using-chatgpt/"><u>Achieving Success: A Guide to Setting Health Objectives Using ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beneath-the-binary-chatgpts-interpretative-mechanism-explored/"><u>Beneath the Binary: ChatGPT's Interpretative Mechanism Explored</u></a></li>
<li><a href="https://tech-revival.techidaily.com/bing-chat-vs-chatgpt-for-freelancers-a-comprehensive-analysis-of-8-crucial-factors/"><u>Bing Chat Vs. ChatGPT for Freelancers: A Comprehensive Analysis of 8 Crucial Factors</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boost-income-with-ai-ventures-expert-tech-for-building-computers-and-nostalgic-handheld-device-tips/"><u>Boost Income with AI Ventures, Expert Tech for Building Computers & Nostalgic Handheld Device Tips</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comprehensive-tutorial-on-setting-up-codegpt-for-developers-using-vs-code/"><u>Comprehensive Tutorial on Setting Up CodeGPT for Developers Using VS Code</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-error-e1-in-windows-10-11-editions/"><u>Eradicate Error E1 in Windows 10, 11 Editions</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evaluating-artificial-intelligence-for-personal-finance-decisions/"><u>Evaluating Artificial Intelligence for Personal Finance Decisions</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evolving-interactions-discover-the-six-surprising-uses-of-snapchats-my-ai-feature/"><u>Evolving Interactions: Discover the Six Surprising Uses of Snapchat's My AI Feature</u></a></li>
<li><a href="https://tech-revival.techidaily.com/excel-and-evolve-with-ai-proven-techniques-to-succeed-in-a-technology-driven-office/"><u>Excel and Evolve with AI: Proven Techniques to Succeed in a Technology-Driven Office</u></a></li>
<li><a href="https://tech-revival.techidaily.com/excels-visualization-brilliance-chatgpt-counterpart-lacks-this/"><u>Excel's Visualization Brilliance: ChatGPT Counterpart Lacks This</u></a></li>
<li><a href="https://tech-revival.techidaily.com/generative-ai-showdown-comparing-chatgpt-and-bing-chat-who-takes-the-lead/"><u>Generative AI Showdown: Comparing ChatGPT and Bing Chat – Who Takes the Lead?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/get-back-to-binge-watching-solved-issues-of-netflix-not-playing-properly-on-xbox/"><u>Get Back to Binge-Watching: Solved Issues of Netflix Not Playing Properly on Xbox</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-many-tokens-can-chatgpt-process-and-is-there-a-way-to-go-over-the-limit/"><u>How Many Tokens Can ChatGPT Process and Is There a Way to Go Over the Limit?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-safe-is-your-ai-companion-unpacking-the-threats-of-neural-network-mining/"><u>How Safe Is Your AI Companion: Unpacking the Threats of Neural Network Mining</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-8-plus-to-android-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 8 Plus to Android? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/humor-by-algorithm-assessing-chatgpts-ability-to-deliver-a-punchline/"><u>Humor by Algorithm: Assessing ChatGPT's Ability to Deliver a Punchline</u></a></li>
<li><a href="https://tech-revival.techidaily.com/impatient-for-a-direct-chat-with-chatgpt-on-your-computer-heres-why-you-shouldnt-overlook-open-source-substitutes/"><u>Impatient for a Direct Chat with ChatGPT on Your Computer? Here's Why You Shouldn’t Overlook Open Source Substitutes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-high-definition-screen-memory-tools/"><u>In 2024, High Definition Screen Memory Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-realistic-quantum-leaps-a-vfx-perspective/"><u>In 2024, Realistic Quantum Leaps  A VFX Perspective</u></a></li>
<li><a href="https://tech-revival.techidaily.com/love-in-the-time-of-algorithms-how-cyber-crooks-harness-ai-for-fraudulent-affairs/"><u>Love in the Time of Algorithms: How Cyber Crooks Harness AI for Fraudulent Affairs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/master-data-interactions-with-gpt-enhanced-tools/"><u>Master Data Interactions with GPT-Enhanced Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-important-top-6-factors-before-leveraging-chatgpt-for-mental-health-assistance/"><u>Navigating the Important Top 6 Factors Before Leveraging ChatGPT for Mental Health Assistance</u></a></li>
<li><a href="https://tech-revival.techidaily.com/seeking-honesty-in-chatgpts-responses/"><u>Seeking Honesty in ChatGPT's Responses</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-future-workplace-revolution-how-generative-ai-shapes-7-key-job-trends/"><u>The Future Workplace Revolution: How Generative AI Shapes 7 Key Job Trends</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-poets-tool-leveraging-chatgpt-in-verses-writing/"><u>The Poet's Tool: Leveraging ChatGPT in Verses Writing</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-science-behind-conversational-ai-exploring-the-techniques-that-enable-chatbots-to-mimic-human-interaction/"><u>The Science Behind Conversational AI: Exploring the Techniques that Enable Chatbots to Mimic Human Interaction</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-meizu-21-pro-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Meizu 21 Pro Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-8-side-hustles-with-chatgpt-unlocking-real-cash-flow-potential/"><u>Top 8 Side Hustles with ChatGPT: Unlocking Real Cash Flow Potential</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/transform-your-tiktok-footage-with-enlarged-characters-for-2024/"><u>Transform Your TikTok Footage with Enlarged Characters for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/trouble-with-chatgpt-5-effective-tactics-to-verify-its-up-and-running/"><u>Trouble with ChatGPT? 5 Effective Tactics to Verify It's Up and Running</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-ai-black-boxes-an-insight-into-their-functioning/"><u>Understanding AI Black Boxes: An Insight Into Their Functioning</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-gpt-4-an-in-depth-look-at-7-integrated-apps/"><u>Understanding GPT-4: An In-Depth Look at 7 Integrated Apps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleash-inspiration-exploring-the-top-5-ai-text-generators-for-writers/"><u>Unleash Inspiration: Exploring the Top 5 AI Text Generators for Writers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-all-the-secrets-the-full-scoop-on-artificial-intelligence-from-apples-wwdc-2024/"><u>Unveiling All the Secrets: The Full Scoop on Artificial Intelligence From Apple's WWDC 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-power-of-emotion-artificnal-intelligence-understanding-felt-experiences-digitally/"><u>Unveiling the Power of Emotion Artificnal Intelligence: Understanding Felt Experiences Digitally</u></a></li>
<li><a href="https://tech-revival.techidaily.com/what-drives-cybercriminals-to-infiltrate-chatgpt-user-accounts/"><u>What Drives Cybercriminals to Infiltrate ChatGPT User Accounts?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-snapchats-ai-goes-beyond-playful-interaction/"><u>Why Snapchat’s AI Goes Beyond Playful Interaction</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Vivo Y02T | Dr.fone</u></a></li>
</ul></div>
