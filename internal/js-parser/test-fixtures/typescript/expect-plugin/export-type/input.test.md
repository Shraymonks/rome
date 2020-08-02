# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > expect-plugin > export-type`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/expect-plugin/export-type/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "typescript/expect-plugin/export-type/input.js"
		end: Object {
			column: 0
			index: 26
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExportLocalDeclaration {
			exportKind: "type"
			specifiers: undefined
			loc: Object {
				filename: "typescript/expect-plugin/export-type/input.js"
				end: Object {
					column: 25
					index: 25
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: TSTypeAlias {
				id: JSBindingIdentifier {
					name: "Foo"
					loc: Object {
						filename: "typescript/expect-plugin/export-type/input.js"
						identifierName: "Foo"
						end: Object {
							column: 15
							index: 15
							line: 1
						}
						start: Object {
							column: 12
							index: 12
							line: 1
						}
					}
				}
				typeParameters: undefined
				loc: Object {
					filename: "typescript/expect-plugin/export-type/input.js"
					end: Object {
						column: 25
						index: 25
						line: 1
					}
					start: Object {
						column: 7
						index: 7
						line: 1
					}
				}
				right: TSNumberKeywordTypeAnnotation {
					loc: Object {
						filename: "typescript/expect-plugin/export-type/input.js"
						end: Object {
							column: 24
							index: 24
							line: 1
						}
						start: Object {
							column: 18
							index: 18
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```