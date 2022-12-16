<!--

-->
# Why ChatGPT won't scale: The AI Tax

> If you wish to make an apple pie from scratch, you must first invent the universe - Carl Sagan

[ChatGPT](https://www.theverge.com/23488017/openai-chatbot-chatgpt-ai-examples-web-demo) has quickly garnered a lot of attention, and deservedly so. As a tech demo for large language models, it is really impressive. You can ask it pretty much anything and it'll give you an answer. The answers aren't 'correct', but it is very confident about its answer.

This, of course, has spurred a lot of interesting demos that have ChatGPT or similar models. There are definitely some people who see this as part of an immenient future. But while these demos are really neat, it's important to temper expectations and consider alternatives.

https://twitter.com/m1guelpf/status/1603018284282138634

This one developer came up with a command-line autocomplete that uses GPT-3 and a large corpus of knowledge on esoteric command line arguments to figure out the right flags to use to accomplish your task.

I don't want to take away from what Miguel came up with, but it's definitely an example of a cool demo that won't scale.

## Design

If I ever start my own company one day, a designer is going to be one of my first hires. Design extends beyond just the look of the button or even where the button is placed: it's about understanding the user requirements and creating a workflow that works well for that. It's certainly not easy, and it does require a lot of trade-offs.

At the same time, design is a key component of a product. A user shouldn't be expected to read the entire command-line manual to be able to start modifying videos. In this regard, FFMPEG is probably in need of a better design.

As I said, design can extend to [command-line tools](https://clig.dev/) even if FFMPEG doesn't want to add a graphical user interface. Unix does have a lot of weird commands and weirder flags that are just there for legacy reasons.

But why can't we just sent queries to the cloud and get responses back? It's expensive in multiple ways. It can take time to generate the command. It requires a lot of computing power

<!--
- Objective
- Resemble.ai
- Design
- Humor
- Pendragon & Sci-Fi
- Work hackathon
- Tiny offline models
-->
