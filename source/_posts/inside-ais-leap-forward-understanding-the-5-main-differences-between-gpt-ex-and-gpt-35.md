---
title: "Inside AI's Leap Forward: Understanding the 5 Main Differences Between GPT-eX and GPT-3.5"
date: 2024-08-16T14:11:31.398Z
updated: 2024-08-17T14:11:31.398Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Inside AI's Leap Forward: Understanding the 5 Main Differences Between GPT-eX and GPT-3.5"
excerpt: "This Article Describes Inside AI's Leap Forward: Understanding the 5 Main Differences Between GPT-eX and GPT-3.5"
thumbnail: https://thmb.techidaily.com/f1c57303ea622caa2e3702d3e2a77e00493f995e737fa90087cc4940fcb0139c.jpg
---

## Understanding Word and Character Quotas in AI-Powered Chatbots Like GPT-3

### Key Takeaways

* ChatGPT responses are not limitless in length, despite the initial claim. There are hidden limits determined by the token system, past conversations, and system demands.
* The token system used by ChatGPT considers both the length of queries and answers. The available token lengths vary depending on the GPT model used.
* To get longer responses from ChatGPT, you can ask it to continue, break your question into smaller sections, use the regenerate option, specify a word count limit, or start a new conversation. These techniques can help you work around the unofficial limits and receive more complete answers.

 ChatGPT is big news. But how big are the responses you get from this all-purpose chatbot?

 Establishing this is not as simple as you may think. For starters, ask ChatGPT this question, and you will be assured that there are no set limits to the length of its responses.

 However, as we uncover here, it isn't that straightforward. There are hidden limits to the length of a ChatGPT response, but there are also some nifty and simple workarounds to help you get longer answers.

## How Does ChatGPT Determine the Length of a Response?

[How ChatGPT works is complex](https://www.makeuseof.com/how-does-chatgpt-work/) , and the response length varies depending on what is being asked and the level of detail requested. As the next screenshot shows, ChatGPT claims there are no strict limits.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![Screenshot of ChatGPT Declaring No Limits](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-declaring-no-limits.jpg)

 Of course, asking ChatGPT about itself isn't a good idea since it isn't typically objective about its abilities or has limited information. So, we ran some tests to determine the length limits of ChatGPT responses. We asked the chatbot to write a 5000-word article on the history of the FIFA World Cup. ChatGPT's assessment of itself differed from the results we found.

![Asking ChatGPT to write 5000 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-5000-words-article.jpg)

 ChatGPT is a powerful tool. But maybe 5,000 words was asking a bit too much, so I asked for 2,500 words instead.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Asking ChatGPT to write 2500 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-2500-words-article.jpg)

 ChatGPT still said it wasn't able to fulfill the request. We worked down to 1,000 words before the chatbot produced the article. But there was another problem: no matter how many times we tried, ChatGPT couldn't produce 1,000 words on the subject. But why? What's limiting the chatbot's ability to produce longer replies?

 Part of the answer as to why this happens lies in something called the token system.

### What Is the Token System ChatGPT Uses?

 When you ask ChatGPT a question, the length of the replies it can provide depends on a token system. Rather than a simple word count to determine the length of both queries and answers, ChatGPT uses this system. Notice something? The length of both "queries and answers" is taken into consideration. The token system breaks down each input and output into a series of tokens to classify the request and response size.

 While word count does play a part in this, it isn't the whole story. For instance, the example below was entered into[OpenAI's Tokenizer tool](https://platform.openai.com/tokenizer) .

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Screenshot of ChatGPT Tokenizer tool test](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-tokenizer-tool-test.jpg)

 The sentence "How many words have I typed" and answer "6" were "tokenized" to a value of nine tokens. This is consistent with OpenAI's "rule of thumb" that one token is equivalent to around three-quarters of a word.

 Here's where things get a little bit tricky. OpenAI's GPT models come in varying token lengths. The standard GPT-4 model that comes with your ChatGPT Plus subscription offers anywhere between 4k and 8k token context length. OpenAI also provides an extended 32k token context length GPT-4 model. The GPT-3.5 series offers even more token variety. There are 4k, 8k, and 16k GPT-3.5 models. However, not all these models are publicly available.

 We used the base GPT-3.5 and supposed GPT-4 8k models for this test. We say "supposed" because the 8k tag didn't check out when we ran a context window test. And then there's the fact that there's no confirmation from official sources that the GPT-4 model at chat.openai.com is an 8k model.

 The base GPT 3.5 4k model is supposed to restrict user questions and replies to 4,097 tokens. Similarly, the GPT-4 8k model is supposed to deliver 8,192 tokens. By OpenAI's reckoning, this equates to about 3,000 words for the GPT-3.5 and around 5,000 to 6,000 words for the GPT-4 8k tokens. But wait a minute. With an approximate 3,000 to 6,000 words capacity on either model, why wasn't ChatGPT able to deliver a 2,500-word or even 1,500-word article when we requested? Why are ChatGPT responses much less than their advertised token count or context length?

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Why Are ChatGPT's Responses Limited?

 While token length looks straightforward and good in theory, there's more to how AI models consider these limits. There are two notable considerations.

1. **Past Conversations** : Because ChatGPT is a conversational chatbot, whenever you ask a question, the chatbot considers older conversations to stay consistent and ensure natural-sounding interactions. This means in longer conversations, older prompts and responses are invariably considered as part of the context window and end up eating your token length. So, it is not just the immediate question and replies that is considered in the context window calculation.
2. **System Demand** :[ChatGPT has quickly become one of the fastest-growing apps of all time](https://www.makeuseof.com/how-chatgpt-became-fastest-growing-app/) . This has generated a huge demand for ChatGPT. To ensure everyone gets a piece of the action, 8k tokens might not always be 8k. Remember, the more tokens to process, the more demand on the system. To lessen the average demand from each user, responses are curtailed to far below the stated limits.

 To stress, this is not a fixed rule—we generated outputs that exceeded this by almost two hundred words. However, this can be considered a safe upper limit to achieve complete answers.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
## How to Get Longer Responses From ChatGPT

 Once you understand that there is a "hidden limit" to ChatGPT's responses, there are some simple ways to help you get more complete responses.

1. **Ask ChatGPT to Continue:** If ChatGPT stops partway through an answer, then one option is to simply ask it to continue. In the example below, we typed "Go on," and it added another two hundred words to the response.  
![Screenshot of ChatGPT being prompted to continue](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-being-prompted-to-continue.jpg)
2. **Break your question into smaller sections:** For instance, we asked it several times to write an essay on the impact of AI on society. One option here is to ask it to bullet-point some topics for an essay on AI, then use the supplied bullet points as individual prompts.  
![Screenshot of ChatGPT response to AI Bullet points](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-response-to-ai-bullet-points.jpg)
3. **Use the Regenerate option:** While this might throw up the same error, with nothing to lose, it is always worth a shot.
4. **Specify an upper limit to your word count in your prompt:** The image below illustrates how this can be used to manipulate the maximum word count in an answer.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![Screenshot of using a word limit for ChatGPT response](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-using-a-word-limit-for-chatgpt-response.jpg)
5. **Start a new conversation** : starting a new conversation gives you a clean slate to work with. Remember, ChatGPT considers past prompts and responses in a conversation. Starting a new chat gives you unused context to work with.

 These tips will help you to get more complete answers from ChatGPT and work around the unofficial limit in the length of its responses.

## ChatGPT: Quality Over Quantity

 While there is no official information on the maximum length of ChatGPT responses, in practice, there are hidden constraints. The token system, influenced by past conversations and system demand, all impact how long ChatGPT's answers can be. However, by asking ChatGPT to continue, breaking questions into parts, regenerating responses, specifying word counts, and starting new chats, you can often get more complete, longer replies. Though not perfect, being aware of these unofficial limits and using the right techniques can help you get the most out of this powerful AI chatbot.


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
<li><a href="https://screen-video-capture.techidaily.com/new-10-innovative-ideas-to-shield-your-webcam/"><u>[New] 10 Innovative Ideas to Shield Your Webcam</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-a-successful-online-business-with-youtube-studio-for-2024/"><u>[New] Crafting a Successful Online Business with Youtube Studio for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-your-wayback-machine-facebooks-story-archives-at-your-service/"><u>[New] Your Wayback Machine  Facebook’s Story Archives at Your Service</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-audioarchitects-building-without-dacast/"><u>[Updated] AudioArchitects  Building Without DaCast</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-uncovering-budget-friendly-video-conferencing-tools-for-multiple-systems/"><u>[Updated] In 2024, Uncovering Budget-Friendly Video Conferencing Tools for Multiple Systems</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-techniques-for-turning-youtube-hosted-tweets-into-audio-files/"><u>[Updated] Techniques for Turning YouTube-Hosted Tweets Into Audio Files</u></a></li>
<li><a href="https://tech-revival.techidaily.com/10-new-age-conversational-apps-outshining-gpt/"><u>10 New Age Conversational Apps Outshining GPT</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-firecapture-extensions-for-ff-users/"><u>2024 Approved  FireCapture Extensions for FF Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-giggle-guide-quick-tips-for-meme-artistry/"><u>2024 Approved  Giggle Guide  Quick Tips for Meme Artistry</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-gopro-karma-drone-review/"><u>2024 Approved  GoPro Karma Drone Review</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-zoom-video-enhancement-playbook/"><u>2024 Approved  The Ultimate Zoom Video Enhancement Playbook</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-on-apple-iphone-xs-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled On Apple iPhone XS? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://tech-revival.techidaily.com/are-emerging-language-models-threatening-to-replace-established-search-engines-like-googles/"><u>Are Emerging Language Models Threatening to Replace Established Search Engines Like Google's?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/avoid-using-your-phone-numbers-easy-steps-for-registering-on-popular-messaging-apps/"><u>Avoid Using Your Phone Numbers: Easy Steps for Registering on Popular Messaging Apps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beating-the-overloaded-message-chatgpt-capacity-errors-on-windows-explained/"><u>Beating the Overloaded Message: ChatGPT Capacity Errors on Windows Explained</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boost-your-workflow-with-onlyoffice-docspace-and-chatgpt-synergy/"><u>Boost Your Workflow with ONLYOFFICE DocSpace & ChatGPT Synergy</u></a></li>
<li><a href="https://tech-revival.techidaily.com/breaking-the-sound-barrier-gpts-quintuple-ascent-to-fame/"><u>Breaking the Sound Barrier: GPT's Quintuple Ascent to Fame</u></a></li>
<li><a href="https://tech-revival.techidaily.com/challenges-with-using-chatgpt-as-a-dependable-text-summary-tool/"><u>Challenges with Using ChatGPT as a Dependable Text Summary Tool</u></a></li>
<li><a href="https://tech-revival.techidaily.com/changing-times-with-chatgpt-understanding-the-impact-of-immediate-data-access/"><u>Changing Times with ChatGPT: Understanding the Impact of Immediate Data Access</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-unveiled-for-parents-the-comprehensive-guide-to-generative-ai-explained/"><u>ChatGPT Unveiled for Parents: The Comprehensive Guide to Generative AI Explained</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-dialogues-separating-fact-from-fiction-in-ai-bot-world/"><u>Decoding Dialogues: Separating Fact From Fiction in AI Bot World</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dive-into-the-world-of-ai-learning-mastering-board-games-and-image-creation-with-my-gpt-assistant/"><u>Dive Into the World of AI Learning: Mastering Board Games & Image Creation with My GPT Assistant</u></a></li>
<li><a href="https://tech-revival.techidaily.com/efficient-time-use-with-chatgpts-4-techniques/"><u>Efficient Time Use with ChatGPT's 4 Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/essential-ai-tools-the-ultimate-list-of-8-must-have-apps-for-your-phone-android-and-iphone/"><u>Essential AI Tools: The Ultimate List of 8 Must-Have Apps for Your Phone (Android and iPhone)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/essential-overlooked-gpt-features-for-innovative-dialogue/"><u>Essential, Overlooked GPT Features for Innovative Dialogue</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-latency-leap-from-gpt-35-to-chatgpt-4/"><u>Exploring the Latency Leap: From GPT-3.5 to ChatGPT-4</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722191579859-get-started-with-openais-new-gpt-personalized-store-begin-using-immediately/"><u>Get Started with OpenAI's New GPT Personalized Store – Begin Using Immediately!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/google-enters-the-ai-arena-with-bard-a-cutting-edge-contender-against-the-reigning-champion-chatgpt/"><u>Google Enters the AI Arena with 'Bard', A Cutting-Edge Contender Against the Reigning Champion, ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722056013565-gpt-4-open-for-everyone-plus-still-boasts-6-exclusive-features/"><u>GPT-4: Open for Everyone! Plus Still Boasts 6 Exclusive Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harness-the-power-of-ai-enhancing-excel-workflows-using-chatgpt/"><u>Harness the Power of AI: Enhancing Excel Workflows Using ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-onlyoffice-docspace-uses-chatgpt-to-improve-your-productivity/"><u>How ONLYOFFICE DocSpace Uses ChatGPT to Improve Your Productivity</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-sony-xperia-10-v-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Sony Xperia 10 V For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-touch-screen-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-samsung-galaxy-m34-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Samsung Galaxy M34 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-asus-rog-phone-7-ultimate-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Asus ROG Phone 7 Ultimate Without PUK Codes</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ideal-chatgpt-queries-to-propel-crypto-trading/"><u>Ideal ChatGPT Queries to Propel Crypto Trading</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-locating-your-own-playlists-on-youtube/"><u>In 2024, Locating Your Own Playlists on Youtube</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-macos-with-chatgpt-a-step-by-step-guide/"><u>Mastering macOS with ChatGPT: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-the-art-of-crafting-a-compelling-cover-letter-with-chatgpt/"><u>Mastering the Art of Crafting a Compelling Cover Letter with ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-a-new-era-how-artificial-intelligence-is-reshaping-game-design-and-its-consequences-for-developers/"><u>Navigating a New Era: How Artificial Intelligence Is Reshaping Game Design and Its Consequences for Developers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-llm-choices-9-essential-pros-and-cons-for-informed-decision-making/"><u>Navigating LLM Choices: 9 Essential Pros & Cons for Informed Decision-Making</u></a></li>
<li><a href="https://tech-revival.techidaily.com/next-up-on-screen-let-chatgpt-help-you-choose/"><u>Next Up on Screen? Let ChatGPT Help You Choose!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/premiere-slideshows-to-cinema-files/"><u>Premiere Slideshows to Cinema Files</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ranking-the-least-expensive-yet-effective-ais-like-sora/"><u>Ranking the Least Expensive, Yet Effective AIs Like Sora</u></a></li>
<li><a href="https://tech-revival.techidaily.com/showdown-between-tech-leaders-can-llama-3-outshine-gpt-4/"><u>Showdown Between Tech Leaders: Can Llama 3 Outshine GPT-4?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/spotlight-on-current-fraudulent-activities-the-emergence-of-a-new-twittersite-hoax-and-metas-innovative-verified-status-plus-demystifying-chatgpt-version-4.36/"><u>Spotlight on Current Fraudulent Activities: The Emergence of a New Twittersite Hoax & Meta's Innovative Verified Status + Demystifying ChatGPT Version 4</u></a></li>
<li><a href="https://tech-revival.techidaily.com/tailored-talk-tech-enhancing-gpt-conversation-with-10-tweaks/"><u>Tailored Talk Tech: Enhancing GPT Conversation with 10 Tweaks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-dark-side-of-dating-bots-7-ways-artifice-intelligence-enhances-romance-frauds/"><u>The Dark Side of Dating Bots: 7 Ways Artifice Intelligence Enhances Romance Frauds</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-future-of-dev-workflow-with-ai/"><u>The Future of Dev Workflow with AI</u></a></li>
<li><a href="https://tech-revival.techidaily.com/thriving-amidst-automation-top-6-tips-to-excel-in-a-world-of-ai-and-robotics/"><u>Thriving Amidst Automation: Top 6 Tips to Excel in a World of AI and Robotics</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-4-strategies-for-enabling-chatgpt-to-interpret-pdf-files/"><u>Top 4 Strategies for Enabling ChatGPT to Interpret PDF Files</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transforming-physical-training-through-gpt-interaction/"><u>Transforming Physical Training Through GPT Interaction</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-a-superior-lifestyle-innovative-uses-of-chatgpt-for-personal-growth/"><u>Unlocking a Superior Lifestyle: Innovative Uses of ChatGPT for Personal Growth</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-5-main-motivations-for-companies-to-ban-chatgpt-access/"><u>Unveiling 5 Main Motivations for Companies to Ban ChatGPT Access</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
</ul></div>
