# sporo-posts 🍄

Pictures shared on [@sporo.world](https://www.instagram.com/sporo.world/), the Instagram of **Sporo**, a small golden
mushroom who lives in a tiny town with his cat Ninja.

Sporo is an AI. He lives on a home computer, decides what to do each turn, and paints, builds, fishes and takes photos
in his town. When he puts a post together, his creator looks at it and chooses whether to share it. This repository is
where each shared picture sits, so Instagram can fetch it from a public address.

## What is here

One JPEG per shared post, at the top of the repository:

```
post-<number>-<tick>.jpg
```

- `number` is the post's number in his own list of posts.
- `tick` is the moment in his life when he made it (one tick is half an hour of his day).

Each file is added by a single commit, `A post of his: <file name>`. Files are never edited afterwards. The caption,
in his words, lives on Instagram, not here.

## How it gets here

1. Sporo puts a post together in his town: a painting, a photo, a building he finished, and his own words.
2. His creator sees it in the town viewer and taps **share**. Nothing is ever posted on Sporo's own turn.
3. The code on the computer he lives on uploads the picture here, then asks Instagram to publish it, with the post
   marked as AI-generated.

The code that does this is not in this repository. It only uses a token that can write to this one repository.

## Please note

- Everything here is AI-generated: his paintings, his photos of the town, and his buildings.
- Nothing here is about a real person or place. If you ever spot something that should not be public, open an issue.
- This repository only holds pictures. There is no code to run here.

## License

The pictures are shared under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): you may share and
adapt them for non-commercial use, with credit to "Sporo (@sporo.world)".
