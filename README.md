# .sass-lint.yml

files:
  include: '**/*.scss'
options:
  formatter: stylish
  merge-default-rules: false
rules:
  border-zero:
    - 1
    - convention: zero
  brace-style:
    - 1
    - allow-single-line: true
  class-name-format: 0
  clean-import-paths:
    - 1
    - filename-extension: false
      leading-underscore: false
  empty-line-between-blocks:
    - 1
    - ignore-single-line-rulesets: true
  extends-before-declarations: 0
  extends-before-mixins: 0
  final-newline:
    - 1
    - include: true
  force-attribute-nesting: 1
  force-element-nesting: 0
  force-pseudo-nesting: 0
  hex-length:
    - 1
    - style: short
  hex-notation:
    - 1
    - style: lowercase
  id-name-format: 0
  indentation:
    - 1
    - size: 2
  leading-zero:
    - 1
    - include: true
  mixins-before-declarations: 0
  nesting-depth:
    - 1
    - max-depth: 6
  no-color-keywords: 1
  no-color-literals: 0
  no-css-comments: 0
  no-duplicate-properties: 1
  no-empty-rulesets: 1
  no-extends: 0
  no-ids: 0
  no-important: 0
  no-invalid-hex: 1
  no-mergeable-selectors: 1
  no-misspelled-properties:
    - 1
    - extra-properties: []
  no-qualifying-elements:
    - 1
    - allow-element-with-attribute: false
      allow-element-with-class: false
      allow-element-with-id: false
  no-trailing-zero: 0
  no-url-protocols: 1
  no-vendor-prefixes:
    - 1
    - additional-identifiers: []
      excluded-identifiers: []
  placeholder-in-extend: 1
  placeholder-name-format: 0
  property-sort-order:
    - 1
    - ignore-custom-properties: false
      order: recess
  quotes:
    - 1
    - style: single
  shorthand-values:
    - 0
    - allowed-shorthands:
        - 1
        - 2
        - 3
        - 4
  single-line-per-selector: 1
  space-after-comma:
    - 1
    - include: true
  space-before-brace:
    - 1
    - include: true
  space-before-colon: 1
  space-between-parens:
    - 1
    - include: false
  trailing-semicolon: 1
  url-quotes: 1
  variable-for-property:
    - 0
    - properties: []
  zero-unit: 1
