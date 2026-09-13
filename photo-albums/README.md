# Make your old photo albums more accessible

Old photo albums are easy to leave on a shelf. Getting the pictures into a digital collection makes them easier to browse, share and come back to.

These instructions ask an AI agent to build a tool for your own albums. Photograph whole pages, upload a batch, then review the individual pictures it extracts. The tool crops, straightens and rotate prints, detect faces you can name, flag possible glare or reflections for retakes, and save your progress.

## What you need

1) a paid subscription to either openAI or Anthropic. this work is not suitable for free ai usage as you do not really get access to fronteer models, you only get low thinking and get very limited usage limits.
2) use your Ai in 'work mode'. both Anthropic and AI include 'work modes' this unlock s the agents ability to work and use tooling to build locally.
3) use as good a model as you can, a better model will have less usage and will take more sessions to complete the tooling, a 'lesser' model will work more quickly and complete the task sooner but will be more likely to require rework. as a minimum i suggest GTP-5.6-sol medium or Opus 5 medium.

## Privacy and family photographs

Assume the photographs the agent inspects may be sent to your AI provider. That includes faces and any writing on the pages. Keeping the files on your computer does not mean the agent's work happens entirely there.

The prompt asks for an app that processes photographs locally, without additional cloud recognition services. Only supply photographs you are comfortable sharing with your chosen AI provider. 


## Getting started

Create a working folder for the agent to use. Put the photos you took of the pages of the albums in there.
Tip: try to be aware of glare and reflections on the photographs you take and minimise as much as possible.


Copy the [full agent instructions](prompt.md) into your agent and give it access to the working folder. Allow it to create files and run code there. It will inspect the sample, choose an implementation for your computer and carry the work through to a functioning tool.

The result will be a locally running app. the agent will give you a link to open it in the browser. this is only running locally and for your use only, no other internet users can access the app as it is only running on your computer for you.


