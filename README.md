# HyMinions

Hypixel Skyblock - Minions Calculator and Events Timer. Know your most profitable minions! Tailor made for each profile, highly accurate.

The website is live at https://hyminions.herokuapp.com

## Disclaimer

I have forked KidProf's HyMinions git repo with the aim to restore up-to-date Forge calculator data.
A personal API token key is needed. The changes were needed because KidProf used their own personal backend to fetch Auction data.
The functionality was restored by modifying and adapting old unused code.
The new Forge contacts directly Hypixel's own API, and has to perform up to 70 API requests every time the Forge page gets loaded, so expect load times up to 30 seconds on page refresh.

All credits go to KidProf for the awesome tool, and the original contributors/credits.

## Installation

Requires Node.js and npm

```bash
npm install
```

or

```bash
yarn
```

## Usage

```bash
npm run start
```

or

```bash
yarn start
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

More contributing guidelines at https://hyminions.herokuapp.com/contribute

## License
Copyright © 2020 KidProf

This work is licensed under the [MIT license](https://choosealicense.com/licenses/mit/).