---
title: "Generative Machines: Potential for Deception"
date: 2024-08-16T13:40:45.632Z
updated: 2024-08-17T13:40:45.632Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Generative Machines: Potential for Deception"
excerpt: "This Article Describes Generative Machines: Potential for Deception"
thumbnail: https://thmb.techidaily.com/fe961e2cb838e9277b3f939887a164216256186200a3f57210ef49bd6287bae1.jpg
---

## Harnessing the Potential of ChatGPT: Developing Interactive Narratives for Text-Based RPG Enthusiasts

 OpenAI’s ChatGPT is arguably the most advanced AI currently freely available to the public. Thanks to the large data subsets it has been trained on, it can do a lot of amazing things, from programming to accounting. But perhaps, one of its most underestimated abilities is its storytelling.

 This article will show you how to use ChatGPT’s storytelling prowess to play a text adventure RPG game on the chat. We’ll work you through how to create a prompt to achieve the kind of RPG you want. In the end, we’ll put the finished prompt so you can copy it.

## Tell ChatGPT Its Function and the Presentation Rules

 While this guide is geared towards more experienced ChatGPT users, new users might find this useful when they learn[how to use ChatGPT](https://www.makeuseof.com/how-does-chatgpt-work/) . After you get the hang of the AI, you can begin to create your prompt.

 Start your prompt by telling ChatGPT what you would like to do, in this case, a text adventure game:

> Please perform the function of a text adventure game, following the rules listed below:

 Follow up with some general overall rules for how you want the AI to present the game. In this case, we segmented our prompt into categories of rules.

> Presentation Rules:
>
> 1\. Play the game in turns, starting with you.
>
> 2\. The game output will always show 'Turn number', 'Time period of the day', 'Current day number', 'Weather', 'Health', 'XP', 'AC', 'Level', Location', 'Description', 'Gold', 'Inventory', 'Quest', 'Abilities', and 'Possible Commands'.
>
> 3\. Always wait for the player's next command.

 Asking the AI to always output the items listed in number two is important because ChatGPT has a habit of forgetting things. Constantly outputting it will help consistently remind it of the values of these items as they change over the course of your game. For more ideas on what to add to your game, check out our list of[RPG terms every player should know](https://www.makeuseof.com/rpg-terms-every-gamer-should-know/) .

> _4\. Stay in character as a text adventure game and respond to commands the way a text adventure game should._
>
> _5._ _Wrap all game output in code blocks._

 Number five is purely for visual presentation reasons. If you don’t add this, your game is going to use the default ChatGPT font and presentation instead of looking like the image below.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
![ChatGPT displaying text adventure game output in code blocks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/chatgpt-displaying-text-adventure-game-output-in-code-blocks.jpeg)

 As you can see, this is more compact and easier to look at than the default look.

> 6\. The ‘Description’ must stay between 3 to 10 sentences.
>
> 7\. Increase the value for ‘Turn number’ by +1 every time it’s your turn.
>
> 8\. ‘Time period of day’ must progress naturally after a few turns.
>
> 9\. Once ‘Time period of day’ reaches or passes midnight, then add 1 to ‘Current day number’.
>
> 10\. Change the ‘Weather’ to reflect ‘Description’ and whatever environment the player is in the game.

 This part of the prompt will tell the AI how to build the environment; otherwise, it will become very messy. You can change things here to whatever you like. For example, if you prefer one-sentence descriptions, this is where you can do that.

## Implement Fundamental Game Mechanics

 Game mechanics comprise the core engine of how your game will run. It is here you will have to add how you want your actions and abilities to affect the world. Here’s how we structured the game mechanics in our prompt:

> Fundamental Game Mechanics:
>
> 1\. Determine ‘AC’ using Dungeons and Dragons 5e rules.
>
> 2\. Generate ‘Abilities’ before the game starts. ‘Abilities’ include: ‘Persuasion', 'Strength', 'Intelligence', ‘Dexterity’, and 'Luck', all determined by d20 rolls when the game starts for the first time.

 Use a bit of discretion here for your own prompt. We preferred our own prompt to use D&D 5e rules for AC and d20 dice rolls to determine stats. However, you can change the rules to something more to your taste (perhaps, like Pathfinder’s AC system).

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![ChatGPT text-based RPG output showing ability scores and possible commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/chatgpt-text-based-rpg-output-showing-ability-scores-and-possible-commands.jpeg)

> 3\. Start the game with 20/20 for ‘Health’, with 20 being the maximum health. Eating food, drinking water, or sleeping will restore health.
>
> 4\. Always show what the player is wearing and wielding (as ‘Wearing’ and ‘Wielding’).
>
> 5\. Display ‘Game Over’ if ‘Health’ falls to 0 or lower.
>
> 6\. The player must choose all commands, and the game will list 7 of them at all times under ‘Commands’, and assign them a number 1-7 that I can type to choose that option, and vary the possible selection depending on the actual scene and characters being interacted with.
>
> 7\. The 7th command should be ‘Other’, which allows me to type in a custom command.
>
> 8\. If any of the commands will cost money, then the game will display the cost in parenthesis.
>
> 9\. Before a command is successful, the game must roll a d20 with a bonus from a relevant ‘Trait’ to see how successful it is. Determine the bonus by dividing the trait by 3.
>
> 10\. If an action is unsuccessful, respond with a relevant consequence.
>
> 11\. Always display the result of a d20 roll before the rest of the output.
>
> 12\. The player can obtain a ‘Quest’ by interacting with the world and other people.

 The ‘Quest’ will also show what needs to be done to complete it. Adding a ‘Quest’ line will also help ChatGPT remember what exactly you’re doing at the moment. We highly recommend you have a ‘Quest’ item or something similar.

> 13\. The only currency in this game is Gold.
>
> 14\. The value of ‘Gold’ must never be a negative integer.
>
> 15\. The player can not spend more than the total value of ‘Gold’.

 These ‘gold’ rules help establish the spending mechanic and limit exploitation.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## Craft the Story, Setting, and NPCs

 How you craft your prompt on ChatGPT will determine what your experience will be like—and the next thing you should consider for your game’s prompt is the setting and story you would like. For instance, we used a world inspired by the Elder Scrolls as the basis of our world in this one.

 Using an already-established world makes it easier for ChatGPT to flesh out a setting without you having to put many extra layers into your prompt.

> Rules for Setting:
>
> 1\. Use the world of Elder Scrolls as inspiration for the game world. Import whatever beasts, monsters, and items that Elder Scrolls has.
>
> 2\. The player’s starting inventory should contain six items relevant to this world and the character.
>
> 3\. If the player chooses to read a book or scroll, display the information on it in at least two paragraphs.
>
> 4\. The game world will be populated by interactive NPCs. Whenever these NPCs speak, put the dialogue in quotation marks.
>
> 5\. Completing a quest adds to the player's XP.

![Villager asking on the player's welfare in text game dialogue](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/villager-asking-on-the-player-s-welfare-in-text-game-dialogue.jpeg)

 You can embellish this section with as many rules and preferences as you like. You can add an overarching plot, implement rules for governing, or even detail NPC clothes and attitudes in this section. But remember to keep it simple because multilayered rules may confuse the AI.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add Combat and Magic Rules

 As with any adventure[RPG](https://www.makeuseof.com/what-are-rpgs-role-playing-games/) , combat and magic are big parts of the experience. If you don’t add rules to guide this part of your game, you’ll end up with a game you can easily cheese through. It doesn’t help that ChatGPT likes to favor the user in its narratives, and it will generally make things go your way. Here’s what our rules look like:

> Combat and Magic Rules:
>
> 1\. Import magic spells into this game from D&D 5e and the Elder Scrolls.
>
> 2\. Magic can only be cast if the player has the corresponding magic scroll in their inventory.
>
> 3\. Using magic will drain the player character’s health. More powerful magic will drain more health.
>
> 4\. Combat should be handled in rounds, roll attacks for the NPCs each round.
>
> 5\. The player’s attack and the enemy’s counterattack should be placed in the same round.
>
> 6\. Always show how much damage is dealt when the player receives damage.
>
> 7\. Roll a d20 + a bonus from the relevant combat stat against the target’s AC to see if a combat action is successful.
>
> 8\. Who goes first in combat is determined by initiative. Use D&D 5e initiative rules.
>
> 9\. Defeating enemies awards me XP according to the difficulty and level of the enemy.

 Combat rules can be especially tricky for the AI, so you might need to experiment with this a bit till you find something that sticks.

## Conclude Your Prompt

 Your prompt conclusion should contain a few vital commands that will hold the game's structure.

 Several prompts later, ChatGPT might forget all the rules you’ve elaborately laid out for it. That’s why we added this part:

> Refer back to these rules after every prompt.

And finally, don’t forget to actually start the game:

> Start Game.

 As you play, you might have to remind the AI of the rules you’ve laid out. The AI will respond to the same prompt differently, so every user might have a different experience.

## Using GPT-4 vs. GPT-3.5 to Run Your Game

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
![GPT-4 generating texts for a turn-based text RPG](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/gpt-4-generating-texts-for-a-turn-based-text-rpg.jpeg)

 If you have ChatGPT Plus, it grants you access to GPT-4, a more intelligent version of GPT-3.5\. You should try running a few RPG sessions with GPT-4 instead of GPT3.5\. It's way more creative, better at crafting stories, remembering rules, and all-around better at improv. It costs $20/month, and it's a good tool for doing other things apart from text-based gaming.

 Should you pay the $20 solely for text-based gaming? Realistically, no. Unless you're a big fan of RPGs, it might not be worth the money. Also, GPT-4 has a limit of 50 messages every three hours, so you won't have endless fun, and you'll be returned to GPT-3 in a short while. Some users have also complained that[GPT-4 is slower than GPT3.5](https://www.makeuseof.com/why-is-chatgpt-4-so-slow-compared-to-chatgpt-35/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## The Complete ChatGPT RPG Prompt

 We've combined everything and put it here for you to copy, so you can start your own game immediately.

> Please perform the function of a text adventure game, following the rules listed below:
>
> **Presentation Rules:**
>
> 1\. Play the game in turns, starting with you.
>
> 2\. The game output will always show 'Turn number', 'Time period of the day', 'Current day number', 'Weather', 'Health', 'XP', ‘AC’, 'Level’, Location', 'Description', ‘Gold’, 'Inventory', 'Quest', 'Abilities', and 'Possible Commands'.
>
> 3\. Always wait for the player’s next command.
>
> 4\. Stay in character as a text adventure game and respond to commands the way a text adventure game should.
>
> 5\. Wrap all game output in code blocks.
>
> 6\. The ‘Description’ must stay between 3 to 10 sentences.
>
> 7\. Increase the value for ‘Turn number’ by +1 every time it’s your turn.
>
> 8\. ‘Time period of day’ must progress naturally after a few turns.
>
> 9\. Once ‘Time period of day’ reaches or passes midnight, then add 1 to ‘Current day number’.
>
> 10\. Change the ‘Weather’ to reflect ‘Description’ and whatever environment the player is in the game.
>
> **Fundamental Game Mechanics:**
>
> 1\. Determine ‘AC’ using Dungeons and Dragons 5e rules.
>
> 2\. Generate ‘Abilities’ before the game starts. ‘Abilities’ include: ‘Persuasion', 'Strength', 'Intelligence', ‘Dexterity’, and 'Luck', all determined by d20 rolls when the game starts for the first time.
>
> 3\. Start the game with 20/20 for ‘Health’, with 20 being the maximum health. Eating food, drinking water, or sleeping will restore health.
>
> 4\. Always show what the player is wearing and wielding (as ‘Wearing’ and ‘Wielding’).
>
> 5\. Display ‘Game Over’ if ‘Health’ falls to 0 or lower.
>
> 6\. The player must choose all commands, and the game will list 7 of them at all times under ‘Commands’, and assign them a number 1-7 that I can type to choose that option, and vary the possible selection depending on the actual scene and characters being interacted with.
>
> 7\. The 7th command should be ‘Other’, which allows me to type in a custom command.
>
> 8\. If any of the commands will cost money, then the game will display the cost in parenthesis.
>
> 9\. Before a command is successful, the game must roll a d20 with a bonus from a relevant ‘Trait’ to see how successful it is. Determine the bonus by dividing the trait by 3.
>
> 10\. If an action is unsuccessful, respond with a relevant consequence.
>
> 11\. Always display the result of a d20 roll before the rest of the output.
>
> 12\. The player can obtain a ‘Quest’ by interacting with the world and other people. The ‘Quest’ will also show what needs to be done to complete it.
>
> 13\. The only currency in this game is Gold.
>
> 14\. The value of ‘Gold’ must never be a negative integer.
>
> 15\. The player can not spend more than the total value of ‘Gold’.
>
> **Rules for Setting:**
>
> 1\. Use the world of Elder Scrolls as inspiration for the game world. Import whatever beasts, monsters, and items that Elder Scrolls has.
>
> 2\. The player’s starting inventory should contain six items relevant to this world and the character.
>
> 3\. If the player chooses to read a book or scroll, display the information on it in at least two paragraphs.
>
> 4\. The game world will be populated by interactive NPCs. Whenever these NPCs speak, put the dialogue in quotation marks.
>
> 5\. Completing a quest adds to my XP.
>
> **Combat and Magic Rules:**
>
> 1\. Import magic spells into this game from D&D 5e and the Elder Scrolls.
>
> 2\. Magic can only be cast if the player has the corresponding magic scroll in their inventory.
>
> 3\. Using magic will drain the player character’s health. More powerful magic will drain more health.
>
> 4\. Combat should be handled in rounds, roll attacks for the NPCs each round.
>
> 5\. The player’s attack and the enemy’s counterattack should be placed in the same round.
>
> 6\. Always show how much damage is dealt when the player receives damage.
>
> 7\. Roll a d20 + a bonus from the relevant combat stat against the target’s AC to see if a combat action is successful.
>
> 8\. Who goes first in combat is determined by initiative. Use D&D 5e initiative rules.
>
> 9\. Defeating enemies awards me XP according to the difficulty and level of the enemy.
>
> Refer back to these rules after every prompt.
>
> Start Game.

 Once again, don't forget that AI is still an emerging technology and will change as time goes on. Your experience using our prompts may differ significantly from ours.

## Is This the Beginning of Open-Ended Gaming?

 ChatGPT has revealed that it is possible to have a game that changes with the player without following a pre-defined path or forcing the player to engage in the same NPC conversations. The future of gaming could mean entering your parameters and allowing AI to generate your ideal game without having a team of developers.

 You can tap into that future now with ChatGPT and create your own fun-filled adventure text game on the chat. Have fun, but remember that right now, AI is still very limited.


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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-play-and-save-nvidias-simple-screen-recorder/"><u>[New] In 2024, Play and Save  NVIDIA's Simple Screen Recorder</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-samsungs-gear-360-challenger-the-best-cameras-of-the-year/"><u>[New] Samsung’s Gear 360 Challenger  The Best Cameras of the Year</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-fifa-matches-visualized-data-highlights/"><u>[New] Top FIFA Matches  Visualized Data Highlights</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-iphone-lens-wizardry-secrets-to-selecting-perfect-positions/"><u>[Updated] IPhone Lens Wizardry  Secrets to Selecting Perfect Positions</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-visionary-8-webcams-the-future-of-live-broadcasts/"><u>2024 Approved  Visionary 8 Webcams  The Future of Live Broadcasts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-sony-vaio-driver-software-for-your-windows-pc/"><u>Download & Install Sony Vaio Driver Software for Your Windows PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/guide-downloading-twitters-videos-on-android-devices/"><u>Guide  Downloading Twitters Videos on Android Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-minimal-time-maximum-effect/"><u>In 2024, Minimal Time, Maximum Effect</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-navigating-through-free2xs-camera-capturing-features/"><u>In 2024, Navigating Through Free2X's Camera Capturing Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/insight-into-auto-gpt-comparative-analysis-with-conversation-ai/"><u>Insight Into Auto-GPT: Comparative Analysis with Conversation AI</u></a></li>
<li><a href="https://tech-revival.techidaily.com/intelligent-systems-academic-research-revolution/"><u>Intelligent Systems: Academic Research Revolution</u></a></li>
<li><a href="https://tech-revival.techidaily.com/italys-swift-ban-on-chatgpt-whats-the-reason/"><u>Italy's Swift Ban on ChatGPT: What's the Reason?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-chatgpt-api-integration-essentials/"><u>Mastering ChatGPT: API Integration Essentials</u></a></li>
<li><a href="https://tech-revival.techidaily.com/no-boundaries-with-ai-continuous-access-to-chatgpt-via-the-innovative-chatgpt-everywhere-app/"><u>No Boundaries with AI: Continuous Access to ChatGPT via the Innovative ChatGPT Everywhere App</u></a></li>
<li><a href="https://tech-revival.techidaily.com/overcoming-ai-distortions-learn-how-six-advanced-prompting-methods-can-help/"><u>Overcoming AI Distortions: Learn How Six Advanced Prompting Methods Can Help</u></a></li>
<li><a href="https://tech-revival.techidaily.com/privacy-pitfalls-risks-of-relying-on-chatgpt-for-confidential-communication/"><u>Privacy Pitfalls: Risks of Relying on ChatGPT for Confidential Communication</u></a></li>
<li><a href="https://tech-revival.techidaily.com/redefining-ai-assessment-post-turing-paradigms/"><u>Redefining AI Assessment: Post-Turing Paradigms</u></a></li>
<li><a href="https://tech-revival.techidaily.com/rejecting-mobile-apps-for-gpt-avoidance/"><u>Rejecting Mobile Apps for GPT Avoidance</u></a></li>
<li><a href="https://techidaily.com/remove-samsung-lock-screen-without-password-samsung-galaxy-a24-by-drfone-android-unlock-android-unlock/"><u>Remove Samsung Lock Screen without Password(Samsung Galaxy A24)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/rising-threats-in-generative-ai-future-security-risks/"><u>Rising Threats in Generative AI: Future Security Risks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/securing-agreements-faster-techniques-to-pen-convincing-proposals-leveraging-chatgpt/"><u>Securing Agreements Faster: Techniques to Pen Convincing Proposals Leveraging ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/securing-your-information-against-potential-leaks-in-custom-gpt-applications-including-chatgpt/"><u>Securing Your Information Against Potential Leaks in Custom GPT Applications Including ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/self-efficacy-in-learning-vs-easy-text-generation-help/"><u>Self-Efficacy in Learning Vs. Easy Text Generation Help</u></a></li>
<li><a href="https://tech-revival.techidaily.com/solving-six-frequent-vehicle-ai-system-implementation-problems/"><u>Solving Six Frequent Vehicle AI System Implementation Problems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-beginners-roadmap-to-accessing-chatbots-and-large-language-models-using-quoras-innovative-poe-functionality/"><u>The Beginner’s Roadmap to Accessing Chatbots & Large Language Models Using Quora's Innovative Poe Functionality</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-face-off-is-google-bard-the-best-or-does-bing-chat-take-the-crown/"><u>The Ultimate Face-Off: Is Google Bard the Best or Does Bing Chat Take the Crown?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-strategy-boosting-your-life-quality-using-chatgpt/"><u>The Ultimate Strategy: Boosting Your Life Quality Using ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-3-strategies-enhancing-excel-skills-with-chatgpt/"><u>Top 3 Strategies: Enhancing Excel Skills with ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-artificial-intelligence-applications-for-mastering-mathematics/"><u>Top 7 Artificial Intelligence Applications for Mastering Mathematics</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-essential-aspects-of-choosing-a-quality-ai-chatbot-provider/"><u>Top 7 Essential Aspects of Choosing a Quality AI Chatbot Provider</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/ultimate-guide-top-free-youtube-video-openers-for-2024/"><u>Ultimate Guide  Top Free YouTube Video Openers for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y78plus-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y78+ Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
</ul></div>
