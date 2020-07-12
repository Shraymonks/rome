# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > errors > adjacent-tags`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "input.jsx"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["jsx"]
	loc: Object {
		filename: "input.jsx"
		end: Object {
			column: 38
			index: 38
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Adjacent JSX elements must be wrapped in an enclosing tag. Did you want a JSX fragment \\<>...\\</>?"}
			}
			location: Object {
				filename: "input.jsx"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 22
					index: 22
					line: 1
				}
				start: Object {
					column: 22
					index: 22
					line: 1
				}
			}
		}
	]
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "input.jsx"
				end: Object {
					column: 38
					index: 38
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "input.jsx"
					end: Object {
						column: 38
						index: 38
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "input.jsx"
								identifierName: "x"
								end: Object {
									column: 5
									index: 5
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.jsx"
							end: Object {
								column: 38
								index: 38
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
						init: JSBinaryExpression {
							operator: "<"
							loc: Object {
								filename: "input.jsx"
								end: Object {
									column: 38
									index: 38
									line: 1
								}
								start: Object {
									column: 8
									index: 8
									line: 1
								}
							}
							left: JSBinaryExpression {
								operator: ">"
								loc: Object {
									filename: "input.jsx"
									end: Object {
										column: 30
										index: 30
										line: 1
									}
									start: Object {
										column: 8
										index: 8
										line: 1
									}
								}
								right: JSReferenceIdentifier {
									name: "two"
									loc: Object {
										filename: "input.jsx"
										identifierName: "two"
										end: Object {
											column: 30
											index: 30
											line: 1
										}
										start: Object {
											column: 27
											index: 27
											line: 1
										}
									}
								}
								left: JSBinaryExpression {
									operator: "<"
									loc: Object {
										filename: "input.jsx"
										end: Object {
											column: 26
											index: 26
											line: 1
										}
										start: Object {
											column: 8
											index: 8
											line: 1
										}
									}
									right: JSReferenceIdentifier {
										name: "div"
										loc: Object {
											filename: "input.jsx"
											identifierName: "div"
											end: Object {
												column: 26
												index: 26
												line: 1
											}
											start: Object {
												column: 23
												index: 23
												line: 1
											}
										}
									}
									left: JSXElement {
										name: JSXIdentifier {
											name: "div"
											loc: Object {
												filename: "input.jsx"
												end: Object {
													column: 12
													index: 12
													line: 1
												}
												start: Object {
													column: 9
													index: 9
													line: 1
												}
											}
										}
										attributes: Array []
										selfClosing: false
										typeArguments: undefined
										loc: Object {
											filename: "input.jsx"
											end: Object {
												column: 22
												index: 22
												line: 1
											}
											start: Object {
												column: 8
												index: 8
												line: 1
											}
										}
										children: Array [
											JSXText {
												value: "one"
												loc: Object {
													filename: "input.jsx"
													end: Object {
														column: 16
														index: 16
														line: 1
													}
													start: Object {
														column: 13
														index: 13
														line: 1
													}
												}
											}
										]
									}
								}
							}
							right: JSRegExpLiteral {
								global: false
								insensitive: false
								multiline: false
								noDotNewline: false
								sticky: false
								unicode: false
								loc: Object {
									filename: "input.jsx"
									end: Object {
										column: 38
										index: 38
										line: 1
									}
									start: Object {
										column: 31
										index: 31
										line: 1
									}
								}
								expression: JSRegExpSubExpression {
									loc: Object {
										filename: "input.jsx"
										end: Object {
											column: 37
											index: 37
											line: 1
										}
										start: Object {
											column: 32
											index: 32
											line: 1
										}
									}
									body: Array [
										JSRegExpCharacter {
											value: "d"
											loc: Object {
												filename: "input.jsx"
												end: Object {
													column: 33
													index: 33
													line: 1
												}
												start: Object {
													column: 32
													index: 32
													line: 1
												}
											}
										}
										JSRegExpCharacter {
											value: "i"
											loc: Object {
												filename: "input.jsx"
												end: Object {
													column: 34
													index: 34
													line: 1
												}
												start: Object {
													column: 33
													index: 33
													line: 1
												}
											}
										}
										JSRegExpCharacter {
											value: "v"
											loc: Object {
												filename: "input.jsx"
												end: Object {
													column: 35
													index: 35
													line: 1
												}
												start: Object {
													column: 34
													index: 34
													line: 1
												}
											}
										}
										JSRegExpCharacter {
											value: ">"
											loc: Object {
												filename: "input.jsx"
												end: Object {
													column: 36
													index: 36
													line: 1
												}
												start: Object {
													column: 35
													index: 35
													line: 1
												}
											}
										}
										JSRegExpCharacter {
											value: ";"
											loc: Object {
												filename: "input.jsx"
												end: Object {
													column: 37
													index: 37
													line: 1
												}
												start: Object {
													column: 36
													index: 36
													line: 1
												}
											}
										}
									]
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

 input.jsx:1:22 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Adjacent JSX elements must be wrapped in an enclosing tag. Did you want a JSX fragment
    <>...</>?

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```