<!--
Also: Bird SQL: https://twitter.com/perplexity_ai/status/1603441221753372673
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

But why can't we just sent queries to the cloud and get responses back? It's expensive in multiple ways. It can take time to generate the command. It requires a lot of computing power and a lot of electricity to do even trivial tasks like mute a video. And these systems are also not free at scale.

[Pricing for GPT-3](https://openai.com/api/pricing/) is at most $0.02 per thousand words. That's a rough estimate, and it doesn't include add-ons like custom models. For examples like the **plz** command-line tool, you can reach a thousand words fairly quickly. Two cents isn't a lot, but it quickly adds up for a commercial product. A hundred users could cost $2/day, or roughly $60/month.

I have been playing around with AI-generated voices through [Resemble.ai](https://www.resemble.ai/pricing/) and the pricing similar does not scale. At $0.36 a minute, a business built on this would quickly need to monetize.

This is why I say it won't scale. Good engineering design is meant to limit costs. Do you really need to build an entire new universe just to bake some apples? Do you need to run a ton of GPUs on a massive language model just to get a command-line flag? There are more efficient ways to solve this problem.

<!-- TODO Add screenshot -->

It's also not good at objective facts. Things like the World Cup sports don't require a large language model to get the score. I just need to go to a website. That's a more efficient solution to the objective. I think we'll quickly find that just throwing tons of compute power at a problem is the worst solution to a number of problems.

## Where do LLMs work?

https://twitter.com/HandNF/status/1600857982819966976

I don't want to deride the technology entirely. It just needs to find areas where it can excel.

> “I know it’s hard for you guys to understand,” he began. “But the capacity of our data systems is incredible. What we’ve been doing here with Abe Lincoln and theHindenburgdoesn’t even scratch the surface.”
> “Yeah, it’s all pretty cool,” I said. “But you can’t predict the future.”
> Patrick smiled and said, “Well, in a way, we can.”

In [The Never War](https://en.wikipedia.org/wiki/The_Never_War), part of the Pendragon series, the protagonist finds a large, powerful computer that is able to use its understanding about the world to create an alternate history in which the Hindenburg doesn't crash. This kind of large inference makes sense, as this kind of requirement cannot be solved with something simpler.

https://twitter.com/HandNF/status/1602141744988131329

Other places where large language models make sense is for processing and generating text. If the input has to be in an unstructured format, a complex model will be needed to process it. In cases where the input can be consolidated into a simple data structure, it's definitely overkill.

## Where ChatGPT won't make a difference

I've seen a lot of speculation about how AI will take over jobs or create some runaway effect, but I just don't see it. In a lot of situations, it's just going to moderately raise the bar of existing things but not change them.

Consider call centers. A voice model is $0.36 per minute, or $22 an hour. Tying that in with speech-to-text and other AI technology, you're probably able to deliver the software for a relatively high expense. A human employee can still be cheaper than linking together a lot of these systems. Sure, costs will go down and quality will go up, but I'm not expecting that to happen in the near future.

Consider spam or misinformation. While ChatGPT can create a message with a lot of high-quality fluff, quality was not a limiting factor. Spam [is intentionally riddled with errors](https://josephsteinberg.com/why-scammers-make-spelling-and-grammar-mistakes/). Misinformation was not being held back by quality. If people are supcetible, they'll believe things [that are completely fabricated](https://www.snopes.com/tag/joe-biden/) if it reinforces their beliefs. A ten-paragraph 'scoop' is a waste of time if you can just put a lie on a meme and share it.

And you don't need a large language model to trick people into believing something is real. A much simpler tool called [SciGen](https://en.wikipedia.org/wiki/SCIgen) generated a fake paper that was accepted in an academic conference in 2005.

Sure, maybe things are going to be a bit tougher to detect today, but let's not say that humans are great at discerning scams today.

<!-- Call centers. Spam. IEEE -->

## Towards the future

I participated in a hackathon at work this week and a lot of the projects dealt with AI in some way. It's clear that is a great tool that allows to accomplish a lot of tasks that once were hard and expensive.

It's also clear that tasks that can be completed by AI do not need to be completed by AI. Better design, documentation, and software can accomplish tasks in ways that are efficient in many regards.

What does the future look like? Perhaps rather than needing a massive language model like GPT-3, you'll be able to have tiny models that can run directly in the operating system or within a given program. That way you can just ask your computer how to mute a video and it'll be able to do that with a single GPU entirely offline. It'll be a lot faster and work better in specific use-cases.

This sounds almost like [app actions](https://developers.google.com/assistant/app), but might work even better in complex desktop applications.

Either way, I'm excited to see what demos are created next.

<!-- Workplace hackathon, tiny models -->

<!--
- Objective
- Resemble.ai
- Design
- Humor
- Pendragon & Sci-Fi
- Work hackathon
- Tiny offline models
- Resemble v call centers
-->
