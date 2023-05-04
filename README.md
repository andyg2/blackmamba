# BlackMamba POC

## Reconstructed BlackMamba POC code from fragments found on the internet

Python is not my primary programming language and I don't have a ChatGPT key or shitty MS Teams so it probably contains more than a couple of bugs.

I added a concept of permuting the initial prompt as that just seemed to make sense.

I also modified the main loop to continue generating new code until some keystrokes are logged. This isn't if the computer in unattened as this will probably get the chatGPT api key/account banned. There's a 1 minute delay between retrying the code generation.

Supposedly this can be compiled into an exe with [auto-py-to-exe](https://pypi.org/project/auto-py-to-exe/).
