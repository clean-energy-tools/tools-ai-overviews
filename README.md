# tools-ai-overviews
Context documents to assist AI systems in understanding clean energy protocols

This repository contains Markdown files describing the architecture, function, and use of various clean energy software tools.  The "tools" are primarily communication protocols used in clean energy systems, but also include systems like NodeRED or N8N.

The descriptions are meant to serve two purposes:

1. Help human beings understand the tools
2. Help AI systems understand the tools

When we use an AI system (generative AI like Large Language Models) to develop software, deployment plans, documentation, or the like, it's helpful to provide contextual information about the tools or programming platforms being used.  The LLM system you're using (e.g. Claude Code) will create far more accurate results if it knows abnout the tools you're using.

For example, a coder might be creating an electric vehicle service equipment (EVSE) control system which is to be controlled by the OCPP, OCPI and OpenADR protocols.  That means any generative AI system used by the coder must understand those three protocols.

The generative AI system may, or may not, have already "read" the protocol specifications and already how they work.  If it hasn't read the protocols, the AI system will make wild guesses (hallucinate) how the protocols work.  Even if it has "read" the protocol specifications, the AI system might not have properly understood what it read.  But, a well-crafted summary of the protocol or other tool, giving practical information on its architecture or use, can make all the difference in the world.

# The equivalent of a `CLAUDE.md` for every clean energy tool

The audacious goal of this project is creating a Markdown file for every clean energy protocol or software tool which is the equivalent to a `CLAUDE.md` file.

The `CLAUDE.md` file is used with Claude Code.  Other tools (like OpenCode) use a file named `AGENTS.md` for a similar purpose.  Whatever the file name, these files describe the project, its goals, primary use cases, software tools and packages used in the project, and more.  These files assist the AI system to more accurately implement the software you envision.

The `CLAUDE.md` or `AGENTS.md` file are meant to contain the contextual overview of a given project.

For a protocol like OCPP there might be a file, `OCPP.md`, containing the contextual overvie of the OCPP protocol.  Coders implementing the OCPP protocol could therefore reference `OCPP.md` in their `CLAUDE.md` or `AGENTS.md` file.

That's what this project aims to do - to publish Markdown files containing the contextual overview of each protocol or tool in the clean energy space.

# Asking for help

THis project is audacious in scope, and clearly cannot be implemented by a lone volunteer.  Instead, this project requires domain experts for each protocol or tool to contribute these files.
