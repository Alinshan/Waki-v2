# Waki


## Tech stack

- [Flux Schnell](https://togetherai.link/together-flux/) from BFL for the image model
- [Together AI](https://togetherai.link) for inference
- Next.js app router with Tailwind
- Helicone for observability
- Plausible for website analytics

## Cloning & running

1. Clone the repo:
2. Create a `.env.local` file and add your [Together AI API key](https://togetherai.link): `TOGETHER_API_KEY=`
3. Run  and install dependencies and run locally

## Installation
```
git clone https://github.com/Alinshan/Waki-v2
 ```
```
cd Waki-v2
```

```
npm install
```

```
npm run dev
```

## Future Tasks

- [ ] Show a download button so people can get their images
- [ ] Add auth and rate limit by email instead of IP
- [ ] Show people how many credits they have left
- [ ] Build an image gallery of cool generations w/ their prompts
- [ ] Add replay functionality so people can replay consistent generations
- [ ] Add a setting to select between steps (2-5)
