Data poisoning risk for AI
Last updated: Dec 12, 2024
Risks associated with input
Training and tuning phase
Robustness
Traditional AI risk
Description
A type of adversarial attack where an adversary or malicious insider injects intentionally corrupted, false, misleading, or incorrect samples into the training or fine-tuning datasets.

Why is data poisoning a concern for foundation models?
Poisoning data can make the model sensitive to a malicious data pattern and produce the adversary’s desired output. It can create a security risk where adversaries can force model behavior for their own benefit.

Background image for risks associated with input
Example
Low-resource Poisoning of Data

As per the source article, a group of researchers found that with very limited resources anyone can add malicious data to a small number of web pages whose content is usually collected for AI training (e.g, Wikipedia pages), enough to cause a large language model to generate incorrect answers.

Sources:

Business Insider, March 2024

Background image for risks associated with input
Example
Image Modification Tool

As per the source article, the researchers have developed a tool called “Nightshade” that modifies images in a way that damages computer vision but remains invisible to humans. When such “poisoned” modified images are used to train AI models, the models may generate unpredictable and unintended results. The tool was created as a mechanism to protect intellectual property from unauthorized image scraping but the article also highlights that users could abuse the tool and intentionally upload “poisoned” images.

Sources:

The Conversation, December 2023

Parent topic: AI risk atlas

We provide examples covered by the press to help explain many of the foundation models' risks. Many of these events covered by the press are either still evolving or have been resolved, and referencing them can help the reader understand the potential risks and work towards mitigations. Highlighting these examples are for illustrative purposes only.
