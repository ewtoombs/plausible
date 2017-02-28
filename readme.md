# plausible

It mimics text vaguely resembling some training text, optimising for hilariousness. *Still in planning stages.*

There will be two modes of operation: causal and random. In random mode, plausible will just generate random text written in the same style as its training text. Only the text being imitated will be required for training.

In causal mode, pieces of the text being imitated will be paired with context text from a different source, assuming a causal link between the second source and the text being imitated. Consider for example a certain upstart orange-haired fellow living in the fabled land south of canada. Sample as many of his tweets as possible, along with those of the news outlets his tweets are known to be informed by and train plausible with these tweets. When the training is complete, you'll be able to input a sample news-related tweet and expect to see some hilarious responses!
