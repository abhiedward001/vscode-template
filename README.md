{
	// Place your settings in this file to overwrite the default settings
	/* editor config */
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.detectIndentation": true,
	"editor.lightbulb.enabled": "off",
	"editor.fontFamily": "Fira Code",
	"editor.fontLigatures": true,
	"editor.formatOnSave": true,
	"editor.formatOnType": true,
	"editor.rulers": [80],
	"editor.snippetSuggestions": "top",
	"editor.wordBasedSuggestions": "off",
	"editor.suggest.localityBonus": true,
	"editor.acceptSuggestionOnCommitCharacter": false,
	"editor.minimap.enabled": false,
	"editor.fontSize": 10,
	"editor.lineHeight": 20,
	"editor.tabSize": 2,
	"editor.hover.enabled": true,
	"editor.renderWhitespace": "boundary",
	"editor.glyphMargin": false,
	"editor.formatOnPaste": true,
	"editor.multiCursorModifier": "ctrlCmd",
	"editor.bracketPairColorization.enabled": true,
	"editor.codeActionsOnSave": {
		"source.fixAll.eslint": "never"
	},
	"editor.cursorStyle": "line",
	"editor.lineNumbers": "on",
	"editor.wordSeparators": "/\\()\"':,.;<>~!@#$%^&*|+=[]{}`?-",
	"editor.wordWrap": "off",
	"editor.inlineSuggest.enabled": true,
	"editor.cursorSmoothCaretAnimation": "on",
	"editor.smoothScrolling": true,
	"editor.suggestSelection": "first",
	"editor.semanticHighlighting.enabled": true,
	"editor.quickSuggestionsDelay": 0,
	"editor.tokenColorCustomizations": {
		"textMateRules": []
	},
	"workbench.sideBar.location": "right",
	"workbench.settings.editor": "json",
	"workbench.startupEditor": "none",
	"workbench.editor.closeEmptyGroups": false,
	"workbench.editor.showTabs": "multiple",
	"workbench.editor.limit.enabled": true,
	"workbench.editor.limit.perEditorGroup": false,
	"workbench.editor.limit.value": 10,
	"emmet.showSuggestionsAsSnippets": true,
	"emmet.triggerExpansionOnTab": true,
	"explorer.confirmDragAndDrop": false,
	"prettier.requireConfig": true,
	"explorer.confirmDelete": false,
	"[javascript]": {
		"editor.defaultFormatter": "vscode.typescript-language-features",
		"editor.suggestSelection": "recentlyUsed",
		"editor.suggest.showKeywords": false,
		"editor.codeActionsOnSave": {
			"source.fixAll.eslint": "explicit"
		}
	},
	"[typescript]": {
		"editor.defaultFormatter": "vscode.typescript-language-features",
		"editor.suggestSelection": "recentlyUsed",
		"editor.suggest.showKeywords": false
	},
	"files.exclude": {
		"USE_GITIGNORE": true
	},
	"files.associations": {
		"*.md": "mdx"
	},
	"files.defaultLanguage": "{activeEditorLanguage}",
	"javascript.validate.enable": true,
	"search.exclude": {
		"**/node_modules": true,
		"**/bower_components": true,
		"**/coverage": true,
		"**/dist": true,
		"**/build": true,
		"**/.build": true,
		"**/.gh-pages": true
	},
	/* eslint config */
	"eslint.run": "onSave",
	"eslint.enable": true,
	"eslint.lintTask.enable": true,
	"eslint.debug": true,
	"eslint.validate": [
		"javascript",
		"javascriptreact",
		"typescript",
		"typescriptreact"
	],
	"eslint.options": {
		"overrideConfig": {
			"env": {
				"browser": true,
				"jest/globals": true,
				"es6": true
			},
			"parserOptions": {
				"ecmaVersion": 2019,
				"sourceType": "module",
				"ecmaFeatures": {
					"jsx": true
				}
			},
			"rules": {
				"no-debugger": "off"
			}
		}
	},
	"eslint.codeAction.showDocumentation": {
		"enable": true
	},
	"jest.autoRun": "off",
	"jest.debugMode": true,
	"jest.showCoverageOnLoad": true,
	"explorer.openEditors.visible": 0,
	"debug.javascript.codelens.npmScripts": "never",
	"grunt.autoDetect": "off",
	"npm.runSilent": true,
	"gulp.autoDetect": "off",
	"extensions.ignoreRecommendations": true,
	"spellright.language": ["en"],
	"spellright.documentTypes": ["markdown", "plaintext", "mdx"],
	"spellright.parserByClass": {
		"mdx": {
			"parser": "markdown"
		}
	},
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"[jsonc]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"npm.packageManager": "npm",
	"prettier.useEditorConfig": false,
	"html.format.indentInnerHtml": true,
	"html.format.indentHandlebars": true,
	"terminal.integrated.fontSize": 12,
	"terminal.integrated.lineHeight": 1.25,
	"[html]": {
		"editor.defaultFormatter": "vscode.html-language-features"
	},
	"vim.vimrc.path": "$HOME/.vimrc",
	"vim.useCtrlKeys": false,
	"vim.statusBarColors.insert": "#fff",
	"vim.statusBarColors.normal": "#fff",
	"vim.statusBarColors.visual": "#fff",
	"vim.statusBarColors.visualblock": "#fff",
	"vim.statusBarColors.visualline": "#fff",
	"vim.cursorStylePerMode.insert": "line",
	"vim.cursorStylePerMode.normal": "block",
	"vim.cursorStylePerMode.replace": "underline",
	"vim.cursorStylePerMode.visual": "block",
	"vim.statusBarColorControl": true,
	"workbench.editorAssociations": {
		"*.ipynb": "jupyter-notebook"
	},
	"prettier.useTabs": true,
	"workbench.colorTheme": "GitHub Light Default",
	"workbench.preferredDarkColorTheme": "GitHub Light Default",
	"workbench.preferredLightColorTheme": "GitHub Light Default",
	"security.workspace.trust.untrustedFiles": "open",
	"terminal.integrated.allowChords": false,
	"terminal.integrated.tabs.enabled": false,
	"terminal.integrated.fontFamily": "monospace",
	"terminal.integrated.cursorBlinking": true,
	"terminal.integrated.defaultLocation": "editor",
	"json.schemas": [],
	/* sync settings */
	"settingsSync.ignoredExtensions": [
		"angular.ng-template",
		"johnpapa.angular2",
		"formulahendry.auto-rename-tag",
		"mgmcdermott.vscode-language-babel",
		"aaron-bond.better-comments",
		"bycedric.vscode-expo",
		"orta.vscode-jest",
		"syler.sass-indented"
	],
	/* sonarlint */
	"sonarlint.rules": {
		"typescript:S6325": {
			"level": "off"
		},
		"typescript:S1301": {
			"level": "off"
		},
		"typescript:S4138": {
			"level": "off"
		},
		"typescript:S3923": {
			"level": "off"
		},
		"typescript:S107": {
			"level": "off"
		},
		"Web:BoldAndItalicTagsCheck": {
			"level": "off"
		}
	},
	"sonarlint.pathToNodeExecutable": "/Users/streamhub/.nvm/versions/node/v16.13.2/bin/node",
	"workbench.colorCustomizations": {
		"statusBar.background": "#fff",
		"statusBar.noFolderBackground": "#fff",
		"statusBar.debuggingBackground": "#fff"
	},
	"[sass]": {
		"editor.defaultFormatter": "syler.sass-indented"
        },
		"breadcrumbs.enabled": false,
		"editor.linkedEditing": true,
		"github.copilot.enable": {
			"*": true,
			"plaintext": false,
			"markdown": false,
			"scminput": false,
			"yaml": false,
			"python": true,
			"javascript": true,
			"typescript": true,
			"json": false
		},
		"git.openRepositoryInParentFolders": "never",
		"[python]": {
			"editor.formatOnType": true
		},
		"eslint.format.enable": true,
		"gitlens.advanced.messages": {
			"suppressLineUncommittedWarning": true
		},
        "react-native-tools.showUserTips": false,
		"terminal.integrated.env.osx": {},
				"terminal.integrated.env.windows": {},
		"terminal.integrated.enableMultiLinePasteWarning": false,
		"cSpell.userWords": [
			"rawdata"
		],
		"workbench.iconTheme": "file-icons",
		"workbench.preferredHighContrastColorTheme": "GitHub Light Default",
		"workbench.preferredHighContrastLightColorTheme": "GitHub Light Default",
		"workbench.activityBar.location": "hidden",
		"explorer.confirmPasteNative": false,
		"workbench.layoutControl.enabled": false,
		"chat.commandCenter.enabled": false,
		"workbench.navigationControl.enabled": false,
		"window.commandCenter": false,
		"biome.rename": true,
		"redhat.telemetry.enabled": true
	// livestream
	/*
	"window.zoomLevel": 0,
	"editor.fontSize": 22,
	"terminal.integrated.fontSize": 20,
	"workbench.statusBar.visible": false,
	"editor.cursorBlinking": "solid",
	"explorer.decorations.colors": false,
	"explorer.decorations.badges": false,
	"editor.tokenColorCustomizations": {
		"textMateRules": []
	}
	/**/
	// SCREENSHARE
	/*
	"editor.fontSize": 20,
	"terminal.integrated.fontSize": 15,
	"scm.diffDecorations": "none",
	"editor.lineNumbers": "off",
	"workbench.editor.showTabs": false,
	"workbench.statusBar.visible": false,
	"editor.cursorBlinking": "solid",
	"window.zoomLevel": -1,
	"breadcrumbs.enabled": false,
	"editor.parameterHints.enabled": false,
	"editor.suggestOnTriggerCharacters": false,
	"explorer.decorations.colors": false,
	"explorer.decorations.badges": false
	/**/
	// build react apps
	/*
	"editor.fontSize": 20,
	"terminal.integrated.fontSize": 15,
	"scm.diffDecorations": "none",
	"workbench.statusBar.visible": false,
	"editor.cursorBlinking": "solid",
	"window.zoomLevel": -1,
	"editor.parameterHints.enabled": false,
	"editor.suggestOnTriggerCharacters": false,
	"explorer.decorations.colors": false,
	"explorer.decorations.badges": false
	/**/
	// workshop
	/*
	"editor.fontSize": 22,
	"terminal.integrated.fontSize": 20,
	"scm.diffDecorations": "none",
	"workbench.statusBar.visible": false,
	"editor.cursorBlinking": "solid",
	"window.zoomLevel": 1,
	"workbench.colorTheme": "Night Owl Light",
	"explorer.decorations.colors": false,
	"explorer.decorations.badges": false,
	/**/
	// Talk
	/*
	"editor.fontSize": 22,
	"terminal.integrated.fontSize": 20,
	"scm.diffDecorations": "none",
	"editor.lineNumbers": "off",
	"workbench.statusBar.visible": false,
	"editor.cursorBlinking": "solid",
	"window.zoomLevel": 1,
	"workbench.colorTheme": "Night Owl Light",
	"breadcrumbs.filePath": "off",
	"breadcrumbs.symbolPath": "off",
	"editor.parameterHints.enabled": false,
	"editor.quickSuggestions": false,
	"editor.suggestOnTriggerCharacters": false,
	"explorer.decorations.colors": false,
	"explorer.decorations.badges": false,
	/**/
}
