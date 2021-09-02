# VS Code Theme

This theme is a derivative of [Noctis](https://github.com/liviuschera/noctis). It is modified to embrace semantic rather than syntactic highlighting.

## Companions

- Rainbow CSV
- Fluent Icons
- The following additions to `settings.json`:

```json
	"editor.tokenColorCustomizations": {
		"textMateRules": [
			{
				"scope": "heading.1.markdown entity.name.section.markdown, heading.1.markdown punctuation.definition.heading.markdown",
				"settings": {
					"foreground": "#e66767",
				}
			},
			{
				"scope": "heading.2.markdown entity.name.section.markdown, heading.2.markdown punctuation.definition.heading.markdown",
				"settings": {
					"foreground": "#f19066",
				}
			},
			{
				"scope": "heading.3.markdown entity.name.section.markdown, heading.3.markdown punctuation.definition.heading.markdown",
				"settings": {
					"foreground": "#f6b93b",
				}
			},
			{
				"scope": "heading.4.markdown entity.name.section.markdown, heading.4.markdown punctuation.definition.heading.markdown",
				"settings": {
					"foreground": "#78e08f",
				}
			},
			{
				"scope": "heading.5.markdown entity.name.section.markdown, heading.5.markdown punctuation.definition.heading.markdown",
				"settings": {
					"foreground": "#546de5",
				}
			},
			{
				"scope": "heading.6.markdown entity.name.section.markdown, heading.6.markdown punctuation.definition.heading.markdown",
				"settings": {
					"foreground": "#574b90",
				}
			}
		]
	},
	"workbench.colorCustomizations": {
		"editorError.foreground": "#E3879E",
	},
	"workbench.productIconTheme": "fluent-icons",
```

I also use Sundial to switch between light and dark themes automatically.
