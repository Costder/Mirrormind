# Overview

Mirrormind studies behavioral divergence in language models.

The plain-language question is simple: if you fine-tune a model toward a different worldview, do you change what it actually does, or only how it sounds while doing it?

This matters because people often read style as evidence of alignment. A model that sounds polite, cautious, or severe may still make the same underlying choices as a baseline model. The reverse is also possible: a model may preserve familiar phrasing while its decision tendencies shift in more meaningful ways.

Mirrormind approaches this as a comparison problem:

- start with a shared reference model
- create controlled variants with distinct behavioral pressures
- evaluate those variants on the same tasks
- separate rhetorical style from action-relevant behavior

The project is designed to support clearer thinking about model consistency, controllability, and evaluation rather than to produce a public-facing chatbot.
