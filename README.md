# DebugWalk

Ever get so stuck on a bug that you just stare at the screen for an hour? Yeah, me too. 

I built **DebugWalk** for the DEV Community Hacktoberfest "Touch Grass" challenge. It's a super simple web app designed to act as a circuit breaker when you're dealing with screen fatigue or a coding problem that just won't click. 

Instead of opening another Stack Overflow tab, you tell the app what you're working on. It then uses AI to generate a quick, 15-minute outdoor walking mission metaphorically tied to your problem. It forces you to step away from the laptop, go outside, and clear your head.

## Live Demo
You can try it out right now: **[Link to your GitHub Pages URL]**

## How it's built
I wanted to keep this as lightweight as possible. There is no backend, no database, and no tracking. 
* **Frontend:** Plain HTML and Vanilla JavaScript.
* **Styling:** Tailwind CSS (pulled via CDN).
* **AI:** Google Gemini API (`gemini-1.5-flash`).

Everything runs locally in your browser. Your API key and whatever frustrations you type into the prompt never touch a database.

## Running it locally
Since it's just a static HTML file, running it on your own machine takes about five seconds.

1. Clone this repo:
   ```bash
   git clone [https://github.com/badshahaditya57-sketch/debugwalk.git](https://github.com/badshahaditya57-sketch/debugwalk.git)
