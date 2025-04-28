# AI Research and Article Writing Agent

## About the Project

This project is an **AI Research and Article Writing Agent**.  
It uses **CrewAI** to create a team of AI agents that work together to **research** a topic, **summarize** the information, and **write** a complete article.

I made this project because I wanted to see how different AI agents can work together to finish a big task, like writing a full article.

---

## How I Built It

### Tools I Used
- **CrewAI** — to manage and organize the agents and their tasks.
- **OpenAI GPT-4.0-mini** — to do the research, write summaries, and create the article.

### Steps I Followed

1. **Created Agents**  
   I made different agents using CrewAI:
   - A **Research Agent** to find information about a given topic.
   - A **Summarizer Agent** to make short notes from the research.
   - A **Writer Agent** to write the final article using the notes.

2. **Set Up the Crew**  
   I put all the agents together into one **Crew**. I told the crew what steps to follow:  
   (First research ➔ then summarize ➔ then write.)

3. **Used GPT-4.0-mini**  
   Each agent used GPT-4.0-mini to understand the task, find information, and write clearly.

4. **Testing**  
   I tested the system with different topics to make sure the final articles were correct and easy to read.

---

## How It Works

- You give the system a **topic**.
- The Research Agent finds information.
- The Summarizer Agent makes short notes.
- The Writer Agent writes a full article based on the notes.
- You get a ready-to-use article!

---

## What I Learned

- How to use **CrewAI** to make agents work together.
- How to **break a big task** (writing an article) into smaller tasks.
- How to **control** what each agent should do clearly.
- How powerful **GPT-4.0-mini** can be when used in a team of agents.

---

## Future Plans

- Add an **Editor Agent** to check grammar and improve writing.
- Make a simple web page for easy use.

---

## Final Thoughts

This project showed me how agents can work together to do complex jobs.  
It was a fun and useful way to learn about **multi-agent AI systems**.
