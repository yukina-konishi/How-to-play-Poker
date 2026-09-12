# How to Play Poker — Beginner Edition

A beginner's guide to Texas Hold'em poker, built as a small multi-page website. Covers the basic rules, betting rounds, beginner strategy tips, and ends with a self-grading quiz to test what you've learned.

**Live site:** https://yukina-konishi.github.io/How-to-play-Poker/

## Background

This started as an assignment for my web development course at ELTE. 
After the semester, I revisited it to practice building a more polished, 
portfolio-ready site — redesigning the visual style, rebuilding the quiz 
to grade itself in the browser instead of emailing answers, and refining 
the accessibility features.

## Features

- **Rules & strategy pages** — walks through the setup, the four betting rounds, hand rankings, and common beginner mistakes to avoid
- **Self-grading quiz** — a multiple-choice quiz built with vanilla JavaScript that checks your answers instantly in the browser and shows the correct answer for anything you got wrong, no page reload or server needed
- **Accessibility mode** — a toggle that switches to a high-contrast color scheme and larger text
- **Responsive layout** — adapts from desktop down to mobile
- **Intro video** — with a full text description page for accessibility

## Tech stack

- HTML, CSS, and vanilla JavaScript (no frameworks for the interactive logic)
- [Bootstrap](https://getbootstrap.com/) for a couple of utility classes (video aspect ratio, visually-hidden text)
- [Google Fonts](https://fonts.google.com/) (Fraunces, Inter)

## Pages

| Page | Description |
|---|---|
| `index.html` | Home page — intro to poker and the intro video |
| `rules.html` | The rules of Texas Hold'em |
| `strategy.html` | Beginner strategy tips and hand probability table |
| `form.html` | Self-grading quiz |
| `video-description.html` | Plain-text accessible description of the intro video |

## Running locally

Clone the repo and open `index.html` in any browser — no build step or dependencies required.

```bash
git clone https://github.com/yukina-konishi/How-to-play-Poker.git
```

## Author

Yukina Konishi — [woofin.5oo@gmail.com](mailto:woofin.5oo@gmail.com)
