# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 228`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/uncategorised/228/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/228/input.js"
		end: Object {
			column: 49
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			location: Object {
				filename: "es2015/uncategorised/228/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 38
					line: 1
				}
				start: Object {
					column: 37
					line: 1
				}
			}
			description: Object {
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Argument <emphasis>"}
						"t"
						RAW_MARKUP {value: "</emphasis> name clash in strict mode"}
					]
				}
				advice: Array [
					log {
						category: "info"
						text: MARKUP {parts: Array [RAW_MARKUP {value: "Defined already here"}]}
					}
					frame {
						location: Object {
							filename: "es2015/uncategorised/228/input.js"
							identifierName: "t"
							end: Object {
								column: 38
								line: 1
							}
							start: Object {
								column: 37
								line: 1
							}
						}
					}
				]
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "a"
				loc: Object {
					filename: "es2015/uncategorised/228/input.js"
					identifierName: "a"
					end: Object {
						column: 10
						line: 1
					}
					start: Object {
						column: 9
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/uncategorised/228/input.js"
				end: Object {
					column: 49
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/uncategorised/228/input.js"
					end: Object {
						column: 12
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				loc: Object {
					filename: "es2015/uncategorised/228/input.js"
					end: Object {
						column: 49
						line: 1
					}
					start: Object {
						column: 13
						line: 1
					}
				}
				directives: Array [
					JSDirective {
						value: "use strict"
						loc: Object {
							filename: "es2015/uncategorised/228/input.js"
							end: Object {
								column: 28
								line: 1
							}
							start: Object {
								column: 15
								line: 1
							}
						}
					}
				]
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "es2015/uncategorised/228/input.js"
							end: Object {
								column: 47
								line: 1
							}
							start: Object {
								column: 29
								line: 1
							}
						}
						expression: JSObjectExpression {
							loc: Object {
								filename: "es2015/uncategorised/228/input.js"
								end: Object {
									column: 45
									line: 1
								}
								start: Object {
									column: 30
									line: 1
								}
							}
							properties: Array [
								JSObjectMethod {
									kind: "method"
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "b"
											loc: Object {
												filename: "es2015/uncategorised/228/input.js"
												identifierName: "b"
												end: Object {
													column: 33
													line: 1
												}
												start: Object {
													column: 32
													line: 1
												}
											}
										}
										loc: Object {
											filename: "es2015/uncategorised/228/input.js"
											end: Object {
												column: 33
												line: 1
											}
											start: Object {
												column: 32
												line: 1
											}
										}
									}
									loc: Object {
										filename: "es2015/uncategorised/228/input.js"
										end: Object {
											column: 43
											line: 1
										}
										start: Object {
											column: 32
											line: 1
										}
									}
									body: JSBlockStatement {
										body: Array []
										directives: Array []
										loc: Object {
											filename: "es2015/uncategorised/228/input.js"
											end: Object {
												column: 43
												line: 1
											}
											start: Object {
												column: 40
												line: 1
											}
										}
									}
									head: JSFunctionHead {
										async: false
										generator: false
										hasHoistedVars: false
										rest: undefined
										returnType: undefined
										thisType: undefined
										typeParameters: undefined
										loc: Object {
											filename: "es2015/uncategorised/228/input.js"
											end: Object {
												column: 39
												line: 1
											}
											start: Object {
												column: 33
												line: 1
											}
										}
										params: Array [
											JSBindingIdentifier {
												name: "t"
												loc: Object {
													filename: "es2015/uncategorised/228/input.js"
													identifierName: "t"
													end: Object {
														column: 35
														line: 1
													}
													start: Object {
														column: 34
														line: 1
													}
												}
												meta: JSPatternMeta {
													optional: undefined
													typeAnnotation: undefined
													loc: Object {
														filename: "es2015/uncategorised/228/input.js"
														end: Object {
															column: 35
															line: 1
														}
														start: Object {
															column: 34
															line: 1
														}
													}
												}
											}
											JSBindingIdentifier {
												name: "t"
												loc: Object {
													filename: "es2015/uncategorised/228/input.js"
													identifierName: "t"
													end: Object {
														column: 38
														line: 1
													}
													start: Object {
														column: 37
														line: 1
													}
												}
												meta: JSPatternMeta {
													optional: undefined
													typeAnnotation: undefined
													loc: Object {
														filename: "es2015/uncategorised/228/input.js"
														end: Object {
															column: 38
															line: 1
														}
														start: Object {
															column: 37
															line: 1
														}
													}
												}
											}
										]
									}
								}
							]
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

 es2015/uncategorised/228/input.js:1:37 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Argument t name clash in strict mode

  ℹ Defined already here

    function a() { "use strict"; ({ b(t, t) { } }); }
                                         ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
