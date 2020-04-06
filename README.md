# React Native Starter :star: _Yorkshire Edition_ :coffee:

A React Native starter repo with the aim to implement scalable "gold star" standards from the get go.

## Intro

This hopefully exists as a living repo, that will grow and change as new

> For the love of god, follow everything here: https://facebook.github.io/react-native/docs/getting-started

## Outline

This starter will setup you up with a project that:

1. Structure/Architecture with Prettier and ESLint
2. React Native
3. Redux, Redux-Thunk
4. React Native Debugger
5. React Navigation
6. Axios
7. Formik and Auth forms
8. Basic screens

> We'll probably sprinkle some Lodash/FP in there to get things going.

- Analytics?
- Crashes? Sentry?
- Firebase? Push Notifications?
- Deeplinks?
- Redux Persist?
- TypeScript examples
- Unit tests? Jest?
- Integration tests? Jest?
- Detox/Appium E2E tests?
- Fastlane?
- Project.pbx setup?

## Assumptions

- You enjoy single line quotes, no semi-colon enforcement and auto-formatting from Prettier.
- You agree with the current ESLint ruling - this is mainly what I'm used to so go fish for something different.
- You're potentially going to require that your state/ folder is going to be shared across multiple platforms.

## Motivations

TODO

## Explanations

Maybe one day

## Troubleshooting

RIP

Network requests not showing in React Native Debugger?
This could be for a multitude of reasons but more than likely you haven't right clicked in the left side / state window and clicked 'Enable Network Inspect'. **I think it's silly as well but it's what we've got**.

If you're confused why you can't see you're state/state tree in React Native Debugger -> make sure the redux tools aren't on auto select as it might default to React Navigation rather than the redux state!

# Useful links
