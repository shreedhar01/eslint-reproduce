1. `Install and Config Eslint`
```
pnpm create @eslint/config@latest //for  pnpm
npm init @eslint/config@latest //for npm
```
2. While configuring in cli try to change position of options in `✔ What do you want to lint? ` and `✔ Where does your code run?` and press enter but they dont get selected.
```
shree@shree:~/check$ pnpm create @eslint/config@latest
@eslint/create-config: v1.10.0

✔ What do you want to lint? · javascript
✔ How would you like to use ESLint? · syntax
✔ What type of modules does your project use? · commonjs
✔ Which framework does your project use? · none
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser
✔ Which language do you want your configuration file be written in? · ts
The config that you've selected requires the following dependencies:

eslint, globals, typescript-eslint
✔ Would you like to install them now? · No / Yes
✔ Which package manager do you want to use? · pnpm
☕️Installing...
Packages: +120
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Progress: resolved 120, reused 120, downloaded 0, added 120, done

devDependencies:
+ eslint 9.35.0
+ globals 16.4.0
+ typescript-eslint 8.43.0

Done in 4.8s using pnpm v10.15.0
A config file was generated, but the config file itself may not follow your linting rules.
```
