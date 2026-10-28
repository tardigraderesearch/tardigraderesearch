<img src="media/hero.jpg" alt="I build robots that walk and map themselves, AI agents that remember and code, and tooling that takes robots from simulation to reality" width="100%">

<p align="center"><b>Every tile flips to a live demo. Click one to open the project.</b><br>
<a href="mailto:tardigraderesearch@yahoo.com">tardigraderesearch@yahoo.com</a></p>

### Robots

<table>
<tr>
<td><a href="https://github.com/tardigraderesearch/hexapod-rl"><img src="media/tiles/hexapod-rl.gif" width="370" alt="Hexapod: a six-legged robot I designed and built, taught to walk in simulation. Click to open the repo."></a></td>
<td><a href="https://github.com/tardigraderesearch/robo_prober"><img src="media/tiles/robo_prober.gif" width="370" alt="Robo Prober: plug in an unknown robot and it finds its own motors and safe limits. Click to open the repo."></a></td>
</tr>
<tr>
<td><a href="https://github.com/tardigraderesearch/builds"><img src="media/tiles/builds.gif" width="370" alt="Builds: robots, a hand-wound electric motor and the hardware I make. Click to open the repo."></a></td>
<td><a href="https://github.com/tardigraderesearch/digital-twin-generator"><img src="media/tiles/digital-twin-generator.gif" width="370" alt="Digital Twin: real robot in, simulation-ready model out. Click to open the repo."></a></td>
</tr>
</table>

### AI agents

<table>
<tr>
<td><a href="https://github.com/tardigraderesearch/ari"><img src="media/tiles/ari.gif" width="768" alt="ARI: my personal AI assistant. Its memory is a vault of notes I own, so any AI model can run it. Click to open the repo."></a></td>
</tr>
</table>

### Tooling

<table>
<tr>
<td><a href="https://github.com/tardigraderesearch/aruco-tag-maker"><img src="media/tiles/aruco-tag-maker.gif" width="370" alt="ArUco Tag Maker: prints named tags that let a camera track real objects in 3D. Click to open the repo."></a></td>
<td><a href="https://github.com/tardigraderesearch/posebridge"><img src="media/tiles/posebridge.gif" width="370" alt="PoseBridge: pose a figure by hand and get the same pose in Blender and Unreal. Click to open the repo."></a></td>
</tr>
<tr>
<td colspan="2"><a href="https://github.com/tardigraderesearch/digital_twin_generator"><img src="media/tiles/digital_twin_generator.gif" width="768" alt="Digital Twin Generator app: eight guided steps from 3D scan to a robot model a simulator can load. Click to open the repo."></a></td>
</tr>
</table>

### Currently

- **U.S. Air Force Independent Duty Medical Technician (Staff Sergeant).** A credentialed provider who has treated 6,000+ patients without an on-site physician, and an instructor for the rescue teams that cover astronauts and Navy SEALs.
- **Directing AI coding agents** (Claude, Codex, Gemini) in parallel against written specs and tests, through ARI, my own assistant. An acceptance gate grades every job on independent checks rather than the agent's own report: 255 jobs graded so far.
- **Proving robots safe before they move.** 0 of 220,902 commanded servo pulses left their safe limits across 26 randomized simulated robots, backed by 450+ automated tests and CI on Linux, Windows and macOS.

### How I work

I start from the physical problem and the person who has to use the tool, then design
the system around it: what it must do, what "working" means, and what must never happen.

- **Safety before convenience.** Hardware doesn't move until it's armed, stays inside
  limits a person set, moves at a capped speed, and can always be stopped.
- **It has to just work.** One launcher checks its own dependencies, builds its own
  environment and runs on Linux, Windows and macOS.
- **Pieces that compose.** I break big systems into tools that stand on their own and
  plug into each other.
