# openTCG

> experimental TCG game engine

openTCG is a monorepo that contains:
- **engine**: python code for the game engine
- **lobby**: nodejs code for match making, overall game stats
- **match**: nodejs that store match session and use game engine
- **player**: nodejs code that store player stats, preferences
- **web**: react code to display game

The engine of openTCG in inherently stateful and cpu bound. Therefore, it use oop most of the time.

## Dependencies
- node
- pnpm
- react
- python
- uv
- docker
- cloudfare
  - worker
