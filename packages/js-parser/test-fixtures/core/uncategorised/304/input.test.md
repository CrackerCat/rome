# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 304`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/304/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/304/input.js"
		end: Object {
			column: 8
			index: 32
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSWhileStatement {
			loc: Object {
				filename: "core/uncategorised/304/input.js"
				end: Object {
					column: 8
					index: 32
					line: 2
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			test: JSBooleanLiteral {
				value: true
				loc: Object {
					filename: "core/uncategorised/304/input.js"
					end: Object {
						column: 11
						index: 11
						line: 1
					}
					start: Object {
						column: 7
						index: 7
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "core/uncategorised/304/input.js"
					end: Object {
						column: 8
						index: 32
						line: 2
					}
					start: Object {
						column: 13
						index: 13
						line: 1
					}
				}
				body: Array [
					JSContinueStatement {
						label: undefined
						loc: Object {
							filename: "core/uncategorised/304/input.js"
							end: Object {
								column: 23
								index: 23
								line: 1
							}
							start: Object {
								column: 15
								index: 15
								line: 1
							}
						}
					}
					JSExpressionStatement {
						loc: Object {
							filename: "core/uncategorised/304/input.js"
							end: Object {
								column: 6
								index: 30
								line: 2
							}
							start: Object {
								column: 0
								index: 24
								line: 2
							}
						}
						expression: JSReferenceIdentifier {
							name: "there"
							loc: Object {
								filename: "core/uncategorised/304/input.js"
								identifierName: "there"
								end: Object {
									column: 5
									index: 29
									line: 2
								}
								start: Object {
									column: 0
									index: 24
									line: 2
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```