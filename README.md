<p align="center">
  <img src="https://github.com/wearrrrr/Alu/assets/99224452/dd1bef45-e96f-49bd-ac09-caa4ddc214d6" alt="AluLogo" width="250"/>
</p>

# Alu

Alu is a beautiful, functional, and sleek web proxy, which focuses on customization and ease of use.

# Features

- 🌐 UV and Rammerhead support
- 🎨 Themes
- 🕶 Multiple site cloaking options
- 🎮 50+ Games to choose from
- 🌎 English and Japanese support
- 🚀 High performance
- 🔍 Multiple Search Engines to pick from

# Deploying Alu

Deploying Alu is about as simple as it gets, from your terminal, type

`git clone https://github.com/titaniumnetwork-dev/Alu --recurse-submodules`

This command should clone Alu's frontend, as well as [alu-games](https://github.com/wearrrrr/alu-games). If you wish to skip cloning games, then leave out the last flag.

Install pnpm with `npm I -g pnpm`.

Then simply run `pnpm i` to install all node_modules, and then build the frontend with `pnpm run build`, this shouldn't take more than a couple seconds.

Finally, run `pnpm start` to actually serve Alu! It defaults to port 3000 for everything, but this can be specified in an env file.

Congrats, you've now deployed your very own web proxy!

## What about Docker?

Alu can be easily dockerized with the `Dockerfile` provided in the repository. Simply run `docker build -t alu .` to build the image, and then `docker run -p 3000:3000 alu` to run the container, and you're good to go!

# Technologies

- Ultraviolet by Titanium Network
- Bare Server from TompHTTP
- Rammerhead by binary-person
- Astro from astro.build
- Typescript
- ExpressJS
- Prettier
- ESLint

# License

Alu is licensed under the GNU GPL v3.0 License as of 2/9/2024.
