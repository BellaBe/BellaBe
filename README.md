# LeanOS

AI native operating system for solo founders. One person. Fiveperson output.

LeanOS is a composition of independent modules. Each runs one business function end to end. They compose through the filesystem.

## The Modules

| Module | Function | Price |
||||
| [StrategyOS](https://github.com/BellaBe/strategyos) | Research, hypothesis, gap analysis | Free — MIT |
| RevenueOS | Pipeline, outreach, nurture, retention | Paid |
| EngineeringOS | Spec → build → verify → deploy | Paid |
| WriterOS | Longform content from artifacts | Paid |
| StyleOS | Brand inputs → production design system | Paid |
| FoundryOS | Specs and builds the modules above | Paid |

Each module: own repo, own agents, own skills. No shared runtime. Plain markdown, no compiled code, no hidden prompts. `cat` any file.

## How They Compose

StrategyOS is the entry point. It produces the Hypothesis Register and Gap Register.

Downstream modules consume it:

 RevenueOS reads gaps → builds outreach
 EngineeringOS reads validated hypotheses → builds product
 StyleOS reads positioning → builds brand
 WriterOS reads everything → produces narrative

FoundryOS sits underneath. 6 agents, 27 skills. You describe a system, it specs construction, builds agents and skills, wires infrastructure, assembles the orchestrator. Every module above was built with FoundryOS. Including FoundryOS.

Decide before you build. Build what survives validation. Sell what's been built.

## Foundation

 Claude Code as runtime
 Markdown skills, no compiled code
 Filesystem as message bus
 Plain text artifacts, no vendor lockin

## Start Here

Begin with StrategyOS. Free. MIT. Decides what to build before you spend cycles building.

```bash
git clone https://github.com/BellaBe/strategyos
cd strategyos
claude
```

Paid modules: [bellabe.github.io/leanos](https://bellabe.github.io/leanos/)



[LinkedIn](https://linkedin.com/in/bellabelgarokova/) · UAE
