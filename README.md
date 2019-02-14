# shortcut-challenges
A set of challenges for the shortcut challenge runner https://routinehub.co/shortcut/1953

## Challenge Format

Challenge names should be all lowercase and alphanumeric
with spaces allowed (`/[a-z0-9 ]+^$/`). Other characters are
allowed but may make it more difficult to be played.

```json
{
	"_list": [<challenge name>],
	<challenge name>: {
		"name": <challenge name>,
		"description": <a description of your challenge and detailed instructions on what input translates to what output>,
		"input": <what input your challenge requires. see Types below>,
		"output": <what output your challenge requires. see Types below>,
		"tests": [
			{
				"input": <your test input>,
				"output": <expected output>
			}
		]
	}

}
```

### Types

Challenge input and output should be written so the types
and variable names are clear. Types are represented using
lowercase like `text` and `list`. Variable names are represented
using uppercase like `A` and `Range`. See other challenges
for examples of this.

Challenges must have their names be added to the `_list` to
appear in shortcuts.
