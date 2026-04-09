# Event Horizon

**The Cognitive Doomsday Clock** — tracking the erosion of human cognitive independence in the AI era.

A scroll-driven single-page experience that visualizes the slow, invisible shift from a world built by humans through machines, to a world built by machines for machines.

## The Thesis

The current generation is the last that built things from scratch — the last that can independently verify whether AI output is correct. Future generations won't lack intelligence. They'll lack the friction that produces understanding. They won't know what they don't know.

The clock doesn't strike midnight. It simply becomes unreadable.

## How It Works

- **9 eras** from 1990 to 2076, each a "minute" on the doomsday clock
- **The clock degrades** as you scroll — golden and whole at the start, fractured and fading by the end
- **Earth's atmosphere** represents the shrinking window of human cognitive independence — calculated from today's real date, narrowing each day
- **Audio ticks** echo through a synthesized hall reverb on each step forward
- **Past events** are cited with references; **future projections** fade visually — uncertain, not asserted

## Tech

Single `index.html` with embedded CSS and JS. No frameworks, no build step, no dependencies.

- Canvas 2D API (space background + clock)
- Web Audio API (synthesized echoing tick)
- Snap scroll with discrete clock steps

## Deploy

Serve `index.html` and `tick.mp3` from any static file server.

```
index.html    # Everything
tick.mp3      # Optional: real clock tick sample (fallback from Web Audio synthesis)
```

## Contributors

<a href="https://github.com/martinlall">
  <img src="https://github.com/martinlall.png" width="60" style="border-radius:50%" alt="Martin Lall">
</a>
<a href="https://github.com/marctuulik">
  <img src="https://github.com/marctuulik.png" width="60" style="border-radius:50%" alt="Marc Tuulik">
</a>

**[Martin Lall](https://github.com/martinlall)**
**[Marc Tuulik](https://github.com/marctuulik)**

## License

MIT
