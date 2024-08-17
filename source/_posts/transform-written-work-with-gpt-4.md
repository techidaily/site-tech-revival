---
title: Transform Written Work with GPT-4
date: 2024-08-16T15:05:20.160Z
updated: 2024-08-17T15:05:20.160Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Transform Written Work with GPT-4
excerpt: This Article Describes Transform Written Work with GPT-4
thumbnail: https://thmb.techidaily.com/a0bc606d13bf5b4bb98db38e302e2de3fccfa94f74c2f49ef3ec08979e13d4fd.jpg
---

## Can CodeGPT Transform How You Write Code? Discover Its Capabilities Now

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
### Quick Links

* [What Is CodeGPT?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#what-is-codegpt)
* [How Much Does CodeGPT Cost?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#how-much-does-codegpt-cost)
* [Can CodeGPT Really Write Code?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#can-codegpt-really-write-code)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
### Key Takeaways

* CodeGPT is an AI-powered coding assistant that helps programmers write and fix code, with features like auto-completion and code explanation.
* CodeGPT is available for free, but subscription plans for some features range from $9.99 to $49.99 per month.
* While CodeGPT can write code, its output may not always be error-free or follow best practices, so you should aim to understand and modify the generated code as necessary.

 If you're looking for an AI-powered assistant to help you write code, chances are you've encountered CodeGPT. It's one of many AI-powered tools you can use to assist you when programming. But can CodeGPT actually write code?

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is CodeGPT?

 CodeGPT is a dedicated extension that uses different artificial intelligence (AI) models to help programmers write and fix code. It includes various features geared towards faster and easier programming, including auto-completion, code explanation, refactoring, documentation, unit testing, error-checking, and bug-fixing. It also has a ChatGPT-like interface you can access from your code editor.

 The extension is particularly powerful because it lets you connect to various mainstream[large language models (LLMs)](https://www.makeuseof.com/what-are-large-langauge-models-how-do-they-work/) from different providers like OpenAI and Google. On top of that, CodeGPT lets you create your own AI agents that you can use in your projects or share with others.

 While there are several[code editors for Linux](https://www.makeuseof.com/best-ide-code-editors-for-linux/) , macOS, and Windows, CodeGPT is only available in two. Today, you can either[install and use CodeGPT in VS Code](https://www.makeuseof.com/install-use-codegpt-in-vs-code/) or in Cursor, which is a fork of VS Code.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How Much Does CodeGPT Cost?

 You can download and install CodeGPT for free, but using the extension comes at a cost. CodeGPT offers various subscription packages that you can pay for if you need unlimited access.

 CodeGPT Plus has three subscription plans. The Basic plan goes for $9.99/month, followed by Standard ($19.99/month) and Gold ($49.99/month). There's a free trial period available, which you can use to evaluate the extension. Each package gives you access to specific AI agents with unlimited interactions.

 Bear in mind that you'll need to pay for unlimited usage of third-party AI models like OpenAI's GPT-4 model, for example. Although you can[access Open AI's GPT-4 model for free](https://www.makeuseof.com/ways-access-gpt-4-free/) , you cannot do so from within VS Code or Cursor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<li><a href="https://youtube-data.techidaily.com/implified-guide-to-free-youtube-card-designing-for-2024/"><u>[New] Simplified Guide to Free YouTube Card Designing for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-how-to-upside-down-your-instagram-videos-complete-manual/"><u>[Updated] In 2024, How to Upside Down Your Instagram Videos [Complete Manual]</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-insta-videography-dimensions-for-the-ultimate-visual-impact/"><u>2024 Approved  Insta Videography  Dimensions for the Ultimate Visual Impact</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Tecno Spark Go (2024) | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/abandon-chatgpt-step-by-step/"><u>Abandon ChatGPT: Step by Step</u></a></li>
<li><a href="https://tech-revival.techidaily.com/academic-evolution-or-revolution-the-role-of-ai-in-modern-student-essays/"><u>Academic Evolution or Revolution? The Role of AI in Modern Student Essays</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-as-therapy-the-unseen-risks-you-should-know/"><u>AI as Therapy: The Unseen Risks You Should Know</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-driven-approaches-to-streamline-domestic-life/"><u>AI-Driven Approaches to Streamline Domestic Life</u></a></li>
<li><a href="https://tech-revival.techidaily.com/balancing-risk-with-ais-financial-forecasts-the-challenge/"><u>Balancing Risk with AI's Financial Forecasts: The Challenge</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-your-apple-iphone-6s-plus-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code On your Apple iPhone 6s Plus</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/bypassing-instagrams-video-roadblocks-effortlessly/"><u>Bypassing Instagram's Video Roadblocks Effortlessly</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/charting-new-territory-after-magixs-acid-pro-for-2024/"><u>Charting New Territory After Magix's ACID Pro for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-and-the-path-to-regular-meditation-tips-and-strategies-for-a-peaceful-mind/"><u>ChatGPT and the Path to Regular Meditation: Tips and Strategies for a Peaceful Mind</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpts-impact-on-modern-day-job-seekers/"><u>ChatGPT's Impact on Modern-Day Job Seekers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/claude-2-demystified-what-it-is-how-to-use-it-and-why-you-should-care/"><u>Claude 2 Demystified: What It Is, How to Use It, and Why You Should Care</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-grok-ai-with-elon-musk-the-breakthrough-in-artificial-intelligence-explained/"><u>Decoding Grok AI with Elon Musk: The Breakthrough in Artificial Intelligence Explained</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dodging-fraudsters-a-guide-to-genuine-vs-bogus-bingcoin-offers/"><u>Dodging Fraudsters: A Guide to Genuine vs Bogus BingCoin Offers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/emoji-less-tweets-for-clarity-linuss-revealed-secrets-trojans-explained-and-ai-conversational-challenges/"><u>Emoji-Less Tweets for Clarity, Linus's Revealed Secrets, Trojans Explained, & AI Conversational Challenges.</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-ai-accuracy-six-innovative-approaches-to-reduce-hallucination-in-machine-learning-responses/"><u>Enhancing AI Accuracy: Six Innovative Approaches to Reduce Hallucination in Machine Learning Responses</u></a></li>
<li><a href="https://tech-revival.techidaily.com/essential-extensions-elevating-vs-code-with-gpt-features/"><u>Essential Extensions: Elevating VS Code with GPT Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evaluating-bing-chat-vs-chatgpt-key-considerations-for-freelancers/"><u>Evaluating Bing Chat Vs. ChatGPT: Key Considerations for Freelancers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/explore-the-most-effective-chatterbots-5-unbeatable-extensions-for-vs-code-developers/"><u>Explore the Most Effective Chatterbots: 5 Unbeatable Extensions for VS Code Developers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-consequences-of-the-european-commissions-ai-act-on-ai-communication-systems-like-chatgpt/"><u>Exploring the Consequences of the European Commission's AI Act on AI Communication Systems Like ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-realm-of-artificial-intelligence-understanding-risks-involved/"><u>Exploring the Realm of Artificial Intelligence: Understanding Risks Involved</u></a></li>
<li><a href="https://tech-revival.techidaily.com/free-gpt-4-for-everyone-nonetheless-select-plus-membership-continues-to-provide-unique-services/"><u>Free GPT-4 for Everyone; Nonetheless, Select Plus Membership Continues to Provide Unique Services.</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-tutorial-to-bypass-your-lava-storm-5g-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Lava Storm 5G Face Lock?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-epson-v39-printer-drivers-up-to-date-on-windows-7-8-and-10/"><u>Get Your Epson V39 Printer Drivers Up to Date on Windows 7, 8 & 10</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guiding-youngsters-a-parents-guide-to-securely-using-chatgpt/"><u>Guiding Youngsters: A Parent’s Guide to Securely Using ChatGPT</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-infinix-hot-40i-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Infinix Hot 40i</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-will-machine-learning-reshape-the-landspectrum-of-video-games/"><u>How Will Machine Learning Reshape the Landspectrum of Video Games?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-apple-iphone-12-mini-and-ipad-securely-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on Apple iPhone 12 mini and iPad Securely</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y200e-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y200e 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-interactive-cosmos-explored-metaverse-versus-omniverse-discussed/"><u>In 2024, Interactive Cosmos Explored  Metaverse Versus Omniverse Discussed</u></a></li>
<li><a href="https://tech-revival.techidaily.com/machine-talk-deciphering-the-gpt-bing-divide/"><u>Machine Talk: Deciphering the GPT-Bing Divide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-chatgpts-unique-command-options-what-can-they-accomplish/"><u>Navigating ChatGPT’s Unique Command Options – What Can They Accomplish?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-pathway-of-earning-through-bug-hunting-at-openai/"><u>Navigating the Pathway of Earning Through Bug Hunting at OpenAI</u></a></li>
<li><a href="https://extra-resources.techidaily.com/photo-pinnacle-top-tripods-for-android-and-iphones/"><u>Photo Pinnacle  Top Tripods for Android & iPhones</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-workflow-7-amazing-benefits-of-integrating-chatgpt-into-your-daily-routine/"><u>Revolutionize Your Workflow: 7 Amazing Benefits of Integrating ChatGPT Into Your Daily Routine</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionizing-conversational-agents-unlock-potential-with-these-7-powerful-ai-prompt-tips/"><u>Revolutionizing Conversational Agents: Unlock Potential with These 7 Powerful AI Prompt Tips</u></a></li>
<li><a href="https://tech-revival.techidaily.com/sarah-silverman-joins-legal-battle-against-openai-and-meta-the-rising-conflict-over-ai-rights/"><u>Sarah Silverman Joins Legal Battle Against OpenAI & Meta: The Rising Conflict over AI Rights</u></a></li>
<li><a href="https://tech-revival.techidaily.com/surprising-connectivity-discuss-with-chatgpt/"><u>Surprising Connectivity: Discuss with ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-non-number-registration-guide-for-telegram-and-more/"><u>The Non-Number Registration Guide for Telegram & More</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-ai-uprising-between-gemini-max-and-gptplusplus/"><u>The Ultimate AI Uprising: Between Gemini Max & GPT++</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-vivo-y100-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Vivo Y100 Reset Code | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-10-international-tech-visionaries-share-their-insights-on-artificeial-intelligence/"><u>Top 10 International Tech Visionaries Share Their Insights on Artificeial Intelligence</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-5-no-cost-innovative-image-design-tools/"><u>Top 5 No-Cost, Innovative Image Design Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-thrilling-new-capabilities-of-bard-unveiled-at-google-io-2023-event/"><u>Top 7 Thrilling New Capabilities of BARD Unveiled at Google I/O 2023 Event</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/top-rated-mouse-compatible-with-your-ipad-find-the-ultimate-pairing/"><u>Top-Rated Mouse Compatible with Your iPad: Find the Ultimate Pairing</u></a></li>
</ul></div>
