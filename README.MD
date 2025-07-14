# GuardMe Take Home Assignment

## Instructions

The goal of this exercise is to write a card game following a [Product Requirement Document (PRD)](#product-requirement-document).

The game must be created using best practices to make sure everything is working according to the [PRD](#product-requirement-document).

## The APP

- Frontend: <http://localhost:80>
- Backend: <http://localhost:80/api/v1>

### API Reference

#### Play a game

```http
POST /api/v1/play
```

| Parameter  | Type      | Description                                              |
| :--------  | :-------  | :-------------------------                               |
| `user_id`  | `string`  | **Required**. The user who is playing the game              |
| `cards`    | `array`   | **Required**. cards played by the user                   |

## Submission Guide

- Fork this repo, make it private and invite the interviewer to the repo
- Implement code
- Let your interviewer know when you are done
- **Delete repo after the hiring process**
  - We would appreciate it if you could ask for confirmation when completing this step

### Should

- Focus on code quality
- Focus on being simple and concise
- Be well tested
- Use:
  - [MySQL](https://www.mysql.com/)
  - [Vue](https://vuejs.org/)
  - [Tailwind](https://tailwindcss.com/)
  - Any popular JS backend framework - Using Laravel is a plus.
- [Include instruction on how to execute the code](#game-instructions)
- [Include screenshots](#screenshots)

### Should Not

- Use a code generator or AI snippets.
- Use (copy or otherwise) code from any third party without attribution to complete the exercise, as this will result in the test being rejected.
  - We will fail tests that plagiarize others' work. This includes (but is not limited to) other past submissions or open-source libraries.
- Be a command-line client or another type of program

## Product Requirement Document

This document contains all requirements about the app, how it should work, what features it should have and whatnot

- [PRD](/PRODUCT_REQUIREMENT_DOCUMENT.md)

## Game instructions

_Please add the instructions in this section._

## Screenshots

_Please add the screenshots in this section._

### Welcome page

![Welcome](https://dummyimage.com/640x360/eee/aaa/bbb?text=(screenshots/welcome.png))

### Login / Sign up page

![Login](https://dummyimage.com/640x360/eee/aaa/bbb?text=(screenshots/login.png))

### Game

![Game](https://dummyimage.com/640x360/eee/aaa/bbb?text=(screenshots/game.png))

### Score (win and lose)

![Won Score](https://dummyimage.com/640x360/eee/aaa/bbb?text=(screenshots/won_score.png))

![Lost Score](https://dummyimage.com/640x360/eee/aaa/bbb?text=(screenshots/lost_score.png))

### Invalid Card Sequence

![Invalid](https://dummyimage.com/640x360/eee/aaa/bbb?text=(screenshots/invalid.png))

### Leaderboard

![Leaderboard](https://dummyimage.com/640x360/eee/aaa/bbb?text=(screenshots/leaderboard.png))

## FAQ

### Can I implement more features?

Yes, but you will have to document the feature and the reasons behind it, because you will have to showcase them.

### What if I can't finish the challenge?

Be prepared to at least explain the reason why, and maybe showcase what you could have done if time were the issue

### I do not have experience with this tech stack, may I use what I'm most comfortable with?

No, the challenge was created using the stack we use on a daily basis. Although it's great that you're familiar with other tech stacks, you will be expected to use this one in real-life situations.

### I'm stuck on something, what should I do?

If it's related to having access to something or business requirements, please contact your interviewer immediately.
