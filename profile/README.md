# Agent-Driven Development

Hi, I'm **Beau**. I'm a human. You can find my GitHub profile [here](https://github.com/bburrier). ***So what is this?*** This is a GitHub Organization that I have created to serve as a sandbox for AI agent-driven development. It also serves as a hub for the tools and platforms I develop related to AI, and insights I gather during my exploration of this ever-evolving frontier.

### Outside the IDE

Like most software engineers currently I use AI to assist in development using various IDE's and tools that let me interact with the code and also ask for the help of an agent when I want to.

I am exploring and documenting a different approach here. Rather than using an agent tethered to my local IDE, I have setup an autonomous agent (**[Hermes](https://hermes-agent.nousresearch.com/)**) on a remote server (**Hostinger VPS**). I primarily communicate with this agent through **Telegram** conversations.

<table>
  <tr>
    <td width="72" align="center"><a href="https://hermes-agent.nousresearch.com/"><img src="assets/hermes.png" alt="Hermes Agent" width="40" /></a></td>
    <td><strong>Hermes</strong> - The autonomous AI agent that drives this workflow. It plans work, writes code, and pushes changes to repositories in this organization. As the scale of agent managed projects increases the <a href="https://hermes-agent.nousresearch.com/docs/user-guide/features/kanban">Hermes Kanban(Multi-Agent Board)</a> feature can be implemented to support a true multi-agent workflow that also provides observability for the human orchestrator. </td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://github.com/bburrier-ai"><img src="assets/github.png" alt="GitHub" width="40" /></a></td>
    <td><strong>GitHub</strong> - Where the code lives. This organization holds the repos that Hermes creates and maintains, authenticated via a GitHub App.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://www.hostinger.com/vps-hosting"><img src="assets/hostinger.png" alt="Hostinger" width="40" /></a></td>
    <td><strong>Hostinger</strong> - The VPS that hosts Hermes outside my local machine. It gives the agent a persistent and isolated remote environment with the freedom it needs to operate autonomously.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://tailscale.com/"><img src="assets/tailscale.png" alt="Tailscale" width="40" /></a></td>
    <td><strong>Tailscale</strong> - Establishes a zero-trust network between the VPS and my devices (desktop, mobile). Allows me to reach the agent environment securely over the tailnet without exposing public ports on the VPS.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://telegram.org/"><img src="assets/telegram.png" alt="Telegram" width="40" /></a></td>
    <td><strong>Telegram</strong> — My primary control interface to Hermes. I communicate with the agent through Telegram conversations rather than through a local editor integration. This allows me to control and receive communication from Hermes in one continuous conversation when moving between desktop and mobile.</td>
  </tr>
</table>


### Free the agent

I own the repositories under this organization, but so does **Hermes**. It can create new repositories, plan, write code, document, commit, and push. It has essentially free reign on the server (VPS) and also within this organization, bounded by the scope and permissions set on the GitHub App it uses for [authentication](https://docs.github.com/en/apps/creating-github-apps/authenticating-with-a-github-app/authenticating-as-a-github-app-installation).

The repos here are created by me and my agent working together, but mainly the agent. The goal is to continue to iron out the details of how to use an autonomous agent like Hermes in a development process that frees the agent(s) as much as possible to get maximum leverage and productivity while also protecting critical data and resources.
