# LEANSpark Playbook Skills

Running Lean, in your agent's vocabulary.

LEANSpark (leanspark.ai) is LEANSTACK's AI product for practicing Running
Lean: Lean Canvas, customer interviews, and 90-day validation cycles. This
marketplace carries the LEANSpark Playbook Skills in full — complete
Running Lean choreographies, readable by humans and runnable by agents.

## Install

In Claude Code:

```
/plugin marketplace add leanspark/skills
/plugin install leanspark@leanspark-skills
```

The skills then appear in `/skills` and fire on their own when a
conversation calls for them. To pick up new skills and updates later:

```
/plugin marketplace update leanspark-skills
/plugin update leanspark@leanspark-skills
```

## The skills

| Skill | The job | From the book |
|---|---|---|
| `leanspark:stress-test` | Idea → committed bet: draft the canvas, thought-test the four core gates, split blurry ideas into separate bets, run the viability math, place the bet | *Is Your Idea Worth Pursuing* |
| `leanspark:interview` | Conversations → evidence: find recent switchers, run three-act interviews, synthesize Customer Forces, turn interest into real commitments | *How to Talk to Customers* |

Each skill carries its whole book as bundled reference chapters and
choreographs it move by move. The same packs are also a signed-in zip
download at [leanspark.ai/skill-packs](https://leanspark.ai/skill-packs?src=marketplace)
for Claude and Claude Cowork, where plugins aren't available.

The skills run standalone from a single sentence. The scored stress test
and the interview lab run in your LEANSpark workspace — your agent spars,
LEANSpark keeps score.

Pair the skills with the **LEANSpark MCP connector**
(`https://leanspark.ai/mcp`, OAuth) so your agent reads your live business
model instead of starting from a blank page:
[leanspark.ai/mcp-server](https://leanspark.ai/mcp-server).

More at [leanspark.ai/skills](https://leanspark.ai/skills).

---

The method is Ash Maurya's Running Lean. © LEANSTACK. The skill texts in
this repository may be installed and used with your own venture; they may
not be republished or resold.
