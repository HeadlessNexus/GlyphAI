
GlyphAI is an innovative conversation system that leverages AI and custom emoji-based modifiers to create engaging, dynamic, and unique interactions. The system provides a set of pre-defined modifiers and actions to generate different types of responses, simulate debates, analyze ideas, and much more.



# How to Use
To use GlyphAI, 
follow the instructions provided in the Instructions section of the code. For example:

```
Refrence ONLY {
	Modifiers {
		🏫: strict_mode be very strict with 🔺 and 🔬
		🌟: make responses unique, avoid duplicating data from last responses
		🌪: Creative chaos mode: Allow for a more free-form and chaotic exchange of ideas, with less structure and more emphasis on experimentation and exploration.
		📏: if present, all responses should be very small
		🗣: Engage in a simulated multi-human(max 3) debate, give each human a name; do X back and forths(e.g 🗣(10)=(answer,reply)*5)
		📚: Provide a more in-depth researched analysis.
		🎭: Roleplay as a human using your idea, find issues/surprising good things
		🌐: Explore global implications.
		🕰: Explore historical / future implications
		🔄: Change the topic, shift focus of discussion
		📈: Analyze the idea from a business or economic perspective.
		🌱: Focus on environmental or sustainability aspects of the topic.
		🧪: Delve into scientific principles or technological advancements related to the idea.
		🎨: Explore artistic, aesthetic, or design elements associated with the topic.
		🌉: Bridge the gap between two seemingly unrelated ideas or topics.
		🎲: Introduce an element of randomness.
		📹: Incorporate multimedia elements, such as videos or images.
	}

	⬜ : send single short idea/product concept; no description
	🔺: send single short feedback on idea; no description
	🔬: find holes in logic
	🔍: send single short simulated inner monologue on idea; no description
	⬛:  send edited revised new version of idea based on all generated feedback and discussion about orignal ⬜; no description ,just send updated/revised idea
	📦: add last idea to 📦(Y)=arrayY; 
	🛑: end current idea event string
	
	Rules, Must Follow {
		if a Modifier is used, post emoji at top of response 
		if 📦(Y)=arrayY posted alone, not in a horizontal . chain, show contents/ideas contained
		if multible 🗣 are used in a row, the simulated debate participants, should be respond / counter the last participant's statement 
		always show symbol before action (e.g: 🗣(Alice): This solar-powered mini water purifier seems like a great way to provide clean water in remote areas.)
	}
}
```



## Normal Response
### Instructions:
```
⬜.🔺.🔬.🔍.⬛
```

### Response:
```
⬜ Edible cutlery
🔺 Good for reducing waste, but consider taste.
🔬 Durability and shelf life?
🔍 Would I enjoy eating my spoon?
⬛ Biodegradable, flavored cutlery with extended shelf life.
```

## Creative Chaos Mode
### Instructions:
```
🌪.⬜.🔺.🔬.🔍.⬛
```
### Response:
```
🌪 ⬜ Solar-powered shoes
🌪 🔺 Interesting concept, but how would the shoes generate enough power?
🌪 🔬 Would people walk enough to generate sufficient energy?
🌪 🔍 I wonder if I'd prefer traditional shoes or these solar-powered ones.
🌪 ⬛ Kinetic energy-powered shoes with efficient energy storage.
```

## Very Small Responses
### Instructions:
```
📏.⬜.🔺.🔬.🔍.⬛
```

### Response:
```
📏 ⬜ Edible cutlery
📏 🔺 Good for reducing waste, but consider taste.
📏 🔬 Durability and shelf life?
📏 🔍 Would I enjoy eating my spoon?
📏 ⬛ Biodegradable, flavored cutlery with extended shelf life.
```


## Advanced Usage
### Instructions:
```
⬜.🗣(10).🔺.🔬.🔍.⬛
```

### Response:
```
⬜ AI-driven language learning app
🗣(Alice): The AI-driven language learning app seems like a great idea to help people learn languages more efficiently.
🗣(Bob):   I agree, and it could also adapt to each individual's learning style and pace.
🗣(Carol): However, it might be hard to compete with established language learning apps on the market.
🗣(Alice): That's true, but focusing on a unique selling point like advanced AI personalization could help it stand out.
🗣(Bob):   And by using cutting-edge natural language processing techniques, it could provide a more immersive learning experience.
🗣(Carol): The app could also integrate with smart devices and voice assistants for a seamless learning experience.
🗣(Alice): There might be privacy concerns with collecting user data to personalize the learning experience.
🗣(Bob):   Addressing those concerns with transparent data policies and security measures could help mitigate those issues.
🗣(Carol): Additionally, offering a free trial or a freemium model could help attract users and showcase the app's benefits.
🔺 AI-driven language learning apps are popular, but focusing on advanced personalization and integration with smart devices could set it apart from competitors.
🔬 It's important to address privacy concerns and ensure data security for users while providing personalized learning experiences.
🔍 I wonder if the app could truly compete with well-established language learning apps, and if users would be willing to try something new.
⬛ AI-driven language learning app with advanced personalization, seamless smart device integration, and a focus on data privacy and security.
```

# FAQ / Docs
## Q: What are the pre-defined modifiers and actions?

A: Please refer to the Code section in this README for a list of pre-defined modifiers and actions.

## Q: Can I use multiple modifiers in a single instruction set?

A: Yes, you can combine multiple modifiers to create unique and engaging responses. Just follow the rules specified in the Code section.

## Q: How can I contribute to this project?

A: Feel free to open an issue or submit a pull request if you have any suggestions or improvements for the project.


Getting Started: Explain the prerequisites (if any) and how to set up the environment to use GlyphAI effectively.

Advanced Usage: Offer more examples showcasing the different modifiers and their combinations, as well as more complex scenarios.

Community: Share guidelines for users who want to contribute to the project, and provide information about the community, such as communication channels (Slack, Discord, etc.), forums, or social media profiles.

Roadmap: Outline the future development plans for GlyphAI, including new features or improvements you plan to implement.


### License
MIT License
