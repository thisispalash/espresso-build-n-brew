# Semicolon Fingers
> Addressing the loneliness epidemic..

> [!NOTE]
> See hackathon specific information [below](#hackathon-information)

Semicolon Fingers is a storytelling platform tackling the global loneliness epidemic through an emotionally intelligent, token-incentivized web3 experience. By blending interactive text, sentiment analysis, and open-source infrastructure, it offers a new kind of human connection — one that is meaningful, measurable, and mental-health-forward.

_See the application in action_

[![youtube-demo](https://img.youtube.com/vi/7HWkueO_RF4/0.jpg)](https://youtu.be/7HWkueO_RF4?si=yQt1qHiockcr1JXB)

## How it works

Semicolon Fingers has two entrypoints — the writing side (empty-your-mug) and the reading side (pull-my-thread); On the writing side, a user selects a colour (base emotion), a prompt (nuanced emotion), and writes their story. They then deploy their story on the network as a NFT contract (which is sponsored). On the reader side, a user is presented with a random story, coloured by its emotion, which they can unfurl to read, or stumble upon another story. This stumbling informs the rate at which new tokens are dripped to the writers of the stories being read.

For more detailed information, please see the following,
- [`rollup`](./docs/rollup.md)
- [`tokenomics`](./docs/tokenomics.md)

## Hackathon Information
> chain id: `1066601`, a reference to belphegor number(s)

All code pertaining to the hackathon is available in [`src/`](./src/). Since there are multiple repositories, they have been added as submodules to this submission.

- [**contracts**](./src/contracts/) These are the current contracts enabling the network.
- [**espresso**](./src/espresso/) Repositories containing the forks of nitro-contracts and the espresso nodes.
- [**client**](./src/client/) Repositories containing the frontend code.

Finally, information about open intents can be [found here](./docs/intents.md).