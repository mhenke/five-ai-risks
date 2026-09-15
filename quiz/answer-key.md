# Answer key

For the questions in [quiz.md](./quiz.md). Each entry gives the right option, why it matches the video, and why each wrong option fails.

## Question 1: shadow AI

Right option: "An employee using a personal account on a popular AI chatbot to help draft a confidential internal strategy document."

Why it fits: shadow AI is work done in tools IT never vetted or approved, and a personal account drafting a confidential doc is that exact case.

Why the rest fail: an IT-deployed firewall is IT-run even if nobody announced it. A board-authorized library went through approval, the opposite of shadow. A corporate-licensed tool summarizing public news is approved and handles low-risk material.

## Question 2: data leakage

Right option: "The input data may be used to train subsequent versions of the AI model, becoming part of its internal parameters."

Why it fits: vendor terms may let inputs flow into training, and once data is baked into model weights you cannot claw it back.

Why the rest fail: these tools do not encrypt your prompt with a key you cannot access. They do not store prompts on a blockchain. Prompts are not blasted to thousands of public servers; control is lost through the vendor's training pipeline.

## Question 3: hallucination laundering

Right option: "It occurs when a human presents AI-generated inaccuracies as their own verified work or fact."

Why it fits: laundering means falsehoods pass through personal credibility into formal deliverables, which is exactly what copying raw output into a work report does.

Why the rest fail: models do not intend to lie, so "intentionally lies" misstates how hallucinations happen. No encryption is involved. One model cleaning up another model's output is a different idea entirely.

## Question 4: why bans backfire

Right option: "Employees often find workarounds, leading to a loss of visibility for the IT department into what tools are being used."

Why it fits: bans push people to personal devices or unblocked tools, so the same risk continues with zero IT visibility.

Why the rest fail: models do not single out an organization for extraction because it banned tools. AI is not built into hardware at the BIOS level. No IBM reporting rule is triggered by a ban.

## Question 5: indirect prompt injection

Right option: "The malicious instructions are hidden within data or documents that the AI retrieves and processes."

Why it fits: nobody types anything suspicious; the attack rides in through an email, document, or page the AI reads as part of its context.

Why the rest fail: touching training weights is model tampering, not prompt injection. Slow corruption from typing is not the defining trait. A physical data-center breach is a different crime.

## Question 6: zombie AI agent

Right option: "An unmonitored AI agent that remains active and authenticated after its specific project or purpose has ended."

Why it fits: leftover API keys and access become a backdoor nobody watches, which is the whole zombie problem.

Why the rest fail: output continuing after training data is deleted is nonsense. A virus-spreading agent describes malware. Ignoring all human commands describes rogue behavior, not an abandoned running agent.

## Question 7: agentic AI

Right option: "The ability to read and write to databases and execute code autonomously."

Why it fits: agents act on outside systems without a human in the loop, while a standard chatbot answers inside the chat window.

Why the rest fail: human-like text is something both do. Approving every word is the opposite of agentic. Next-word prediction describes both.

## Question 8: the sixth way

Right option: "Falling behind the curve by refusing to use AI at all."

Why it fits: the video's too-cute sixth point is that abstaining leaves you behind while everyone else moves on.

Why the rest fail: deepfake verification, emotional-support overuse, and automating HR firings never appear as the sixth point.

## Question 9: accountability

Right option: "The individual who submitted and presented the content as fact."

Why it fits: the name on the document owns the error, whether the error started with a model or not.

Why the rest fail: the developers built the model but did not sign the filing. IT may share governance blame, but the submission decision belonged to the employee. Nothing in the video supports treating AI errors as acts of nature.

## Question 10: system prompt

Right option: "It provides the 'rules of the road' or internal instructions that dictate how the AI should behave."

Why it fits: the system prompt tells the chatbot what to do and what to refuse, which is what an attacker tries to override.

Why the rest fail: it is not a network firewall. It is not hardware. It is not a login key.
