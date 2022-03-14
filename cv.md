# Zhanat Lepesbayeva
-----------------------------------

## Contacts
- Location: Minsk, Belarus
- Phone: +375 44 744 27 95
- Email: zhankaam@gmail.com
- Github: [zhankaam](https://github.com/zhankaam)
- Linkedin: [Zhanat Lepesbayeva](https://by.linkedin.com/in/zhanat-lepesbayeva-937a06201)

-----------------------------------

## About me
I am open-minded and learn new things quickly.I am open to challenges and constructive feedback.

-----------------------------------

## Skills
- HTML / CSS / SASS
- JavaScript / TypeScript
- React / Redux / Redux-toolkit
- Git / Github / Gitlab / Bitbucket
- VS Code, IntelliJ IDEA (Webstorm / PhpStorm)
- Material-UI / Ant-design / Tailwind-css
- Redux-thunk / Redux-saga
- Next.js
- Storybook
- Unit-tests / React-testing-library

------------------------------------

## Experience:
***JavaScript Software Engineer - EffectiveSoft***

## Code example

John wants to give a total bonus of ```$851``` to his three employees taking fairly as possible into account their number of days of absence during the period under consideration. Employee A was absent ```18``` days, B ```15``` days, and C ```12``` days.

The more absences, the lower the bonus ...

How much should each employee receive? John thinks A should receive ```$230```, B ```$276```, C ```$345``` since ```230 * 18 = 276 * 15 = 345 * 12``` and ```230 + 276 + 345 = 851```.

### Task:
Given an array  ```arr``` (numbers of days of absence for each employee) and a number ```s``` (total bonus) the function ```bonus(arr, s)``` will follow John's way and return an array of the fair bonuses of all employees in the same order as their numbers of days of absences.

```s``` and all elements of ```arr``` are positive integers.
### Examples:
```sh
bonus([18, 15, 12], 851) -> [230, 276, 345]
bonus([30, 27, 8, 14, 7], 34067) -> [2772, 3080, 10395, 5940, 11880]
```

### My Solution:

```
const bonus = (arr, s) => arr.map(a => Math.round(s / arr.reduce((acc,i) => acc + a / i,0)))
``` 

------------------------------------

### Courses:
- [Stepik](https://welcome.stepik.org/ru)
- [IT-incubator](https://it-incubator.by/React-online.html)
- [UI-dev](https://ui.dev/c)

------------------------------------

## Languages:

- English: **A2+ / B1**
- Russian: **Advanced**
- Kazakh: **Native**
