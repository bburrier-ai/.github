# Agent-driven Development

Hi, I'm **Beau**. I'm a human. You can find my GitHub profile [here](https://github.com/bburrier). ***So what is this?*** This is a GitHub Organization that I have created to serve as a sandbox for AI agent-driven development.

### Outside the IDE

Like most software engineers currently I use AI to assist in development using various IDE's and tools that let me interact with the code and also ask for the help of an agent when I want to.

I am exploring a different approach here. Rather than using an agent tethered to my local IDE, I have setup an autonomous agent (**[Hermes](https://hermes-agent.nousresearch.com/)**) on a remote server (**Hostinger VPS**). I primarily communicate with this agent through **Telegram** conversations.

<table>
  <tr>
    <td width="72" align="center"><a href="https://hermes-agent.nousresearch.com/"><img src="assets/hermes.png" alt="Hermes Agent" width="40" /></a></td>
    <td><strong>Hermes</strong> — The autonomous AI agent that drives this workflow. It plans work, writes code, and pushes changes to repositories in this Organization.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://github.com/bburrier-ai"><img src="assets/github.png" alt="GitHub" width="40" /></a></td>
    <td><strong>GitHub</strong> — Where the code lives. This Organization holds the repos that Hermes creates and maintains, authenticated via a GitHub App.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://www.hostinger.com/vps-hosting"><img src="assets/hostinger.png" alt="Hostinger" width="40" /></a></td>
    <td><strong>Hostinger</strong> — The VPS that hosts Hermes outside my local machine. It gives the agent a persistent and isolated remote environment with the freedom it needs to operate autonomously.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://telegram.org/"><img src="assets/telegram.png" alt="Telegram" width="40" /></a></td>
    <td><strong>Telegram</strong> — My primary interface to Hermes. I communicate with the agent through Telegram conversations rather than through a local editor integration.</td>
  </tr>
</table>


### Free the agent

I own the repositories under this Organization, but so does **Hermes**. It can create new repositories, plan, write code, document, commit, and push. It has essentially free reign on the server (VPS) and also within this Organization, bounded by the scope and permissions set on the GitHub App it uses for [authentication](https://docs.github.com/en/apps/creating-github-apps/authenticating-with-a-github-app/authenticating-as-a-github-app-installation).

The repos here are created by me and my agent working together, but mainly the agent. The goal is to iron out the details of how to use an autonomous agent like Hermes in a development process that frees the agent as much as possible to get maximum leverage and productivity while also protecting critical data and resources.